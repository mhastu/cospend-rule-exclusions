# OWASP CRS - Rule Exclusions Plugins for 3rd party apps
If you use the [OWASP Coreruleset](https://github.com/coreruleset/coreruleset) together with Nextcloud, there already is a [rule-exclusions-plugin](https://github.com/coreruleset/nextcloud-rule-exclusions-plugin) to prevent false positives triggered by features that Nextcloud normally uses. However, this plugin does not support all apps. So here we are.

# Installation
Just put the `.conf` files of the apps you use in the plugins folder of your coreruleset installation (e.g. on Debian: `/etc/modsecurity/crs/plugins/`.

# Supported Apps
- Cospend
- Memories

# Contribution
Please create an issue if you encounter false positives, find bugs or have other suggestions.
