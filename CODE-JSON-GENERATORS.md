##OMB M-16-21 Federal Source Code Policy Inventory Requirement
Since the release of the OMB M-16-21 Federal Source Code Policy (FSCP), the U.S. Government (CFO Act agencies) have been focused on completing a comprehensive inventory of all custom developed software from August 2016. Additionally, the Federal agencies have to identify which of those custom developed software can be open source, government wide reuse or exempt to comply with the OMB M-16-21 FSCP. For a full list of requirements please see the [Metadata Schema 2.0.0 ](https://code.gov/#/policy-guide/docs/compliance/inventory-code)requirements.

##Code.gov Metadata Schema 2.0.0 Requirements
[https://code.gov/#/policy-guide/docs/compliance/inventory-code]()

The Code.gov program and U.S. Government would like to developed a code.json generator/scraper tool that would support all GIT version control systems (vcs) and legacy vcs to capture the software inventory systematically. The main objective is to reduce the manual process, increase efficiency, reduce human error, and standardize the technical solution. To accomplish these objectives we would like to setup an ongoing working group from the Federal agencies and Open Source Community to support the implementation of the code.json generator/scraper tools.

##Generators
Feature             | [Scraper](https://github.com/llnl/scraper) | [Code-JSON Generator](https://github.com/usgs/code-json-generator) |  [Code-Inventory Generator](https://github.com/GSA/codeinventory-github) | [Code Inventory](https://github.com/GSA/codeinventory-github) |
--------------------|-----------------------|-----------------------|-----------------------|-----------------------|  
Language            | Python                | Node.js | Ruby | Ruby |
GitHub.com?        | :white_check_mark:    | :white_check_mark: | :white_check_mark: |  :white_check_mark: 
GitLab.com?        | :warning:             | :white_check_mark: | :x: | :x: |
Bitbucket.org?     | :warning:             | :x: | :x: |  :x: | 
Labor Hours Estimates        | :white_check_mark:    | :x: | :x: | :x: | 
Lead Developer		| [IanLee1521](https://github.com/IanLee1521)	| [emartinez-usgs](https://github.com/emartinez-usgs)	| [contolini](https://github.com/contolini) | [jfredrickson5](https://github.com/jfredrickson5)
Agency					|	DOE-LLNL		|	DOI-USGS  		|	CFPB   	|  GSA
GitHub API			| REST API v3		|	REST API v3  | GraphQL API v4 |	REST API v3  | 
		

  

##Resources
GraphQL API v4 | https://developer.github.com/v4/
CFPB Code Inventory Generator

Additional GIT vcs platforms:
https://bitbucket.org
https://about.gitlab.com
 asd
