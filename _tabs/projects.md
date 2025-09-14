---
layout: page
icon: fas fa-code
order: 3
title: Projects
---

<style>
.page-header,
#main > .container > .row > .col-12 > h1:first-of-type,
h1.dynamic-title,
.post-title,
.page-title {
  display: none !important;
}
</style>

<div class="projects-container">

  <!-- Publications Section -->
  <div class="mb-5" id="publications">
    <h2>Publications</h2>
    <div class="publications-section">
      <div class="col-12 mb-4">
        <div class="project-card h-100">
          <div class="project-left">
            <div class="project-thumbnail">
              <img src="https://github.com/itsSirish/Images/raw/main/vgg.png" alt="ECG Classification Publication" class="project-img">
            </div>
            <div class="project-tags">
              <span class="badge bg-primary">Deep Learning</span>
              <span class="badge bg-secondary">Mobile AI</span>
              <span class="badge bg-success">Healthcare</span>
              <span class="badge bg-info">IoT</span>
              <span class="badge bg-warning">ECG Analysis</span>
            </div>
          </div>
          <div class="project-content">
            <div class="project-header">
              <h3 class="project-title">
                <i class="fas fa-heartbeat me-2"></i>
                <a href="https://ieeexplore.ieee.org/abstract/document/10301669" target="_blank">A Smartphone-Enabled Deep Learning Approach for Myocardial Infarction Detection Using ECG Traces for IoT-Based Healthcare Applications</a>
                <span class="publication-venue">| IEEE Sensors Letters, vol. 7, no. 11, pp. 1-4</span>
              </h3>
              <div class="project-date-links">
                <span class="project-date">November 2023</span>
                <a href="https://ieeexplore.ieee.org/abstract/document/10301669" target="_blank" class="btn btn-sm btn-outline-info">
                  <i class="fas fa-file-pdf me-1"></i>View Paper
                </a>
              </div>
            </div>
            <div class="project-preview">
              <p>Ensemble deep learning model for real-time myocardial infarction detection on mobile devices using ECG traces.</p>
              <button class="read-more-btn" onclick="toggleDescription('desc-pub-1', this)">Read more</button>
            </div>
            <div class="project-description collapsed" id="desc-pub-1">
              <ul>
                <li>Developed majority voting ensemble with five quantized transfer learning architectures (FP16 and INT8 formats)</li>
                <li>Achieved 99.34% accuracy using fivefold cross-validation scheme for mobile health imaging</li>
                <li>Created portable smartphone-based healthcare system for real-time MI and heart abnormality detection</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Projects Section -->
  <div class="mb-5" id="projects">
    <h2>Projects</h2>
  </div>

  <div class="row">
    <!-- Project 1 - Most Recent -->
    <div class="col-12 mb-4">
      <div class="project-card h-100">
        <div class="project-left">
          <div class="project-thumbnail">
            <img src="https://github.com/itsSirish/Images/raw/main/scrabble.png" alt="Scrabble RL Project" class="project-img">
          </div>
          <div class="project-tags">
            <span class="badge bg-primary">Reinforcement Learning</span>
            <span class="badge bg-secondary">PyTorch</span>
            <span class="badge bg-success">OpenAI Gym</span>
            <span class="badge bg-info">Python</span>
          </div>
        </div>
        <div class="project-content">
          <div class="project-header">
            <h3 class="project-title">
              <i class="fas fa-gamepad me-2"></i>
              <a href="https://github.com/itsSirish/Scrabble-RL-Project" target="_blank">Reinforcement Learning Environment for Scrabble</a>
            </h3>
            <div class="project-date-links">
              <span class="project-date">Mar 2025 – May 2025</span>
              <a href="https://github.com/itsSirish/Scrabble-RL-Project" target="_blank" class="btn btn-sm btn-outline-primary">
                <i class="fab fa-github me-1"></i>GitHub
              </a>
            </div>
          </div>
          <div class="project-preview">
            <p>Custom OpenAI Gym-compliant Scrabble environment with multiple RL agents and comprehensive benchmarking.</p>
            <button class="read-more-btn" onclick="toggleDescription('desc-1', this)">Read more</button>
          </div>
          <div class="project-description collapsed" id="desc-1">
            <ul>
              <li>Engineered environment with full rule fidelity, bag/rack simulation, and GADDAG-based prefix graph for legal move generation</li>
              <li>Implemented Tabular Q-Learning, DQN, PPO, and Self-Play PPO agents with CNN encoders over (2 × 15 × 15) boards</li>
              <li>Achieved 95% win rate vs. greedy/random agents using reward shaping, GAE, and top-50 move selection</li>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <!-- Project 2 -->
    <div class="col-12 mb-4">
      <div class="project-card h-100">
        <div class="project-left">
          <div class="project-thumbnail">
            <img src="https://github.com/itsSirish/Images/raw/main/ad.png" alt="EEG Classification Project" class="project-img">
          </div>
          <div class="project-tags">
            <span class="badge bg-primary">Transformers</span>
            <span class="badge bg-secondary">PyTorch</span>
            <span class="badge bg-success">EEG</span>
            <span class="badge bg-info">Python</span>
          </div>
        </div>
        <div class="project-content">
          <div class="project-header">
            <h3 class="project-title">
              <i class="fas fa-brain me-2"></i>
              <a href="https://github.com/subro608/Neuroinformatics" target="_blank">AD-FTD-CN EEG Classification using Multi-View Transformers</a>
            </h3>
            <div class="project-date-links">
              <span class="project-date">Jan 2025 – May 2025</span>
              <a href="https://github.com/subro608/Neuroinformatics" target="_blank" class="btn btn-sm btn-outline-primary">
                <i class="fab fa-github me-1"></i>GitHub
              </a>
            </div>
          </div>
          <div class="project-preview">
            <p>Deep learning pipeline using Multi-View Transformer for neurological condition classification from 19-channel EEG data.</p>
            <button class="read-more-btn" onclick="toggleDescription('desc-2', this)">Read more</button>
          </div>
          <div class="project-description collapsed" id="desc-2">
            <ul>
              <li>Designed MVT with Graph Attention, cross-view fusion, and multiscale EEG embeddings integrating time, spectral, and spatial features</li>
              <li>Achieved 98.55% within-subject and 64.95% cross-subject accuracy, outperforming SVM, MLP, and ADformer</li>
              <li>Generated scalp heatmaps and attention maps for enhanced interpretability of lobe-specific frequency patterns</li>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <!-- Project 3 -->
    <div class="col-12 mb-4">
      <div class="project-card h-100">
        <div class="project-left">
          <div class="project-thumbnail">
            <img src="https://github.com/itsSirish/Images/raw/main/detigen.png" alt="Det-IGEN Watermarking Project" class="project-img">
          </div>
          <div class="project-tags">
            <span class="badge bg-primary">GenAI</span>
            <span class="badge bg-secondary">PyTorch</span>
            <span class="badge bg-success">Docker</span>
            <span class="badge bg-info">Python</span>
          </div>
        </div>
        <div class="project-content">
          <div class="project-header">
            <h3 class="project-title">
              <i class="fas fa-shield-alt me-2"></i>
              <a href="https://github.com/pandeysh-25/det-IGEN" target="_blank">Det-IGEN: Detectable Watermarking in Image Generation</a>
            </h3>
            <div class="project-date-links">
              <span class="project-date">Sept 2024 – Dec 2024</span>
              <a href="https://github.com/pandeysh-25/det-IGEN" target="_blank" class="btn btn-sm btn-outline-primary">
                <i class="fab fa-github me-1"></i>GitHub
              </a>
            </div>
          </div>
          <div class="project-preview">
            <p>Invisible tree ring watermarking system for Diffusion Models to detect AI-generated content.</p>
            <button class="read-more-btn" onclick="toggleDescription('desc-3', this)">Read more</button>
          </div>
          <div class="project-description collapsed" id="desc-3">
            <ul>
              <li>Implemented watermarking in the generation process by modifying initial noise vector in Fourier domain</li>
              <li>Achieved perfect detection performance (AUC and TPR@1%FPR of 1.000) with negligible impact on image quality</li>
              <li>Maintained high performance under adversarial conditions for robust AI content detection</li>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <!-- Project 4 -->
    <div class="col-12 mb-4" id="hate-speech-project">
      <div class="project-card h-100">
        <div class="project-left">
          <div class="project-thumbnail">
            <img src="https://user-images.githubusercontent.com/73981982/146150161-f1af3e58-647e-42bb-ab88-828128bdda57.png" alt="Hate Speech Detection Project" class="project-img">
          </div>
          <div class="project-tags">
            <span class="badge bg-primary">TensorFlow</span>
            <span class="badge bg-secondary">NLTK</span>
            <span class="badge bg-success">SpaCy</span>
            <span class="badge bg-info">PySpark</span>
          </div>
        </div>
        <div class="project-content">
          <div class="project-header">
            <h3 class="project-title">
              <i class="fas fa-comments me-2"></i>
              <a href="https://github.com/itsSirish/Hate-Speech-Detection" target="_blank">Multi-Source Hate Speech Detection</a>
            </h3>
            <div class="project-date-links">
              <span class="project-date">Jan 2023 – May 2023</span>
              <a href="https://github.com/itsSirish/Hate-Speech-Detection" target="_blank" class="btn btn-sm btn-outline-primary">
                <i class="fab fa-github me-1"></i>GitHub
              </a>
            </div>
          </div>
          <div class="project-preview">
            <p>Multi-class hate speech detection system using 11 Twitter datasets with advanced NLP techniques.</p>
            <button class="read-more-btn" onclick="toggleDescription('desc-4', this)">Read more</button>
          </div>
          <div class="project-description collapsed" id="desc-4">
            <ul>
              <li>Developed system using 79k samples after preprocessing (URL/emoji removal, stopword removal, text normalization)</li>
              <li>Implemented TF-IDF, GloVe, and BERT-based embeddings with ELECTRA, DistilBERT variants and various classifiers</li>
              <li>Achieved ROC AUC 0.962, F1 Score 0.896 with ELECTRA + Logistic Regression using PCA optimization</li>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <!-- Project 5 -->
    <div class="col-12 mb-4" id="blockchain-project">
      <div class="project-card h-100">
        <div class="project-left">
          <div class="project-thumbnail">
            <img src="https://github.com/itsSirish/game-asset-dapp/raw/main/images/Capture8.PNG" alt="Gaming Assets NFT Marketplace" class="project-img">
          </div>
          <div class="project-tags">
            <span class="badge bg-primary">Solidity</span>
            <span class="badge bg-secondary">React</span>
            <span class="badge bg-success">Web3.js</span>
            <span class="badge bg-info">Tailwind CSS</span>
          </div>
        </div>
        <div class="project-content">
          <div class="project-header">
            <h3 class="project-title">
              <i class="fas fa-gamepad me-2"></i>
              <a href="https://github.com/itsSirish/game-asset-dapp" target="_blank">Gaming Assets NFT Marketplace</a>
            </h3>
            <div class="project-date-links">
              <span class="project-date">Sept 2022 – Dec 2022</span>
              <a href="https://github.com/itsSirish/game-asset-dapp" target="_blank" class="btn btn-sm btn-outline-primary">
                <i class="fab fa-github me-1"></i>GitHub
              </a>
            </div>
          </div>
          <div class="project-preview">
            <p>Specialized gaming NFT marketplace on Polygon network for trading in-game assets as ERC-721 tokens.</p>
            <button class="read-more-btn" onclick="toggleDescription('desc-5', this)">Read more</button>
          </div>
          <div class="project-description collapsed" id="desc-5">
            <ul>
              <li>Integrated marketplace enabling players to trade characters, skins, weapons with automated royalty distribution</li>
              <li>Processed 500+ transactions with 2-second average confirmation time</li>
              <li>Built responsive frontend with Web3.js integration and IPFS for decentralized metadata storage</li>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <!-- Project 6 - Eye Tracker (Commented Out) -->
    <!--
    <div class="col-12 mb-4">
      <div class="project-card h-100">
        <div class="project-header">
          <h3 class="project-title">
            <i class="fas fa-eye me-2"></i>
            <a href="https://github.com/itsSirish/Eye-Tracker-and-Gaze-Estimation" target="_blank">Interactive Eye-Tracking and Gaze Estimation System</a>
          </h3>
          <div class="project-tags">
            <span class="badge bg-primary">OpenCV</span>
            <span class="badge bg-secondary">PyAutoGUI</span>
            <span class="badge bg-success">Python</span>
            <span class="badge bg-info">Computer Vision</span>
          </div>
          <div class="project-date">Sept 2022 – Dec 2022</div>
        </div>
        <div class="project-description">
          <p>Interactive eye-tracking system for cursor control and gaming interfaces using computer vision techniques.</p>
          <ul>
            <li>Developed system using OpenCV, MediaPipe, and PyAutoGUI for cursor control, touch emulation, and gaming interfaces</li>
            <li>Implemented algorithmic optimization with Hill Climbing (82.5% accuracy) and Genetic Algorithms (90.2% accuracy)</li>
            <li>Created custom face mapping dataset enabling precise cursor movement based on eye and gaze tracking</li>
          </ul>
        </div>
        <div class="project-links">
          <a href="https://github.com/itsSirish/Eye-Tracker-and-Gaze-Estimation" target="_blank" class="btn btn-sm btn-outline-primary">
            <i class="fab fa-github me-1"></i>GitHub
          </a>
        </div>
      </div>
    </div>
    -->

    <!-- Project 5 -->
    <div class="col-12 mb-4" id="led-project">
      <div class="project-card h-100">
        <div class="project-left">
          <div class="project-thumbnail">
            <img src="https://github.com/itsSirish/Images/raw/main/led.png" alt="LED Audio Visualizer Project" class="project-img">
          </div>
          <div class="project-tags">
            <span class="badge bg-primary">Arduino</span>
            <span class="badge bg-secondary">ESP32</span>
            <span class="badge bg-success">FFT</span>
            <span class="badge bg-info">Embedded Systems</span>
          </div>
        </div>
        <div class="project-content">
          <div class="project-header">
            <h3 class="project-title">
              <i class="fas fa-music me-2"></i>
              <a href="https://arcbphc.vercel.app/projects/2021-12-05-blog-LED-Matrix" target="_blank">Audio Visualiser Arduino</a>
            </h3>
            <div class="project-date-links">
              <span class="project-date">Oct 2021 – Nov 2021</span>
              <a href="https://arcbphc.vercel.app/projects/2021-12-05-blog-LED-Matrix" target="_blank" class="btn btn-sm btn-outline-secondary">
                <i class="fas fa-external-link-alt me-1"></i>Project Details
              </a>
            </div>
          </div>
          <div class="project-preview">
            <p>Audio spectrum visualizer with LED matrix that responds to music in real-time.</p>
            <button class="read-more-btn" onclick="toggleDescription('desc-6', this)">Read more</button>
          </div>
          <div class="project-description collapsed" id="desc-6">
            <ul>
              <li>Created dynamic LED matrix display that visualizes audio frequency spectrum</li>
              <li>Employed ESP32 microcontroller with Fast Fourier Transform (FFT) processing</li>
              <li>Implemented programmable NeoPixels for responsive and colorful audio visualization</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>


  <div class="mt-5" id="games">
    <h2>Games</h2>
    <p class="lead text-muted">Games developed as part of game design coursework and personal projects.</p>

    <div class="games-section">
      <div class="games-grid">
        <div class="game-card">
          <div class="game-thumbnail">
            <img src="https://github.com/itsSirish/Images/raw/main/zombie.png" alt="Zombieland Game" class="game-img">
          </div>
          <div class="game-header">
            <h3 class="game-title">
              <i class="fas fa-crosshairs game-icon-zombie me-2"></i>
              <a href="https://isshihara.itch.io/zombieland" target="_blank">Zombieland</a>
            </h3>
          </div>
          <div class="game-description">
            <p>Survival horror game featuring zombie apocalypse scenarios with strategic gameplay elements.</p>
            <div class="game-features">
              <span class="feature-tag">Survival Horror</span>
              <span class="feature-tag">Strategy</span>
              <span class="feature-tag">Action</span>
            </div>
          </div>
          <div class="game-links">
            <a href="https://isshihara.itch.io/zombieland" target="_blank" class="btn btn-sm btn-outline-primary">
              <i class="fas fa-play me-1"></i>Play Game
            </a>
          </div>
        </div>

        <div class="game-card">
          <div class="game-thumbnail">
            <img src="https://github.com/itsSirish/Images/raw/main/outpost.png" alt="Outpost Epsilon Game" class="game-img">
          </div>
          <div class="game-header">
            <h3 class="game-title">
              <i class="fas fa-rocket game-icon-space me-2"></i>
              <a href="https://isshihara.itch.io/outpost-epsilon" target="_blank">Outpost Epsilon</a>
            </h3>
          </div>
          <div class="game-description">
            <p>Space exploration game set in a remote outpost with mystery and adventure elements.</p>
            <div class="game-features">
              <span class="feature-tag">Space Exploration</span>
              <span class="feature-tag">Mystery</span>
              <span class="feature-tag">Adventure</span>
            </div>
          </div>
          <div class="game-links">
            <a href="https://isshihara.itch.io/outpost-epsilon" target="_blank" class="btn btn-sm btn-outline-primary">
              <i class="fas fa-play me-1"></i>Play Game
            </a>
          </div>
        </div>

        <div class="game-card">
          <div class="game-thumbnail">
            <img src="https://github.com/itsSirish/Images/raw/main/zero.png" alt="Zero Vector Game" class="game-img">
          </div>
          <div class="game-header">
            <h3 class="game-title">
              <i class="fas fa-arrows-alt game-icon-gravity me-2"></i>
              <a href="https://jal-ms.itch.io/level-design" target="_blank">Zero Vector</a>
            </h3>
          </div>
          <div class="game-description">
            <p>Gravity-shifting boss fight platformer game featuring dynamic physics-based gameplay mechanics.</p>
            <div class="game-features">
              <span class="feature-tag">Platformer</span>
              <span class="feature-tag">Gravity Mechanics</span>
              <span class="feature-tag">Boss Fight</span>
            </div>
          </div>
          <div class="game-links">
            <a href="https://jal-ms.itch.io/level-design" target="_blank" class="btn btn-sm btn-outline-primary">
              <i class="fas fa-play me-1"></i>Play Game
            </a>
          </div>
        </div>

        <div class="game-card">
          <div class="game-thumbnail">
            <img src="https://github.com/itsSirish/Images/raw/main/peng.png" alt="Penguin Adventure Game" class="game-img">
          </div>
          <div class="game-header">
            <h3 class="game-title">
              <i class="fas fa-snowflake game-icon-ice me-2"></i>
              <a href="https://zzhuang.itch.io/penguin-adventure" target="_blank">Penguin Adventure</a>
            </h3>
          </div>
          <div class="game-description">
            <p>Charming adventure game featuring a penguin protagonist in arctic environments with puzzle elements.</p>
            <div class="game-features">
              <span class="feature-tag">Adventure</span>
              <span class="feature-tag">Puzzle</span>
              <span class="feature-tag">Family Friendly</span>
            </div>
          </div>
          <div class="game-links">
            <a href="https://zzhuang.itch.io/penguin-adventure" target="_blank" class="btn btn-sm btn-outline-primary">
              <i class="fas fa-play me-1"></i>Play Game
            </a>
          </div>
        </div>
      </div>

      <div class="portfolio-link mt-4 text-center">
        <a href="https://isshihara.itch.io/" target="_blank" class="btn btn-outline-secondary">
          <i class="fas fa-external-link-alt me-2"></i>View Complete Game Portfolio
        </a>
      </div>
    </div>
  </div>

</div>

<style>
.projects-container {
  max-width: 100%;
}

.project-card {
  background: var(--card-bg);
  border: 1px solid var(--border-color);
  border-radius: 0.5rem;
  padding: 0;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  overflow: hidden;
  display: flex;
  flex-direction: row;
  align-items: stretch;
}

.project-left {
  width: 300px;
  min-width: 300px;
  display: flex;
  flex-direction: column;
}

.project-thumbnail {
  width: 100%;
  height: 200px;
  overflow: hidden;
  position: relative;
  background: var(--card-bg);
  border-radius: 0.5rem 0 0 0;
}

.project-content {
  flex: 1;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.project-img {
  width: calc(100% - 30px);
  height: calc(100% - 30px);
  object-fit: contain;
  object-position: center;
  transition: transform 0.3s ease, filter 0.3s ease;
  margin: 15px;
  border-radius: 0.375rem;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}

.project-card:hover .project-img {
  transform: scale(1.02);
  filter: brightness(1.1);
}


.project-header {
  padding: 1.5rem 1.5rem 0.5rem 1.5rem;
}

.project-description {
  padding: 0 1.5rem;
}

.project-description.collapsed {
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.3s ease, padding 0.3s ease;
  padding-top: 0;
  padding-bottom: 0;
}

.project-description.expanded {
  max-height: 500px;
  transition: max-height 0.3s ease, padding 0.3s ease;
  padding-top: 0.5rem;
  padding-bottom: 0.5rem;
}

.project-links {
  padding: 0.5rem 1.5rem 1.5rem 1.5rem;
  margin-top: auto;
}

.project-preview {
  padding: 0.25rem 1.5rem 0.5rem 1.5rem;
  margin-bottom: 0;
  line-height: 1.5;
}

.project-date-links {
  display: flex;
  align-items: center;
  gap: 1rem;
  padding: 0 0 0.5rem 0;
}

.project-date {
  color: var(--text-muted-color);
  font-size: 0.9rem;
  font-weight: 500;
}

.project-tags {
  padding: 0.75rem 1rem;
  background: var(--card-bg);
  border-radius: 0 0 0 0.5rem;
  border-top: 1px solid var(--border-color);
}

.project-tags .badge {
  margin-right: 0.5rem;
  margin-bottom: 0.25rem;
}

.publication-venue {
  font-size: 0.85rem;
  color: var(--text-muted-color);
  font-weight: 400;
  margin-left: 0.5rem;
}

.read-more-btn {
  background: none;
  border: none;
  color: var(--link-color);
  cursor: pointer;
  font-size: 0.9rem;
  margin-top: 0.5rem;
  padding: 0;
  text-decoration: underline;
}

.read-more-btn:hover {
  color: var(--link-hover-color);
}

.project-preview {
  margin-bottom: 0.5rem;
  line-height: 1.5;
}

.project-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
}

.project-header {
  margin-bottom: 1rem;
}

.project-title {
  font-size: 1.25rem;
  font-weight: 600;
  margin-bottom: 0.5rem;
  color: var(--heading-color);
}

.project-title a {
  color: var(--link-color);
  text-decoration: none;
  transition: color 0.2s ease;
}

.project-title a:hover {
  color: var(--link-hover-color);
  text-decoration: none;
}

.project-tags {
  margin-bottom: 1rem;
}

.project-tags .badge {
  margin-right: 0.5rem;
  margin-bottom: 0.25rem;
}

.project-date {
  color: var(--text-muted-color);
  font-size: 0.85rem;
  font-weight: 500;
  margin-top: 0.5rem;
}

.project-description {
  flex-grow: 1;
  margin-bottom: 1rem;
}

.project-description ul {
  margin-bottom: 0;
  padding-left: 1.2rem;
}

.project-description li {
  margin-bottom: 0.25rem;
  font-size: 0.9rem;
}

.project-links .btn {
  margin-right: 0.5rem;
  margin-bottom: 0.5rem;
}

.contribution-item {
  margin-bottom: 1.5rem;
}

.contribution-item h4 {
  font-size: 1.1rem;
  margin-bottom: 0.5rem;
}

.contribution-item a {
  color: var(--link-color);
  text-decoration: none;
}

.contribution-item a:hover {
  text-decoration: underline;
}

/* Publications section styling */
.publications-section {
  margin-top: 1rem;
}

.publication-card {
  background: var(--card-bg);
  border: 1px solid var(--border-color);
  border-radius: 0.5rem;
  padding: 2rem;
  margin-bottom: 1.5rem;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.publication-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
}

.publication-header {
  margin-bottom: 1rem;
}

.publication-title {
  font-size: 1.2rem;
  font-weight: 600;
  color: var(--heading-color);
  margin-bottom: 0.75rem;
  line-height: 1.3;
}

.publication-title a {
  color: var(--heading-color);
  text-decoration: none;
  transition: color 0.2s ease;
}

.publication-title a:hover {
  color: var(--link-color);
  text-decoration: none;
}

.publication-venue {
  color: var(--link-color);
  font-weight: 500;
  font-size: 1rem;
  margin-bottom: 0.25rem;
}

.publication-date {
  color: var(--text-muted-color);
  font-size: 0.9rem;
  font-weight: 500;
}

.publication-description {
  margin-bottom: 1rem;
}

.publication-description ul {
  margin-bottom: 1rem;
  padding-left: 1.2rem;
}

.publication-description li {
  margin-bottom: 0.5rem;
  line-height: 1.5;
}

.publication-tags {
  margin-bottom: 1rem;
}

.publication-tags .badge {
  margin-right: 0.5rem;
  margin-bottom: 0.25rem;
}

.publication-links {
  display: flex;
  gap: 0.5rem;
  flex-wrap: wrap;
}

.publication-links .btn {
  margin-bottom: 0.5rem;
}

.publication-citation {
  margin-bottom: 1rem;
  background: var(--tag-bg, #f8f9fa);
  padding: 1rem;
  border-radius: 0.375rem;
  border-left: 3px solid var(--link-color);
}

.publication-citation h4 {
  font-size: 0.9rem;
  font-weight: 600;
  color: var(--heading-color);
  margin-bottom: 0.5rem;
}

.citation-text {
  font-size: 0.9rem;
  line-height: 1.5;
  margin: 0;
  color: var(--text-color);
  font-family: 'Times New Roman', serif;
}

/* Games section styling */
.games-section {
  margin-top: 1rem;
}

.games-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 1.5rem;
  margin-bottom: 1rem;
}

.game-card {
  background: var(--card-bg);
  border: 1px solid var(--border-color);
  border-radius: 0.5rem;
  padding: 0;
  margin-bottom: 1.5rem;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  overflow: hidden;
}

.game-thumbnail {
  width: 100%;
  height: 200px;
  overflow: hidden;
  position: relative;
  background: var(--card-bg);
  border-radius: 0.5rem 0.5rem 0 0;
}

.game-img {
  width: calc(100% - 30px);
  height: calc(100% - 30px);
  object-fit: contain;
  object-position: center;
  transition: transform 0.3s ease, filter 0.3s ease;
  margin: 15px;
  border-radius: 0.375rem;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}

.game-card:hover .game-img {
  transform: scale(1.02);
  filter: brightness(1.1);
}

.game-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
}

.game-header {
  margin-bottom: 1rem;
  padding: 1.5rem 1.5rem 0.5rem 1.5rem;
}

.game-description {
  padding: 0 1.5rem 1.5rem 1.5rem;
}

.game-links {
  padding: 0 1.5rem 1.5rem 1.5rem;
  padding-top: 0;
}

.game-title {
  font-size: 1.3rem;
  font-weight: 600;
  color: var(--heading-color);
  margin-bottom: 0.5rem;
}

.game-title a {
  color: var(--link-color);
  text-decoration: none;
  transition: color 0.2s ease;
}

.game-title a:hover {
  color: var(--link-hover-color);
  text-decoration: none;
}

.game-description {
  margin-bottom: 1rem;
}

.game-features {
  margin-top: 0.75rem;
}

.feature-tag {
  background: var(--bs-primary);
  color: white;
  padding: 0.25rem 0.75rem;
  border-radius: 1rem;
  font-size: 0.8rem;
  margin-right: 0.5rem;
  margin-bottom: 0.25rem;
  display: inline-block;
  font-weight: 500;
}

.feature-tag:nth-child(2n) {
  background: var(--bs-secondary);
}

.feature-tag:nth-child(3n) {
  background: var(--bs-success);
}

.feature-tag:nth-child(4n) {
  background: var(--bs-info);
}

.feature-tag:nth-child(5n) {
  background: var(--bs-warning);
  color: var(--bs-dark);
}

.game-links {
  display: flex;
  gap: 0.5rem;
  flex-wrap: wrap;
}

.game-links .btn {
  margin-bottom: 0.5rem;
}

/* Colorized game icons */
.game-icon-zombie {
  color: #dc3545; /* Red for zombie theme */
}

.game-icon-space {
  color: #6f42c1; /* Purple for space theme */
}

.game-icon-gravity {
  color: #20c997; /* Teal for physics/gravity theme */
}

.game-icon-ice {
  color: #17a2b8; /* Cyan for ice/winter theme */
}

@media (max-width: 768px) {
  .project-card {
    flex-direction: column;
  }

  .project-thumbnail {
    width: 100%;
    min-width: 100%;
    height: 180px;
    border-radius: 0.5rem 0.5rem 0 0;
  }

  .project-title {
    font-size: 1.1rem;
  }

  .publication-card {
    padding: 1rem;
  }

  .publication-title {
    font-size: 1.1rem;
  }
}
</style>

<script>
function toggleDescription(descId, button) {
  const desc = document.getElementById(descId);

  if (desc.classList.contains('collapsed')) {
    desc.classList.remove('collapsed');
    desc.classList.add('expanded');
    button.textContent = 'Read less';
  } else {
    desc.classList.remove('expanded');
    desc.classList.add('collapsed');
    button.textContent = 'Read more';
  }
}
</script>