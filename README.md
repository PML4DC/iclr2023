##  PML4DC @ <a target='_blank' href='https://iclr.cc/'> ICLR 2023</a>

{% if jekyll.environment  == "production" %}
        {% assign basepath = "/iclr2023" %}
        {%else%}
        {% assign basepath = "" %}
        {% endif %}

<!-- ## Practical ML for Developing Countries: learning under limited/low resource scenarios -->

### Practical Machine Learning for Developing Countries: learning under limited/low resource scenarios

<!--<div class="update">
        ICLR 2022 will be a fully virtual conference. While the details for remote presentation are being finalized, authors of accepted papers/posters are encouraged to view the <a href="https://iclr.cc/Conferences/2022/virtual"> ICLR virtual presentation guidelines here </a> .-->

       
The constant progress being made in machine learning needs to extend across borders if we are to democratize ML in developing countries. Adapting state-of-the-art (SOTA) methods to resource constrained environments such as developing countries can be challenging in practice. Recent breakthroughs in natural language processing and generative image models, for instance, rely on increasingly complex and large models that are pre-trained on large unlabeled datasets. In most developing countries, resource constraints make the adoption of these breakthroughs challenges. Methods such as transfer learning will not fully solve the problem either due to bias in pre-training datasets that do not reflect environments in developing countries or the cost of fine-tuning larger models. This gap in resources between SOTA requirements and developing country capacities hinders a democratic development of machine learning methods and infrastructure. 


Practical Machine Learning for Developing Countries (PML4DC) workshop is a full-day event that has been running regularly for the past 3 years at ICLR (past events include <a href="https://pml4dc.github.io/iclr2020/" target="_blank">PML4DC 2020</a>, <a href="https://pml4dc.github.io/iclr2021/" target="_blank"> PML4DC 2021</a> and <a href="https://pml4dc.github.io/iclr2022/" target="_blank"> PML4DC 2022</a>). PML4DC aims to foster collaborations and build a cross-domain community by featuring invited talks, panel discussions, contributed presentations (oral and poster) and round-table mixers. 


The main goal of PML4DC is to bring together researchers and practitioners (from academia, industry and government agencies) to reflect on aspects of designing, implementing, deploying and monitoring machine learning (ML) solutions that are typical in low resource environments across multiple sectors, such as healthcare, finance, agriculture, or education. Specifically, we encourage contributons that highlight issues related to:
* Advances in algorithms and methods tailored for problems related with data-scarcity, imbalanced representations and limited computational resource
*  Industry practices to scale-up ML solutions in low resource settings while balancing performance and latency tradeoffs
* Societal and policy impacts of ML solutions in developing countries obtained via pilot studies, qualitative research, and human-in-the-loop settings.


## Keynote Speakers
<div>

 <div class="iblock headshotname"> Kathleen Simunyu </div>
 <p><a href="https://twitter.com/siminyu_kat" class="headshotaffiliation" target="_blank">Mozilla</a></p>
 <div class="iblock headshotbox"> 
  <p><img src="{{basepath}}/images/speakers/kat.jpg" class="headshot" alt="picture of Kat"></p>
  <p align='justify'>
  Kathleen Siminyu is an AI Researcher focused on Natural Language Processing for African Languages. She works at Mozilla Foundation as a Machine Learning Fellow to support the development of Kiswahili Speech Recognition. Kathleen is also currently part of a committee constituted by the African Union to develop an Artificial Intelligence continental strategy for Africa.  Before joining Mozilla, Kathleen was Regional Coordinator of AI4D Africa, where she worked with ML and AI communities in Africa to run various programs. One of these, a fellowship for African language dataset creation, led to the creation of over 15 African language datasets. For this work, Kathleen was listed as one of the <a href="https://www.technologyreview.com/innovator/kathleen-siminyu/" > MIT Technology Review 35 Innovators under 35 for 2022</a>. She continues to organise communities as part of the<a href="http://deeplearningindaba.com/" > Deep Learning Indaba</a> and the <a href="https://www.masakhane.io/" >Masakhane Research Foundation</a> .-->

  </p>
 </div>

 <br><br>

  <div class="iblock headshotname"> James Zou </div>
 <p><a href="https://www.james-zou.com/" class="headshotaffiliation" target="_blank">Stanford University</a></p>
 <div class="iblock headshotbox"> 
  <p><img src="{{basepath}}/images/speakers/james.jpeg" class="headshot" alt="picture of James"></p>
  <p align='justify'>
  James is Assistant Professor of Biomedical Data Science and, by courtesy, of Computer Science and Electrical Engineering at Stanford University. He works on making machine learning more reliable, human-compatible and statistically rigorous, and he especially interested in applications in human disease and health. Several of our algorithms are widely used in tech and biotech industries. He received a Ph.D from Harvard in 2014, and was a member of Microsoft Research, a Gates Scholar at Cambridge and a Simons fellow at UC Berkeley. He joined Stanford in 2016 and am excited to be a two-time Chan-Zuckerberg Investigator and the faculty director of the university-wide Stanford Data4Health hub. He also a member of the Stanford AI Lab. His research is supported by the Sloan Fellowship, the NSF CAREER Award, and Google, Amazon and Adobe AI awards. 
  </p>
 </div>

 <br><br>
 <div class="iblock headshotname"> Adji Bousso Dieng </div>
  <p><a href="https://vertaix.princeton.edu/people/" class="headshotaffiliation" target="_blank">Princeton University</a></p>
 <div class="iblock headshotbox"> 
  <p><img src="{{basepath}}/images/speakers/adji.jpeg" class="headshot" alt="picture of Adji"></p>
  <p align ='justify'>
  Adji is assistant Professor of Computer Science at Princeton University where she lead Vertaix on research at the intersection of artificial intelligence and the natural sciences. She is affiliated with the High Meadows Environmental Institute (HMEI). She is also a Research Scientist at Google AI and the founder and President of the nonprofit The Africa I Know. She has been named an AI2050 Early Career Fellow by Schmidt Futures and the Annie T. Randall Innovator of 2022 for her research and advocacy by the American Statistical Association. She received her PhD from Columbia University where she was advised by David Blei and John Paisley. Her doctoral work received many recognitions, including a Google PhD Fellowship in Machine Learning, a rising star in Machine Learning nomination by the University of Maryland, and a Savage Award from the International Society for Bayesian Analysis, for her doctoral thesis. she hail from Kaolack, Senegal.
  </p>
 </div>
  
  <br><br>

 <div class="iblock headshotname"> Joshua Blumenstock </div>
  <p><a href="https://www.jblumenstock.com/" class="headshotaffiliation" target="_blank">University of California, Berkeley</a></p>
 <div class="iblock headshotbox"> 
  <p><img src="{{basepath}}/images/speakers/jos.jpg" class="headshot" alt="picture of Joshua"></p>
  <p align ='justify'>
   Joshua Blumenstock is a Chancellor’s Associate Professor at the U.C. Berkeley School of Information and the Goldman School of Public Policy. He is the Co-director of the Global Policy Lab and the Center for Effective Global Action. Blumenstock does research at the intersection of machine learning and empirical economics, and focuses on applications of novel data to global poverty and inequality. He has a Ph.D. in Information Science and a M.A. in Economics from U.C. Berkeley, and Bachelor’s degrees in Computer Science and Physics from Wesleyan University. He is a recipient of awards including the NSF CAREER award, the Intel Faculty Early Career Honor, and the U.C. Berkeley Chancellor's Award for Public Service. His work has appeared in general interest journals including Science, Nature, and Proceedings of the National Academy of Sciences,as well as top economics journals (e.g., the American Economic Review) and computer science conferences (e.g., ICML, KDD, AAAI, WWW, CHI).
  </p>
 </div>
 
   <br><br>

 <div class="iblock headshotname">Rose Nakasi </div>
  <p><a href="https://www.jblumenstock.com/" class="headshotaffiliation" target="_blank">Researcher, AI LAB, Makerere University</a></p>
 <div class="iblock headshotbox"> 
  <p><img src="{{basepath}}/images/speakers/Nakasi.jpg" class="headshot" alt="picture of Joshua"></p>
  <p align ='justify'>
  Rose Nakasi is a PhD Researcher of Computer Science at AI and Data Science Lab, Makerere University in Uganda as well as Chair for Topic Group AI-based detection of Malaria (TG-Malaria) at the ITU-Focus Group AI for Health (FGAI4H). Her research interests are in Artificial Intelligence and Data Science and particularly in the use of these for developing improved automated tools and techniques for diagnosis and prediction of Malaria in low resourced but highly endemic Countries.
  </p>
 </div>
  </div>

 



## Panelists
<div class="panelists">
<div>
  <div class="iblock headshotbox"> 
  <img src="{{basepath}}/images/speakers/jade.jpeg" class="headshot"  alt="picture of Jade">
  </div>
  <div class="iblock headshotname">Jade Abbott</div>
  <p><a href="https://www.jabbott.io" class="headshotaffiliation" target="_blank">lelapa.ai</a></p>
</div>


<div>
  <div class="iblock headshotbox"> 
  <p><img src="{{basepath}}/images/speakers/teka.jpeg" class="headshot"  alt="picture of teka"></p>
  </div>
  <div class="iblock headshotname">Asmelash Teka Hadgu </div>
  <p><a href="https://twitter.com/asmelashteka" class="headshotaffiliation" target="_blank">Lesan</a></p>
</div>
        

</div>

<div class="panelists">

<div>
  <div class="iblock headshotbox"> 
  <img src="{{basepath}}/images/speakers/paul.jpeg" class="headshot"  alt="picture of paul">
  </div>
  <div class="iblock headshotname">Paul Azunre</div>
  <p><a href="https://www.azunre.com/" class="headshotaffiliation" target="_blank">Ghana NLP</a></p>
</div>
        
<div>
   <div class="iblock headshotbox"> 
   <p><img src="{{basepath}}/images/speakers/timit.jpeg" class="headshot"  alt="picture of Timnit"></p>
   </div>
   <div class="iblock headshotname">Timnit Gebru</div>
   <p><a href="https://www.dair-institute.org/about" class="headshotaffiliation" target="_blank">DAIR</a></p>
 </div>
</div>

