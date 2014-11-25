Meetin.gs APS Standard deployment guide
====================

Audience
--------
This document is intended for people who need to deploy the Meetin.gs APS package to a provisioning system (like Parallels Panel).

Provisioned application editions
--------------------------------
With proper API credentials the APS package allows provisioning a "paid" status for Meetin.gs users.

With the default credentials, the package provisions "freemium" users in the global Meetin.gs cloud.

Getting API credentials
-----------------------
To request your development or production API credentials, please contact antti@meetin.gs after negotiating the appropriate financial agreements with Meetin.gs Ltd.

APS compliance
--------------
This package has been tested to work with the http://dev.apsstandard.org/ lin-mn sandbox provisioned on Feb. 21, 2014.

How to deploy the package
-------------------------
Follow the [deployment example document](https://docs.google.com/document/d/11TiE47GPzk_IeaBS3hViSU_buQ_7GiG-MN85-qnQuKI/pub) published in Google Documents.

How to verify provisioning
--------------------------
1. Follow the application link in the parallels panel.
2. On the first login, verify the account single sign in capabilities trough the email which was set up for the user.
3. Open Settings > Account (from the top right corner profile picture dropdown).
4. Verify the text on the page indicates the user has a paid account.
