Supplementary material for the paper: 
“Implementing a Reverse Dictionary, based on word definitions, using a Node-Graph Architecture” 
by Sushrut Thorat and Varad Choudhari

The folder “demo_jupyter” contains a Jupyter notebook with python code to implement the reverse dictionary. It uses the WordNet 3k BLM, which can be found under the subfolder “data”. The variable ‘input_phrase’ accepts the input phrase, which is processed as explained in the paper. The output words will be outputted at the end of the notebook.
*Run the header section, and load the BLM only once (this takes longest). After that just edit the input_phrase, and run all sections below it. That way, you’ll get outputs real quick.*

The folder “test_data” contains the 179 user-generated phrases and the corresponding target words that are used to evaluate the performance in the paper.

The sub-folder “demo_jupyter/data” also contains a .csv file ‘3k_wordlist’ which contains the 3k lexicon (made of 3107 words). To make a fair comparison with our approach, truncate the outputs of any reverse dictionary to the 3k lexicon.

