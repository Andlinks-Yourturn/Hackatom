# Yourturn: Token management platform for charity purpose based on Comsmos-sdk & Tendermint

This project is designed for Cosmos Hackatom #2.
# Overview

The management of charity fund is a crucial problem in our society. We face many ethic problems.
The donors sometimes question the management of money, meanwhile people have difficulty finding help. 

In this example, we show you an example of using blockchain technologies for efficiently managing tokens( created with Basecoin). In our platform, we let the school provide reliable information about certain students.On the other hand, donors are allowed to set criteria of their own token-distribution projects. At Yourturn, students can browse through projects and apply. Smart contracts will automatically transfer tokens to the student’s account. All the criteria files are stored in IPFS and any modification or application actions is recored with the help of ABCi. This ABCi is Merkel Tree based where the logs are stored.![alt text](https://github.com/Andlinks-Yourturn/Hackatom/blob/master/architecture.jpeg)

# What Yourturn  Can Do
*Set up campaigns for raising tokens for charity purpose<br/>
*Anyone eligible could apply for fund<br/>
*Automated allocated fund to designated people<br/>
*Audit the flow of fund<br/>
# User Story
Donor set up projects to help hard-working students.<br/>

The schools provide reliable data about the students. <br/>

Student apply certain projects at Yourturn. The underlying ABCi will make the decision. <br/>Afterwards, the tokens will be transferred to the student.

# Project Architecture
The architecture is shown in following picture.


# Deployment
1. Environment

    OS: ubuntu / Mac OS 

    Docker: we provide an API wrapped in a containers.

2. Deploy

    