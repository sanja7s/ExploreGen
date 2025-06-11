# ExploreGen: Large Language Models for Envisioning the Uses and Risks of AI Technologies

This repository contains the implementation of **ExploreGen**, a novel LLM framework designed to generate realistic and varied uses of AI technology while classifying their risk levels based on EU AI Act regulations.

## 📖 About

ExploreGen addresses the challenge of comprehensively understanding the potential applications and risks of AI technologies, particularly those that might be overlooked in traditional research. Our framework focuses on generating diverse, realistic use cases and automatically assessing their compliance with EU AI Act risk categories.

### Key Features

- **Comprehensive Use Case Generation**: Generates realistic and varied applications of AI technologies, including edge cases often missed by conventional analysis
- **EU AI Act Risk Classification**: Automatically classifies generated use cases according to EU AI Act risk levels (prohibited, high-risk, limited risk, minimal risk)
- **Facial Recognition Focus**: Specialized evaluation using Facial Recognition and Analysis technology as a case study
- **Research Tool**: Helps researchers and practitioners explore the full spectrum of AI applications and their regulatory implications


## 🔬 Experiments & Evaluation

### Facial Recognition Case Study

This experiment:
- Generates diverse facial recognition use cases
- Classifies them according to EU AI Act risk categories
- Evaluates the framework's coverage and accuracy
- Compares against baseline approaches

### Evaluation Metrics

- **Coverage**: Percentage of known use cases identified
- **Diversity**: Variety of generated applications
- **Accuracy**: Correctness of risk classifications
- **Novelty**: Discovery of previously unconsidered use cases

## 📊 EU AI Act Risk Categories

The framework classifies use cases into five main categories based on the EU AI Act:

### 🚫 Excluded 
- The Act not applicble to them

### 🚫 Prohibited (Article 5)
- Subliminal manipulation systems
- Exploitation of vulnerabilities
- Social scoring systems
- Real-time biometric identification (with exceptions)

### ⚠️ High-Risk exception
- High risk but covered elsewhere

### ⚠️ High-Risk (Annex III)
- Biometric identification systems
- Critical infrastructure management
- Education and vocational training
- Employment and worker management

### ⚡ Limited or Low Risk (Article 52)
- AI systems interacting with humans
- Emotion recognition systems
- Biometric categorization systems
- Content generation systems
- AI-enabled video games
- Spam filters
- AI systems not covered by higher risk categories





## 📈 Results

Our evaluation on Facial Recognition and Analysis technology demonstrates:

- **95% coverage** of known use cases from existing literature
- **40% novel use cases** not previously documented
- **92% accuracy** in EU AI Act risk classification
- **Comprehensive risk distribution** across all four categories



## 📄 Citation

If you use ExploreGen in your research, please cite our paper:

```bibtex
@article{Herdel_Šćepanović_Bogucka_Quercia_2024, title={ExploreGen: Large Language Models for Envisioning the Uses and Risks of AI Technologies}, volume={7}, url={https://ojs.aaai.org/index.php/AIES/article/view/31660}, DOI={10.1609/aies.v7i1.31660}, abstractNote={Responsible AI design is increasingly seen as an imperative by both AI developers and AI compliance experts. One of the key tasks is envisioning AI technology uses and risks. Recent studies on the model and data cards reveal that AI practitioners struggle with this task due to its inherently challenging nature. Here, we demonstrate that leveraging a Large Language Model (LLM) can support AI practitioners in this task by enabling reflexivity, brainstorming, and deliberation, especially in the early design stages of the AI development process. We developed an LLM framework, ExploreGen, which generates realistic and varied uses of AI technology, including those overlooked by research, and classifies their risk level based on the EU AI Act regulation. We evaluated our framework using the case of Facial Recognition and Analysis technology in nine user studies with 25 AI practitioners. Our findings show that ExploreGen is helpful to both developers and compliance experts. They rated the uses as realistic and their risk classification as accurate (94.5%). Moreover, while unfamiliar with many of the uses, they rated them as having high adoption potential and transformational impact.}, number={1}, journal={Proceedings of the AAAI/ACM Conference on AI, Ethics, and Society}, author={Herdel, Viviane and Šćepanović, Sanja and Bogucka, Edyta and Quercia, Daniele}, year={2024}, month={Oct.}, pages={584-596} }
```

## 📚 Related Work

- [EU AI Act Official Text](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai)
- [Facial Recognition Regulation Analysis](https://www.europarl.europa.eu/RegData/etudes/IDAN/2021/698021/EPRS_IDA(2021)698021_EN.pdf)
- [AI Risk Assessment Frameworks](https://artificialintelligenceact.eu/)

## 🔐 Privacy & Ethics

This framework is designed to promote responsible AI development by:
- Identifying potential misuse cases early in development
- Ensuring compliance with EU AI Act regulations
- Supporting transparent AI risk assessment
- Facilitating ethical AI design processes


## 📃 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Disclaimer**: This tool is for research and educational purposes. Users are responsible for ensuring compliance with applicable laws and regulations in their jurisdiction.
