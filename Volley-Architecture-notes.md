# Volley Architecture notes and commitments


#### More info: 
* [ ] Notebook 1 p 4 Nik on tech infra
* [ ] Notebook 1 p 14b infra & dev practices
* [ ] https://gist.github.com/nikvdp/b0b1adfd340c6e68045fefbabedc18ee#file-volley-sources-md


#### Tech infrastructure tools:
* [ ] [draw.io](https://www.draw.io)



### Volley Differentiators
* Personalization
   * The 5 right resources for you, not 1.2bn "matching" ones
   * Collaborative filtering and tagging of resources
* Adaptability (of style of delivery) -  improves as you use it / give feedback
* Engagement / Presentation
   * microlearning (e.g. excerpt right 3 min from 20 min video)
   * mobile-first, gamification, learning-driven content
* Verifiability
   * Analytics, BI 
   * Assessments
* Pedagogy
* auto-generated content
* Users engage in effective learning actions (e.g. assessments/games)
 
 
 ### Volley Product Commitments
 * Volley is a primary learning resource for professional training
   * To progress from being a 2nd / supplementary resource to a primary source, need to add:
     * pedagogy
     * content coverage: curriculum or use case coverage
     * content / knowledge base
 * Volley is mobile first (Master Interface is not a mobile interface)
 * The future of assessments is automatic quiz generation
 * Volley's improvements over usual microcourses are: personalization, form factor, auto-generated content (inexpensive) incorporating pedagogy, quiz driven recommendations
 * Volley's improvement over search is smart search (search over related terms, soon graph powered)
 * Volley's technology is subject matter agnostic

### Value prop / problems V seeks to solve
* Expensive to make online training content
* Indeterminate value of online training content to you
* Access to the material you need (e.g. Khan Academy - narrow focus)
* Non-pedagogical presentation (e.g. Wikipedia)
* Uneven content (e.g. Wolfram Alpha)
* Delivery problems (e.g. LMSs)

* **Access**
* **Engagement**
* **Personalization**

#### Major Capability Areas & the features that drive them
* Smart Search (driven by RED - "recursive exploratory drilldown")
 * Contextual - personalization, relevance
  * Role based access control? - search w/in partitions, incorporating access rules?
 * Over internal content - unstructured & structured data
 * Taking into account resource freshness & other quality measures (e.g. popularity, resource @ which other searches terminate)
* Smart Collections - cluster affiliated resources according to TiDDBit - o lead to Microbriefings / microcourses
 * Coalescing sources to cover areas
 * Incorporate experts
 * Use templates to help with quality measures? (E.g. history of ..., current events in ...)
* Assessments
* Question Answering

### Metrics for content quality ("fit for purpose")
 * Coverage/scope
 * Currency
 * Correctness
 * Personalization
 
#### Automated Measures for content quality
 * tools for language clarity, readability
 * user conversion after experiencing content
 * content unit completion (vs. dropping)
 * pace of consumption

#### Manual Measures / user feedback
 * quality of personalization (leverages what I know, fills in what I don't)
 * pedagogic progression (was this presented in the right order)
 * content is readily findable
 * content has verifiability (backup / provenance)


### Off-track
* Enterprises spend huge $ attracting and retaining the right people.  Can our assessments help employers determine what knowledge makes a successful employee? Can this help produce actually-relevant job ads that characterize the needed qualities for a job?
* Experts on demand
* Using our data on alternative resource composition / learning pathways to find "the best under xyz conditions"
 
## Technical positions on CG
* CG purpose overall:
 * Find concordances, interpolate, and re-present information fragments
 * A source of truth for truths that keyword searching will not reveal:
   * personalized - by interpolating from user profile features
   * flexible pathways
* The CG contains propositions
* ? How capture ordering, granularity, dependence btw propositions, proposition calculus (e.g. combinations)
* ? Provenance, source reliability / characterization?
* ? Where incorporate basic (not sensible to induce) logic e.g. mereology, system of measures, org & social relationships?



## Specific technical commitments
* Presenting appropriate fragments of material in response to demonstrated needs (search, or quiz performance - "knowledge gap detection")
  * Incl cutting down longer videos to salient part
* Collaborative filtering and tagging of resources
* automated ingest & content organization (downplaying the need for corporate SME assistance, much manual work, or additional resources)
* personalization (e.g. knowledge gap detection influencing resource recommendations)
* latent pedagogy
* ontology induction
* SRL statistical relational learning
* auto-question generation
* "personalization and pedagogy are too complex - they are worth experimenting with but must not be the substance of our offering" (Carson 5/23/17)

