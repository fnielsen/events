#About
This file hosts my submissions to [PIDapalooza](http://pidapalooza.org/), which is to take place on November 9-10, 2016, in Reykyavik. Note that these are topics I would like to discuss, not necessarily topics I have done research about.

- An API for ethics: so far, most of the ecosystem of ethical review of past, present and future research is basically hidden. This is a barrier to communicating ethical aspects of research, establishing best practices and standards, and educating researchers and the public about this topic. Assigning PIDs to important components of the ethical review process (e.g. [IRB](https://en.wikipedia.org/wiki/Institutional_review_board) or other ethics committee, review requests, reviews, IRB decisions) could pave the way for ethical aspects of research to be included more prominently in research communication.

  - examples:
    - ["The proposed investigation received the approval of the Ethics Committee of the United Oxford Hospitals."](https://doi.org/10.1111/j.1365-2044.1971.tb04793.x)
    - ["The study was approved by the ethics committee of the hospital, and the patients gave informed consent."](https://doi.org/10.1056/NEJM199010113231505)
    - ["The project was approved by two local Ethics Committees and one national committee"](https://doi.org/10.1177/030006057300100505)
    - ["The relevant ethics approval for this study was granted by a Department of Primary Industries NSW Animal Ethics Committee of qualified scientific and lay members (AEC Number 100802/04)"](https://doi.org/10.1186/s40317-016-0107-6)
    - ["The data collected anonymously will be made available to any research group in the world following the data-sharing agreement initiative (http://www.wellcome.ac.uk/News/Media-office/Press-releases/2016/WTP060169.htm), provided that they have a clear, non-redundant research question and a biomedical research Ethics committee approval"](https://epgl.unige.ch/zika-in-pregnancy-registry/)
    - ["Does your work need IRB approval? Better check, says author of retracted paper"](http://retractionwatch.com/2016/09/30/does-your-work-need-irb-approval-better-check-says-author-of-retracted-paper/)
    - [timeline "ethics committee" vs. "informed consent"](https://books.google.com/ngrams/graph?content=%22ethics+committee%22%2C%22informed+consent%22&case_insensitive=on&year_start=1800&year_end=2000&corpus=15&smoothing=3&share=&direct_url=t4%3B%2C%22%20ethics%20committee%20%22%3B%2Cc0%3B%2Cs0%3B%3B%22%20Ethics%20Committee%20%22%3B%2Cc0%3B%3B%22%20ethics%20committee%20%22%3B%2Cc0%3B.t4%3B%2C%22%20informed%20consent%20%22%3B%2Cc0%3B%2Cs0%3B%3B%22%20informed%20consent%20%22%3B%2Cc0%3B%3B%22%20Informed%20Consent%20%22%3B%2Cc0%3B%3B%22%20Informed%20consent%20%22%3B%2Cc0%3B%3B%22%20INFORMED%20CONSENT%20%22%3B%2Cc0)
   
 - questions:
    - Which aspect of the research triggered the need for ethics approval?
    - How can I find the relevant documentation (e.g. "AEC Number 100802/04" or the informed consent forms)?
    - What options did the relevant Ethics Committee(s) have to choose from?
    - Was there any discussion within the Committee?
    - Was there any discussion with the team who had requested the approval?
    - Was there any modification to the request as a consequence of the approval process?
    - How to find past approvals or rejections for similar research?

 - principles:
    - ["The research protocol must be submitted for consideration, comment, guidance and approval to the concerned research ethics committee before the study begins. This committee must be transparent in its functioning, must be independent of the researcher, the sponsor and any other undue influence and must be duly qualified."](http://www.wma.net/en/30publications/10policies/b3/)

- Should each version of a research object get a new DOI?

- Data management plans are gaining ground as a component of the research funding process. However, they can also be used as implied by their name, i.e. to manage data. An important step in this direction would be to make data management plans machine actionable, which would mean to embed them into a network of datasets, repositories, grants, researchers, publications et al. that all have PIDs.

- The most common way of constructing an ontology is to define the terms and then (maybe) give them an identifier. Another way of going about it would be to start with identifiers for the terms, which could then be annotated with relations between the terms and between terms and the outside world if needed, and expanded to use natural language. The same could be done for the relations between terms, and I would like to discuss this approach on the basis of experiences gathered by contributing to Wikidata.

- Many libraries are curating a set of publications for which they know not just the string of characters that represents the authors' names, but also something about the authors' identities, though not necessarily using PIDs. ORCIDs are a way of bringing PIDs to authors of scholarly publications, but they do not go back sufficiently in time to cover all authors of scholarly publications throughout history, nor do they cover authors more broadly. Wikidata has both functionalities, and could serve as a bridge between authors that do and do not have an ORCID, at least for those that are notable by Wikidata standards.