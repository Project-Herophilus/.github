# Background
Open Source or the "community" development model has been used in software development for almost two decades. Over the
last decade all significant software innovation in the past 10 years has been from open-source communities. Here is a
<a href="https://www.redhat.com/rhdc/managed-files/rh-enterprise-open-source-report-f27565-202101-en.pdf" target="_blank">report</a>
that showcases all the various ways open source and it's culture is transforming the way not only software is delivery but
changing the way new innovation is being delivered. Healthcare for many decades has also relied upon community development
in areas such as treatment protocols, safety standards, and industry standards based data formats. Now, as we head into
a new era driven by comsumption and secure managed services it is a perfect time in healthcare for open source and
healthcare.

Welcome to Project Herophilus, our mission is to be an open source upstream healthcare
community focused on enabling healthcare care to solve problems with data driven assets. In order to help healthcare it was
critical that we define [specific design principles](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Platform-Content/Design/DesignPrinciples.md) to ensure a very
[scalable, extensible and reusable architecture](Platform-Content/Design/Architecture.md) with a focus on enabling
specific [capabilities](Platform-Content/Design/Capabilities.md). The intent of this organization is two fold: help drive
data driven open source capabilities into healthcare while demonstrating how healthcare can leverage open source to
solve industry problems. Why the name? Herophilus or spelled Herophilos, Herophilus was a Greek physician who is often
credited with being the founder of Anatomy. Since anatomy is the foundation for medicine and our focus is around enabling
healthcare we felt this was a very good name.

Project Herophilus intent is to help with various areas related to data challenges consistently seen across all areas of
healthcare for decades. We created a [fictious organization](Platform-Content/General/FictitiousOrg.md) for consistency and ensure we
can accurately define and relate any solutions being developed. The overall project is intended to deal with
[integration standards support](Platform-Content/Design/IntegrationStandardsSupported.md) and non industry standard data challenges.
At Project Herophilus, we [leverage industry leading open source technologies](Platform-Content/Technical/Technologies.md)
to help us bring the most widely adopted and used capabilities to bear. Assets currently available provide tools for configuration,
testing, legacy and modern data integration, modern application integration, synthetic data, and more. All of these assets
are available to any organization. The sole purpose of ALL the capabilities we have built for healthcare
is to focus on enabling <b> Data as an Asset</b>. The major focus of our efforts is to reduce, and hopefully remove, the data barriers
while reducing risk and moving data integration towards <b>Data Innovation</b> and enable it to move from a specific task based
enabler to a mainstream application development enablement.has made these assets available to anyone using fully open
source software and all under Apache 2 licensing.

Here is a detailed and Cloud Agnostic visual:<br/><br/>
![Cloud Agnostic](/images/iDaaS-Platform/Implementations/Implementations-Gen-CloudAgnostic.png)


# Core Repositories
To support any iDaaS branded artifact there are a subset of assets avaiable to assist in the implementation : <br/>

| Repository Name | Description |
| ------ | ------------|
|[iDaaS Connect](https://github.com/Project-Herophilus/iDaaS-Connect)|Connecting to all types of data and providing access to information in near realtime. It is intended to be a comprehensive set of design patterns, reference architecture, accelerators to help anyone and supports hundreds of connectors from legacy to modern connectivity to industry standards to various public clouds connectivity needs.|
|[iDaaS DREaM](https://github.com/Project-Herophilus/iDaaS-DREAM)|Assets designed from multiple technologues that serve a variery of purposes from routing of data to data transformation to business driven data assets.|
|[iDaaS KIC](https://github.com/Project-Herophilus/iDaaS-KIC)|Knowledge, Insight and Conformance is all about providing the ability to process errors, audit and other data. This consists of the endpoints, processing and persistence needed to support the platform.|
| [iDaaS Data Simulators](https://github.com/Project-Herophilus/iDaaS-DataSimulators)| Having data is one aspect, the other is having tooling that can quickly be configured and used to test components. We have developed a data-simulators for our core components, Simulators to help in implementation and testing.  |   
| [Event Builder](https://github.com/Project-Herophilus/Event-Builder)| A comprehensive library for parsing and building various types of healthcare industry standards based data.|

# Add-Ons Efforts and Supporting Repositories 
To support any iDaaS branded artifact there are a subset of assets avaiable to assist in the implementation : <br/>

| Add-On | Description |
| ------ | ------------|
| [Project Herophilus Technical Content](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Platform/Content) | Variety of content specific to iDaaS - PowerPoints, Word Docs, and Draw.IO diagrams|
| [Test Data](https://github.com/Project-Herophilus/Project-Herophilus-Assets/tree/main/Testing)  | Test data for all healthcare industry standards work|
| [Synthetic Data](https://github.com/Project-Herophilus/DataSynthesis)| When it comes to building or testing assets having lots of data to resemble you production data is critical, it also helps drive innovation. We have open sourced a synthetic data platform and continue to enahnce it based on feedback. It currently contains over 18 billion specific data attributes that can be used |
| [De-Identification or Anonymization of Data](https://github.com/Project-Herophilus/Defianz)|Providing the capability to de-identify or anonymze data |


