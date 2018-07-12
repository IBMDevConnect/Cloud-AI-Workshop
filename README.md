# IBM Cloud & AI technical workshop

## Agenda

09:45 - 10:00 : IBM Developer Way (Opening Talk) - Raghavendra Deshpande

10:00 - 11:00 : Introduction to IBM Cloud & Watson (Tech Talk) - Rajesh Gudikoti

11:00 - 11:15 : Coffee / Tea break

11:15 - 12:45 : How to deploy your app on IBM Cloud using browser and CLI ? (Hands-on Workshop) - Sudharshan Govindan

12:45 - 13:45 : Lunch break

13:45 - 15:15 : Analyze an image and send a status alert (Hands-on Workshop) - Krishna Chaitanya

15:15 - 15:30 : Coffee / Tea break

15:30 - 16:30 : Serverless - what it is and what it is not ? (Tech Talk) - Sudharshan Govindan


## Pre-Requisites

1. Sign up for IBM Cloud Account - [https://ibm.biz/BdZfzb](https://ibm.biz/BdZfzb)  

2. Install IBM Cloud Command Line Interface (CLI) bundle - https://console.bluemix.net/docs/home/tools

    (OR)

   Install stand-alone IBM Cloud CLI - https://console.bluemix.net/docs/cli/reference/bluemix_cli/download_cli.html#install_use

   Verify the CLI install

   `ibmcloud dev help`

3. Sign up for a free IBM Coder account - [https://ibmcoders.influitive.com/](https://ibmcoders.influitive.com/)

4. Signup for a free GitHub account, if not already done  - [https://github.com/](https://github.com/)

5. Install a Git command line or GUI client - [https://git-scm.com/downloads/](https://git-scm.com/downloads/)

6. Download & install Node.JS - [https://nodejs.org/en/download/](https://nodejs.org/en/download/)

7. Install CURL - [https://curl.haxx.se/download.html](https://curl.haxx.se/download.html)


## Configure your environment

From your Terminal / Powershell, type the below commands:

1. To point to US-South region

  `ibmcloud api https://api.ng.bluemix.net`
  
  To point to UK region
  
  `ibmcloud api https://api.eu-gb.bluemix.net`

2. Login to IBM Cloud

  `ibmcloud login`

3. **Note:**
  
  Cloud Foundry Organisation = your IBM Cloud login / email id  
  Cloud Foundry Space = dev

4. Connect to your Cloud Foundry Organisation and Space

  `ibmcloud target -o <value> -s <value>`
  
    (OR)
  
  `ibmcloud target --cf`


## Hands-on Workshop 1

* Follow the steps given in 

https://console.bluemix.net/docs/runtimes/nodejs/getting-started.html#getting-started-with-node-js-on-bluemix

* Github repo - https://github.com/IBM-Cloud/get-started-node


## Hands-on Workshop 2

* Follow the steps given in https://github.com/IBMDevConnect/IotImageAnalysis


## Useful Links

* [Call for Code](https://developer.ibm.com/code/2018/05/24/global-importance-answering-call-code/)
* [IBM Code](https://developer.ibm.com/code/)
* [IBM Code Patterns](https://developer.ibm.com/code/patterns/?cm_sp=Developer-_-Top-Nav-_-Journeys)
* [CognitiveClass.AI](https://cognitiveclass.ai/)
* [Model Asset Exchange](https://developer.ibm.com/code/exchanges/models/)
* [Fabric for Deep Learning](https://github.com/IBM/FfDL)
* [IBM DevConnect Meetup Group](https://www.meetup.com/IBMDevConnect-Bangalore/)
* [IBM DevConnect Slack Channel](https://slackrequest.mybluemix.net)
* [IBM Cloud Solution Tutorials](http://ibm.biz/solution-tutorials)
* [Bot Asset Exchange](https://developer.ibm.com/code/exchanges/bots/)
