<p align="center">
  <img src=./assets/img/keck.jpg>
</p>

# Week 7: Guided Support, Ticket Practice, and App Documentation​

***Weekly goal:** Start guided support, shadow break/fix, build Application Doc 2, and refine access/server tracking.*

***Weekly deliverables:** PACS cheat sheet v1, Application Doc 2 draft/complete, supervised ticket notes, late-person notes, and access/server list.​*

***Mentor:** Rick/Patricia/ SMEs: Robert, Mike​*

| Day       | Focus | What to do | EOD Output |
|-----------|-------|------------|------------|
| Monday    | Review modality onboarding + continue rounding​ | - Schedule rotating daily meetings with Robert and Mike. | Modality questions closed; access gaps updated; App Doc 2 started.​ ​
||| - Review the completed modality onboarding process with an SME and shadow a setup if available. ​
||| - Continue radiology site rounding.​           
| Tuesday   | Refine PACS cheat sheet + shadow tickets​      | - Attend the weekly Imaging Team meeting. ​            | PACS cheat sheet updated; new INC shadow notes captured.​           
||| - Refine the PACS cheat sheet ​
||| - Review architecture and server request process. ​
||| - Shadow break/fix on new incoming incidents with the assigned team member. ​
||| - Begin Application Documentation 2.​
| Wednesday | Shadow late-person duties + server testing​      | - Daily meeting with SME           | Late support notes and server list updated.​           
||| - Locate Imaging Early and Late Schedule and shadow the late person to understand duties. ​
|||- Continue server access setup, server access testing​
|||- Continue Application Documentation 2.​
| Thursday  | Attempt low-risk ticket + HL7 training​      |            |            |
| Friday    | Complete App Doc 2 draft + weekly review​      |            |            |

10/19
------------------
- [x] Scheduled weekly meetings with Mike and Robert
  - [x] Schedule site intro at UAH with Mike
- [ ] Fill out the rest of Synapse app doc. Note gaps
- [x] Schedule meetings with Patricia to help fill out gaps app docs and go over hangin protocols
- [x] Abmra ticket
- [x] Synapse auto-logoff ticket
- [ ] Review archtecture notes
  - [ ] Prepare questions for Daniel
  - [ ] Schedule follow up meeting

- [x] Work with Jack to onboard CareStream portable
  - [x] Creat new modality onbaording [documentation]()
  - [x] Ticket assigned to me for Samsung portable 
  - Keck hospital will be demoing various portables from different vendors. I'll get hands on training for new modality onboarding
- [x] Respond to service engineer, Jacob, with filled out installation checklist. Add installation to the calendar for next week (10/26)
- [ ] Delinea RDP folder
  - Dominik(IAM) placed a ticket with Sail point to create an RDP account for my priv. Infosec needs to approve

10/20
--------------------------
- [ ] UAH templates 
- [ ] HL7 Training
- [x] Synapse dev env testing
- [x] magview training with mike
  - [ ] install magview test
- [x] follow up on delinea folders issue
- [x] update modality xls with device info provided by Jacob

10/21
--------------------------
- [x] UAH rounding
- [x] Delinea folders fixed!
- [x] Arcadia Specialty clinic modality trouble shooting and testing
  - [x] new c-arm pulls `MWL` from `DCMSys`
  - [x] new c-arm `DICOM STORE` points to `DCMSys`
  - [x] fuji portable pulls `MWL` from `DCMSys`
  - [ ] fuji portable `DICOM STORE` points to `DCMSys`
    - return on another day to get this setup
- [ ] PMOB portable connection
  - return on another day to get this setup
  - storage points directly to synapse
  - mwl doesnt work
  - device location info still set to previous location
  - need to find AET

10/22
--------------------------
- [x] DCMSys intro with robert
- [x] Questions for Patricia from last week
  - [x] When we have 3D order, does it need to be marked complete in order for the radiologist to sign off on the report for the original order? This might have just a misunderstanding between the reading room and the radiologist
  - This was a misunderstanding. The original study can be completed
  

- [x] What is the `Dictated` status indicate in Synapse? I understand that the exam is marked `Final` when a radiologist signs off on the report in PS360. What triggers a status change to `Dictated`?
  - A draft changes the status to `Dictated`

10/23
--------------------------
- [x] Edit and format Synapse notes and kbs
- [ ] [Review DCMSys](./dcmsys.md)
- [x] PMOB portable set up


[<< Week 6](./week_6.md) | [Week 8 >>](./week_8.md)
<br></br>
***[Home](./README.md)***