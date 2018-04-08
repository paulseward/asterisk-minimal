# Minimal CNet Asterisk config

No DAHDI, no voicemail, no bells, no whistles.  Just a minimal starting point for asterisk configuration.  Includes SIP and IAX2 support.

The config will attempt to include the following files:
* `local/extensions.conf` Your local dialplan
* `local/sip.conf` Your local SIP trunks/peers/users
* `local/iax.conf` Your local IAX config

We're also using git submodules to pull in a couple of other bits of config which are in their own repositories:
* `asterisk-tim` UK speaking clock from https://github.com/paulseward/asterisk-tim
* `dialcnet` C*Net access macro from https://github.com/paulseward/dialcnet
