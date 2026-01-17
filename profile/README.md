# Integrated Knowledge Exchange (IKE) Community

**The Integrated Knowledge Exchange (IKE) Community** is built on a foundation of versioned knowledge graphs with pluggable formalisms. We embrace OWL/RDF semantics and property graph models as foundational—and extend them with STAMP versioning and cross-formalism integration they weren't designed to provide. Every vertex carries STAMP coordinates (Status, Time, Author, Module, Path), enabling precise tracking of when content was valid, who authored it, and how versions relate. And because change-sets are first-class constructs, you get collaborative development out of the box—supporting both iterative work-in-progress and publication of finalized artifacts for any formalism.

Within this substrate, any knowledge structure can be represented as traversable, versionable content. EL++ terminology definitions, BPMN process models, clinical decision logic—each retains its semantics while becoming composable and version-aware. A workflow can reference a SNOMED concept that contains its own axiom structure, and when either evolves, dependencies are explicit and trackable.

This matters because knowledge systems fail silently. Clinical decision support malfunctions—where alerts stop firing because an identifier changed upstream, or rules break from untracked edits—[affect virtually every healthcare organization](https://pubmed.ncbi.nlm.nih.gov/27026616/). These aren't edge cases; they're version coordination failures that current tools can't prevent or detect. STAMP versioning makes the invisible visible.

As AI systems increasingly depend on structured knowledge—for training data, retrieval-augmented generation, and decision grounding—curation quality becomes critical infrastructure. Flawed knowledge at scale fails *confidently*—and the burden of catching it falls to you. IKE enables principled knowledge curation at scale: expert judgment captured in version-controlled, machine-processable form, so human expertise and modern computation reinforce each other rather than working at cross-purposes.

IKE provides open-source tooling, specifications, and collaborative infrastructure for building knowledge systems that evolve safely. Our work builds on and implements HL7 standards including [Tinkar](https://www.hl7.org/implement/standards/product_brief.cfm?product_id=573) (Terminology Knowledge Architecture) and [ANF](https://www.hl7.org/implement/standards/product_brief.cfm?product_id=523) (Analysis Normal Form). Whether you're coming from ontology engineering, knowledge graph development, or clinical terminology management, if you're working on systems where knowledge changes and correctness matters, you're in the right place.

## Get Involved

Join the conversation on [IKE Zulip](https://ike.zulipchat.com)—an open-source, threaded chat platform where discussions stay organized and searchable over time. Whether you're asking questions, proposing ideas, or collaborating on implementations, Zulip is where the community connects.

---

**Topics:** ontology · knowledge graphs · description logic · terminology management · clinical informatics · SNOMED CT · LOINC · RxNorm · EL++ · OWL · clinical decision support · version control · STAMP · healthcare AI
