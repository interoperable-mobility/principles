## Definitions

<a name="mobility_technology_component"></a>
[**Mobility Technology Component**](#mobility_technology_component)
:   Any hardware or software component that is used  to:  

     - Plan journeys (e.g.  journey planning applications),
    Provide mobility information to travelers (e.g. travel alerts, arrival predictions, LED signage, public address systems),  
     - Conduct transactions between [mobility providers](#mobility_provider) and travelers (e.g. reservation requests, ticketing, payments, stop request buttons)   
     - Facilitate the duties of drivers, operators or other on-board staff (e.g. communications hardware or software, Mobile Data Terminals, tablets, driver interface software),  
     - Facilitate the duties of dispatch, supervisory, or scheduling staff (e.g. scheduling software, CAD/AVL software, SCADA, APC), and  
     - Manage the mobility system (e.g. performance reporting, shift selection, non-revenue schedules)

<a name="mobility_data"></a>
[**Mobility Data**](#mobility_data)
:   Data used by any mobility technology component to execute its core functions.

<a name="mobility_technology_system"></a>
[**Mobility Technology System**](#mobility_technology_system)
:   An assemblage of mobility technology components whose functionality is dependent on another component. 

<a name="interoperability"></a>
[**Interoperability**](#interoperability)
:   The ability for any mobility technology component to exchange data in an [open standard](#open_standard) or schema with other components in that system.

<a name="mobility_provider"></a>
[**Mobility Provider**](#mobility_provider)
:   Any organization that transports people or directly facilitates transport (e.g. a public transportation agency, a private tour bus, vehicle share, rideshare, or a non-emergency medical transportation (NEMT) company).

<a name="transportation_technology_company"></a>
[**Transportation Technology Company**](#transportation_technology_company)
:   Any organization that provides a Mobility Technology Component.

<a name="transportation_system_manager"></a>
[**Transportation System Manager**](#transportation_system_manager)
:   Any organization that:  

     - Coordinates the service of multiple mobility providers (e.g. some MPOs, local governments, regional transit providers or state DOTs),  
     - Procures or regulates the services of a third-party mobility provider (e.g. a local city contracting with a micro-mobility service),  
     - Maintains (or funds the maintenance of) physical infrastructure used by transit providers to transport people (e.g. local, state or federal departments of transportation), or  
     - Receives legally mandated reports from transit providers in order to maintain service quality, safety, and efficiency (e.g. utilities oversight bodies, safety boards, or other government or nonprofit bodies).

<a name="open_standard"></a>
[**Open Standard**](#open_standard)
:   A specific ontology, schema, or format used by the mobility industry in order to facilitate the consistent communication of information between devices which is:  

     - Free from cost and restrictions to use, 
     - Publicly [documented](#documented_format) in its entirety, 
     - Actively maintained by an independent organization,  
     - Contains structured releases, versions, or changelogs, and 
     - Has an open community of contributors and users, and transparent, inclusive governance.

	Examples include the General Transit Feed Specification (GTFS), Mobility Data Specification (MDS), OpenStreetMap (OSM),  and General Bikeshare Feed Specification (GBFS).  

## Clarifications
<a name="open_standard_list"></a>
???+ question "Where can I find a list of all the appropriate open standards? <br>What does it mean to be a *proposed* open standard (and where would I find them?)" 

???+ question "What does it mean to be compatible with open standards ?"

<a name="documented_format"></a>
???+ question "What is a documented data format? <br>How should schemas and APIs be documented? <br>What are appropriate language-neutral, machine-readable formats for documenting data schemas and APIs?"
    An appropriately-documented data format is:

     - Documented in its entirety on a public webpage in human-readable form
     - Documented in a language-neutral, machine-readable format at a [permalink](https://en.wikipedia.org/wiki/Permalink) in a format applicable to the following categories of schemas:
         - API: [OpenAPI](https://spec.openapis.org/oas/latest.html)
         - Tabular data schemas(i.e. csvs): [frictionless](https://frictionlessdata.io/standards/) data table, data resource or data package
         - Tagged data schemas: [json-schema](https://json-schema.org/)
     - Use structured releases, versions, or changelogs. 

<a name="publish"></a>
???+ question "What does it mean to *publish* data?"
    Data which is “published” shall be available either at a [permalink](https://en.wikipedia.org/wiki/Permalink) or via a [documented](#documented_format) API. Access to published data could require automatically-generated API keys. 

<a name="programmatic_access"></a>
???+ question "What is fully capable programmatic access?”
    Programmatic access is a method which allows a computer (program) to exchange information and commands rather than requiring a human to intervene.  Examples of programmatic access include  Application Programming Interfaces (APIs), webhooks, and direct database access.   Fully capable programmatic access implies that actions that human users can perform through a graphical user interface should also be available to transit providers and other transit technology components through these programmatic means. 

<a name="purpose"></a>
???+ question "What is the purpose of these principles compared to documents like the [California Minimum GTFS Guidelines](https://dot.ca.gov/cal-itp/california-minimum-general-transit-feed-specification-gtfs-guidelines), etc."

    __Overall System vs Specific Component__: The Mobility Data Interoperability Principles address high-level needs in order to achieve an overall [systems](#mobility_technology_system) which operates on and leverages interoperable data, whereas the California Minimum GTFS Guidelines provides the details about how to achieve this interoperability for a particular data transaction (rider-facing information).  Many of the sub-systems could have more specific implementation guidelines in the future which would list specific open standards to employ, etc. <p><br>
    __Collective vs California__: The Mobility Data Interoperability Principles Represents the collective perspective of a significant portion of the mobility ecosystem whereas the [California Minimum GTFS Guidelines](https://dot.ca.gov/cal-itp/california-minimum-general-transit-feed-specification-gtfs-guidelines), while built on top of collective documents such as GTFS Best Practices, are managed by Caltrans and represent an expectation which is based off of specific support which Caltrans intends to provide. 
