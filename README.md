![banner](https://github.com/lorainemnrc/big-data-researcher-opportunity/assets/23328647/7e3a3fd3-f03a-4149-a2df-2ec0f464cd15)

<h1 style="color: #1048CB"><b>Overview</b></h1>

In today's highly competitive and multidisciplinary [[5]](https://direct.mit.edu/qss/article/1/2/730/96146/How-common-are-explicit-research-questions-in) academic landscape, where time and resources are scarce, it becomes crucial to optimize research efforts and ensure the impactful dissemination of scholarly work. Surprisingly, studies have shown that a significant portion of journal articles, approximately 90% [[1]](https://blogs.lse.ac.uk/impactofsocialsciences/2014/04/23/academic-papers-citation-rates-remler/)[[2]](https://www.smithsonianmag.com/smart-news/half-academic-studies-are-never-read-more-three-people-180950222/), remain uncited [[3]](https://www.insidehighered.com/news/2018/04/19/study-examines-research-never-receives-citation), while around 50% go largely unnoticed by anyone beyond their authors and editors. This alarming trend highlights the need for a robust and efficient system to enhance the visibility and reach of research outputs.

By leveraging machine learning techniques and data analysis, we aim to develop a predictive model that can identify the factors influencing the citation [[4]](https://journals.sagepub.com/doi/10.1177/2158244019829575) and readership of scholarly articles. This model will help researchers and institutions prioritize their efforts by focusing on articles with a higher potential for citation and readership. By providing valuable insights into the determinants of article impact, we hope to empower researchers to make informed decisions about their publishing strategies, ultimately leading to increased visibility, recognition, and the wider dissemination of their work.

<h1 style="color: #1048CB"><b>Data Source</b></h1>

<span style="color:#003b7f; font-size:18px"><i>Original Data Source</i></span>

The original data source for the April 2023 Public Data File is [Crossref](https://www.crossref.org/).

Crossref is a non-profit organization that provides DOIs and comprehensive metadata for academic and scholarly content. They collaborate with publishers, institutions, and researchers to ensure the accurate and reliable dissemination of scholarly 

<span style="color:#003b7f; font-size:18px"><i>April 2023 Public Data File from Crossref</i></span>

The April 2023 Public Data File from Crossref is a comprehensive dataset that contains scholarly metadata from various publications. It includes bibliographic information such as titles, authors, publication dates, DOIs (Digital Object Identifiers), abstracts, and citation data. This dataset aims to provide researchers, developers, and stakeholders with standardized access to scholarly information for analysis and research purposes.

<span style="color:#003b7f; font-size:18px"><i>Download Details</i></span>

*The dataset can be downloaded from [Academic Torrents](https://academictorrents.com/details/d9e554f4f0c3047d9f49e448a7004f7aa1701b69).*

Academic Torrents is a platform dedicated to sharing and distributing large scientific datasets. It collaborates with researchers, institutions, and organizations to make academic data openly accessible, fostering data-driven research and promoting collaboration among scholars worldwide.

<span style="color:#003b7f; font-size:18px"><i>Crossref Unified Resource API</i></span>

There is also an available [Resource API](https://api.crossref.org) for the April 2023 Public Data File to allow for efficient retrieval and linking of scholarly metadata from a vast network of publications.

The API enables researchers to access and integrate the dataset seamlessly into their research workflows, facilitating data-driven analyses and investigations across a wide range of scholarly materials.

<span style="color:#003b7f; font-size:18px"><i>Dataset Summary</i></span>

- is a data file of the public elements from Crossref’s 143.5+ million metadata records.
- includes bibliographic information such as titles, authors, publication dates, DOIs, abstracts, and citation data.
- also includes details about the journal or publication venue, such as the journal name, ISSN (International Standard Serial Number), publisher, and volume/issue numbers.
- terms or phrases used to describe the main topics or subjects covered in the publication.
- information on whether the full text of the publication is freely accessible or requires a subscription or purchase.
- details about the funding sources that supported the research or publication.
- information about the licensing terms and usage rights associated with the publication.

<h1 style="color: #1048CB"><b>Highlights</b></h1>

<span style="color:#003b7f; font-size:17px"><i>Enablers of Opportunity</i></span>

This study highlights the importance of network and connections, and cross-disciplinary collaboration in unlocking opportunities for authors. While stable fields such as General Medicine and Biochemistry have shown consistently strong performance over the years, emerging fields like General Materials Sciences and Engineering also signals a notable shift in focus towards interdisciplinary areas with high potentials for advancements and innovation.

<span style="color:#003b7f; font-size:17px"><i>Data Quality</i></span>

Data quality is of utmost importance for the Crossref dataset, currently we can gain a lot of insights however we cannot confidently use some fields as the missing values are lot. High-quality data ensures the accuracy and reliability of the information contained within the dataset. It allows researchers, publishers, and stakeholders to confidently use the dataset for analysis, research, and decision-making. By maintaining data quality standards, the Crossref dataset can continue to be a valuable resource in the academic and publishing communities, facilitating the dissemination of knowledge and driving further advancements in research.

<span style="color:#003b7f; font-size:17px"><i>Predicting Opportunity – Feature Importance</i></span>

Due to limitations, we were unable to explore a wide range of models in our analysis. However, considering the size of our dataset, it would be worth considering the implementation of Neural Networks and studying their effectiveness further. It is important to note that running the analysis across all subject areas might introduce biases related to the organizations involved. To achieve improved citation results, it might be beneficial to develop separate models for each subject area, although this approach can be costly and may require focusing on specific, high-impact fields. It is important to acknowledge that adopting this approach may yield different results across all metrics compared to our previous methods.

<span style="color:#003b7f; font-size:17px"><i>ML Model and Performance</i></span>

While we were able to run the descriptive queries seamlessly, we encountered challenges when attempting to process the full dataset on our EMR. Even with 6-7 instances being utilized, the task failed to complete due to the complexity of the calculations involved. As a result, we may need to strategize and design a pipeline to handle this dataset efficiently or consider working with a sample of the data while providing appropriate statistical analysis.

<span style="color:#003b7f; font-size:17px"><i>AWS Cloud</i></span>

While we enjoyed the perks of running on AWS cloud very conveniently we experienced huge costing when we were working on different regions as the EMR downloaded files and, as we've learned in class, AWS charges these activities. There was also an instance when one of the studios rolled back all the files and we could not find the reason for it and needed to re-do the codes. Cloud services can be expensive if not properly managed, as costs can quickly accumulate based on factors such as storage, computational resources, and data transfer. Effective management, cost optimization strategies, and monitoring usage are essential to ensure that cloud expenses remain under control and align with the organization's budget and requirements.
