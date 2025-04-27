This project involves processing a dataset of prescription images using an LLM. Follow the steps below to set up and run the project.

Step 1: Clone the Repository
git clone <repository-url>
cd Phrase-1

Step 2: Prepare the Dataset
Phrase-1/
└── data/
    ├── 1.jpg
    ├── 2.jpg
    └── ...
    └── 129.jpg

Step 3: Set Up the Virtual Environment (Windows)
Create a virtual environment:
python -m venv myenv
Activate the virtual environment:
myenv\Scripts\activate


Step 4: Install Dependencies
pip install -r requirements.txt

Step 5: Add Your API Key
genai.Client(api_key="your_api_key_here")

Step 6: Run the Script
python examine_image.py




