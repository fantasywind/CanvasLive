# Canvas Live

Live streaming on facebook from node.js canvas

__IMPORTANT! This repo is under development, please don't use on production projects.__

## Requirements

- Cairo
- ffmpeg

### Mac OS

Install by brew

```shell
brew install cairo
brew install ffmpeg
```

## Permission

You should get a token from facebook with scope: __publish_actions__.

## Command

```shell
yarn # install modules

export FB_TOKEN={YOUR_AUTHORIZED_FACEBOOK_TOKEN} # set facebook token in ENV Vars
DEBUG=CanvasLive* ./node_modules/.bin/babel-node ./index.js
```
