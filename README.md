# final-sa-ISS
group project

# Open first PowerShell window
cd "C:\Users\Yuri Maverick Ibasco\Desktop\college\IS\final 4\backend" cd backend
npm start
venv\Scripts\activate
uvicorn app:app --reload --port 8000

# Open SECOND PowerShell window
cd "C:\Users\Yuri Maverick Ibasco\Desktop\college\IS\final 4\backend" cd backend
npm start
venv\Scripts\activate
python seed_mock_data.py

# Open THIRD PowerShell window
cd "C:\Users\Yuri Maverick Ibasco\Desktop\college\IS\final 4\frontend"  or cd frontend
npm start
