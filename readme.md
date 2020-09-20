
# Table of Contents

1.  [Presenter](#org2aad75b)
2.  [Exploratory text analysis and visualization in the research context](#org4b059ec)
3.  [Voyant - Demo](#org164ca22)
    1.  [Installing Voyant vs using the hosted web version](#orgf6e39b4)
    2.  [File types and corpus building](#org3d9b831)
    3.  [Exploring the interface](#org4677d4d)
    4.  [Tools of note](#org20f931b)
    5.  [Exporting results](#org242b184)
4.  [Taguette - Demo](#org799a46f)
    1.  [Installing Taguette vs using the hosted web version](#org2c07ac1)
    2.  [File types](#org87e4f13)
    3.  [Basic workflow](#org023b6d6)
    4.  [Exporting results](#org9542213)
5.  [Putting it together: between distant and close reading](#orgadd42f4)
6.  [Resources](#orgdeaa660)



<a id="org2aad75b"></a>

# Presenter

[Scott Bailey](https://www.lib.ncsu.edu/staff/csbaile3)   
Digital Research and Scholarship Librarian   
Copyright and Digital Scholarship Center   
[NC State University Libraries](https://www.lib.ncsu.edu)


<a id="org4b059ec"></a>

# Exploratory text analysis and visualization in the research context

Key take-aways:

1.  Text corpora exist with a wide range of metadata, cleanliness, and quality.
2.  Even when we have a good sense of method or approach, exploring our data, whether quantitative or qualitative, helps us refine research questions, fine-tune methods, and scope our project to be successful.
3.  Voyant and Taguette are free and open source tools that allow you analyze and visualize texts, whether as single documents or whole corpora.


<a id="org164ca22"></a>

# Voyant - Demo


<a id="orgf6e39b4"></a>

## Installing Voyant vs using the hosted web version

There is a hosted version of Voyant at [https://voyant-tools.org/](https://voyant-tools.org/) that has two text corpora available. This is a great way to experiment with and learn Voyant, and can be used for your own corpora.

You can also download and host Voyant yourself, and I recommend this for working with larger corpora and in order to work offline. Since you can adjust the memory available to Voyant, there is an advantage in speed and the size of corpus you can analyze.

Download and install page: <https://digihum.mcgill.ca/voyant/resources/run-your-own/voyant-server/>


<a id="org3d9b831"></a>

## File types and corpus building

Voyant can handle single documents, either by uploading them or simply copying text into the Voyant home screen input box. It provides even more power, though, when you upload many documents as a corpus.

Supported file types:

-   plain text: .txt
-   HTML: .htm, .html
-   XML: .xml
-   Word: .doc, .docx
-   RTF: .rtf
-   PDF: .pdf


<a id="org4677d4d"></a>

## Exploring the interface

-   Basic layout
-   Getting help for each tool
-   Settings for each tool
-   Clicking on a document or word in one tool typically causes the other tools to update accordingly


<a id="org20f931b"></a>

## Tools of note

-   Summary: basic statistics on your document or your corpus, including most frequent terms and most distinctive terms per document (tf-idf)
-   Contexts: keyword-in-context tool
-   Correlations: Pearson&rsquo;s correlation for pairs of terms in the document/corpus, and significance for the correlation
-   Trends: trends over documents or document chunks for terms according to relative frequency or raw count
-   Topics (Hidden by default): topic modeling by way of the latent dirichlet allocation (LDA) algorithm
-   There are many tools - explore them all!


<a id="org242b184"></a>

## Exporting results

What formats you can use for export depends on each tools, but in general:

-   Exporting visualizations: PNG, HTML, SVG
-   Exporting data: HTML, TSV, JSON


<a id="org799a46f"></a>

# Taguette - Demo


<a id="org2c07ac1"></a>

## Installing Taguette vs using the hosted web version

Taguette also has a hosted version at [https://app.taguette.org/](https://app.taguette.org/). You can use the hosted for full projects, including collaborating with others on your qualitative analysis project.

You can also download and run Taguette on your own computer, or run your own server. On your own computer, you won&rsquo;t be able to use the collaboration feature, but can still carry out your analysis and export results.

Download and install page: <https://www.taguette.org/install.html>


<a id="org87e4f13"></a>

## File types

Supported file types:

-   plain text: .txt
-   HTML: .htm, .html
-   Word: .doc, .docx
-   RTF: .rtf
-   PDF: .pdf
-   Open Documents: .odt
-   E-books: .epub, .mobi


<a id="org023b6d6"></a>

## Basic workflow

-   Creating a project
-   Adding documents
-   Highlighting text and adding tags
    -   Creating hierarchical tags (parent and child codes)


<a id="org9542213"></a>

## Exporting results

-   Exporting collated tagged texts: PDF, HTML, DOCX, XSLX, CSV
-   Exporting your codebook: PDF, HTML, DOCX, XSLX, CSV, XML


<a id="orgadd42f4"></a>

# Putting it together: between distant and close reading

Key take-aways:

1.  Distant reading allows us to analyze and draw conclusions from collections of texts at large scale.
2.  Close reading helps us develop a nuanced understanding of texts.
3.  Research is iterative, and moving between distant and close reading allows us to develop interpretations and conclusions that draw on the whole of a corpus without losing the nuance.


<a id="orgdeaa660"></a>

# Resources

-   Voyant Docs: <https://digihum.mcgill.ca/voyant/>
-   Voyant Tools Docs: <http://docs.voyant-tools.org/tools/>
-   UC Santa Cruz Getting Started with Voyant: <https://guides.library.ucsc.edu/DSCguides/Voyant>
-   Taguette Getting Started Guide: <https://www.taguette.org/getting-started.html>
-   Illinois Library Coding with Taguette Guide: <https://guides.library.illinois.edu/qualitative/taguette>

