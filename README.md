Cellosaurus
===========

From the CALIPHO group of the SIB - Swiss Institute of Bioinformatics; neXtProt project

##A knowledge resources on cell lines

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
- Structured comments that are describe a number of topics such as: contaminated cell lines, misspellings, breed/subspecies a cell line is derived from, gene transfection, metastatic site for cancer cell lines, transformant, etc.
- For cancer and human genetic disease cell lines, we provide the NCI Thesaurus entry code for the disease(s) that the individual from which the cell line originated was suffering from.
- For human cell lines where this information is available, we provide the STR (short tandem repeat) profile information.
- The species of origin.
- If a cell line originate from another one we provide a link to the parent cell line.
- If a cell line originate from the same individual as other cell line(s) (sister cell lines) cross-reference to these sister cell line(s) are provided.
- The sex of the individual from which the cell line has been derived.
- The category to which a cell line belong. Currently this can be one of the following categories: Adult stem cell; Cancer cell line; Conditionally immortalized cell line; Embryonic stem cell; Factor-dependent cell line; Finite cell line; Hybrid cell line; Hybridoma; Induced pluripotent stem cell; Spontaneously immortalized cell line; Stromal cell line; Telomerase immortalized cell line; Transformed cell line; Undefined cell line type
- Web links.
- Publication references. We principally provide the references for publications describing the establishment of a cell line or its characterization. We do not attempt to capture all the literature that make use of a particular cell line.
- Cross-references to cell line catalogs/collections, ontologies, cell lines databases/resources and to databases that list cell lines as samples.

##Availability

The Cellosaurus is available/searchable on the web and downloadable by FTP

Home page:
http://web.expasy.org/cellosaurus/

Individual entry pages: 'http://web.expasy.org/cellosaurus/%s' where %s is the accession number of the cell line

Example:
http://web.expasy.org/cellosaurus/CVCL_0033

FTP: 
ftp://ftp.expasy.org/databases/cellosaurus

The files that are distributed by FTP and are on GitHub are:

- cellosaurus.txt: Cellosaurus in structured flat file format
- cellosaurus_refs.txt: Reference file: publications, patents, book chapters
- cellosaurus_xrefs.txt: File describing how to build live links to all the resources listed in the Cellosaurus

- cellosaurus.obo: Cellosaurus in OBO format

- cellosaurus.xml: Cellosaurus in XML format
- cellosaurus.xsd: XML Schema Definition (XSD) for the Cellosaurus XML

- cellosaurus_deleted_ACs.txt: List of deleted accession numbers/entries
- cellosaurus_faq.txt: Frequently asked questions
- cellosaurus_relnotes.txt: Release notes: provides statistics and description of format changes from the previous release

Important note: the cellosaurus.xml file is only available on the FTP site
as it is too big to be stored in GitHub.

