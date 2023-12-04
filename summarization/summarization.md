---
layout: default
permalink: /summarization/
exclude: false
---


# <center>Text Summarization using LLMs </center>



<script
	type="module"
	src="https://gradio.s3-us-west-2.amazonaws.com/3.44.1/gradio.js"
></script>

<gradio-app src="https://nikhilwani-nikhilwani-machine-translation-en-fr-6b3a170.hf.space"></gradio-app>

<center> <b> Sample input</b></center>
<p></p>

<p style=" background:#eff0f1;padding: 1%;text-align: justify;">
Hunter Biden, the president’s son, was charged on Thursday by federal prosecutors with lying about his drug use when he purchased a handgun in 2018 and with illegally possessing the weapon, setting up the potential for a trial coinciding with his father’s re-election campaign.
</p>

<!-- **Sample input:** 
Hunter Biden, the president’s son, was charged on Thursday by federal prosecutors with lying about his drug use when he purchased a handgun in 2018 and with illegally possessing the weapon, setting up the potential for a trial coinciding with his father’s re-election campaign. -->


We use the ```T5``` tokenizer and fine-tune the model to generate summary. 

---
---
<p></p>
<b>References:</b>  
[1] Raffel, Colin, et al. "[Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer](https://arxiv.org/abs/1910.10683){:target="_blank"}." arXiv preprint arXiv:1910.10683 (2019).

<p></p>

*Last updated: Oct 2023*