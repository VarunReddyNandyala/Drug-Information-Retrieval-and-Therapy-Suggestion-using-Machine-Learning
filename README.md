# Drug-Information-Retrieval-and-Therapy-Suggestion-using-Machine-Learning
# 💊 Drug Information Retrieval and Therapy Suggestion using ML

This project is an intelligent drug information assistant that allows users to search for medicines by their name or composition and get detailed information including:

✅ Manufacturer

✅ Uses / Indications

✅ Side effects

✅ Average review score (calculated from ratings)

✅ Similarity score (based on semantic matching)

The system uses machine learning–based semantic search (Sentence Transformers + FAISS) to retrieve the most relevant drug information from a structured dataset.

# ⚠️ Disclaimer: This project is for educational reference only. It is not medical advice. Always verify with official labels and consult a licensed clinician before using any medicine.
# 🚀 Features

➡️ 🔍 Semantic drug search (handles partial/misspelled queries)

➡️ 📊 Displays manufacturer and review score

➡️ 📝 Expandable cards for clean results

➡️ ⚠️ Side effects & usage shown clearly

➡️ 🌐 Gradio-powered interactive web interface

➡️ 📦 Ready for deployment on Hugging Face Spaces or local run

# 📂 Dataset
The project uses a Kaggle dataset containing the following fields:

➡️ Medicine Name

➡️ Composition

➡️ Uses

➡️ Side_effects

➡️ Manufacturer

➡️ Excellent Review %, Average Review %, Poor Review %
🛠️ Tech Stack

➡️ Python 3.10+

➡️ Gradio (UI interface)

➡️ Pandas (data handling)

➡️ Sentence Transformers (text embeddings)

➡️ FAISS (vector search)
# 📦 Installation & Setup
1. Clone Repository
git clone https://github.com/<your-username>/drug-info-assistant.git
cd drug-info-assistant

2. Install Requirements
pip install -r requirements.txt

3. Run App Locally
python app.py


This will launch the Gradio interface at:
http://127.0.0.1:7860

# 🌐 Deploy on Hugging Face Spaces

1. Create a new Space on Hugging Face

2. Set SDK = Gradio.

3. Upload:

      1. app.py

      2. requirements.txt

      3. dataset CSV file

4. Your app will be permanently available at:

                https://huggingface.co/spaces/<your-username>/drug-info-assistant
# 📊 Example Output
▼ 💊 Paracetamol (500 mg)
    🏭 Manufacturer: XYZ Pharma
    ⭐ Average Review Score: 4.3 / 5
    📌 Usage/Indication: Pain relief, fever
    🩺 Therapy: Not available
    ⚠️ Side Effects: Nausea, liver toxicity (overdose)
    🔢 Similarity Score: 0.873

# ⚠️ Disclaimer

This tool is built only for educational purposes.
It is NOT a substitute for professional medical advice, diagnosis, or treatment.
Always consult a qualified healthcare provider before making medical decisions.
