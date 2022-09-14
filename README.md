## Fine-grained informal settlements in GBA for SDG 11.1.1
# Introduction
Timely and accurate information of informal settlements is essential to measure and help achieve United Nations' Sustainable Development Goals (SDGs). Traditional methods can only produce data with sparse coverage and are costly in terms of time and labour. Although recent advances in remote sensing technology have made global population datasets available, these open datasets lack semantic information on informal settlements. To fill the gap and effectively measure the SDG 11.1.1 of mega-city clusters, we release the fine-grained semantic layer of informal settlements in GBA predicted by our proposed HMIS framework, to assess the SDG 11.1.1, i.e., the proportion of the urban population living in informal settlements. 

#GBA_InformalSettlement_byHMIS_v1.0
The proposed semantic layer of informal settlement in the study area in the the GCJ-02 coordinate system. It's predicted by the proposed HMIS framework. For more details, please check in the journal article, Towards SDG 11: Spatial and demographic analysis based on fine-grained informal settlement mapping in the Guangdong-Hong Kong-Macao Greater Bay Area in China.

#sample_GBA.csv
This file contains the training and testing samples to train and validate our proposed HMIS framework. These settlement samples are manually collected in our study area via online streetview images and field study, for a total sample size of 139,960.
- lat_gcj, lon_gcj: latititude and longtitude of the samples in the GCJ-02 coordinate system.
- is_informalsettlement: positive or negative sample.