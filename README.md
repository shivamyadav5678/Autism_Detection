# Autism Detection in Children

## Overview
This project is a web-based **Autism Detection System** built using **Python, Streamlit, and SQL**. It utilizes an **SVM (Support Vector Machine) model** to assess early signs of autism in children based on user-input data.

## Features
- **User-friendly interface** using Streamlit.
- **Machine Learning-based prediction** using an SVM model.
- **SQL database integration** for storing responses and predictions.
- **Real-time assessment** with quick results.

## Tech Stack
- **Frontend:** Streamlit
- **Backend:** Python, Flask
- **Database:** SQL
- **Machine Learning Model:** Support Vector Machine (SVM)

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- pip
- Virtual environment (optional but recommended)

### Steps to Install
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/yourusername/autism-detection.git
   cd autism-detection
   ```
2. **Create and Activate Virtual Environment:**
   ```sh
   python -m venv venv
   source venv/bin/activate   # On macOS/Linux
   venv\Scripts\activate      # On Windows
   ```
3. **Install Dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

## Usage
1. **Run the Streamlit App:**
   ```sh
   streamlit run app.py
   ```
2. Open the provided URL in your web browser.
3. Enter the required details for assessment.
4. Click **Submit** to get the autism risk prediction.

## Dataset
The model is trained on an autism screening dataset containing behavioral and demographic responses from children. Features include age, gender, and responses to autism-related questions.

## Model Training
1. Preprocess the dataset (handling missing values, encoding categorical features).
2. Train the **SVM model** on labeled data.
3. Save the trained model using `joblib`.

## Future Improvements
- Enhance the UI/UX.
- Improve model accuracy with deep learning approaches.
- Deploy on cloud services like AWS or Render.
- Add multilingual support.

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests.

## License
This project is licensed under the MIT License.



