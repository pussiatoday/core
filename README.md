# Form Tools Core

[![Build Status](https://travis-ci.org/formtools/core.svg?branch=master)](https://travis-ci.org/formtools/core)

- [About](#about)
- [Getting Help](#help)
- [Branches](#branches)
- [Upcoming Versions](#upcoming)
- [Tests](#tests)
- [Local Development](#development)
- [Useful links](#links)


<a name="about"></a>
## About 

Form Tools is a data management script written in PHP and MySQL. You install it on your website and use it to either _create_ forms, or tie in your own forms. In both cases, Form Tools generates a custom database to house and manage your data. To find out more about the script, see [formtools.org](https://formtools.org) or look over the [documentation](https://docs.formtools.org).

This repo contains the source code for the Form Tools Core. The Core provides the minimal code needed to run Form Tools
on your server.

*PHP version support*

- Everything up to *Form Tools Core 2.2.7* supports PHP 4.3 - 5.x.
- Form Tools Core 3.0.0 supports PHP 5.3 and later.

Like the project? :star: the repo! Or [donate](https://formtools.org/donate/). Or both! 


<a name="help"></a>
## Getting help

Form Tools has some pretty extensive [documentation](https://docs.formtools.org) - that'll be the place to start. But for specific questions, feel free to open an issue on this repo. Please note that much as I enjoy working on Form Tools, I'm only one guy with a day job and a long daily commute - so prompt responses are difficult!


<a name="branches"></a>
## Branches 

- The `master` branch contains the latest work being done on 3.1. `master` is not production ready.
- `3.0.x` (3.0.1, 3.0.2, 3.0.3...) contain the tip of the various releases, but they're tagged and put into final
releases when complete. Still, handy place to get the latest 3.0.x version if you need it. 


<a name="upcoming"></a>
## Upcoming versions

See the following post for details about the upcoming roadmap.
https://formtools.org/wordpress/?p=802

Summary:

- `3.1` - rewriting the installation/upgrade code so that there's no longer hardcoded bundles of the Form Tools script
including those modules/themes we choose, but instead you select whatever components your want during the installation, 
or later on. 
- `3.2` - revamping the UI. Totally new design, upgrading all the front-end code (i.e. moving to React)
- `3.3` - revamping the user permissions to make it roles-based and not have hardcoded "admin" and "client" accounts like
now.


<a href="tests"></a>
### Tests

Check out TESTS.md. Still in its infancy, but we're getting there. With the addition of the new React code in 3.1 we'll be testing the client side code a lot more. 


<a href="development"></a>
### Local Development

See the [Development](DEVELOPMENT.md) page for details on how to get Form Tools running locally for development.


<a name="links"></a>
## Useful Links

- [formtools.org](https://formtools.org/)
- [Twitter feed (day to day news)](https://twitter.com/formtools/)
- [Documentation](https://docs.formtools.org)
- [Form Tools modules](https://modules.formtools.org/)
- [About Form Tools modules](https://docs.formtools.org/userdoc/modules/) 
- [Installation instructions](https://docs.formtools.org/userdoc/modules/installing/)
- [Upgrading](https://docs.formtools.org/userdoc/modules/upgrading/)
