---
title: "Mobile on Windows"
sidebar: katalon_studio_docs_sidebar
permalink: katalon-studio/docs/mobile-on-windows.html
redirect_from:
    - "/display/KD/Mobile+on+Windows/"
    - "/display/KD/Mobile%20on%20Windows/"
    - "/x/jwbR/"
    - "/katalon-studio/docs/mobile-on-windows/"
    - "/katalon-studio/tutorials/setting_mobile_application_automation.html"
description:
---
Katalon Studio Supported Environment on Windows
-----------------------------------------------

> You can only test an **iOS** application using **macOS**. If you wish to set up your macOS environment for Katalon Studio, please refer to [this guide](/x/9AXR).

* Appium: 1.12.1 onwards.
* Android: 6.x onwards (official releases).

Installing Appium
-----------------------

To install Appium, follow [these steps](http://appium.io/docs/en/about-appium/getting-started/#installing-appium).

> Attention
>
> Make sure you install Node.js into a location where you have full **Read** and **Write** permissions.

Setting Up Your Devices
-----------------------

Turn on the phone's developer mode (go to **Settings** > **Developer options**).

Connect your Android phone to your computer via a USB cable.

Confirm if prompted to accept/trust the device.

In the **Developer Options** on your mobile user interface, enable:
- USB debugging – Debug mode when USB is connected 
- Install via USB – Allow installing apps via USB
- USB debugging (Security Setting) – Allow granting permissions and simulating input via USB debugging 

Install Android SDK: Katalon Studio will detect and ask you to install Android SDK automatically if your current machine doesn't have it. Please allow Katalon Studio to install it in this case.

Verifiying the Setup
--------------------

Open a Mobile Testing Sample Project (which is packaged in your Katalon Studio installation).

Execute a test suite using an Android device: 

![](../../images/katalon-studio/docs/mobile-on-windows/image2017-6-29-143A483A34.png)
Select your device from the **Android Devices** list. Click **OK**. 

![](../../images/katalon-studio/docs/mobile-on-windows/image2018-1-26-183A393A1.png)

If your test suite runs successfully, you will see the results in the test reports as follow:

![](../../images/katalon-studio/docs/mobile-on-windows/image2018-6-15-173A473A28.png)

For more information on how to run a test suite, check out the documentation [here](/pages/viewpage.action?pageId=786668).

Finishing
---------------

Once the setup is successful, follow the following guides to perform mobile testing in Katalon Studio

*   [Record Mobile Utility](/display/KD/Record+Mobile+Utility)
*   [Spy Mobile Utility](/display/KD/Spy+Mobile+Utility)
*   [Execute a Test Case or a Test Suite](/display/KD/Execute+a+Test+Case+or+a+Test+Suite)

Troubleshooting Common Issues
-----------------------------

_**Please refer to [this](/display/KD/Troubleshooting+automated+mobile+testing) troubleshooting tutorial**_
