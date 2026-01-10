---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

<style>
img{
  border-radius: 10px;
}
.col-md-3 {
  margin-top:10px;
  margin-bottom:10px;
  padding:0px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  background: white;
  border-radius: 20px;
  height: auto;
}
iframe {
  margin:0;
  padding:0;
  width: 175px;
  display: inline;
  vertical-align: middle;
}
</style>

### Featured

<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<h4>Watermarking Discrete Diffusion Language Models (2025)</h4>

<p><strong>Avi Bagchi</strong>, Akhil Bhimaraju, Moulik Choraria, Daniel Alabi, and Lav R. Varshney</p>

<p><img src="{{ site.baseurl }}/images/watermark.png" alt="Watermarking Discrete Diffusion Language Models" style="max-width: 50%; height: auto; margin: 20px 0; border-radius: 10px;"></p>

<p>Watermarking has emerged as a promising technique to track AI-generated content and differentiate it from authentic human creations. While prior work extensively studies watermarking for autoregressive large language models (LLMs) and image diffusion models, none address discrete diffusion language models, which are becoming popular due to their high inference throughput. We introduce the first watermarking method for discrete diffusion models by applying the distribution-preserving Gumbel-max trick at every diffusion step and seeding the randomness with the sequence index to enable reliable detection.</p>

<p><em>Under submission. Presentation to UIUC Information and Intelligence Group.</em></p>

<a href="https://arxiv.org/abs/2511.02083" target="_blank">[arXiv PDF]</a> | <a href="{{ site.baseurl }}/Watermarking_Presentation_10_30%20(2).pdf" target="_blank">[Slides]</a>
</div>
</div>

<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<h4>Doppler Invariant CNN for Signal Classification (2025)</h4>

<p><strong>Avi Bagchi</strong>, Dwight Hutchenson</p>

<p><img src="{{ site.baseurl }}/images/doppler.png" alt="Doppler Invariant CNN for Signal Classification" style="max-width: 50%; height: auto; margin: 20px 0; border-radius: 10px;"></p>

<p>Radio spectrum monitoring in contested environments motivates the need for reliable automatic signal classification technology. Prior work highlights deep learning as a promising approach, but existing models depend on brute-force Doppler augmentation to achieve real-world generalization, which undermines both training efficiency and interpretability. In this paper, we propose a convolutional neural network (CNN) architecture with complex-valued layers that exploits convolutional shift equivariance in the frequency domain. To establish provable frequency bin shift invariance, we use adaptive polyphase sampling (APS) as pooling layers followed by a global average pooling layer at the end of the network. Using a synthetic dataset of common interference signals, experimental results demonstrate that unlike a vanilla CNN, our model maintains consistent classification accuracy with and without random Doppler shifts despite being trained on no Doppler-shifted examples. Overall, our method establishes an invariance-driven framework for signal classification that offers provable robustness against real-world effects.</p>

<p><em>Under submission. Full report & slides internally distributed at MIT Lincoln Labs.</em></p>

<a href="https://arxiv.org/abs/2511.14640" target="_blank">[arXiv PDF]</a>
</div>
</div>

### In Progress

<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<h4>Polynomial Flow Matching</h4>

<p><img src="{{ site.baseurl }}/pfm_daigram.png" alt="Polynomial Flow Matching Diagram" style="max-width: 50%; height: auto; margin: 20px 0; border-radius: 10px;"></p>

<p>Preliminary work for ESE 5460 Final Project under Professor Pratik Chaudhari</p>
<p>Continuing with Sourya Basu, Lav R. Varshney, Daniel Alabi</p>

<a href="{{ site.baseurl }}/PFM.pdf" target="_blank">[PDF]</a>

</div>
</div>


<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<h4>Towards Efficient and Trustworthy Discrete Diffusion Models</h4>
<p><strong>Avi Bagchi</strong></p>

<p>Senior Thesis under Professors Weijie Su and Surbhi Goel</p>

</div>
</div>


<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<h4>Diffusion Factor Models</h4>

<p><strong>Avi Bagchi</strong>, Om Shastri, Michael Tesfaye</p>

<p>Extension of "Diffusion Factor Models: Generating High-Dimensional Returns with Factor Structure" (Chen et al. 2025)</p>

</div>
</div>


### Smaller Projects

<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<h4>On the PAC Learnability of Distortion-Free Language Model Watermarks</h4>

<p><strong>Avi Bagchi</strong>, Michael Tesfaye</p>
<p>CIS 6250 Final Project under Professor Michael Kearns</p>

<a href="{{ site.baseurl }}/CIS_6250___Final_Project%20(8).pdf" target="_blank">[PDF]</a>

</div>
</div>

<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<h4>Elliptic Curve Cryptography (2024)</h4>

<p><strong>Avi Bagchi</strong></p>

<p><img src="{{ site.baseurl }}/images/ecc.png" alt="Elliptic Curve Cryptography" style="max-width: 50%; height: auto; margin: 20px 0; border-radius: 10px;"></p>

<p>Directed Reading Program. Research on elliptic curve cryptography and its applications.</p>
<p><em>Presentation to Penn Department of Mathematics</em></p>
<a href="{{ site.baseurl }}/DRP_Presentation%20(4).pdf" target="_blank">[Slides]</a>

</div>
</div>

<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<h4>Auditing the Use of Language Models
to Guide Hiring Decisions (2024)</h4>
<p>Johann D. Gaebler, Sharad Goel, Aziz Huq, and Prasanna Tambe</p>

<p>I was acknowledged for my research assistance at The Wharton School (Operations, Information, and Decisions Department) under Professor Prasanna Tambe in this work.</p>



<a href="https://arxiv.org/pdf/2404.03086" target="_blank">[arXiv PDF]</a>
</div>
</div>

<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<h4>MOSQUITO EDGE: An Edge-Intelligent Real-Time Mosquito Threat Prediction Using an IoT-Enabled Hardware System (<em>Sensors</em> 2022)</h4>

<p>Shyam Polineni<sup>†</sup>, Om Shastri<sup>†</sup>, <strong>Avi Bagchi</strong><sup>†</sup>, Govind Gnanakumar<sup>†</sup>, Sujay Rasamsetti<sup>†</sup>, Prabha Sundaravadivel</p>

<p><sup>†</sup> Equal contribution</p>

<p><img src="{{ site.baseurl }}/images/mosquitoedge.png" alt="MOSQUITO EDGE System" style="max-width: 50%; height: auto; margin: 20px 0; border-radius: 10px;"></p>

<p>Species distribution models (SDMs) using climate variables effectively predict mosquito niches under current and future conditions. We use NOAA climate data matched to mosquito presence and absence points from NASA’s GLOBE Observer and the National Ecological Observatory Network to train an 86%-accurate Random Forest classifier that predicts mosquito threat. Temperature increases threat up to about 28 °C, producing high-threat clusters in warm, humid regions and low-threat clusters in cold, dry ones. We develop a low-cost IoT edge device that collects local climate data and automatically queries the model, enabling real-time predictions in remote or resource-limited settings and supplying new data for future SDM training.</p>

<p><em>Published in Sensors (2022). Cited 14.</em></p>

<a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC8780188/" target="_blank">[Paper]</a>
</div>
</div>

### Archival & Policy Research

<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<h4>The South Sea Bubble (<em>The Concord Review</em> 2021)</h4>

<p><strong>Avi Bagchi</strong></p>

<p><img src="{{ site.baseurl }}/images/southseabubble.png" alt="The South Sea Bubble by William Hogarth" style="max-width: 50%; height: auto; margin: 20px 0; border-radius: 10px;"></p>


<p>
"I can calculate the motions of heavenly bodies, but not the madness of people."  ---Isaac Newton
</p>

<p>
Through an investigation within the British Archives, this paper uncovers the British government's corrupt involvement in the fraudulent South Sea Company.
</p>



<p><em>Published in The Concord Review (a premier international history journal)</em></p>
<a href="{{ site.baseurl }}/The%20South%20Sea%20Bubble.pdf" target="_blank">[PDF]</a>
</div>
</div>


<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<h4>Water Insecurity in Forgotten Nations (<em>World Food Prize</em> 2020)</h4>

<p><strong>Avi Bagchi</strong></p>

<div style="text-align: left;">
  <img src="{{ site.baseurl }}/uzbekistan.png" alt="Uzbekistan Water Insecurity" style="max-width: 50%; height: auto; margin: 20px 0; border-radius: 10px;">
  <p style="font-size: 0.9em; color: #777;"><em>Photo taken in Mongolia (Penn Global Seminar 2025) where I continued water insecurity research.</em></p>
</div>

<p>
Institutional fragmentation, contested borders, and "ninja mining" threaten water insecurity in Uzbekistan and Mongolia.
</p>



<p><em>Published in The Global Youth Institute World Food Prize Conference. Cited 1. </em></p>
<a href="https://www.worldfoodprize.org/documents/filelibrary/youth_programs/2021_gyi/2021_gyi_student_papers/BagchiAvi_21232C23E1BC3.pdf" target="_blank">[PDF]</a>
</div>
</div>