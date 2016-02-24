---
title: Field Guide to GIS
---

Are you interested in creating a map to help your community assess their environment? Are you trying to catalog the projects of local organizations, groups, and fellow Volunteers? Are you concerned with mapping out zones and neighborhoods that are unsafe for Volunteers? Are you interested in visualizing the effect of your project and your efforts over time?

Understanding your objectives from the outset will help to ask the right questions, pick the right mapping platform(s), and learn on the best tools for the task.

___



## Table of Contents

- [Introduction](#introduction)
- [Why this Field Guide?](#why-this-field-guide)
- [What is GIS?](#what-is-gis)
- [What are maps?](#what-are-maps)
- [Show me the layers](#show-me-the-layers)
- [What kinds of spatial data may be useful in my work?](#what-kinds-of-spatial-data-may-be-useful-in-my-work?)
	- [Remote sensed images](#remote-sensed-images)
	- [Administrative boundaries](#administrative-boundaries)
	- [Human and situation data](#human-and-situation-data)
	- [Terrain](#terrain)
- [Questions to ask before starting a GIS project](#questions-to-ask-before-starting-a-GIS-project)
- [Do GIS by not starting with GIS tools](#do-gisprojects-by-not-starting-with-gis-tools)
- [An example of thinking without technology](#an-example-of-thinking-without-technology)
- [Moving forward with confidence](#moving-foward-with-confidence)
- [Peace Corps can use GIS to...](#peace-corps-can-use-gis-to...)
- [Tutorials and Basics](#tutorials-and-basics)
	- [Getting Started in GIS in International Development](#getting-started-in-gis-in-international-development)
	- [Readings on GIS in International Development](#readings-on-gis-in-international-development)
	- [Readings on GIS in Government](#readings-on-gis-in-government)
- [Technologies](#technologies)
	- [Cloud-based GIS and Mapping Platforms](#cloud-based-gis-and-mapping-platforms)
	- [Software and Platforms](#software-and-platforms)
	- [Browser-based GIS Services](#browser-based-gis-services)
	- [OpenStreetMap (OSM)](#openstreetmap-osm)
		- [OSM Tutorials](#osm-tutorials)
		- [OSM Services and Apps](#osm-services-and-apps)
		- [OSM and Peace Corps](#osm-and-peace-corps)
		- [Criticisms of OSM](#criticisms-of-osm)
- [Data](#data)
	- [Geospatial-related Databases](#geospatial-related-databases)
	- [Shape Files](#shape-files)
- [Projects](#projects)
	- [Peace Corps Volunteer Projects](#peace-corps-volunteer-projects)
	- [External Case Studies](#external-case-studies)
	- [Topical Maps Showcase](#topical-maps-showcase)
	- [Fun and Interesting](#fun-and-interesting)
- [Advanced](#advanced)
	- [Guides and Manuals](#guides-and-manuals)
	- [Advanced Analysis](#advanced-analysis)
	- [Advanced Development](#advanced-development)
	- [Advanced Tools and Services](#advanced-tools-and-services)
	- [Showcase Map Examples](#showcase-map-examples)
- [Opportunities for Volunteers to work in GIS](#Opportunities for Volunteers to work in GIS)
	- [Pre-Departure](#pre-departure)
	- [Trainees](#trainees)
	- [Volunteers](#volunteers)

___



## Introduction

Welcome, cartography nerds! Our purpose here is to provide a basic overview and links to resources to get you started in GIS and mapping during your service as a Peace Corps Volunteer (and beyond).

It's important to remember that this field can be absolutely **HUGE** and sometimes overwhelming. Don't be discouraged! There are many points of entry, and even a little knowledge in this stuff can go a long way to making your projects more effective, transparent, and sustainable. So hopefully there's something for everyone here, and this toolkit can help you to level-up your mapping skills.

Without further ado, let's get started!



## Why this Field Guide?

We want the Peace Corps community to learn to analyze, map, and publish spatial information using GIS tools that are available and appropriate in the field. We hope that this guide will help to develop skills in web and paper-based cartography, collaborative online mapping, spatial data analysis, mobile phone data collection, and using and manipulating satellite and aerial imagery.



## What is GIS?

Up first—A GIS (Geospatial [or Geographic] Information System) system is 'designed to capture, store, manipulate, analyze, manage, and present all types of spatial or geographical data ([wikipedia source](https://en.wikipedia.org/wiki/Geographic_information_system)).

When we talk about GIS, we could be referring to the academic discipline, the collection of software and platforms, processes, or even simply data that has a spatial component. Context matters here in determining which one is being discussed. Also, you'll sometimes see 'GIS' and 'Mapping' thrown around interchangeably. For our purposes in this toolkit, they are interchangeable, so try not to get hung up on them.



## What are maps?

Second—Maps. What are maps? OK, that's actually going to be a tough one, and it's a little outside of the scope here to define. Suffice it to say, this toolkit is basically going to refer to [awesome maps like this](http://americangeo.org/map-links/):

![World Map](https://cdn.shopify.com/s/files/1/0071/5032/products/World_Maps_International_20mil_1.jpg?v=1413619116)
*Don't be tempted by the neo-colonial legacy hegemony of the oft-used [Mercator Projection](https://en.wikipedia.org/wiki/Mercator_projection). This is Peace Corps.*

But when we talk about GIS, we're not simply talking about political maps that have different colors for different countries that are neatly labeled and agreed upon.

We could be talking about specific parts of the world zoomed in from countries, even down to specific neighborhoods and addresses. It's not just labels of place names, but can be things like shapes of rivers, lakes, and mountains (topography), boundaries of areas that might include data on land ownership or voting districts (sometimes called polygons or shapes), and points of interest or dots where interesting things occur (points), as well as images overlaid on top of these maps that might show temperatures of hot spots or satellite imagery.

Phew.

Oh, and it's not just in two-dimensions (could be three or even four!), and it might not be static like a map on a wall, but dynamic like a map that lets you zoom in and out and select different layers of interest. Oh, now that I've mentionned 'layers'...



## Show me the layers

Before your mind explodes, just try to digest this image. The amazing thing about maps, mapping, GIS, and computers these days is that we can put all of these things together in new and interesting ways.

We can see relationships and data presented to us in a way that allows us to see new connections, gain new insights, and monitor important situations.

This great image below shows how these pieces *can* fit together to combine data into something that could be really interesting ([image source](http://www.co.ontario.ny.us/index.aspx?NID=1176)).

![GIS Data Layers](/img/gis-layers.png)


## What kinds of spatial data may be useful in my work?

Using GIS software or web tools, maps are made by combining spatial data layers to create the desired combination of geographic information. Types of layers of particular interest in Peace Corps’ work
include the following.

### Remote sensed images

These comprise satellite or aerial photography. The images must be processed and geo-referenced before they can be used. Base maps These
could be a scanned (raster) image of a paper map. Or, built up from a series of vector data layers – roads, rivers, settlements, etc.

### Administrative boundaries

Vector files showing the various levels of the country’s administrative geography (provinces, districts etc) are often essential. This
is because much situation information of humanitarian relevance is collected via the normal administrative apparatus of the country; to map, for example, disease incidence by district it is necessary to have map data showing the district boundaries.

### Human and situation data

Such as the locations of the beneficiary population, the locations of aid resources, and so on. This may be data you collect yourself,
or obtain from partners. It should be linked to your other work data sets – assessment data, programme plans, etc. Remember that any spatially-referenced
data in a suitable format can be imported into your GIS.

### Terrain

Hills and valleys can be represented by a digital elevation model (DEM) which can create a contour map layer. You know, the fun stuff.


## Questions to ask before starting a GIS project

While we're thinking about the different *types* of GIS maps, layers, technologies, and everything else, it might be a great opportunity to take a deep breath, step back, and ask ourselves some of the important questions that will guide our efforts and thinking. You don't have to know them all now, but they're here to help -- 
 
- What is my overall objective, and who is this for?
- Who will help me build this?
- What tools (software, computing, phone, bandwidth, etc.) will I need?
- What do I know how to do, and what will I or others need to learn?
- What information do I already have, and what do I need?
- Am I putting anyone or any community at risk by collecting or displaying this information?
- What are the various policies that my counterpart or Peace Corps operate under?
- Is this a one-off platform/presentation or is this meant to be sustainable and dynamic over time?

Now that we've had some food-for-though, let's stay at 30,000 feet and thinking about *how* we approach thinking around our tools and technologies...



## Do GIS by not starting with GIS tools

Now that your mind has hopefully been blown a little bit, let's roll up our sleeves. How in the heck can you use maps in your projects? The most important piece of advice that I can give would be to think of GIS and mapping as **the thing that allows you to do the thing**, they aren't the thing itself....

...huh?

Basically this just means that you should think of GIS and mapping as tools to achieve your objectives as a Peace Corps Volunteer first, not simply as the solution that's going to magically solve things for you. One helpful exercise before even beginning to sort through the links and resources below is to define what you're wanting to do *without* invoking technology or mapping. Why do this? One, because it helps to ensure you've got a clearly articulated objective laid out ahead of you. Two, it's actually kind of difficult.



## An example of thinking without technology

Maybe you want to "create a map of all the bednets that are distributed within my community." Great! But let's think about this -- why do we want to create a map of this? What are we missing?

"...so that we can see where there are unequal distributions of the nets and correct for that on an ongoing basis..." Better, but not perfect. Maps don't do that magically -- we need to think about the data behind the map, and connect that to the lessons learned from that, and connect these two with our mapping platform as the vehicle to move us from point A to point B.

"Our team would like to correct for unequal distributions of bednets across our community in as real-time as possible." Ahhh. Doesn't that feel better? We know what we want, and we know what success is. NOW, we just get to add the tool that we'll use to achieve that -- "...by using an easily accessible and editable web-map..."



## Moving forward with confidence

This is a great start. But it also should just be the beginning. As with any project like this, you'll also want to consider things like designing with your users in mind, using open-standards, addressing privacy and security of the data, and how you're going to make this project sustainable and not simply a one-off that looks oh so cool on your DOS (Description Of Service). Lots more on this here and in other toolkits.

But enough talk -- let's get to the data! Remember that they are works in progress, and new stuff is coming down the pike every single day. Help to contribute to this toolkit (or any of the ICT4D Playbook Toolkits) by checking out the Contributing page. We need your help!



___



### Peace Corps can use GIS to...

###### ...help keep Volunteers safe.
- Individual Volunteer Safety and Security
- Safety and Security at the Post level
- Madagascar cyclone versus cellphone data...
- Areas with security incidents / off-limits
- Travel to Volunteer sites


###### ...help Volunteers do their jobs.
- Michael and cashews
- Coordinate COPs
- Community mapping
- PACA, PACA 2.0

###### ...find relationships we never knew existed.
- Using public data and layers
- Data from aiddata.gov, USAID, GDP v. Peace Corps placement, etc.
- Facilities use and carbon footprint

###### ...make data-driven decisions.
- OHS and the medical staff reporting
- OSIRP adjusts according to AVS mapping...
- OPATS using it to review sector/area/project activities
- Strategic Planning agency-wide
- OSS (emergency management, Volunteer status, consolidation mapping)
- OSIRP (AVS, ET, Dashboards, etc.)
- OHS (health incidence, accidents, trends, etc.)
- OPATS (Programs, M&E)
- VRS (FBR, Strats, applications, trends, etc.)
- 3GL (RPCV mapping, resources, competitions, etc.)


###### ...tell the Peace Corps story.
- Where have Volunteers served
- State to country map since 1963...
- Choropleth map over time
- Volunteer Projects and Programs
- Storymap of where Volunteers have served over time
- [Volunteer Openings](http://www.peacecorps.gov/openings/) and [Where Peace Corps Volunteers Serve](http://www.peacecorps.gov/volunteer/learn/wherepc/?noflash=yes)

###### ...monitor our community.
- Disasters
- Volunteer status
- Consolidation points

###### ...recruit the best next generation of Volunteers.
- RROs, FBR, Strats, campuses
- VRS applications, diversity, etc.

###### ...promote a better understanding of other peoples.
- [World maps](http://theworldmapproject.com) with their students and youth over engage with as a community and youth-development activity.
- [Third Goal Activities](https://www.peacecorps.gov/resources/returned/thirdgoal/register/)



___


# Tutorials and Basics



### Getting Started in GIS in International Development

- [Basics of Geodata and Open Mapping (video)](https://www.youtube.com/watch?v=LZaa8jIUDVY) -- 20-minute introduction from on geodata and open-mapping from Max Richman for Tech Change.

- [Maptime](http://maptime.io/) --Open learning environment for all levels and degrees of knowledge, offering intentional educational support for the beginner.

- [Harvard Introduction to GIS](http://hcl.harvard.edu/libraries/maps/gis/tutorials.html) -- Three-part movie accompanied by hands-on exercises (the exercises apparently require an ArcGIS license -- but the videos are worth watching.) 

- [State of the Map 2015](http://stateofthemap.us/program/) -- All of the talks and threads of the US Government involvement in OpenStreetMap in particular. See our very own [Courtney Clark discuss Peace Corps and OSM](http://stateofthemap.us/osm-in-peace-corps/)!



### Readings on GIS in International Development

- [Social Media, Crisis Mapping and the New Frontier of Disaster Response](http://www.theguardian.com/global-development-professionals-network/2013/oct/08/social-media-microtasking-disaster-response) -- Nice little overview of crisis mapping.

- [Why GeoMapping is worth a Thousand Words](http://www.ictworks.org/2015/01/19/why-good-geo-mapping-is-worth-a-thousand-words/) -- Great defense of mapping from Taryn Davis of Development Gateway.



### Readings on GIS in Government

- [USAID Welcomes the Crowd to Use Geo-Mapping Tools for Open Source Development](http://blog.usaid.gov/2014/01/usaid-welcomes-the-crowd-to-use-geo-mapping-tools-for-open-source-development/) -- Delightful overview from a government agency that's gotten out ahead on this stuff. "OpenStreetMap and Field Papers is changing the way USAID does business by freely sharing open source mapping programs and bringing in the global community to help solve local problems."

- [Shadrok Roberts on Crowdsourcing at USAID & Geodata (video)](https://www.youtube.com/watch?v=9B9RUdDn3xA) -- TED-esque style talk by former USAID geodata guru (Shadrok is now at [Ushahidi](http://www.ushahidi.com)) detailing a project to get crowds to fill in the blanks on messy geospatial data. Peace Corps can learn from this example, yeah?

- [Slumdog mapmakers fill in the urban blanks](http://www.newscientist.com/article/mg22429924.100-slumdog-mapmakers-fill-in-the-urban-blanks.html?full=true#.VGgPd5PF-0s) -- Defense of open-mapping from the point of view of ground-truthing the poverty situation.

- [Crowdsourcing 2.0: Why Putting the Slum on a Map is not Enough](http://ced.berkeley.edu/bpj/2014/03/crowdsourcing-2-0-why-putting-the-slum-on-a-map-is-not-enough/) -- A mostly-defense-of-mapping but with cautions, particularly with the famous Kibera, Kenya example.

- [For government, OpenStreetMap is more than excellent data. It's a transformation](http://openstreetmap.us/2015/03/government-and-openstreetmap/) -- Presidential Innovation Fellow and MapGive Founder Mikel Maron talks about OSM.



# Technologies



### Cloud-based GIS and Mapping Platforms

- [Google Maps](http://maps.google.com) -- The industry standard right now. Has directions, ability to add custom layers/point, Street View, and a bunch of other things. Also has apps with more and more increased (and offline) functionality for smartphones.

- [OpenStreetMap](http://osm.org) -- Open-source map created by community of mappers that contribute and maintain data about roads, trails, cafés, railway stations, and much more, all over the world. Check out the [wiki](http://wiki.openstreetmap.org/wiki/Main_Page) for more information.

- [Here Maps](https://www.here.com/) -- Road-centric maps. Built by a consortium of car manufacturers -- the offline apps are really great.








### Software and Platforms

- [ESRI - ArcGIS](http://www.esri.com/software/arcgis/arcgis-for-desktop) -- The industry-standard in GIS software and solutions. Better with enterprise accounts, but you're able to do a trial version to make interested layered maps on their ArcGIS Online platform. The suite of ESRI tools is pretty expansive, ranging from consumer-level items like their smartphone apps all the way up to enterprise-level server platforms. If you're getting involved in GIS, you've no doubt heard this name, especially with respect to ArcGIS Desktop.

Limitations: Price tag, desktop software processes, high learning curve and training/expertise investment, proprietary formats.

- [QGIS](http://www.qgis.org/) -- Free and Open Source Geographic Information System. Basically compares to ArcGIS Desktop (with even a few bells and whistles added). It's a little *less* user friendly, and it's more-or-less a standalone GIS solution (it won't host the content or provide you raw datasets). Check out the tutorials to level up on this if you're ready to move past looking at OpenStreetMap layers. Also has Windows, Mac, and Linux versions available.

- Limitations: Not a full GIS package in that it still requires external tools (cloud or web-based software) to translate the data into something dynamic or more visually appealing.

- [QGIS Tutorials and Tips](http://www.qgistutorials.com/en/) -- Great documentation from the QGIS team.

- [QGIS Walkthrough (video)](https://www.youtube.com/watch?v=L0r1GNTT-0o) -- Video introduction from the TechChange team to QGIS.

- [QGIS Interactive Tutorial from Harvard](http://maps.cga.harvard.edu/qgis/) -- A little dated but still good tutorial walking through the QGIS interface.



### Browser-based GIS Services

- [CartoDB](https://cartodb.com/) -- Browser-based mapping and analysis of location data.

- [CartoDB Map Academy](http://academy.cartodb.com/) -- Learn how to create maps on the web and visualize geospatial data using CartoDB.

- [MapBox](http://www.mapbox.com/) -- Pick from a dozen beautifully designed maps and create an application from it in just a few seconds. Great for creating visually appealing maps from preexisting or pre-cleaned data. Also has iOS, Android, and mobile web versions.

- [Mapbox Studio - Mapbox](https://www.mapbox.com/mapbox-studio/) -- Design studio to create stunning interactive maps (formerly TileMill).

- [Stamen Maps](http://maps.stamen.com/) -- Toner, terrain, and watercolor maps, free for the taking.

- [Dropchop.io](http://dropchop.io/) -- Browser-based GIS powered by Mapbox.js and Turf.js

- [Ushahidi](https://www.ushahidi.com/) -- A web-based platform for mapping information from reports from SMS, Twitter, e-mail, and web. Initially used to map election violence and intimidation in Kenya.



### OpenStreetMap (OSM)

There's a lot to say about the crowd-sourced and open platform of OpenStreetMap. And others have done so much better than I can, including our own Courtney Clark. Definitely check out the [OSM-flavored Mapping Toolkit](https://github.com/PeaceCorps/mapping-toolkit) for more info!



##### OSM Tutorials

- [MapGive](http://mapgive.state.gov) -- An initiative of the State Department's Humanitarian Information Unit. Several highly recommended video tutorials explaining the importance of OSM for humanitarian response and how to edit using the ID editor.

- [LearnOSM](http://learnosm.org/en/) -- Tutorials on a variety of OSM topics, including the iD editor, the JOSM editor, Field Papers, organizing mapping trainings, remote mappings, using a GPS device and more. Tutorials are in English, German, French, Croatian, Bahasa Indonesia, Italian, Chinese, Norwegian, Portuguese, Russian and Kiswahili. 

- [TeachOSM](http://teachosm.org/en/) -- Curriculum for educators to incorporate OSM into their classrooms. The site includes assessment tools and case studies. 



##### OSM Services and Apps

- [Field Papers](http://fieldpapers.org/) -- Print an atlas, record what you see in the world through street mapping, and upload the data to OpenStreetMap. 

- [Maps.me](http://maps.me/en/home) -- Download fast, detailed and completely offline maps for mobile devices. 

- [Big Map](http://wiki.openstreetmap.org/wiki/Bigmap) -- Print large maps of OSM data from your browser.

- [MapOSMatic](http://www.maposmatic.org/) -- Generate maps of cities using OpenStreetMap data. The generated maps are available in PNG, PDF and SVG formats and are ready to be printed.

- [Open Street Map Directions](http://map.project-osrm.org/) -- Google Maps alternative for directions (routing from point A to point B) using OSM.



##### OSM and Peace Corps

- [Intro to Mapping for Peace Corps (slide deck)](https://docs.google.com/presentation/d/1vhoaPy0jB4CuUi76ypZmjyZO6ueBjigVwF8bRM-pzlI/edit?usp=sharing) -- Presentation by Peace Corps' Courtney Clark on using OSM for Volunteer Projects.

- [Current Peace Corps Tasking Manager tasks](http://tasks.hotosm.org/?sort_by=priority&direction=asc&search=peace+corps) -- The Humanitarian OpenStreetMap Team (HOT) list of tasks that are defined/curated by Peace Corps Volunteers looking for particular communities and neighborhoods to be mapped for their projects.

- [Real Time Edits By #PeaceCorps Mappers](http://powerful-mesa-2776.herokuapp.com/) -- Realtime mapping efforts of #PeaceCorps on OpenStreetMap.



##### Criticisms of OSM

- [OpenStreetMap Diversity Wiki page](https://wiki.openstreetmap.org/wiki/Diversity) -- OSMs own links and breakdown of discussions.

- [Improving Diversity in OpenStreetMap](http://stateofthemap.us/improving-diversity-in-osm/) -- Post on the importance of opening up the platform.

### Other GIS Technologies and Platforms

**Mapbox, TileMill, QGIS, GRASS, Leaflet.js, CartoDB, Google Maps, Excel, D3, Microsoft Dynamics CRM, etc...**

There are a lot of different types of applications to support mapping, GIS, and geospatial workflows in a variety of applications. I have personally worked with a number of offices to figure out different ways to approach their business case for various mapping cases, and established an agency working group to articulate all the various use cases and technologies across the agency so that we can get the best bang for our buck.

- **Mapbox** -- An open source mapping platform for developers and designers. Speed and complete cartographic design potential. 

Limitations: But once the tiling is done and the symbology has been laid out, it's not that easy to change things on the fly. Does well with interactivity of objects and popups that could display lots of data.

- **CartoDB** -- Uses the PostGIS database architecture. The power of PostGIS and Mapnik but none of the setup headache, all wrapped in attractive packaging.

- **Google Fusion Tables** -- Maps, Charts, Motion Chart a.k.a. GapMinder.

- **Google Spreadsheet Chart Maps** -- Quick but limited.

- **Google Maps** -- Google's webmapping service application. Provides satellite and road layers, as well as route planners.

- **MapBox.js**

- **Leaflet**

- **D3**

- **DataMapping**

### Visualization Software

- Illustrator, Photoshop, Sketch, Others
- [Tableau](http://www.tableausoftware.com/) -- Data visualization and business intelligence software (with built-in mapping charts and widgets).
- [R (stats package)](https://www.r-project.org/) -- 'R' is a free software programming language and software environment for statistical computing and graphics. R's extensible object-system includes objects for (among others): regression models, time-series and geo-spatial coordinates.
- [Processing (programming language)](https://processing.org/) -- Open source programming language and integrated development environment (IDE) built for the electronic arts, new media art, and visual design communities.



# Data



### Geospatial-related Databases

- [COD Fundamental Registry](https://cod.humanitarianresponse.info/country-region) -- The Common Operational Datasets (CODs) are critical datasets that are used to support the work of humanitarian actors across multiple sectors. They are considered a de facto standard for the humanitarian community and should represent the best-available datasets for each theme.

- [GeoNames Name Server](http://geonames.nga.mil/gns/html/) -- Official repository of standard spellings of all foreign geographic names, sanctioned by the United States Board on Geographic Names (US BGN). The database also contains variant spellings (cross-references), which are useful for finding purposes, as well as non-Roman script spellings of many of these names. Download the [Country Files](http://geonames.nga.mil/gns/html/namefiles.html) for offline use.

- [GeoNames](http://www.geonames.org/) -- Covers all countries and contains over eight million placenames that are available for download free of charge.

 - [Demographic and Health Surveys (DHS)](http://dhsprogram.com/) -- DHS analyzes and distributes survey results regarding health, nutrition, HIV for over 75 countries.

- [The World Bank Maps](http://maps.worldbank.org/) -- Mapping data globally, regionally, country-level, and thematically across all World Bank projects.

- [AidData](http://aiddata.org/maps) -- Geospatial data and tools enabling development stakeholders to more effectively target, coordinate and evaluate aid. Lots of good datasets and analysis in the International Development sector.

- [Poverty Net - World Bank](http://www.worldbank.org/en/topic/poverty) -- Resource site for measuring and analyzing poverty - includes Poverty Mapping section under Topics link, with Poverty Mapping Documents and Links which has good links to examples of articles and programs.

- [GeoPlatform](http://www.geoplatform.gov/) -- Shared and trusted geospatial data, services, and applications for use by the public and by government agencies and partners to meet their mission needs. Integrated with Data.gov.

- [UNDP Projects](http://open.undp.org/?goback=%2Egde_65094_member_191436479#2012) -- Detailed information on the UNDP’s 6,000+ development projects in 177 countries and territories worldwide. Browse the summaries, click a filter on the right, or search through the full list of projects.

- [Map Links – American Geographical Society](http://americangeo.org/map-links/) -- Really great links to maps on a wide variety of subjects.

- [WorldPop](http://www.worldpop.org.uk/) -- Open access archive of spatial demographic datasets for Central and South America, Africa and Asia to support development, disaster response and health applications.

- [Penn State Open Educational Geography Resources](http://open.ems.psu.edu/courseware) -- Wide range of free online geography and GIS courses, including Problem-Solving with GIS, Cartography and Visualization, Open Web Mapping, and Location Intelligence for Business. 



### Shape Files

- [Natural Earth Data](http://www.naturalearthdata.com/) -- Public domain map dataset available at 1:10m, 1:50m, and 1:110 million scales. Featuring tightly integrated vector and raster data

- [Ellipsoid World with georeference lines and names](https://www.your-vector-maps.com/hi/-144-free-vector-world-maps/-ellipsoid-world-with-georeference-lines-and-names-jpg-300-dpi/?image=wrld-bm-2) -- Site with a bunch of links to vector-based maps and shape files of the whole Earth. Good for building things in Illustrator or Sketch or the web.

- [Vector Maps](https://www.freevectormaps.com/world-maps) -- Various formats and projections.



# Projects



### Peace Corps Volunteer Projects

- [OSM for Malaria Eradication in Botswana Case Study.](https://drive.google.com/file/d/0BxqYHzBUSr1NRzlKNk01ekdONE0/view?usp=sharing) By Theresa Govert and Mike Banfield, Peace Corps Botswana. February 2015. 

- ["'Re mmogo!' The White House, Peace Corps and You -- Together We Can Map Botswana".](http://passport.peacecorps.gov/2015/05/26/re-mmogo-the-white-house-peace-corps-and-you-together-we-can-map-botswana/) By Theresa Govert, Mike Banfield and Christy Nekvinda, Peace Corps Botswana. May 26, 2015, Peace Corps Passport.

- [Mapping and the Power of the Crowd: Peace Corps' Response to Disaster in Vanuatu](http://passport.peacecorps.gov/2015/04/03/mapping-and-the-power-of-the-crowd-peace-corps-response-to-disaster-in-vanuatu/) -- Looking at Peace Corps staff putting information on OSM. 

- [A Break in the Clouds for Open-Source Mapping](http://thenicadventure.com/2015/02/11/a-break-in-the-clouds-for-open-source-mapping/) --  Using OSM and State Department satellite data.

- [Botswana Weekly Awesome: How do you eat an elephant?](http://stompoutmalaria.org/botswana-weekly-awesome-how-do-you-eat-an-elephant/) -- Malaria eradication activities using maps to help gauge project success.

- [Let Data Drive Your Projects](http://issuu.com/peacecorps/docs/pc-15-q2-116_pages_center/1?e=3593068/13460098) -- Article in Peace Corps Times on Peace Corps Botswana's use of OSM and GIS tools for malaria eradication.

- [Alice Deal Middle School's podcast](http://dealmartini.podomatic.com/entry/2015-05-21T18_22_21-07_00) features the GIS club's experience mapping for Peace Corps communities on OSM. May 21, 2015. 



### External Case Studies

- [A Case Study in Eastern Indonesia - Health Mapping in a Low Resource Setting](http://www.ij-healthgeographics.com/content/10/1/15) -- Mostly about HOT, but a great description of the team doing a bunch of work prior to and during the Nepal earthquake.

- [The Internet Mapmakers Helping Nepal - The Atlantic](http://www.theatlantic.com/technology/archive/2015/05/the-mapmakers-helping-nepal/392228/) -- A great overview of the Nepal mappers example.

- [Why Mapping is Important](http://www.wired.com/wiredscience/2013/11/spacial-collective-map-kibera/) -- The 'famous' Kibera example from Kenya.

- [OpenStreetMap: Mapping Power to the People](https://medium.com/@ricaji/openstreetmap-mapping-power-to-the-people-e938c38da93d) -- Promoting the use of mapping from Kibera project lead.




### Topical Maps Showcase

- [Malaria Atlas Project](http://www.map.ox.ac.uk/) -- Disseminates free, accurate and up-to-date information on malaria and associated topics, organized on a geographical basis.

- [HealthMap](http://healthmap.org/en/) --  Real-time intelligence on a broad range of emerging infectious diseases for a diverse audience including libraries, local health departments, governments, and international travelers.

- [Climate Change and African Political Stability Map - Robert Strauss Center](http://ccaps.aiddata.org/climate) -- Comparing climate change to political stability with an Esri map (complete with controls and sliders).



### Fun and Interesting

- [What3words](http://what3words.com/about/) -- A universal addressing system based on a 3mx3m global grid.

- [Map Porn - Reddit](https://www.reddit.com/r/MapPorn/) -- Subreddit devoted to new/interesting maps. Great for inspiration and falling down black holes.

- [Mapillary](http://www.mapillary.com/map) -- Crowd-street Street Views. 

- [What your favorite map projection says about you, a la XKCD](http://xkcd.com/977/) -- Personally, I oscilate between being an upside-down [Peters](https://www.flourish.org/upsidedownmap/) guy and a [Dymaxion](https://en.wikipedia.org/wiki/Dymaxion_map) guy.

- [The Upsidedown Map Page](https://www.flourish.org/upsidedownmap/) -- Site showing different types of maps as 'upside-down'. Awesome resource to use in lessons with students about the cultural and political nature of maps. Which way is 'up'? Why does it feel 'wrong' if indeed it does?



# Advanced



### Guides and Manuals

- [A Guide to Geocoding International Locations](http://www.aaas.org/content/guide-geocoding-international-locations) -- Quite relevant for Peace Corps projects that are trying to clean up a great deal of messy data.

- [Geodata for Development: A Practical Approach (book)](http://www.eisourcebook.org/cms/files/Geodata%20for%20Development,%20A%20Practical%20Approach.pdf) -- A surprisingly good read that walks through a lot of the main issues involved in developing and using maps in the International Development sector.



### Advanced Analysis

- [Spatial Statistics Resources](http://blogs.esri.com/esri/arcgis/2010/07/13/spatial-statistics-resources/) -- From ESRI, offering a list data-mining and statistics in geospatial information.



## Advanced Development 

- [How Web Maps Work - MapBox Guide](http://www.mapbox.com/developers/guide/) -- One page intro that is helpful for the developer (or curious).

- [Great Circles Connections](http://flowingdata.com/2011/05/11/how-to-map-connections-with-great-circles/) -- Mapping connections globally with circle arcs.

- [Leaflet Event Mapping](https://github.com/whichlight/nodejs-leaflet-eventstreams) -- Mapping tweets real time using the streaming location api.

- [Mike Bostock Maps Tutorial (D3)](http://bost.ocks.org/mike/map/) -- Make a modest map from scratch using D3 and TopoJSON.

- [MapBox and Leaflet Primer](http://www.mapbox.com/blog/mapbox-js-with-leaflet/) -- Seamlessly merge tile and vector data (yay!)

- [Mapping with Google Fusion Tables](http://mappingmashups.net/2012/11/29/mapping-with-google-fusion-tables/) -- A little dated but still really relevant mechanism for simply combining GIS data from a Google Fusion Table to a real-time map.

- [Intro to Leaflet from Maptime Boston](http://maptimeboston.github.io/leaflet-intro/) -- Tutorial using Leaflet.

- [Intro to Leaflet from JS Luxembourg](http://luxembourgjs.github.io/leaflet-demo/#/) -- Another tutorial with Leaflet.

- [D3 Bostock Bubble Map](http://bost.ocks.org/mike/bubble-map/) -- Building a simple map with D3.

- [Choropleth Map Example - USA](http://bl.ocks.org/mbostock/4060606) -- Beautiful example from Mike Bostock (D3 creator) that shows the code and raw data for creating a choropleth map (color-gradient map).

- [Datamaps](http://datamaps.github.io/) -- Customizable SVG map visualizations for the web in a single Javascript file using D3.js

- [ModestMaps](http://modestmaps.com/) -- Small Mapping Framework

- [PolyMaps](http://polymaps.org/) -- JavaScript Maps Library.

- [Easey](https://www.mapbox.com/easey/) --  Map animation library. It works with Modest Maps and provides advanced easing as well as inertial panning and zooming.

- [Animated Choropleths](http://rmaps.github.io/blog/posts/animated-choropleths/) -- Step-by-step approach to creating an animated, interactive choropleth map using rMaps and DataMaps.



### Advanced Tools and Services

- [Topojson](https://github.com/mbostock/topojson/wiki) -- Extension of JSON for topography.

- [Mapshaper - GeoJSON and TopoJSON](http://www.mapshaper.org/) -- Tools for editing geospatial vector data.

- [Distillery](http://shancarter.github.io/distillery/) -- Simplify geoJSON at variable rates.




### Showcase Map Examples
 
- [Syria Tracker](https://syriatracker.crowdmap.com) -- a Project of Humanitarian Tracker Crowdsourcing the Syrian Conflict since April 2011.

- [Mapping Latinos in the US](http://developmentseed.org/blog/2011/oct/10/mapping-latinos-united-states-npr/) -- Example from DevelopmentSeed (the rock stars of data in the development sector).



---



## Opportunities for Volunteers to work in GIS

### Pre-Departure

Use [OpenStreetMap](http://www.openstreetmap.org/#map=13/-6.1842/25.1807&layers=Q) to explore country roads and structures. If Community-Based Training (CBT) sites are known, look to see how much (or little) of the roads and buildings are accounted for when compared to satellite imagery.

For smartphones, look at apps like [OSMAND](http://osmand.net/) (Android) and [Galileo](https://galileo-app.com/) (iOS) -- Apps that access and store OSM data. Map data can be stored on your device's memory card for offline use.

### Trainees

What are the various instances where mapping your community is helpful, and how could these be supplemented through digital maps?

During site visit and various travel, are there opportunities to assess your whereabouts. These include:

- Ability to identify and record GPS coordinates (smartphone, GPS devices),
- Areas where there is voice and data connectivity (and where there isn’t),
- Routing to your town/site/house provided by adequate road and travel data (door-to-door),
- Routing to/from consolidation points and emergency locations, dangerous areas in the CBT site, in the capital for travel, on site visit, etc.,

### Volunteers

In the first three months, Volunteers will want to ensure that they have adequately documented and confirmed their **Site Locator Form** and that they have discussed/approved it through the appropriate channels.

More coming soon to the Field Guide!


 