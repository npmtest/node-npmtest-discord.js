# npmtest-discord.js

#### basic test coverage for  [discord.js (v11.0.0)](https://github.com/hydrabolt/discord.js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-discord.js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-discord.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-discord.js.svg)](https://travis-ci.org/npmtest/node-npmtest-discord.js)

#### A powerful library for interacting with the Discord API

[![NPM](https://nodei.co/npm/discord.js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/discord.js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-discord.js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-discord.js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-discord.js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-discord.js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-discord.js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-discord.js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-discord.js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-discord.js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-discord.js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-discord.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-discord.js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-discord.js/build/test-report.html](https://npmtest.github.io/node-npmtest-discord.js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-discord.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-discord.js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-discord.js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-discord.js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-discord.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-discord.js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-discord.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-discord.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Amish Shah"
    },
    "browser": {
        "ws": false,
        "uws": false,
        "erlpack": false,
        "opusscript": false,
        "node-opus": false,
        "tweet-nacl": false,
        "src/sharding/Shard.js": false,
        "src/sharding/ShardClientUtil.js": false,
        "src/sharding/ShardingManager.js": false,
        "src/client/voice/dispatcher/StreamDispatcher.js": false,
        "src/client/voice/opus/BaseOpusEngine.js": false,
        "src/client/voice/opus/NodeOpusEngine.js": false,
        "src/client/voice/opus/OpusEngineList.js": false,
        "src/client/voice/opus/OpusScriptEngine.js": false,
        "src/client/voice/pcm/ConverterEngine.js": false,
        "src/client/voice/pcm/ConverterEngineList.js": false,
        "src/client/voice/pcm/FfmpegConverterEngine.js": false,
        "src/client/voice/player/AudioPlayer.js": false,
        "src/client/voice/player/BasePlayer.js": false,
        "src/client/voice/player/DefaultPlayer.js": false,
        "src/client/voice/receiver/VoiceReadable.js": false,
        "src/client/voice/receiver/VoiceReceiver.js": false,
        "src/client/voice/util/SecretKey.js": false,
        "src/client/voice/ClientVoiceManager.js": false,
        "src/client/voice/VoiceConnection.js": false,
        "src/client/voice/VoiceUDPClient.js": false,
        "src/client/voice/VoiceWebSocket.js": false
    },
    "bugs": {
        "url": "https://github.com/hydrabolt/discord.js/issues"
    },
    "dependencies": {
        "@types/node": "^6.0.0",
        "pako": "^1.0.0",
        "superagent": "^3.3.0",
        "tweetnacl": "^0.14.0",
        "ws": "^1.1.0"
    },
    "description": "A powerful library for interacting with the Discord API",
    "devDependencies": {
        "discord.js-docgen": "github:hydrabolt/discord.js-docgen#master",
        "eslint": "^3.12.0",
        "parallel-webpack": "^1.6.0",
        "uglify-js": "github:mishoo/UglifyJS2#harmony",
        "webpack": "2.2.0-rc.3"
    },
    "directories": {},
    "dist": {
        "shasum": "735a4fc5607b04b2c1d0d699c88ea2936cf0d656",
        "tarball": "https://registry.npmjs.org/discord.js/-/discord.js-11.0.0.tgz"
    },
    "engines": {
        "node": ">=6.0.0"
    },
    "gitHead": "c8f6b6b0596c50dfb0d910dca88b5a32931041b6",
    "homepage": "https://github.com/hydrabolt/discord.js#readme",
    "keywords": [
        "discord",
        "api",
        "bot",
        "client",
        "node",
        "discordapp"
    ],
    "license": "Apache-2.0",
    "main": "./src/index",
    "maintainers": [
        {
            "name": "hydrabolt"
        }
    ],
    "name": "discord.js",
    "optionalDependencies": {},
    "peerDependencies": {
        "erlpack": "hammerandchisel/erlpack#master",
        "node-opus": "^0.2.0",
        "opusscript": "^0.0.1",
        "uws": "^0.12.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/hydrabolt/discord.js.git"
    },
    "runkitExampleFilename": "./docs/examples/ping.js",
    "scripts": {
        "docs": "docgen --source src --custom docs/index.yml --output docs/docs.json",
        "lint": "eslint src",
        "test": "eslint src && docgen --source src --custom docs/index.yml",
        "test-docs": "docgen --source src --custom docs",
        "web-dist": "node ./node_modules/parallel-webpack/bin/run.js"
    },
    "types": "./typings/index.d.ts",
    "version": "11.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
