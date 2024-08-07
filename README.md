# Awesome Federated Content Search (FCS) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of awesome FCS frameworks, libraries, software and resources

<!-- see https://github.com/sindresorhus/awesome-lint -->
<!--lint disable double-link-->

## Contents

- [Websites](#websites)
- [Specification Documents](#specification-documents)
- [Guides and Tutorials](#guides-and-tutorials)
- [Reference Implementations for SRU / FCS](#reference-implementations-for-sru--fcs)
- [Endpoint Implementations](#endpoint-implementations)
- [Client Implementations](#client-implementations)
- [Query Parsers](#query-parsers)

## Websites

*Websites about FCS.*

- [Content search at CLARIN](https://www.clarin.eu/content/content-search)
- [Federated Content Search (CLARIN-FCS) - Technical Details](https://www.clarin.eu/content/federated-content-search-clarin-fcs-technical-details)
- [Official FCS SRU Aggregator at CLARIN](https://contentsearch.clarin.eu/) - Main FCS client and frontend for users.
- [CLARIN Centre Registy (FCS)](https://centres.clarin.eu/fcs) - List of CLARIN FCS Endpoints.
- [CLARIN-FCS Endpoint Validator (previously: Conformance Tester)](https://www.clarin.eu/fcsvalidator)
- [CLARIN Forum - Topics with _fcs_ tag](https://forum.clarin.eu/tag/fcs)
- [CLARIN-FCS Latest Documents](https://clarin-eric.github.io/fcs-misc/) - GitHub Build of specification/tutorial documents of the `fcs-misc` repo.

## Specification Documents

*Specification documents related to FCS and related technologies.*

- [FCS Specification Document Sources for FCS 2.0, 1.0, Data Views, AAI (AsciiDoc)](https://github.com/clarin-eric/fcs-misc) - Also contains XSD schema files and examples.
  - [FCS 2.0 Core Specification (PDF, v20230426)](https://office.clarin.eu/v/CE-2017-1046-FCS-Specification-v20230426.pdf) [(PDF, v20220803)](https://office.clarin.eu/v/CE-2017-1046-FCS-Specification-v89.pdf)
  - [FCS Data Views 1.0 Specification (PDF, v20170613)](https://office.clarin.eu/v/CE-2014-0317-CLARIN_FCS_Specification_DataViews_1_0-v20170613.pdf)
- [Library of Congress: SRU/CQL](https://www.loc.gov/standards/sru/) - Search/Retrieval via URL, Contextual Query Language.
  - [CQL: Contextual Query Language](http://www.loc.gov/standards/sru/cql/spec.html) - Query language for mandatory BASIC search capability that each endpoint must support.
  - [SRU 1.2](https://www.loc.gov/standards/sru/sru-1-2.html) - For FCS 1.0 and backward compatibility in FCS 2.0.
  - [SRU 2.0](https://www.loc.gov/standards/sru/sru-2-0.html) - For FCS 2.0.
  - [Differences between SRU 1.2 and SRU 2.0](http://www.loc.gov/standards/sru/differences.html)
- [OASIS: searchRetrieve: Part 0. Overview Version 1.0](http://docs.oasis-open.org/search-ws/searchRetrieve/v1.0/os/part0-overview/searchRetrieve-v1.0-os-part0-overview.html)
  - [searchRetrieve: Part 1. Abstract Protocol Definition Version 1.0](http://docs.oasis-open.org/search-ws/searchRetrieve/v1.0/os/part1-apd/searchRetrieve-v1.0-os-part1-apd.html)
  - [searchRetrieve: Part 2. searchRetrieve Operation: APD Binding for **SRU 1.2** Version 1.0](http://docs.oasis-open.org/search-ws/searchRetrieve/v1.0/os/part2-sru1.2/searchRetrieve-v1.0-os-part2-sru1.2.html)
  - [searchRetrieve: Part 3. searchRetrieve Operation: APD Binding for **SRU 2.0** Version 1.0](http://docs.oasis-open.org/search-ws/searchRetrieve/v1.0/os/part3-sru2.0/searchRetrieve-v1.0-os-part3-sru2.0.html)
  - [searchRetrieve: Part 5. **CQL: The Contextual Query Language** Version 1.0](http://docs.oasis-open.org/search-ws/searchRetrieve/v1.0/os/part5-cql/searchRetrieve-v1.0-os-part5-cql.html)
  - [searchRetrieve: Part 7. **Explain** Version 1.0](http://docs.oasis-open.org/search-ws/searchRetrieve/v1.0/os/part7-explain/searchRetrieve-v1.0-os-part7-explain.html)
 
## Guides and Tutorials

*Guides and Tutorial about FCS.*

- [FCS Endpoint Development Guide](https://www.clarin.eu/fcsdevguide) - RevealJS presentation about FCS, SRU, endpoint development and more.
- *WIP* [FCS Endpoint Dev Tutorial](https://github.com/clarin-eric/fcs-misc/tree/feature/fcs-endpoint-dev-tutorial) [[PDF, 2016-01](https://github.com/clarin-eric/fcs-misc/blob/feature/fcs-endpoint-dev-tutorial/historical/documents/FCS-2-endpoint-developers-tutorial.pdf)] - Endpoint Developers' Tutorial for using the CLARIN SRU/FCS libraries.
- [Content Search Tutorial using the CLARIN FCS Aggregator](https://www.clarin.eu/content/content-search-tutorial)
- [How to Search for Linguistic Patterns across Collections of Resources](https://docs.google.com/document/d/1lVAnLtvasR3FZ4jPjVQM9X_xXqIsgVYUIFgz1Rgbteo/edit#heading=h.qk98yzwql21k)

## Reference Implementations for SRU / FCS

*Libraries and reference implementations.*

- [SRU/CQL server implementation conforming to SRU/CQL (Java)](https://github.com/clarin-eric/fcs-sru-server) 
  [[docs](https://clarin-eric.github.io/fcs-sru-server/)] 
  [[python impl](https://github.com/Querela/fcs-sru-server-python)]
- [SRU/CQL client implementation conforming to SRU/CQL (Java)](https://github.com/clarin-eric/fcs-sru-client) 
  [[docs](https://clarin-eric.github.io/fcs-sru-client/)]
- [Simple CLARIN FCS endpoint (Java)](https://github.com/clarin-eric/fcs-simple-endpoint) 
  [[docs](https://clarin-eric.github.io/fcs-simple-endpoint/)] 
  [[python impl](https://github.com/Querela/fcs-simple-endpoint-python)]
- [CLARIN-FCS client implementation (Java)](https://github.com/clarin-eric/fcs-simple-client) 
  [[docs](https://clarin-eric.github.io/fcs-simple-client/)]
- [FCS SRU Aggregator (Java)](https://github.com/clarin-eric/fcs-sru-aggregator)
- [Korp FCS 2.0 Reference Endpoint Implementation (Java)](https://github.com/clarin-eric/fcs-korp-endpoint) 
  [[python impl](https://github.com/Querela/fcs-korp-endpoint-python)]
- [SRU/CQL/FCS Endpoint Conformance Tester](https://github.com/clarin-eric/fcs-endpoint-tester)
- [SRU/CQL/FCS Endpoint Validator](https://github.com/saw-leipzig/fcs-endpoint-validator) - Rewrite of the Conformance Tester with more features.
- [SRU/FCS Endpoint Archetype](https://github.com/clarin-eric/fcs-endpoint-archetype) - Easy bootstrapping of new Java SRU/FCS Endpoint projects.

## Endpoint Implementations

*Endpoint implementations in various languages for different search backends.*

- [Korp FCS 2.0 Reference Endpoint Implementation (Java)](https://github.com/clarin-eric/fcs-korp-endpoint) 
  [[python impl](https://github.com/Querela/fcs-korp-endpoint-python)]
- [FCS (2.0) SRU CQI Bridge (Java)](https://github.com/clarin-eric/fcs-sru-cqi-bridge)
- [BlackLab and Mtas FCS 2.0 endpoint implementation](https://github.com/INL/clariah-fcs-endpoints)
- [KorapSRU - FCS 2.0 endpoint for KorAP (Java)](https://github.com/KorAP/KorapSRU)
- [ARCHE-FCS - FCS 2.0 endpoint for ARCHE (PHP)](https://github.com/acdh-oeaw/arche-fcs)
- [CLARIAH Federated Content Search Corpora - FCS 2.0 endpoint (Java)](https://github.com/INL/clariah-fcs-endpoints)
- [Kielipankki Korp FCS 2.0 Endpoint (Java)](https://github.com/CSCfi/Kielipankki-fcs-korp-endpoint)
- [FCS 2.0 endpoint for Manatee-go (Go)](https://is.muni.cz/th/g4k0b/) [[sources](https://is.muni.cz/th/g4k0b/manatee-fcs2.zip)]
- [FCS **1.2** endpoint in NoSketchEngine/Bonito (frontend for Manatee) (Python)](https://nlp.fi.muni.cz/trac/noske)
- [FCS **1.0** endpoint in KonText (frontend for Manatee) (Python)](https://github.com/czcorpus/kontext/blob/master/lib/views/fcs.py)
- [CLARIN FCS **2.0** Endpoint for Manatee-open corpus search engine](https://github.com/czcorpus/mquery-sru)
- [FCS 2.0 endpoint for NoSketchEngine/Bonito (Java)](https://github.com/Leipzig-Corpora-Collection/fcs-noske-endpoint)

## Client Implementations

*FCS client implementation to query endpoints.*

- [Official FCS SRU Aggregator (Java)](https://github.com/clarin-eric/fcs-sru-aggregator)
  - [Vue Pinia Store to communicate with *FCS SRU Aggregator* REST API (JavaScript)](https://git.saw-leipzig.de/text-plus/FCS/textplus-fcs-store/)
- [SRU/CQL/FCS Endpoint Conformance Tester](https://github.com/clarin-eric/fcs-endpoint-tester)

## Query Parsers

*Parsers, syntax highlighters and converters for FCS query languages.*

### CQL (Contextual Query Language)

- [CQL Parser (Java)](https://github.com/indexdata/cql-java)
- [CQL Parser (JavaScript)](https://github.com/Querela/cql-js)
- [CQL Parser (Python)](https://github.com/Querela/cql-python)
- [CQL Parser - from `Cheshire3` Search Engine and Information Framework (Python)](https://github.com/cheshire3/cheshire3/blob/develop/cheshire3/cqlParser.py)
- [CQL Parser - from `ARCHE-FCS` (PHP)](https://github.com/acdh-oeaw/arche-fcs/tree/master/src/acdhOeaw/cql)

### FCS-QL (Federated Content Search Query Language)

- [FCS-QL parser and utilities (Java)](https://github.com/clarin-eric/fcs-ql)
- [FCS-QL parser (based on Java implementation) (Python)](https://github.com/Querela/fcs-ql-python)

### Query Converters

- [Translation of query languages to serialized KoralQuery protocol (Java)](https://github.com/gremid/Koral) - CQL/FCS-QL to Koral.
- [CQL to XCQL Transformer (XQuery)](https://github.com/digicademy/cql-parser-xqm)

### Syntax Highlighters and Higlighting Grammars

- [Prism.js for CQL and FCS query languages (JavaScript)](https://github.com/clarin-eric/fcs-syntax-highlighting)
- [Input Overlay with Prism.js for CQL and FCS query languages (Vue, JavaScript)](https://git.saw-leipzig.de/text-plus/FCS/textplus-fcs-prism)
