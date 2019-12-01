# OpenSMTPD


![logo](images/logo-1.jpg)

<span style='font-size:100px;'>&#9888;</span> **This site is still under construction**

In the meanwhile please check out:

- [git repository](https://github.com/OpenSMTPD/OpenSMTPD)
- [opensmtpd.org](https://opensmtpd.org/)


---------------------

**OpenSMTPD** is a FREE implementation of the server-side
[SMTP](https://en.wikipedia.org/wiki/Simple_Mail_Transfer_Protocol) protocol as
defined by [RFC 5321](https://tools.ietf.org/html/rfc5321), with some
additional standard extensions. It allows ordinary machines to exchange emails
with other systems speaking the SMTP protocol.
OpenSMTPD is part of the [OpenBSD Project](http://www.openbsd.org/). The
software is freely usable and re-usable by everyone under an [ISC
license](https://opensource.org/licenses/ISC). 


OpenSMTPD is primarily developed by Gilles Chehade and Eric Faurot, with
contributions from various OpenBSD hackers and members from other communities.


## Project Goals

Started out of dissatisfaction with other implementations, OpenSMTPD is a
fairly complete SMTP implementation that pursues to be:

- Secure: code carefully, do strict validity checks
  especially in the network input path, and use bounded buffer operations. Use
  privilege separation to mitigate the effects of possible security bugs.
- Reliable: any email that OpenSMTPD has accepted has to be handled with
  care and must not be lost.
- Lean: provide implementation, sufficient for a majority. Don't try to
  support each and every obscure usage case, but cover the typical ones.
- Approachable: provide a powerful and easy to understand
  configuration language.
- Efficient: OpenSMTPD must be able to handle large queues with reasonable
  performance. 


## Portable and Native Distribution

There are two major distributions of OpenSMTPD - native and portable.

OpenBSD team produces native OpenSMTPD distribution - a very small, secure, and
easy to maintain version for the OpenBSD project. The portability team adds
portability code so that OpenSMTPD can run on many other operating systems.

Portable distribution of OpenSMTPD runs on the following Unix-like operating
systems:

- [Linux](https://en.wikipedia.org/wiki/Linux)
- [OpenBSD](http://www.openbsd.org/)
- [FreeBSD](https://www.freebsd.org/)

- NetBSD
- DragonFlyBSD
- SmartOS
- Mac OS X 

Unfortunately, the portability teams can not package and test OpenSMTPD for all
aforementioned operating systems and architectures due to lack of resources.
OpenSMTPD relies on community support for testing, packaging and distribution.
If you are a package maintainer or if wish to contribute to OpenSMTPD please
[get in touch](#get-in-touch) with us.

The portable OpenSMTPD follows development of the native version, but releases
are not synchronized. Portable releases are marked with a 'p' (e.g.  6.6.0p1).
The native OpenBSD distribution will never use the 'p' suffix in it's version. 


## Get In Touch

There are multiple ways to get in touch with OpenSMTPD team. on your 
goal and preferred style of communications 

### Email

There are 3 mailing lists available: general purpose and 2 developers private.

#### General purpose mailing list

Any questions, issues and ideas may be discussed on our
[misc@opensmtpd.org](mailto:misc@opensmtpd.org) list. The list is not
moderated, however registration is required. At this time, the list is very low
volume, so feel free to introduce yourself ;-) 

To register, simply send a mail to to
[misc+subscribe@opensmtpd.org](mailto:misc+subscribe@opensmtpd.org).

To unregister, send a mail to
[misc+unsubscribe@opensmtpd.org](misc+unsubscribe@opensmtpd.org).

If you want to read conversations that already took place visit [the
archive](https://www.mail-archive.com/misc@opensmtpd.org/)


#### Developers private mailing list

Security-related issues may be sent to the private list
[security@opensmtpd.org](mailto:security@opensmtpd.org) which is read only by
the OpenSMTPD developers. Please use this mailing list only to discuss security
related issues.

For issues not related to security use
[bugs@opensmtpd.org](mailto:bugs@opensmtpd.org) which is also read only by the
OpenSMTPD developers. 

### GitHub

If you want to submit a patch, report an issue or request a feature visit
[OpenSMTPD GitHub repository](https://github.com/OpenSMTPD/OpenSMTPD). You are
also welcome submit question there too!

### IRC

If you prefer interactive style of communication IRC might be the right place
to hash things out. Join `#opensmtpd` channel on
[Freenode](https://freenode.net/) The highest activity in the channel occurs
during business hours of [CET](https://www.timeanddate.com/time/zones/cet) and
[ET](https://www.timeanddate.com/time/zones/et) timezones.


