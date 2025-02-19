# Call for Presentations

##  The Third ROSE Festival, ESEC/FSE 2019
##  Recognizing and Rewarding Open Science in Software Engineering  

<img align="center" src="etc/img/header.png">  

Submissions due ~~July 24, 2019~~ (we are still accepting submissions).  
A track at [ESEC/FSE 2019](https://esec-fse19.ut.ee/).

[Submit via Easychair](https://easychair.org/conferences/?conf=rosefse19) (See instructions below)

- Chairs and organizers:
     - Gregory Gay, Chalmers | University of Gothenburg, Sweden
     - Tim Menzies, NC State University, USA
- Steering Committee:
     - Robert Feldt,	Chalmers | University of Gothenburg, Sweden
     - Tim Menzies, NC State University, USA
     - Thomas	Zimmermann,	Microsoft Research, USA
- Program Committee:
     - Neil	Ernst,	University of Victoria, Canada
     - Robert	Feldt,	Chalmers | University of Gothenburg, Sweden
     - Daniel	Graziotin,	University of Stuttgart, Germany
     - Martin	Monperrus,	University of Lille & INRIA, France
     - Chakkrit	Tantithamthavorn, Monash University, Australia
     - Sira	Vegas,	Universidad Politécnica de Madrid, Spain
     - Thomas	Zimmermann,	Microsoft Research, USA
 
## Aim

The ROSE festival is a world-wide salute to replication and reproducibility in SE (for a definition of these terms, see the end of this CFP). 
The aim of the ROSE Festival is to create a celebration of open science in Software Engineering. This is a venue where researchers can come together to discuss issues in availability, replication, and reproduction of research data and research results, and where researchers can receive public credit for facilitating and participating in open science.

ROSE is needed since most current conferences only evaluate research artifacts generated by that venue’s accepted papers. This makes it difficult for research papers to earn credit for replication and reproduction by other researchers (since no other team of researchers has yet to see this new result).

Enter ROSE. ROSE is a 90 minute session comprising lightning talks by researchers presenting replicated and reproduced results or discussing issues in and solutions for open science in SE, followed by a panel discussing issues of replication in software engineering. Presentations can be about any prior SE publication (and is not restricted just to results from ESEC/FSE’19).

Note that:

- ROSE is a non-archival forum. Material presented at ROSE may also be submitted to other forums.
- Journal special issues are being planned to take the better ROSE-results to an archival publication. Venue TBD but, perhaps, the Empirical Software Engineering Journal.

## HOW TO SUBMIT:

Submit your proposal to [Easychair](https://easychair.org/conferences/?conf=rosefse19).

Submissions to ROSE are an abstract (one page pdf, max) for a proposed lightning talk (2-5 mins). Each talk must be about two things:

- A prior SE publication (Paper1) which has been replicated/reproduced.
- Substantive evidence that that parts of Paper1 has been replicated/reproduced. This evidence must be substantive e.g.
     - A recent research SE paper (Paper2)
     - A Url links to an as yet unpublished pre-print

Note that Paper1 and Paper2 can come from any SE venue (ideally, peer-reviewed but if otherwise, reviewers will assess the paper on a case-by-case basis).

We also welcome methodological (meta) talks that help promote, facilitate or increase understanding about open science, replication and reproduction of software engineering research.

To facilitate easy reviewing, authors are encouraged to following the following format for their abstract:

- TITLE: “A [Partial] (Replication|Reproduction) of XYZ”. Please add the term “partial” to your title if only some of the original work could be replicated/reproduced.
- WHO: name the original authors (and paper) and the authors that performed the replication/reproduction. Include contact information (e-mails). Mark one author as the corresponding author.
     - IMPORTANT: include also a web link to a publically avaialble URL directory containing (a)the original paper (that is being reproduced) and (b)any subsequent paper(s)/documents/reports that do the reproduction.
- WHAT: describe the “thing” being replicated/reproduced;
- WHY: clearly state why that “thing” is interesting/important;
- HOW: say how it was done first
- WHERE: describe the replication/reproduction. If the replication/reproduction was only partial, then explain what parts could be achieved or had to be missed.
- DISCUSSION: What aspects of this thing made it easier/harder to replicate/reproduce. What are the lessons learned from this work that would enable more replication/reproduction in the future for other kinds of tasks or other kinds of research.

Naturally, meta papers might need a different structure so if you are planning to do a meta talk, please contact the chairs.

## EVALUATION:

- Two PC members will review each abstract, possibly reaching out to the authors of the original Paper1. Abstracts will be ranked as follows:
    - If PC members do not find sufficient substantive evidence for replication/reproduction, the abstract will be rejected.  
    - Any abstract that is overly critical of prior work will be rejected (*).
    - The remaining abstracts will be sorted according to (a) interestingness and (b) correctness.  

The top 10 abstracts (or more, if there is time), will be invited to give lightning talks.

(*) Our goal is to foster a positive environment that supports and rewards researchers for conducting replications and reproductions.  To that end, we require that all ROSE abstracts and presentations pay due respect to the work they are reproducing/replicating. Criticisms of prior work is acceptable only as part of a balanced and substantive discussion of prior accomplishments.

## DEFINITIONS:

ROSE adopts the ACM artifact badging conventions. ROSE seeks replicated and reproduced results defined as follows:

<table>
<thead></thead>
<tbody(s)>
<tr><td><strong>Functional</strong>	</td><td align="center"> <strong>Reusable</strong> </td><td align="center"> <strong>Available</strong></td><td align="center"> <strong>Replicated</strong> </td><td align="center"> <strong>Reproduced</strong> </td></tr>
<tr><td>No Badge </td><td align="center"> <dl><img src="https://2019.icse-conferences.org/getImage/orig/red.jpg" alt=""></dl>  </td><td align="center"> <dl><img src="https://2019.icse-conferences.org/getImage/orig/green.jpg" alt=""></dl>	   </td><td align="center">  <dl><img src="https://2019.icse-conferences.org/getImage/orig/blue.jpg" alt=""></dl> </td><td align="center">  <dl><img src="https://2019.icse-conferences.org/getImage/orig/deepBlue.jpg" alt=""></dl> </td></tr>
<tr><td> <!--Functional--> Artifacts documented, consistent, complete, exercisable, and include appropriate evidence of verification and validation </td><td align="center"> <!--Reusable--> Functional + very carefully documented and well-structured to the extent that reuse and repurposing is facilitated. In particular, norms and standards of the research community for artifacts of this type are strictly adhered to. </td><td align="center"> <!--Available-->  Functional + placed on a publicly accessible archival repository. A DOI or link to this repository along with a unique identifier for the object is provided. </td><td align="center"> <!--Replicated--> Available + main results of the paper have been obtained in a subsequent study by a person or team other than the authors, using, in part, artifacts provided by the author. </td><td align="center"> <!--Reproduced--> Available + the main results of the paper have been independently obtained in a subsequent study by a person or team other than the authors, without the use of author-supplied artifacts.</td></tr>
</tbody>
</table>

**IMPORTANT POINT:** Replication is more than just "they downloaded my scripts and ran exactly those". There must be something changed in the replication work (but perhaps that change is not very large).
