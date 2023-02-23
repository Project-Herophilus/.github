# Background
Welcome to Project Herophilus, Herophilus was a Greek physician who was an anatomist and credited with being the founder 
of Anatomy. Why would we have chosen this name for our project? Our intent and goal is to lead by example by showing the 
ways platforms and/or innovation with healthcare data and systems integration can be modernized while introducing integration and 
application development as side by side efforts. 

Our mission is to be a premier healthcare community focused on enabling healthcare care to solve data 
challenges and problems. The sole purpose of ALL the capabilities we have built for healthcare
is to focus on enabling <b> Data is the Asset</b> Everything we do is all intended to fall under what we have branded Healthcare Data Foundation (HDF). The way we plan on enabling this is through open source. Our decision to be completely open 
is based on what we have seen in the last decade, open source has powered ALL significant software innovation. 
Here is a <a href="https://www.redhat.com/rhdc/managed-files/rh-enterprise-open-source-report-f27565-202101-en.pdf" target="_blank">report</a> 
that showcases all the various ways open source and it's culture are transforming its importance to enterprises and the way 
new innovation is being delivered. While there are many industries that have benefited from open source there is no 
industry that has potentially benefited more than Healthcare. For many decades it has also relied upon community development 
in areas such as treatment protocols, safety standards, and industry standards based data formats. Now, as we head into a 
new era driven by consumption and secure managed services it is a perfect time in healthcare for open source and
healthcare.  Our goal is to [leverage industry leading open source technologies](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Platform-Content/Technical/Technologies.md) to help us bring the most widely adopted and used capabilities. Assets currently available provide tools for
configuration, testing, legacy and modern data integration, modern application integration, application development, synthetic data, and more.
All of these assets are available to any organization.

The vision, supporting our mission, helps drive data driven open source capabilities into healthcare while 
demonstrating how healthcare can leverage open source to solve industry problems. In order to deliver our vision and help 
healthcare it was critical that we define [specific design principles](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Platform-Content/Design/DesignPrinciples.md) 
to ensure a very [scalable, extensible and reusable architecture](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Platform-Content/Design/Architecture.md) 
with a focus on enabling specific [capabilities](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Platform-Content/Design/Capabilities.md). 
To help us better tell the industry challenges better we created a [fictitious organization](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Platform-Content/General/FictitiousOrg.md) and ensure we can accurately define and relate any solutions being developed. When it comes to data integration there are a set of 
[industry based integration standards support](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Platform-Content/Design/IntegrationStandardsSupported.md) 
and non industry standard data challenges.

Apart from the links above here are some other key points about our community and what we are working
towards.
- We want everyone to join our [community](https://github.com/Project-Herophilus/Project-Herophilus-Assets/edit/main/Platform-Content/General/CodeOfConduct.md) and would love whatever contributions resources are comfortable providing. These 
could be code, content, project management, executive steering or in the form of many other activities. We hope you
can help us continually improve in any manner you deem needed.
- Take a look at the [consulting partners](https://github.com/Project-Herophilus/Project-Herophilus-Assets/blob/main/Platform-Content/Technical/Partner-Implementations.md) that have developed or solution on top of one or more iDaaS components
- Feel free to look at our [roadmap](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Platform-Content/Roadmap/index.md), it is updated monthly
- All the assets within this project are available and provided "as-is" under [Apache 2 licensing](https://www.apache.org/licenses/LICENSE-2.0).
- To help and continue improving implementation expericence we have a series of implementation guides developed, please start [here](https://github.com/Project-Herophilus/Project-Herophilus-Assets/blob/main/Platform-Content/ImplementationGuides/intro.md) to get some instructions on how to implement.

# Key Overall Project Capabilities Provided 
As we built this platform out there are an extensive set of capabilities. We have tried to seperate those into categories.

## Data Integration Capabilities
While there are a ton of very specific features and capabilities provided the platform and use cases it supports there 
are some very basic overall capabilities, here is a [link](IntegrationCapabilities.md) with all the details.

### Integration Repositories 
These repositories will help with integration specific needs.

| Repository Name                                                                                         | Description |
|---------------------------------------------------------------------------------------------------------| ------------|
| [Integration Framework for HDF](https://github.com/Project-Herophilus/IntegrationFramework-HDF)                    |Connecting to all types of data and providing access to information in near realtime. It is intended to be a comprehensive set of design patterns, reference architecture, accelerators to help anyone and supports hundreds of connectors from legacy to modern connectivity to industry standards to various public clouds connectivity needs.|
| [ACE (Audit, Compliance and Error Handling) Framework](https://github.com/Project-Herophilus/ACEFramework-HDF) |Audit, Compliance and Error Handling is all about providing the ability to process errors, audit and other data. This consists of the endpoints, processing and persistence needed to support the platform.|
| [Data Simulators](https://github.com/Project-Herophilus/DataSimulators)                                 | Having data is one aspect, the other is having tooling that can quickly be configured and used to test components. We have developed data-simulators for our core components, Simulators to help in implementation and testing.  |   

## Application Development Repositories
There is a wide variety of application development and integration capabilities that we have provided. Below are the specific 
repositories that exist.

| Repository Name                                                                                       | Description |
|-------------------------------------------------------------------------------------------------------| ------------|
| [Application Framework for HDF](https://github.com/Project-Herophilus/ApplicationFramework-HDF)       |Assets designed from multiple technologies that serve a variety of purposes from routing of data to data transformation to business driven data assets.|
| [Defianz (De-Identification or Anonymization of Data)](https://github.com/Project-Herophilus/Defianz) |Providing the capability to de-identify or anonymize data |
| [Event Builder](https://github.com/Project-Herophilus/Event-Builder)                                  | A comprehensive library for parsing and building various types of healthcare industry standards based data.|
| [Synthetic Data](https://github.com/Project-Herophilus/DataSynthesis)                                 | When it comes to building or testing assets, having lots of data to resemble your production data is critical, it also helps drive innovation. We have open sourced a synthetic data platform and continue to enhance it based on feedback. It currently contains over 18 billion specific data attributes that can be used |

### Supporting Repositories 
Customer application development efforts that support leveraging existing integrated assets are available to assist 
provide additional capabilities for any implementation : <br/>

| Add-On | Description |
| ------ | ------------|
| [Project Herophilus Technical Content](https://github.com/Project-Herophilus/Project-Herophilus-Assets) | Variety of content specific to iDaaS - PowerPoints, Word Docs, and Draw.IO diagrams|
| [Test Data](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Testing)  | Test data for all healthcare industry standards work|

             
