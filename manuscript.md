---
title: 'Biological Information Flow Ontology: A Framework for Mechanistically Constrained Propagation in Biomedical Knowledge Graphs'
keywords:
- biological information flow
- knowledge graph
- ontology
- propagation
- graph conditioning
- personalized pagerank
- biomedical knowledge graph
- mechanistic constraint
- admissibility
lang: en-US
date-meta: '2026-04-27'
author-meta:
- Deanne M. Taylor
- Taha Mohseni Ahooyi
- Benjamin J. Stear
- Yuanchao Zhang
- J. Alan Simmons
- Aditya Lahiri
- James Terry
- Jonathan C. Silverstein
header-includes: |
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta property="og:type" content="article" />
  <meta name="dc.title" content="Biological Information Flow Ontology: A Framework for Mechanistically Constrained Propagation in Biomedical Knowledge Graphs" />
  <meta name="citation_title" content="Biological Information Flow Ontology: A Framework for Mechanistically Constrained Propagation in Biomedical Knowledge Graphs" />
  <meta property="og:title" content="Biological Information Flow Ontology: A Framework for Mechanistically Constrained Propagation in Biomedical Knowledge Graphs" />
  <meta property="twitter:title" content="Biological Information Flow Ontology: A Framework for Mechanistically Constrained Propagation in Biomedical Knowledge Graphs" />
  <meta name="dc.date" content="2026-04-27" />
  <meta name="citation_publication_date" content="2026-04-27" />
  <meta property="article:published_time" content="2026-04-27" />
  <meta name="dc.modified" content="2026-04-27T17:54:00+00:00" />
  <meta property="article:modified_time" content="2026-04-27T17:54:00+00:00" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Deanne M. Taylor" />
  <meta name="citation_author_institution" content="The Department of Biomedical and Health Informatics, The Children&#39;s Hospital of Philadelphia, Philadelphia, PA, USA" />
  <meta name="citation_author_institution" content="Department of Pediatrics, University of Pennsylvania Perelman School of Medicine, Philadelphia, PA, USA" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <meta name="citation_author" content="Taha Mohseni Ahooyi" />
  <meta name="citation_author_institution" content="The Department of Biomedical and Health Informatics, The Children&#39;s Hospital of Philadelphia, Philadelphia, PA, USA" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <meta name="citation_author" content="Benjamin J. Stear" />
  <meta name="citation_author_institution" content="The Department of Biomedical and Health Informatics, The Children&#39;s Hospital of Philadelphia, Philadelphia, PA, USA" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <meta name="citation_author" content="Yuanchao Zhang" />
  <meta name="citation_author_institution" content="The Department of Biomedical and Health Informatics, The Children&#39;s Hospital of Philadelphia, Philadelphia, PA, USA" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <meta name="citation_author" content="J. Alan Simmons" />
  <meta name="citation_author_institution" content="Department of Biomedical Informatics, School of Medicine, University of Pittsburgh, Pittsburgh, PA, USA" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <meta name="citation_author" content="Aditya Lahiri" />
  <meta name="citation_author_institution" content="The Department of Biomedical and Health Informatics, The Children&#39;s Hospital of Philadelphia, Philadelphia, PA, USA" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <meta name="citation_author" content="James Terry" />
  <meta name="citation_author_institution" content="The Department of Biomedical and Health Informatics, The Children&#39;s Hospital of Philadelphia, Philadelphia, PA, USA" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <meta name="citation_author" content="Jonathan C. Silverstein" />
  <meta name="citation_author_institution" content="Department of Biomedical Informatics, School of Medicine, University of Pittsburgh, Pittsburgh, PA, USA" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <link rel="canonical" href="https://TaylorResearchLab.github.io/bifo-paper-0/" />
  <meta property="og:url" content="https://TaylorResearchLab.github.io/bifo-paper-0/" />
  <meta property="twitter:url" content="https://TaylorResearchLab.github.io/bifo-paper-0/" />
  <meta name="citation_fulltext_html_url" content="https://TaylorResearchLab.github.io/bifo-paper-0/" />
  <meta name="citation_pdf_url" content="https://TaylorResearchLab.github.io/bifo-paper-0/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://TaylorResearchLab.github.io/bifo-paper-0/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://TaylorResearchLab.github.io/bifo-paper-0/v/edd5ca940379831c0e06ee6cc792e4cc1fb24145/" />
  <meta name="manubot_html_url_versioned" content="https://TaylorResearchLab.github.io/bifo-paper-0/v/edd5ca940379831c0e06ee6cc792e4cc1fb24145/" />
  <meta name="manubot_pdf_url_versioned" content="https://TaylorResearchLab.github.io/bifo-paper-0/v/edd5ca940379831c0e06ee6cc792e4cc1fb24145/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
This manuscript
([permalink](https://TaylorResearchLab.github.io/bifo-paper-0/v/edd5ca940379831c0e06ee6cc792e4cc1fb24145/))
was automatically generated
from [TaylorResearchLab/bifo-paper-0@edd5ca9](https://github.com/TaylorResearchLab/bifo-paper-0/tree/edd5ca940379831c0e06ee6cc792e4cc1fb24145)
on April 27, 2026.
</em></small>



## Authors



+ **Deanne M. Taylor**
  ^[✉](#correspondence)^<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [taylordm](https://github.com/taylordm)
    <br>
  <small>
     The Department of Biomedical and Health Informatics, The Children's Hospital of Philadelphia, Philadelphia, PA, USA; Department of Pediatrics, University of Pennsylvania Perelman School of Medicine, Philadelphia, PA, USA
     · Funded by NIH Common Fund R03OD030600; NIH Common Fund OT2OD030162
  </small>

+ **Taha Mohseni Ahooyi**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [tma1](https://github.com/tma1)
    <br>
  <small>
     The Department of Biomedical and Health Informatics, The Children's Hospital of Philadelphia, Philadelphia, PA, USA
  </small>

+ **Benjamin J. Stear**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    <br>
  <small>
     The Department of Biomedical and Health Informatics, The Children's Hospital of Philadelphia, Philadelphia, PA, USA
  </small>

+ **Yuanchao Zhang**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    <br>
  <small>
     The Department of Biomedical and Health Informatics, The Children's Hospital of Philadelphia, Philadelphia, PA, USA
  </small>

+ **J. Alan Simmons**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    <br>
  <small>
     Department of Biomedical Informatics, School of Medicine, University of Pittsburgh, Pittsburgh, PA, USA
  </small>

+ **Aditya Lahiri**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    <br>
  <small>
     The Department of Biomedical and Health Informatics, The Children's Hospital of Philadelphia, Philadelphia, PA, USA
  </small>

+ **James Terry**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    <br>
  <small>
     The Department of Biomedical and Health Informatics, The Children's Hospital of Philadelphia, Philadelphia, PA, USA
  </small>

+ **Jonathan C. Silverstein**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    <br>
  <small>
     Department of Biomedical Informatics, School of Medicine, University of Pittsburgh, Pittsburgh, PA, USA
     · Funded by NIH Common Fund OT2OD026663; NIH Common Fund OT2OD026675
  </small>


::: {#correspondence}
✉ — Correspondence possible via [GitHub Issues](https://github.com/TaylorResearchLab/bifo-paper-0/issues)
or email to
Deanne M. Taylor \<taylordm@chop.edu\>.


:::


## Abstract {.page_break_before}

The Biological Information Flow Ontology (BIFO) is an ontological framework that defines the admissible biological entities, entity states, and information flows over which mechanistic signal can propagate in heterogeneous biomedical knowledge graphs. BIFO specifies fourteen entity classes covering genes, chromatin states, RNA, proteins, macromolecular complexes, small molecules, ions, pathways, cells, spatial contexts, phenotypes, diseases, perturbagens, and mechanical inputs, along with a typed taxonomy of flow classes governed by an admissibility framework that enforces directionality, state dependence, spatial constraint, and temporal progression. Unlike existing ontologies that catalog biological entities or annotate relationships, BIFO defines propagation rules: it specifies which transformations between which entities are biologically valid and may carry information, separately from which relationships merely correlate or constrain. This separation enables a graph conditioning protocol that converts any property graph satisfying a minimal substrate assumption into a propagation-ready, mechanistically constrained operator. We present BIFO Specification v0.02, a reference implementation against the Common Fund Data Ecosystem Data Distillery Knowledge Graph (DDKG), and a worked example showing that conditioning yields a non-symmetric, biologically interpretable propagation operator. BIFO provides a foundation for hypothesis-driven inference, signal propagation, and mechanistic reasoning across heterogeneous biomedical knowledge graphs, and it is currently used as the conditioning layer for the BIFO-PPR pathway-enrichment system [@TODO:bifo-paper-1-biorxiv].


## Introduction

Knowledge graphs (KGs) have become important tools for integrating and analyzing heterogeneous biomedical data, enabling the linkage of diverse datasets in a structured and semantically enriched manner [@doi:10.1038/s41597-024-04070-w]. As biomedical KGs scale to millions of nodes and tens of millions of edges drawn from dozens of source vocabularies, a problem distinct from data integration emerges: not every relationship in such a graph encodes the same kind of biological information. Hierarchy edges define structure, lexical edges define identity, statistical co-occurrence edges record correlation, and only a subset of typed predicates encode the directional, state-changing transformations that mechanistic biological reasoning requires. Naive propagation algorithms operating over such graphs implicitly treat all of these as equivalent channels, producing reachable state spaces that include semantically invalid paths and obscure biologically meaningful signal.

Existing frameworks address parts of this problem but do not resolve it. Ontologies such as the Gene Ontology [@doi:10.1038/75556] and the Human Phenotype Ontology [@doi:10.1093/nar/gkaa1043] provide structured representations of biological concepts but do not define propagation rules. Knowledge graph systems support typed traversal but rely on user-defined queries rather than biologically grounded constraints. Causal-assertion frameworks such as BEL [@TODO:bel-citation] and GO-CAM [@TODO:go-cam-citation] encode mechanistic relationships but operate within curated representations and do not provide a general protocol for conditioning arbitrary heterogeneous graphs. Standards such as SBML [@TODO:sbml-citation] encode explicitly defined mechanistic models but require model construction up front rather than acting on integrated KGs. Foundational ontologies such as BFO [@TODO:bfo-citation] specify upper-level categories without addressing biological propagation specifically. Graph machine learning approaches can operate over heterogeneous structures but learn propagation behavior from data rather than enforcing biologically interpretable constraints.

To address this gap, we introduce the Biological Information Flow Ontology (BIFO), an ontological framework that formally defines admissible biological entities, entity states, and the information flows between them. BIFO specifies what kinds of biological entities can exist in a flow-aware network, what transformations between those entities are biologically meaningful, and in which directions information can propagate. Within this framework, we distinguish three categories of relationships. **Mechanistic** relationships encode directional, state-changing biological transformations such as signal transduction, transcriptional regulation, and biochemical catalysis, and they participate in propagation. **Observational** relationships, such as statistical co-expression or text-mining co-occurrence, capture correlative associations without encoding causal state transitions and are excluded from propagation. **Contextual** relationships encode spatial, temporal, or structural constraints that restrict which transitions are feasible without themselves carrying signal. Applied to a heterogeneous knowledge graph, these definitions produce a constrained propagation substrate: the constraint is a consequence of the definitions, not their purpose. BIFO is not designed to restrict graphs; it is designed to formalize what biology *is* in terms of admissible entities and flows.

BIFO is currently used as the conditioning layer for two production knowledge-graph applications. In the Common Fund Data Ecosystem Data Distillery Knowledge Graph (DDKG), BIFO conditioning supports the BIFO-PPR pathway-enrichment system [@TODO:bifo-paper-1-biorxiv], where it converts a heterogeneous DDKG export into a mechanistically constrained Personalized PageRank operator. In the broader Petagraph environment [@doi:10.1038/s41597-024-04070-w], BIFO complements the Homo sapiens Chromosomal Location Ontology [@doi:10.1038/s41597-024-04358-x] by adding flow-aware semantics on top of the positional semantics that HSCLO provides.

In this paper we present the BIFO specification, describe its reference implementation against the DDKG, report graph-conditioning coverage statistics on a production DDKG export, and walk through a small worked example illustrating how conditioning transforms a heterogeneous property graph into a propagation-ready, biologically admissible operator.


## Methods

### Building BIFO

BIFO is organized around four normative components: (1) an entity-class taxonomy defining the kinds of biological objects a flow-aware network must distinguish; (2) a set of state attributes attached to those entities; (3) a flow-class taxonomy specifying admissible transformations; and (4) an admissibility framework that governs when a candidate transformation is biologically valid in context. The full specification, including all tables, is provided as BIFO Specification v0.02 [@TODO:bifo-spec-osf-doi].

#### Entity classes

BIFO defines fourteen entity classes: G (genes and genomic features), CH (chromatin states), RNA (transcripts and noncoding RNA), P (proteins), CM (macromolecular complexes), SM (small molecules and metabolites), ION (ions), PW (pathways and biological processes), C (cells and cell types), S (spatial and compartmental contexts), PH (phenotypes), DS (diseases), X (perturbagens such as drugs and chemical probes), and MECH (mechanical inputs and physical signals). Entity classes are populated either by direct type assignment in graphs that carry typed nodes, or by CURIE resolution against a normative two-level mapping that aligns identifiers from standard biomedical ontologies (HGNC, UniProt, Reactome, GO, MONDO, HPO, ChEBI, Cell Ontology, UBERON, and others) to the appropriate BIFO entity class.

#### Flow classes

Flows are organized into a typed taxonomy spanning central-dogma transformations (Transcription, Translation), regulatory and signaling flows (Signal Transduction, Protein-DNA Regulation, Signal Termination), biochemical flows (Biochemical Transformation, Metabolic Coupling), transport flows, intercellular communication flows, cellular state and progression flows, mechanotransduction, perturbational effects, and phenotype/disease flows. A separate group of observational flows captures correlative associations that inform model construction but do not propagate biological state.

#### Admissibility framework

Admissibility constraints govern all flows: directionality (each directed flow is a distinct biological process with independent admissibility conditions in forward and reverse), state dependence (flow validity depends on entity states such as protein activity, RNA role, or chromatin configuration), spatial constraint (flows are inadmissible if source and target occupy incompatible compartments), temporal progression (transitions follow `state(t) → state(t+1)`), and non-flow exclusion (hierarchy, identifier, lexical, and purely statistical edges are not information-carrying flows).

### Graph conditioning protocol

BIFO defines a four-step protocol that converts a raw property graph into a conditioned graph in which only admissible flows participate in propagation. The protocol is KG-agnostic and applies to any property graph satisfying the BIFO Substrate Assumption (typed nodes and edges with resolvable CURIEs and edge provenance). The four steps are (1) Entity Class Assignment, (2) Flow Class Assignment and Edge Filtering, (3) State and Spatial Annotation, and (4) Confidence and Provenance Annotation. KG-specific implementation guides document how each step is performed against a particular graph schema and identifier system.

### DDKG reference implementation

The reference instantiation of BIFO targets the Common Fund Data Ecosystem Data Distillery Knowledge Graph (DDKG), which inherits Unified Biomedical Knowledge Graph (UBKG) and Petagraph infrastructure [@doi:10.1038/s41597-024-04070-w]. In this implementation, predicate-to-flow-class assignment is configured through `bifo_mapping.yaml` v0.7.1, containing 252 predicate-to-flow entries, 96 explicit non-flow designations, and 46 observational edge definitions across five classification tiers (mechanistic, weak-mechanistic, observational, contextual, and bridge). SAB-tagged source vocabularies in DDKG resolve directly to BIFO entity classes through the normative CURIE mapping. The DDKG-BIFO Implementation Guide documents the full mapping and any DDKG-specific extensions or restrictions [@TODO:ddkg-bifo-impl-guide].

### Worked-example methodology

To illustrate BIFO conditioning on a graph small enough to inspect by hand, we constructed a synthetic property graph of [TODO: final node count, target ~12-15] nodes spanning multiple BIFO entity classes (G, RNA, P, PW, PH, DS) and including a representative mix of edge types: central-dogma flows, regulatory flows, pathway-membership bridge edges, plus deliberately non-admissible edges (an `is_a` hierarchy edge, a lexical `synonym` edge, and a statistical co-expression edge) that should be filtered by conditioning. We then applied the four-step BIFO conditioning protocol to this graph and recorded the resulting admissible-edge set, the entity-class assignments, and the structural properties of the conditioned operator. Details of the toy graph construction, including all node and edge specifications, are in [TODO: supplementary materials reference].

### DDKG coverage measurement

To quantify BIFO coverage at production scale, we applied the conditioning protocol to a production DDKG export and recorded: (1) the fraction of nodes successfully assigned to a BIFO entity class, (2) the fraction of edges successfully assigned to a flow class, (3) the breakdown of admissible vs. non-admissible flows by flow-class tier, and (4) the predicate-level attribution of retained edges to their source vocabularies. The export and conditioning runs that produced these statistics are described in detail in the BIFO-PPR methods paper [@TODO:bifo-paper-1-biorxiv]; we report the headline coverage numbers in Results below.


## Results

### BIFO ontology overview

BIFO Specification v0.02 defines fourteen entity classes, [TODO: confirm count] flow classes organized into five classification tiers (mechanistic, weak-mechanistic, observational, contextual, and bridge), and an admissibility framework with six constraint families (directionality, state dependence, spatial constraint, temporal progression, metabolic-model consistency, non-flow exclusion, and contextual admissibility). The hierarchical organization of entities, flows, and admissibility constraints is summarized schematically in [TODO: Fig 1, modeled on HSCLO Fig 1]. The full specification, including the CURIE-to-entity-class mapping, the predicate-to-flow-class mapping, the flow-class tables organized by biological process category (central dogma, regulation, biochemistry, transport, communication, state and progression, mechanotransduction, phenotype and disease, observational), and the full table of admissibility constraints, is provided as BIFO Specification v0.02 [@TODO:bifo-spec-osf-doi].

A complete enumeration of BIFO entity classes, their state attributes, and example CURIE namespaces is provided in [TODO: Table 1, modeled on HSCLO Table 1]. The flow-class taxonomy and admissibility-constraint table are provided as [TODO: Table 2 and Table 3]. The four-step graph conditioning protocol is illustrated in [TODO: Fig 2].

### DDKG conditioning coverage

Applied to a production DDKG export [@TODO:bifo-paper-1-biorxiv], BIFO conditioning retained 104,342 of 174,352 input edges (59.8%) as propagation-admissible. The retained edges break down by flow-class tier as [TODO: per-tier breakdown table; values to be pulled from the canonical bifo_conditioning.py output and Paper 1 §SM]. Predicate-level attribution shows that the largest contributors to admissible-edge volume are [TODO: top-N predicates], which together account for [TODO: percentage] of retained edges. Source-vocabulary attribution shows that [TODO: top-N SABs] contribute the bulk of admissible edges; this matches the design intent of BIFO admissibility, which prioritizes predicate vocabularies with explicit directional or causal semantics.

[TODO: Optional Table 4 — source-vocabulary breakdown analogous to Paper 1's ST6 but presented at ontology rather than methods scope.]

### Worked example: BIFO conditioning of a synthetic property graph

To illustrate the conditioning protocol on a graph small enough to inspect directly, we constructed a synthetic property graph spanning genes, transcripts, proteins, pathways, phenotypes, and a disease term [TODO: precise node and edge counts after design]. The graph deliberately includes both admissible mechanistic edges (Transcription, Translation, Signal Transduction, Pathway Contribution, Molecular-to-Phenotype, Phenotype Aggregation) and non-admissible edges (a hierarchy `is_a` edge, a lexical `synonym` edge, and a statistical co-expression edge) so that the filtering behavior can be observed concretely.

[TODO: Fig 3 — toy graph before BIFO conditioning, showing all edges including non-admissible.]

[TODO: Fig 4 — toy graph after BIFO conditioning, with non-admissible edges removed and remaining edges colored by flow-class tier; the resulting directed adjacency operator is clearly non-symmetric.]

After conditioning, the admissible edge set is [TODO: count] of [TODO: count] input edges. The non-admissible edges (hierarchy, lexical, statistical) are excluded as expected. The resulting propagation operator preserves directional flow from G through RNA, P, PW, and PH to DS along the central-dogma backbone defined in the specification, and it preserves Pathway Contribution bridge edges that connect molecular entities to pathway concept nodes. Personalized PageRank applied to this conditioned operator from a seed at the gene layer produces non-trivial mass at the disease and phenotype layers, [TODO: with quantitative comparison to a Personalized PageRank run on the unconditioned graph showing that the conditioned operator routes mass along biologically interpretable paths while the unconditioned operator distributes mass through hierarchy and lexical edges that lack mechanistic interpretation].

This worked example is intended for didactic illustration of the conditioning protocol. Quantitative validation at cohort scale, including benchmark recovery on curated reference pathways and rare-variant pathway analysis on Kids First cohorts, is presented in the BIFO-PPR methods paper [@TODO:bifo-paper-1-biorxiv].


## Discussion

BIFO is a structured ontological framework for organizing and categorizing the admissible biological entities and information flows along which mechanistic signal can propagate in heterogeneous biomedical knowledge graphs. The ontology establishes a normative vocabulary and typed taxonomy for describing what biology *is* in a flow-aware setting, separately from how any particular knowledge graph chooses to represent it. Given the heterogeneous character of biomedical graphs assembled from many source vocabularies, BIFO serves as a unifying framework that enables KG-agnostic graph conditioning, mechanistically constrained propagation, and downstream inference grounded in biologically valid paths.

### Strengths

BIFO offers several advantages for graph-based biomedical inference. The ontology is designed around propagation rules rather than entity cataloging, addressing a gap that existing biomedical ontologies do not occupy. The conditioning protocol is KG-agnostic, depending only on the BIFO Substrate Assumption (typed nodes and edges with resolvable CURIEs), so the same ontology can be applied to property graphs of arbitrary schema and source-vocabulary composition. The mechanistic / weak-mechanistic / observational / contextual classification preserves observational and contextual edges in the conditioned graph as non-propagating annotations, allowing them to inform model construction (priors, weights, constraints) without mistakenly carrying biological state in propagation. The reference DDKG implementation [TODO: cite implementation guide] shows that BIFO conditioning is operationally tractable at production-graph scale, and the separately published BIFO-PPR methods paper [@TODO:bifo-paper-1-biorxiv] reports cohort-scale validation on rare-variant pathway analysis.

### Limitations

BIFO has several limitations that constrain the scope of the present resource. First, the ontology is normative for predicate-to-flow assignment but the predicate vocabulary it covers reflects the source ontologies represented in the DDKG and a small number of related biomedical resources; predicates from source vocabularies outside this scope require extension of `bifo_mapping.yaml` before they can participate in admissibility decisions. Second, the admissibility framework is operational rather than formal in the description-logic sense; flow validity is evaluated procedurally during conditioning rather than reasoned over in an OWL or similar reasoner, [TODO: discuss the trade-off and note that an OWL representation is plausible future work]. Third, the worked example presented here is illustrative; the cohort-scale validation against Kids First congenital heart defect and neuroblastoma data, the benchmark evaluation against curated pathways, and the comparison with non-conditioned baselines are reported in the BIFO-PPR methods paper rather than here. Fourth, BIFO version 0.02 covers a focused set of biological flow categories sufficient for current production use but it is not exhaustive; flow classes for some specialized biology (for example, [TODO: list any known gaps such as immune-receptor recombination, prion propagation, or specific metabolic-network constructs]) are flagged for future extension.

### Position relative to existing frameworks

BIFO is complementary to existing biomedical ontologies and standards rather than competitive with them. The Gene Ontology and HPO provide canonical entity vocabularies that BIFO consumes via its CURIE mapping layer. BFO supplies upper-level categorical commitments (continuants vs. occurrents, dependent vs. independent entities) that are consistent with BIFO's entity-class structure but operate at a higher level of abstraction. GO-CAM and BEL encode mechanistic relationships within their own representational scope; BIFO defines a graph-conditioning protocol that can ingest predicates from such frameworks where they appear in a target KG but does not depend on them being present. SBML encodes explicitly-defined mechanistic models and is targeted at simulation-grade reaction networks; BIFO targets the integrated-KG regime where the input is a heterogeneous property graph rather than a curated model. The Sequence Ontology and HSCLO [@doi:10.1038/s41597-024-04358-x] provide structural vocabularies for genomic features and chromosomal positions; BIFO complements these by adding flow-aware semantics on top of positional and structural semantics. [TODO: round out the comparison with one or two more frameworks the user wants mentioned, such as Reactome representational schema, BioPAX, or graph-ML approaches that condition implicitly on graph topology rather than on biological semantics.]

### Implications and future directions

In clinical and biomedical research contexts, mechanistically grounded propagation in heterogeneous KGs supports rare-disease gene prioritization, cross-cohort pathway analysis, hypothesis-driven exploration of variant function, and integrative analysis across multi-omic and phenotypic data layers. BIFO provides a foundational substrate for these applications by separating biologically valid propagation channels from correlative and structural relationships in the underlying KG. Planned future work includes: extending the predicate vocabulary as new source ontologies are integrated, formalizing the admissibility framework in a description-logic representation suitable for OWL reasoners, [TODO: propagation algorithms beyond Personalized PageRank such as flow-aware diffusion or GNN message passing constrained by BIFO admissibility], and broadening the reference implementation to additional knowledge graphs beyond DDKG.

BIFO stands out from earlier biomedical ontologies by focusing on propagation rules and admissibility constraints over heterogeneous KGs, addressing a gap that entity-centric and relationship-centric ontologies do not occupy. It is well positioned as a unifying conditioning layer for any property graph carrying typed predicates from standard biomedical vocabularies, and it offers a foundation for the next generation of mechanistically grounded inference tools operating on integrated biomedical knowledge graphs.


## Data availability

The BIFO Specification v0.02 in Markdown and PDF form, the predicate-to-flow-class mapping configuration `bifo_mapping.yaml` v0.7.1, and the worked-example synthetic property graph in node-edge CSV form are deposited at the BIFO project page on the Open Science Framework: [TODO: OSF DOI]. The DDKG conditioning coverage statistics reported in Results are derived from the production DDKG export and conditioning runs described in the BIFO-PPR methods paper [@TODO:bifo-paper-1-biorxiv]; the corresponding edge files and conditioning outputs are deposited at [TODO: data deposition target, likely OSF or Zenodo].

## Code availability

The BIFO ontology, including normative tables, mapping configurations, and the conditioning protocol specification, is maintained at <https://github.com/TaylorResearchLab/BIFO>. The BIFO graph conditioning reference implementation, written in Python and operating against the DDKG schema, is available in the BIFO-PPR analysis repository at [TODO: bifo-graph repository URL]. The Manubot source for this manuscript is at <https://github.com/TaylorResearchLab/bifo-paper-0>, with the rendered HTML manuscript at <https://taylorresearchlab.github.io/bifo-paper-0/> and a versioned PDF at <https://taylorresearchlab.github.io/bifo-paper-0/manuscript.pdf>.


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

