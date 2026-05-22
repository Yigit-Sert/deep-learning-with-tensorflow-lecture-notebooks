# Deep Learning With Tensorflow Lecture Notebooks

A technical archive of experiments, implementations, and research modules focusing on Deep Learning, architectural optimization, and NLP methodologies using **TensorFlow/Keras**.

---
## 📂 Project Archive

### 1. Architectural Optimization & Training Workflows
* **MLP Regularization & Generalization Study (`homework1.ipynb`):** A comparative analysis of Baseline, Dropout, and L2 regularization strategies on Fashion-MNIST. Achieved optimal generalization at **88.63%** test accuracy.
* **Custom Training Ecosystem (`homework2.ipynb`):** High-performance `tf.data` pipelines, custom `@tf.function` training loops, and gradient-stable training regimes (Gradient Clipping + Warmup/Cosine Decay schedules).

### 2. Computer Vision & Transfer Learning
* **Spatial Pattern Recognition (`homework3.ipynb`):** Development and fine-tuning of custom CNN architectures for image classification.
* **ResNet50 Fine-tuning (`midterm.ipynb`):** Staged transfer learning pipeline for satellite imagery, employing a frozen-base warm-up strategy to mitigate **catastrophic forgetting**.

### 3. NLP & Text Analysis
* **Machine-Generated Text Detection (`project.ipynb` — SemEval-2024 Task 8):** A binary classification framework designed to distinguish human-written from LLM-generated content. Focuses on transformer-based two-path experimental architectures to address AI-driven misinformation.

---

## 🛠️ Technical Stack
- **Core:** TensorFlow 2.19.0+, Keras
- **Environment:** NumPy, Pandas, Matplotlib, Scikit-Learn
- **Execution:** Optimized for GPU-accelerated environments

---

## 🚀 Usage
You can explore the notebooks directly via GitHub's preview. If you wish to interact with the code:

1. Clone this archive:
   ```bash
   git clone [https://github.com/your-username/tensorflow-engineering-lab.git](https://github.com/your-username/tensorflow-engineering-lab.git)
   
1. Clone this archive:
   ```bash
    pip install tensorflow numpy pandas matplotlib scikit-learn
