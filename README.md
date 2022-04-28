# Medication-Change-Events-Detection-
Shan and Sheng's n2c2 2022 track 1 sub 2 &amp; 3 task's attempts.

Track1 subTask 2 and 3 are two realted subtask:

subTask2:
You will be provided with clinical notes and ann files containing NER annotations (i.e. medications). You can submit solutions for Event or Event+Context tasks.

subTask3: 
You will be provided with clinical notes and ann files containing NER & Event annotations. You can submit solutions for the Context task.

Our experiements consist four major part:

1. Fine tuning on pre-train language models (classification task built 6 different classififers for five different event elements and detect disposition)
2. Prompt tuning on T5 (classification task built 6 different classififers for five different event elements and detect disposition)
3. Fine tuning on pre-train language model (clinical-Bert) as treat the question as multi label classification task for subtask3.
4. Use data balancing technique to improve our best system (Fine tuning on clinical BERT)
