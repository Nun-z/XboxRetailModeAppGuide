This method (used first by tunip3) allows apps to be installed to an Xbox in retail mode that would normally only be available in dev mode.  Note that there are better options available if you just want to run RetroArch on your Xbox.  This is intended for those that want to create their own storefront containing RetroArch or those that want to self-host.

### Guide to Installing Apps to an Xbox in Retail Mode

### Table of Contents
* [Introduction](#introduction)

* [Requirements](#requirements)

* [Step 1: Sign up for a developer account](#step-1-sign-up-for-a-developer-account)

* [Step 2: Create an application in Microsoft Partner Center](#step-2-create-an-application-in-microsoft-partner-center)
    
    * [Step 2.1: Enter availability settings](#step-21-enter-availability-settings)
    
    * [Step 2.2: Enter properties settings](#step-22-enter-properties-settings)
    
    * [Step 2.3: Enter age ratings settings](#step-23-enter-age-ratings-settings)
    
    * [Step 2.4: Enter store listing settings](#step-24-enter-store-listing-settings)

* [Step 3: Prepare the application's package for upload](#step-3-prepare-the-applications-package-for-upload)

    * [Step 3.1: You have the source code](#Step-31-you-have-the-source-code)
    
    * [Step 3.2: You don't have the source code or don't want to compile the app](#Step-32-you-dont-have-the-source-code-or-dont-want-to-compile-the-app)

* [Step 4: Upload the application to the Microsoft Store](#step-4-upload-the-application-to-the-microsoft-store)

* [Step 5: Create a website that links to the app or copy over the link](#step-5-create-a-website-that-links-to-the-app-or-copy-over-the-link)

* [Step 6: Install the app to your Xbox in retail mode](#step-6-install-the-app-to-your-xbox-in-retail-mode)

### Introduction

This guide will describe the process of uploading a Universal Windows Platform (UWP) app to the Microsoft Store for use on an Xbox in retail mode.  Apps that you install to your Xbox in this way will not need to be sideloaded in dev mode.  This is useful because it allows you to use emulators without restarting the Xbox, and you can bypass the 2 GB file size limit imposed on dev mode.

There are some things you should be aware of if you choose to follow this guide.  Installing emulation apps to an Xbox in retail mode is against Microsoft’s terms of service.  Breaking these terms of service often leads to being banned from uploading further apps to the Microsoft Store, requiring you to then purchase dev mode for a new Microsoft account.  Note that this is only a risk for the person uploading apps to the Microsoft Store, not for those using the apps.  For each account, you will need to pay around $2 in order to start uploading apps to the store.

Once you've signed up for a Microsoft dev account, this tutorial will have you use a tool known as the Scarlet Sideloader to quickly upload your apps to the Microsoft Store.  If you encounter a technical error when using the sideloader, please report it to the tool's GitHub page here: https://github.com/Dantes-Dungeon/Scarlet-Sideloader/issues.

### Requirements

To follow this guide, you will need $2 and a computer running Windows.

### Step 1: Sign up for a developer account

If you have a Microsoft account that you log into on your Xbox and $2, you have everything you need to complete this step.  If you have a developer account already, skip this step.

**1.**  Go to this URL (https://developer.microsoft.com/en-us/store/register/) and click on the “sign up” button.

**2.**  If you are not already signed in with your Xbox’s Microsoft account, sign in using the prompt displayed.

**3.**  You will then be presented with a dropdown menu for selecting your region.  Choose Argentina.

**4.**  Once you select a region, the account type options will be displayed.  Select “individual” account type option.
![AccountType](https://i.imgur.com/3M84Ydq.png "Sign up for an individual account")

**5.**  Scroll down to the “publisher display name (company name)” textbox and enter your desired publisher name.  This can be anything as long as it hasn’t already been claimed by someone else.

**6.**  Scroll down and fill in the “contact info” textboxes.  Then, press the “next” button at the bottom of the page.

**7.**  On the next page, click on “add a new payment method.”

**8.**  Enter your payment information, go to the Review page, and complete the purchase.  You now have a Microsoft developer account.
