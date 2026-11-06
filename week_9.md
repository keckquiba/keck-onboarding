<p align="center">
  <img src=./assets/img/keck.jpg>
</p>

# Week 9

### ***Summary:***
The main topics covered this week were DCMSys, radiologist training, and the worklist presentation.

I'll be slowly taking responsibility for the Synapse training sessions for radiologists. I've been learning the onboarding process (completing radiologist onboarding STASKS and using those tickets to properly provision and set up radiologists in Synapse and PowerScribe) and observing the live training sessions that Patricia hosts. Next week we have at least 3 scheduled training sessions. I will be driving the Synapse portion of the training and continue to observe and learn the training process for the PowerScribe portion. 

DCMSys does not seem like a big priority for my responsibilities as of yet but I find the application very interesting, so I'm trying to squeeze in some learning when I can. I had a second meeting with Robert this week where we went a bit more in depth with how the DWML router responds to worklist requests, as well as how and why the DICOM router is set up differently (DWML has 1 entry point vs many entry points in the DICOM router) 

I've made some progress on the presentation and met with Rick for feedback. The information I have so far is good but the flow of the presentation already needs work. Rick has provided a guide to use, so I'll use that as a new draft and start adding editing from there. Patricia and I needed to make some changes to the BCO worklists. Editing worklists has allowed me to learn *how to build* the worklists, and continuing working on them is providing good opportunities for me to learn more about *why* we need so many worklists. As I learn more about worklists and Synapse in general I can better put together my worklist presentation.

I'm also slowly getting familiar with Patricia's meetings with clinical staff. We have meetings with the reading room as well as management for exam QA purposes. These meetings involve examining orders that may need corrections. Some of the follow up work for us would be to move exams and reports. The management meeting is getting me acquainted with CPT, CDM and ICD-10 codes.

# 11/2
-sick day-

# 11/3
- [ ] resident img link requires user to login every time
- [ ] UAH templates get cloned from Keck templates and only update procedure codes and contrast fields
- [x] Test synapse img link
- [x] dcmsys part 2
- [x] check on new rads in AD and cerner
- [ ] update worklist power point

# 11/4
- [ ] uah temp
- [x] f/u with tac
- [x] pp presentation
- [x] training with pourjabbar
- [x] training with riv

# 11/5
- [ ] compile rad training notes
- [ ] work on presentation
- [ ] review DCMSys
- [ ] UAH templates
- [ ] UAH technologist workflow
- [x] BCO worklist clean up
  - BCO Clinician workflow:
    - Some of the ordering Drs are not Rads but they will still read studies
    - In these cases, the Dr will write up a report in Cerner and copy/paste into PACS.
    - Since these exams are now read, we need to make sure they don't end up on a rad's worklist
    - When a clinician puts a report into the notes section of the powerjacket, the study status does not change **(?)** therefore it will remain on a radiologist's worklist in a typical workflow
    - In our current setup, exams ordered by these clinicians don't hit the radiologist worklists by default
    - Upon the clinician's request, the technologist will change the study priority to "\<Specialty> to read "
    - This will place it on a rad's worklist
- [x] sante install
- [x] spin tech install
- [x] Radiologist worklist for ACR
- [x] Orderable CPT/CDM cleanup meeting

# 11/6

- [ ] Weekly summary
- [ ] Complete rad training notes for monday
- [ ] Worklist presentation progress
- [ ] Train with Patricia
- [ ] Observe weekly exam review and try to understand the work being done in these meetings
  - CRI sends a spreadsheet to Lippi and Krystal with comments on potential issues with exams. Some examples of issues:
    - Wrong exam was billed
    - CPT code associated to an exam is incorrect
    - Auto bill items missing
  - Sometimes the result of these issues is that a new order needs to be built or an existing order needs to be renamed.
  - Do we need to update procedure codes in PowerScribe or Synapse when this happens
  - If an incorrect order was placed altogether, a new order will be dropped and we will move the images to the newly placed order. We will also need to move the report
- [ ] Intro to test scripts for Synapse 7.4.320

[<< Week 8](./week_8.md) | [Week 10 >>](./week_10.md)
<br></br>
***[Home](./README.md)***