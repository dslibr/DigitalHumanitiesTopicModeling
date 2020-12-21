---
layout: page
title:  "Items & Topics Data"
---


From the probabilistic topic modeling algorithm, Latent Dirichlet Allocation, dominant topics were assigned to each item in the digital items list based on the probabilities of the words located in the title and abstract. That is, if the sum of the probabilities of the words associated with one topic was greater than the sum of the probabilities of the words associated with another topic, the topic with the highest sum of probabilities became the dominant topic for the given item. 

The <i>Distribution of Items by Topics</i> bar chart below illustrates the distribution of items per topic and the proportion of documents with abstracts per topic. The light blue bar shows the total number of items for the given topic. The dark blue bar shows the number of documents with abstracts for the given topic.</p>

<img src="https://lisaover.github.io/DigitalHumanitiesTopicModeling/Graphs/topics.png" alt="Distribution of Items by Topic Bar Chart" />

The file with items assigned to a dominant topic was output to a CSV file named <i>items_dominant_topics.csv</i>.

The total number of items assigned to each topic as well as the proportion of items within each topic were written to the file <i>items_topics_summ.csv</i>. 
This file also contains the top-10 keywords, topic names, and short topic names (used for graph titles).

All topic numbers referenced in other sections of this site correspond to the 'Dominant_Topic_Vis' and 'Topic_Num_Vis' fields of the <i>items_dominant_topics.csv</i> and 
<i>items_topics_summ.csv</i> files, respectively.

The table below lists the data files for the project and includes a data dictionary for each file to explain the fields.<br/><br/>

| Data File                                  | Description                                                                                         |
|:-------------------------------------------|:----------------------------------------------------------------------------------------------------|
| <a href="https://media.githubusercontent.com/media/lisaover/DigitalHumanitiesTopicModeling/Output%20Data/items\_dominant\_topics.csv" target="\_blank">Items\_dominant\_topics.csv</a>                | Lists the digital humanities items with fields that identify the dominant topic for each item       |
|  |  |
| <a href="https://media.githubusercontent.com/media/lisaover/DigitalHumanitiesTopicModeling/Output%20Data/items\_dominant\_topics\_data_dict.csv" target="\_blank">Items\_dominant\_topics\_data\_dict.csv</a>    | Data dictionary for items\_dominant\_topics.csv                                                     |
|  |  |
| <a href="https://media.githubusercontent.com/media/lisaover/DigitalHumanitiesTopicModeling/Output%20Data/items\_topics\_summ.csv" target="\_blank">Items\_topics\_summ.csv</a>                    | Lists the topic numbers from both Mallet and Gensim models, keywords, and topic name for each topic |
|  |  |
| <a href="https://media.githubusercontent.com/media/lisaover/DigitalHumanitiesTopicModeling/Output%20Data/items\_topics\_summ\_data_dict.csv" target="\_blank">Items\_topics\_summ\_data\_dict.csv</a>        | Data dictionary for items\_topics\_summ.csv                                                         |
