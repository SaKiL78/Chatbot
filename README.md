# Chatbot
Chatbot implementation in customer service industry through deep neural networks


We have implemented the Deep NLP model which is the Sec2Sec model with one of the best APIs to build a Deep learning application or AI which is Tensorflow.

Steps in which we implemented to create a chatbot in Python:

 


Getting Started: Anaconda
•	Install Anaconda
•	Install Virtual Environment using Anaconda Shell
•	Go to Start > Anaconda3 > Anaconda Prompt
•	To build a virtual environment, run the following line of code. The -n option is used to specify the virtual environment's name, and Python 3.5 is installed, so make sure you do the same to avoid any complications.
conda create -n chatbot python=3.5 anaconda
•	Activate Virtual Environment & Install Tensorflow
•	In Anaconda Navigator, go to Environments which you can find on the left side-bar
•	You'll find your virtual environment there, as well as the Anaconda root virtual environment, click on your environment > right-click > open with python terminal and execute the following code.
•	Activate   nameofyourvirtualenvironment. After activating the virtual environ-ment, install TensorFlow version 1.0.0 only, as later versions deprecate particular functions like tf.reset_default_graph.

pip install tensorflow == 1.0.0
5.2	Download the Corpus Dataset
We trained an open source Twitter corpus scrap dataset from twitter (700k lines), where odd lines are tweet and even lines are corresponding responded tweets. This dataset is intended to capture non-Star Trek conversations that a user would have with a chatbot. We used 50,000 post-response tweet combinations with an average of 16.18 words per utterance.
5.3	Getting Started: Spyder
•	Launch Spyder IDE through the Anaconda Navigator.
•	Navigate to your directory using the explorer window in the top right corner of Spyder IDE, along with additional choices like variable explorer, etc. Save the py-thon file to the same directory as the chatbot.
