---
date: "2019-01-01T00:00:00Z"
external_link: ""
image:
  caption: 
  focal_point: Smart
links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/th1loz
links:
- name: 'Slides (HTML)'
  url: '/slides/RANZCR2021/PROMS_Innovations_RANZCR_ASM_2021.html'
- name: 'Slides (PDF)'
  url: '/slides/RANZCR2021/PROMS_Innovations_RANZCR_ASM_2021.pdf'
- name: 'Interactive Dashboard'
  url: 'https://thiloschuler.shinyapps.io/prospector-asm21'
# slides: example
summary: Project to establish routinely collected electronic patient-reported outcomes (ePROs) as a one key element underpinning innovations in care and clinical research of patients with prostate cancer referred to Northern Sydney Cancer Centre (NSCC) Radiation Oncology department. 
tags:
- 'Patient-generated Data'
- 'Clinician-recorded Data'
- 'Augmenting RO Routine Care with Real-time Data'
- 'RACER platform'
title: 'Routine ePROs in the Care of Prostate Cancer Patients Treated with RT'
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---
Project to establish **routinely collected electronic patient-reported outcomes (ePROs)** as a one key element underpinning innovations in care and clinical research of patients with prostate cancer referred to Northern Sydney Cancer Centre (NSCC) Radiation Oncology department.  

The design and implementation of **clinical workflows** including decision on PRO instruments to use and **technical infrastructure** for collection of ePROs and clinician-rated outcomes forms part of Thilo Schuler’s **PhD**.  

In terms of technical platform, we use the well-known [REDCap system](https://www.project-redcap.org/) integrated with our in-house clinical research system. It was a several year **journey** to arrive at this solution:
-	Thilo Schuler developed an EMR-integrated [prototype ePRO system](https://www.researchgate.net/publication/271133402_PROsaiq_A_Smart_Device-Based_and_EMR-Integrated_System_for_Patient-Reported_Outcome_Measurement_in_Routine_Cancer_Care) in 2013 while a resident medical officer at Wollongong Hospital. This system was the basis for the [PROMPT-Care system](https://www.jmir.org/2020/10/e19685/).
-	When starting as an advanced trainee at NSCC in 2015 we adopted a similar system allowing collection of ePROs on iPads in the waiting room. However, completion rates (35-59%; [RANZCR ASM 2017](https://webcast.ranzcr.com/Mediasite/Catalog/Mobile/FolderPresentation/1e393b2b749149f79d6723cdbe177cbe21/e699ab5f-d576-4619-8f5d-0c448cee0674/dd0307a4d252472483b4c6be6556b2cf1d/)) were deemed too low for use in routine care.
-	**Logistical bottle necks** in the waiting room and understandably lower “appetite” for completing surveys by patients who are about to see their oncologist for first time were identified as biggest barriers rather than technology savviness of patients.
-	In 2017 we searched for vendors offering ePRO systems that allowed off-site collection hoping that this would improve completion rates. Unfortunately **no vendor** selling their system in Australia at the time **fulfilled our requirements**. Main missing features were ability to define ePROs ourselves (form designer) and/or API support (for integration).
-	We re-discovered **REDCap**, after having previously felt it lacked usability for routine care consultations from the clinician’s perspective, as an excellent **“ePRO survey engine”**  and re-implemented our in-house clinical research system in 2018 to allow integration of REDCap for ePRO collection and display.
-	Since 2019 we have been using ePROs routinely as part of our prostate cancer new patient and follw-up clinic.
