# Healthcare Data Integration Capabilities
Within the Herophilus community we have tried to ensure and focus on providing comprehensive capabilities that
match what numerous vendors have developed and delivered.

## Base Capabilities

| Capability                                | Details                                                                                                                                   |
|-------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| Cloud Native Purpose Built Design         | Designed and built from the ground up to run on multiple types of platforms: physical, virtual, devices, container based, and/or public cloud. |
| Administrative Management User Interface | Any integration based asset features a consistent management interface.                                                                   |
| Event Driven Architecture Focused         | Every platform supports a consistent event driven architecture focused around application and data integration.                           |                                                                                                                        |
| Integrated Auditing                       | A consistent auditing platform and event structure.                                                                                       |
| Third Party Tool Support                  | Implementations are able to use third party tools like mapping tools, APIs or other technologies                                          |
| Configuration Based Platform              | All aspects of the platform are configuration based for ease of extensibility and reuse.                                                  |
| Industry Connectivity - FHIR Servers      | Several FHIR servers and cloud SaaS are natively supported and have been tested.                                                          |
| Data Simulators                           | Ability to test implementations with sample data and performance test implementation components                                           |

### Data Integration Standards Support
While the capabilities we provide are very specific to healthcare industry needs we also have very
base level support for capabilities like files, relational databases and other data needs that are very commonly used.

| Industry Std. | Details                                                                                                                                                                                                                                                                                  |
|---------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| HL7 v2        | Ability to process the 9 most common HL7 v2x messages from any vendor using Files, MLLP, or HTTP are supported. Specific details can be found [here](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Platform-Content/Design/IntegrationStandardsSupported.md) |
| CCDA          | Ability to process the CCDA messages from any vendor using Files, or HTTP are supported.                                                                                                                                                                                                 |
| FHIR          | Ability to process all FHIR Resources from any vendor using Files, or HTTP are supported. Specific details can be found [here](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Platform-Content/Design/IntegrationStandardsSupported.md)                       |
| EDI           | Ability to process all EDI 5010 transactions from any vendor using Files, or HTTP are supported.                                                                                                                                                                                         |

There are other potentials that can be implemented like ePrescribe. This implementation would be similar to EDI.

### Core Integration Capabilities Support
All the following capabilities are provided within each repository and/or sub-module as settings or properties.

| Capability                                    | Details                                                                                                           |
|-----------------------------------------------|-------------------------------------------------------------------------------------------------------------------|
| Automated Conversion to FHIR                  | HL7v2 and CCDA to FHIR are in place as of 5/2021                                                                  |
| Terminology Mediation/Management              | Persistence of terms, basic mapping with external vendor API support coming                                       |
| Public Cloud Integration PaaS/SaaS components | AWS Support as of 7/22, Azure and GCP efforts coming soon                                                         |
| Data Tier SaaS Support                        | Enables implementation based capabilities to work with SaaS data providers like SnowFlake, MongoDB and DataBricks |

### Mandated Integration Capabilities Support
All the following capabilities are provided within each repository and/or sub-module as settings or properties. Keep in mind this is a general
platform so there is NOT 100 percent build out of comprehensive support. In some cases the components are in place but need to be stictched into
industry or implementation centric offerings that partner/customer already have running. This allows the greatest flexibility and extensibility.

| Capability                                                                            | Supported Capabilities Repository                                                                    |
|---------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------|
| [CARIN IG](http://build.fhir.org/ig/HL7/carin-bb/)                                    | [CMS-BlueButton](https://github.com/Project-Herophilus/iDaaS/Connect/tree/main/cms-blue-button) |
| [Davinci CDEX](http://hl7.org/fhir/us/davinci-cdex/history.html) | [CMS-Interoperability](https://github.com/Project-Herophilus/iDaaS-Connect/tree/main/cms-interoperability) |
| [Davinci DGEX](http://hl7.org/fhir/us/davinci-pdex/)                                  | [CMS-Interoperability](https://github.com/Project-Herophilus/iDaaS-Connect/tree/main/cms-interoperability) |
| [Davinci PDEX](http://hl7.org/fhir/us/davinci-pdex/)                                  | [CMS-Interoperability](https://github.com/Project-Herophilus/iDaaS-Connect/tree/main/cms-interoperability) |
| [US CDI](https://www.healthit.gov/isa/united-states-core-data-interoperability-uscdi) | [FHIR](https://github.com/Project-Herophilus/iDaaS-Connect/tree/main/iDaaS-Connect-FHIR)                                     | 
