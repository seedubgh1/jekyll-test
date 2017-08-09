---
layout: post
title:  "Wednesday, August 9, 2017"
date:   2017-08-02 11:30:00 -0700
categories: developer meeting
---
**_Recent Go-Lives_**
* ODS
	* Modify interval for archiving MLSR records (CHG0027336)
	* Decommission of DB link LINK_AUDIT_DI

**_Future Go-Lives, Maintenance_**
* EDW
	* ADT - New not null columns (OSHPD_PAYOR_CAT_CD) for batch team (CHG0023962), **_go-live: 9-Aug_**
	* FLWEP - Clinical Observations, add LDA_ID, re-map CLIN_OBSERV_DTL_DESC (CHG0027645), **_go-live: 9-Aug_**
  
**_In Development_**
* ODS
	* ADTRAW - Reprocess qstat 3 on patient merge messages (A18) (CHG0026017)
	* Moved to ODSC, analyst testing
* EDW
	* LABSQ - Specimen container ID, new SAC segment, pending analyst validation of queue data (CHG???)
	* ADT -  New not null columns (ADM_CONFIRM_STS_CD) for batch team (CHG0021546)
	* RXEP - Drop columns from table (APPL_STG_QA.ORD_SRC_CD) for batch team (CHG0025251), currently in EDWDBT
* CDR Oracle 12C upgrade
	* Assess chains, links, source code
* Wellness Data: 11Health (CHG???)
	* New PL/SQL upload procedure for ostomy data, developed by Renier in EDWDBD
	* Accuchek (CHG???), go-live TBD, support model to be refined

**_Announcements_**
* Dennis, Carlton in late after doctor on 11-Aug
* Ben out 6,7,8-Sep

* Enterprise GitHub is available!  Migrate repositories as you see fit.

**_Open Discussion_**
* Conversion team update
