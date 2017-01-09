#Tensorflow Seq2Seq Chatbot
Overview
============
In this demo code, we implement Tensorflows [Sequence to Sequence](https://www.tensorflow.org/versions/r0.12/tutorials/seq2seq/index.html) model to train a
chatbot on the [Cornell Movie Dialogue dataset](https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html).The dataset has been in the project. After training for a few hours, the bot is able to hold a fun conversation.

Example QA
===========
>> where are you?
I ' m here .

>>how is going?
Fine .

>> Can you think of it?
I don ' t think so .

>> who is your father
I ' m not sure .

>> what is time now?
I don ' t know .

>> what the hell
What ?

>> What are you doing now?
I ' m going to get out .

Dependencies
============
* pytho3.52
* numpy
* scipy 
* six
* tensorflow12 (https://www.tensorflow.org/versions/r0.12/get_started/os_setup.html)

Use [pip](https://pypi.python.org/pypi/pip) to install any missing dependencies


Usage
===========
Firstly, create an empty directory named woking_dir in the project.
To train the bot, edit the `seq2seq.ini` file so that mode is set to train like so

`mode = train`

then run the code like so

``python execute.py``

To test the bot during or after training, edit the `seq2seq.ini` file so that mode is set to test like so

`mode = test`

then run the code like so

``python execute.py``


###Due date: December 8th

Also see this issue, some people have found this discussion helpful
https://github.com/llSourcell/tensorflow_chatbot/issues/3

Credits
===========
Credit for the vast majority of code here goes to [suriyadeepan](https://github.com/suriyadeepan). I've merely created a wrapper to get people started. 
