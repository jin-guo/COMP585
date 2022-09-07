# [COMP585_Fall2022] Intelligent Software Systems

The syllabus is mostly inherited from the previous years. Will be updated until the start of the semester.

## General Information
|||
| :---: | ------------- |
| Instructor    | [Jin Guo](http://jguo-web.com/index.html)  |
| TA | [Deeksha Arya](https://cs.mcgill.ca/~darya2) |
| Class Time    | MW 01:05 pm-02:25 pm |
| TA Office Hours    | TBD |
| Location      | ENGMC 103  |
| Discussion Forum | Slack (link on MyCourses) |


- The lectures consist of many in-class activities to motivate discussion and collaborative learning. **In-person participation is required**.
- Occasionally, if there are unforeseen reasons that prevent you from joining the lectures in person, we will try to accommodate. Please contact us prior to the lecture.



## Description
This course is going to explore how to design and build an intelligent system from a software engineering perspective, from requirement gathering and analysis to deployment and maintenance. We will also touch AI ethics and its implications to design.

## Prerequisite
COMP 303, COMP 424/COMP 551 (or equivalent background)

## Reference Material
We will not concentrate on any particular resources. Instead, the readings will include content from book chapters, research papers, blog posts, talks, etc. The pointers to those content will be added to the schedule later.

- **Books**: 
  * [Thinking in Systems: A Primer](https://www.amazon.ca/Thinking-Systems-Primer-Donella-Meadows/dp/1603580557) (Chapter scans will be shared through OneDrive links)
  * [Human Compatible: AI and the Problem of Control](https://people.eecs.berkeley.edu/~russell/hc.html) (Chapter scans will be shared through OneDrive links)
  * [Design Justice](https://mitpress.mit.edu/books/design-justice) (open access) 
  * [Building Intelligent Systems <em>A Guide to Machine Learning Engineering</em>](https://learning.oreilly.com/library/view/building-intelligent-systems/9781484234327/) (access through McGill Library)

## Assessment and Evaluation (Tentative)

|  Assessment Method | Weight |
| :---: | :---: |
|  Participation | 10% |
|  Reading Reports | 10% |
|  Assignment |  45% |
|  Final Project | 35% |

- Any form of plagiarism, cheating is strictly banned during midterm or final exam. Integrity is crucial to this course and your future career. Any violation against academic integrity will be taken very seriously. For more information, please refer [here](https://www.mcgill.ca/students/srr/academicrights/integrity).


## Schedule (Tentative)
*Subject to adjustments*

| Lecture | Date | Content | Reading | Note |
| :---: |:---:| :---: | :---: | :---: |
|1	|  31 Aug  | [Introduction](Slides/1-Intro.pdf) | BIS book: Chapter 1, 2 <br> TIS book: Intro ([Onedrive](https://mcgill-my.sharepoint.com/:b:/g/personal/jin_guo_mcgill_ca/EVxp4i8fWBdPjW7wE2vxxSQB6uJ2dQZV-Y1eMOf9fZn6CQ?e=80avDh)) |  |
|2	|  7 Sep  | [Intelligent Systems and Software Engineering](Slides/2-IS_SE.pdf)  | Human Compatible: Intelligence ([Onedrive](https://mcgill-my.sharepoint.com/:b:/g/personal/jin_guo_mcgill_ca/EWpJNhlrUy1Bm8_VZVEFP1YBZWPLz07VUSaaBRV1o65j9w?e=mmyjQO)) <br> [Quality Attributes](https://resources.sei.cmu.edu/asset_files/technicalreport/1995_005_001_16427.pdf)| |
|3	|  12 Sep  | ML Model Quality| BIS book: Chapter 19, 20 <br>[Beyond Accuracy: Behavioral Testing of NLP Models with CheckList](https://arxiv.org/pdf/2005.04118.pdf)<br>[Model Cards for Model Reporting](https://dl.acm.org/doi/pdf/10.1145/3287560.3287596?casa_token=18FG8CITJy4AAAAA:ioP5uVyMqxHYfdMum0ZFqzftEHa9_ddDXLHNau9X_ZiGCrzHXE4DVSpRDK6mARu6iEywkrEaO_cT) |  |
|4	|  14 Sep  | From Model to System | [Software Engineering for Machine Learning: A Case Study](https://www.microsoft.com/en-us/research/uploads/prod/2019/03/amershi-icse-2019_Software_Engineering_for_Machine_Learning.pdf)<br>[Hidden Technical Debt in Machine Learning Systems](https://papers.nips.cc/paper/2015/file/86df7dcfd896fcaf2674f757a2463eba-Paper.pdf)<br> TIS book: Chapter 4 Why Systems Suprise Us ([Onedrive](https://mcgill-my.sharepoint.com/:b:/g/personal/jin_guo_mcgill_ca/EbxmmASBbx9KsdwGgZ2ZULQBH2oMwV3TYp103WY7cWXAPg?e=hXFdgw)) |  |
|5	|  19 Sep  | Data Acquisition & Management | BIS book: Chapter 9 <br>[A Survey on Data Collection for Machine Learning: A Big Data - AI Integration Perspective](https://ieeexplore.ieee.org/abstract/document/8862913) |  |
|6	|  21 Sep  | Requirement and AI - 1 | [Requirements Engineering for Machine Learning: Perspectives from Data Scientists](https://arxiv.org/pdf/1908.04674.pdf)|  | |
|7	|  26 Sep  | Requirement and AI - 2| [Keynote talk by Amy Ko at RE 2021](https://youtu.be/yf1wfyfgXvA) |  |
|8	|  28 Sep  | Team and Collaboration | [Collaboration Challenges in Building ML-Enabled Systems: Communication, Documentation, Engineering, and Process](https://www.cs.cmu.edu/~ckaestne/pdf/icse22_seai.pdf) <br> [Data Scientists in Software Teams:State of the Art and Challenges](https://andrewbegel.com/papers/data-scientists.pdf)|  |
|9	|  3 Oct  | Data Quality | BIS book: Chapter 15| |
|10	|  5 Oct  | Continous Delivery and System Quality| [The ML Test Score: A Rubric for ML Production Readiness and Technical Debt Reduction](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/aad9f93b86b7addfea4c419b9100c6cdd26cacea.pdf)| |
|11	|  13 Oct (READING WEEK MakeUp Class)  |  Design for Human-AI Interaction (UX) | [Guidelines for Human-AI Interaction](https://www.microsoft.com/en-us/research/publication/guidelines-for-human-ai-interaction/) <br> [Human-Centered Artificial Intelligence: Three Fresh Ideas](https://aisel.aisnet.org/thci/vol12/iss3/1/)| |
|12	|  17 Oct  |  Design - Visualization | [Will you accept an imperfect AI? exploring designs for adjusting end-user expectations of AI systems](https://www.microsoft.com/en-us/research/uploads/prod/2019/01/chi19_kocielnik_et_al.pdf)<br>[When (ish) is my bus? user-centered visualizations of uncertainty in everyday, mobile predictive systems](https://idl.cs.washington.edu/files/2016-WhenIsMyBus-CHI.pdf)<br>[The state of the art in integrating machine learning into visual analytics](https://arxiv.org/abs/1802.07954)|  |
|13	|  19 Oct  | Design - Decision-making | [The Principles and Limits of Algorithm-in-the-Loop Decision Making](https://scholar.harvard.edu/files/bgreen/files/19-cscw.pdf)<br>[Judgment under uncertainty: Heuristics and biases](https://www.jstor.org/stable/pdf/1738360.pdf?casa_token=PEUwAsY9bNoAAAAA:i7KvVWYA73fJzugepP9xnVfBc_tCv1TWq884garHfyiwpR0kooepIGbSSfu__bxvaMYyMxTwGpCTCfzWrRXJI5-ghi44wtwX_WrGiSdQ2fKla6PhPH8) |  |
|14	|  24 Oct  | Design - Learning | [ArgueTutor: An Adaptive Dialog-Based Learning System for Argumentation Skills](https://dl.acm.org/doi/10.1145/3411764.3445781)<br>[Augmenting Scientific Papers with Just-in-Time, Position-Sensitive Definitions of Terms and Symbols](https://dl.acm.org/doi/10.1145/3411764.3445648) | |
|15	|  26 Oct  | Design - Creativity | [Creativity support tools: accelerating discovery and innovation](https://dl.acm.org/doi/10.1145/1323688.1323689)<br>[AI as Social Glue: Uncovering the Roles of Deep Generative AI during Social Music Composition](https://dl.acm.org/doi/10.1145/3411764.3445219)| |
|16	|  31 Oct  | Design - Inclusion  | [Disability-first Dataset Creation: Lessons from Constructing a Dataset for Teachable Object Recognition with Blind and Low Vision Data Collectors](https://www.microsoft.com/en-us/research/publication/disability-first-datasets/)<br>[Design Values: Hard-Coding Liberation?](https://design-justice.pubpub.org/pub/3h2zq86d/release/1) |  |
|17	|  2 Nov  | AI principles Overview | [Automated generation of storytelling vocabulary from photographs for use in AAC](https://aclanthology.org/2021.acl-long.108.pdf)<br>[Principled Artificial Intelligence: Mapping Consensus in Ethical and Rights-based Approaches to Principles for AI](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3518482) |  |
|18	|  7 Nov  | Safety|[Autonomous Vehicle Safety: An Interdisciplinary Challenge](https://ieeexplore.ieee.org/abstract/document/7823109)<br>[An Analysis of ISO 26262: Using Machine Learning Safely in Automotive Software](https://arxiv.org/pdf/1709.02435.pdf) | |
|19	|  9 Nov  | Security |[The AI-Based Cyber Threat Landscape: A Survey](https://dl.acm.org/doi/abs/10.1145/3372823) | |
|20	|  14 Nov  | Privacy | [SoK: Towards the Science of Security and Privacy in Machine Learning](https://arxiv.org/pdf/1611.03814.pdf) <br>[Designing privacy-aware internet of things applications](https://www.sciencedirect.com/science/article/pii/S0020025519309120?casa_token=gj30woV-fm4AAAAA:4XFjzxa8dhskuzkc1PSjTm8FFIXbj1DEp-MUPvtsWCyaYtvoSqzHuyeHy1QqXjtUvCu0k0OfHA)| |
|21	|  16 Nov  | Accountability/Auditing | [Closing the AI Accountability Gap: Defining an End-to-End Framework for Internal Algorithmic Auditing](https://dl.acm.org/doi/pdf/10.1145/3351095.3372873?casa_token=ETIdzxHvH-MAAAAA:DJKwhwzspR3Rb2Z2RuDMTDcl4L2te37a-4GdqkmRhPyC3zCLL0wledNr1v-HKnqrd4kIKeYGLRXQ) <br>[Toward Trustworthy AI Development: Mechanisms for Supporting Verifiable Claims (Section 2 and 3)](https://arxiv.org/pdf/2004.07213.pdf)|  |
|22	|  21 Nov  | Transparent and Explainability |[Explainable machine learning in deployment](https://dl.acm.org/doi/abs/10.1145/3351095.3375624) <br>[Designing Theory-Driven User-Centric Explainable AI](https://dl.acm.org/doi/pdf/10.1145/3290605.3300831?casa_token=TvYM-Ik6lakAAAAA:bLF4QklCqOopi6TBhZekzVhfmV2o226OcvSGSYQ5VYwh7mD1gRBkxMDbZ7no1oQRnNMw0uMJoUGX) |  |
|23	|  23 Nov  | Fairness - 1 | [Improving Fairness in Machine Learning Systems: What Do Industry Practitioners Need?](https://dl.acm.org/doi/10.1145/3290605.3300830)<br>[Co-Designing Checklists to Understand Organizational Challenges and Opportunities around Fairness in AI](http://www.jennwv.com/papers/checklists.pdf)|  |
|24	|  28 Nov  | Fairness - 2 | |  |
|25	|  30 Nov  | Wrap up | [“The Human Body is a Black Box”: Supporting Clinical Decision-Making with Deep Learning](https://dl.acm.org/doi/pdf/10.1145/3351095.3372827) |  |
|26	|  5 Dec  | Presentation | |  |
 

# Credit:
The content regarding engineering aspects is greatly inspired by [CMU 17-445/645: Software Engineering for AI-Enabled Systems](https://ckaestne.github.io/seai/) which is developed by [Christian Kästner](http://www.cs.cmu.edu/~ckaestne/) et. al.

# License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />Unless otherwise noted, the content of this repository is licensed under a  <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

