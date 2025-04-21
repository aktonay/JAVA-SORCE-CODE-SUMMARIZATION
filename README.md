# 🧠 Java Source Code Summarization using T5 (Transformer)

This project demonstrates how to use the `T5-small` model from Hugging Face Transformers for summarizing Java source code into human-readable descriptions. It's useful for understanding, documenting, or navigating large codebases.

---

## 📌 Project Highlights

- ✅ Built using the `T5-small` transformer model.
- 📚 Fine-tuned on a dataset of Java code and corresponding summaries.
- ⚡ Accelerated using GPU (if available).
- 💾 Model saving and loading integrated with Google Drive.
- 🔁 Custom PyTorch `Dataset` and `DataLoader` classes for efficient training.
- 🧪 Inference-ready function for real-time code summarization.

---

## 📂 Dataset

The training data is expected in a tab-separated file (`java-train_clean.tsv`) with two columns:

- `code`: Java source code snippet
- `summary`: A brief natural language description of the code's functionality

Example row:

| code | summary |
|------|---------|
| `public int add(int a, int b) { return a + b; }` | Adds two integers and returns the result. |

