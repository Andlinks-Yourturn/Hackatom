# Yourturn: Token management platform for charity purpose based on Comsmos-sdk & Tendermint

This project is designed for Cosmos Hackatom #2.
# Overview

The management of charity fund is a crucial problem in our society. We face many ethic problems.
The donors sometimes question the management of money, meanwhile people have difficulty finding help. 

In this example, we show you an example of using blockchain technologies for efficiently managing tokens( created with Basecoin). In our platform, we let the school provide reliable information about certain students.On the other hand, donors are allowed to set criteria of their own token-distribution projects. At Yourturn, students can browse through projects and apply. Smart contracts will automatically transfer tokens to the student’s account. All the criteria files are stored in IPFS and any modification or application actions is recored with the help of ABCi. This ABCi is Merkel Tree based where the logs are stored.

# What Yourturn  Can Do
*Set up campaigns for raising tokens for charity purpose<br/>
*Anyone eligible could apply for fund<br/>
*Automated allocated fund to designated people<br/>
*Audit the flow of fund<br/>
# User Story
![alt text](https://github.com/Andlinks-Yourturn/Hackatom/blob/master/workflow.png)
Donor set up projects to help hard-working students.<br/>

The schools provide reliable data about the students. <br/>

Student apply certain projects at Yourturn. The underlying ABCi will make the decision. <br/>Afterwards, the tokens will be transferred to the student.

# Project Architecture
The architecture is shown in following picture.
![alt text](https://github.com/Andlinks-Yourturn/Hackatom/blob/master/architecture.jpeg)

Yourturn is compose of three parts.

There is a Web & Java Web server. They call the function through wrapped API.

# Deployment
1. Environment

    OS: ubuntu / Mac OS 

    Docker: we provide an API wrapped in a containers.

2. Deploy

2.1 Install IPFS

install IPFS in your machine

https://ipfs.io/docs/install/


2.2 Deploy Web Application

The instruction for deploying java projects can be found at 

    https://github.com/Andlinks-Yourturn/Java/tree/master

and 

    https://github.com/Andlinks-Yourturn/Web


2.3 Deploy Abci & Cosmos Service

Make sure you have Tendermint installed & initialized in your machine.

Start Tendermint `tendermint node`

Install ABCi

run `go get https://github.com/Andlinks-Yourturn/abci/cmd/...`

Let’s start a ABCi application. `dummy`

Install Basecoin 

run `go get https://github.com/Andlinks-Yourturn/BasecoinService/cmd/...`

Let’s start a Basecoin application. `basecoin start`




    
    
# Demo

you can find our demo video in the following link:

 <a href="http://www.youtube.com/watch?feature=player_embedded&v=oqAMhmyZgYQ
 " target="_blank"><img src="http://img.youtube.com/vi/oqAMhmyZgYQ/0.jpg" 
 alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>




