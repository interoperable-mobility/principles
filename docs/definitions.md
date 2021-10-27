# Definitions

<a name="mobility_data"></a>
**Mobility Data**
:   Data used by any [mobility technology component](#mobility_technology_component) to execute its core functions.

<a name="interoperability"></a>
**Interoperability**
:   The ability for any [mobility technology component](#mobility_technology_component) to exchange data in an [open standard](#open_standard) or schema with other components in that [mobility technology system](#mobility_technology_system).

<a name="mobility_service_provider"></a>
**Mobility Service Provider**
:   Any organization that transports people or directly facilitates transport (e.g. a public transportation agency, a private tour bus, vehicle share, rideshare, or a non-emergency medical transportation (NEMT) company).

<a name="mobility_technology_component"></a>
**Mobility Technology Component**
:   Any hardware or software component that is used  to:  

     - Plan journeys (e.g.  journey planning applications),  
     - Provide mobility data to travelers (e.g. travel alerts, arrival predictions, LED signage, public address systems),  
     - Conduct transactions between [mobility providers](#mobility_service_provider) and travelers (e.g. reservation requests, ticketing, payments, stop request buttons)   
     - Facilitate the duties of drivers, operators or other on-board staff (e.g. communications hardware or software, Mobile Data Terminals, tablets, driver interface software),  
     - Facilitate the duties of dispatch, supervisory, or scheduling staff (e.g. scheduling software, CAD/AVL software, SCADA, APC), and  
     - Manage the mobility system (e.g. performance reporting, shift selection, non-revenue schedules), and
     - Collect and/or compute traveler feedback (e.g. crowdsourcing of incidents, accidents, delays, on-board crowd levels, comfort, condition of stops and/or vehicles).  

<a name="mobility_technology_system"></a>
**Mobility Technology System**
:   An assemblage of [mobility technology components](#mobility_technology_component) whose functionality is dependent on another component.

<a name="transportation_technology_company"></a>
**Transportation Technology Company**
:   Any organization that provides a [Mobility Technology Component](#mobility_technology_component) to a Transit Agency or a Mobility Service Provider.

<a name="transportation_system_manager"></a>
**Transportation System Manager**
:   Any organization that:  

     - Coordinates the service of multiple transit agencies or other [mobility service providers](#mobility_service_provider) (e.g. some MPOs, local governments, regional transit providers or state DOTs), 
     - Procures or regulates the services of a third-party [mobility service provider](#mobility_service_provider) (e.g. a local city contracting with a micro-mobility service),  
     - Maintains (or funds the maintenance of) physical infrastructure used by transit agencies or other [mobility service providers](#mobility_service_provider) to transport people (e.g. local, state or federal departments of transportation), or  
     - Receives legally mandated reports from transit providers in order to maintain service quality, safety, and efficiency (e.g. utilities oversight bodies, safety boards, or other government or nonprofit bodies).

<a name="open_standard"></a>
**Open Standard**
:   A specific ontology, schema, or format used by the mobility industry in order to facilitate the consistent communication of information between devices which is:  

     - Free from cost and restrictions to use,
     - Publicly documented in its entirety,
     - Actively maintained by an independent organization whose business interests are not actually - and would not reasonably give the appearance of being potentially - impacted by the contents of the standard, 
     - Contains structured releases, versions, or changelogs, and
     - Has an open community of contributors and users, and transparent, inclusive governance.  

     Examples include the General Transit Feed Specification (GTFS), Mobility Data Specification (MDS), and General Bikeshare Feed Specification (GBFS). 

<a name="proposed_open_standard"></a>
**Proposed Open Standard**
:    Any specific ontology, schema, or format that:  

     - Meets all the criteria of an [open standard](#open_standard),  
     - Has been transitioned to maintenance by an independent organization,  
     - Has at least one stable release as determined by the maintaining independent organization, and  
     - Has not met the standards for adoption as determined by the maintaining independent organization.

<a name="open_standard_compatibility"></a>
**Open Standard Compatibility**
:   Refers to the ability of a [mobility technology component](#mobility_technology_component) to publish valid open standards with data stored or handled by the components and to ingest valid open standards.

<a name="published_data"></a>
**Published Data**
:   Data that is available either at a permalink or via a documented application programming interface (API), access to which may require automatically-generated API keys.

<a name="programmatic_access"></a>
**Programmatic Access**
:   A method of accessing information in which computer programs are permitted to exchange information and commands rather than requiring human intervention (e.g. APIs, webhooks, and direct database access).  

<a name="fully_capable_programmatic_access"></a>
**Fully Capable Programmatic Access**
:   The ability of transit agencies, other [mobility service providers](#mobility_service_provider), and [mobility technology components](#mobility_technology_component) to perform by means of programmatic access any actions that human users can perform by means of a graphical user interface.

<a name="documented_data_format"></a>
**Documented Data Formats**
:   A format that:
     - Is documented in its entirety on a public webpage in human-readable form  
     - Is documented in a language-neutral machine-readable format at a permalink in a format applicable to the following categories of schemas:  
       - API: [OpenAPI](https://www.openapis.org/)  
       - Tabular data schemas(i.e. csvs): [frictionless data table, data resource or data package](https://frictionlessdata.io/standards/)  
       - Tagged data schemas: [json-schema](https://json-schema.org/), or [XML schema definition](https://en.wikipedia.org/wiki/XML_Schema_(W3C))  
     - Uses structured releases, versions, or changelogs.  

