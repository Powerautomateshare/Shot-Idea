# Privacy policy — shot idea

_Last updated: 21 November 2026 (version 1.1)_

shot idea is a free Windows app for screenshots, screen recording, annotation, text recognition and live presenting. It is made by Sorasit Moungon (published as PowerIT). This page explains what the app does with your information.

**In short: shot idea has no account, no ads, no tracking and no analytics. Your screenshots, videos and notes stay on your computer. Only the optional features listed below send data over the internet, and only when you use them.**

## What stays on your computer

- **Screenshots, videos and notes.** They are saved only where you choose (or copied to your clipboard). shot idea does not upload them anywhere, unless you connect your own OneDrive or Google Drive (below).
- **Camera and microphone.** They are used only while you record a video with the camera bubble or voice turned on. Windows shows you when they are in use, and you can turn access off at any time in Windows Settings > Privacy & security. Nothing is streamed or sent anywhere.
- **PDF and printing.** Save as PDF creates the file on your computer. Print sends the picture only to the printer you choose in the Windows print window; if that is a network or cloud printer, its own service handles the print.
- **Fonts.** The font list shows the fonts installed on your computer. It is read on your computer and never sent anywhere.
- **Text recognition (OCR). Reading printed text from a screenshot uses the text recognition built into Windows, on your computer.
- **Settings.** Your choices are saved in `%LocalAppData%\ShotIdea\settings.json`. If something goes wrong, a short error log (`ShotIdea-error.log`) is written in the same place. It describes the error only and is never sent anywhere.
- **Keys you enter.** If you add your own Microsoft Translator or Azure key, it is stored in the Windows Credential Locker, encrypted for your Windows account.

## Features that go online (only when you use them)

1. **Translation.** When you open the translation side of extracted text, that text is sent to a translation service:
   - [MyMemory](https://mymemory.translated.net/doc/privacy.php) (the default, free service), or
   - [Microsoft Translator](https://privacy.microsoft.com/privacystatement), if you add your own key.

   Only the text being translated is sent, not the picture.

2. **Reading handwriting.** This feature is off unless you add your own Azure AI Vision key. When you then ask shot idea to read handwriting, that picture is sent to Microsoft Azure to be read. Microsoft's [privacy statement](https://privacy.microsoft.com/privacystatement) applies.

3. **OneDrive or Google Drive (version 1.1 and later).** This is off unless you choose Setting > Cloud, pick **one** of them and sign in. You can connect only one at a time. While connected:
   - screenshots and videos you save are uploaded to your own cloud, and
   - the start bar's Open button lists and downloads the latest pictures from that folder.

   shot idea never sees your password, never shares your files with anyone, and only reads or writes them for the actions above. Choose Disconnect to remove the sign-in from your PC; your files in the cloud stay where they are.

   - **OneDrive:** sign-in happens in the Windows sign-in window (or your web browser). Windows gives the app a sign-in token, stored encrypted for your Windows account in `%LocalAppData%\ShotIdea`. Files go to `OneDrive\Pictures\shot idea` and `OneDrive\Videos\shot idea`. shot idea talks only to Microsoft Graph (graph.microsoft.com) and asks only to read and write your files and see your account name. Microsoft's [privacy statement](https://privacy.microsoft.com/privacystatement) applies.
   - **Google Drive:** sign-in happens in your web browser on Google's page. shot idea asks only for the `drive.file` permission, so it can see and change **only the files it saved itself** (a `shot idea` folder), not the rest of your Drive, plus your e-mail address to show which account is connected. The sign-in token is stored in the Windows Credential Locker, encrypted for your Windows account. shot idea talks only to Google (accounts.google.com, oauth2.googleapis.com, www.googleapis.com). shot idea's use and transfer of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements. Google's [privacy policy](https://policies.google.com/privacy) applies.

4. **Edit in Clipchamp.** This button opens the video in the Clipchamp app on your computer, or opens Clipchamp's website (app.clipchamp.com) in your browser and shows the video in File Explorer so you can drag it in. shot idea itself sends nothing; a video goes to Clipchamp only if you add it there, under Microsoft's privacy statement.

Those services handle the data under their own privacy policies. shot idea does not send them anything else about you.

## Windows settings

If you choose to use the Print Screen key for shot idea, the app asks you first. With your OK, it switches off one Windows keyboard option ("Use the Print screen key to open screen capture") for your account. If you later choose another key, shot idea switches that option back on. You can also change it yourself in Windows Settings > Accessibility > Keyboard.

## Purchases

shot idea is free. If optional purchases or donations are offered in the future, they will go through the Microsoft Store, and Microsoft handles all payment details. shot idea never sees your card or payment information.

## Feedback

"Send feedback" in the app opens a new issue on GitHub in your browser, with the app version and Windows version filled in. Nothing is sent until you post it yourself, and GitHub issues are public, so please don't include personal information.

## Children

shot idea does not knowingly collect any personal information from anyone, including children.

## Changes

If this policy changes, the new version will be posted on this page with a new date.

## Contact

Questions? Please open an issue at [github.com/Powerautomateshare/Shot-Idea/issues](https://github.com/Powerautomateshare/Shot-Idea/issues).
