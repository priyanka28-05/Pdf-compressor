# 🚀 Document Conversion Module
### PDF ⇄ Word Conversion Made Simple, Fast & Fun

Welcome to the **Document Conversion Module**, where your files get a makeover!  
Turn PDFs into Word documents or convert Word files into polished PDFs — all inside one sleek interface.

---

## 🎯 Features at a Glance

### 🔄 PDF ➜ Word Conversion
Want to edit a PDF like a normal human?  
Now you can.

- Extracts and converts PDF text into `.docx`
- Supports multi-page PDFs
- Creates clean, structured Word documents
- Fast, lightweight, and simple to use

> ⚠️ **Note:** Complex layouts, tables, and images may not fully convert. Best results with text-heavy PDFs.

---

### 🔄 Word ➜ PDF Conversion
Lock in your formatting with a smooth PDF export.

- Converts `.docx` / `.doc` to PDF
- Preserves formatting as much as possible
- Powered by **Apache POI** + **XDocReport**
- Handles even complex Word documents

> ⚠️ Custom fonts may be replaced if unavailable on the server.

---

## 🎨 User Interface Enhancements

### 🗂️ New “Document Conversion” Tab
- Dedicated tab for all conversion operations
- Choose between **PDF → Word** and **Word → PDF**
- Clean and intuitive radio button workflow

### 🔧 Adaptive Upload Area
- Upload field updates based on selected conversion type
- Shows supported file formats
- Clear progress indicators and feedback messages

### 📥 Download + Cleanup
- Converted files download instantly
- Automatic cleanup of temporary files
- Correct MIME/content-type handling

---

## 🛠️ Technical Implementation

### 🧩 Backend (Spring Boot)
- Added **Apache POI** for Word processing
- Integrated **XDocReport** for Word → PDF conversion
- Introduced `DocumentConversionService`
- New REST endpoints for conversion workflows

### 💻 Frontend (Next.js)
- Added dedicated API routes for document conversion
- UI components for conversion selection
- Drag-and-drop file uploads
- Friendly success/error notifications

---

## ⚠️ Limitations

### PDF → Word
- Focuses on text extraction
- Visual formatting, images, and tables may not be perfect

### Word → PDF
- Advanced Word styles may render slightly differently
- Missing fonts may cause substitution

---

## 🧪 How to Use

1. Open the **Document Conversion** tab.
2. Choose your conversion direction:
   - **PDF → Word**
   - **Word → PDF**
3. Upload the appropriate file.
4. Click **Convert**.
5. Download your freshly converted document.

---

## 💡 Bonus
This module works seamlessly alongside your **file compression features**, making your app feel like a mini Adobe toolkit — minus the subscription. 😄

---

If you want:
- A more professional README  
- A version with GitHub badges  
- Or a README with screenshots  

Just tell me!
