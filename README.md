# 📄 Research Paper Summary

A simple AI-powered system to summarize research papers using **LangChain, FAISS, and Hugging Face embeddings**.

## 🚀 Features
✅ Loads PDFs  
✅ Splits text for better processing  
✅ Uses **FREE** embeddings (HuggingFace)  
✅ Stores vectors in FAISS  
✅ Supports semantic search & Q&A  

## 🔧 Installation
1. **Clone this repo**:
   ```bash
   git clone https://github.com/VinayakGalande01/Research_Paper_Summary.git
   cd Research_Paper_Summary
```

2. Install dependencies:  
pip install -r requirements.txt


---

### **✅ 2. Add Usage Instructions**
Now, tell users how to run the project:

```markdown
## 🚀 Usage
1. Place your research paper PDF in the project folder.
2. Run the script:
   ```bash
   python main.py
query = "What is breast cancer?"
result = db.similarity_search(query, k=3)
print(result[0].page_content)

---
### **✅ 3. Example Output**
```markdown
## 📌 Example Output
**Query:** "What is breast cancer?"  
**Response: *"Breast cancer is a type of cancer that begins in the breast cells. It is commonly estrogen-receptor positive and can be treated with hormonal therapy like Tamoxifen..."*
```
## 🔍 Future Improvements
- Improve response accuracy by increasing chunk size.
- Use more advanced embeddings for better semantic understanding.
- Build a simple UI for easy access.

touch README.md

git add README.md
git commit -m "Added README with installation & usage guide"
git push origin main

