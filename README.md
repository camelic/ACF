Flickr field
=============

## Description

This is an add-on for the Advanced Custom Fields WordPress plugin that creates a list of all Flickr sets/galleries from a specific Flickr user.

**Contributors**:

* Paul Huisman	([paulhuisman-online.nl](http://www.paulhuisman-online.nl))

## Notice

- This add-on needs [ACF](http://www.advancedcustomfields.com/) 


## Installation

1.Download or clone the ACF Flickr set repo to your plugin or theme:  
* https://github.com/phuisman88/ACF/zipball/master or  
* git clone git://github.com/phuisman88/ACF.git acf-flickr-field  

2.Register the field 

register_field($name, $path);

	if(function_exists('register_field')) {    
		register_field('flickr_set', dirname(__File__) . '/fields/flickr/flickr.php');  
	}  

Make sure the folder flickr is located in wp-content/themes/[YOUR THEME]/fields

## More documentation

* Check out [my personal website](http://www.paulhuisman-online.nl/fresh-look/flickr-field) for more documentation on how to use this custom field for ACF.