<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2800&pause=900&color=818CF8&center=true&vCenter=true&repeat=true&width=640&lines=🤖+Building+intelligent+systems;🧠+Deep+Learning+%7C+Computer+Vision+%7C+NLP;📄+Reproducing+research+papers+into+working+code;🌏+Building+AI+for+Vietnamese+language+%26+context" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/hiiluo08/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/>
  </a>
  &nbsp;
  <a href="mailto:hiilu0.work@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white"/>
  </a>
  &nbsp;
  <img src="https://komarev.com/ghpvc/?username=hiiluo08&color=818cf8&style=flat-square&label=Profile+Views"/>
</p>

---

## 🧑‍💻 About Me

I'm **Nguyen Huy Luong**, a Computer Science student at **Ho Chi Minh City University of Technology (HCMUT)**, passionate about building AI systems that bridge the gap between cutting-edge research and real-world applications.

- 🔭 Currently working on **Transformer-based video understanding** and **Vietnamese NLP pipelines**
- 🧪 Interested in **multimodal learning**, **generative models**, and **efficient AI**
- 📖 I enjoy re-implementing research papers from scratch to deeply understand the underlying mechanics
- 🌏 Building AI solutions tailored for Vietnamese language and context

---

## 🛠️ Tech Stack

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,pytorch,opencv,docker,git,jupyter&perline=6" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
  &nbsp;
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
  &nbsp;
  <img src="https://img.shields.io/badge/XGBoost-189AB4?style=for-the-badge&logoColor=white"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Weights_%26_Biases-FFBE00?style=for-the-badge&logo=weightsandbiases&logoColor=black"/>
</p>

---

## 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🚗 Traffic Accident Detection</h3>
      <p>Reproduction of a <strong>Transformer-based video classifier</strong> for accident detection from surveillance footage. Dual-stream ResNet-50 extracts RGB + Optical Flow features, fed into a 3-layer, 8-head Transformer Encoder with masked mean pooling.</p>
      <p>
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
        <img src="https://img.shields.io/badge/WandB-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black"/>
        <img src="https://img.shields.io/badge/Computer_Vision-5C3EE8?style=flat-square"/>
      </p>
      <a href="https://github.com/hiiluo08/traffic-accident-detection-transformer">→ View Project</a>
    </td>
    <td width="50%" valign="top">
      <h3>🖼️ Image Captioning</h3>
      <p>CNN-Transformer architecture for natural language image description. <strong>ResNet-50</strong> extracts spatial features; a <strong>Transformer Decoder</strong> with causal masking and cross-attention generates captions. Evaluated with BLEU, METEOR, CIDEr on Flickr8k.</p>
      <p>
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
        <img src="https://img.shields.io/badge/Multimodal-818CF8?style=flat-square"/>
      </p>
      <a href="https://github.com/hiiluo08/image-captioning">→ View Project</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>⚖️ Legal Contract Analysis <em>(Vietnamese NLP)</em></h3>
      <p>End-to-end NLP pipeline over <strong>17 Vietnamese legal contracts</strong> (988 clauses): clause splitting, NER, SRL, intent classification (TF-IDF / SVM / PhoBERT), and a rule-based QA system. <strong>Hit@1 = 96%</strong> on 25-question test set.</p>
      <p>
        <img src="https://img.shields.io/badge/PhoBERT-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
        <img src="https://img.shields.io/badge/VnCoreNLP-4CAF50?style=flat-square"/>
        <img src="https://img.shields.io/badge/NLP-3776AB?style=flat-square"/>
      </p>
      <a href="https://github.com/hiiluo08/legal-contract-analysis">→ View Project</a>
    </td>
    <td width="50%" valign="top">
      <h3>🎙️ Speech Emotion Recognition</h3>
      <p>Ensemble of <strong>SVM (RBF + PCA)</strong>, <strong>XGBoost (GPU)</strong>, and <strong>Logistic Regression</strong> on 1058-dim audio features extracted from RAVDESS. Weighted soft voting by per-model validation accuracy.</p>
      <p>
        <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/>
        <img src="https://img.shields.io/badge/XGBoost-189AB4?style=flat-square"/>
        <img src="https://img.shields.io/badge/Audio_ML-10B981?style=flat-square"/>
      </p>
      <a href="https://github.com/hiiluo08/speech-emotion-recognition">→ View Project</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🧩 AI Logic Puzzle Solver</h3>
      <p>Blind DFS vs. heuristic solvers (<strong>Constraint Propagation + MRV</strong> for Nonograms; <strong>Forward Checking + MRV</strong> for Star Battle). Includes benchmark suite and an interactive step-by-step HTML visualizer.</p>
      <p>
        <img src="https://img.shields.io/badge/Search_Algorithms-6366F1?style=flat-square"/>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
      </p>
      <a href="https://github.com/hiiluo08/intro2AI-assignment1-search">→ View Project</a>
    </td>
    <td width="50%" valign="top">
      <h3>🖼️ CIFAR-10 Classification</h3>
      <p>Image classification experiments on the CIFAR-10 benchmark dataset, exploring different CNN architectures and training strategies.</p>
      <p>
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
        <img src="https://img.shields.io/badge/Computer_Vision-5C3EE8?style=flat-square"/>
      </p>
      <a href="https://github.com/hiiluo08/CIFAR10">→ View Project</a>
    </td>
  </tr>
</table>

---

## 📊 GitHub Stats

<div align="center">
  <img height="170em" src="https://github-readme-stats.vercel.app/api?username=hiiluo08&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117"/>
  &nbsp;
  <img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hiiluo08&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&langs_count=6"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=hiiluo08&theme=tokyonight&hide_border=true&background=0D1117" />
</div>

---

## 📫 Let's Connect

<p align="center">
  <a href="https://www.linkedin.com/in/hiiluo08/">
    <img src="https://img.shields.io/badge/LinkedIn-%40hiiluo08-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  &nbsp;&nbsp;
  <a href="mailto:hiilu0.work@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-hiilu0.work%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12&height=100&section=footer" width="100%"/>
</div>
