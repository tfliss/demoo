#### Recommend and Demonstrate a Lightweight workflow for Ontology Creation and Maintenance


##### Our use case


Select and deploy and document a simple, usable tool and pracice that enable industry-standard creation, deployment and maintenance of a biological ontology.

- CSV Import (multiple CSV's, YAML, etc. templates may be needed)
- Non-expert configuration and use (neither ontologist or programmer needed for daily editing, clear and simple documentation)
- SHACL validation when an ontology is generated with updated input files
- Versioning (essentially github with versioned ontology artifacts)


##### Ontology


An ontology is essentially a directed graph of relations between entities organized around a backbone taxonomy ('Is a' releationships) and their definitions expressed in terms of relations and entities.

Modern domain ontologies are modular, shared and interoperable. [OBO Foundry](http://www.obofoundry.org/) is an example of a collection of such ontologies. [Basic Formal Ontology](https://basic-formal-ontology.org/) provides a minimal upper ontology with shared definitions such as temporal and spatial entities.


##### Proliferation of tools, practices and notation


Modern practice adopts software engineering techniques of version control, validation and a build pipeline. The pipeline can be light weight, such as a method for running command-line tools in a certain order and working in a [GitHub](https://github.com/) repository. Ontology validation tools such as [SHACL](https://www.w3.org/wiki/SHACL/Examples) (SHApe Constraint Language) can be configured in a build system to detect errors.


Communities of practice exist around different organizations which has led to a proliferation of tools, techniques and notations for authoring ontologies. Each has various goals, intended audiences and maturity levels. Notations such as RDF/XML, Turtle and Manchester notation might be better for human or machine readability, but they are largely interoperable. Examples of authoring techniques such as [OBO Principles](http://www.obofoundry.org/principles/fp-004-versioning.html), "best practices" for working with the BFO (see Chapter 3 of [Building Ontologies with Basic Fromal Ontology](https://mitpress.mit.edu/books/building-ontologies-basic-formal-ontology) and evolving patterns such as [DOS-DP](https://github.com/INCATools/dead_simple_owl_design_patterns) (Dead-Simple Ontology Design Patterns)


##### What is best for us right now

There are dozens of existing tools of varying levels of popularity, functionality, maturity, and from different communities of practice. There are plugins for CSV import into Protege. The [Onto Animal](http://www.hegroup.org/ontozoo/) family is an example of web based tools. [Robot](http://robot.obolibrary.org/) and [Ontology Development Kit](https://github.com/INCATools/ontology-development-kit) represent command-line packages that are gaining popularity. [OwlReady2](https://pythonhosted.org/Owlready2/), a Python library and [OWL API](http://owlcs.github.io/owlapi/), a Java library do not provide complete pipelines, but may be needed to adapt existing pipelines or to debug or fix problems.

Existing ontology authoring tools fall into categories of Editors and integrated development environments (IDE's), command-line packages, web forms, and software libraries. The categories are fluid. Many of the tools are written as libraries (or libraries provide simple tools). Many editors provide a scripting or plugin facility. Many of the tools are inherently interoperable due to the standard nature of the underlying formats.


##### The Long(-ish) list

There's a longer list that includes detailed evaluation criteria that will be updated over the course of the next day or two.

[OntoZoo/Ontorat](http://ontorat.hegroup.org/) - Web tools, older, decent use

[OwlReady2](https://pythonhosted.org/Owlready2/) - Python library, usable, gaining popularity

[OWL API](http://owlcs.github.io/owlapi/) - Java library "industry standard"

[OntoPilot](http://ontopilot.com/) - Commercial tool, recently abandoned

[Tawny-OWL](https://github.com/phillord/tawny-owl#tawny-owl) - Clojure functional language editor and tools

[INCATOOLs/ontology-development-kit](https://github.com/INCATools/ontology-development-kit#ontology-development-kit) - all-in-one OBO ontology project generator

[ROBOT](http://robot.obolibrary.org/) - command-line tools for working with OBO Foundry

----

[GUID-o-matic](http://bioimages.vanderbilt.edu/guid-o-matic/index.htm) - basic tool for CSV import of library/museum ontologies

[Term GENIE](https://github.com/geneontology/termgenie) - Automatic generation of ontologies

[Ontology PreProcessing Language](http://oppl2.sourceforge.net/) - A language for specifying repeated patterns in an ontology.

