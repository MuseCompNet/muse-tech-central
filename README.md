muse-tech-central
=================

A collection of open-source museum projects. This is simply a list of organizations active on github along with a list of "featured projects" hopefully of interest to the broader community. It will attempt to be a more open replacement for the lost MuseTechCentral resource.

My aim is to eventually model this after the [JQuery Plugin site](https://github.com/jquery/plugins.jquery.com), where repos can opt-in by including a manifest and a post-receive hook. For now, a list:

## Institutions
- ### [Cooper Hewitt National Design Museum](https://github.com/cooperhewitt)
    - [palette-server](https://github.com/cooperhewitt/palette-server)
        - palette-server is a small little WSGI-compliant httpony to extract colours from an image. ([blog post](http://labs.cooperhewitt.org/2013/giv-do/))
    - [shannon-server](https://github.com/cooperhewitt/shannon-server)
        - shannon-server is a small little WSGI-compliant httpony to calculate the shannon entropy for an image. ([blog post](http://labs.cooperhewitt.org/2013/default-sort-or-what-would-shannon-do/))
    - [tms-tools](https://github.com/cooperhewitt/tms-tools)
        - tms-tools is a set of libraries and command-line scripts for extracting, talking to and working with TMS data. ([blog post](http://labs.cooperhewitt.org/2013/tms-tools-this-is-a-blog-post-about-code/))
    - [collection-wall](https://github.com/cooperhewitt/collection-wall)
        - collection-wall is an early labs experiment for displaying collection objects as a waterfall-like wall of images. ([blog post](http://labs.cooperhewitt.org/2012/building-the-wall/))
    - [chromecast-signage](https://github.com/cooperhewitt/chromecast-signage)
        - A proof-of-concept Chromecast application for web-based signage in museums.
    - [objectphone](https://github.com/cooperhewitt/objectphone)
    	- objectphone is a simple implementation of the collections API connected to voice and SMS via [Twilio](http://twilio.com) . It is written in Python and there is a Node version as well. ([blog post](http://labs.cooperhewitt.org/2013/object-phone/))
    - [plumbing-atkinson-server](https://github.com/cooperhewitt/plumbing-atkinson-server)
    	- A simple Flask-based HTTP-pony to dither images.
    - [py-cooperhewitt-api](https://github.com/cooperhewitt/py-cooperhewitt-api)
    	- Python bindings for the Cooper-Hewitt collections API.
    - [py-cooperhewitt-csvtools](https://github.com/cooperhewitt/py-cooperhewitt-csvtools)
    	- Cooper-Hewitt tools for ensuring and wrangling CSV files ... because character encoding.
    - ... and more

- ### [Indianapolis Museum of Art](https://github.com/IMAmuseum/)
    - [ChicagoCodeX](https://github.com/IMAmuseum/ChicagoCodeX)
        - An authoring and publishing environment for online catalogues with full scholarly apparatus
    - ... and more

- ### [Maine Discovery Museum](https://github.com/mainehackerclub/MDM)
    - "Our hackers are doing a lot of good work at the Maine Discovery Museum in Bangor, Maine. This is the code for the various exhibits that we've repaired or enhanced."

- ### [Media Lab at the Metropolitan Museum of Art](https://github.com/metmuseum-medialab)
    - Some visualization and exhibit experience sketches.
    - [Collections API](https://github.com/jedahan/collections-api)
        - A screen scraper that powers [scrapi.org](http://scrAPI.org), grabbing object information from the met's collection pages.

- ### [Minneapolis Institute of Arts](https://github.com/artsmia)
    - [griot](https://github.com/artsmia/griot)
      - A tool for building engaging stories around objects, both
        in-gallery and on the web.
        [Wordpress](https://github.com/artsmia/GriotWP) for friendly
        content entry, piped as JSON for presentation in a 'rich web
        app'.
    - [metadrafts](https://github.com/artsmia/metadrafts)
      - Wordpress editorial revision workflow
    - [galleries.csv](https://github.com/miabot/galleries.csv)
      - What's currently on view. Updated daily, diff\`ed, and
        annotated with thumbnails.

- ### [Museum of Life and Science](https://github.com/lifeandscience)
    - Arduino, Oauth2, and Wordpress

- ### [Museum Victoria](https://github.com/museumvictoria)
    - [describe-me](https://github.com/museumvictoria/describe-me)
        - Describe Me is a website that asks you to write alternative text (alt-text) for images contained within Museum Victoria’s collection.
    - [digital-labels](https://github.com/museumvictoria/digital-labels)
        - Web API for delivering data for museum exhibitions labels.
    - iOS and Android code for Field Guide apps.

- ### [Science Museum of Minnesota](https://github.com/scimusmn/)
    - HTML5 kiosk apps
    - Kiosk control software
    - DevOps tools for deployment and systems monitoring

- ### [Victoria and Albert Museum](https://github.com/organizations/vanda)
    - [jquery_collections_browser](https://github.com/vanda/jquery_collections_browser)
        - A jQuery plugin for browsing the Victoria and Albert Museum's collections data and images via its API.
    - [DigitalLabels](https://github.com/vanda/DigitalLabels)
        - Django app to generate an interactive gallery label interface, optimised for touch screens and tablets.

- ### [Walker Art Center](https://github.com/walkerart)
    - [infolounge_walls](https://github.com/walkerart/infolounge_walls)
        - HTML5 Kiosk built on top of Swipe.js (old 2.0 branch) and Leaflet.js, this project creates a touch interface a set of zoomable images or video.
    - [garden](https://github.com/walkerart/garden)
        - Minneapolis Sculpture Garden 25th Anniversary: OpenStreetMaps data and Leaflet.
    - ... and more

- ### Your institution here
    - Fork this repo and submit a pull request!

## Projects
- [Serendip-o-matic](https://github.com/chnm/serendipomatic/)
    - Source code for serendipitous discovery tool built at One Week ¦ One Tool open-source software-development institute that includes results from DPLA, Europeana (and now Trove). More national and topic aggregators would be ace!

- [Museum APIs](https://github.com/mialondon/Museum-APIs)
    - Bits of (really quite old) PHP code used to access various museum APIs. 
	
- [The Museum System API](https://github.com/smoore4moma/TmsApi)
    - Services to access basic TMS tombstone and object package data.  Services are written in .NET, clients are jQuery.	

- [si-scrape](https://github.com/mdlincoln/si-scrape)
    - A set of Ruby scripts to scrape information from the Smithsonian Institution's collections portal, and parse it into machine-readable JSON.
