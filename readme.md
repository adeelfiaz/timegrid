<a href="http://www.timegrid.io/">
    <img src="http://i.imgur.com/pUUoU6H.png" alt="timegrid.io" title="timegrid.io" align="right" />
</a>

timegrid
============

> Online appointments for freelancers and businesses made easy.

[![Build Status](https://travis-ci.org/timegridio/timegrid.svg?branch=development)](https://travis-ci.org/timegridio/timegrid)
[![Code Climate](https://codeclimate.com/github/timegridio/timegrid/badges/gpa.svg)](https://codeclimate.com/github/timegridio/timegrid)
[![Test Coverage](https://codeclimate.com/github/timegridio/timegrid/badges/coverage.svg)](https://codeclimate.com/github/timegridio/timegrid/coverage)
[![Current Stable](https://img.shields.io/badge/beta--stable-4.3.0-green.svg?style=flat-square)](http://timegrid.io/)
[![Current Beta](https://img.shields.io/badge/dev--alpha-4.4-orange.svg?style=flat-square)](http://demo.timegrid.io/)
[![License](https://img.shields.io/:license-AGPL--3.0-blue.svg?style=flat-square)](http://www.gnu.org/licenses/agpl-3.0.txt)

**The Problem**

Freelancers and medium scale businesses wish to provide online appointments of services to their customers, but the tools out there are either *too expensive* or *too complex* for their needs.

**The Solution**

Timegrid lets them to *easily* interact through *online appointments*. *Simple*, *Useful*, and *Fast*.

Built with the [**Laravel 5.2**](http://laravel.com/docs/5.2) framework for [**PHP**](http://php.net/).

![Timegrid Mindmap](http://i.imgur.com/mJsbo5G.png)

## Appointment Library

Timegrid uses [Concierge package](https://github.com/timegridio/concierge) for handling the appointments.

## Screenshots

![Self-Service Reservation Screenshot](http://i.imgur.com/2UXCx2N.png)
![Appointment Example Screenshot](http://i.imgur.com/y1sw5nH.png)
![Business Dashboard Example Screenshot](http://i.imgur.com/bsnRNk2.png)

## Live Demo

Give a try the [*beta* live demo](http://demo.timegrid.io/)

> **ADVICE:** I hate spam the same you do. Despite demo does not currently send emails, you may use a [maildrop.cc](http://maildrop.cc/) fake account for testing.

## Features

  * User classic and oAuth2 Sign-in/Sign-up with [Socialite](https://github.com/laravel/socialite)
  * Business management
    * Contact addressbook
    * Services management
    * Staff management
    * Availability management
    * Appointment schedule view
    * Appointment calendar view with [fullcalendar](https://github.com/fullcalendar)
    * Basic search
  * Self-service appointment reservation with datepicker
  * Basic email notifications
  * Multiple Languages Support (Localization)
  * Multiple Timezones Support
  * Simple live chat support with [TidioChat](https://www.tidiochat.com/)
  * GUI with [AdminLTE](https://github.com/almasaeed2010/AdminLTE) [Twitter Bootstrap 3](https://github.com/twbs/bootstrap) based theme.

For future features check [issues](https://github.com/timegridio/timegrid/issues?q=is%3Aissue+is%3Aopen+label%3Afeature-request)

## Installing

[Read the INSTALLING section](INSTALLING.md)

## Development

  * [Frequently Asked Questions](https://github.com/timegridio/timegrid/wiki/FAQ)
  * [Troubleshooting](https://timegrid.slack.com/messages/general/)
  * [Contributing](CONTRIBUTING.md)
  * [Roadmap](https://trello.com/b/VNFqnxhc/timegrid-io-dev)
  * [Developer Documentation](http://timegrid-doc-dev.readthedocs.org/en/latest/?badge=latest)

## Author

Timegrid is developed and maintained by [Ariel Vallese](http://alariva.com).

## Special Thanks & Credits

  * [PeGa!](http://ar.linkedin.com/in/pabloegonzalez) for infra support
  * [Mohamed G.Hafez](https://github.com/mg-freelancer) for contributions
  * [John Ezekiel](https://github.com/zeke8402) for friendly hints and creating a really nice [booking-app](https://github.com/zeke8402/booking-app)
  * [Victor](https://github.com/pappavic) for testing and documentation contributions
  * [Mohammad Hossein Mojtahedi](https://github.com/MHM5000) for doc review
  * [Jose V Herrera](https://github.com/josevh) for contributions
  * Using modified icon originally made by [SimpleIcon](http://www.flaticon.com/authors/simpleicon) from www.flaticon.com

## License

Timegrid is open-sourced software licensed under the [AGPL](http://www.gnu.org/licenses/agpl-3.0-standalone.html)
