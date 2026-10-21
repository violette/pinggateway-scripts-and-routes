# PingGateway route examples!

This repository contains short and simple routes ready to deploy for [**PingGateway**](https://product-downloads.pingidentity.com/browse/ig/featured)

An install of [**PingAM**](https://product-downloads.pingidentity.com/) is required to perform authentication/authorization examples.

## What does PingGateway do? What can I do with PingGateway?

- [AWS: Deploy PingGateway with Amazon Web Services](https://github.com/openig-contrib/script-util-for-openig/tree/master/AWS-config-examples) _(scripts and utilities)_
- [Docker Secrets and PingGateway Secrets](https://github.com/openig-contrib/script-util-for-openig/tree/master/docker)

- [OAuth2: NASCAR page - Authenticate through PingAM, Google, MSN or LinkedIn](https://github.com/openig-contrib/script-util-for-openig/tree/master/OAuth2/OPENIG-712)
- [OAuth2: Discovery](https://github.com/openig-contrib/script-util-for-openig/tree/master/OAuth2/OPENIG-712)
- [OAuth2/OpenID: Authenticate through PingAM, check the token and get access to your protected application!](https://github.com/openig-contrib/script-util-for-openig/tree/master/OAuth2/OPENIG-933)
- [OAuth2/OpenID: Authenticate using private_key_jwt](https://github.com/openig-contrib/script-util-for-openig/tree/master/OAuth2/private_key_jwt)

- [Policy Enforcement Filter(PEF): how to retrieve attributes in a policy decision](https://github.com/openig-contrib/script-util-for-openig/tree/master/PEP/OPENIG-824)
- [Policy Enforcement Filter(PEF): how to set environment and retrieve advices in a policy decision](https://github.com/openig-contrib/script-util-for-openig/tree/master/PEP/OPENIG-836)
- [Policy Enforcement Filter(PEF): configure PingAM as a PDP](https://github.com/openig-contrib/script-util-for-openig/tree/master/PEP/Setting_Up_OpenAM_As_A_PDP.groovy) _(groovy script only)_

- [UMA 1.0](https://github.com/openig-contrib/script-util-for-openig/tree/master/UMA) _(groovy script only)_
- [UMA 2.0](https://github.com/openig-contrib/script-util-for-openig/tree/master/UMA) _(groovy script only)_

- [JwtBuilderFilter(6.1): Passdown PingAM user information from PingGateway into a header](https://github.com/openig-contrib/script-util-for-openig/tree/master/Others/JwtBuilderFilter)
- [Create a simple redirect route](https://github.com/openig-contrib/script-util-for-openig/tree/master/Others/Redirect)
- [User Profile: Retrieve user information from PingAM](https://github.com/openig-contrib/script-util-for-openig/tree/master/Others/UserProfile)

- [STS: transform OAuth2/OpenID to SAML assertions!](https://github.com/openig-contrib/script-util-for-openig/tree/master/STS/TokenTransformationFilter)

- BOT detection - See examples :
  - [AI agent detection groovy](https://github.com/openig-contrib/script-util-for-openig/tree/master/ai-agent-detection-groovy.json)
  - [AI agent detection](https://github.com/openig-contrib/script-util-for-openig/tree/master/ai-agent-detection.json)
  - [bot detection](https://github.com/openig-contrib/script-util-for-openig/tree/master/bot-detection.json) 
- 
> **Note: that PingGateway is now launched in PRODUCTION MODE by default**

>
> Don't forget to change it to DEVELOPMENT to access Studio or for editing routes.
>
> **Tip:** You can run PingGateway with `java -jar start.jar -Dig.run.mode=development`

## How to configure PingAM??? I just want to try...

**Don't panic!**

There are Groovy scripts provided for each example to help you to configure your PingAM quickly.
Each folder contains Groovy scripts which are configuring PingAM via REST: configure OAuth2Provider, Policies, Identities and so on...

## Official links
- [Get PingGateway](https://www.pingidentity.com/en/product/pinggateway.html)
- [Get PingAM](https://docs.pingidentity.com/pingam/release-notes/preface.html)
- [Ping Identity official website](https://www.pingidentity.com/en/product/pinggateway.html)

## Disclaimer

This project is not supported by Ping Identity.

----------
