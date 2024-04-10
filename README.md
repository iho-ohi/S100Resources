<p align="right">
 <img src="https://iho.int/uploads/user/logo/IHO_Logo_RGB_Complete_EN.png" alt="IHO S-100 Resourcet" width="210" height="70">
 </p>
### Introduction
This page provides resources related to the S-100 based Product Specifications as prioritized in the [Annex 2 of the S-100 Roadmap](https://iho.int/uploads/user/About%20IHO/Council/S-100_ImplementationStrategy/S-100%20Roadmap_Annex_2_v2.0_July2022.pdf). In addition to the Product Specifications themselves, Test Datasets and information about related S-100 testbed is provided. It is intended to support system developers in implementting S-100 based Product Specifications and provide a central location to provide feedback on their different components.

### S-100 based Product Specifications: Phase 1 in the S-100 Roadmap
*Product Specifications are listed below indicating the versions published for testing and development. Component elements can be downloaded from the IHO Geospatial Information (GI) Registry by following the link for each Product Specification entry*

| Product Specification | S-101            | S-102       |  S-104    |  S-111    |  S-124    |  S-129    |      
| ----------------------|:----------------:|:-----------:|:---------:|:---------:|:---------:|:---------:|
| Compliant to S-100    | [S-100 Ed.5.0.0] |[S-100 Ed.5.0.0]|[S-100 Ed.5.0.0] | [S-100 Ed.5.0.0] | [S-100 Ed.5.0.0]  | [S-100 Ed.5.0.0]|
| Product Specification | [S-101 Ed.1.2.0] |[S-102 Ed.2.2.0]|[S-104 Ed.1.1.0] | [S-111 Ed.1.2.0] | [S-124 Ed.1.0.0]  |[S-129 Ed.1.1.0] |
| DCEG[^1]              | S-101 Ed.1.2.0   |             |           |           |           |           |
| Feature Catalogue     | S-101 Ed.1.2.3   |S-102 Ed.2.2.0 | S-104 Ed.1.1.0 | S-111 Ed.1.2.0      | S-124 Ed.1.0.0 |S-129 Ed.1.1.0   |
| Portrayal Catalogue   | S-101 Ed.1.2.3   |             |           |           |  S-124 Ed.1.0.0           |S-129 Ed.1.1.0|
| Validation Checks     | S-101 Ed.1.1.1   |             |           |           |           |           |
| IHO website links     | [IHO S-101PT]    |[IHO S-102PT]| [IHO TWCWG]| [IHO TWCWG] |[IHO NIPWG] | [IHO S-129PT]|

[S-100 Ed.4.0.0]:https://registry.iho.int/productspec/view.do
[S-100 Ed.5.0.0]:https://registry.iho.int/productspec/view.do?idx=194&product_ID=S-100&statusS=5&domainS=ALL&category=product_ID&searchValue=
[S-101 Ed.1.2.0]:https://registry.iho.int/productspec/view.do?idx=203&product_ID=S-101&statusS=5&domainS=ALL&category=product_ID&searchValue=
[S-104 Ed.1.1.0]:https://registry.iho.int/productspec/view.do?idx=198&product_ID=S-104&statusS=ALL&domainS=ALL&category=product_ID&searchValue=
[S-111 Ed.1.2.0]:https://registry.iho.int/productspec/view.do?idx=178&product_ID=S-111&statusS=ALL&domainS=ALL&category=product_ID&searchValue=
[S-102 Ed.2.2.0]:https://registry.iho.int/productspec/view.do?idx=199&product_ID=S-102&statusS=5&domainS=ALL&category=product_ID&searchValue=
[S-124 Ed.1.0.0]:https://registry.iho.int/productspec/view.do?idx=181&product_ID=S-124&statusS=5&domainS=ALL&category=product_ID&searchValue=
[S-129 Ed.1.1.0]:https://registry.iho.int/productspec/view.do?idx=196&product_ID=S-129&statusS=5&domainS=ALL&category=product_ID&searchValue=
[IHO S-101PT]:https://iho.int/en/s-101-project-team-1 
[IHO S-102PT]:https://iho.int/en/s-102-project-team-1
[IHO S-129PT]:https://iho.int/en/resources-0-0-0
[IHO TWCWG]:https://iho.int/en/twcwg
[IHO NIPWG]:https://iho.int/en/nipwg


### Product Software Support
This section lists software applications which provide the capability to create and edit S-100 datasets, which have now implemented S-100 Edition 5.0.0.


| Software Provider    | Application                       | S-101    | S-102    |  S-104    |  S-111    |  S-124    |  S-129    |      
| ---------------------|:----------------------------------|:--------:|:---------:|:---------:|:---------:|:--------:|:---------:|
| KHOA                 |[KHOA S-100 viewer] **`Free`**     |Ed.1.0.0  |  Ed.1.0.0 |           | Ed.1.0.0  |          |           |
| NIWC                 |[NIWC S-100 viewer] **`Free`**     |Ed.1.2.0  | Ed.2.2.0  | Ed.1.1.0  | Ed.1.2.0  |Ed.1.0.0  | Ed.1.1.0  |
| I4Insight            |[dKart S-101 Converter] **`Free`** |Ed.1.0.0  |           |           |           |          |           |
| Teledyne CARIS       |[CARIS Easy view]   **`Free`**     |Ed.1.x.x  | Ed.2.1.0  |           |           |          |           |
|                      |HPD 4.1.36                         |Ed.1.1.0  |           |           |           |          |           |
|                      |BASE Editor 5.5.6                  |          | Ed.2.1.0  |           |           |          |           |
| Esri Inc             |ArcGIS Pro 3.1                     |Ed.1.0.0  |           |           |           |          |           |
| IIC                  |Feature Builder[^6]                |Ed.1.1.0  |           |           |           |          |           |
|                      |Exchange Set Builder               |   Yes    | Yes       |Yes        |Yes        |Yes       |Yes        |
| 7Cs                  |Analyzer for Validation            |Ed.1.1.0  |           |           |           |          |           |
|                      |FME based S-57 to S-101 conversion |Ed.1.1.0  |           |           |           |          |           |
| ECC/PRIMAR           |IHO S-100 Ed4 and Ed5 SA protection application  |Support|Support             |Support    |Support    |Support   |Support    |
| ECC                  |GDS(Geodata Distribution Server)   |Support      |Support|To be supported     | Support   |          |           |

[KHOA S-100 viewer]: https://github.com/S-100ExpertTeam/khoa-s100-viewer
[NIWC S-100 viewer]: https://registry.iho.int/repository/list.do "NIWC (former SPAWAR) S100Viewer, Editor and Shore ECDIS"
[dKart S-101 Converter]:https://registry.iho.int/repository/list.do 
[CARIS Easy view]:https://www.teledynecaris.com/en/products/easy-view/

### Test Datasets
S-164 *- IHO Test Datasets in ECDIS* have been produced to fulfil the requirement for a set of datasets necessary to accomplish all ECDIS testing requirements as outlined in the IEC 61174 standard.  The Test DataSets (TDS) are published as IHO Publication S-164 and consist of numerous datasets required for testing as well as the TDS Instruction Manual (TIM).  The TIM provides supporting documentation about the organization, understanding, and use of the ENC TDS and is intended to be used along with the datasets included in the TDS. 

S-164 can be found at the following link: [In development][S-164 webpage In development]

[S-164 webpage In development]:https://github.com/iho-ohi/S-164-Sub-Group 

The following are links to various test datasets that are produced by the individual Project Teams as well as various IHO Member States in support of S-100 Implementation. 


| Name           | S-101           | S-102           |  S-104          |  S-111                  |  S-124          |  S-129    |      
| ---------------|:---------------:|:---------------:|:---------------:|:-----------------------:|:---------------:|:---------:|
| S-101 TDS[^2]  |[LINK][S101TDS]  |                 |                 |                         |                 |           |
| KHOA S1OOP[^3] |                 |                 |                 |                         |                 |           |
| UKHO MDP  [^4] | [LINK][UKHO TDS1]|[LINK][UKHO TDS2] |[LINK][UKHO TDS4] | [LINK][UKHO TDS11]|  |                 |           |
| NOAA PMN  [^5] |                 |[LINK][NOAA TDS] |                 |[LINK][NOAA TDS]         |                 |            |
| PRIMAR Chart Catalogue |         | [LINK][PRIMAR Chart]|[LINK][PRIMAR Chart] |                |                  |           |
| PRIMAR security scheme test - PRIMAR remote update protocol |                 |[LINK][PRIMAR security] |           |[LINK][PRIMAR security]|           |           |

[S101TDS]: https://github.com/iho-ohi/S-101-Test-Datasets 
[UKHO TDS1]: https://datahub.admiralty.co.uk/portal/apps/sites/#/marine-data-portal/pages/s-100
[UKHO TDS2]: https://datahub.admiralty.co.uk/portal/apps/sites/#/marine-data-portal/items?tags=%22s102%20ports%22
[UKHO TDS4]:https://datahub.admiralty.co.uk/portal/apps/sites/#/marine-data-portal/items/5f6630b0327f47689c5fa2bcb3b5eefd
[UKHO TDS11]: https://datahub.admiralty.co.uk/portal/apps/sites/#/marine-data-portal/items/d94b8ecbe3884b129d231e8b5b757a6b
[NOAA TDS]: https://beta.marinenavigation.noaa.gov/gateway/
[PRIMAR Chart]: https://primar.ecc.no/primar/portal/cc/mapClient.jsf
[PRIMAR security]: https://primar.learnworlds.com/course/s-100-data-protection-source-code-and-testdata


### Testbed Programmes

|  Name                     | Contributors                                                                | Related standards     |  Information                                     | Contact          |       
| --------------------------|:---------------------------------------------------------------------------:|:---------------------:|:------------------------------------------------:|:----------------:|
| KHOA S-100 Testbed        | Rep.of Korea                                                                | S-98, S-1xx           |                                                  |[Martin PARK]         |
| IHO-Singapore Lab         | Singapore                                                                   | S-101, S-102          | [LINK][Lab LINK]                                 |[Parry Oei]       |
| S-100 Across the channel  |France, UK                                                                   | S-101, S-102          |                                                  |[Christian Mouden]|
|PRIMAR Conversion Project  |PRIMAR, PRIMAR RENC member states, NTOU, SevenCs, i4Insight, TCaris, ECC   | S-101                 |[LINK][PRIMAR conversion]                         | data@ecc.no      |
| S-100 / S-102 Demo        |ECC, PRIMAR, Norway                                                          | S-101,S-102,S-111,S-129|[S-100 Demo][S-100 Demo], [S-102 Demo][S-102 Demo]|                  |   
| S-100 as a service        |ECC, PRIMAR, CHS, TCaris, SevenCs                                            | S-102, S-104, S-111    | [LINK][S-100 service]                            |                  |

[Lab LINK]: https://iho.int/en/projects 
[Parry Oei]:mailto:Parry_OEI@mpa.gov.sg
[Martin PARK]:mailto:martin.park@korea.kr
[Christian Mouden]:mailto:christian.mouden@shom.fr
[PRIMAR conversion]: https://iho.int/uploads/user/Services%20and%20Standards/S-100WG/S-101PT10/S-101PT10_2023_08.02_EN_PRIMAR_CTF_status_20230612.pdf
[S-100 Demo]: https://s-100.no/
[S-102 Demo]: https://s102.no/
[S-100 service]: https://blog.ecc.no/s-100-data-as-a-service-how-the-chs-leverages-the-new-s-100-paradigm




### Provide Feedback

Please reach out to the contact persons listed below for your feedback on the Test Dataset and Product Specification

| Title                   | S-101               | S-102                |  S-104    |  S-111         |  S-124         |  S-129        |      
| ------------------------|:-------------------:|:--------------------:|:---------:|:--------------:|:--------------:|:-------------:|
| Test Dataset            |[Thomas Richardson]  | [Lawrence Haselmaier] |           |                |[Eivind Mong]   | [Jason Rhee]  |
| Product Specification   |[Thomas Richardson]  | [Lawrence Haselmaier] |           |                |[Eivind Mong]   | [Jason Rhee]  |


[Thomas Richardson]:mailto:Thomas.Richardson@UKHO.gov.uk
[Lawrence Haselmaier]:mailto:lawrence.h.haselmaier.civ@us.navy.mil
[Jason Rhee]:mailto:j.rhee@omcinternational.com
[Eivind Mong]:mailto:Eivind.Mong@dfo-mpo.gc.ca


[^1]: Data Classification and Encoding Guide.
[^2]: Test Dataset.
[^3]: S-100 Open Online Platform.
[^4]: Marine Data Portal.
[^5]: Precision Marine Navigation Programme.
[^6]: Support to produce S-101 and GML encoded products(S-12X).


    
###### *Please contact [IHO Secratariat](mailto:yong.baek@iho.int "Mr.Yong BAEK") if you encounter any technical issues on this webpage.*



