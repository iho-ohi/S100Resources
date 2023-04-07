
### Introduction
This page provides resources related to the S-100 based Product Specifications as prioritized in the [Annex 2 of the S-100 Roadmap](https://iho.int/uploads/user/About%20IHO/Council/S-100_ImplementationStrategy/S-100%20Roadmap_Annex_2_v2.0_July2022.pdf). In addition to the Product Specifications themselves, Test Datasets and information about related S-100 testbed is provided. It is intended to support system developers in implementting S-100 based Product Specifications and provide a central location to provide feedback on their different components.

### S-100 based Product Specifications: Phase 1 in the S-100 Roadmap
*Where all components of a Product Specification can be found at the same location (such as the IHO Geospatial Information (GI) Registry, Product Specification Register),  the link to these components is included in the Product Specification entry only*

| Product Specification | S-101            | S-102       |  S-104    |  S-111    |  S-124    |  S-129    |      
| ----------------------|:----------------:|:-----------:|:---------:|:---------:|:---------:|:---------:|
| Compliant to S-100    | [S-100 Ed.5.0.0] |             |           |           |           |           |
| Product Specification | [S-101 Ed.1.0.0] |             |           |           |           |           |
| DCEG[^1]              | S-101 Ed.1.0.2 |             |           |           |           |           |
| Feature Catalogue     | S-101 Ed.1.0.2 |             |           |           |           |           |
| Portrayal Catalogue   | S-101 Ed.1.0.2 |             |           |           |           |           |
| Validation Checks     |                  |             |           |           |           |           |
| IHO website links     | [IHO S-101PT]    |[IHO S-102PT]| [IHO TWCWG]| [IHO TWCWG] |[IHO NIPWG] | [IHO S-129PT]|

[S-100 Ed.5.0.0]:https://registry.iho.int/productspec/view.do?idx=194&product_ID=S-100&statusS=5&domainS=ALL&category=product_ID&searchValue=
[S-101 Ed.1.0.0]:https://registry.iho.int/productspec/view.do?idx=78&product_ID=S-101&statusS=5&domainS=ALL&category=product_ID&searchValue=
[IHO S-101PT]:https://iho.int/en/s-101-project-team-1 
[IHO S-102PT]:https://iho.int/en/s-102-project-team-1
[IHO S-129PT]:https://iho.int/en/resources-0-0-0
[IHO TWCWG]:https://iho.int/en/twcwg
[IHO NIPWG]:https://iho.int/en/nipwg


### Product Software Support
This section lists software applications which provide the capability to create and edit S-100 datasets, which have now implemented S-100 Edition 5.0.0.


| Software Provider    | Application                       | S-101    | S-102    |  S-104    |  S-111    |  S-124    |  S-129    |      
| ---------------------|:---------------------------------|:--------:|:---------:|:---------:|:---------:|:--------:|:---------:|
| KHOA                 |[KHOA S-100 viewer] **`Free`**     |Ed.1.0.0  |  Ed.1.0.0 |           | Ed.1.0.0  |          |           |
| NIWC                 |[NIWC S-100 viewer] **`Free`**     |Ed.1.0.0  |           |           |           |          |           |
| I4Insight            |[dKart S-101 Converter] **`Free`** | Ed.1.0.0 |           |           |           |          |           |
| Teledyne CARIS       |HPD 4.1.36                         |Ed.1.0.0  |           |           |           |          |           |
| Esri Inc             |ArcGIS Pro                         |          |           |           |           |          |           |
| IIC                  |Feature Builder[^6]                    | Ed.1.1.0 |           |           |           |          |           |
| IIC                  |Exchange Set Builder               |    Yes   | Yes       |Yes        |Yes        |Yes       |Yes        |
[^6]: support to produce S-101 and any GML encoded products(S-12X)

[KHOA S-100 viewer]: https://github.com/S-100ExpertTeam/khoa-s100-viewer
[NIWC S-100 viewer]: https://registry.iho.int/repository/list.do "NIWC (former SPAWAR) S100Viewer, Editor and Shore ECDIS"
[dKart S-101 Converter]:https://registry.iho.int/repository/list.do 

### Test Datasets
S-164 *- IHO Test Datasets in ECDIS* have been produced to fulfil the requirement for a set of datasets necessary to accomplish all ECDIS testing requirements as outlined in the IEC 61174 standard.  The Test DataSets (TDS) are published as IHO Publication S-164 and consist of numerous datasets required for testing as well as the TDS Instruction Manual (TIM).  The TIM provides supporting documentation about the organization, understanding, and use of the ENC TDS and is intended to be used along with the datasets included in the TDS. 

S-164 can be found at the following link: [In development][S-164 webpage In development]

[S-164 webpage In development]:https://github.com/iho-ohi/S-164-Sub-Group 

The following are links to various test datasets that are produced by the individual Project Teams as well as various IHO Member States in support of S-100 Implementation. 


| Name           | S-101           | S-102           |  S-104    |  S-111         |  S-124    |  S-129    |      
| ---------------|:---------------:|:---------------:|:---------:|:--------------:|:---------:|:---------:|
| S-101 TDS[^2]  |[LINK][S101TDS]  |                 |           |                |           |           |
| KHOA S1OOP[^3] |                 |                 |           |                |           |           |
| UKHO MDP  [^4] | [LINK][UKHO TDS]|                 |           |                |           |           |
| NOAA PMN  [^5] |                 |[LINK][NOAA TDS] |           |[LINK][NOAA TDS]|           |           |

[S101TDS]: https://github.com/iho-ohi/S-101-Test-Datasets 
[UKHO TDS]: https://datahub.admiralty.co.uk/portal/apps/sites/#/marine-data-portal/pages/s-100
[NOAA TDS]: https://beta.marinenavigation.noaa.gov/gateway/



### Testbed Programmes

|  Name                     | Contributors      | Related standards    |  Information    | Contact        |       
| --------------------------|:-----------------:|:--------------------:|:---------------:|:--------------:|
| KHOA S-100 Testbed        | Rep.of Korea      | S-98, S-1xx          |                 |[Ms Iji KIM]    |
| IHO-Singapore Lab         | Singapore         | S-101, S-102         | [LINK][Lab LINK]|[Dr Parry Oei]  |
| S-100 Across the channel  |France, UK         | S-101, S-102         |                 |                |   

[Lab LINK]: https://iho.int/en/projects 
[Dr Parry Oei]:mailto:Parry_OEI@mpa.gov.sg
[Ms Iji KIM]:mailto:izzykim@korea.kr




### Test Framework

A Test Framework has been developed to facilitate testing of S-100. This sets out a number of testing objectives to support testbeds in creating more detailed test materials. It includes some example user stories and where relevant references to associated Test Datasets. Feedback is welcome on the Test Framework. [In preparation](https://iho-ohi.github.io/S100Resources/)


### Provide Feedback

| Title                  | S-101      | S-102    |  S-104    |  S-111    |  S-124    |  S-129    |      
| -----------------------|:----------:|:--------:|:---------:|:---------:|:---------:|:---------:|
| Test Dataset Feedback  |TEMPLATE    |          |           |           |           |           |
| Product Specification  | TEMPLATE   |          |           |           |           |           |
| Test Framework         | TEMPLATE   |          |           |           |           |           |
| Point of Contact       | TEMPLATE   |          |           |           |           |           |


[^1]: Data Classification and Encoding Guide.
[^2]: Test Dataset.
[^3]: S-100 Open Online Platform.
[^4]: Marine Data Portal.
[^5]: Precision Marine Navigation Programme.


    
###### *Please contact [IHO Secratariat](mailto:yong.baek@iho.int "Mr.Yong BAEK") if you encounter any technical issues on this webpage.*

</html>

