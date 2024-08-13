# attribution-description-framework

Ths repository intends to define standards for attribution of content that
is used for training of (generative) AI models.  The Attribution Description 
Framework (ADF) builds upon RDF (Resource Description Framework) to create a 
mechanism to describe both the origin and permitted uses of particular 
content within training corpora of machine learning models.

RDF is chosen as a basis for ADF because a variety or tools and standards
already exists in relation to RDF, including 
[an abstract syntax](https://www.w3.org/TR/2014/REC-rdf11-concepts-20140225/), 
a (concrete XML syntax)[https://www.w3.org/TR/rdf-syntax-grammar/], the 
[Terse RDF Triple Language](https://www.w3.org/TR/turtle/), and most 
importantly, [a semantics](https://www.w3.org/TR/2014/REC-rdf11-mt-20140225/) 
Evert ADF document or snippet should be a valid RDF document or snippet (in 
the appropriate syntax).  The converse statement will be strived for, but
may possibly be violated if necessary as requirements are clarified.

The key insight in this approach to an attribution (and provenance) standard
is that every *obligation* that a creator may impose upon derived AI models
can be expressed in relationship to a specific license that governs rights and
permissions.  Such licenses will typically fall within the family of [Responsible 
AI Licenses](https://www.licenses.ai/), but other licenses such as CC-0 or even
fully proprietary and non-permissive license can similarly be described.
