# Evaluation

- **Status:** In Progress
- **Application Document:**  https://github.com/w3f/Grants-Program/blob/master/applications/SydTek.md
- **Milestone:** 2
- **Kusama Identity:** Address
- **Previously successfully merged evaluation:** [M1](https://github.com/w3f/Grant-Milestone-Delivery/blob/master/evaluations/sydtek_1_semuelle.md)

| Number | Deliverable | Accepted | Link | Evaluation Notes |
| ------ | ----------- | -------- | ---- |----------------- |
|      0. | Rights  |<ul><li>[x] </li></ul>|https://github.com/jgophd/Developed-Materials-and-Raw-Data | |
|  **1.** | Interviews |<ul><li>[ ] </li></ul>| [link](https://github.com/jgophd/Developed-Materials-and-Raw-Data/blob/main/Interview%20Transcripts%20Transcribed%20by%20Otter.ai)  | One interview, other transcripts extracted from youtube |
| **1a.** | Specific Coverage |<ul><li>[ ] </li></ul>| [link](https://github.com/jgophd/Developed-Materials-and-Raw-Data/blob/main/Digital%20Inheritance%20in%20Web3:%20A%20Case%20Study%20of%20Soulbound%20Tokens%20and%20the%20Social%20Recovery%20Pallet%20within%20the%20Polkadot%20and%20Kusama%20Ecosystems) | Some changes requested |

**General Notes**


Interviews:

In the requirement, you say: "The SydTek team will interview members of Phala Network, RMRK and Parity Technologies to identify ways users can leverage SBTs and the Social Recovery pallet within the Polkadot and Kusama ecosystems for digital inheritance.".

The first interview is with Joshua Waller from Phala Network, a member of the SydTek team, as reported in your application: https://github.com/w3f/Grants-Program/blob/master/applications/SydTek.md. I found the video here: https://www.youtube.com/watch?v=AgW1Dc-zBMY.


The second interview is with Tyler Doussan from Safe Heaven. I was not able to find your interview with him. However, I notice in the transcript some copy-and-paste transcripts from podcasts and youtube channels. Could you explain that?

The transcript from this interview was added as we cited that interview in the study as you can now cite YouTube interviews in academic journal articles. As we initially researched SafeHaven due to the fact that they have a similar product on VeChain, after speaking with Jürgen Schouppe, the CEO of SafeHaven, the team is looking to integrate the suggested recommendations mentioned in the study to develop a solution on Kusama using the social recovery pallet. If you need a formal interview with Jurgen or Tyler to discuss these plans, we can do that and upload it to the submission.


Starting from line 389 the transcript was extracted from this podcast: https://podcasts.apple.com/us/podcast/safe-haven-pioneering-decentralized-digital-inheritance/id1593028990?i=1000565482923


Starting from line 490 of the transcript, they were extracted from this youtube video (https://www.youtube.com/watch?v=oenymBrwfLw).


There are also transcripts from this video Substrate Social Recovery Pallet Code Walkthrough with Joe Petrowski and Shawn Tabrizi (https://www.youtube.com/watch?v=rRnWKDaTb9E).


Could you provide explanations on why did you copy and pasted transcripts of youtube videos on a deliverable that should be interviews conducted by SydTek with Phala Network, RMRK and Parity Technologies members?

Joshua Waller and Zoe Meckbach of Phala made the introduction to Mark Ryan of RMRK to set up an interview with their team, but we were unable to coordinate anything. I also sent a message to Shawn Tabrizi on 11/14/22 to request an interview on the social recovery pallet given he was the lead developer that discussed the pallet. As I didn’t receive a response from Shawn, as a contingency, we included the transcripts from Shawn’s interview with Joe Petroski as well as his presentation. As with the SafeHaven interviews, we included these transcripts because we cited these interviews within the study. 

The paper is well-written and easy to understand. Some small requests here:

1. In the section THE SOCIAL RECOVERY PALLET, Fig 1 is not available in the text. Please include the image in the deliverable.

Please see the figure below. I also included it in the deliverables. 

<img width="243" alt="image" src="https://user-images.githubusercontent.com/77424673/214847872-cfebd323-21e7-4175-9911-1c161ed44e19.png">
FIGURE 1. An overview of the pubkey change process

3. In the section EXECUTING THE DIGITAL INHERITANCE PROCESS ON POLKADOT AND KUSAMA, the schema described starts with "the digital executor could submit a deposit to initiate the social recovery". My question is, how the digital executor will know that he/she needs to start social recovery?

Similar to the Web2 world, when someone passes, the beneficiaries or trustees will notify the executor of the estate that the person has passed - the beneficiaries want the assets and it is the trustees responsibility to ensure things are in order upon the death of the testator. The same will hold true in the Web3 world as the testator will have worked with his or her trustees and their beneficiaries before death to set up wallets and understand the digital inheritence process beforehand.

5. In the section ACKNOWLEDGEMENT, it must include a notice that the paper was supported by the web3 foundation, as discussed in the application. 

Below is the full acknowledgement section:
ACKNOWLEDGEMENT
The authors would like to thank Joshua Waller, Ray Lu, and the other team members from Phala and Bit.Country from the Polkadot and Kusama ecosystems for their thoughts and input into this study. The authors would also like to thank Charlotte McCurdy of Perley-Robertson, Hill & McDougall for providing input from a legal aspect on digital asset inheritance. This work was supported by a research grant from the Web3 Foundation. 

7. We expect for the paper delivery that a PDF should be provided and a preprint should be registered in some archive (ex. [arvix](https://arxiv.org/)). This could be performed in the next milestone if it is more convenient for you.
The preprint to ARXIV can be found below:
https://arxiv.org/submit/4707279/view
