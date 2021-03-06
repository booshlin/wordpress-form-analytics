# Form Analytics for WordPress by Booshlin

* Contributors: booshlin
* Donate link: http://www.booshlin.com/donate/
* Tags: analytics, forms, google analytics
* Requires at least: 3.0.1
* Requires PHP: 5.4
* Tested up to: 4.9
* Stable tag: 1.0.1
* License: GPLv2 or later
* License URI: http://www.gnu.org/licenses/gpl-2.0.html

Add new Google Analytics events for measuring form engagement and usage.

## Description

Form Analytics for WordPress by Booshlin introduces new, custom events to your Google Analytics account to better understand and track form visibility, interactions and submissions on your web site.

An event will be appear in Google Analytics:
* category of 'Booshlin Form Events'
* action is the event listed below.
* label is the form name

### Events Actions

Events fire once per form, except for submitAttempt.

**visibilityPartial**
* The top of the form enters the browser's viewable area.

**visibilityComplete**
* The bottom of the form enters the browser's viewable area.

**fieldFocus**
* A form field is clicked.

**submitAttempt**
* The submit button of the form is clicked.

**submitSuccess**
* The form submit validates and returns a success response.

### Event Label

Event label will be a unique id for this form, composed of:
* WordPress page slug
* form id (if present)
* form name (if present)
* form role (if present)
* id number based off the number of forms on page

`homepage_signup_1` would be the label of the first form, a signup form on your web site's homepage.

## Features:

* Compatible with multiple forms on a page at a time.
* Excludes adminbar and search forms.


## Compatible with:

* Contact Form 7

### Compatibility Roadmap (in no particular order)

* Ninja Forms
* WPForms
* Gravity Forms
* Pirate Forms
* Formidable Pro

## Installation

This section describes how to install the plugin and get it working.

1. [Set up Google analytics tracking](https://support.google.com/analytics/answer/1008080?hl=en)
	1. Install it on your web site through your theme or a plugin
1. Upload contents of `form-analytics-for-wordpress` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress


## Changelog

### 1.0

* Contact Form 7 compatible
