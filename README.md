### PIT Business
This content is part of a library of solutions build by PIT Business based on the experience of its experts.<br>
Please visit [PIT Business Website](http://www.pit-business.com) to **discover our Services and Solutions** for Scorecard, Stratgy Map, Master Data Management, BI Catalog, BI ChatBot, Project Portfolio Management, Dependency Graphs, ...<br>
*PIT Business, the best Qlik Influence Partner in Luxembourg & Belgium.*<br>

# Indexed Catalog
An **indexed access point** based on a **smart search toolbar** that displays results as cards.<br>
Cards shows details about results, and can links to other pages or platforms.<br>

## Use case : BI Catalog
Plugged on top of **multiple BI platforms** (ex: Qlik Sense, IBM Cognos), users can search for a specific Report, Dashboard, Measure, Dimension, Source, Data Warehouse Table, Operational Source over all the BI platforms.<br>
A list of cards is displayed as search results, and users can quickly see **what's inside a BI object** before opening it in the corresponding platform.<br>
Users can also display the **lineage** in a  **dependency graph** from the Operational Source, through the DWH tables, until the BI applications and visualizations.

## Which challenges does it address?

**Business Users**
 - Get a simple Smart Search over any content that we can load in a Qlik Sense application
 - In BI context: Business Users don‘t have an overview over the content available within their entire BI environment and the given functionality

**BICC/IT**
 - Offer a Smart Search interface that relies on the power of Qlik in back-end, without having to set a dedicated database environment
 - In BI context: BICC is often contacted by Business Users to guide them to existing apps, or by IT to get the usage of a source

## Versions

Version: 1.3
  -  New Qlik Sense API controller to load Cards with pre-computed information
  -  New UI with better display and filters
  -  Integration of a Lineage Graph that displays Cards' information in a [Dependency Graph](https://github.com/PITBusiness/dependencygraph-qlik)

Version: 1.2
  -  Data model enhancement to add Cognos elements, fields and sources
  -  Data model enhancement to create Cards with pre-computed detailed information

Version: 1.1
  -  Data sources extension with a Parser that get new information (fields, sources) from Qlik Sense API
  -  Data sources extension with a Parser that get new information (packages, reports, fields, Sources) from IBM Cognos SDK

Version: 1.0
  -  Initial [Qlik Sense Agent](https://github.com/QlikPreSalesDACH/Qlik-Sense-Agent) project

## Architecture
Technologies: Qlik Sense, HTML, CSS, JavaScript, JQuery, C#/.Net, Qlik Sense API, IBM Cognos SDK.

### Quick installation
This Indexed Catalog is not available without context introduction and basic understandings, please [contact PIT Business](http://www.pit-business.com) to get the Solution.<br>

----------

### Copyright
Licensed under the GNU AGPLv3<br>
*Strongest copyleft license are conditioned on making available complete source code of licensed works and modifications, which include larger works using a licensed work, under the same license. Copyright and license notices must be preserved. Contributors provide an express grant of patent rights. When a modified version is used to provide a service over a network, the complete source code of the modified version must be made available.*<br>
Information about the license at https://choosealicense.com/licenses/agpl-3.0<br>
<br>
For commercial use, contact us via [PIT Business Website](http://www.pit-business.com)<br>
Copyright 2018 PIT Business SARL<br>
