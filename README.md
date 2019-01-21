# <img src="http://www.rice.edu/_images/rice-logo.jpg" width=180> Comp427, Spring 2018, Homework 1
## Rational Paranoia
The homework specifications, as well as the corresponding course slide decks,
can be found on the [Comp427 Piazza](https://piazza.com/class/jqifhp864b37ju).
This assignment is due **Thursday, January 17 at 6 p.m.**

You will do this homework by editing the _README.md_ file. It's in
[MarkDown format](https://guides.github.com/features/mastering-markdown/)
and will be rendered to beautiful HTML when you visit your GitHub repo.

## Student Information
Please also edit _README.md_ and replace your instructor's name and NetID with your own:

_Student name_: Yijun HE

_Student NetID_: yh61

Your NetID is typically your initials and a numeric digit. That's
what we need here.

_If you contacted us in advance and we approved a late submission,
please cut-and-paste the text from that email here._

Because of late registration (sorry about that), I can only see this github repository on Jan 19. The late submission request is not approved yet. Below is the text from Nathan.

> Dan your thoughts?
> — :: Nathan Dautenhahn :: — 
> On Jan 18, 2019, at 5:23 AM, <yijun.he@rice.edu> <yijun.he@rice.edu> wrote:
> 
> Hi Nathan,
>  
> I have found the mail sent from Piazza, I can see the course now. Please ignore the previous mail.
>  
> May I request a 2 days late for HW1 because the late registration? I just know that the due date of HW1 is Thursday, when I can see the course in Piazza
>  
> Many thanks,
> Yijun


## Problem 1
- Scenario: Documents
- Assumptions:
  - The documents are very important to the law firm. Lawyers need this document to track the cases of each customer. The documents are digitalized and stored in the documents management system.
- Assets:
  - The **confidentiality** of the documents. The content of the documents cannot be accessed by anyone unauthorized. 
  - The **authenticity** of these documents. The documents must be uploaded or modified by the authorized people in the law firm or the customers.
  - The **availability** of these documents. The documents should be always available to the person when he or she has the right the access it. 
  - The **integrity** of these documents. The documents should be exactly what they are supposed to be looked like. All creations, modification and deletion operations should be recorded.
- Threats:
  - The documents could be accessed by someone unauthorized, in or out of the law firm, which breaches the confidentiality.
  - The documents could be created or modified by someone unauthorized, so the user of the documents would misled by the inauthentic information. That breaches the authenticity.
  - The documents could be unavailable because one of the following reasons: any damage to the hard drives causing data lost, network issue, server/system issue, etc,.
  - The documents could unintended modified by someone or some programs so that they are not same as what they should be looked like.
- Countermeasures:
  - To ensure the confidentiality, an user login system is one of the efficient solution. The users accounts and their privilege should be managed by the system administrators and all the operations of admins and users should be recorded. The documents that exported from the system should be protected by the password and automatically expires in a certain period of time.
  - To ensure the authenticity if the documents, the privilege of uploading and modifying of the documents should be strictly controlled. Every version of the documents should be saved in a separated backup system.
  - To ensure the availability, a disaster recovery mechanism should be setup in a distant location. The running system should synchronize the data to the backup system. When the running system is unavailable, the backup system would be automatically or manually brought up.
  - To ensure integrity, we can record every modification detail of each document, like what we can see in a file history of a GitHub repository. When a document is modified unintended, we can track the modification history and detect the error very soon.

## Problem 2
- Scenario: {Stadium|TSA|Documents|Grading|G20}
- Assumptions:
  - explain_your_assumptions
- Assets:
  - explanatory_paragraph
  - explanatory_paragraph ...
- Threats:
  - explanatory_paragraph 
  - explanatory_paragraph ...
- Countermeasures:
  - explanatory_paragraph
  - explanatory_paragraph ...

## Problem 3
- Scenario: Your choice (give a brief explanation)
- Assumptions:
  - explain_your_assumptions
- Assets:
  - explanatory_paragraph
  - explanatory_paragraph ...
- Threats:
  - explanatory_paragraph 
  - explanatory_paragraph ...
- Countermeasures:
  - explanatory_paragraph
  - explanatory_paragraph ...

