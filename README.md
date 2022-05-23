# Rest-Api
UTS Web lanjut
Copyright ©2022 Xeon Bot Inc.

===app.json==========================

{
  "name": "repo name",
  "description": "whatsapp md bot build with nodejs",
  "repository": "https://github.com/Wildanhaq1986/Rest-Api",
  "logo": "https://pbs.twimg.com/media/FO7fojOakAAyYgt?format=jpg&name=900x900",
  "keywords": ["nodejs", "bot", "whatsapp bot", "whatsapp automation", "multi device"],
  "buildpacks": [
    {
      "url": "heroku/nodejs"
    },
    {
      "url": "https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest"
    },
    {
      "url": "https://github.com/DuckyTeam/heroku-buildpack-imagemagick"
    },
    {
      "url": "https://github.com/clhuang/heroku-buildpack-webp-binaries.git"
    }
  ],
   "formation": {
        "worker": {
            "quantity": 1,
            "size": "free"
        }
    }
}

===[ readme.md ]=========================

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=[repo link](https://github.com/Wildanhaq1986/Rest-Api)/)
