---
layout: post
title:  "Wednesday, August 2, 2017"
date:   2017-08-02 11:30:00 -0700
categories: developer meeting
---
**_Recent Go-Lives_**
* Wellness Data: Google Fit (CHG0025396)

**_Future Go-Lives, Maintenance_**
* Wellness Data: Accuchek (CHG???)
	* Go-live TBD, support model to be refined
* EDW
	* ADT - New not null columns (OSHPD_PAYOR_CAT_CD) for batch team (CHG0023962), **_Go-Live: week of 31-Jul_**
	* FLWEP - Clinical Observations, add LDA_ID, CLIN_OBSERV_DTL_DESC (CHG0027645), **_Go-Live: 1-Aug ish_**
* ODS
	* Modify interval for archiving MLSR records (CHG0027336) **_Go-Live: week of 01-Aug_**
	* Decommission of DB link LINK_AUDIT_DI **_Go-Live: week of 08-Aug_**
  
**_In Development_**
* ODS
	* ADTRAW - Reprocess qstat 3 on patient merge messages (A18) (CHG0026017)
  * Moved to ODSC, analyst reviewing
* EDW
	* LABSQ - Specimen container ID, new SAC segment, pending analyst validation of queue data (CHG???)
	* ADT -  New not null columns (ADM_CONFIRM_STS_CD) for batch team (CHG0021546)
	* RXEP - Drop columns from table (APPL_STG_QA.ORD_SRC_CD) for batch team (CHG0025251)
* CDR Oracle 12C upgrade
  * Assess chains, links, source code
* Wellness Data: 11Health (CHG???)
  * New PL/SQL data upload procedure for ostomy data being developed by Renier in EDWDBD

**_Announcements_**
* Carlton WFM after dentist on 4-Aug

**_Open Discussion_**
