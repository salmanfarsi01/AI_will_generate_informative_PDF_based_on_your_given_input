🎓 Matched Information to PDF Generator
This Jupyter Notebook generates synthetic foundation data, matches relevant info using a LLM, and exports the matched results to a PDF file.

📌 Features
Generates dummy foundation data (names, locations, fields, funding types, deadlines, contacts).

Uses Google Generative AI (Gemini) to process and match information.

Converts matched results into a neatly formatted PDF.

Useful for prototyping Retrieval-Augmented Generation (RAG) pipelines with PDF output.

⚙️ How it Works
1️⃣ Generate Data:
Uses Faker to create random foundation records with realistic fields.

2️⃣ Upload Data:
Allows uploading a dataset if you have real info.

3️⃣ Query with LLM:
Uses your Google Generative AI API key to match or filter data as needed.

4️⃣ Export PDF:
Takes the matched results and saves them as a PDF report.

🧩 Tech Stack
Python (pandas, faker, fpdf)

Google Generative AI (google-generativeai library)

Jupyter Notebook for easy execution

🚀 Usage
1️⃣ Install dependencies:

pip install pandas faker fpdf google-generativeai python-dotenv
2️⃣ Add your Gemini API Key:
Edit the notebook:
os.environ["GEMINI_API_KEY"] = "YOUR_API_KEY"
3️⃣ Run the notebook step by step.

4️⃣ Get your PDF output!

📁 Output
📄 dummy_foundations_50.xlsx — Generated dummy data.

📑 PDF file — Matched results exported to PDF.

💡 Use Case
A simple prototype for:

RAG pipelines.

Data matching workflows.

Exporting AI-generated summaries.
