# Being an Ethical Data Scientist

### Data Collection

An ethical data scientist understands the following about data collection:

1. The accuracy of collected data impacts subjects' lives.
2. Biases can misinform collection processes. 
3. Collection can be intrusive and "always costs someone something." (http://conflict.lshtm.ac.uk/page_13.htm#Ethical_Introduction)

In many ways, these values emobdy a common theme of understanding the impact of data collection on others.  A central component to ethically source data is to understand that collecting data produces not only the data itself, but impacts the subject(s) of data collection.  

This can be thought of as the notion that "data collection always costs someone something." In particular, data is used to drive conclusions and analysis, so an ethical data scientist must start with understanding the potential impact of faulty data collection.  

Simmons, et al. explain this possibility through highlighting the choices researchers must make during data collection: "Should more data be collected? Should some observations be excluded? Which conditions should be combined and which ones compared?
Which control variables should be considered? Should specific measures be combined or transformed or both?"  According to their article, it is infeasible for researchers to answer these questions in the best way possible. Ultimately, according to the authors, this likely (and necessarily) leads to false-positive findings well over the stated 5% threshold.  

If poor decisions made about data collection produces conclusions that incorrectly model reality, then the associated benefits of scientific progress are lost, or can actually hurt the lives of associated stakeholders.  Take, for instance, a demographic analysis used to inform the distribution of funds for certain social programs (gross oversimplification of the issue, but useful for this example).  Say the researchers did not follow best practices for collecting the associated data,  (like asking their 5 best friends) and then concluded that the social programs were not beneficial to a community. That conclusion could be used to justify the axing of said programs.  However, those programs may very well have been beneficial and have a direct impact on people's lives.  Had the researchers collected the data ethically and accurately, then they would have concluded the same.

An entical data scientist will strive for accurate collection, broad casting of a "collection" net, and for reasoning about what is the most relevant for a particular study.  

### Data Wrangling

According to Furche, et al., data wrangling is an expensive process.  For this reason, compromises must be made which take into priority the data's context, the purpose of the data, and the "user context."  Highlighting this idea of compromises is key for being an ethical data scientist.  If a researcher attempts too much, they may end up neglecting certain critical areas.  If a researcher makes the wrong choices in aggregating the data in a meaningful way, then this can potentially obfuscate the insights gained from the data.  

This last piece is key in both the aformentioned article and in being an ethical data scientist.  When wrangling data, the researcher must take into consideration the users of that wrangled data and make informed compromises from it.  From a utilitarian perspective posited by the article, this means that end users will have an easier time to use the data and it will be more economical for the researcher.  From an ethical perspective, making concious decisions about how to best present data will result in a dataset which is more likely to (1) provide useful insights and (2) be used in the conclusions made about poeple's lives (and the subsequent impact on them) as discussed in the previous section.  

An ethical data scientist will understand that compromises are necessary in data wrangling, but will ensure those compromises are ultimately in the best interest in the "users" of the dataset.


### Data Analysis

Much like in life, one of the best (and ethical) things you can do in data science is to not assume you are absolutely correct.  More generally, it is critical for data scientists to have an understanding of their place in the world and understand that--they too, are subject to human flaws.  Boyd and Crawford summarize this topic extremely well: 
"Interpretation is at the center of data analysis. Regardless of the size of a data set, it is subject to limitation and bias. Without those biases and limitations being understood and outlined, misinterpretation is the result. Big Data is at its most effective when researchers take account of the complex methodological processes that underlie the analysis of social data."

Without taking these factors into account prior to analyzing datasets (and also, without fully exposing them and discussing alongside the analysis), data scientists run the risk of producing conclusions which are taken as fact, when in fact they are merely a reflection of a researchers biases.  This is a disservice to the scientific method, which is intended to move the meter closer to a better, more informed understanding of the world. 

A final and key piece that an ethical data scientist incorporates into the analysis process is to follow the principle of "picking the right tools for the job."  Many different types of analyses (something like a t-test compared to a logistic regression) often will produce different results re: the null hypothesis.  If the data scientist picks an inadequate statistical method, it follows that they are not conducting data science ethically.  The role of a researcher is to present the best possible understanding of a dataset--making choices which contradict this responsibility results in an ethically questionable data scientist.

An ethical data scientist will strive to distance themselves from attatchments to hypotheses, analyses, and techniques and will instead prioritize answering a question in the most informed way.  

### Data Visualization

Much like in other aspects, being an ethical data scientist in the realm of data visualization means that clarity is of the upmost important.  Visualizations should be considered a vehicle by which to communicate the findings of a particular study, and (like in data analysis) should not be used to further an ideological objective predetermined by the researcher.  Related to this theme of clarity is the idea that visualizations should not be used to deceive through the manipulation of how to present a particular finding. According to Kirk, "Visualization ethics relates to the potential deception that can be created intentionally or otherwise, from an ineffective and inappropriate representation of data."

Kirk goes on to highlight the key component for an ethical data visualization as being one which actually incorporates the data in a meaningful way.  They provide the example of a status bar meant to show that Wikipedia has reached 10% of its donation goal, but in fact the visualization of this number takes up around 24% of the total status bar. 

An ethical data scientist must value the actual conclusions and data of the study when creating visualizations instead of the decoration of those visualizations.  An ethical visualization actually embodies the study's findings and provides a means of understanding those findings.

### References

Simmons, Joseph, et al. “False-Positive Psychology: Undisclosed Flexibility in Data Collection and Analysis Allows Presenting Anything as Significant.” PsycEXTRA Dataset, vol. 22, no. 11, 17 Oct. 2011, doi:10.1037/e519702015-014.

Furche, Tim, et al. "Data Wrangling for Big Data: Challenges and Opportunities." EDBT. 2016. www.orsigiorgio.net/wp-content/papercite-data/pdf/fgl*16.pdf

Crawford, Kate. "Six provocations for big data." (2011). https://papers.ssrn.com/sol3/papers.cfm?abstract_id=1926431

Kirk, Andy. Data Visualization: a successful design process. Packt Publishing Ltd, 2012. 


