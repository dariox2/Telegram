## Telegrog - Telegram API compatible messenger for Android

[Telegrog] () is a fork of [Telegram](https://telegram.org), a messaging app with a focus on speed and security. It’s superfast, simple and free.

The official repo of source code is at: [DrKLO/Telegram
](https://github.com/DrKLO/Telegram/network).

##Creating your Telegram compatible Application

There are several things we require from **all developers** for the moment.

1. [**Obtain your own api_id**](https://core.telegram.org/api/obtaining_api_id) for your application.
2. Please **do not** use the name Telegram for your app — or make sure your users understand that it is unofficial.
3. Kindly **do not** use our the Telegram standard logo (white paper plane in a blue circle) as your app's logo.
3. Please study the [**security guidelines**](https://core.telegram.org/mtproto/security_guidelines) and take good care of your users' data and privacy.
4. Please remember to publish **your** code too in order to comply with the licences.

### API, Protocol documentation

Telegram API manuals: https://core.telegram.org/api

MTproto protocol manuals: https://core.telegram.org/mtproto

### Usage

**Beware of using the dev branch and uploading it to any markets, in many cases it not will work as expected**.

First of all, take a look at **src/main/java/org/telegram/messenger/BuildVars.java** and fill it with correct values.
Import the root folder into your IDE (tested on Android Studio), then run project.

### Localization

All translations were moved to https://www.transifex.com/projects/p/telegram/. Please use it.
