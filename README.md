# Two-Factor Authentication Working Group

Working group dedicated to two-factor authentication in Nextcloud. This includes the core logic within Nextcloud itself, the modular two-factor providers and any aspects of connected clients and applications.

# Scope and purpose

The two-factor auth working group is dedicated to improving and maintaining all two-factor aspects inside the Nextcloud ecosystem.

## Leads

* [Anna Larch](https://github.com/miaulalala)
* [Christoph Wurst](https://github.com/ChristophWurst)
* [Joas Schilling](https://github.com/nickvergessen)

## Components

The code and information is spread across multiple repositories. The following list shows where the main bits and pieces can be found.

* [Nextcloud Public OCP API](https://github.com/nextcloud/server/tree/master/lib/public/Authentication/TwoFactorAuth)
* [Nextcloud Server logic](https://github.com/nextcloud/server/tree/master/lib/private/Authentication/TwoFactorAuth)
* [Backup Codes Provider](https://github.com/nextcloud/server/tree/master/apps/twofactor_backupcodes)
* [Nextcloud Provider](https://github.com/nextcloud/twofactor_nextcloud_notification)
* [TOTP Provider](https://github.com/nextcloud/twofactor_totp)
* [U2F Provider](https://github.com/nextcloud/twofactor_u2f)
