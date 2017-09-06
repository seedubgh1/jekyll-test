---
layout: post
title:  "Weekly Meeting, September 06, 2017"
date:   2017-09-06 11:30:00 -0700
categories: developer meeting
---
**NOTE: Meeting was not held due to low attendee turn-out (out of office)**

**_Recent Go-Lives_**
* Nothing for the period

**_Future Go-Lives, Maintenance_**
* EDW
	* LABSQ - Specimen container ID, new SAC segment, pending analyst validation of queue data (CHG0026400)
     	* Go-live date: 10-Sep
  * Widen columns for RXEP queue, PID20 widenend to 40 chars to accommodate international driver license numbers
 
* CDR
  * Widen columns for IMGSR queue, PID20_01 widenend to 40 chars to accommodate international driver license numbers

**_In Development_**
* EDW
	* RXEP - Drop columns from table (APPL_STG_QA.ORD_SRC_CD) for batch team (CHG0025251), currently in EDWDBT
* CDR Oracle 12C upgrade
	* Waiting to confirm scope and duration for FTP chain cutover
* Wellness Data:  
	* 11Health: New PL/SQL upload procedure for ostomy data, developed by Renier in EDWDBD
	* Accuchek: go-live TBD, support model to be refined
  * GoogleFit: Added functionality to upload user weight, added by Renier currently in EDWDBD
* Meeting notes: migration pending, GitHub wiki under review

**_Announcements_**
* Ben out of office 6,7,8-Sep, Dennis to cover 6,7,8 and Carlton to cover weekend.

**_Open Discussion_**
* Deep6 extract program, troubleshooting
* Python, Pandas ramp-up continues
* Conversion team update
  * KJOC: ready to start phase one of sending to Epic/OnBase
