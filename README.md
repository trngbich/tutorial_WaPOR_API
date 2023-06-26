# WaPOR API examples

![](http://www.fao.org/typo3temp/pics/93f49ce381.jpg)

Author: Bich Tran (b.tran@un-ihe.org)

Description: Ipython notebooks that contain code snippets on how to use FAO's WaPOR database API in Python

<html>
  <head>
    <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>
  </head>
</html>

## Python env

requests

pandas

matplotlib

rasterio

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


