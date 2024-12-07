# HR Promotions Prediction System

A **MERN stack** application with integrated **Machine Learning** to assist HR departments in making fair, data-driven promotion decisions. This system ensures bias-free promotions by evaluating employee performance and eligibility criteria, leveraging predictive analytics to enhance decision-making accuracy.

---

## 🛠️ Skills Used
- **MongoDB**: Database for storing employee data and promotion records.
- **Express.js**: Backend framework for API development.
- **React.js**: Frontend library for building the user interface.
- **Node.js**: Backend runtime for server-side logic.
- **Cloudinary**: Cloud service for handling media uploads.

---

## ✨ Features
- **Fair Promotion Decisions**: Ensures unbiased employee evaluations based on data.
- **Predictive Analytics**: Uses machine learning models to predict promotion eligibility.
- **Intuitive Interface**: User-friendly platform for HR teams to review recommendations.
- **Real-Time Media Uploads**: Employees can upload performance reports directly using Cloudinary.

---

## 📂 Project Structure
HR-Promotions-Prediction-System/ ├── client/ # React frontend │ ├── src/ │ ├── public/ │ └── package.json ├── server/ # Express backend │ ├── models/ # Database models │ ├── routes/ # API routes │ ├── controllers/ # Business logic │ ├── config/ # Configuration files │ └── server.js # Main server file ├── ML_Model/ # Machine learning model scripts │ ├── model.pkl # Trained ML model │ ├── preprocessing.py # Data preprocessing scripts │ └── prediction.py # Prediction logic ├── .env # Environment variables ├── README.md # Project documentation └── package.json # Server dependencies

yaml
Copy code

---

## 🚀 How to Run the Project

### Prerequisites
- Node.js
- MongoDB
- Python (for ML integration)
- Cloudinary account

### Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/KaranPrajapati20/CarrerLift.git
Setup Environment Variables

Create a .env file in the server/ directory with the following keys:
makefile
Copy code
MONGO_URI=your_mongo_database_url
CLOUDINARY_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
Install Dependencies

Backend:
bash
Copy code
cd server
npm install
Frontend:
bash
Copy code
cd client
npm install
Start the Application

Backend:
bash
Copy code
cd server
npm start
Frontend:
bash
Copy code
cd client
npm start
Run the Machine Learning Model

Navigate to the ML_Model/ directory and ensure Python is installed.
Install dependencies and run the model server:
bash
Copy code
pip install -r requirements.txt
python prediction.py
Access the Application

Open your browser and navigate to http://localhost:3000.
🧪 Machine Learning Model
Built using Python and Scikit-learn.
Model evaluates employee performance data to predict promotion eligibility.
Pre-trained and integrated into the Node.js backend for seamless operation.
📊 Demo

🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

🌟 Acknowledgments
MongoDB for efficient database management.
Cloudinary for media uploads.
Scikit-learn for machine learning models.
📧 Contact
If you have any questions, feel free to reach out:

Email: prajapatikaran799@gmail.com
GitHub: your-username
markdown
Copy code

### Instructions:
1. Copy the content above.
2. Replace placeholders like `your-username`, `your-email@example.com`, and `link-to-demo.gif` with your details.
3. Save it as `README.md` in your GitHub repository.
