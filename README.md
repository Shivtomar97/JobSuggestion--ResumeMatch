# JobSuggestion--ResumeMatch
Scan candidate resume and find similarity match with job requisitions by extracting and comparing keywords
JS.ipynb is the main file, it consists of code which reads a candidate resume and checks whether it is a pdf or a docx.

Extracts keywords from resume and matches it with the job description and skills in the csv file.

Provides you with the similarity match % with each and every job req for each resume!

I have used the Gensim library for this which makes comparing dictionaries easier.

The code counts each unique keywords and gives it a unique integer.

It counts the frquency of the word in all the requsitions and the resume.

The integer then becomes the key part of the dictionary and the frequency becomes the value part.

Running the JS.ipynb file will give you a result of top 5 matched jobs with your resume or the one I have uploaded.
It will provide you with a % match of keywords!

This code can be used for anything where you need a percentage match based on comparing keyowrds of one file to the other.

