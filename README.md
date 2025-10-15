                                                                           # LogicLegends#
🌍 Climate Change Dashboard
📌 Project Title:
Climate Change Dashboard: An Interactive Data Visualization Web Application
________________________________________
🧩 Problem Statement
Climate change is one of the most critical global challenges of our time.
Despite the vast amount of data available about global warming, CO₂ emissions, and environmental degradation, this data often remains unorganized and difficult for the general public to understand.
Most people are aware that the Earth’s climate is changing, but few can visualize the actual impact through data-driven insights.
Decision-makers, students, and activists need an interactive tool to:
•	View real-time trends,
•	Analyze environmental metrics,
•	And understand the urgency for climate action.
________________________________________
🎯 Objective of the Project
The main objective of this project is to develop a user-friendly and interactive web dashboard that displays real-time and historical climate data using clear and meaningful visualizations.
Specific Goals:
•	Collect and organize climate-related data such as CO₂ emissions, global temperature rise, and sea level changes.
•	Build an intuitive dashboard for data visualization using graphs and charts.
•	Enable user interaction such as selecting countries, time ranges, and metrics.
•	Connect a Flask (Python) backend API with a React (JavaScript) frontend.
•	Raise awareness and encourage data-driven understanding of global climate issues.
________________________________________
💡 Proposed Solution
The proposed solution is a full-stack Climate Change Dashboard that integrates:
•	A Flask backend to process and serve climate data from CSV files or databases.
•	A React frontend that dynamically visualizes data through interactive charts and graphs.
The system converts raw data into visual insights such as:
•	Temperature changes over decades,
•	CO₂ emissions by country,
•	Sea level rise trends,
•	Renewable energy usage growth.
This allows users to explore data visually and make informed conclusions.
________________________________________
🌟 Uniqueness of the Project
1.	Interactive Visualization:
Instead of static charts, this dashboard allows users to filter and explore data dynamically.
2.	Real-Time Integration:
The backend API serves updated datasets directly to the frontend via RESTful endpoints.
3.	Full Stack Architecture:
Combines Python’s analytical power (Flask + Pandas) with React’s dynamic UI rendering.
4.	Educational Focus:
Designed to be simple enough for students, yet powerful enough for researchers and policymakers.
5.	Scalability:
The project can be extended to include Machine Learning models for future climate predictions.
________________________________________
⚙️ Technologies Used
🖥️ Frontend:
•	React.js (Vite Framework) — for fast rendering and modular UI components
•	Recharts / Chart.js — for graph and data visualization
•	Tailwind CSS — for responsive design and modern styling
•	Axios — for API communication with the Flask backend
⚙️ Backend:
•	Python Flask — as the web framework for serving APIs
•	Flask-CORS — to handle cross-origin communication between backend and frontend
•	Pandas — for reading, cleaning, and processing CSV data
•	JSON / CSV Files — as the data source
🗄️ Database (Optional):
•	Can later integrate MySQL or MongoDB for large datasets.
________________________________________
🧠 Features Implemented
✅ Dashboard showing global climate indicators
✅ RESTful API with structured endpoints
✅ Real-time data communication between frontend and backend
✅ Country-based and year-based filters
✅ Mobile and desktop responsive design
✅ Error handling and backend health check route
________________________________________
🛠️ Project Setup
Step 1 — Clone Repository
git clone:  https://github.com/zahidali-dev/LogicLegends.git
cd climate_project/climate_project
Step 2 — Run Flask Backend
cd backend
pip install -r requirements.txt
python app.py
Runs on:
👉 http://127.0.0.1:5000
Step 3 — Run React Frontend
Open a new terminal:
cd frontend
npm install
npm run dev
Runs on:
👉 http://localhost:5173
Step 4 — Access Application
Open the dashboard at:
🌐 http://localhost:5173
________________________________________
📊 Example API Endpoints
Endpoint	Method	Description
/api/health	GET	Checks backend status
/api/emissions	GET	Returns CO₂ emission data
/api/temperature	GET	Returns global temperature rise data
/api/sea_levels	GET	Returns global sea level rise statistics
________________________________________
🚧 Challenges Faced During Development
1.	CORS Policy Issues
When connecting React (port 5173) and Flask (port 5000), CORS errors initially prevented API communication.
➜ Solved by installing and configuring Flask-CORS.
2.	Data Cleaning and Formatting
Climate data in CSV format had missing and inconsistent values.
➜ Used Pandas to clean, format, and normalize data for consistent visualization.
3.	Vite Configuration Errors
React with Vite initially failed to load due to path and dependency issues.
➜ Fixed by ensuring correct file paths and reinstalling dependencies (npm install).
4.	Flask Not Recognized Command
Flask command was not recognized in PowerShell.
➜ Solved by adding Python Scripts path to system environment variables and using python -m flask run.
5.	Empty Dashboard Page
Frontend initially showed a blank page due to incorrect linking of the main JSX file.
➜ Corrected the <script> path in index.html and confirmed React build.
________________________________________
📈 Expected Outcomes
•	A fully working Climate Dashboard displaying interactive global statistics.
•	Increased awareness of climate issues through visualized data.
•	Potential integration with predictive ML models for future forecasting.
________________________________________
🔮 Future Improvements
•	Integrate machine learning to predict future climate trends.
•	Add a database for storing large datasets dynamically.
•	Include user authentication for saving personal dashboards.
•	Deploy the application on AWS / Render / Vercel.
________________________________________
👩💻 Developer Information
Developed by or Team Lead: Naaz Ahmed
🎓 Software Engineering Student
📧 Email: naazbaloch957957@gmail.com
📞 Contact: 03093449136
Member 1: Hasnain Ahmed
Member 2: Zahid Ali
________________________________________
📜 License
This project is licensed under the MIT License.
You are free to use, modify, and distribute with proper credit.
________________________________________
🌿 Conclusion
The Climate Change Dashboard project demonstrates how technology can transform raw climate data into meaningful and actionable visualizations.
Through interactive charts and real-time integration, the platform empowers individuals and researchers to understand environmental changes and take informed action against climate change.

