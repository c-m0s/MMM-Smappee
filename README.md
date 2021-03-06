[![api](https://img.shields.io/badge/api-Smappee-orange.svg)](https://smappee.atlassian.net/wiki/spaces/DEVAPI/overview)
[![Known Vulnerabilities](https://snyk.io/test/github/cfenner/mmm-smappee/badge.svg?targetFile=package.json)](https://snyk.io/test/github/cfenner/mmm-smappee?targetFile=package.json)
[![Maintainability](https://api.codeclimate.com/v1/badges/d36710fbef288959cc75/maintainability)](https://codeclimate.com/github/CFenner/MMM-Smappee/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/d36710fbef288959cc75/test_coverage)](https://codeclimate.com/github/CFenner/MMM-Smappee/test_coverage)
[![Build Status](https://travis-ci.org/CFenner/MMM-Smappee.svg?branch=master)](https://travis-ci.org/CFenner/MMM-Smappee)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/CFenner/MMM-Smappee/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/CFenner/MMM-Smappee/?branch=master)
[![Code Coverage](https://scrutinizer-ci.com/g/CFenner/MMM-Smappee/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/CFenner/MMM-Smappee/?branch=master)
[![Build Status](https://scrutinizer-ci.com/g/CFenner/MMM-Smappee/badges/build.png?b=master)](https://scrutinizer-ci.com/g/CFenner/MMM-Smappee/build-status/master)

# MMM-Smappee
A module for the MagicMirror, to display informations about the currently energy consumption measured by a Smappee Energy Monitor.

![module preview](.github/preview.png)

## Usage

_Prerequisites_

- a Smappee Energy Monitor at home
- an API key for Smappees API

### API Access

To use this module, it is required to have access to Smappees API. 
You can request access to the API by opening a [ticket](https://support.smappee.com/hc/de/requests/new) or by sending an [email](mailto:support@smappee.com) with the following information:
- full name
- account name
- serial number

### Installation

To install this module, just clone this repository to the __modules__ folder of your MagicMirror: 

```
git clone https://github.com/CFenner/MMM-Smappee.git
```

### Configuration

The module needs the standard configuration block in your config.js to work.

```
{
	module: 'MMM-Smappee',
	position: 'bottom_left',
	config: {
        user: {
            id: '<smappee user id>', 
            password: '<smappee user password>'
        },
        client: {
            id: '<smappee api client id>', 
            secret: '<smappee api client secret>'
        },
	}
}
```

## Languages

The following languages are available:
- :uk:
- :de: 

Further contributions welcome!
