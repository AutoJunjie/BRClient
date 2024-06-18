<div align="center">
<img src="./app/icons/bedrock_32.svg" alt="icon"/>

<h1 align="center">BRClient Cognito</h1>

English / [简体中文](./README_CN.md)

It is a Bedrock client forked from https://github.com/Yidadaa/ChatGPT-Next-Web/

And it was simplified to support AWS Bedrock only.


</div>

## Installation:

Use Cloudformation to deploy

Cloudformation template:
https://raw.githubusercontent.com/AutoJunjie/BRClient/main/aws/cloudformation/BRClientWebDeploy.json


#### For Developer:


As the project is still in rapid itelating, we would like to suggest developers to build it their own version following the following steps:

1. git clone current project: `git clone https://github.com/DamonDeng/BRClient.git`
2. install yarn on your desktop
3. go to the project folder
4. run `yarn install` to install all the dependences of the project
5. run `yarn app:dev` to start a desktop app in developer mode.    or:   run `yarn dev` to start a local server and then access the app with browser.
6. Optional, if you want to run it as an app, run `yarn app:build` to build it, and the find the target file (we believe you can, :-)

if you want to build a new zip

1. yarn export
2. zip -r out.zip out/ -x "*/"
3. upload .zip to s3 or github, then use it with your cloudformation

## Donation
If you like this project, buy original author yidadaa a Coffee
[Buy Original Author a Coffee](https://www.buymeacoffee.com/yidadaa)

## LICENSE

[MIT](https://opensource.org/license/mit/)
