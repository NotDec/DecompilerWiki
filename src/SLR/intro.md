# What is Systematic Literature Review?


## What is SLR?

The systematic literature review originates from medical research and social science but has been adapted and extended to Software Engineering.

To simplify:
- It is based on a defined search strategy that aims to detect as much of the relevant literature as possible.
- If some literature is excluded, it requires explicit inclusion and exclusion criteria to assess each potential primary study.
- Specify the information to be obtained from each primary study including quality criteria by which to evaluate each primary study.

**Other types of review**：

- Systematic Mapping Studies: plot the studies to find clusters and deserts to identify potential research areas or direct the focus of future systematic reviews.
- Tertiary Reviews: a systematic review of systematic reviews to answer wider research questions. (If a number of systematic reviews exist already).

**Is a SLR needed?**

- Can you find an important software engineering question, which the review addressed?
- Was a thorough search done? Were all potentially important sources explored?

**What is a SoK Paper?**

The [SoK paper](https://oakland31.cs.virginia.edu/sokfaq.html) aims to provide a high value to the community. Sometimes the community seems to lose memory of things that have been done in the past and produces too many incremental results that don't always lead to a better general understanding.

## The SLR Process

The SLR process is iterative. For example, remember to refine the inclusion and exclusion criteria.

**Research Question**

- Identifying the impact of technologies on reliability and performance.
- Is meaningful and important to practitioners as well as researchers.
  - identify and/or scope future research activities.
- Will lead either to changes in current practice or to increased confidence in the value of current practice.
- Will identify discrepancies between commonly held beliefs and reality.

### Filtering

If there are too many articles, you can filter them by:

- Study Type
  - include: Review and original content
  - exclude: Reports, thesis, and editorials
- Source: Peer-reviewed articles, Conference proceedings.
- Year of Publication: filter out something too old
- Language: e.g., only include English
- Techniques


## Tools

- [semi-automatic-literature-survey](https://github.com/cabrerac/semi-automatic-literature-survey): Besides searching, it uses `Lbl2Vec` to applies customised syntactic and semantic filters to group paper by topic.
- [findpapers](https://github.com/jonatasgrosman/findpapers): a python package to help to search for papers.

Places to find tools:

- [github topics: systematic-literature-reviews](https://github.com/topics/systematic-literature-reviews)
- [github topics: literature-search](https://github.com/topics/literature-search)
- [github topics: literature-review-tool](https://github.com/topics/literature-review-tool)


## Related Materials

- [Systematic​ ​Literature​ ​Review​ ​in Computer​ ​Science​ ​-​ ​A​ ​Practical​ ​Guide](https://www.researchgate.net/profile/Rodrigo-Silva-20/publication/320704338_Systematic_Literature_Review_in_Computer_Science_-_A_Practical_Guide/links/59f631caaca272607e2bc1c1/Systematic-Literature-Review-in-Computer-Science-A-Practical-Guide.pdf)
- ["SEGRESS: Software Engineering Guidelines for REporting Secondary Studies"](https://ieeexplore.ieee.org/document/9772383)
- ["Guidelines for performing Systematic Literature Reviews in Software Engineering"](https://legacyfileshare.elsevier.com/promis_misc/525444systematicreviewsguide.pdf)
  - Section 2 provides an introduction to systematic reviews. 
  - Section 3 explains why social science SLR methodology is appropriate in the 
    context of software engineering research. 
  - Section 4 specifies the stages in a systematic review. 
  - Section 5 discusses the planning stages of a systematic review.
    - Identification of the need for a review (See Section 5.1). 
    - Commissioning a review (See Section 5.2). 
    - Specifying the research question(s) (See Section 5.3). (**The most important**)
    - Developing a review protocol (See Section 5.4). 
    - Evaluating the review protocol (See Section 5.5). 
  - Section 6 discusses the stages involved in conducting a systematic review. 
    - Identification of research (See Section 6.1). 
    - Selection of primary studies (See Section 6.2). 
    - Study quality assessment (See Section 6.3). 
    - Data extraction and monitoring (See Section 6.4). 
    - Data synthesis (See Section 6.5). 
  - Section 7 discusses reporting a systematic review.
    - Specifying dissemination mechanisms (See Section 7.1). 
    - Formatting the main report (See Section 7.2). 
    - Evaluating the report (See Section 7.3).
  - Section 8 discusses systematic mapping studies. 
