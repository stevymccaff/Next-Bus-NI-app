# Installing Next Bus NI

Next Bus NI isn't on Google Play yet, so for now you install it straight from this page. It takes
about five minutes. It's for **Android phones only** (Android 8 or later); there's no iPhone version.

There are two ways. The first one tells you when there's an update, so it's the one to use if you can.

## Option 1 (easiest): with Obtainium, so you get updates

[Obtainium](https://github.com/ImranR98/Obtainium) is a free app that installs apps from pages like
this one and lets you know when a new version comes out.

1. On your phone, open the
   [Obtainium releases page](https://github.com/ImranR98/Obtainium/releases/latest) and download
   **`app-release.apk`**. Open it and install it (see [the warnings you might see](#warnings-you-might-see)).
2. Open Obtainium and tap **Add app**.
3. In **App source URL**, paste:

   ```
   https://github.com/stevymccaff/Next-Bus-NI-app
   ```

4. Tap **Add**, then **Install**.

When there's a new version, Obtainium shows it; tap **Update**. Your widgets and settings stay as
they are.

## Option 2: download it yourself

1. On your phone, open the
   [latest release](https://github.com/stevymccaff/Next-Bus-NI-app/releases/latest) and tap the
   file ending in **`.apk`** (for example `NextBusNI-1.1.0.apk`) under **Assets**.
2. Open the downloaded file and install it.

To update later, come back here and do the same again. It installs over the top, and your widgets
and settings stay as they are.

## Warnings you might see

These are normal for any app that doesn't come from Google Play.

- **"For your security, your phone isn't allowed to install unknown apps from this source."** Tap
  **Settings**, turn on **Allow from this source**, then go back. It's asked once for your browser
  (or Files app), and once for Obtainium.
- **Google Play Protect: "Unsafe app blocked" or "Send app for a security check?"** Tap **More
  details** → **Install anyway**. Play Protect warns about apps it hasn't seen before. Next Bus NI
  asks for very little: internet, alarms (to refresh on time, including after the phone restarts)
  and, only if you tap Near me, your location.

## Setting it up

1. Open **Next Bus NI**. It shows three numbered steps until they're done:
   1. **Exact alarms → Allow**, so the widget refreshes on time.
   2. **Battery → Open** → App battery usage → **Unrestricted**, so your phone doesn't stop the
      refreshes to save battery.
   3. **Add widget**, then choose your stop and routes.
2. To choose a stop: search for its name, tap **Near me**, or type the stop code from the bus stop
   pole. Tap the stop, then tick the routes you want (or "Any bus from this stand"). Tap **Save**.
3. You can also add a widget the usual way: long-press your home screen → **Widgets** → **Next Bus
   NI**. To change a widget later, long-press it → **Widget settings**, or in the app, **Your
   widgets → Edit**.

**Samsung, Xiaomi, OnePlus, Huawei, Oppo or Vivo phone?** These have extra battery saving that can
stop the widget refreshing. The app links to the page for your phone on
[dontkillmyapp.com](https://dontkillmyapp.com); follow it once.

## Something wrong, or an idea?

In the app, scroll down to **Help & feedback**. Pick **Report a problem**, **Problem with a stop's
times** or **Suggest something**. It fills in the details for you (app version, phone, your widgets'
stops and routes; never your location), and you can read and change it before it's sent by email.
Or just email [nextbusni@gmail.com](mailto:nextbusni@gmail.com).

If times at your stop look wrong, the stop code in the report is what lets it be checked.

## Removing it

Long-press the widget → **Remove**, then uninstall **Next Bus NI** like any other app. Nothing is
kept anywhere else.

## Checking the download (optional)

Every release is signed with the same key. If you use an app like
[AppVerifier](https://github.com/soupslurpr/AppVerifier), the signing certificate's SHA-256
fingerprint is:

```
16:3C:E0:B0:FC:D9:06:54:EA:7C:67:A2:77:53:F4:C4:CC:C5:36:3B:2E:E0:A1:39:6A:86:EA:BA:0A:76:F7:A0
```
