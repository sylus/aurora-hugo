Hugo variant for Aurora
=======================

[![Build Status][travisci-badge]][travisci]

[Hugo][hugo] variant for Aurora

## Example

Please consult our [Digital Academy][aurora-website] site to see how this theme is implemented.

## Requirements

The theme is built using the Aurora theme.

  * [hugo 0.13+][hugo]: `brew install hugo`
  * [node.js][nodejs]: `brew install npm`
  * [yarn][yarn]: `yarn install`

## Manual Steps

Simply follow the commands listed below given you have the appropriate files
(config.yml|toml etc) at the project root.

```sh
    hugo new site `website`
    mkdir themes && cd themes
    git clone https://github.com/sylus/aurora-hugo.git aurora && cd aurora
    bower install
    hugo server --theme=aurora \
                --watch
```

<!-- Links Referenced -->

[yarn]:                 https://yarnpkg.com
[hugo]:                 http://gohugo.io
[nodejs]:               http://nodejs.org
[travisci]:             http://travis-ci.org/sylus/aurora-hugo
[travisci-badge]:       https://api.travis-ci.org/sylus/aurora-hugo.svg?branch=master
[aurora-hugo]:          https://github.com/sylus/aurora-hugo
[aurora-website]:       https://github.com/sylus/digital-academy
