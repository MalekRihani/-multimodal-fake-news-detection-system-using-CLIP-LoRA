# CLIP + LoRA Fine-Tuning for Image-Text Classification (Fakeddit Dataset)

This project fine-tunes OpenAI's CLIP model using LoRA (Low-Rank Adaptation) for fake news detection using the **Fakeddit** dataset — a multimodal dataset with both image and text content from Reddit posts.

---

## 📚 Dataset: Fakeddit

**Fakeddit** is a large-scale dataset for fake news detection and multimodal classification. It contains over 1 million Reddit posts labeled as:

- **Binary**: Real (1) or Fake (0)
- **Multi-class**: satire, misleading, biased, fake, real, etc. (used in 2-way, 3-way, 6-way tasks)

### 🔗 Source:

- [Fakeddit on Hugging Face](https://huggingface.co/datasets/andrew/fakeddit)
- [Original Paper (ICWSM 2020)](https://ojs.aaai.org/index.php/ICWSM/article/view/7347)

### 📁 Format (example from CSV):
| id         | title             | image_url                        | 2_way_label |
|------------|-------------------|----------------------------------|-------------|
| abc123     | "Some headline"   | http://imageurl.jpg              | 1           |

---

## 🧪 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
