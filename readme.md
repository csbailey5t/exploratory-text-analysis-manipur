
# Table of Contents

1.  [Presenter](#org73b2d27)
2.  [Exploratory text analysis and visualization in the research context](#orgf336508)
3.  [Voyant - Demo](#org03c70d0)
    1.  [Installing Voyant vs using the hosted web version](#org2242939)
    2.  [File types and corpus building](#org20dcde1)
    3.  [Exploring the interface](#orgd9381dc)
    4.  [Tools of note](#org142c1bd)
    5.  [Exporting results](#org848f38d)
4.  [Taguette - Demo](#org0916516)
    1.  [Installing Taguette vs using the hosted web version](#org636ab12)
    2.  [File types](#org7c6fc22)
    3.  [Basic workflow](#org84ac7dc)
    4.  [Exporting results](#orgccc1ada)
5.  [Putting it together: between distant and close reading](#orga702e44)
6.  [Resources](#org5dfa0f6)



<a id="org73b2d27"></a>

# Presenter

[Scott Bailey](https://www.lib.ncsu.edu/staff/csbaile3)   
Digital Research and Scholarship Librarian   
Copyright and Digital Scholarship Center   
[NC State University Libraries](https://www.lib.ncsu.edu)


<a id="orgf336508"></a>

# Exploratory text analysis and visualization in the research context

Key take-aways:

1.  Text corpora exist with a wide range of metadata, cleanliness, and quality.
2.  Even when we have a good sense of method or approach, exploring our data, whether quantitative or qualitative, helps us refine research questions, fine-tune methods, and scope our project to be successful.
3.  Voyant and Taguette are free and open source tools that allow you analyze and visualize texts, whether as single documents or whole corpora.


<a id="org03c70d0"></a>

# Voyant - Demo


<a id="org2242939"></a>

## Installing Voyant vs using the hosted web version

There is a hosted version of Voyant at [https://voyant-tools.org/](https://voyant-tools.org/) that has two text corpora available. This is a great way to experiment with and learn Voyant, and can be used for your own corpora.

You can also download and host Voyant yourself, and I recommend this for working with larger corpora and in order to work offline. Since you can adjust the memory available to Voyant, there is an advantage in speed and the size of corpus you can analyze.

Download and install page: <https://digihum.mcgill.ca/voyant/resources/run-your-own/voyant-server/>


<a id="org20dcde1"></a>

## File types and corpus building

Voyant can handle single documents, either by uploading them or simply copying text into the Voyant home screen input box. It provides even more power, though, when you upload many documents as a corpus.

Supported file types:

-   plain text: .txt
-   HTML: .htm, .html
-   XML: .xml
-   Word: .doc, .docx
-   RTF: .rtf
-   PDF: .pdf


<a id="orgd9381dc"></a>

## Exploring the interface

-   Basic layout
-   Getting help for each tool
-   Settings for each tool
-   Clicking on a document or word in one tool typically causes the other tools to update accordingly


<a id="org142c1bd"></a>

## Tools of note

-   **Summary**: basic statistics on your document or your corpus, including most frequent terms and most distinctive terms per document (tf-idf)
-   **Contexts**: keyword-in-context tool
-   **Correlations**: Pearson&rsquo;s correlation for pairs of terms in the document/corpus, and significance for the correlation
-   **Trends**: trends over documents or document chunks for terms according to relative frequency or raw count
-   **Topics** (Hidden by default): topic modeling by way of the latent dirichlet allocation (LDA) algorithm
-   There are many tools - explore them all!


<a id="org848f38d"></a>

## Exporting results

What formats you can use for export depends on each tools, but in general:

-   Exporting visualizations: PNG, HTML, SVG
-   Exporting data: HTML, TSV, JSON


<a id="org0916516"></a>

# Taguette - Demo


<a id="org636ab12"></a>

## Installing Taguette vs using the hosted web version

Taguette also has a hosted version at [https://app.taguette.org/](https://app.taguette.org/). You can use the hosted for full projects, including collaborating with others on your qualitative analysis project.

You can also download and run Taguette on your own computer, or run your own server. On your own computer, you won&rsquo;t be able to use the collaboration feature, but can still carry out your analysis and export results.

Download and install page: <https://www.taguette.org/install.html>


<a id="org7c6fc22"></a>

## File types

Supported file types:

-   plain text: .txt
-   HTML: .htm, .html
-   Word: .doc, .docx
-   RTF: .rtf
-   PDF: .pdf
-   Open Documents: .odt
-   E-books: .epub, .mobi


<a id="org84ac7dc"></a>

## Basic workflow

-   Creating a project
-   Adding documents
-   Highlighting text and adding tags
    -   Creating hierarchical tags (parent and child codes)


<a id="orgccc1ada"></a>

## Exporting results

-   Exporting collated tagged texts: PDF, HTML, DOCX, XSLX, CSV
-   Exporting your codebook: PDF, HTML, DOCX, XSLX, CSV, XML


<a id="orga702e44"></a>

# Putting it together: between distant and close reading

Key take-aways:

1.  Distant reading allows us to analyze and draw conclusions from collections of texts at large scale.
2.  Close reading helps us develop a nuanced understanding of texts.
3.  Research is iterative, and moving between distant and close reading allows us to develop interpretations and conclusions that draw on the whole of a corpus without losing the nuance.


<a id="org5dfa0f6"></a>

# Resources

-   Voyant Docs: <https://digihum.mcgill.ca/voyant/>
-   Voyant Tools Docs: <http://docs.voyant-tools.org/tools/>
-   UC Santa Cruz Getting Started with Voyant: <https://guides.library.ucsc.edu/DSCguides/Voyant>
-   Taguette Getting Started Guide: <https://www.taguette.org/getting-started.html>
-   Illinois Library Coding with Taguette Guide: <https://guides.library.illinois.edu/qualitative/taguette>

