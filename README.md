
<h1>Persian Question Answering with T5</h1>

 ### [Google Colab Link](https://colab.research.google.com/drive/1Y3gSyxIA2tihNoMOORXX9M-lyuHlFa21?usp=sharing)

<h2>Description</h2>
In this project a Question Answering model for persian QA dataset is implemented. For this purpose we fine-tune T5 for Question Answering task using HuggingFace Transformers, pytorch Lightning &amp; Python. you can find the original paper of T5(Text to Text Transfer Transformer model) in <a href="https://arxiv.org/pdf/1910.10683.pdf">here</a>. The Persian QA dataset is also available in this<a href="https://github.com/sajjjadayobi/PersianQA"> link</a>.
<br />
For Tokanization <a href="https://huggingface.co/Ahmad/parsT5-base">Ahmad/parsT5-base</a>'s base model was utilized which is a monolingual T5 model for Persian language. 35 Gig deduplicated version of Persian data was used for pre-training the model. It's similar to the English T5 model but just for Persian.


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 
- <b>Pytorch Lightning</b>
- <b>Transformers</b>
- <b>Sklearn</b>
- <b>Pandas</b>
- <b>Numpy</b>



<p align="center">
<img src="https://i.imgur.com/7gyrJ2l.jpg" height="60%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>Loss Curves</h2>
You can see the Training Loss and validation loss during the training process, below. These plots are generated using TensorBoardLogger. You can read more about
it <a href="https://pytorch-lightning.readthedocs.io/en/stable/extensions/generated/pytorch_lightning.loggers.TensorBoardLogger.html">here</a>.
<h3>Training Loss</h3>

<p align="center">
<img src="https://i.imgur.com/bVAGCDM.png" height="400px"/>
<br />
<br />

<h3>Validation Loss</h3>
<p align="center">
<img src="https://i.imgur.com/Yngd4ca.png" height="400px"/>
<br />
<br />







<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
