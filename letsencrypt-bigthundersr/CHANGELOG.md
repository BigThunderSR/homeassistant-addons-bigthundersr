# Changelog

## 5.4.7

- Fix root certificate format when using custom ACME server from upstream

## 5.4.6

- Fix custom ACME server for DNS challenge (fixes #1769) from upstream

## 5.4.5

- Update certbot-dns-directadmin to 1.0.15 from upstream

## 5.4.4

- Update certbot to 3.3.0 from upstream
- Update acme to 3.3.0 from upstream
- Update cryptography to 44.0.2 from upstream

## 5.4.3

- Update certbot-dns-websupport to 3.0.0 from upstream
- Re-enable certbot-dns-websupport from upstream

## 5.4.2

- Update certbot-dns-dynu to 0.0.8 from upstream
- Update certbot-dns-gandi to 1.6.1
  (incl. switch back to a renamed updated original version) from upstream

## 5.4.1

- Fix TransIP global_key handling from upstream

## 5.4.0

- Add additional arguments to certbot (dry-run, test-cert, verbose) from upstream
- Switch gandi-dns to a maintained version (certbot-plugin-gandi-modern) from upstream
- Refactor scripts from upstream
- Improve documentation from upstream
- Refactor configuration and align with documentation from upstream

## 5.3.3

- Re-enabled certbot-dns-mijn-host from upstream

## 5.3.2

- Update certbot to 3.2.0 from upstream
- Update acme to 3.2.0 from upstream
- Update certbot-dns-inwx to 3.0.2 from upstream

## 5.3.1

- Add Eurodns DNS support from upstream

## 5.3.0

- Disabled certbot-dns-mijn-host (Breaking change) from upstream
  - issue: [mijnhost/certbot-dns-mijn-host#8](https://github.com/mijnhost/certbot-dns-mijn-host/issues/8)
- Disabled certbot-dns-websupport (Breaking change) from upstream
  - issue: [johnybx/certbot-dns-websupport#1](https://github.com/johnybx/certbot-dns-websupport/issues/1)
- Update to Python 3.13
- Update to Alpine 3.21
- Update certbot to 3.1.0
- Update acme to 3.1.0
- Update cryptography to 44.0.1
- Update certbot-dns-azure to 2.6.1
- Update certbot-dns-directadmin to 10.0.13
- Update certbot-dns-duckdns to 1.5
- certbot-dns-dynu 0.0.6 (already existing in this fork)
- Update certbot-dns-inwx to 3.0.1
- Update certbot-dns-ionos to 2024.11.9
- Update certbot-dns-norisnetwork to 0.3.0
- Update certbot-dns-porkbun to 0.9.1
- Update certbot-dns-netcup to 1.4.4
- Update certbot-dns-njalla to 2.0.2
- Update the remaining dns challenges with DNS_PROVIDER placeholder from upstream

## 5.2.12

- Add rfc2136_sign_query parameter to config.yaml from upstream

## 5.2.11

- Use a newer, maintained Hurricane Electric plugin from upstream

## 5.2.10

- Add transip global_key parameter to config.yaml from upstream

## 5.2.9

- Update certbot-dns-infomaniak to 0.2.3 from upstream

## 5.2.8

- Add transip global_key parameter to support authentication without IP whitelist requirements from upstream

## 5.2.7

- Add mijn.host DNS support from upstream
- Update certbot-dns-dynu-dev to v0.0.6

## 5.2.6

- Fix dns-loopia username error from upstream

## 5.2.5

- Update certbot-dns-directadmin to 1.0.12 from upstream

## 5.2.4

- Add Loopia DNS support from upstream

## 5.2.3

- Fix typo in previous update from upstream which prevented the add-on from running

## 5.2.2

- Add IONOS DNS support from upstream

## 5.2.1

- Revert Cryptography to 42.0.8 to avoid deprecation warnings from upstream

## 5.2.0

- Update Certbot/ACME to 2.11.0 & update all plugins to their latest version from upstream
- Update to Python 3.12 from upstream
- Update to Alpine 3.20 from upstream

## 5.1.4

- Drop Google Domains support (the new operator Squarespace has no ACME support) from upstream

## 5.1.3

- Add godaddy.com DNS support from upstream

## 5.1.2

- Fixes subdomain DNS challenge not working for Simply.com from upstream

## 5.1.1

- Add Simply.com DNS support from upstream

## 5.1.0

- Add external account binding support from upstream

## 5.0.27

- Add Plesk DNS challenge support from upstream

## 5.0.26

- Add noris network DNS challenge support from upstream

## 5.0.25

- Add DigitalOcean propagation-seconds support from upstream

## 5.0.24

- Fix Gandi DNS support using API key from upstream

## 5.0.23

- Fix missing domain configuration for joker.com DNS challenge from upstream

## 5.0.22

- Add joker.com DNS challenge support from upstream

## 5.0.21

- Fix configuration to make list of provider parsable again from upstream

## 5.0.20

- Fix file-structure.sh script from upstream
- Fix domainoffensive plug-in installation from upstream

## 5.0.19

- Add domainoffensive challenge support from upstream

## 5.0.18

- Fix Gandi DNS support using API key from upstream
- Add Gandi DNS support using token authentication from upstream

## 5.0.17

- Add WebSupport challenge support from upstream

## 5.0.16

- Add Dynu challenge support from upstream - This was already existing in this fork

## 5.0.15

- Add easyDNS challenge support from upstream

## 5.0.14

- Update docs for key_type setting from upstream

## 5.0.13

- By default, choose key type based on existing certificates at startup from upstream
- Allow ECDSA curve selection from upstream

## 5.0.12

- Fix ClouDNS challenge support from upstream
- Add HE DNS challenge support from upstream v5.0.11

## 5.0.10

- Add ClouDNS DNS challenge support from upstream

## 5.0.9

- Add option to specify Private Key type from upstream

## 5.0.8

- Add Dreamhost DNS challenge support from upstream

## 5.0.7

- Add Porkbun DNS challenge support from upstream

## 5.0.6

- Add Infomaniak DNS challenge support from upstream

## 5.0.5

- Fix DirectAdmin DNS challenge support from upstream

## 5.0.4

- Add Namecheap DNS challenge support from upstream

## 5.0.3

- Add deSEC DNS challenge support from upstream

## 5.0.2

- Fix DirectAdmin DNS challenge support from upstream

## 5.0.1

- Add DuckDNS DNS challenge support from upstream
- Fix GANDI configuration file options from upstream
- Use new non-namesspaced configuration for all DNS providers from upstream

## 5.0.0

- Upgrade to Certbot 2.7.4 & all DNS authenticator plug-ins to match upstream addon update
- Drop CloudXNS (removed in Certbot upstream) to match upstream addon update
- Add GANDI DNS propagation delay setting to match upstream addon update
- Temporarily use certbot-dns-dynu-dev until upstream fix is made in certbot-dns-dynu to remove hard dependency on 'dns-lexicon>=3.11.7'

## 4.12.12

- Updated base image to Python 3.11 on Alpine 3.18

## 4.12.11

- Changed slug name to use "_" instead of "-" due to breaking change in HA Core 2023.9
- Updated base image to Alpine 3.18

## 4.12.10

- Add Dynu DNS challenge support

## 4.12.9

- Add Google Domains DNS challenge support

## 4.12.8

- Add INWX DNS challenge support

## 4.12.7

- Add Hetzner DNS challenge support

## 4.12.6

- Add Azure DNS challenge support

## 4.12.5

- Fix another syntax error in runs script for rfc2136

## 4.12.4

- Fix syntax error in runs script for rfc2136
- Fix finish script for S6 V3

## 4.12.3

- Fix the DNS propagation delay setting for the rfc2136 provider

## 4.12.2

- Use HA wheels when possible during build

## 4.12.1

- Set preferred chain to "ISRG Root X1"

## 4.12.0

- Update Certbot 1.21.0 & Plugins
- Update to Python 3.9
- Update to Alpine 3.14

## 4.11.0

- Add support for Njalla DNS

## 4.10.0

- Add support for custom ACME server and Certificate Authority

## 4.9.0

- Add support for DirectAdmin DNS

## 4.8.0

- Add support for Gandi DNS

## 4.7.1

- Adjust init settings

## 4.7.0

- Fix issue with DNS challenge
- Convert to s6-overlay

## 4.6.0

- Streamline propagation seconds
- Add propagation seconds to CloudFlare / option selection

## 4.5.0

- Update certbot to 1.2.0
- Update image to Alpine 3.11
- Support CloudFlare API Token

## 4.4.0

- Added support for nectup dns

## 4.3.0

- Added support for google dns
- Fixed AWS support
- Updated documentation
- Update certbot to 1.0.0

## 4.2.0

- Bugfix default empty dns setting

## 4.1.0

- Pin image to Alpine3.10
- Bugfix default options with empty dns

## 4.0.0

- Added support for dns challenges
