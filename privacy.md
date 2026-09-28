# Privacy policy

**Next Bus NI** · last updated 28 September 2026

Next Bus NI is a free Android widget that shows bus times in Northern Ireland. It's made by one
person, Stephen McCaffrey, who is the data controller for anything described here. This policy
covers the Android app and this website.

**In short:** there are no accounts, no ads, no analytics and no tracking. The app talks only to
Translink's Journey Planner, and only to get bus times. Nothing else leaves your phone unless you
choose to send a report yourself.

## What the app sends, and to whom

The app has no server of its own. To show bus times it asks **Translink's Journey Planner**
(`journeyplanner.translink.co.uk`) directly, sending:

- **The stop codes of your widgets' stops**, each time the widgets refresh (about once a minute in
  the commute times you set, every 15 minutes otherwise, and never with the screen off).
- **What you type in the stop search** on the set-up screen.
- **Your location, only when you tap "Near me"**, to list the stops around you. You choose in
  Android's own prompt whether the app gets your precise or approximate location, and you can
  refuse. The location is used for that one search and isn't stored.
- A request for current **service alerts** (the same for everyone).

Each request carries the app's name, version and contact address (for example `NextBusNI/1.1.0
(nextbusni@gmail.com)`), which says nothing about you. Like any website, Translink's servers see
your phone's IP address when it connects. What Translink does with its requests is covered by
Translink's own privacy notice on [translink.co.uk](https://www.translink.co.uk). Next Bus NI is not
affiliated with Translink.

## What stays on your phone

Your widgets' stops and routes, your settings, the last bus times fetched, and (if the app has
crashed) a record of the crash. These are kept only on your phone. They aren't sent anywhere, they
aren't included in Android's backups or device transfers, and they're deleted when you uninstall
the app.

## Reports you choose to send

**Help & feedback** in the app can write a report for you. It's never sent automatically: it opens
in **your own email app** (or you copy it), and you can read and change every word before sending.
A report contains:

- the app's version, your phone's make and model, and its Android version,
- whether the app's setup steps are done,
- your widgets' stop names, stop codes and routes, when the widgets last refreshed and the last
  error,
- the crash record, if you send a report after a crash.

It **never** includes your location or your search history.

If you email a report or a question to [nextbusni@gmail.com](mailto:nextbusni@gmail.com), I get
your email address and whatever you wrote. I use it only to reply and to fix the problem, I never
share it, and I delete it when it's dealt with. Problems are copied into a private to-do list with
your email address removed.

## What the app doesn't do

- No accounts and no sign-in.
- No ads, analytics, crash-reporting services or tracking of any kind.
- No Google Play Services or other third-party code that sends data.
- Nothing is sold or shared with anyone.

## Permissions

| Permission | Why |
|---|---|
| Internet, network state | To ask Translink's Journey Planner for bus times. |
| Alarms and reminders (exact alarms) | To refresh the widget on time. |
| Run at startup | To set the refresh alarms again after the phone restarts. |
| Location (precise or approximate), optional | Only for "Near me". Asked for the first time you tap it. |

## Children

The app isn't aimed at children under 13 and doesn't knowingly collect anything from them.

## This website

This site is hosted on GitHub Pages. GitHub may log visitors' IP addresses for security; see
[GitHub's privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).
The site itself sets no cookies and uses no analytics.

## Your rights

Under UK data protection law you can ask what I hold about you, and ask for it to be corrected or
deleted. Apart from any emails you've sent, I hold nothing. Email
[nextbusni@gmail.com](mailto:nextbusni@gmail.com). You can also complain to the
[Information Commissioner's Office](https://ico.org.uk).

## Changes

If this policy changes, the new version will be posted here with a new date, and the
[changelog](CHANGELOG.md) will mention it.

## Contact

Stephen McCaffrey · [nextbusni@gmail.com](mailto:nextbusni@gmail.com)
