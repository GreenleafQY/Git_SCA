# What's SCA?
  
  SCA is the abbreviation of Sentence Component Analyze.
  
  This project's purpose is to try using a pure language way to solve the language problems. Not like the current NLP applications which use the mathematical algorithms to handle language issues, this projcet sticks to the old language analyzing method. 
  
  The disdavantages have been repeated everywhere. The most important advantage laying in two aspects, one is that this is closer to human language and the second we can handle language without redundant training data.
  
  The basic belief is that the most frequently used gramma is limited and a set of effcient applications can solve most language needs after a hard, time-consuming but once-for-all compiling.

# Version

- This SCA 0.0.1 only includes one-sentence component analyzing. And unfortunately the marked database is limited to only 20 thousand Chinese words due to my limited devotion. So it might function worse if the sentences happened include words it does not recognize. Anyway, if this is the only reason for the ill-function, it is a great success. Anyway, the current version has tried the best to include the most common used Chinese words, and words mostly used for news.

- The ongoing functions include sentence-component-analyzing by paragraph, relationship and distance of words, summary, emotions, reasoning, writing, etc.

- The continues version might be updated to a bigger word-pool of about 300 thousand words, hopefully.

# System

- Windows 10

# Python Version

- Python 3.6

# Necessary libs:

- jieba 0.42.1
- pyhanlp 0.1.64
- pypinyin 0.37.0
- pandas 1.1.5

# How to use

- Simply put a single Chinese sentence into the "sentence.txt" file, and then run SCA.py.

# How to read the result
  - The content in "()" is a decorating component to the next part connected with a "*".
  
  - The main structure of the sentence consisted of subject, verb, and object, with "+" as the connected symbol.
  
  - A complete list of the abbreviation of components:
    - "s" for subject
    - "p" for predicate
    - "o" for object
    - "s_2" for second-subject in a a double-subject sentence
    - "p_2" for second-predicate in a a double-predicate sentence
    - "o_2" for second-object in a a double-object sentence
    - "mv" for modal verbs
    - "v_j" for a verb with the function of passivation or activation.
    - "s_sc" for subject in a sentence with a subject clause
    - "p_sc" for predicate in a sentence with a subject clause
    - "o_sc" for object in a sentence with a subject clause
    - "s_in_sc" for the subject in the subject clause in a sentence with a subject clause
    - "p_in_sc" for the predicate in the subject clause in a sentence with a subject clause
    - "o_in_sc" for the object in the subject clause in a sentence with a subject clause
    - "s_oc" for subject in a sentence with an object clause
    - "p_oc" for predicate in a sentence with an object clause
    - "o_oc" for object in a sentence with an object clause
    - "s_in_oc" for the subject in the object clause in a sentence with an object clause
    - "p_in_oc" for the predicate in the object clause in a sentence with an object clause
    - "o_in_oc" for the object in the object clause in a sentence with an object clause
    - "re" means represent, take the place of someone or something.
    - (speaker) means the part before it is the announcer of the following sentence.
    
# The marks and numbers

- Simply ignore them unless you want to contribute to this project.

# License and Use

Greenleaf © 2021 

Use it anyway, if you feel fun.


    

  


