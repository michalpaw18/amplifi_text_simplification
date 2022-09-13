# project
Lexical and Synctatic Simplification in Transformer Based models. 

The following project can be cloned by: 


git clone https://github.com/michalpaw18/project/edit/main/README.md

To  install all the requirements:



To train MUSS:  

cd './project/muss'
pip install -e .


To train T5:

cd './project/ts_t5'
pip install  -e .

Then open the TS_T5.ipynb notebook and run all the cells. To train use the command:
python scripts/train.py


To Train BERT_GPT2:
cd './project/BERT_GPT2'
pip install -e . 

Note the training and testing is done inside the same script, 'run.py'. Simply, different functions must be called for different phases, 'train' and 'test'. First open the 'bert_gpt2_train.ipynb' notebook and run commands to train a model from scratch or the last checkpoint: 
python run.py train

To test the best model trained use:

python run.py test

