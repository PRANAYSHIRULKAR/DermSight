# DermSight
Nirmaan Project - 1 AI-powered multimodal triage system that analyzes medical images and patient-reported symptoms to generate explainable, risk-based early healthcare insights.
# DermSight: Pre-Clinical Multimodal Triage System

**Author(s):** Pranay Shirulkar  
**Affiliation:** St. Vincent Pallotti College Of Engineering & Technology 
**Date:** 7th April 2026  

---

## 🧾 Abstract

DermSight is an AI-powered pre-clinical triage system designed to assist in early healthcare guidance by analyzing both medical images and patient-provided text inputs. Patients often struggle to accurately describe visual symptoms, leading to delayed diagnosis or unnecessary clinical visits. DermSight leverages multimodal artificial intelligence techniques combining computer vision and natural language processing to generate risk-based triage insights. The system classifies cases into low, moderate, and high-risk categories while providing explainable outputs such as visual heatmaps and symptom reasoning. The platform prioritizes safety by avoiding direct diagnosis and incorporating human-in-the-loop validation. This approach enhances clinical decision support, reduces healthcare burden, and improves early detection of high-risk cases. The system is designed to be scalable and integrable with telehealth platforms via API-based architecture.

---

## 📌 Introduction

With the rapid growth of telemedicine, patients increasingly rely on digital platforms for initial healthcare consultation. However, one major challenge remains — accurately conveying symptoms, especially for visually identifiable conditions such as skin diseases. Miscommunication often leads to incorrect triage, delayed treatment, or unnecessary hospital visits.

DermSight addresses this gap by combining image analysis with textual symptom understanding to provide early-stage triage assistance. The objective is to improve accessibility, reduce healthcare system overload, and ensure that high-risk patients are prioritized efficiently. By integrating explainable AI and ethical safeguards, DermSight aims to bridge the gap between patients and healthcare providers in a safe and scalable manner.

---

## 📚 Literature Review

Several solutions exist in the domain of AI-based healthcare assistance, including symptom checker applications and image-based diagnostic tools. Traditional platforms like telehealth services rely heavily on manual triage and patient descriptions, which may lack accuracy.

Recent research in multimodal AI has demonstrated improved performance by combining visual and textual data. Models such as Convolutional Neural Networks (CNNs) for image processing and Transformer-based NLP models have shown significant success in healthcare applications. However, most existing systems lack explainability, integration capability, and safety-focused design.

DermSight builds upon these advancements by integrating multimodal learning with explainable outputs and enterprise-ready deployment, addressing limitations in current systems.

---

## ⚙️ Methodology

DermSight uses a multimodal AI pipeline that processes both image and text inputs. The image is analyzed using a convolutional neural network to detect visual anomalies, while the text input is processed using a natural language processing model to extract symptoms. These outputs are combined in a fusion layer to generate a risk score. The system then classifies the case into risk categories and produces explainable outputs such as heatmaps and highlighted symptoms. A safety layer ensures non-diagnostic responses and supports human validation.

---

## 💻 Implementation

### Programming Languages:
- Python
- JavaScript

### Frameworks / Libraries:
- TensorFlow / PyTorch (for AI models)
- OpenCV (for image processing)
- Hugging Face Transformers (for NLP)
- React.js (for frontend UI)
- Node.js / Flask (for backend API)

### Tools Used:
- Visual Studio Code
- Git & GitHub
- Postman (API testing)
- Docker (optional deployment)
- Cloud Platforms (AWS / Azure / GCP)

---

## 📊 Results and Discussion

The system successfully demonstrates multimodal triage capabilities by analyzing both images and text inputs. Outputs include:

- Risk classification (Low / Moderate / High)
- Visual heatmaps highlighting affected regions
- Symptom-based reasoning for transparency

Performance evaluation shows improved accuracy compared to single-modal systems. The explainability feature enhances trust and usability, making it suitable for real-world healthcare applications. The system effectively reduces ambiguity in patient-reported symptoms and supports early intervention.
![1000592174](https://github.com/user-attachments/assets/68ca9a91-8342-47ce-8c33-ab9c36479e81)
![1000592178](https://github.com/user-attachments/assets/5fe72779-6414-46ef-8db2-eca9319db245)
![1000592175](https://github.com/user-attachments/assets/285eb2c1-f103-4d4f-ac49-0a4f5dfb1235)

---

## ⚠️ Limitations

- Limited dataset availability for diverse skin conditions
- Potential bias across different skin tones
- Not a replacement for professional medical diagnosis
- Requires further clinical validation
- Performance may vary with image quality

---

## 🚀 Future Scope

- Expansion to other medical domains (eye, wound care, etc.)
- Integration with real-time telehealth platforms
- Implementation of bias detection and fairness modules
- Deployment in rural and low-bandwidth environments
- Regulatory compliance and clinical trials
- Mobile application development for wider accessibility


---

## ✅ Conclusion

DermSight presents a scalable and responsible AI solution for early healthcare triage. By combining image analysis with natural language understanding, the system improves symptom interpretation and prioritizes patient care effectively. Its explainable and safety-focused design makes it suitable for integration into modern healthcare ecosystems. The project demonstrates the potential of multimodal AI in transforming pre-clinical decision support systems.

---

## 📖 References

[1] Esteva et al., "Dermatologist-level classification of skin cancer with deep neural networks," Nature, 2017.  
[2] Vaswani et al., "Attention is All You Need," 2017.  
[3] WHO Telemedicine Guidelines – https://www.who.int  
[4] https://huggingface.co  
[5] https://opencv.org  

---
