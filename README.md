# Krumo

## Requirements

* CodeIgniter 2
* [CodeIgniter Sparks](http://getsparks.org/)

## Setup

1. [Install Sparks](http://getsparks.org/install) if you haven't done so already.
2. Install the google-analytics-lib spark (see [here](http://getsparks.org/get-sparks) if you don't know how).

## Info

Integration krumo into codeigniter.

## Usage

controler call

## $this->load->spark('krumo/x.x.x');

To load the aggregate spark..


## Krumo

#### incluede:

	config-> autoload.php
	libraries->krumo.php
	libraries->krumo.ini
	libraries->krumo.js
	libraries->skins

#### Setup:

in config file ( krumo.ini into library folder )

[skin]
for select krumo skin

[css]
for extend external css file ( not recommend , more load time )


HOW TO CALL:

krumo('string');

krumo($variable);