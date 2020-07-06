# CFDE Glossary

##### <u>A2CPS</u>
[`Acute to Chronic Pain Signatures program`](https://commonfund.nih.gov/pain). The most comprehensive study to date to investigate the connections of peripheral biology, brain, psychological, and bio-behavioral risk factors. Composed of a consortium of organizations and scientists throughout the U.S. and Canada, A2CPS is part of the multi-pronged [NIH HEAL](https://heal.nih.gov/) (Helping to End Addiction Long-Term) initiative, an aggressive effort to speed scientific solutions to stem the national opioid public health crisis.

---

##### <u>API</u> 
`Application Programmer Interface`. Allows developers to manipulate (query, update) remote data sources through specific protocols or specific standards for communication (e.g., REST,SOAP). An important element of the ecosystem will be the standardization and publishing of an API that can be used by data consumers to retrieve the inventories, the data asset specification, and additional metadata associated with the assets. This will allow for consumers of these inventories to programmatically interrogate the federated system for information that may be relevant to a consuming service.

---

##### <u>ASHG</u>
`American Society of Human Genetics`. They hold an annual conference that is the largest human genetics and genomics meeting and exposition in the world.

---

##### <u>Asset</u>
a `sample or a file`, which are also known as `material asset` or `digital asset` respectively.

---

##### <u>Asset Inventory</u>
an asset inventory is a collection of digital asset  distributed by the DCCs through a portal.

---

##### <u>BIC</u>
`Bioinformatics Center`. The BIC is responsible for the task of harmonizing the large quantity and diversity of data and metadata being generated by the consortium and performing meaningful integrative analyses across these omics data types.

---

##### <u>Biospecimens</u>
a `material asset`, collected from an organism, a cell culture, or a material containing organisms, such as an environmental material. syn: [Sample](#Sample)

---

##### <u>C2M2</u>
the [`CrossCut Metadata Model`](https://www.nih-cfde.org/product/full-c2m2-er-model/)is a data model specification developed by NIH [CFDE](#CFDE) to represent experiments and datasets. Recycling a number of entities from the [DATS specification](#DATS)

---

##### <u>C2M2 Creation Flow</u>
the process which generated the C2M2 model.

---

##### <u>C2M2 Extractor Flow</u>
a process which transforms information stored in a given DCC representation format into the CFDE C2M2 model instances.

---

##### <u>CC</u>
`Coordinating Center`. The [CFDE](#CFDE)-CC’s purpose is to improve growth in use and reuse of CF program data by supporting [DCC](#DCC)s that participate in the Common Fund Data Ecosystem.

---

##### <u>CFDE</u>
`Common Fund Data Ecosystem`. A data ecosystem is a collection of data silos or commons joined together by a set of standards and services that facilitate findability, accessibility, reuse, and interoperability of datasets between silos/commons. A data ecosystem is focused on enabling multi-way connectivity between datasets, in a horizontal fashion, rather than deeper vertical analysis within each dataset. The goal of an ecosystem is to enable use cases between data silos, not within.

---

##### <u>CFDE Asset Manifest</u>
a collection of *Assets* described by the *CFDE Asset Specification*. The ecosystem will support the concept of a manifest that describes a collection of files. The manifests enable bundling lists of CFDE data assets into a machine-readable file using a common format. Manifests will also be used to publish the complete inventories of data from each DCC, and will enable uniform collection of asset metadata to support indexing of the assets in the CFDE portal.

---

##### <u>CFDE-asset-manifest</u>
a type of Metadata Manifest describing an  [Asset Inventory](#Asset-Inventory)

---

##### <u>CFDE Asset Specification</u>
defines the set of attributes used to charaterize an *Asset*. The specification simplifies the discovery of assets hosted at the DCCs with a minimal set of descriptors for each of these files. The types of files that are referenced (e.g., genomic sequence, metagenomic, RNA-Seq, physiological and metabolic data) are flexible and contain a small number of essential elements such as a *GUID*, originating institution (e.g., Broad Institute), assay type (e.g., whole genome/exome, transcriptome, epigenome), file type (e.g., fastq, alignment, vcf, counts), and tissue source and species name for the sample.

---

##### [CFDE Common Metadata Format](https://fair-research.org/deliverables/cfde-metadata-format.html)
specifies a minimal set of attributes (metadata) related to an *Asset*.

<!-- ![common metadata format](https://user-images.githubusercontent.com/40363469/66134031-a8833580-e5c5-11e9-9cc8-5e4b275fa20c.png)
<img src="https://user-images.githubusercontent.com/40363469/66134031-a8833580-e5c5-11e9-9cc8-5e4b275fa20c.png" alt="drawing" style="border:1px solid black;" width="650"  align="top" /> -->
---

##### <u>CFDE Core ER Diagram</u>
the `CFDE Core Entity Relationship diagram` corresponds to a  `Level 0 representation richness` and is available from the following [github repository](https://github.com/nih-cfde/cfde-deriva/blob/2019-08/diagrams/cfde-core-model.png)

---

##### <u>CFDE Core Table Schema</u>
the `CFDE Core Table Schema` corresponds to a  `Level 0 representation richness`, expressed as a [Frictionless Data Package](#Frictionless) represenstation and is available from the following [github repository](https://github.com/nih-cfde/cfde-deriva/blob/2019-08/table-schema/cfde-core-model.json)

---

##### <u>CFDE Data Dashboard</u>
the [`CFDE Data Dashboard`](https://cfde.derivacloud.org/deriva-webapps/plot/)is
an interface that monitors DCC data upload to the cloud and usage statistics to support cross-DCC search and ecosystem integration.

---

##### <u>CFDE Entity-Relation Diagram</u>
the `CFDE Core Entity Relationship diagram` corresponds to a  `Level 2 representation richness` and is available from the following [github repository](https://github.com/nih-cfde/cfde-deriva/blob/2019-10/extractors_and_metadata.GTEx/cfde-core-model.2019.10.21.1430.png)

---

##### <u>CFDE Query Portal</u>
a portal enabling users and administrators to search all the federated data assets at each Common Fund Program. The CFDE portal increases a user's ability to find these important resources, as well as mix and match sets of data from each site to use in subsequent analysis. Administrators and Program Officers at Common Fund can use a single website to view the growth of data from their program over time, review objective FAIR metrics for these assets, understand download statistics and geographic distribution, and view the degree of harmonization of these data in comparison to other sites.

---

##### <u>Common Fund Programs</u>
the intent of the CF programs is to provide a strategic and nimble approach to address key roadblocks in biomedical research that impede basic scientific discovery and its translation into improved human health. In addition, these programs capitalize on emerging opportunities to catalyze the rate of progress across multiple biomedical fields. The CF programs include:

- ###### [4DN](https://www.4dnucleome.org/)
the `4D Nucleome program`'s goal is to study the three-dimensional organization of the nucleus in space and time (the 4th dimension). 

- ###### [GTEx](https://www.gtexportal.org/home/)
the`Genotype-Tissue Expression` project is an ongoing effort to build a comprehensive public resource to study tissue-specific gene expression and regulation.

- ###### [HMP](https://www.hmpdacc.org/)
the `Human Microbiome Project` whose mission is to generate resources to facilitate characterization of the human microbiota to further our understanding of how the microbiome impacts human health and disease. 

- ###### [Kids First](https://kidsfirstdrc.org/) 
the `Kids First Pediatric Research Program` Data Resource Center enables researchers, clinicians, and patients to work together to accelerate research and promote new discoveries for children affected with cancer and structural birth defects. 

- ###### [LINCS](http://lincsproject.org/) 
the `Library of Integrated Network-based Cellular Signatures project` is based on the premise that disrupting any one of the many steps of a given biological process will cause related changes in the molecular and cellular characteristics, behavior, and/or function of the cell – the observable composite of which is known as the cellular phenotype. Observing how and when a cell’s phenotype is altered by specific stressors can provide clues about the underlying mechanisms involved in perturbation and, ultimately, disease.

- ###### [Metabolomics]() 
the `Metabolomics program` was developed with the goal of increasing national capacity in metabolomics by supporting the development of next generation technologies, providing training and mentoring opportunities, increasing the inventory and availability of high quality reference standards, and promoting data sharing and collaboration.

- ###### [SPARC]() 
the `Stimulating Peripheral Activity to Relieve Conditions program` seeks to accelerate development of therapeutic devices that modulate electrical activity in nerves to improve organ function.

---

##### <u>CV</u>
`Controlled Vocabulary`: an organized arrangement of words and phrases used to index content and/or to retrieve content through browsing or searching. It typically includes preferred and variant terms and has a defined scope or describes a specific domain. For example, the [DCIC](#DCIC) curates an internal [4DN](#4DN) controlled vocabulary to provide definitions for emerging technologies and techniques, metadata terms, and captures important data features not defined by previous ontologies.

---

##### <u>Data Citation Rubric</u>
a collection of rules to assess [FAIRness](#FAIR-Evaluation) of data citation using the [FAIRshake tool](#FAIRshake) available from the following [github repository](https://github.com/nih-cfde/FAIR/blob/master/Demos/FAIRAssessment/data_citation_rubric.py)

---

##### <u>Data-Generating Event</u>
a process, such as a data acquisition or a data transformation, resulting in the creation of a file (digital asset).

---

##### <u>Data Object</u>
a region of storage that contains a value or group of values. Each value can be accessed using its identifier or a more complex expression that refers to the object. In addition, each object has a unique data type.

---

##### <u>Dataset</u>
a `collection of data`, published or curated by a single agent, and available for access or download in one or more formats.

---

##### <u>DATS</u>
[`Data Article Tag Suite`](https://github.com/datatagsuite/README) is a data model for representing key information about datasets with an emphasis on data discovery and data findability, which has inspired the creation of the NIH-C2M2 model. [The DATS model is expressed as a JSON schema](https://datatagsuite.github.io/docs/html/dats.html). Associated JSON-LD context files support search engine optimization because they map into [schema.org](https://schema.org) and [DCAT](www.w3.org/TR/vocab-dcat-2/). Mappings into biological entities are also available via [OBO Foundry resources](http://www.obofoundry.org). 

---

##### [dbGaP](https://www.ncbi.nlm.nih.gov/gap/)
`Database of Genotypes and Phenotypes`. The database of Genotypes and Phenotypes (dbGaP) was developed to archive and distribute the data and results from studies that have investigated the interaction of genotype and phenotype in Humans.

---

##### <u>DCC-data-ingestion-process</u>
a process which converts a dataset obtained from a [DCC](#DCC) and transforms its data and metadata into a [C2M2](#C2M2) model instance representation and persists it to a [DERIVA](#DERIVA) endpoint  

---

##### <u>DCCs</u> 
`Data Coordinating/Resource Centers`.

---

##### <u>DCIC</u>
`Data Coordination and Integration Center`. Data generated by [4DN](#4DN) partner institutions are integrated, curated, analyzed, and disseminated here.

---

##### <u>DERIVA</u>
[`Discovery Environment for Relational Information and Versioned Assets`](https://docs.derivacloud.org/platform.html) is a suite of tools and services that are designed to significantly reduce the overhead and complexity of creating and managing complex, big datasets. DERIVA provides a digital asset management system for scientific data to streamline the acquisition, modeling, management, and sharing of complex, big data, and provides interfaces so that these data can be delivered to diverse external tools for big-data analysis and analytic tools.

---

##### [DERIVA Catalog](https://cfde.derivacloud.org/)
a group of assets that may be digital objects (i.e., files) or references to physical objects. [DERIVA](#DERIVA) uses an entity-relationship data model to catalog and organize these assets. 

---

##### <u>DTC</u>
`Data and Tools Cores`. The [Metabolomics Program](#Metabolomics) consortium consists of six RCMRCs and seven DTCs that are overseen by the Metabolomics Consortium Coordinating Center at the University of Florida.

---

##### <u>Entity-relationship-model</u>
an `Entity-relationship-model` (or ER model) describes interrelated things of interest in a specific domain of knowledge. A basic ER model is composed of entity types (which classify the things of interest) and specifies relationships that can exist between entities (instances of those entity types). In software engineering, an ER model is commonly formed to represent things a business needs to remember in order to perform business processes. Consequently, the ER model becomes an abstract data model, that defines a data or information structure which can be implemented in a database, typically a relational database. source: Wikipedia).

---

##### <u>eRA Commons</u>
the [`electronic Research Administration`](https://public.era.nih.gov/commons) is an online interface where signing officials, principal investigators, trainees, and post-docs at institutions/organizations can access and share administrative information relating to research grants. It is the `designated ID provider` for the whitelist of DCCs.

---

##### [FAIR](https://www.go-fair.org/fair-principles/)
`Findable, Accessible, Interoperable, and Reusable`. Making data FAIR is the main goal of the DCCs.

---

##### <u>FAIR Assessment</u>
a process which evaluates the level of compliance of a dataset with the FAIR principles. The assessment may be performed with tools such as [FAIRshake](https://fairshake.cloud) or [FAIREvaluator](https://fairsharing.github.io/FAIR-Evaluator-FrontEnd/#!/).

---

##### [FAIR Insignia]()
a grid of colored squares developed to visually communicate FAIRness level. The [FAIR](#FAIR) insignia identifies areas of strength and weakness in the FAIRness level of digital objects, guiding digital object producers on how to improve the FAIRness of their products. FAIR insignia is an output of the [FAIRshake](#FAIRshake)

<img src="https://github.com/nih-cfde/the-fair-cookbook/blob/master/content/images/logo/FAIRinsignia.png?raw=true" alt="drawing" style="border:1px solid black;" width="100"  align="top" />

---

##### [FAIRshake](https://fairshake.cloud/)
a tool produced for carrying out *FAIR Assessment*. Under the [CFDE](#CFDE), each data center’s inventory will be evaluated consistently based on FAIRshake, and the Coordinating Center will work with the individual Common Fund programs to adjust [FAIR](#FAIR) measures to meet the needs of the Common Fund. FAIRshake includes evaluating the FAIRness of digital objects including datasets, tools, and repositories.

---

##### [Figshare](https://figshare.com/)
an online open access repository where researchers can preserve and share their research outputs, including figures, datasets, images, and videos.

---

##### <u>File</u>
a `digital asset`, that is a type of digital object that each of the [DCCs](#DCC) hosts, such as genomic, metagenomic, RNA-Seq sequence data, physiological, and metabolic data or generic metadata electronic document.

---

##### [Frictionless Data Package](http://frictionlessdata.io/data-package/)
a format specification produced by the [Open Knowledge Foundation](https://okfn.org/) and supported by the Frictionlessdata.io organization. It aims to shorten the path from data to insight with a collection of specifications and software for the publication, transport, and consumption of data. This kills the cycle of find/improve/share that makes for a dynamic and productive data ecosystem.

---

##### [GitHub](https://github.com/)
an online hub for storing and sharing computer programs and other plain text files. The [CFDE](#CFDE) team uses it for storage, hosting websites, communications, and project management.

---

##### [Globus Automate]()
a distributed research automation platform that addresses the problem of securely and reliably automating, for many thousands of scientists, sequences of data management tasks that may span locations, storage systems, administrative domains, and timescales, and integrate both mechanical and human inputs.

---

##### <u>Globus Automate Flow</u>
a process which relies on Globus Automate, a software service created and based at the University of Chicago, to help scientists simplify their workflow by automating data transfer and synchronization tasks. Users can create automated sequences initiated by events, known as `Globus Automate Flows`.

---

##### <u>GUID</u>
`Globally Unique IDentifier`. a chain of characters, usually 128-bit long used to uniquely identify an entity. Modern hashing functions used to generate GUIDs make `identifier collisions` (the event of the function producing the same sequence) highly unlikely (but not impossible), hence those can only be `nearly guaranteed to be unique`.

---

##### <u>HMP</u>
the`Human Microbiome Project`. 

---

##### [Jupyter Notebook](https://jupyter.org/)
a web-based interactive environment for organizing data, performing computation, and visualizing output.

---

##### <u>M3C</u>
the `Metabolomics Consortium Coordinating Center` at the University of Florida, which handles overall coordination for the Metabolomics program.

---

##### <u>Metadata Ingest</u>
a process which assigns identifiers to the objects, then extracts or creates metadata for these objects and persists them.

---

##### <u>MGP</u>
[`Human Metabolome Gene/Protein Database`](https://www.metabolomicsworkbench.org/databases/proteome/MGP.php). Developed by the Common Fund Metabolomics program and part of Metabolomics Workbench. A database of metabolome-related genes and proteins containing over 7,300 genes and over 15,500 proteins. Users can search by gene (name, symbol, entrez ID, etc.), HMDB Pathway, or Reactome Pathway. MGP displays genes/proteins and metabolites associated with a pathway of interest. Searching by gene displays information about the gene’s associated proteins and pathways, including a summary of the function and metabolites involved in the pathway.

---

##### <u>MoTrPAC</u>
[`Molecular Transducers of Physical Activity Consortium`](https://www.motrpac.org/). MoTrPAC is a national research consortium designed to discover and perform preliminary characterization of the range of molecular transducers (the "molecular map") that underlie the effects of physical activity in humans. The program's goal is to study the molecular changes that occur during and after exercise and ultimately to advance the understanding of how physical activity improves and preserves health. The six-year program is the largest targeted NIH investment of funds into the mechanisms of how physical activity improves health and prevents disease.

---

##### <u>MW</u>
[`Metabolomics Workbench`](https://www.metabolomicsworkbench.org/). The MW is an online interface to the [NMDR](#NMDR) developed at UCSD, by the Common Fund [Metabolomics](#Metabolomics) program, . It allows users to manage and upload studies as well as browse and search available studies. Using the MW interface, submitters upload data and results, including metadata, targeted data measurements, protocols/methods files, untargeted data measurements, and raw data (MS/NMR files, etc.). Other researchers can then use the MW website to browse, search, analyze, and download data as well as view summary figures of key study search parameters (e.g., bubble chart showing studies by sample source). For example, studies can be filtered by study metadata (disease, sample source, species, instrumentation) or metabolite information (metabolite classification, biochemical pathways, retention time, etc.) to identify data relevant to the user’s needs. Additionally, it provides analysis tools and access to metabolite standards, protocols, tutorials, training, and other resources to support metabolomic researchers (such as [RefMet](#RefMet), [Metabolomics Workbench Metabolite Database](#Metabolomics-Workbench-Metabolite-Database)).

---

##### <u>Metabolomics Workbench Metabolite Database</u>
a PostgreSQL database containing over 65,000 structures and annotations of biologically relevant metabolites collected from public repositories (e.g., LIPID MAPS, ChEBI, HMDB, BMRB, PubChem, KEGG). Users can search for metabolites in the database by substructure, text, or mass (m/z ratio). Each entry contains key information about the metabolite, including structure, molecular weight, common and systematic names, PubChem compound ID, and classification. Entries also contain cross references to external databases and repositories (e.g., HMDB, ChEBI, LIPID MAPS, METLIN, ChemSpider, KEGG, etc.) as well as links to the MoNA MS spectra and human metabolic pathways containing the metabolite. Additionally, the open-source chemistry cartridge enables substructure searching, generation of chemistry-centric attributes (formula, exact mass), and interconversion of molecular formats.

---

##### <u>Metadata</u>
a type of information entity usually defined as `data about the data`, understood as `descriptors to understand the context of a dataset`. For example, metadata about an FASTQ file may be `file size` or `file creator`. Metadata is often classified into `descriptive metadata`, `structural metadata`, `administrative metadata`, and `provenance metadata`, all of which provide ++`context`++ to the actual data/dataset.

---

##### <u>Metadata Manifest</u>
a file that includes metadata for a group of accompanying files that are part of a coherent unit (manifest), such as name, version, background scripts, and browser actions.

---

##### <u>NMDR</u>
`National Metabolomics Data Repository`. Responsible for collating, analyzing, and distributing the data gathered by the RCMRCs and hosting the tools and methods created by the [DTC](#DTC)s.

---

##### [NPM](https://www.npmjs.com/)
`Node Package Manager`: a package manager for the JavaScript programming language. It is the default package manager for the JavaScript runtime environment Node.js. It consists of a command line client, also called npm, and an online database of public and paid-for private packages, called the npm registry.

---

##### <u>Organization</u> 
an entity comprising of multiple people, such as an institution or an association, that has a particular purpose.

---

##### <u>Proof of Concept (POC)</u>
a process or realization of a certain method or idea in order to demonstrate its feasibility. 

---

##### <u>Project</u>
a entity to describe administrative/funding/contract/etc. hierarchy governing ownership/management/purview/responsibility of/for subcollections of experimental resources and metadata 

---

##### <u>RAS</u>
`Researcher Authorization Service`. A service under development by the NIH's Center for Information Technology that will facilitate access to controlled data assets and repositories.

---

##### <u>RCMRC</u>
`Regional Comprehensive Metabolomics Resource Cores`. The Metabolomics Program consortium consists of six RCMRCs, also called the Compound Identification Cores (CIDCs), and seven Data and Tools Cores ([DTC](#DTC)s) that are overseen by the Metabolomics Consortium Coordinating Center at the University of Florida.

---

##### <u>RefMet</u>
[`Reference list of Metabolite names`](https://www.metabolomicsworkbench.org/databases/refmet/index.php). Developed by the Common Fund Metabolomics program. Effectively, a large spreadsheet that provides a standard nomenclature for over 95,500 chemical species. From the Metabolomics Workbench website, it can be browsed and searched directly or a user can input a list of metabolite names and have them automatically converted to RefMet nomenclature. A user can also directly download the data, either in whole or after filtering as one would with a simple Excel sheet. Or the entire dataset can be downloaded as part of a Shiny R app and queried locally.

---

##### <u>Richness-levels</u>
a qualifier indicative of the depth and granularity of an object model or [Entity-Relationship model](#Entity-relationship-model). In the context of [CFDE](#CFDE), the [C2M2](#C2M2) model is described by the following increasing richness levels: [Level-0, Level-1, Level-2]

---
##### <u>Sample</u>
a material collected from an organism, a cell culture, or a material containing organisms, such as an environmental material. syn: *[Biospecimens](#Biospecimens)*.

---

##### <u>SSO</u>
`Single Sign-On`: An authentication scheme that allows a user to log in with a single ID and password to any of several related, yet independent, software systems. It is often accomplished by using the [Lightweight Directory Access Protocol (LDAP)](https://ldap.com/) and stored LDAP databases on (directory) servers. A simple version of single sign-on can be achieved over IP networks using cookies but only if the sites share a common DNS parent domain.

---

##### <u>STRIDES</u>
`Science and Technology Research Infrastructure for Discovery, Experimentation, and Sustainability` initiative by the NIH. Common Fund leadership has partnered with the STRIDES initiative, which provides lower-cost cloud services to NIH projects.

---

##### <u>Subject</u>
a study participant (human, animal) from which samples may be obtained.

---

##### <u>Subject Group</u>
a set of study subjects sharing some characteristics or undergoing the same type of study intervention.

---

##### <u>Table Schema to DERIVA Translation</u>
a process of metadata ingest which uses tabular formatted data such as Frictionless data package to persist information in the [DERIVA system](#DERIVA). The code for such a process is available from Github from [this repository]((https://github.com/nih-cfde/cfde-deriva/blob/2019-08/examples/tableschema_to_deriva.py))

---

##### <u>TCC</u>
`Training Coordination Center`. This center is staffed by experts in bioinformatics curriculum development, teaching, and community building. It provides support and resources for the development of DCC-specific training programs as well as end-user training on CFDE products and general topics of interest to the Common Fund research community. The TCC can help with logistical support for hosting workshops, as well as providing guidance on how to grow and build a sustainable training program. The TCC provides instructor training for the [DCC](#DCC)s and assists with creating useful qualitative and quantitative feedback and assessment tools. In addition to site-specific training, the TCC offers training on CFDE products as they become available, and pilots a general bioinformatics workshop curriculum on topics of broad interest within the Common Fund.

---

##### <u>TOPMed</u>
[`Trans-Omics for Precision Medicine`](https://www.nhlbiwgs.org/).  The Trans-Omics for Precision Medicine (TOPMed) program, sponsored by the National Institutes of Health (NIH) National Heart, Lung and Blood Institute (NHLBI), is part of a broader Precision Medicine Initiative, which aims to provide disease treatments tailored to an individual’s unique genes and environment. TOPMed contributes to this Initiative through the integration of whole-genome sequencing (WGS) and other omics (e.g., metabolic profiles, epigenomics, protein and RNA expression patterns) data with molecular, behavioral, imaging, environmental, and clinical data.

---

<!-- *[A2CPS]: Acute to Chronic Pain Signatures program
*[SSO]: Single Sign-On
*[DATS]: Data Article Tag Suite
*[DERIVA]: Discovery Environment for Relational Information and Versioned Assets
*[C2M2]: Cross Cut Metadata Model
*[CFDE]: Common Fund Data Ecosystem
*[GUID]: Globally Unique Identifier
*[CC]: Coordinating Center
*[ASHG]: American Society of Human Genetics
*[BIC]: Bioinformatics Center
*[LDAP]: Lightweight Directory Access Protocol
*[DCC]: Data Coordination Center.
*[TCC]: Training Coordination Center.
*[FAIR]: Findable Accessible Interoperable Reusable
*[DCAT]: Data Catalog Vocabulary
*[OBO]: Open Biomedical Ontology
*[POC]: Proof of Concept
*[NIH]: National Institutes of Health
*[NHLBI]: National Heart, Lung and Blood Institute
*[WGS]: Whole Genome Sequencing
*[STRIDES]: Science and Technology Research Infrastructure for Discovery, Experimentation 
*[DNS]: Domain Name System 
*[RNA]: ribonucleic acid
Use case terms 
##### <u>Objective</u>
a description of a scientific process, told without reference to a specific technology solution. Focuses on resources required, method(s) followed, and outcome(s) targeted. Can be validated with scientific stakeholders.
##### <u>Persona</u>
a type of user who will appear in the epics and stories that follow.
##### <u>Requirement</u>
a well-scoped and defined piece of software or data engineering work that is needed to support a User Task. These should be small tasks that can be verified with engineering teams (e.g. `did we deliver it?` `yes` or `no`). A single requirement may be important for any number of different [User Task](#User-Task)s, and various collections of Requirements can be grouped to support different User Tasks.
##### <u>Summary</u>
a high-level, non-technical description of an entire `use case`. The user in each summary has a name, a scientific or administrative problem, and both proximate and ultimate goals. The focus is on the problem and what is generally needed to solve it.
##### <u>Use Case</u>
a `use case`, in software and systems engineering, is a list of actions or event steps typically defining the interactions between a role and a system to achieve a goal. The actor can be a human or other external system.
##### <u>User Task</u>
a `user story` is a story told from the user’s perspective that captures a concrete step in a user's interactions with tools (e.g., software solutions) in the service of achieving the scientific objective. A `user task` ++must be written in terms that are meaningful to the user, from their perspective++. This can be thought of as one in a series of medium scale tasks that must be completed to answer the question posed in the scientific objective. The list of `user tasks` in a [`use case`](#Use-Case) should cover everything the users needs to achieve their goals, even interactions that do not involve the software or data from the Common Fund.
 -->