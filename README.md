# OWASP CRS - Cospend Rule Exclusions Plugin
If you use the [OWASP Coreruleset](https://github.com/coreruleset/coreruleset) together with Nextcloud, there already is a [rule-exclusions-plugin](https://github.com/coreruleset/nextcloud-rule-exclusions-plugin) to prevent false positives triggered by features that Nextcloud normally uses. However, this plugin does not support the Cospend app. So here we are.

# Installation
Just put the `.conf` files in the plugins folder of your coreruleset installation (e.g. on Debian: `/etc/modsecurity/crs/plugins/`.

# Contribution
Please create an issue if you encounter false positives, find bugs or have other suggestions.
