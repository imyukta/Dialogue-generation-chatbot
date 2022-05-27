# Dialogue-generation-chatbot
**Dialogue Generation**

**Group: 22A11**

**Team members: -**

- Shubhanshi Srivastava (1816410272)
- Shubhi Tripathi (1816410274)
- Srishti Tiwari (1816410284)
- Yukta Vishwakarma (1816410314)

**Supervisor: -**

- Anurag Tewari (Assistant Professor)

**Files in the DVD**
 - RL
     - Data <br/> (Extracted data from movie corpus.) 
           - all_words.txt <br/> (Removed all the stopwords, unwanted words and punctuations.)
           - tokenized_all_words.txt <br/>(Tokenized all the words.)
           - utterance_dict (Dictionary of all the words according to their frequency.)
     - Python <br/>
           - RL <br/> (RL model creation)
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- rl_model.py<br/>
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- test.py <br/>
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- train.py <br/>
           - config.py <br/> 
           - data_parser.py <br/> (Parsed data)
           - data_reader.py <br/> (read data)
           - feature_extracted.py <br/> (extracted the features from the data)
           - model.py <br/> (created whole model for training)
           - simulate.py <br/> (simulate the conversation between the bot and the user)
           - test.py <br/>
           - train.py <br/>
     - Saved_model <br/> (saved models after training)
           - RL <br/>
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- checkpoint <br/> 
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- model-56-3000.index <br/>
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- model-56-3000.meta <br/>
           - reversed <br/>
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- checkpoint <br/>
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- model-63.index <br/>
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- model-63.meta <br/>
           - seq2seq <br/>
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- checkpoint <br/>
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- model-77.index <br/>
               &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- model-77.meta <br/>
           - word_vector.bin
- chat_gui (created the interface of chatbot)
     - __init__.py
- media  (Images used in interface)
     - robot.png
     - send.png
     - user.png
- spellcheck (checks the spellings of the output produced by the bot)
     - __init__.py
- __init__.py (used trained model to predict the output from the bot)
- mapper.py ( session handler)
- README.md

**Hardware Requirements: -**

- Hard disk – 1 TB
- RAM – 8 GB
- 64 bit processor
- 2.10 GHz clock speed

**Software Requirements: -**

- Colab Notebook.
- Google Chrome
- Windows 10
- Libraries :- NumPy , Pandas, NLTK, KERAS, Tensor flow.
