---
permalink: /
title: # "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


<style>
.selected-publications {
  display: flex;
  flex-direction: column;
  gap: 2rem;
  margin-top: 2rem;
}

.publication {
  display: flex;
  align-items: flex-start;
  gap: 1.5rem;
}

.publication-image img {
  width: 15rem;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.publication-info {
  flex: 1;
}

.publication-info h3 {
  margin: 0;
  font-size: 1.0rem;
  color: #4B6D93;
}

.publication-info p {
  margin: 0.5rem 0;
  font-size: 0.8rem;
  color: #607080;
}

.publication-links {
  display: flex;
  align-items: center;
  gap: 0.5rem;
}

.publication-links a {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 32px;
  height: 32px;
  border-radius: 50%;
  background-color: #f4f4f4;
  transition: transform 0.2s ease, background-color 0.2s ease;
}

.publication-links a img {
  width: 32px;
  height: 32px;
}

.publication-links a:hover {
  transform: scale(1.1);
  background-color: #e0e0e0;
}

/* Ensure SVG has no white background */
.publication-links a img.icon {
  background-color: transparent; /* Ensure the background is transparent */
  border-radius: 50%; /* If you want a circular icon */
}

/* Optional: Adjust the size and alignment if needed */
.publication-links a img {
  width: 32px;
  height: 32px;
  object-fit: contain; /* Ensure the SVG scales properly */
}

/* Bold and larger font size for your name */
.publication-info strong {
  font-size: 0.7rem; /* Slightly larger font */
  font-weight: bold;
  color: #4B6D93; /* Highlight color */
  display: inline; /* Ensure inline display */
}

/* Smaller font size for co-authors */
.publication-info .co-authors {
  font-size: 0.6rem; /* Smaller size */
  color: #607080; /* Subtle gray color */
  display: inline; /* Ensure inline display */
}

.research-areas {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1rem;
  margin-top: 1.5rem;
  padding: 1rem;
  background-color: #f9f9f9; /* Subtle background */
  border-radius: 12px; /* Rounded corners */
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Subtle shadow */
}

.area {
  display: flex;
  align-items: center; /* Aligns icons and text */
  gap: 0.75rem;
  background-color: #ffffff; /* White cards */
  padding: 1rem;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* Subtle shadow */
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  text-decoration: none !important; /* Ensure no underlines */
  color: inherit !important; /* Inherit the text color */
}

.area:hover {
  transform: scale(1.05); /* Slight zoom on hover */
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); /* Enhanced shadow on hover */
  background-color: #f0f0f0; /* Slightly highlighted background */
}

.area p {
  margin: 0;
  font-size: 1rem;
  font-weight: 500;
  color: #4B6D93; /* Consistent highlight color */
  line-height: 1.5; /* Improves vertical alignment */
  text-decoration: none !important; /* Removes underline on links inside p */
}

.icon {
  font-size: 1.5rem; /* Larger icon size */
  color: #4B6D93; /* Highlight color */
}

</style>



Hello, I'm **Serdar**. As a researcher in computer vision, I am dedicated to developing technologies that effectively bridge theoretical concepts with practical applications. My research spans the comprehensive field of biometrics and specialized areas like histopathology image analysis. At the heart of all my projects is a focus on enhancing how we transform images into meaningful vector representations.

I am focused on creating fast, accurate models with robust generalization capabilities, ensuring that our advancements are both innovative and applicable in real-world settings. This dedication drives my efforts to transform cutting-edge research into effective solutions for diverse applications, from medical diagnostics to security systems.

As I explore potential PhD opportunities and continue to expand my contributions to the field, I actively share the code from my studies on [GitHub](https://github.com/serdaryildiz). I am eager to collaborate with academic peers who are committed to pushing the boundaries of computer vision. If you are passionate about advancing computer vision, I invite you to connect with me to discuss how we can collaborate on future projects.



## Research Areas

<div class="research-areas">
  <a href="/research-areas/#person-reid" class="area">
    <span class="icon">👤</span>
    <p>Person Re-Identification</p>
  </a>
  <a href="/research-areas/#geo-localization" class="area">
    <span class="icon">🌍</span>
    <p>Geo-Localization</p>
  </a>
  <a href="/research-areas/#scene-text-recognition" class="area">
    <span class="icon">📝</span>
    <p>Scene Text Recognition</p>
  </a>
  <a href="/research-areas/#image-captioning" class="area">
    <span class="icon">🖼️</span>
    <p>Image Captioning</p>
  </a>
  <a href="/research-areas/#mitosis-detection" class="area">
    <span class="icon">🧬</span>
    <p>Mitosis Detection</p>
  </a>
  <a href="/research-areas/#nuclei-instance-segmentation" class="area">
    <span class="icon">🔬</span>
    <p>Nuclei Instance Segmentation</p>
  </a>
  <a href="/research-areas/#semi-supervised-learning" class="area">
    <span class="icon">📚</span>
    <p>Semi-Supervised Learning</p>
  </a>
</div>




## Selected Publications

<div class="selected-publications">
  
  <div class="publication">
    <div class="publication-image">
      <img src="selected_publications/turkish-scene-text-recognition.png" alt="Paper 1 Image">
    </div>
    <div class="publication-info">
      <h3>Turkish scene text recognition: Introducing extensive real and synthetic datasets and a novel recognition model</h3>
        <p>
          <strong>Serdar YILDIZ</strong> 
        </p>
      <p><em>Engineering Science and Technology, an International Journal, 2024</em></p>
      <div class="publication-links">
        <a href="https://www.sciencedirect.com/science/article/pii/S2215098624002672" target="_blank" title="Paper">
          <img src="images/paper.png" alt="Paper Icon" class="icon">
        </a>
        <a href="https://github.com/serdaryildiz/MViT-TR" target="_blank" title="GitHub">
          <img src="images/github.png" alt="GitHub Icon" class="icon">
        </a>
        <a href="https://github.com/serdaryildiz/TS-TR" target="_blank" title="GitHub">
          <img src="images/github.png" alt="GitHub Icon" class="icon">
        </a>
        <a href="https://github.com/serdaryildiz/STS-TR" target="_blank" title="GitHub">
          <img src="images/github.png" alt="GitHub Icon" class="icon">
        </a>
        <a href="https://huggingface.co/spaces/serdaryildiz/MViT-TR" target="_blank" title="HuggingFace">
          <img src="images/huggingface.png" alt="HuggingFace Icon" class="icon">
        </a>
      </div>
    </div>
  </div>
    <div class="publication">
    <div class="publication-image">
      <img src="selected_publications/entireid.png" alt="Paper 1 Image">
    </div>
    <div class="publication-info">
      <h3>ENTIRe-ID: An Extensive and Diverse Dataset for Person Re-Identification</h3>
        <p>
          <strong>Serdar YILDIZ</strong> 
           <span class="co-authors">, A. Nezih Kasım</span>
        </p>
      <p><em>IEEE 18th International Conference on Automatic Face and Gesture Recognition (FG), 2024</em></p>
      <div class="publication-links">
        <a href="https://ieeexplore.ieee.org/abstract/document/10581945" target="_blank" title="Paper">
          <img src="images/paper.png" alt="Paper Icon" class="icon">
        </a>
        <a href="https://arxiv.org/pdf/2405.20465" target="_blank" title="Arxiv">
          <img src="images/arxiv.png" alt="Paper Icon" class="icon">
        </a>
        <a href="https://serdaryildiz.github.io/ENTIRe-ID/" target="_blank" title="GitHub">
          <img src="images/github.png" alt="GitHub Icon" class="icon">
        </a>
      </div>
    </div>
  </div>
  <div class="publication">
    <div class="publication-image">
      <img src="selected_publications/cnmi-yolo.png" alt="Paper 1 Image">
    </div>
    <div class="publication-info">
      <h3>ConvNext Mitosis Identification—You Only Look Once (CNMI-YOLO): Domain Adaptive and Robust Mitosis Identification in Digital Pathology</h3>
        <p>
          <span class="co-authors">Yasemin TOPUZ, </span>
          <strong>Serdar YILDIZ</strong> 
          <span class="co-authors">, Songül VARLI</span>
        </p>
      <p><em>Laboratory Investigation, 2024</em></p>
      <div class="publication-links">
        <a href="https://www.sciencedirect.com/science/article/abs/pii/S0023683724018087" target="_blank" title="Paper">
          <img src="images/paper.png" alt="Paper Icon" class="icon">
        </a>
      </div>
    </div>
  </div>
  <div class="publication">
    <div class="publication-image">
      <img src="selected_publications/trcaptionnet.png" alt="Paper 1 Image">
    </div>
    <div class="publication-info">
      <h3>TRCaptionNet: A novel and accurate deep Turkish image captioning model with vision transformer based image encoders and deep linguistic text decoders</h3>
        <p>
          <strong>Serdar YILDIZ</strong> 
          <span class="co-authors">, Abbas MEMİŞ, Songül VARLI</span>
        </p>
      <p><em>Turkish Journal of Electrical Engineering and Computer Sciences, 2023</em></p>
      <div class="publication-links">
        <a href="https://journals.tubitak.gov.tr/elektrik/vol31/iss6/11/" target="_blank" title="Paper">
          <img src="images/paper.png" alt="Paper Icon" class="icon">
        </a>
        <a href="https://github.com/serdaryildiz/TRCaptionNet" target="_blank" title="GitHub">
          <img src="images/github.png" alt="GitHub Icon" class="icon">
        </a>
        <a href="https://huggingface.co/spaces/serdaryildiz/TRCaptionNet" target="_blank" title="HuggingFace">
          <img src="images/huggingface.png" alt="HuggingFace Icon" class="icon">
        </a>
        <a href="https://huggingface.co/spaces/serdaryildiz/TRCaptionNet-TasvirEt" target="_blank" title="HuggingFace">
          <img src="images/huggingface.png" alt="HuggingFace Icon" class="icon">
        </a>
      </div>
    </div>
  </div>
    <div class="publication">
    <div class="publication-image">
      <img src="selected_publications/turnaround.png" alt="Paper 1 Image">
    </div>
    <div class="publication-info">
      <h3>A turnaround control system to automatically detect and monitor the time stamps of ground service actions in airports: A deep learning and computer vision based approach</h3>
        <p>
          <strong>Serdar YILDIZ</strong> 
          <span class="co-authors">, Onur Aydemir, Abbas MEMİŞ, Songül VARLI</span>
        </p>
      <p><em>Engineering Applications of Artificial Intelligence, 2022</em></p>
      <div class="publication-links">
        <a href="https://www.sciencedirect.com/science/article/pii/S0952197622002056" target="_blank" title="Paper">
          <img src="images/paper.png" alt="Paper Icon" class="icon">
        </a>
      </div>
    </div>
  </div>
  

</div>











