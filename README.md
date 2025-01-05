# 🧠 Neural-Private-GPT
> **الجيل القادم من أنظمة الذكاء الاصطناعي المحلي - خصوصية كاملة وسيادة بيانات.**

Neural-Private-GPT هو إطار عمل احترافي مبني على تقنيات RAG (Retrieval-Augmented Generation)، يسمح للمؤسسات والأفراد بالدردشة مع مستنداتهم الخاصة (PDF, Docx, TXT) باستخدام نماذج لغوية ضخمة تعمل محلياً بالكامل دون الحاجة للاتصال بالإنترنت.

### 📸 System Interface Preview
<p align="center">
  <img src="https://raw.githubusercontent.com/OMERNAJ-hub/Neural-Private-GPT/main/screenshots/ai1.jpg" width="45%" />
  <img src="https://raw.githubusercontent.com/OMERNAJ-hub/Neural-Private-GPT/main/screenshots/ai2.jpg" width="45%" />
</p>

## ✨ المميزات الرئيسية
- **خصوصية مطلقة:** لا يتم إرسال أي بيانات إلى السحابة أو طرف ثالث.
- **دعم مستندات متنوعة:** القدرة على تحليل وفهرسة ملفات PDF و Excel و Word بذكاء.
- **معالجة محلية سريعة:** دعم كامل لـ NVIDIA CUDA و Apple M-series لسرعة الاستجابة.
- **فهم سياقي عميق:** يستخدم تقنيات Vector Database لاسترجاع المعلومات بدقة.

## 🛠 التقنيات المستخدمة
- **المنطق البرمجي:** Python 3.11, LangChain, LlamaIndex.
- **قواعد البيانات:** ChromaDB / Qdrant.
- **النماذج المدعومة:** Llama 3, Mistral, Groq (Local).

## 🚀 التشغيل السريع
1. `pip install -r requirements.txt`
2. ضع مستنداتك في مجلد `source_documents`.
3. `python run_local_gpt.py`