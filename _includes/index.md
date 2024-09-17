## Library Data Project: Digital Humanities Topic Modeling

This site outlines the results of a topic modeling analysis performed on a list of digital humanities items from the University Library at the University of Pittsburgh. For more information on the data, method, and evaluation of the model, please <a href="[https://lisaover.github.io/DigitalHumanitiesTopicModeling/final_paper_Library_Data_Project.pdf](https://github.com/dslibr/DigitalHumanitiesTopicModeling/blob/gh-pages/final_paper_Library_Data_Project.pdf)" target="_blank">read the report</a>.

### Introduction

The Humanities Data Librarian for the University Library at the University of Pittsburgh, Tyrica Terry Kapral, provided data for an analysis of the digital humanities items in the library.

This was an exploratory, unsupervised learning project. The high-level goal was to investigate which topics are present within the humanities digital collection, and how those topics vary over time. Specifically, Mrs. Terry Kapral was interested in answers to the following questions about the data:

* What are the latent topics across the digital items?
* What items are related by topic?
* How do topics change over time with respect to the time period covered by the items within each topic?
* Are there any problems with the data?

These questions were answered through data exploration, including word embeddings and t-SNE plots, and topic modeling, using the unsupervised learning algorithm, Latent Dirichlet Allocation (LDA). Data exploration revealed problems in the data, some of which were mitigated. The final LDA model revealed 19 latent topics from the titles and abstracts in the metadata for the 124,517 digitized humanities items that had a title.
