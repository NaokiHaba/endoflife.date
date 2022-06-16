---
title: WordPress
category: server-app
releasePolicyLink: https://codex.wordpress.org/Supported_Versions
sortReleasesBy: "releaseCycle"
releases:
-   releaseCycle: "6.0"
    eol: false
    releaseDate: 2022-05-24
    latest: "6.0.0"
    link: https://wordpress.org/support/wordpress-version/version-6-0/
    latestReleaseDate: 2022-05-24
-   releaseCycle: "5.9"
    eol: 2022-05-24
    releaseDate: 2022-01-25
    latestReleaseDate: 2022-04-05
    latest: "5.9.3"
    link: https://wordpress.org/support/wordpress-version/version-5-9-3/
auto:
-   git: https://github.com/WordPress/wordpress-develop.git
permalink: /wordpress
activeSupportColumn: false
releaseColumn: true
releaseDateColumn: true
discontinuedColumn: false
versionCommand: wp core version
icon:
  simpleicons: wordpress

---

> [WordPress](https://wordpress.org/) is a free and open-source content management system written in PHP.

Only the latest major release is supported. Security patches are backported when possible, but this is not guaranteed.