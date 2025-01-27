
**This fork is made for Sonaris Media, [this](https://github.com/Sigma-Production/Azuri-Bot) version might be better for you.**

[AzuraCast]: (https://www.azuracast.com/)
[Discord]: (https://discord.com)

# Azuri: A [Discord] bot for [AzuraCast]

[![Apache 2.0 License](https://img.shields.io/github/license/azuracast/azuracast.svg)]()
[![Ethical Open Source](https://img.shields.io/badge/open-ethical-%234baaaa)](https://ethicalsource.dev/definition/)
[![DeepScan grade](https://deepscan.io/api/teams/11651/projects/14572/branches/274342/badge/grade.svg)](https://deepscan.io/dashboard#view=project&tid=11651&pid=14572&bid=274342)

Azuri is a simple but powerful [Discord](https://discord.com/) bot to integrate the open-source web radio management suite **[AzuraCast](https://azuracast.com)** into your [Discord] community.

Azuri is currently in active development with new features and bugs fixed on the daily and is not a *final product* by any means. Azuri was created to support new radios that use [AzuraCast], and provide a platform to connect the radio and community.

## Installing Self-Hosted Version

Azuri is open-source, so you can host your own! Perfect if you want to customize something yourself.

### Via Docker (Recommended)

#### Requirements:

 - [Docker](https://www.docker.com/products/docker-desktop)
 - Docker Compose (included with Docker Desktop for Windows or Mac)
 - [Discord bot token](https://discord.com/developers/applications)
 - [Read a how-to guide](https://discordpy.readthedocs.io/en/latest/discord.html)

#### Installation and Usage

 1. Copy `azuri.sample.env` to `azuri.env`
 2. Edit `azuri.env` with your Discord `BOT_TOKEN`
 3. Run `docker-compose up -d`

### Direct Installation

#### Requirements:
 - [**NodeJS**](https://nodejs.org/): >= 12.18.4
 - [**NPM**](https://www.npmjs.com/get-npm): >= 6.14.6

#### Installation

To install and run:

 1. Copy `azuri.sample.env` to `.env`
 2. Edit `.env` with your Discord `BOT_TOKEN`
 3. Run `npm i`
 4. Run `npm run azuri`

## Dependencies Used

We use multiple packages to make sure Azuri is easy to use and navigate for the end-user. 
- [Discord.JS](http://discord.js.org/) with [Opus](https://www.npmjs.com/package/@discordjs/opus) offical NodeJS library
- [Axios](https://www.npmjs.com/package/axios) used for API calls
- [dotenv](https://www.npmjs.com/package/dotenv) used for `.env` files and enviroment variables
- [ffmpeg](https://www.npmjs.com/package/ffmpeg-static) used for audio streaming
- [fs](https://www.npmjs.com/package/fs) used for storing data in files

### Developer Resources
- [nodemon](https://www.npmjs.com/package/nodemon) hot reloading for development
- [eslint](https://www.npmjs.com/package/eslint) used for code functionaility and error checking

## Bug Reporting 
Found a bug? [Report it](https://github.com/AzuraCast/Azuri/issues/new?assignees=&labels=bug&template=bug_report.md&title=%5BBUG%5D+)!

\* *before reporting please check for existing [issues](https://github.com/AzuraCast/Azuri/issues)* <!-- and [Projects](https://github.com/AzuraCast/Azuri/projects)-->

## Feature Request
Thought of a great idea? [Request it](https://github.com/AzuraCast/Azuri/issues/new?assignees=&labels=enhancement&template=feature_request.md&title=%5BFEATURE%5D)!

\* *before requesting please check for existing [issues](https://github.com/AzuraCast/Azuri/issues)* <!-- and [Projects](https://github.com/AzuraCast/Azuri/projects)-->

## Support
Azuri is provided free of charge — but if you find it useful, support us and AzuraCast!

### AzuraCast
[Support AzuraCast here!](https://github.com/AzuraCast/AzuraCast/blob/master/README.md#support-azuracast-development)


## License

Azuri is licensed under the [Apache License, version 2.0](https://github.com/AzuraCast/Azuri/blob/master/LICENSE). This project is free and open-source software; pull requests are always welcome along with bug and feature reports/requests.
