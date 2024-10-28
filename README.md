**Topic Modeling**
To run topic modeling algorithms, first of all, the required libraries need to be installed. To do so first insure that Python3 is installed in your system along with pip. After moving to the directory 'topic-modeling', then, run the following commands:

>python3 -m venv venv

>env\Scripts\activate.bat [Windows] OR >source venv/bin/activate

>pip install > requirements.txt

After the required libraries are installed, the project is ready to run. Then, one can run any one of the models by using the command

>python topic_modeling_lda.py [To run the LDA model]

>python topic_modeling_nmf.py [To run the NMF model]

>python topic_modeling_lsa.py [To run the LSA model]

Test sentences have been embedded into the code itself, so if new text is to be tested, change the line 29 (variable 'text') with desired text to test against the model.
