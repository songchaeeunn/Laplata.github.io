---
layout: project_page
permalink: /
title: "Pet Caring"
authors:
  - Chaeeun Song*
  - yeeun Yang
    
affiliations:
  - Soongsil University

paper: "https://ojs.aaai.org/index.php/AAAI/article/view/32257"
video: "https://youtu.be/5nSJh-IPWd0"
code: "https://github.com/sidl-benchmark/sidl-benchmark.github.io"
site: "[https://github.com/your-repo/dataset](https://petcaring.site/)"
---

<body>
  <hr>
  <img src = "images/Ex01.jpg" alt = "Example 001" style="display: block; margin: auto;">
</body>


<!-- Using HTML to center the abstract -->
<div class="columns is-centered has-text-centered">
  <div class="column is-four-fifths">
    <h2>Abstract</h2>
    <div class="content has-text-justified">
      강아지 고양이 영양 정보를 AI 뭉치에게 물어보세요!
      강아지 고양이에게 간식을 줄 때, AI 뭉치를 이용하면 영양성분 정보를 빠르고 간편하게 얻을 수 있습니다.
      장소 추천, 커뮤니티 기능도 제공해요.
    </div>
  </div>
</div>


<!-- Dataset Download Buttons -->

## SIDL Dataset 
We provide 80% of the scenes for training and learning. The remaining scenes are used for online evaluation.
### Patchify images (512x512)
For efficient training and learning, we provide patchified images. 
<div class="buttons" style="text-align: center; margin-top: 1em;">
  <a class="button is-primary" href="https://petcaring.site/" target="_blank">site</a>
  <a class="button is-primary" href="https://drive.google.com/file/d/1u5-MDauO3XolXsU6eOARwlXo7SnpLwqA/view?usp=sharing" target="_blank">Validation</a>
  <a class="button is-primary" href="https://drive.google.com/file/d/1-SFyyjH0G3C68OfDjZ_O7M4mOqkcJdEf/view?usp=sharing" target="_blank">Test</a>
</div>


### Online Evaluation  
<div class="buttons" style="text-align: center; margin-top: 1em;">
  <a class="button is-primary" href="http://203.253.25.170:8080" target="_blank">Click here to launch evaluation</a>
</div>  
Click the button above to evaluate your model on the SIDL benchmark.


### ISP pipeline
Coming soon


### Citation
<pre><code class="language-bibtex">
@inproceedings{choi2025sidl,
  title     = {SIDL: A Real-World Dataset for Restoring Smartphone Images with Dirty Lenses},
  author    = {Choi, Sooyoung and Park, Sungyong and Kim, Heewon},
  booktitle = {Proceedings of the AAAI Conference on Artificial Intelligence},
  volume    = {39},
  number    = {3},
  pages     = {2545--2554},
  year      = {2025}
}
</code></pre>

