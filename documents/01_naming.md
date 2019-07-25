> There are only two hard things in computer science: cache invalidation
> and naming things - Phil Karlton

Background
----------

------------------------------------------------------------------------

Names are really important.

Good names are:

-   clear
-   consistent
-   efficient

These qualities often come into tension with one another, which is why
conventions are important.

A shared understanding will help us navigate the compromises without
compromising our work.

Survey naming
-------------

------------------------------------------------------------------------

### Key data points

Folder structures for storing surveys are user-specific in Qualtrics,
and so too is the information they offer about the surveys within. While
each user is invited to keep their surveys in whatever folders they
like, this means that surveys have to be uniquely identified by their
names.

-   client organization
-   project name
-   survey order in participant workflow
-   survey name

### Example

-   client org: Elizabeth Fry

-   project name: My Start Up

-   survey order in participant workflow: First Survey

-   survey name: Baseline Survey

-   ideal name for pattern matching / api search:
    efry\_my-start-up\_01\_baseline

### Discussion

-   how much can we standardize the survey names? I’m thinking something
    like:
    -   baseline (currently “Input”, “Intake”, “Baseline”)
    -   end-of-training (currently “feedback”, “exit”, “end of porgram”)
    -   end-of-work-placement
    -   follow-up-3-month
    -   follow-up-6-month

### Version control

-   rely on qualtrics’ built-in version contral
-   include some primer material here about how to do that
-   don’t make copies of surveys to track changes.

Question naming
---------------

------------------------------------------------------------------------

### Key data points to include

-   block or scale
-   coding instructions??
-   item tag

### Guidelines

-   check library before developing new questions / blocks
-   after developing new questions / blocks, save them to the library
-   only include lowercase letters and underscores
-   prefer full words, only use common abbreviations or acronyms
-   for likert tables, include question name in item name
-   keep names the same across surveys
