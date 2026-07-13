**🌱 OptiCrop - Smart Crop Recommendation System**


OptiCrop is a Machine Learning based web application that recommends the most suitable crop based on soil nutrients and environmental conditions. It helps farmers make informed decisions by analyzing key agricultural parameters.

**Live Demo**

https://opti-crop-omega.vercel.app

 📌 Features

- Predicts the best crop for cultivation
- Simple and user-friendly interface
- Machine Learning powered recommendation
- Fast prediction using a trained model
- Responsive web design
- Deployed on Vercel

🛠️ Technologies Used

### Frontend
- HTML5
- CSS3

### Backend
- Python
- Flask

### Machine Learning
- Scikit-learn
- Joblib
- Pandas
- NumPy

### Deployment
- GitHub
- Vercel

 📂 Project Structure

OptiCrop/
│
├── static/

│   ├── style.css

│   └── farm.jpg

├── templates/

│   └── index.html

├── crop_model.pkl

├── app.py

├── requirements.txt

├── vercel.json

├── train_model.py

└── README.md

 📊 Input Parameters

The application predicts the best crop using the following inputs:

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature (°C)
- Humidity (%)
- Soil pH
- Rainfall (mm)

⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/Modinianupoju/OptiCrop.git
```

Go to the project folder:

```bash
cd OptiCrop
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate the environment:

 Windows

```bash
venv\Scripts\activate
```

 Linux/Mac

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000
```

🧠 Machine Learning Model

The crop recommendation model is trained using the Crop Recommendation Dataset.

Algorithms used:

- Random Forest Classifier
- Scikit-learn
- Joblib for model serialization

The trained model is stored as:

```
crop_model.pkl
```
 📸 Application Preview

The application provides:

- Input form for soil and weather parameters
- Crop prediction result
- Clean and responsive user interface

📦 Deployment

This project is deployed using **Vercel**.

Deployment URL:

https://opti-crop-omega.vercel.app

 👩‍💻 Author

**Peddehapu Niharika**

GitHub:
https://github.com/Niharika-20-star/Opticrop_project.git


⭐ Future Enhancements

- Weather API Integration
- Fertilizer Recommendation
- Soil Health Analysis
- Crop Yield Prediction
- Disease Detection using Deep Learning
- Multi-language Support
- Mobile Application

 📄 License

This project is developed for educational purposes.
