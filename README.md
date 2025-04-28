# Medical Prescription Extractor

- **Extract** patient and doctor information using **Google Gemini AI**.

---

## Features

- Automatically **extract**
  - Patient's full name
  - Patient's age
  - Patient's gender
  - Doctor's full name
  - Doctor's license number
  - Prescription date
  - List of medications
  - Additional notes

---

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/punjjs/Phrase-1
   ```
2. **Add data**
   ```bash
   Project 
   ├── examine_image.py
   ├── requirements.txt
   ├── README.md
   └── data/
    └── (Uploaded images here)
   ```
3. **Create and activate `virtual environment`**
   ```bash
    py -m venv myenv
    myenv\Scripts\activate
   ```
4. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

5. **Add your Gemini API Key in `examine_image.py` code**
   ```bash
   client = genai.Client(api_key="")
   ```
   between double quotes add Gemini API Key

7. **Run the `examine_image.py`**
   
   ```bash
   py examine_image.py
   ```
