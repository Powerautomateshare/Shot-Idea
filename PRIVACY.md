# Privacy policy — shot idea

_Last updated: 17 November 2026_

shot idea is a free Windows app for screenshots, screen recording, annotation, text recognition and live presenting. It is made by Sorasit Moungon (published as PowerIT). This page explains what the app does with your information.

**In short: shot idea has no account, no ads, no tracking and no analytics. Your screenshots, videos and notes stay on your computer. Only two optional features send data over the internet, and only when you use them.**

## What stays on your computer

- **Screenshots, videos and notes.** They are saved only where you choose (or copied to your clipboard). shot idea does not upload them anywhere.
- **Camera and microphone.** They are used only while you record a video with the camera bubble or voice turned on. Windows shows you when they are in use, and you can turn access off at any time in Windows Settings > Privacy & security. Nothing is streamed or sent anywhere.
- **Text recognition (OCR).** Reading printed text from a screenshot uses the text recognition built into Windows, on your computer.
- **Settings.** Your choices are saved in `%LocalAppData%\ShotIdea\settings.json`. If something goes wrong, a short error log (`ShotIdea-error.log`) is written in the same place. It describes the error only and is never sent anywhere.
- **Keys you enter.** If you add your own Microsoft Translator or Azure key, it is stored in the Windows Credential Locker, encrypted for your Windows account.

## Features that go online (only when you use them)

1. **Translation.** When you open the translation side of extracted text, that text is sent to a translation service:
   - [MyMemory](https://mymemory.translated.net/doc/privacy.php) (the default, free service), or
   - [Microsoft Translator](https://privacy.microsoft.com/privacystatement), if you add your own key.

   Only the text being translated is sent, not the picture.

2. **Reading handwriting.** This feature is off unless you add your own Azure AI Vision key. When you then ask shot idea to read handwriting, that picture is sent to Microsoft Azure to be read. Microsoft's [privacy statement](https://privacy.microsoft.com/privacystatement) applies.

Those services handle the data under their own privacy policies. shot idea does not send them anything else about you.

## Windows settings

If you choose to use the Print Screen key for shot idea, the app asks you first. With your OK, it switches off one Windows keyboard option ("Use the Print screen key to open screen capture") for your account. If you later choose another key, shot idea switches that option back on. You can also change it yourself in Windows Settings > Accessibility > Keyboard.

## Purchases

shot idea is free. If optional purchases or donations are offered in the future, they will go through the Microsoft Store, and Microsoft handles all payment details. shot idea never sees your card or payment information.

## Feedback

If you use "Send feedback" in the app, it opens your own email program. What you send, and your email address, are used only to reply to you and improve the app.

## Children

shot idea does not knowingly collect any personal information from anyone, including children.

## Changes

If this policy changes, the new version will be posted on this page with a new date.

## Contact

Questions? Please open an issue at [github.com/Powerautomateshare/Shot-Idea/issues](https://github.com/Powerautomateshare/Shot-Idea/issues).
