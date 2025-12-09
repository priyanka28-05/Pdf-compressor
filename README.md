🚀 Document Conversion Module
PDF ⇄ Word Conversion Made Simple, Fast & Fun

Welcome to the Document Conversion Module, where your files get a makeover!
Turn PDFs into Word documents or convert Word files into polished PDFs — all inside one sleek interface.

🎯 Features at a Glance
🔄 PDF ➜ Word Conversion

Want to edit a PDF like a normal human?
Now you can.

Extracts and converts PDF text into .docx

Supports multi-page PDFs

Creates clean, structured Word documents

Fast, lightweight, and super simple to use

⚠️ Note: Complex layouts, images, or tables may not fully carry over. Text-focused PDFs work best.

🔄 Word ➜ PDF Conversion

Lock in your formatting with a smooth PDF export.

Converts .docx / .doc to PDF

Preserves formatting as much as possible

Uses Apache POI + XDocReport for high-quality output

Handles even complex Word documents

⚠️ Custom fonts may get substituted if not available on the server.

🎨 Updated & Interactive User Interface
🗂️ New “Document Conversion” Tab

The UI now includes its very own conversion hub:

Choose between PDF → Word or Word → PDF

Intuitive radio button selection

Clean, simple, user-friendly workflow

🔧 Adaptive Upload Area

Depending on your selected conversion:

File upload field adjusts automatically

Shows allowed file types

Clear progress and feedback indicators

📥 Download + Auto-Cleanup

Converted files download instantly

Temporary files are auto-cleaned

Correct content-type mapping for all formats

🛠️ Technical Implementation
🧩 Backend (Spring Boot)

Added Apache POI for Word handling

Integrated XDocReport for PDF generation

New DocumentConversionService

Dedicated REST endpoints for conversion tasks

💻 Frontend (Next.js)

New API routes for document conversion

Conversion direction selection UI

Drag-and-drop file uploads

Clean success / error handling

⚠️ Limitations

Before you try converting your 500-page fancy brochure… here’s the honest truth:

PDF → Word

Focuses on text extraction

Complex elements (tables, images) may not be perfect

Word → PDF

Very advanced Word features may behave differently

Missing fonts may cause slight visual changes

🧪 How to Use

Go to the Document Conversion tab

Select your conversion direction
– PDF ➜ Word
– Word ➜ PDF

Upload your file

Hit Convert

Download your transformed masterpiece
