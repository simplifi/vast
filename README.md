VAST
=====

A library for parsing Digital Video Ad Serving Template (VAST) documents, as outlined by the Interactive Advertising Bureau at 
http://www.iab.net/iab_products_and_industry_services/508676/digitalvideo/vast. This library strives to be as true to the 
standard as possible, while presenting a Ruby-friendly interface.

VAST outlines a standard document format for communication between digital video players and ad servers, including support for 
multiple forms of creative and tracking support that conforms to the latest IAB standards.

Installation
------------

VAST is available as a RubyGem.  

    gem install vast

Usage
-----

Parse a VAST document and access it's contents easily. See the documentation for the individual classes for an overview of
what information available for each class.

    document = VAST::Document.parse(File.read("vast_document.xml"))
