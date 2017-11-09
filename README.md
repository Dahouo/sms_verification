<a href="https://www.twilio.com">
  <img src="https://static0.twilio.com/marketing/bundles/marketing/img/logos/wordmark-red.svg" alt="Twilio" width="250" />
</a>

# Twilio Account Security Quickstart - Two-Factor Authentication and Phone Verification

A simple Java, Spring and AngularJS implementation of a website that uses Twilio Account Security services to protect all assets within a folder. Additionally, it shows a Phone Verification implementation.

It uses four channels for delivery, SMS, Voice, Soft Tokens, and Push Notifications. You should have the [Authy App](https://authy.com/download/) installed to try Soft Token and Push Notification support.

#### Two-Factor Authentication Demo
- URL path "/protected" is protected with both user session and Twilio Two-Factor Authentication
- One Time Passwords (SMS and Voice)
- SoftTokens
- Push Notifications (via polling)

#### Phone Verification
- Phone Verification
- SMS or Voice Call

### Setup
- Clone this repo
- Run `gradle build`
- Register for a [Twilio Account](https://www.twilio.com/).
- Setup an Account Security app via the [Twilio Console](https://twilio.com/console).
- Grab an Application API key from the Dashboard and paste it in `.env.example`
- Save the `.env.example` file as `.env`
- Load the configuration with `source .env`
- Run `gradle appRun` from the cloned repo to run the app

### License
- MIT
