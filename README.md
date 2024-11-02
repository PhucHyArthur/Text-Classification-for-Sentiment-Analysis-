<h1>Text Classification with Mamba - Project</h1>

<h2>I. Introduction</h2>
<p>
    Recently, Mamba is a newly introduced architecture that has received strong support from the research community. Mamba has become a trend due to its superior capabilities compared to Transformer (the currently popular architecture). Its superiority is demonstrated in all three main criteria for evaluating a model: accuracy, speed, and computational cost.
</p>

<div align="center">
  <img src="./image/1.png" alt="Overview of System">
  <p><em>Figure 1: Overview of MAMBA Model</em></p>
</div>

<p>
    In this project, we will explore the basics of the Mamba architecture and apply Mamba to the text classification problem.
</p>

<h2>II. Implementation</h2>

<h3>1. Dataset IMDB</h3>
<p>
    The IMDB dataset consists of 50,000 movie reviews. It is used for classifying reviews as either negative or positive. The dataset is evenly split into two parts, with 25,000 samples for training and 25,000 samples for testing. Additionally, the dataset provides 50,000 unlabeled samples to support the training process. However, in this project, we will only use the labeled data to train the model.
</p>
<div align="center">
  <img src="./image/2.png" alt="Illustrative example of the IMDB dataset.">
  <p><em>Figure 2: Illustrative example of the IMDB dataset.</em></p>
</div>

<h3>2. Build Custom Mamba Model</h3>

<div align="center">
  <img src="./image/3.png" alt="Illustrative example of the SQuAD2.0 dataset.">
</div>

<p>You can see it in <code>[solution]_Text_Cls_with_Mamba_Project.ipynb</code></p>
