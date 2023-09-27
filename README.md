# BigThunderSR Home Assistant Add-on Repository

[![Home Assistant Add-on](https://img.shields.io/badge/home_assistant-add--on-blue.svg?logo=homeassistant&logoColor=white)](https://github.com/BigThunderSR/homeassistant-addons-bigthundersr)
![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports i386 Architecture][i386-shield]
<!-- [![CodeQL](https://github.com/BigThunderSR/homeassistant-addons-bigthundersr/actions/workflows/github-code-scanning/codeql/badge.svg)](https://github.com/BigThunderSR/homeassistant-addons-bigthundersr/actions/workflows/github-code-scanning/codeql) -->
[![Lint](https://github.com/BigThunderSR/homeassistant-addons-bigthundersr/actions/workflows/lint.yaml/badge.svg)](https://github.com/BigThunderSR/homeassistant-addons-bigthundersr/actions/workflows/lint.yaml)
[![Builder](https://github.com/BigThunderSR/homeassistant-addons-bigthundersr/actions/workflows/builder.yaml/badge.svg)](https://github.com/BigThunderSR/homeassistant-addons-bigthundersr/actions/workflows/builder.yaml)
<!-- [![Notarize Assets with CAS](https://github.com/BigThunderSR/homeassistant-addons-bigthundersr/actions/workflows/cas_notarize.yml/badge.svg)](https://github.com/BigThunderSR/homeassistant-addons-bigthundersr/actions/workflows/cas_notarize.yml)
[![Authenticate Assets with CAS](https://github.com/BigThunderSR/homeassistant-addons-bigthundersr/actions/workflows/cas_authenticate.yml/badge.svg)](https://github.com/BigThunderSR/homeassistant-addons-bigthundersr/actions/workflows/cas_authenticate.yml)
[![Notarize and Authenticate Docker Image BOM with CAS](https://github.com/BigThunderSR/homeassistant-addons-bigthundersr/actions/workflows/cas-docker-notarize-authenticate.yml/badge.svg)](https://github.com/BigThunderSR/homeassistant-addons-bigthundersr/actions/workflows/cas-docker-notarize-authenticate.yml) -->

Home Assistant Add-ons created and/or modified by [BigThunderSR](https://github.com/BigThunderSR).

<!--Add-on documentation: <https://developers.home-assistant.io/docs/add-ons> -->

[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https://github.com/BigThunderSR/homeassistant-addons-bigthundersr)

## Add-ons

This repository contains the following add-ons

- [Letsencrypt-BigThunderSR](https://github.com/BigThunderSR/homeassistant-addons-bigthundersr/tree/main/letsencrypt-bigthundersr)

## My other Home Assistant Add-ons

[https://github.com/BigThunderSR/homeassistant-addons-onstar2mqtt](https://github.com/BigThunderSR/homeassistant-addons-onstar2mqtt)

<!-- _Example add-on to use as a blueprint for new add-ons._ -->

<!--

Notes to developers after forking or using the github template feature:
- While developing comment out the 'image' key from 'example/config.yaml' to make the supervisor build the addon
  - Remember to put this back when pushing up your changes.
- When you merge to the 'main' branch of your repository a new build will be triggered.
  - Make sure you adjust the 'version' key in 'example/config.yaml' when you do that.
  - Make sure you update 'example/CHANGELOG.md' when you do that.
  - The first time this runs you might need to adjust the image configuration on github container registry to make it public
- Adjust the 'image' key in 'example/config.yaml' so it points to your username instead of 'home-assistant'.
  - This is where the build images will be published to.
- Rename the example directory.
  - The 'slug' key in 'example/config.yaml' should match the directory name.
- Adjust all keys/url's that points to 'home-assistant' to now point to your user/fork.
- Share your repository on the forums https://community.home-assistant.io/c/projects/9
- Do awesome stuff!
 -->

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
