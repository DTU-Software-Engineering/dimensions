# Formal Concept Analysis
##### A formal foundation for SEAMS artifact characterization and reasoning.
###### Joe Kiniry

 - [The Big Picture] [http://en.wikipedia.org/wiki/Formal_concept_analysis]
 - [To Do: review papers published since my dissertation was written] [http://scholar.google.com/scholar?hl=en&q=Wille+Formal+concept+analysis&btnG=&as_sdt=1%2C5&as_sdtp=]

## Main Purposes of Foundation

SEAMS artifacts need to be formally characterizable in some fashion so
that they can be assigned dimensions, measured, and compared with each
other.  The formal foundation must support the evolution of both the
artifacts themselves as well as the identification of new, or
evolution of existing, dimensions.

One possible formalization appropriate for this set of goals is formal
concept lattices, also known as Galois lattices.  Formal concept
analysis is a rigorous way to identify, derive, classify, and reason
about ontologies from a collection of objects and their properties.
In our setting, software engineering artifacts are the objects and
dimensions are their properties.

Concepts relate to each other implicitely via their properties and new
objects and properties can be introduced in an arbitrary fashion.  One
can identify new concepts and properties, as well as relationships
between concepts and properties, by virtue of reasoning about the
lattices induced by a specific set of concepts and properties.  

For example, a collection of software engineering artifacts tagged
with (hand-written or generated) metadata can be explored and reasoned
about as a concept lattice with no additional work and, moreover,
relationships between concepts and their properties like "is-a",
"has-a", "is-like", "is-equivalent-to" are automatically identified.

The term formal concept analysis and its application was introduced by
Rudolf Wille in 1984 and is based upon applied lattice and order
theory that came from Birkhoff and others in the early 20th century.

A number of tools, particular from within the area of the semantic
web, support reasoning with/about specific formal concept lattices.
Reasoning about formal concept lattices themselves is within the
purvey of interactive theorem proving (e.g., using PVS, Coq, or
Isabelle).  We have formalized SEAMS concept lattices within PVS using
an existing formalization of formal concept lattices from Alonso et
al.

A nice side effect of choosing formal concept (Galois) lattices as a
foundation is that the semantics of artifacts can be neatly formalized
and reasoned about with RAISE, as Bjorner's recent work on [Domain
Science & Engineering][Bjorner12] is a variant of formal concept
analysis.  Given the nature of Galois lattices, any modern formal
method integrates well with this foundation including, e.g., Alloy,
Event-B, VDM, or Z.

## References

Main references are from Wille and co-authors.  See entries
GanterWille99, LehmannWille95, Sarbo96, Wille82, Wille83, Wille85,
Wille92, Wille95, Wille97, and WilleWille96 in [the bibliography][bib].

  [bib]: ../bib/bib.bib


