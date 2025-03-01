# Awesome ONE Record

> A curated list of awesome resources related to the ONE Record standard.

## Table of Contents
* [About ONE Record](#about-one-record)
* [Community Resources](#community-resources)
* [Good Practices](#good-practices)
* [Software Packages](#software-packages)
* [Cloud Services](#cloud-services)
* [Professional Services](#professional-services)

### About ONE Record
*ONE Record is a standard for data sharing and creates a single record view of the shipment. This standard defines a common data model for the data that is shared via standardized and secured web API.   
(Source: [IATA - ONE Record](https://www.iata.org/one-record/))*

### ONE Record Specifications

* [ONE Record Specification Repository](https://github.com/IATA-Cargo/ONE-Record)
* [ONE Record API Specification](https://iata-cargo.github.io/ONE-Record/)
* [ONE Record Data Model](https://iata-cargo.github.io/ONE-Record/stable/Data-Model/)
* [ONE Record Data Orchestration](https://github.com/IATA-Cargo/ONE-Record/tree/master/working_draft/Data-Orchestration)


### Community Resources

#### Tutorials
* [First Steps with NE:ONE Server](https://github.com/ddoeppner/one-record-server-first-steps) A step-by-step guide to setting up a local ONE Record development environment with NE:ONE Server, GraphDB, Keycloak, NE:ONE View, and NE:ONE Play, as well as creating and updating your first LogisticsObjects.

#### Whitepapers
* [IATA (2020) Catch the Wave of Linked Data with ONE Record](https://www.iata.org/contentassets/a1b5532e38bf4d6284c4bf4760646d4e/one_record_catch_the_wave_of_linked_data_with_one_record.pdf)
* [IATA (2021) Bridging the Internet of Logistics with the ONE Record API](https://www.iata.org/contentassets/a1b5532e38bf4d6284c4bf4760646d4e/one_record_bridging_the_internet-of_logistics_with_the_one_record_api.pdf)


#### Blog Posts
* [Vedia](https://www.vedia.fi/blog/one-record-gateway-to-the-internet-of-logistics/) One Record – gateway to the internet of logistics

#### Videos
* [InTouch TV (2020) ONE Record one step away from fully digital cargo](https://www.youtube.com/watch?v=JPzkqsD3HQo)
* [InTouch TV (2020) The ONE Record API An overview of the key features](https://www.youtube.com/watch?v=8EMtdKyNuog)
* [IATAtv (2020) IATA ONE Record Hackathon 2020](https://www.youtube.com/watch?v=XOxeL1WXOiM)
* [IAM Video Channel (2024) - IAM Session: Let's Move Some Data! Transforming Moving with Next Generation Data Exchange](https://www.youtube.com/watch?v=Iap9QHRyS6w)


#### Hackathons
* [IATA ONE Record Hackathon June 2019](https://www.iata.org/contentassets/c6b62a2a403745ddab9b593b3a664b08/madrid-hackathon-winners.pdf) Corporate Booking Tools using Airlines (NDC) APIs and Cargo processes using IATA’s One Record API. June 2019 in Madrid
* [IATA ONE Record Hackathon September 2020](https://onerecord.devpost.com/project-gallery). 11-13 September 2020 (online only)
* [IATA ONE Record Hackathon September 2021](https://onerecord2021.devpost.com/). 10-12 September 2021 (online only)
* [IATA ONE Record Hackathon May 2022](https://iata-dcsa-ams.devpost.com/). 20-22 May 2022 in Amsterdam.
* [IATA ONE Record Hackathon September 2022](https://onerecord-yyz.devpost.com/). 21-23 October 2022 in Toronto
* [IATA ONE Record Hackathon June 2023](https://onerecord-fra.devpost.com/). 23-25 June 2023 in Seeheim
* [IATA ONE Record Hackathon November 2023](https://onerecord-doh.devpost.com/). 24-26 November 2023 in Doha
* [IATA ONE Record Hackathon March 2024](https://onerecord-szx.devpost.com/). 15-17 March 2024 in Shenzhen
* [IATA ONE Record Hackathon October 2024](https://onerecord-ist.devpost.com/). 5-6 October 2024 in Istanbul
* [IATA ONE Record Hackathon February 2025](https://onerecord-dub.devpost.com/). 24-25 February 2025 in Dublin


### Good Practices
*This section lists resources that describe what an implementation of a use case in ONE Record might look like in what is called good practice.*

* [Good Practice: ShipmentTracking](https://github.com/digital-cargo/good-practice-shipment-tracking)
* [Good Practice: ShipmentRecord](https://github.com/digital-cargo/good-practice-shipment-record)
* [Good Practice: TruckPreAdvice](https://github.com/digital-cargo/good-practice-truck-preadvice)
* [Providing CO2 Transparency in ONE Record](https://github.com/DrPhilippBillion/Co2-Transparency-in-ONE-Record)
* [Checks in ONE Record](https://github.com/DrPhilippBillion/Checks-in-ONE-Record)
* [Digital Accompanying Documents](https://github.com/DrPhilippBillion/Digital-Accompanying-Documents-in-ONE-Record)
* [ServiceOptionRequest in ONE Record](https://github.com/NiclasScheiber/ServiceOptionRequest-in-ONE-Record)


### Software Packages

#### Tools

* [Cargo-XML XFWB / XFZB to ONE Record Converter](https://github.com/riege/one-record-converter) Java library that supports the conversion from xFWB / xFZB to ONE Record JSON data format
* [one-record-ontologymodel](https://github.com/riege/one-record-ontologymodel) Java POJO classes for the ONE Record data model
* [ONE Record with Python](https://pypi.org/project/onerecord/) Python library for interaction with ONE Record APIs
* [NE:ONE Play - ONE Record Editor](https://github.com/erikgoldenstein/neoneplay) Interactive web app to view and edit ONE Record data objects based on React Flow
* [SPARQLing ONE Record Middleware Server](https://github.com/NiclasScheiber/sparqling-one-record) Python-based web API to execute SPARQL queries on ONE Record data using the ONE Record API)
* [ONE Record Ontology Visualizer](https://iata-cargo.github.io/ontology_visualizer/) Interactive web app to view and explore the ONE Record Data Model Ontology.


#### Reference Implementations
*Software bundles that implement all or parts of the ONE Record specification (data model, API, security).*

* [NE:ONE - opeN sourcE: ONE record server software](https://git.openlogisticsfoundation.org/digital-air-cargo/ne-one) Open Source ONE Record Server implementation by [Digital Testbed Air Cargo (DTAC)](https://www.digital-testbed-air-cargo.com)
* [ONE Record Server Java Sandbox](https://github.com/IATA-Cargo/one-record-server-java) JAVA implementation of the ONE Record API by IATA.
* [ONE Record Server (Go + GCP)](https://github.com/chi-deutschland/one-record-server) Go implementation of the ONE Record API. Deployable to the Google Cloud Platform.


### Cloud Services
*Software products that provide ONE Record services and are operated and maintained by 3rd parties in the cloud.*

* [Nexshore](https://nexshore.com/) SaaS solution for Air Cargo Tracking based on ONE Record


### Professional Services
*Commercial service offerings to support organizations in the technical and organizational implementation of ONE Record*.

* [ISO Software Systeme GmbH (ISO Gruppe)](https://www.one-record-hub.com/) 


# Code of Conduct
see [Code of Conduct](CODE_OF_CONDUCT.md)

# Contributing
Your contributions are always welcome. [Please be so kind to follow these guidelines](CONTRIBUTING.md).

# License
[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
