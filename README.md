
# APIcture: Interactively exploring API structural changes and versioning consistency
In this page we present a comprehensive collection of visualization examples, including those featured in the paper, as well as additional examples that we find intriguing but were not included in the paper. For each visualization example, we provide relevant metadata related to the evolution of the subject, such as version numbers, timestamps, and release dates. Additionally, we specify the source OpenAPI Specification (OAS) used to generate the visualizations, ensuring transparency and reproducibility. Each example is accompanied by its corresponding visualization, allowing readers to explore and analyze the visual representations of API evolution. 

**Note that all the selected examples are real world APIs that are in production.**

# API examples included in the paper

<!-- ## RNAget API
Source: 
- [RNAget API changes visualization](https://souhailas.github.io/VISSOFT2023/changes-visualization-%20RNAget%20API.html)
   -->


## Vault API
Source: https://github.com/apideck-libraries/openapi-specs/blob/master/vault.yml

* Found 321 commits changing OAS file
* From [4th December, 2020] to [7th June, 2023]
* API Versions: 194

    * [Vault API changes visualization](https://souhailas.github.io/VISSOFT2023/changes-visualization-vault-api.html)
    * [Vault API version clock](https://souhailas.github.io/VISSOFT2023/versions-clock-vault-api.html)

|API Changes |    	| 
|:---	|---:	|
|API Changes  |        261 Changes|         
|Breaking Changes|     32 (12.26%)  Changes |
|Non Breaking Changes |229 (87.74%)  Changes|

|API Versioning||
|:---	|---:	|
API Versions   | 193 Versions|
Version Changes |194 Changes|


VERSION| CHANGE | BACKWARDS |BREAKING| NON BREAKING
|:---  |---:	|---:	    |---:	 |---:	       
none   |  125   |  0        | **20** |  69          
minor  |  122   |  0        | 0      |  108         
major  |  9     |  0        | 1      |  7           
patch  |  63    |  1        | **11** |  57  


## Main OverOps API
Source: https://github.com/takipi/api-spec/blob/master/services.yaml

(api.overops.com)

* Found 229 commits changing OAS file
* From [11th March, 2018] to [10th June, 2021]
* API Versions: 1

    * [Main OverOps API changes visualization](https://souhailas.github.io/VISSOFT2023/changes-visualization-overops-api.html)
    * [Main OverOps API version clock](https://souhailas.github.io/VISSOFT2023/versions-clock-overops-api.html)


|API Changes |    	| 
|:---	|---:	|
|API Changes | 267 Changes     	| 
|Breaking Changes    | 125 (46.82%)  Changes
|Non Breaking Changes| 142 (53.18%)  Changes



## Openshift Assisted service API

Source: https://github.com/openshift/assisted-service/blob/master/swagger.yaml

(api.openshift.com)

* Found 567 commits changing OAS file
* From [25th February, 2020] to [4th June, 2023]
* API Versions: 1

    * [Openshift Assisted service APIchanges visualization](https://souhailas.github.io/VISSOFT2023/changes-visualization-openshift-api.html)
      * The changed visuali
    * [Openshift Assisted service API version clock](https://souhailas.github.io/VISSOFT2023/versions-clock-openshift-api.html)



|API Changes |    	| 
|:---	|---:	|
API Changes      |    459 Changes          
Breaking Changes  |   187 (40.74%)  Changes
Non Breaking Changes | 272 (59.26%)  Changes

|API Versioning||
|:---	|---:	|   
API Versions   | 1 Versions
Version Changes| 0 Changes 

VERSION| CHANGE |BACKWARDS  |BREAKING| NON BREAKING
|:---  |---:	|---:	    |---:	 |---:	
none   | 565  |   0    |     187 |     231   

---

## Other API examples 
## ARD-Eventhub API
Source: https://github.com/swrlab/ard-eventhub/blob/main/openapi.json
* Found 67 commits changing OAS file
* From [3th February, 2021] to [19th April, 2023]
* API Versions: 45
  
  * [ARD-Eventhub API changes visualization](https://souhailas.github.io/VISSOFT2023/changes-visualization-ARD-Eventhub-api.html)
  * [ARD-Eventhub API version clock](https://souhailas.github.io/VISSOFT2023/versions-clock-ARD-Eventhub-api.html)

## Bmore Responsive API
Source: https://github.com/CodeForBaltimore/Bmore-Responsive

Note: In the recent latest commit in the repository the OpenAPI description is no longer at the root level of the repository and was moved to `src/api-docs/v1/swagger.json`. Where now another new specification for the version `v2` of the API is published. 

* Found 49 commits changing OAS file
* From [6th April, 2020] to [1th March, 2022]
* API Versions: 16
  
  * [Bmore Responsive API changes visualization](https://souhailas.github.io/VISSOFT2023/changes-visualization-bemoreresponsive-api.html)
  * [Bmore Responsive API version clock](https://souhailas.github.io/VISSOFT2023/versions-clock-bemoreresponsive-api.html)

## SunRocks API
Source: https://github.com/trigo-at/sunrocks-public-api-docs/blob/master/public-api.yaml

(https://www.sunrocks.at/)

* Found 24 commits changing OAS file
* From [2th August, 2017] to [17th May, 2023]
* API Versions: 5

  * [SunRocks API changes visualization](https://souhailas.github.io/VISSOFT2023/changes-visualization-sunrocks-api.html)
  * [SunRocks API version clock](https://souhailas.github.io/VISSOFT2023/versions-clock-sunrocks-api.html)



## Megasense data portal API

Source: https://github.com/Metatavu/megasense-data-portal-api-spec/blob/master/swagger.yaml

(https://megasense-server.cs.helsinki.fi/)

* Found 156 commits changing OAS file
* From [30th September, 2020] to [9th May, 2023]
* API Versions: 1

    * [Megasense data portal API changes visualization](https://souhailas.github.io/VISSOFT2023/changes-visualization-megasense-api.html)
    * [Megasense data portal API version clock](https://souhailas.github.io/VISSOFT2023/versions-clock-megasense-api.html)


|API Changes |    	| 
:---      | ---:
API Changes  |        180 Changes  
Breaking Changes    | 106 (58.89%)  Changes
Non Breaking Changes| 74 (41.11%)  Changes

API Versioning | |
 :---     | ---:
API Versions   | 1 Versions
Version Changes | 0 Changes 

VERSION | CHANGE | BACKWARDS| BREAKING| NON BREAKING
:---      | ---: | ---: | ---: | ---:
none      |     154  |   0     |    106   |   69    


## Moank Partner API

Source: https://github.com/Moank/moank-open-api-docs/blob/master/specifications/partners/partners.yml
(https://docs.moank.se/)

* Found 68 commits changing OAS file
* From [23th October, 2019] to [16th June, 2022]
* API Versions: 1

    * [Moank Partner API changes visualization](https://souhailas.github.io/VISSOFT2023/changes-visualization-moank-partner-api.html)
    * [Moank Partner API version clock](https://souhailas.github.io/VISSOFT2023/versions-clock-moank-partner-api.html)


  
## MLModelScope API

Source: https://github.com/rai-project/dlframework/blob/master/dlframework.swagger.json

(www.mlmodelscope.org)

* Found 84 commits changing OAS file
* From [13th June, 2017] to [15th July, 2019]
* API Versions: 3
  
    * [MLModelScope API changes visualization](https://souhailas.github.io/VISSOFT2023/changes-visualization-MLModelScope-api.html)
    * [MLModelScope API version clock](https://souhailas.github.io/VISSOFT2023/versions-clock-MLModelScope-api.html) 


## OpenFairDB API


Source: https://github.com/kartevonmorgen/openfairdb/blob/main/openapi.yaml

(https://slowtec.de)

* Found 144 commits changing OAS file
* From [12th December, 2018] to [24th March, 2023]
* API Versions: 56

    * [OpenFairDB API changes visualization](https://souhailas.github.io/VISSOFT2023/changes-visualization-openfairdb-api.html)
    * [OpenFairDB API version clock](https://souhailas.github.io/VISSOFT2023/versions-clock-openfairdb-api.html) 
  


|API Changes |    	| 
:---      | ---:
API Changes    |      127 Changes          
Breaking Changes |    25 (19.69%)  Changes 
Non Breaking Changes | 102 (80.31%)  Changes


API Versioning | |
 :---     | ---:
API Versions  |  55 Versions
Version Changes| 56 Changes 


VERSION |CHANGE | BACKWARDS | BREAKING | NON BREAKING
:---      | ---: | ---: | ---: | ---:
none    |       86   |   0  |       25  |     32          
minor   |       10   |   1  |       0   |     5           
prepatch |      1    |   0  |      0    |    1           
patch  |        45   |   0  |       0   |     37   



## VTEX - Antifraud Provider API

(https://developers.vtex.com/docs/api-reference)

* Found 101 commits changing OAS file
* From [12th May, 2020] to [19th April, 2023]
* API Versions: 1

    * [Antifraud API changes visualization](https://souhailas.github.io/VISSOFT2023/changes-visualization-Antifraud-api.html)
    * [Antifraud API version clock](https://souhailas.github.io/VISSOFT2023/versions-clock-Antifraud-api.html) 

