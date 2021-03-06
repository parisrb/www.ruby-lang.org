---
layout: news_post
title: "Ruby 2.3.5 Released"
author: "usa"
translator:
date: 2017-09-14 12:00:00 +0000
lang: en
---

Ruby 2.3.5 has been released.

This release includes about 70 bug fixes after the previous release, and also includes several security fixes.
Please check the topics below for details.

* [CVE-2017-0898: Buffer underrun vulnerability in Kernel.sprintf](/en/news/2017/09/14/sprintf-buffer-underrun-cve-2017-0898/)
* [CVE-2017-10784: Escape sequence injection vulnerability in the Basic authentication of WEBrick](/en/news/2017/09/14/webrick-basic-auth-escape-sequence-injection-cve-2017-10784/)
* [CVE-2017-14033: Buffer underrun vulnerability in OpenSSL ASN1 decode](/en/news/2017/09/14/openssl-asn1-buffer-underrun-cve-2017-14033/)
* [CVE-2017-14064: Heap exposure vulnerability in generating JSON](/en/news/2017/09/14/json-heap-exposure-cve-2017-14064/)
* [Multiple vulnerabilities in RubyGems](/en/news/2017/08/29/multiple-vulnerabilities-in-rubygems/)
* Updated bundled libyaml to version 0.1.7

See the [ChangeLog](https://svn.ruby-lang.org/repos/ruby/tags/v2_3_5/ChangeLog) for details.

## Known Problem

_(This section was added at September 15, 2017.)_

An incompatibility has been found for Ruby 2.3.5.
Ruby 2.3.5 can not link with libgmp nor jemalloc.
We will fix this problem with the next release, but if you are facing the problem now and need to overcome it immediately, get a patch from this link:

* [Ruby 2.4.2 and 2.3.5 cannot link with libgmp nor jemalloc](https://bugs.ruby-lang.org/issues/13899)

## Download

* [https://cache.ruby-lang.org/pub/ruby/2.3/ruby-2.3.5.tar.bz2](https://cache.ruby-lang.org/pub/ruby/2.3/ruby-2.3.5.tar.bz2)

      SIZE:   14439326 bytes
      SHA1:   48302800c78ef9bbfc293ffcc4b6e2c728705bca
      SHA256: f71c4b67ba1bef424feba66774dc9d4bbe02375f5787e41596bc7f923739128b
      SHA512: 3ecc7c0ac10672166e1a58cfcd5ae45dfc637c22cec549a30975575cbe59ec39945d806e47661f45071962ef9404566007a982aedccb7d4241b4459cb88507df

* [https://cache.ruby-lang.org/pub/ruby/2.3/ruby-2.3.5.tar.gz](https://cache.ruby-lang.org/pub/ruby/2.3/ruby-2.3.5.tar.gz)

      SIZE:   17836997 bytes
      SHA1:   3247e217d6745c27ef23bdc77b6abdb4b57a118f
      SHA256: 5462f7bbb28beff5da7441968471ed922f964db1abdce82b8860608acc23ddcc
      SHA512: cd6bbba4fb5a0ab5ce7aa6f3b89d021ea742c5aa7934e24b87554d10e2a3233d416051c11aee90f3d8714d168db523a7bf56ef4dafdd256fc8595169c2db496a

* [https://cache.ruby-lang.org/pub/ruby/2.3/ruby-2.3.5.tar.xz](https://cache.ruby-lang.org/pub/ruby/2.3/ruby-2.3.5.tar.xz)

      SIZE:   11437868 bytes
      SHA1:   ef388992fa71cd77c5be960dd7e3bec1280c4441
      SHA256: 7d3a7dabb190c2da06c963063342ca9a214bcd26f2158e904f0ec059b065ffda
      SHA512: c55e3b71241f505b6bbad78b3bd40235064faae3443ca14b77b6356556caed6a0d055dc2e2cd7ebdb5290ab908e06d2b7d68f72469af5017eda4b29664b0d889

* [https://cache.ruby-lang.org/pub/ruby/2.3/ruby-2.3.5.zip](https://cache.ruby-lang.org/pub/ruby/2.3/ruby-2.3.5.zip)

      SIZE:   19887946 bytes
      SHA1:   09c80f9021fa2bfc04ae30a1939faad03b0f5b14
      SHA256: c9971e1ccb6e2f1ab32b1fe05416fce0b19a1cd9ba8fa095c77c4bdf2058e514
      SHA512: 6f14d0cc48d6eaf6168316cb45e22af8d2118ba058fd888ce930f12a22cf7e849e2e185cc7c516fe980f30ee9a942accf9d9e2d4b8a2e79c97b87d4bab704495

## Release Comment

Thanks to everyone who helped with this release.

The maintenance of Ruby 2.3, including this release, is based on the “Agreement for the Ruby stable version” of the Ruby Association.
