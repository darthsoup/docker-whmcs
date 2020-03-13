Docker for WHMCS
===

A WHMCS 7.1+ developer environment for docker/docker-compose which is heavily inspired by [Laradock](https://github.com/laradock/laradock/)

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Support](#support)
- [Contributing](#contributing)

## Installation

Clone this repo with git and copy the _WHMCS_ installation archive to the `./whmcs` directory.

### Requirements

You need a valid and licensed copy of WHMCS 7.1+.
If needed, you can ask the WHMCS Support for a Developer License.

## Usage

Copy the `env-example` to `.env` and edit the parameters if you want too.

Start the container with

```
docker-compose up
```

After building the container, open your browser and browse to the `/install` directory and install it.

WHMCS installation itself may take a while.

## Contributions

Please use [Github](https://github.com/darthsoup/docker-whmcs) for reporting bugs, and making comments or suggestions.
