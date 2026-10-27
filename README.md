# HealthAI Projects

A collection of AI-based healthcare projects developed to explore automated health report analysis, medical parameter interpretation, pattern recognition, and personalized health recommendations.

## 📌 Projects Included

### 1. HealthAI Milestone 1 — Data Ingestion and Parameter Interpretation
- Extracts health parameters from blood reports.
- Supports report processing and parameter standardization.
- Interprets parameters using reference ranges.
- Identifies normal, high, and low values.

### 2. HealthAI Milestone 2 — Pattern Recognition and Context Awareness
- Extends the initial health report analysis workflow.
- Identifies patterns across extracted health parameters.
- Adds context-aware analysis and risk identification.
- Includes integration and testing components.

### 3. HealthAI Milestone 3 — Health Recommendations
- Extends the HealthAI project with a diabetes-related component.
- Includes recommendation and synthesis modules.
- Organizes evaluation resources and example inputs.

### 4. Streamlit Gemini Health Diagnostics
- Provides a Streamlit interface for uploading blood reports.
- Supports PDF, PNG, and JPG report inputs, depending on implementation.
- Uses Google's Gemini AI for report analysis and interactive questions.
- Includes an option to chat about an uploaded report.

## 🛠️ Technologies Used

- Python
- Streamlit
- Google Gemini API
- OCR and document processing tools
- Image and PDF processing libraries
- AI-based health parameter interpretation

## 📂 Repository Structure

The ZIP archive contains the following projects:

```text
HealthAI-Projects/
├── infosys.zip
│
├── Milestone1_HealthAI_Project/
├── Milestone2_HealthAI_Project/
├── HealthAI_Milestone3_Final_With_Diabetes/
└── Streamlit_Gemini_Health_Diagnostics/
```

*Note: The folders above describe the contents of the ZIP archive. They will appear as separate folders on GitHub only after you extract and upload them individually.*

## 🚀 Running the Streamlit Gemini Project

### Prerequisites
- Python installed
- pip package manager
- A valid Google Gemini API key

### Installation

1. Download or clone this repository.
2. Extract `infosys.zip`.
3. Open the `Streamlit_Gemini_Health_Diagnostics` folder in a terminal.
4. Install the dependencies:

```bash
python -m pip install -r requirements.txt
```

5. Create a `.env` file in the project folder and add your API key:

```text
GEMINI_API_KEY=your_gemini_api_key
```

Replace `your_gemini_api_key` with your own valid API key. Never publish your real API key.

6. Run the application:

```bash
python -m streamlit run app.py
```

7. Open the local URL displayed in the terminal, usually `http://localhost:8501`.

## 🔐 Security

- Do not upload `.env` files or API keys to GitHub.
- Do not commit private medical reports or personal health information.
- Use sample or anonymized reports for testing.

## ⚠️ Disclaimer

This project is intended for educational and research purposes only. AI-generated health interpretations are not a substitute for professional medical advice, diagnosis, or treatment. Consult a qualified healthcare professional for medical decisions.

## 👩‍💻 Author

**Manogna Mandaloju**

B.Tech — Information Technology

## 📄 License

No license has been specified yet. Add a license file if you intend to allow others to reuse, modify, or distribute this project.
