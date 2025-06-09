# knowledge-distillation

Where:
- `CE` is Cross Entropy
- `KLDiv` is Kullback–Leibler divergence between soft predictions
- `T` is temperature to soften logits

---

## 📊 Distillation Variants Included

| Type                           | Description                                       |
|--------------------------------|---------------------------------------------------|
| **Standard KD**                | Hinton-style soft targets                        |
| **Cosine Similarity KD**       | Matches cosine of logits/embeddings              |
| **Intermediate Representation**| Uses hidden feature alignment between models     |
| **Relational KD (RKD)**        | Matches student and teacher relational distances |
| **VQA Distillation**           | Applied on DAQUAR VQA task (language + vision)   |

---

## 📈 Use Cases

- ✅ **ImageNet to CIFAR/Weather distillation**
- ✅ **Multimodal distillation (VQA)**
- ✅ **Teacher/Student baseline performance comparison**
- ✅ **Loss ablation: standard KD vs cosine vs intermediate**

---

## 🚀 Getting Started

### 1. Clone this repo
```bash
git clone https://github.com/melanieyes/knowledge-distillation.git
cd knowledge-distillation
