## Open Contracting Data Standard - Linked Data Edition

This project aims at enabling any JSON data that complies with the [OCDS JSON Schema](http://standard.open-contracting.org/latest/en/schema/) to be published as [Linked Data](https://www.w3.org/standards/semanticweb/data).

### What is OCDS

The **[OCDS](http://standard.open-contracting.org/latest/en/)** is a data model that aims at structuring and publishing contracting data (tenders, procurements, awards, transactions, etc.). It got international adoption and is one of the leading models in this domain.

**[Linked Data](https://www.w3.org/standards/semanticweb/data)** is a way of publishing data that relies on few principles:

- a resource is identified with an HTTP URI (not a plain string)
- dereferencing (HTTP GET) this URI returns data about the resource
- the description of the resource contains relations to other resources, also identified with URIs.

The result: a meshed network of resources than can easily be traversed by a machine.

**[RDF](https://www.w3.org/TR/2014/NOTE-rdf11-primer-20140225/#section-Introduction)** is the framework that powers Linked Data.

### An RDF/Linked Data variant of the Open Contracting Data Standard (OCDS) JSON Schema.

The first deliverable of this project is an ontology (~ schema) that translates the structure and semantics expressed in the OCDS JSON Schema into RDF.

- [Turtle file](https://github.com/ColinMaudry/open-contracting-ld/blob/master/ocds.ttl) with lots of comment in the header
- [Visualization](http://vowl.visualdataweb.org/webvowl/index.html#iri=https://raw.githubusercontent.com/ColinMaudry/open-contracting-ld/master/ocds.ttl)
- [SPARQL endpoint](http://dydra.com/colin-maudry/ocds/sparql)

### A JSON-LD context to turn any data compliant with OCDS JSON Schema into RDF

You can find the JSON-LD context files like this format context-xxx.json. We create one context file per concept at the ontology.

### License

This project is licensed under the terms of the [CC-BY license](https://creativecommons.org/licenses/by/2.0/). That basically means you can do what you want with it, as long as you mention I'm the author of the original version, with a link to this page.

This work was developed by Rodrigo Valdez (https://github.com/yank07/) and Camilo Baez (https://github.com/camilobaezcamba/) as part the thesis work of Software Engeineer at the Universidad Nacional de Asuncion

"Original version by Colin Maudry (http://colin.maudry.com), published at https://github.com/ColinMaudry/open-contracting-ld."

