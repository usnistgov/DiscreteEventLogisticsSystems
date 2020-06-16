# Discrete Event Logistics Systems

## Overview
A discrete event logistics system (or DELS) can be described as:

*	a network of resources, arranged in a facility; each resource has one or more processing capabilities and for each capability, it has a capacity; 

*	a set of products flow through this network of resources, and are transformed by processes executed by the resources; a process may require the capabilities of more than one resource; the transformation can change location, age, or condition

The goal of this project is to develop abstractions, model-libraries, and methodologies for applying them to support:
* **Communication** -- improve precision with which we describe these systems and harmonize terminology for both system and analysis modeling.

* **Interoperability** -- support developing integrated software and tools to support design, analysis, and operation

* **Analysis** --  increase accessibility of analysis methods through integrations and transformations from system models

* **Design** -- provide model-libraries to support development of conceptual models and functional architectures

## [Brief] Get-Started
_After you download the whole repository_, there are few basic ways to get started with the models. (Note: A more comprehensive guide is coming in the near future.)

1. For MagicDraw Users:  You can open **DiscreteEventLogisticsSystems.mdzip**. This will open the DELS model library and automatically import the **CommodityFlowNetwork.mdzip**. 

   a) You may open **DELSFramework.mdzip**. This will open the top-level model repository with **_ALL_** of the domain-specific model libraries. Most of the domain-specific model libraries (except DELS and CFN) are work-in-progress or work-not-in-progress (stale projects).
  
   b) Most of the domain-specific model libraries (e.g. **Manufacturing_RefArch.mdzip**) automatically import their dependency tree. So if you want to work with the Manufacturing libraries, you can simply open that library and it'll import both DiscreteEventLogisticsSystems and CommodityFlowNetwork.
  
2. For users of non-MagicDraw SysML editors (e.g., Sparx EA): You can import the **DiscreteEventLogisticsSystems.xmi** and **CommodityFlowNetwork.xmi** files.
3. For non-SysML editors: Use the _html_ files. Unzip **CommodityFlowNetwork.html.zip** and **DiscreteEventLogisticsSystems.html.zip** and open in a browser. Unfortunately, right now Chrome doesn't seem to be working, but Internet Explorer and Edge seem to work just fine.

**Note** These model libraries were created in NoMagic's MagicDraw 18.5 SP1 which implements SysML 1.4

## Summary of Included Packages

* **CommodityFlowNetwork.mdzip** and **DiscreteEventLogisticsSystems.mdzip** are documented in NISTIR-8262 available from https://doi.org/10.6028/NIST.IR.8262.
  * These models are also available in OMG's XML Model Interchange (XMI) format, see **CommodityFlowNetwork.xmi** and **DiscreteEventLogisticsSystems.xmi** which can be imported into most SysML editors.
  * These models are also available to be viewed in html, see **CommodityFlowNetwork.html.zip** and **DiscreteEventLogisticsSystems.html.zip**. While read-only and with limited functionality, this is a quick way to view the content of these models without a SysML modeling tool. You will need to unzip the folder first. Also, Internet Explorer / Edge seem to work best right now.

* **CentralFillPharmazy.mdzip** and **CentralFillPharmacy_deprecated.mdzip** are products of NIST grant _70NANB15H234_ with documentation available at https://nvlpubs.nist.gov/nistpubs/gcr/2019/NIST.GCR.19-022.pdf

* **Functional_Architecture.mdzip** supports the research documented in _Sprock, Timothy, and Leon F. McGinnis. "Analysis of functional architectures for discrete event logistics systems (dels)." Procedia Computer Science 44 (2015): 517-526._

* **Warehouse_RefArch.mdzip** supports the research documented in _Sprock, Timothy, Anike Murrenhoff, and Leon F. McGinnis. "A hierarchical approach to warehouse design." International Journal of Production Research 55.21 (2017): 6331-6343._

* **SupplyChain_RefArch.mdzip** supports the research documented in _Sprock, Timothy, and Leon F. McGinnis. "Simulation model generation of discrete event logistics systems (dels) using software design patterns." Proceedings of the Winter Simulation Conference 2014. IEEE, 2014._

* **M-SysML.mdzip** was initially constructed as part of DARPA Contract _FA8650-11-C-7142_ and currently being continued under NIST grant _70NANB19H067_. Initial documentation can be found at https://apps.dtic.mil/dtic/tr/fulltext/u2/a565243.pdf

* **ElectronicsAssemblyCaseStudy.mdzip** is a current project of the INCOSE Production and Logisistics Modeling Challenge Team, see here for more details: http://www.omgwiki.org/MBSE/doku.php?id=mbse:prodlog

## Disclaimers

The use of any software or hardware by the project does not imply a recommendation or endorsement by NIST. The use of the project results in other software or hardware products does not imply a recommendation or endorsement by NIST of those products. The software developed by NIST employees is not subject to copyright protection within the United States.

https://www.nist.gov/disclaimer
