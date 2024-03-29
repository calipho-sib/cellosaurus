Cellosaurus
===========

## WARNING: This directory is no longer updated: the Cellosaurus files in the 3 formats (text, OBO and XML) are too big to be stored on GitHub

For the current version of the Cellosaurus go to:
ftp://ftp.expasy.org/databases/cellosaurus

All the versions of the Cellosaurus are archived at:
https://yareta.unige.ch/home/search?search=search%3Dcellosaurus

## A knowledge resources on cell lines

From the CALIPHO group of the SIB - Swiss Institute of Bioinformatics

The Cellosaurus is a knowledge resource on cell lines. It attempt to describe all cell lines used in biomedical research.

 - Immortalized cell lines
 - Naturally immortal cell lines (ie stem cell lines)
 - Finite life cell lines when those are distributed and used widely
 - Vertebrate cell lines with an emphasis on human, mouse and rat cell lines
 - Invertebrate (insects and ticks) cell lines

Its scope does not include:

 - Primary cell lines (with the exception of the finite life cell lines described above)
 - Plant cell lines

For each cell line we provide the following information:

- A recommended name. This is most frequently the name provided in the original publication.
- A list of synonyms. We try to list all the different synonyms for the cell line, including alternative use of lower and upper cases characters.
- A unique accession number.
- Structured comments that are describe a number of topics such as: contaminated cell lines, misspellings, breed/subspecies a cell line is derived from, gene transfection, transformant, the sampling site (tissue/organ), population doubling time, HLA typing, sequence variations, etc.
- For cell lines originating from a diseased patient/animal, we provide the NCI Thesaurus entry code for the disease(s) that the individual from which the cell line originated was suffering from. For human rare diseases we also provide the ORDO entry code of the disease.
- For human, mouse and dog cell lines where this information is available, we provide the STR (short tandem repeat) profile information.
- The species of origin.
- If a cell line originate from another one we provide a link to the parent cell line.
- If a cell line originate from the same individual as other cell line(s) (sister cell lines) cross-reference to these sister cell line(s) are provided.
- The sex of the individual from which the cell line has been derived.
- The age of the individual from which the cell line has been derived (at the time of "sampling").
- The category to which a cell line belong. Currently this can be one of the following categories: Cancer cell line; Conditionally immortalized cell line; Embryonic stem cell; Factor-dependent cell line; Finite cell line; Hybrid cell line; Hybridoma; Induced pluripotent stem cell; Spontaneously immortalized cell line; Somatic stem cell; Stromal cell line; Telomerase immortalized cell line; Transformed cell line; Undefined cell line type
- Web links.
- Publication references. We principally provide the references for publications describing the establishment of a cell line or its characterization. We do not attempt to capture all the literature that make use of a particular cell line.
- Cross-references to cell line catalogs/collections, ontologies, cell lines databases/resources and to databases that list cell lines as samples.
- Information on when a Cellosaurus entry was created, when it was last updated and which version of the entry is currently available.

## Availability

The Cellosaurus is available/searchable on the web and downloadable by FTP

Home page:
https://www.cellosaurus.org/

Individual entry pages: 'https://www.cellosaurus.org/%s' where %s is the accession number of the cell line

Example:
https://www.cellosaurus.org/CVCL_0033

Text version of entry pages are also available: 'https://www.cellosaurus.org/%s.txt' where %s is the accession number of the cell line

Example:
https://www.cellosaurus.org/CVCL_0033.txt

API:
https://api.cellosaurus.org/

FTP: 
ftp://ftp.expasy.org/databases/cellosaurus

The files that are distributed by FTP and are on GitHub are:

- cellosaurus.txt: Cellosaurus in structured flat file format
- cellosaurus_refs.txt: Reference records file: publications, patents, book chapters
- cellosaurus_xrefs.txt: File describing how to build live links to all the resources listed in the Cellosaurus

- cellosaurus.obo: Cellosaurus in OBO format

- cellosaurus.xml: Cellosaurus in XML format [*]
- cellosaurus.xsd: XML Schema Definition (XSD) for cellosaurus.xml

- cellosaurus_deleted_ACs.txt: List of deleted accession numbers/entries
- cellosaurus_name_conflicts.txt: Tables of cell lines with identical names
- cellosaurus_faq.txt: Frequently asked questions
- cellosaurus_relnotes.txt: Release notes: release statistics and description of format changes

- cellopub.txt: Abstracts and web links for references that are not in PubMed, DOI or Patent (identifiers CLPUBnnnnn)

[*] Important note: the cellosaurus.xml file is only available on the FTP site as it is too big to be stored in GitHub.

## Reference

Bairoch A.
The Cellosaurus, a cell line knowledge resource.
J. Biomol. Tech. 29:25-38(2018).
DOI: 10.7171/jbt.18-2902-002; PMID: 29805321
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5945021/

## The Cellosaurus "ecosystem"

The Cellosaurus:

* contributes to the Research Identification Initiative by being the supplier of Research Resource Identifiers (RRIDs) for cell lines (https://scicrunch.org/resources)
* contributes to the efforts of the International Cell Line Authentication Committee (ICLAC) (https://iclac.org/databases/)
* closely collaborate with hPSCreg in the framework of the annotation of hESCs and hiPSCs (https://hpscreg.eu/about/structures-and-partners)
* is a participant in the European Joint Programme on Rare Diseases (EJP RD) (https://www.ejprarediseases.org/index.php/coordinated-access-data-services/access-to-data-resources/)
* is a Global Core Biodata Resource (https://globalbiodata.org/what-we-do/global-core-biodata-resources/)
* is an ELIXIR Core Data Resource (https://elixir-europe.org/platforms/data/core-data-resources)
* is an IRDiRC Recognized Resource (https://irdirc.org/resources-2/irdirc-recognized-resources/)

## Some educational material

Video: Why should you use Cellosaurus, the cell line encyclopedia?
https://www.youtube.com/watch?v=xKA2AleIe0g

Introductory course on the Cellosaurus
https://edu.sib.swiss/course/view.php?id=585

## Licensing

[![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a [Creative Commons Attribution 4.0 International
License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
