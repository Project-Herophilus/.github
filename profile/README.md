# Background
Welcome to Project Herophilus, Herophilus was a Greek physician who was an anatomist and credited with being the founder 
of Anatomy. Why would we have chosen this name for our project? Our intent and goal is to lead by example by showing the 
ways platforms and/or innovation with healthcare data and systems integration can be modernized while introducing integration and 
application development as side by side efforts. 

Our mission is to be a premier healthcare community focused on enabling healthcare care to solve data 
challenges and problems. The way we plan on enabling this is through open source. Our decision to be completely open 
is based on what we have seen in the last decade, open source has powered ALL significant software innovation. 
Here is a <a href="https://www.redhat.com/rhdc/managed-files/rh-enterprise-open-source-report-f27565-202101-en.pdf" target="_blank">report</a> 
that showcases all the various ways open source and it's culture are transforming its importance to enterprises and the way 
new innovation is being delivered. While there are many industries that have benefited from opensource there is no 
industry that has potentially benefited more than Healthcare. For many decades it has also relied upon community development 
in areas such as treatment protocols, safety standards, and industry standards based data formats. Now, as we head into a 
new era driven by consumption and secure managed services it is a perfect time in healthcare for open source and
healthcare.

The vision, supporting our mission, helps drive data driven open source capabilities into healthcare while 
demonstrating how healthcare can leverage open source to solve industry problems. In order to deliver our vision and help 
healthcare it was critical that we define [specific design principles](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Platform-Content/Design/DesignPrinciples.md) 
to ensure a very [scalable, extensible and reusable architecture](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Platform-Content/Design/Architecture.md) 
with a focus on enabling specific [capabilities](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Platform-Content/Design/Capabilities.md). 

What differentiates Project Herophilus is our focus and intent to enable unifying siloed areas life developers, data integration, 
application integration, data and data scientists with a cohesive ecosystem approach to solving problems. To help with 
consistency we created a [fictitious organization](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Platform-Content/General/FictitiousOrg.md) and ensure we
can accurately define and relate any solutions being developed. When it comes to data integration there are a set of 
[industry based integration standards support](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Platform-Content/Design/IntegrationStandardsSupported.md) 
and non industry standard data challenges.

At Project Herophilus, we [leverage industry leading open source technologies](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Platform-Content/Technical/Technologies.md) 
to help us bring the most widely adopted and used capabilities to bear. Assets currently available provide tools for 
configuration, testing, legacy and modern data integration, modern application integration, application development, synthetic data, and more. 
All of these assets are available to any organization. The sole purpose of ALL the capabilities we have built for healthcare 
is to focus on enabling <b> Data as an Asset</b>

Feel free to look at our [roadmap](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Platform-Content/Roadmap/index.md), it is updated monthly and remember all the assets are available and provided under Apache 2 licensing.

# Key Overall Project Capabilities Provided 
As we built this platform out there are an extensive set of capabilities. We have tried to seperate those into categories.

## Healthcare Integration Capabilities
While there are a ton of very specific features and capabilities provided the platform and use cases it supports there 
are some very basic overall capabilities.

| Capability                                | Details                                                                                                                                        |
|-------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------|
| Cloud Native Purpose Built Design         | Designed and built from the ground up to run on multiple types of platforms: physical, virtual, devices, container based, and/or public cloud. |
| Administrative Management User Interface | Any integrated asset features a consistent user interface.                                                                                     |
| Event Driven Architecture Focused         | Every platform supports a consistent event driven architecture focused around application and data integration.                                |                                                                                                                        |
| Integrated Auditing                       | A consistent auditing platform and event structure.                                                                                            |
| Third Party Tool Support                  | Implementations are able to use third party tools like mapping tools, APIs or other technologies                                               |
| Configuration Based Platform              | All aspects of the platform are configuration based for ease of extensibility and reuse.                                                       |
| Industry Connectivity - FHIR Servers      | Several FHIR servers and cloud SaaS are natively supported and have been tested.                                                               |
| Data Simulators                           | Ability to test implementations with sample data and performance test implementation components                                                |

### Data Integration Standards Support

| Industry Std. | Details                                                                                                                                                                                                                                                                                  |
|---------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| HL7 v2        | Ability to process the 9 most common HL7 v2x messages from any vendor using Files, MLLP, or HTTP are supported. Specific details can be found [here](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Platform-Content/Design/IntegrationStandardsSupported.md) |
| CCDA          | Ability to process the CCDA messages from any vendor using Files, or HTTP are supported.                                                                                                                                                                                                 |
| FHIR          | Ability to process all FHIR Resources from any vendor using Files, or HTTP are supported. Specific details can be found [here](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Platform-Content/Design/IntegrationStandardsSupported.md)                       |
| EDI           | Ability to process all EDI 5010 transactions from any vendor using Files, or HTTP are supported.                                                                                                                                                                                         |

There are other potentials that can be implemented like ePrescribe. This implementation would be similar to EDI.

### Core Capabilities Support
All the following capabilities are provided within each repository and/or sub-module as settings or properties.

| Capability                                    | Details                                                                     |
|-----------------------------------------------|-----------------------------------------------------------------------------|
| Automated Conversion to FHIR                  | HL7v2 and CCDA to FHIR are in place as of 5/2021                            |
| Terminology Mediation/Management              | Persistence of terms, basic mapping with external vendor API support coming |
| Public Cloud Integration PaaS/SaaS components | AWS Support as of 7/22, Azure and GCP Efforts being accessed                |
| FHIR Data Persistence Tier                    | Coming October 2022                                                         |


### Mandated Integration Capabilities Support
All the following capabilities are provided within each repository and/or sub-module as settings or properties.

| Capability                                                                            | Supported Capabilities Repository                                                                                  |
|---------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------|
| [CARIN IG](http://build.fhir.org/ig/HL7/carin-bb/)                                    | [iDaaS Connect BlueButton](https://github.com/Project-Herophilus/iDaaS-Connect/tree/main/iDaaS-Connect-BlueButton) |
| [Davinci PDEX](http://hl7.org/fhir/us/davinci-pdex/)                                  | [iDaaS Connect FHIR](https://github.com/Project-Herophilus/iDaaS-Connect/tree/main/iDaaS-Connect-FHIR)             |
| [Davinci DGEX](http://hl7.org/fhir/us/davinci-pdex/)                                  | [iDaaS Connect FHIR](https://github.com/Project-Herophilus/iDaaS-Connect/tree/main/iDaaS-Connect-FHIR)             |
| [US CDI](https://www.healthit.gov/isa/united-states-core-data-interoperability-uscdi) | [iDaaS Connect FHIR](https://github.com/Project-Herophilus/iDaaS-Connect/tree/main/iDaaS-Connect-FHIR)                                                                                             | 

#### Mandated Integration Capabilities Under Review
The following capabilities being evaluated for implementation into the core capabilities we provide.

| Capability                                                       |
|------------------------------------------------------------------|
| [Davinci DQEX](https://build.fhir.org/ig/HL7/davinci-deqm/) |
| [Davinci CDEX](http://hl7.org/fhir/us/davinci-cdex/history.html) |


### Key Scenarios Support
The following scenarios are enabled by potentially any or all the features above.

| Capability                  | Details                                                                                                                                                    |
|-----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| FHIR R4 Support             | Currently supports all FHIR resources processing. This can be to public cloud or on premise FHIR servers or not. All based on configuration settings used. |
| SMART on FHIR Support       | Coming November 2022                                                                                                                                       |
| CDS Hooks                   | Coming November 2022                                                                                                                                       |
| Health Plan Price Transparency | Coming December 2022                                                                                                                                       |
| SDOH Data Support           | Coming December 2022                                                                                                                                       |
| Sharing dynamic data        | Coming December 2022                                                                                                                                       |

### Base Repositories 
These repositories will help with core implementation needs.

| Repository Name | Description |
| ------ | ------------|
|[iDaaS Connect](https://github.com/Project-Herophilus/iDaaS-Connect)|Connecting to all types of data and providing access to information in near realtime. It is intended to be a comprehensive set of design patterns, reference architecture, accelerators to help anyone and supports hundreds of connectors from legacy to modern connectivity to industry standards to various public clouds connectivity needs.|
|[iDaaS KIC](https://github.com/Project-Herophilus/iDaaS-KIC)|Knowledge, Insight and Conformance is all about providing the ability to process errors, audit and other data. This consists of the endpoints, processing and persistence needed to support the platform.|
|[iDaaS Data Simulators](https://github.com/Project-Herophilus/iDaaS-DataSimulators)| Having data is one aspect, the other is having tooling that can quickly be configured and used to test components. We have developed data-simulators for our core components, Simulators to help in implementation and testing.  |   

## Application Development Capabilities
While there are a ton of very specific features and capabilities provided the platform and use cases it supports there

### Supporting Repositories 
Custome application development efforts that support leveraging existing integrated assets are available to assist 
provide additional capabilities for any implementation : <br/>

| Repository Name                                                                             | Description |
|--------------------------------------------| ------------|
| [Event Builder](https://github.com/Project-Herophilus/Event-Builder)| A comprehensive library for parsing and building various types of healthcare industry standards based data.|
| [iDaaS DREaM](https://github.com/Project-Herophilus/iDaaS-DREAM)                            |Assets designed from multiple technologies that serve a variety of purposes from routing of data to data transformation to business driven data assets.|
| [Synthetic Data](https://github.com/Project-Herophilus/DataSynthesis)                       | When it comes to building or testing assets, having lots of data to resemble your production data is critical, it also helps drive innovation. We have open sourced a synthetic data platform and continue to enhance it based on feedback. It currently contains over 18 billion specific data attributes that can be used |
| [De-Identification or Anonymization of Data](https://github.com/Project-Herophilus/Defianz) |Providing the capability to de-identify or anonymize data |

## Other Repositories
Here are some other repositories our project offers to help support all the assets provided.

| Add-On | Description |
| ------ | ------------|
| [Project Herophilus Technical Content](https://github.com/Project-Herophilus/Project-Herophilus-Assets) | Variety of content specific to iDaaS - PowerPoints, Word Docs, and Draw.IO diagrams|
| [Test Data](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Testing)  | Test data for all healthcare industry standards work|


# Key Links
Below are some key links that are contained within the content. We wanted to provide a section for some common and consistent critical content areas:

* [Fictitious Organization](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Platform-Content/General/FictitiousOrg.md)
* [Design Principles](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Platform-Content/Design/DesignPrinciples.md)
* [Reusable Architecture](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Platform-Content/Design/Architecture.md)
* [Capabilities](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Platform-Content/Design/Capabilities.md)
* [Integration Standards Supported](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Platform-Content/Design/IntegrationStandardsSupported.md)
* [Open Source Technologies Used](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Platform-Content/Technical/Technologies.md)                 

