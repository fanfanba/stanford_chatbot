# stanford-chatbot
stanford-chatbot tensorflow1.2

原始代码从https://github.com/chiphuyen/stanford-tensorflow-tutorials/tree/master/assignments/chatbot 获取，基于本机的环境上做了细微的改动，使得可以运行训练起来。

本机环境为tensorfow 1.2

训练的模型，经测试，效果有点差，希望有共同在学习的朋友一起研究改进

<<<<<<< A neural chatbot using sequence to sequence model with attentional decoder. This is a fully functional chatbot.

This is based on Google Translate Tensorflow model https://github.com/tensorflow/models/blob/master/tutorials/rnn/translate/

Sequence to sequence model by Cho et al.(2014)

Created by Chip Huyen as the starter code for assignment 3, class CS 20SI: "TensorFlow for Deep Learning Research" cs20si.stanford.edu

The detailed assignment handout and information on training time can be found at http://web.stanford.edu/class/cs20si/assignments/a3.pdf

以下是我训练出来的机器人的对话记录，不忍直视

HUMAN ++++ hi

BOT ++++ i ' ll be a little .

HUMAN ++++ what is your name

BOT ++++ i ' m a little little .

HUMAN ++++ how are you

BOT ++++ i ' m sorry .

HUMAN ++++ how are you

BOT ++++ i ' m sorry .

HUMAN ++++ what

BOT ++++ i ' ll be a little .

HUMAN ++++ say something

BOT ++++ i ' ll be a little .

HUMAN ++++ why

BOT ++++ i ' ll be a little .

HUMAN ++++ what 's your name

BOT ++++ i ' m a little little .

HUMAN ++++ what 's my name?

BOT ++++ i ' m a little little .

HUMAN ++++ god

BOT ++++ i ' ll be a little .

HUMAN ++++ ohhh

BOT ++++ i ' ll be a little .

HUMAN ++++ say something else?

BOT ++++ i ' m sorry .

HUMAN ++++ where are you from

BOT ++++ i ' m a little little .

HUMAN ++++ please

BOT ++++ i ' ll be a little .

HUMAN ++++ do you like california

BOT ++++ i ' m not .

HUMAN ++++ i like california a lot

BOT ++++ i ' m sorry .

HUMAN ++++ sorry for what?

BOT ++++ i ' m a little a little .

HUMAN ++++ i live here

BOT ++++ i ' ll be a little .

HUMAN ++++ do you have a gun?

BOT ++++ no .

Usage

Step 1: create a data folder in your project directory, download the Cornell Movie-Dialogs Corpus from https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html Unzip it

Step 2: python data.py 
This will do all the pre-processing for the Cornell dataset.

Step 3: python chatbot.py --mode [train/chat] 
If mode is train, then you train the chatbot. By default, the model will restore the previously trained weights (if there is any) and continue training up on that.

If you want to start training from scratch, please delete all the checkpoints in the checkpoints folder.

If the mode is chat, you'll go into the interaction mode with the bot.

By default, all the conversations you have with the chatbot will be written into the file output_convo.txt in the processed folder. If you run this chatbot
