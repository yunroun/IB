**v1.7.3** –– 06-24-2020

* updating npm dependencies & resolving vulnerabilities

**v1.7.2** –– 11-18-2018

* auto-login & password-reset now validating against UUIDs and the user's last recorded IP address

**v1.7.1** –– 11-18-2018

* updating mongodb calls to latest driver
* [fix for #12](https://github.com/braitsch/node-login/pull/12)

**v1.7.0** –– 11-18-2018

* updated dependencies to latest versions
* bootstrap v4.1.3 & jquery v3.3.1
* style.css completely rewritten
* [fix for #36](https://github.com/braitsch/node-login/issues/36)

**v1.6.0** –– 06-10-2018

* updated dependencies to latest versions
* updated mongodb connection scheme
* replaced jade templating engine with pug

**v1.5.0** –– 04-21-2016

* redesigned login window
* improved error handling on password reset
* updating client side libraries: 
	* jQuery –– v2.2.3
	* jQuery.form –– v3.51.0
	* Twitter Bootstrap –– v3.3.6

**v1.4.1** –– 02-27-2016

* calls to logout now route to /logout instead of /home
* accounts are now looked up by session.id instead of username
* reset-password modal window fixes
* updating emailjs to v1.0.4
* switching to environment variables for email settings

--
**v1.4.0** –– 06-14-2015

* updating to Express v4.12.4
* adding connect-mongo for db session store 

--
**v1.3.2** –– 03-11-2013

* fixed bug on password reset

--
**v1.3.1** –– 03-07-2013

* adding MIT license

--
**v1.3.0** –– 01-10-2013

* updating to Express v3.0.6

--
**v1.2.1** –– 01-03-2013

* moving vendor libs to /public/vendor

--
**v1.2.0** –– 12-27-2012

* updating MongoDB driver to 1.2.7
* replacing bcrypt module with native crypto

--
**v1.1.0** –– 08-12-2012

* adding /print & /reset methods

--
**v1.0.0** –– 08-07-2012

* initial release

--