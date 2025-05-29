# 🧠 **CS 487: Machine Learning and Adversarial Attacks** 🔐

## 📚 **Learning Outcomes**
By the end of this course, you will:
- ⚡ Identify vulnerabilities of machine learning models to various types of **adversarial attacks**.
- 🔍 Differentiate between **white-box** and **black-box** adversarial evasion attacks and understand **data poisoning attacks**.
- 🛡️ Explain the fundamentals of **adversarial privacy attacks** and outline **privacy-preserving defense** methods.
- 🚨 Describe **jailbreak attacks** on large language models and propose corresponding **mitigation methods**.
- 🔐 List common **defense strategies** against adversarial attacks and discuss approaches to improve the robustness of ML models.
- 🖥️ Identify the unique characteristics of adversarial attacks in **cybersecurity** settings.
- 💻 Implement adversarial attacks and defenses for **conventional and deep learning models**.
- 🧩 Evaluate adversarial attack effectiveness on **anomaly detection systems**, **network intrusion detection**, **malware classifiers**, and **anti-spam filters**.
- ⚖️ Analyze the **ethical and societal implications** of adversarial attacks and defenses.

---

## 📑 **Assignments Overview**

### **Assignment 1**  
**🚨 White-box Evasion Attacks on Deep Learning Models**  
- Objective: Implement white-box adversarial evasion attacks on deep learning classification models.

---

### **Assignment 2**  
**Part 01**  
**🛠️ White-box Evasion Attacks using PyTorch**  
- Objective: Use PyTorch to craft white-box evasion attacks.

**Part 02**  
**🎯 Transferable Black-box Evasion Attacks**  
- Objective: Implement transferable black-box adversarial attacks.  
- **Dataset**: [Objects.zip](https://drive.google.com/file/d/19uC4H5FRJCoEnBM9QufbeU_xOcPFssN4/view?usp=sharing)

---

### **Assignment 3**  
**Part 01**  
**🔒 Black-box Boundary Attack**  
- Objective: Implement black-box boundary attacks on deep learning classifiers.

**Part 02**  
**💡 Adversarial Training Defense**  
- Objective: Apply adversarial training as a defense method.  
- **Dataset**: [Painting.zip](https://drive.google.com/file/d/10iBXJ21wrdhuYjqDPq6oybF3K4x6m16-/view?usp=sharing)

---

### **Assignment 4**  
**Part 01**  
**📚 NLP Adversarial Attacks**  
- Objective: Implement adversarial attacks on NLP models.

**Part 02**  
**🧩 Jailbreaking Attacks on LLMs**  
- Objective: Learn about and perform jailbreak attacks on large language models.

---

### **Assignment 5**  
**🧪 Backdoor Attacks & Cybersecurity Evasion**

**Part 01: Backdoor Poisoning Attack (50 marks)**  
- Based on the **BadNet** approach using the **SVHN** dataset.  
- Train a VGG-16 model in TensorFlow, add a 4-pixel backdoor trigger to a subset of digit "2" images, and evaluate the poisoned model’s behavior.
- Tasks:
  - Load and visualize the SVHN dataset.
  - Train baseline model (target: >93% test accuracy).
  - Poison training/test data using backdoor trigger.
  - Retrain model on poisoned dataset and evaluate (goal: >90% accuracy on clean and poisoned test sets).
- **Report includes**: training plots, poisoned sample visualizations, performance metrics, and written analysis.

**Part 02: Adversarial Attacks on Network Intrusion Detection (50 marks)**  
- Dataset: **UNSW-NB15** (PCAP-based network intrusion records).
- Tasks:
  - Preprocess data: encode categorical features, normalize, explore distribution.
  - Train models: Logistic Regression, Decision Tree, Random Forest, k-NN, Naïve Bayes, SVM, and a custom neural network (target: >85% accuracy for NN).
  - Implement white-box evasion attacks:
    - FGSM on deep learning and logistic regression models
    - JSMA on deep learning model
  - Compare performance across models and attack types.

- **Report includes**: accuracy comparisons, adversarial sample results, and performance analysis.

---

## 🔗 **Links to Datasets**
- [Objects.zip](https://drive.google.com/file/d/19uC4H5FRJCoEnBM9QufbeU_xOcPFssN4/view?usp=sharing)
- [Painting.zip](https://drive.google.com/file/d/10iBXJ21wrdhuYjqDPq6oybF3K4x6m16-/view?usp=sharing)
- `SVHN_dataset.zip` & `SVHN_labels.csv` (for Assignment 5)
- `UNSW-NB15` dataset (included in Assignment 5 files)
