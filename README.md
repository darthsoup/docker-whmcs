# Docker Container for WHMCS

A WHMCS 7.1+ developer environment for Docker, heavily inspired 
by [Laradock](https://github.com/laradock/laradock/)

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Support](#support)
- [Contributing](#contributing)

## Installation

Clone this repository and copy the [WHMCS](https://download.whmcs.com) installation archive to the `./whmcs` directory.

### Requirements

You need a valid and licensed copy of WHMCS. If required, you can contact the WHMCS Support for a development license.

### Tested WHMCS Versions

* [X] 7.1
* [X] 7.2
* [X] 7.4
* [X] 7.6
* [ ] 7.10 (working, but needs additional testing)
* [ ] 8.X (may working, but needs additional testing)

## Usage

Copy the `.env.example` to `.env` and edit the parameters to your needs.

Keep in mind, you need to choose the right PHP version for your WHMCS Installation. See [Requirements](https://docs.whmcs.com/System_Requirements) for additional Information.

**Example:** WHMCS 7.1 needs PHP 7.0 while Version 7.2 requires PHP 7.1+

Start the container with

```bash
docker-compose up
```

After building the container, open your browser and browse to the `/install` directory and follow the installation routine.

Use `mysql` for Database Host to continue with the instllation.

The WHMCS installation itself takes 2-3 minutes.

## Contributions

Please use [Github](https://github.com/darthsoup/docker-whmcs) for reporting bugs, and making comments or suggestions.
