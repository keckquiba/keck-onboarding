<p align="center">
  <img src=./assets/img/keck.jpg>
</p>

# Week 8: Close Access Gaps and Deepen Workflow Knowledge​

### ***Summary:***
This week was an intentionally lighter week than last week. Like physical training, it's important to allow for periods of "recovery" after intense training blocks. In the case of learning, these recovery block can be useful to allow time for reviewing of newly learned concepts to better bind them to memory. 

A decent chunk of time this week was spent organizing and cleaning up notes. In my experience, this adds to the learning process and is similar to code clean-up. When you maintain a code base, it allows you to re-read the code and re-digest it(Provided the codebase isn't a mess and is readable). Even just simple re-factors for the sake of readability will force a developer to try to understand the code again. 

Aside from notes and review, valuable topics covered this week were as follows:
- Modality onboarding
  - Understanding information hand-off between Imaging IT and vendor field engineers
  - Connecting modalities to ***DCMSys*** and gaining understanding routes  
  - Practice with this topic started last week with the C-arm and XR portable at the **Arcadia Clinic**, and the XR portable at **PMOB**. I'll be going back to Arcadia to attempt to configure the XR portable again. The portable was re-configured to pull `MWL` from ***DCMSys***. `DICOM` storage destination is still pointing to PACS. I need to point it to the router
  - ~~Sometime next week, I need to return to **PMOB** to re configure the XR portable. Last week I used a ***DCMSys*** route that sends to both ***Synapse*** and ***Radimetrics***. Robert is aware of this error and has built(?) a new route that only sends to ***Synapse***.~~
    - Double check with Robert during next week's DCMSys review
- Radimetrics
  - Attended the vendor training and gained an understanding about required data for dosage calculations
  - Learned how to troubleshoot rejected studies
  - Need more review here still
- Looped in to issue with **UAH** rads wanting to stick with their personal reporting templates
  - Keck is making an effort to standardize across the enterprise
  - Specific information and statements are required(by who?) to properly bill for reports. Personalized templates often do not meet these standards
  - 

## 10/26
 - [x] [Synapse dev testing](./syn-dev-testing.md)
 - [x] Samsung onboarding
   - [x] [DMWL spread sheet]() updated
 - [ ] Synapse foundations training
 - [x] Ambra tickets

## 10/27
- [x] Start worklist presentation draft
- [x] Ambra tickets

## 10/28
- [x] reach out to infosec to fix delinea again
- [ ] onboard new radiologists
  - [Notes](#new-rad-access-checklist)
  - Pending some users in AD and/or Cerner
- [ ] Troubleshoot magview report not crossing to powerscribe
- [ ] Follow up on UAH templates
- [x] learn to run case logs for radiologists
- [x] Ambra tickets

## 10/29
- [x] Worklist document draft
- [x] schedule time for arcadia clinic fuji portable
- [x] SME meeting with Ryan
  - [x] Aria
  - [x] DCMSys monitoring
- [ ] onboard new radiologists
- [x] Ambra tickets
- [x] Unlock reports in PSRadportal

## 10/30
- [ ] Arcadia clinic portable
- [ ] Schedule f/u meeting with Robert for DCMSys
- [ ] Review and create notes for DCMSys
  - [ ] Ask about Lua scripts
- [ ] onboard new radiologists


### MISC NOTES
magview reports go to where?
cl:
proda_transcription > results


# New Rad Access Checklist
```
NPI = int
NPI in Cerner = bool
User Name in AD = char
```
- [ ] mpower 
- [ ] pacs 
- [ ] fuji eis 
- [ ] powerscribe 
  - [ ] NPI in cerner
    - If NPI not in Cerner, do not activate locations for user that use Cerner for EMR (UAH, UPHC)
- [ ] ad groups 

[NPI Lookup](https://npiregistry.cms.hhs.gov/search)

[<< Week 7](./week_7.md) | [Week 9 >>](./week_9.md)
<br></br>
***[Home](./README.md)***
