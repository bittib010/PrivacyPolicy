# Privacy policy for Matte

Last updated: 21 September 2026

Matte is an app for practising arithmetic and school algebra on squared
paper. It is published by the developer of this repository and is available
on Google Play under the package name `no.matte.matte`.

## The short version

Matte collects nothing, sends nothing and asks for no permissions. It has no
account, no advertising and no analytics, and it works with the device
offline. The same statement is in the app itself, under Settings → Privacy.

## What the app stores

Everything Matte remembers stays on the device, in the app's own private
storage (Android's `SharedPreferences`), and is deleted with the app:

- the settings: language, notation, decimal mark, which methods to use, and
  the limits for each kind of task;
- the last task that was typed and the last method chosen;
- saved focus areas, their chosen method and their practice history;
- what has been written on the scratchpad.

None of it is transmitted anywhere, and none of it is readable by other apps.
Android may include this private storage in a device backup if the device
owner has turned Android's own backup on; that is Android's mechanism, not
the app's, and it is covered by Google's backup terms.

## What the app does not do

- It does not collect or transmit personal information of any kind.
- It does not use the network. The release build asks for no device
  permissions at all — it does not hold the `INTERNET` permission, so it
  cannot reach the internet even if it tried. (Its manifest declares one
  signature-level permission of its own, which Android's support libraries use
  to keep an internal message from leaving the app; it grants access to
  nothing.)
- It shows no advertisements and contains no advertising or analytics
  software development kits.
- It has no accounts, no sign-in and no user-to-user features.
- It makes no purchases.

## The one thing that leaves the app

The settings hold a button for rating Matte. It opens Google Play on Matte's
own listing — the Play app if the device has one, a browser otherwise. That is
a different app with its own privacy policy, and Matte sends nothing along
with the hand-over: no identifier, no usage, nothing. It is the only outward
link in the app, and nothing happens unless the button is pressed.

## Children

Matte is made for school pupils, and children may use it. Because the app
collects no data and has no ads, there is nothing about a child's use of it to
collect, share or profile.

## Deleting your data

Uninstalling the app, or clearing its storage from Android's app settings,
removes everything listed above. There is nothing held anywhere else to
delete.

## Contact

Questions about this policy can be sent to the address on the app's Google
Play listing.
