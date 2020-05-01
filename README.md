# Machine-Hack-Hackathons
Message_Polarity_Prediction_Hackathon: 

All of us receive a ton of messages and emails on a daily basis. Collectively, that is a lot of data which can provide useful insights about the messages that each of us gets. What if you could know whether a certain message has brought you good news or bad news before opening the actual message. In this challenge, we will use Machine Learning to achieve this.

Given are 53 distinguishing factors that can help in understanding the polarity(Good or Bad) of a message,  your objective as a data scientist is to build a Machine Learning model that can predict whether a text message has brought you good news or bad news.

You are provided with the normalized frequencies of 50 words/emojis (Freq_Of_Word_1 to Freq_Of_Word_50) along with 3 engineered features listed below:

TotalEmojiCharacters: Total number of individual emoji characters normalized. (eg. 🙂 )
LengthOFFirstParagraph: The total length of the first paragraph in words normalized
StylizedLetters: Total number of letters or characters with a styling element normalized
Target Variable: IsGoodNews

The data is now available for download on. Proceed to Start/Continue Hackathon and click on the attachments to download the datasets.
Data Description
The unzipped folder will have the following files.

Train.csv – 947 observations.
Test.csv – 527 observations.
Sample Submission – Sample format for the submission.
Below are the file formats for the provided data
Train.csv


Test.csv


Sample_Submission.xlsx


Result:
The model I made using Decision Trees gave me an accuracy of round about 83% and the metric used was F1 score.

The second model that I submitted was the result produced by Voting Classifier which gave me 85% accuracy.


