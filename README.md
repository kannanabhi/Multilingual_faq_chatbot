# Multilingual_faq_chatbot
Multilingual chatbot for answering faq of monuments

## Objective of project
Project creates an interactive chatbot using the RASA framework for answering all faq's related a particular monument (saraswathy temple of bits pilani campus)


## Steps to run the code
we have two code .ipynb files
**refer to project 1 in endsem_report.pdf for further details**
### Saraswathy_mandir_chatbot.ipynb
+ corresponds to the basic implementation of our chatbot (works only in english language)
+ run the code block in the exact order and restartd the instance whenever asked in the comments.
+ the code for interacting with the chatbot is given the end of the file with comments.
+ note that the domain.yml file, nlu.md file and stories.md file can be edited according to the users needs inorder to customize the chatbot
  
### myMandir.ipynb
+ slightly updated version of the above mentioned model
+ has google translate api implemented, thus the model can acept any language input and automatically responds in that language itself
+ run all the code in given order only
+ the code to interact with the chatbot is given with example interaction
+ ensure to run import code for google translate before runniung this code though
  
### Special features of project
+ high accuracy due to RASA framework
+ apt for small scale projects since re-phrasing of questions are taken care properly
+ more details given in report and presentation

### Scope of improvement of project
+ currently the  data to be entereed manualy into the 3 files, it should be automated for scalability of the project
+ context, question, answer format of data cannot be used ideally for this project
