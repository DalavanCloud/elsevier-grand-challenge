# elsevier-grand-challenge

## Introduction
My entry in Elsevier's Grand Challenge [Knowledge Enhancement in the Life Sciences](http://www.elseviergrandchallenge.com/). My original proposal (rather grandly titled "Towards realising Darwin’s dream: setting the trees free") is available from Nature Precedings [doi:10.1038/npre.2008.2217.1](http://dx.doi.org/10.1038/npre.2008.2217.1). A paper describing the actual entry is also available [Visualising a scientific article](http://dx.doi.org/10.1038/npre.2008.2579.1).

My project used a collection of fulltext issues of *Molecular Phylogenetics and Evolution* as the starting point, then extracts citation links to both papers and data, such as Genbank sequences and specimens, together with geotagged localities, and builds a "web" of objects linked by relationships. Each object (such as a publication, a sequence, a specimen, a taxon name, etc.) is treated equally, so that you can take a publication and see what taxa it refers to, or take the taxon and find all the publications that refer to the taxon. Although the database has been seeded with some articles from *Molecular Phylogenetics and Evolution*, much of the data comes from [GenBank](http://www.ncbi.nlm.nih.gov/Genbank/index.html), [PubMed](http://www.ncbi.nlm.nih.gov/sites/entrez?db=PubMed), and specimen databases. These are accessed through bioguid.info, a tool I constructed to resolve identifiers and return associated metadata.

## Background
You can find background on this project [on my blog](http://iphylo.blogspot.com/search?q=challenge). In many ways the inspiration for this project is [SiloBreaker](http://www.silobreaker.com/).