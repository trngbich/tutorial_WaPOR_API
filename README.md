# WaPOR API examples

Author: Bich Tran (b.tran@un-ihe.org)

Description: Ipython notebooks that contain code snippets on how to use FAO's WaPOR database API in Python

## Python env

requests=2.21.0

pandas=0.24.2

matplotlib=3.0.3

## About WaPOR

**Link**: https://wapor.apps.fao.org/

FAO's web portal to monitor Water Productivity through Open-access of Remotely sensed derived data (WaPOR). 
This portal covers Africa and the Near East, with remotely sensed data, to monitor, in near real time, agricultural water and land productivity as well carbon dioxide uptake by vegetation.

For information about the programme, please visit: http://www.fao.org/in-action/remote-sensing-for-water-productivity/en/

## WaPOR API documentation

The ReST API documentation for accessing WaPOR database can be found at: https://io.apps.fao.org/gismgr/api/v1/swagger-ui.html

## WAPOR API Token

API Token is used to authorize access to WaPOR API. To get an API Token, please follow these steps:

### Step 1: Sign up/Log in an account on WaPOR portal

Go to https://wapor.apps.fao.org/, click **Sign in**

![](/img/1_signin.png)

If you don't have an account, create a new account, then log in.

### Step 2: Create API

After logging in, go to **My WaPOR** > **My Profile** 

![](/img/2_mywapor.png)

![](/img/3_myprofile.png)

Under **API Token**, click **Generate API Token**

![](/img/4_generatetoken.png)

The API Token is user's personal key, thus, should be stored and kept private. In case of losing API Token, revoke the old token and create a new one.

![](/img/5_revoketoken.png)


