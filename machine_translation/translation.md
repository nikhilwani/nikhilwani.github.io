---

layout: default
permalink: /translation/

---





# <center> Machine Translation using LLMs </center>



<script
	type="module"
	src="https://gradio.s3-us-west-2.amazonaws.com/3.44.1/gradio.js"
></script>

<gradio-app src="https://nikhilwani-nikhilwani-machine-translation-en-fr-6b3a170.hf.space"></gradio-app>


The ```T5``` tokenizer used for this model requires prompting for NLP tasks.  
**Format:** Translate ```<lang1>``` to ```<lang2>```: Source ```<lang1>``` sentence. 

<!-- 
<center> <b> Sample input</b></center>
<p></p>

<p style=" background:#eff0f1;padding: 1%;text-align: justify;">

<p><strong>Sample input:</strong></p>

<p><strong>Prompt for English to French Translation:</strong><br>
- Translate English to French: How fortunate are we to be alive in the age of Generative AI!</p>

<p><strong>Prompt for French to English Translation:</strong><br>
- Translate French to English: quel moment nous sommes heureux d'être vivants à l'</p>
  
</p> -->


**Sample input:**

**Prompt for English to French Translation:**  
- Translate English to French: How fortunate are we to be alive in the age of Generative AI!

**Prompt for French to English Translation:**  
- Translate French to English: quel moment nous sommes heureux d'être vivants à l'
  
---
---
<p></p>
<b>References:</b>  
[1] Raffel, Colin, et al. "[Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer](https://arxiv.org/abs/1910.10683){:target="_blank"}." arXiv preprint arXiv:1910.10683 (2019).

<p></p>

*Last updated: Oct 2023*