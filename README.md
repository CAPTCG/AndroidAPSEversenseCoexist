This is AndroidAPS 3.4.2.1 with new code. The new code adds Eversense CGM directly and allows "SMB Always". The user selects Eversence in the configuration builder. The Eversense preferences menu has an entry for adding your Eversense Username & Password. This code also removes the annoying yellow triangle & red version # from the home screen. This code allows for a 10hour DIA in all user types & allows profile switching up to 150%. This code also has no version check & never expires. Look in the "AndroidAPS Documents" for additional help.

## Eversense E3/365

### Important Information

The Eversense CGM is experimental as of now.

**Wait till initialization phase is completed**
During the initialization phase after insertion of a new sensor, the glucose reading might be incorrect. Before using automated insulin delivery, be sure to complete the initialization phase using the official Eversense app.

**Transmitter is read by only one app: Eversense app or the AAPS app**
The transmitter is not able to support multiple connections to the same device due to the security protocol.

From Official Eversense app to AAPS app:
* In the official app, go to Connections and tap on the Transmitter and select Disconnect
* In the AAPS app, choose Eversense, login and then select the Transmitter
  * If this is the first time you pair this transmitter with this phone / app, you might need to put the Transmitter into pairing mode before it will show up

From AAPS app to Official Eversense app:
* In the AAPS app, go to Settings, CGM and delete CGM
* In the official app, go to Connections and tap on the Transmitter and select Connect

### Add Eversense CGM

With Eversense added to AAPS you get direct connection to your transmitter for glucose readings and can configure alert notifications. Because the transmitter can only connect to one app at a time, you must first disconnect from the Eversense app before you can connect to the AAPS app.

The AAPS app does not have glucose notification features, at this time. You can enable the on-transmitter notification within the AAPS app so the transmitter will vibrate to alert you of an issue.

The pairing process of both transmitters are simple:
* For the Eversense E3, select the correct transmitter name (see SN at the bottom of your transmitter) and accept the Android pairing prompt (if shown) and wait till the pairing has completed
* For the Eversense 365, you are required to have an internet connection and Eversense account during pairing. This is needed to fetch the security keys for your transmitter. After logging in, select the correct transmitter name (see SN at the bottom of your transmitter) and accept the Android pairing prompt (if shown) and wait till the pairing has completed
  * If this is the first time you pair this transmitter with this phone / app, you might need to put the Transmitter into pairing mode before it will show up

# AAPS
* Check the wiki: https://wiki.aaps.app
* Everyone who's been looping with AAPS needs to fill out the form after 3 days of looping https://docs.google.com/forms/d/14KcMjlINPMJHVt28MDRupa4sz4DDIooI4SrW0P3HSN8/viewform?c=0&w=1

[![Support Server](https://img.shields.io/discord/629952586895851530.svg?label=Discord&logo=Discord&colorB=7289da&style=for-the-badge)](https://discord.gg/4fQUWHZ4Mw)
[![CircleCI](https://circleci.com/gh/nightscout/AndroidAPS/tree/master.svg?style=svg)](https://circleci.com/gh/nightscout/AndroidAPS/tree/master)
[![Crowdin](https://d322cqt584bo4o.cloudfront.net/androidaps/localized.svg)](https://translations.aaps.app/project/androidaps)
[![Documentation Status](https://readthedocs.org/projects/androidaps/badge/?version=latest)](https://wiki.aaps.app/en/latest/?badge=latest)
[![codecov](https://codecov.io/gh/nightscout/AndroidAPS/branch/master/graph/badge.svg?token=EmklfIV6bH)](https://codecov.io/gh/nightscout/AndroidAPS)

DEV:
[![CircleCI](https://circleci.com/gh/nightscout/AndroidAPS/tree/dev.svg?style=svg)](https://circleci.com/gh/nightscout/AndroidAPS/tree/dev)
[![codecov](https://codecov.io/gh/nightscout/AndroidAPS/branch/dev/graph/badge.svg?token=EmklfIV6bH)](https://codecov.io/gh/nightscout/AndroidAPS/tree/dev)

<img src="https://cdn.iconscout.com/icon/free/png-256/bitcoin-384-920569.png" srcset="https://cdn.iconscout.com/icon/free/png-512/bitcoin-384-920569.png 2x" alt="Bitcoin Icon" width="100">
3KawK8aQe48478s6fxJ8Ms6VTWkwjgr9f2
