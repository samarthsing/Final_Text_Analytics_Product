# Final_Text_Analytics_Product
Leveraging Text Analytics Tools on Spatially Resolved Literature in the Intersections of Energy and Social Science – Characterizing the Role of Human Behavior on Decarbonization 

This project is inspired and is an implementation of this wonderful paper:
https://www.sciencedirect.com/science/article/pii/S2214629617301500#upi0005 It mentions the bias among US authors regarding Coal and petroleum,
where coal  is always treated as negative and sorrowful, and oil to be something 'new' and 'positive'.

This bias can vary from country to country and state to state. For this the authors performed sentiment analysis on 30 fiction and non-fiction
texts on both coal and oil written by the US authors. The results clearly state that coal is treated harshly by the people. So, the first step
of the product was to reimplement their algrithms and try to reproduce the results. Then we can perform the same idea on different parts of the 
country and different fossil fuels, and see how they vary.

Full texts to novels which the authors used are not available. First their prefaces available online were used to perform the analysis,but as the
texts were very small, exploratory text analytics results, were not very helpful.

So the data was finally changed and comparsions were made between coal and shale gas,using peer reviewed published papers in the journal
Energy Research and Social Science.
The links to the data are:

https://www.sciencedirect.com/search/advanced?pub=Energy%20Research%20%26%20Social%20Science&cid=305759&title=coal&show=50&sortBy=relevance

https://www.sciencedirect.com/search/advanced?pub=Energy%20Research%20%26%20Social%20Science&cid=305759&title=%22shale%20gas%22&show=25&sortBy=relevance

The articles were not taken arbitraly but only those which had the fuels in their titles and are from varying locations.

The results from them were not that great and insightful, but still provided hands-on with the Text Analytics Methods.

Files:
Mallet_results: Has the topic modelling results

Initial Data: data intially taken which was discarded

FInal Data: Final data whose link are also given above

DS5559_Combine_Lexicons.ipynb: Combines the lexicons to form lexicons.db.( No need to run if the database is already there).

Final Project Coal.ipynb and Final Project Shale Gas: main two notebooks performing sentiment analysis on all the documents

FInal_Coal_Individual.ipynb: Practice notebook which Performs analytics on one text file.

Mallet_corpus_convertor.ipynb: Helps to corpus in excelform to further send the files to Mallet.

textman.py: Utility File
