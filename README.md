# Portable Listings

## About

There exist several standards for describing audiovisual content metadata (such as the EBUCore Metadata Set and TV-Anytime and many, many others). Often these standards do not specify how to discover, access, and manipulate this information, and they do not capture the full range of information typically found in modern Web applications. Several large companies have also released their own non-standard APIs for accessing and interacting with audiovisual content metadata, increasing the burden on developers and Consumers who wish to support most or all Service Providers. Nor do these APIs inform other providers as to how they should construct similar APIs.

Portable Listings is an attempt to specify a complete, modern, and straight-forward Open specification for Service Providers and Consumers of all sizes to make available and consume audiovisual content metadata in a standardized way.

## Why now?

We believe that with the advent of [HTML5 Video](http://en.wikipedia.org/wiki/HTML5_video) and the everyday growing number of video and television services on the Web create the ideal conditions for developing a common, open spec that everyone can benefit from. We also strongly believe that based on the past (and present!) success of similar initiatives in the Social Media space (e.g. [Portable Contacts](http://portablecontacts.net/) and [Open Social](http://www.opensocial.org/)) there lay an opportunity to connect television and broadcast industry services in a similar fashion. 

## Goals

The goal of Portable Listings is to make it easier for developers to give their users a secure way to access audiovisual content metadata and related information over the web. Specifically, we seek to create:

* A common access pattern and listings schema that any Service Provider can implement.
* Well-specified authorization and access rules.
* Free and open source libraries in many languages for most popular platforms.
* Community-sourced support, documentation, and collaborative tools.
* And absolutely minimal complexity, with the lightest possible toolchain requirements for developers.

## Our Approach

Our design is focused around ease of adoption, which means a few things:

* First, our emphasis is on simplicity of design and targeted use cases, keeping our scope intentionally narrow at the outset. For example, this first version is simply about access, and defers for now on the more complex issues around update and sync.
* Second, we are taking a modern approach to audiovisual content metadata description by unifying traditional and more Web oriented data, in order to properly represent the current diversity of television, broadcasting and Web ecosystems.
* Third, we're leveraging and reusing existing broadcast and television industry standards and semantics wherever possible, including the [EBUCore Metadata Set](http://tech.ebu.ch/docs/tech/tech3293v1_4.pdf), [TV-Anytime](http://www.etsi.org/website/technologies/tvanytime.aspx), [BBC Programmes](http://purl.org/ontology/po/), [HTML5 Video](http://dev.w3.org/html5/spec/Overview.html), [Media Multitrack API](http://www.w3.org/WAI/PF/HTML/wiki/Media_Multitrack_Media_API) and related specifications.
* Fourth, we designed the specification to be extensible and pluggable where additional information and functionality can be easily added by Service Providers as needed.
* And lastly, we're designing something that should be easy for current service providers to adopt. We started with a review of all the major existing television, broadcast, Web and Social media standards and APIs and targeted common capabilities that they all share and provide. We believe this pragmatic balance is the best and quickest way to achieve our intended goal of widespread adoption.

Here is the current [draft spec](http://www.portablelistings.net/spec/portable-listings-spec.html) and the [mailing list](http://groups.google.com/group/portablelistings).

This project is currently being undertaken by [Derrick Media](http://www.derrickmedia.com). We need your help, join the [discussion](http://groups.google.com/group/portablelistings)!.
