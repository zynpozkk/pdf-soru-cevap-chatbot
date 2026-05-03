# 📄 PDF Soru-Cevap Chatbotu

PDF belgelerini yükleyerek Türkçe sorular sorabilir ve otomatik rapor oluşturabilirsiniz.

![Uygulama Ekran Görüntüsü](screenshot.png)

## 🚀 Özellikler

- PDF yükleme ve metin çıkarma
- Llama 3.1 8B modeli ile Türkçe soru-cevap
- Otomatik Word (.docx) rapor oluşturma
- Gradio ile kullanıcı dostu arayüz

## 🛠️ Kullanılan Teknolojiler

- **Model:** Meta Llama 3.1 8B Instruct (Hugging Face üzerinden)
- **Arayüz:** Gradio
- **PDF İşleme:** pdftotext
- **Rapor:** python-docx, BeautifulSoup
- **Platform:** Google Colab

## ⚙️ Kurulum ve Kullanım

1. Notebook'u Google Colab'da aç
2. Colab Secrets'a şu anahtarları ekle:
   - `GOOGLE_API_KEY` → [Google AI Studio](https://aistudio.google.com)'dan al
   - `HF_TOKEN` → [Hugging Face](https://huggingface.co/settings/tokens)'dan al
3. Tüm hücreleri sırayla çalıştır
4. Gradio arayüzü açılınca PDF yükle, sorularını yaz, Submit'e bas

## 📋 Gereksinimler
gradio
python-docx
beautifulsoup4
openai
pymupdf
markdown

## 📌 Notlar

- API key'lerini doğrudan koda yazmayın, Colab Secrets kullanın
- Her oturum açıldığında PDF'i tekrar yüklemeniz gerekir
