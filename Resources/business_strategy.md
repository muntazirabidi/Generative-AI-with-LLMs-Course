# Business Executives: Introduction

## Speaker Introduction
- **Name:** Kate Soule
- **Position:** Senior Manager of Business Strategy at IBM Research
- **Presentation Topic:** Strategies to improve foundation model's trustworthiness and efficiency for enterprise deployment.

## Foundation Model Components

### 1. Data

#### Overview
- The significance of quantity, quality, and degree of specialization.

#### Quantity
- Training on vast volumes of unlabeled data.
- Data volume as a critical driver for model performance across tasks.
- Trade-offs: Greater data volume results in higher compute costs.
- Current research is zooming into the minimum data required per model parameter.
  - **Training Requirement:** Around 10 words per parameter.
  - **Inference:** Over 100 words per parameter.

#### Quality
- A direct influencer of model trustworthiness.
- GIGO (Garbage In, Garbage Out): Poor input leads to poor output. Biased data leads to a biased model.
- Facing challenges:
  - Quality verification is tough due to the sheer data volume.
  - Internet-scraped data can sometimes originate from dubious sources.
  - **Proposed Solution:** Implementing Hate and Profanity filtering (abbreviated as HAP filtering).

#### Specialization
- Drawing parallels: Consulting a medical professional versus a generally intelligent individual.
- Specialized models have showcased performance on par, if not better, than their general counterparts.
- Recommendation: A balanced 50/50 data split between specialized and general datasets for optimal performance.

### 2. Architecture

#### Overview
- Architectures act as a model's blueprint, dictating how data is encoded.

#### Styles
- **Decoder Only Model (Example):** GPT3. While powerful, it's notably dense.
- **Encoder Decoder Models:** These are recognized for their lightweight nature and efficiency.

#### Size and Parameters
- It's crucial for model size to be in harmony with the size of the training data.
- Models that are disproportionately large can be prone to overfitting and generally less efficiency.

### 3. Training

#### Overview
- The process involves pre-training, alignment, and other nuanced techniques.

#### Pre-training
- Pre-training establishes the foundation models.
- Dictates the compute costs and the carbon footprint.

#### Alignment
- This is the refining phase that kicks in after pre-training.
- The goal is to calibrate the model to exhibit desired behaviors, with a special emphasis on safety and trustworthiness.
- Adopted techniques include reinforcement learning backed by human feedback, data-centric methods, and post-processing edits.

---
## IBM's Noteworthy Contributions

### Data
- IBM's initiative in constructing expansive enterprise datasets.
- A profound focus on data quality through:
  - Assessing the reputation of sources.
  - Legal oversight for data inclusion.
  - Quality assurance through red teaming.
  - Specialized domains like finance and cybersecurity are a priority.

### Architecture
- Venturing into diverse architectural styles encompassing encoder-decoder, decoder-only, and more.
- Pioneering new architectural patterns.
- Offering models in varied sizes, ranging from 3 billion parameters to 20 billion and even more.

### Training
- IBM's proprietary "Learning to Grow" (LiGO) technique propounds modular training.
- Championing eco-friendly training techniques.
- Leveraging the Vela supercomputer for training tasks.
- A continual quest for refining alignment methodologies.



