##  PML4DC @ <a target='_blank' href='https://iclr.cc/'> ICLR 2022</a>

{% if jekyll.environment  == "production" %}
        {% assign basepath = "/iclr2022" %}
        {%else%}
        {% assign basepath = "" %}
        {% endif %}

<!-- ## Practical ML for Developing Countries: learning under limited/low resource scenarios -->

### Practical Machine Learning for Developing Countries: learning under limited/low resource scenarios

<!--<div class="update">
        ICLR 2022 will be a fully virtual conference. While the details for remote presentation are being finalized, authors of accepted papers/posters are encouraged to view the <a href="https://iclr.cc/Conferences/2022/virtual"> ICLR virtual presentation guidelines here </a> .-->

       
The constant progress being made in artificial intelligence needs to extend across borders if we are to democratize AI in developing countries. Adapting the state-of-the-art (SOTA) methods to resource constrained environments such as developing countries, is challenging in practice. Recent breakthroughs in natural language processing (NLP), for instance, rely on increasingly complex and large models (e.g. most models based on transformers such as BERT, VilBERT, ALBERT, and GPT-2) that are pre-trained on large corpus of unlabeled data. In most developing countries, low/limited resources makes the adoption of these breakthroughs harder. Methods such as transfer learning will not fully solve the problem either due to bias in pre-training datasets that do not reflect real test cases in developing countries as well as the prohibitive cost of fine-tuning these large models. This in turn, hinders the democratization of AI. 


Practical Machine Learning for Developing Countries (PML4DC) workshop is a full-day event that has been running regularly for the past 2 years in row at ICLR (past events include <a href="https://pml4dc.github.io/iclr2020/" target="_blank">PML4DC 2020</a> and <a href="https://pml4dc.github.io/iclr2021/" target="_blank"> PML4DC 2021</a>). PML4DC aims to foster collaborations and build a cross-domain community by featuring invited talks, panel discussions, contributed presentations (oral and poster) and round-table mixers. 

 The main goal of PML4DC is to bring together researchers and practitioners (from academia, industry and government agencies) to reflect on aspects of designing, implementing, deploying and monitoring machine learning (ML) solutions that are typical in low resource environments across multiple sectors, such as healthcare, finance, agriculture, education and natural language processing. Specifically, we encourage contributons that highlight issues related to:
* Advances in algorithms and methods tailored for problems related with data-scarcity, imbalanced representations and limited computational resource
*  Industry practices to scale-up ML solutions in low resource settings while balancing performance and latency tradeoffs
* Societal and policy impacts of ML solutions in developing countries obtained via pilot studies, qualitative research, and human-in-the-loop settings.

## Keynote Speakers
<div>

 <div class="iblock headshotname"> Luciana Benotti </div>
 <p><a href="https://benotti.github.io/" class="headshotaffiliation" target="_blank">Universidad Nacional de Córdoba, Argentina</a></p>
 <div class="iblock headshotbox"> 
  <p><img src="{{basepath}}/images/speakers/luciana.jpg" class="headshot" alt="picture of Luciana"></p>
  <p align='justify'>
  Luciana is an Associate Professor at the Universidad Nacional de Córdoba in Argentina. She grew up in Patagonia, where she got her bachelor degree in Computer Science. Luciana lived in Europe while pursuing her graduate studies obtaining an Erasmus Mundus Masters joint degree by the universities of Bolzano and Madrid, and a PhD in Computer Science from the Université de Lorraine. Her research interests include dialogue systems, natural language grounded in vision, and the study of societal impacts of natural language processing (NLP). She currently serves as the chair of the executive board for the North American Association in Computational Linguistics (NAACL). At NAACL she is committed to lowering access barriers for minorities and to supporting policies towards the study of the societal impacts of NLP technologies.
  </p>
 </div>

 <br><br>

 <div class="iblock headshotname"> Hamed Haddadi </div>
  <p><a href="https://haddadi.github.io/about/" class="headshotaffiliation" target="_blank">Imperial College London & Brave Software, UK</a></p>
 
 <div class="iblock headshotbox"> 
  <p><img src="{{basepath}}/images/speakers/hamed.jpg" class="headshot" alt="picture of Hamed"></p>
  <p align ='justify'>
Hamed is a Reader in Human-Centred Systems and the Director of Postgraduate Studies at the Dyson School of Design Engineering at The Faculty of Engineering, Imperial College London. He serves as a Security Science Fellow of the Institute for Security Science and Technology, leads the Systems and Algorithms Laboratory, and is an Academic Fellow of the Data Science Institute. . In his industrial role, he is a Visiting Professor and the Chief Scientist at Brave Software where he works on developing privacy-preserving analytics protocols. He is interested in User-Centred Systems, IoT, Applied Machine Learning, and Data Security & Privacy. He enjoys designing and building systems that enable better use of our digital footprint, while respecting users' privacy.

He studied for BEng/MSc/PhD at University College London and the University of Cambridge. He was a postdoctoral researcher at Max Planck Institute for Software Systems in Germany, and a postdoctoral research fellow at Department of Pharmacology, University of Cambridge and The Royal Veterinary College, University of London, followed by few years as a Lecturer and consequently Senior Lecturer in Digital Media at Queen Mary University of London. He has spent time working and collaborating with Brave Software, Intel Research, Microsoft Research, AT&T Research, Telefonica, and Sony Europe. When not in the lab, he prefers to be on a ski slope or in a kayak.
  </p>

 </div>
  
<br><br>
    
 <div class="iblock headshotname"> Raesetje Sefala </div>
 <p><a href="https://sefalab.github.io/" class="headshotaffiliation" target="_blank"> DAIR, USA</a></p>
  <div class="iblock headshotbox"> 
 <p><img src="{{basepath}}/images/speakers/raesetje.jpg" class="headshot"  alt="picture of Raesetje"></p>
  <p align='justify'>
  Raesetje uses computer vision, data science, and machine learning techniques to explore research questions with a societal impact. Her current research uses satellite imagery to study the legacy of spatial apartheid in South Africa. She holds a masters degree in computer science from the University of the Witwatersrand and is the co-founder of Women In Computational Science Research (WiCSR), a community that empowers and encourages women’s growth and participation in the computational sciences. Raesetje’s work has been the recipient of the best poster presentation prize at the 2018 Deep Learning Indaba, and she is also the recipient of the data science for social good fellowship and the Sasol Inzalo Foundation scholarship.
  </p>
 </div>

<br><br>
 
<div class="iblock headshotname"> Kush R. Varshney </div>
   <p><a href="https://researcher.watson.ibm.com/researcher/view.php?person=us-krvarshn" class="headshotaffiliation" target="_blank"> IBM Research, NY USA</a></p>
  <div class="iblock headshotbox"> 
  <p><img src="{{basepath}}/images/speakers/kush.jpg" class="headshot" alt="picture of Kush"></p>
  <p align='justify'>
Kush R. Varshney was born in Syracuse, NY in 1982. He received the B.S. degree (magna cum laude) in electrical and computer engineering with honors from Cornell University, Ithaca, NY, in 2004. He received the S.M. degree in 2006 and the Ph.D. degree in 2010, both in electrical engineering and computer science from the Massachusetts Institute of Technology (MIT), Cambridge. While at MIT, he was a National Science Foundation Graduate Research Fellow.
Dr. Varshney is a distinguished research staff member and manager with IBM Research at the Thomas J. Watson Research Center, Yorktown Heights, NY, where he leads the machine learning group in the Foundations of Trustworthy AI department. He was a visiting scientist at IBM Research - Africa, Nairobi, Kenya in 2019. He is the founding co-director of the IBM Science for Social Good initiative. He applies data science and predictive analytics to human capital management, healthcare, olfaction, computational creativity, public affairs, international development, and algorithmic fairness, which has led to recognitions such as the 2013 Gerstner Award for Client Excellence for contributions to the WellPoint team and the Extraordinary IBM Research Technical Accomplishment for contributions to workforce innovation and enterprise transformation, and Harvard Belfer Center Tech Spotlight runner-up for AI Fairness 360. He conducts academic research on the theory and methods of trustworthy machine learning. His work has been recognized through best paper awards at the Fusion 2009, SOLI 2013, KDD 2014, and SDM 2015 conferences and the 2019 Computing Community Consortium / Schmidt Futures Computer Science for Social Good White Paper Competition.
He self-published a book entitled <a href="http://www.trustworthymachinelearning.com/" target='_blank'>'Trustworthy Machine Learning'</a> in 2021. He is a senior member of the IEEE.
  </p>
 </div>
 </div>

## Panelists

<div class="panelists">

<div>
  <div class="iblock headshotbox"> 
  <img src="{{basepath}}/images/speakers/kenza.jpg" class="headshot"  alt="picture of Kenza">
  </div>
  <div class="iblock headshotname">Amara Kenza</div>
  <p><a href="https://ai.ethz.ch/people/kenza-amara.html" class="headshotaffiliation" target="_blank">ETH Zurich</a></p>
</div>
<div>
  <div class="iblock headshotbox"> 
  <p><img src="{{basepath}}/images/speakers/xiaorong.jpg" class="headshot"  alt="picture of Xiarong"></p>
  </div>
  <div class="iblock headshotname">Prof. Xiaorong Ding </div>
  <p><a href="https://faculty.uestc.edu.cn/xiaorongding" class="headshotaffiliation" target="_blank">University of Electronic Science and Technology of China</a></p>
</div>

</div>

<div class="panelists">

<div>
  <div class="iblock headshotbox"> 
  <p><img src="{{basepath}}/images/speakers/jigar.jpg" class="headshot"  alt="picture of Jigar"></p>
  </div>
  <div class="iblock headshotname">Dr. Jigar Doshi</div>
  <p><a href="https://www.jigarkdoshi.com/" class="headshotaffiliation" target="_blank">Wadhwani AI</a></p>
</div>
<div>
   <div class="iblock headshotbox"> 
   <p><img src="{{basepath}}/images/speakers/reinhard.jpg" class="headshot"  alt="picture of Reinhard"></p>
   </div>
   <div class="iblock headshotname">Dr. Reinhard Scholl</div>
   <p><a href="https://www.itu.int/en/ITU-T/wtsa12/Pages/gss/session04/Reinhard-SCHOLL.aspx" class="headshotaffiliation" target="_blank">ITU-T Secretariat</a></p>
 </div>
<div>
  <div class="iblock headshotbox"> 
  <p><img src="{{basepath}}/images/speakers/sebastian.jpg" class="headshot"  alt="picture of Sebastian"></p>
  </div>
  <div class="iblock headshotname">Prof. Sebastian Schelter</div>
  <p><a href="https://ssc.io/" class="headshotaffiliation" target="_blank">University of Amsterdam</a></p>
</div>

</div>

