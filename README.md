#  Smart Classroom and Timetable Scheduling System

A web-based Smart Timetable Scheduling System built using **Python** and **Flask**.  
This system automatically allocates classrooms and time slots to subjects based on faculty availability and room capacity constraints.

---

##  Features

- Add multiple Teachers
- Add multiple Classrooms
- Add multiple Subjects
- Automatic timetable generation
- Faculty availability & free slot handling
- Classroom capacity validation
- Professional Web UI
- Dynamic form inputs (Add / Remove rows)
- Constraint-based scheduling logic

---

## How It Works

### Information Storage
The system stores structured academic data using:
- Dictionaries (Faculty & Classrooms)
- Lists of Objects (Subjects)

### Information Retrieval
During scheduling, the system:
- Searches faculty availability
- Checks free time slots
- Verifies classroom capacity
- Prevents slot conflicts
- Allocates valid slots dynamically

### Scheduling Rules
1. Faculty must be available
2. Faculty must be free
3. Classroom must have sufficient capacity
4. Time slot must not already be allocated

---

## Technologies Used

- Python 3
- Flask
- HTML5
- CSS3
- Bootstrap 5
- Git & GitHub

---

## Project Structure

```
smart_timetable/
│
├── app.py
├── templates/
│   └── index.html
├── static/
│   └── style.css (optional)
├── requirements.txt
└── README.md
```

---

##  Installation & Setup

### 1. Clone Repository

```
git clone https://github.com/yourusername/smart-timetable-system.git
cd smart-timetable-system
```

---

### 2. Create Virtual Environment

```
python -m venv venv
```

Activate it:

**Windows**
```
venv\Scripts\activate
```

**Mac/Linux**
```
source venv/bin/activate
```

---

### 3. Install Dependencies

```
pip install -r requirements.txt
```

If requirements.txt does not exist, run:
```
pip install flask
pip freeze > requirements.txt
```

---

### 4. Run Application

```
python app.py
```

Open in browser:
```
http://127.0.0.1:5000/
```

---

## Example Input

### Time Slots
```
Mon-9, Mon-10, Tue-9, Wed-10
```

### Faculty
- Name: Jina  
- Available Slots: Mon-9, Mon-10, Wed-10  
- Free Slots: Mon-9, Wed-10  

### Classroom
- LH-17 → 60  
- LH-18 → 40  

### Subjects
- ISR → Faculty: Ujjwal → Students: 35  
- CN → Faculty: Jina → Students: 50  

---

## Concepts Implemented

- Information Storage & Retrieval
- Rule-Based Scheduling
- Constraint Satisfaction
- Web Form Handling
- Dynamic UI Rendering
- Data Validation

---

## Future Scope

- Database Integration (MySQL/PostgreSQL)
- AI-Based Optimization
- Automatic Conflict Alerts
- Export Timetable as PDF
- Multi-Department Support
- Admin Authentication System

---

## Academic Relevance

This project demonstrates:
- Structured data management
- Scheduling algorithm implementation
- Practical use of ISR concepts
- Full-stack web application development

---

##  Developed By

Rahkhuo Edward and Thiyam Chingu Robaartt<br>
National Institute of Technology, Manipur

---

## License

This project is developed for educational purposes only.
