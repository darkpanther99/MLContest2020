# MLContest2020

This was my submission to the Artificial intelligence and Machine learning contest of 2020, of Budapest University of Technology and Economics, hosted by the Department of Measurement and Information Systems  

The task can be read <a href="https://github.com/darkpanther99/MLContest2020/blob/main/MIGT2020_versenyfeladat_nov19.pdf">here</a> in hungarian, but a short english summary:  
We are given textual paragraphs about Artificial intelligence, and we have to predict 3 output variables, using a deep learning network:  
chapter: Which chapter is it from the book, between 0 and 27.  
sectionfloat: In which section of the chapter is it, between 0 and 1, 0 meaning it is the start of the chapter, 1 meaning it is the end.  
isextra: The paragraph is inside the book or it is from an extra teaching material about AI.  

My <a href="https://github.com/darkpanther99/MLContest2020/blob/main/Contest_solution.ipynb">solution</a> was to use transfer learning to interpret the paragraph, and to put some fully connected layers on top of the pretrained model to make the predictions.  
We were only given 4 hours to complete the task, so given I had more time to make some hyperparameter optimization, I think I could have done better.  
Nevertheless, the results were great, I earned second place with this approach, as can be read <a href="https://vik.hk/2020/12/ktv-nyertes-hallgatok-a-2020-21-oszi-felevben/">here</a>, in hungarian.
