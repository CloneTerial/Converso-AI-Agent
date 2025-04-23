
# Converso AI Agent

**Converso** adalah AI Agent yang dibangun dengan model [Qwen 2.5-14B Instruct](https://huggingface.co/Qwen/Qwen2.5-14B-Instruct) serta sistem memori jangka panjang menggunakan FAISS dan embedding semantik. Notebook ini dapat dijalankan langsung di Google Colab dengan dukungan GPU.

---

## Jalankan di colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CloneTerial/Converso-AI-Agent/blob/main/converso.ipynb)

---
## Fitur Utama

- **Model LLM**: Qwen 2.5-14B dengan quantization 4-bit (nf4) menggunakan `bitsandbytes`
- **Embedding Semantik**: Menggunakan SentenceTransformer (`all-MiniLM-L6-v2`)
- **Sistem Memori**: Penyimpanan vektor berbasis FAISS untuk merekam dan mengingat
- **Recall Kontekstual**: Secara otomatis memanggil memori lama yang relevan berdasarkan input terkini

---
