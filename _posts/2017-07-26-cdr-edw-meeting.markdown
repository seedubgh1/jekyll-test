---
layout: post
title:  "Wednesday, July 26, 2017"
date:   2017-07-26 11:30:00 -0700
categories: developer meeting
---
**_Recent Go-Lives_**
* ODS (as of 19-Jul)
	* TRSR: MDRH MRN logic enhancement (CHG0024876)
	* Reference Lab reprocessing solution (CHG0026020)
	* CLSR, APSR - Disable SSN validation (CHG0026060)

**_Future Go-Lives, Maintenance_**
* Wellness Data: Google Fit, Accuchek (CHG0025396)
	* Go-live TBD, support model to be refined
* EDW
	* ADT - New not null columns (OSHPD_PAYOR_CAT_CD) for batch team (CHG0023962), **_Go-Live: week of 31-Jul_**
	* FLWEP - Clinical Observations, add LDA_ID, CLIN_OBSERV_DTL_DESC (CHG???), **_Go-Live: 1-Aug_**
* ODS
	* CDRC server will be stopped for maintenance at 12:00, follow job shutdown procedure in Box
  
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

**_Open Discussion_**
  * Conversion team kickoff
