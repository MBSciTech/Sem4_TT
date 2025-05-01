# Sem4_TT

A responsive, modern web application for viewing college lecture timetables by branch and day for Semester 4.

## Features

- 🎓 View lecture schedules for different branches (A1-A9)
- 📅 Organized by weekdays (Monday-Saturday)
- 🕒 Shows full schedule with proper time slots
- 📱 Responsive design works on desktops, tablets and mobile devices
- 🌙 Dark mode interface for reduced eye strain
- ✨ Modern UI with intuitive navigation
- 🆓 Clearly shows free periods and recess times
- 📊 Today's academic status display (teaching day, test, holiday, etc.)
- 📆 Full semester calendar view with color-coded dates

## Time Slots

The system displays classes in the following time slots:

| Period | Time              | Notes          |
|--------|-------------------|----------------|
| 1      | 8:45 AM - 9:45 AM |                |
| 2      | 9:45 AM - 10:45 AM|                |
| Break  | 10:45 AM - 11:30 AM| Recess        |
| 3      | 11:30 AM - 12:30 PM|                |
| 4      | 12:30 PM - 1:30 PM |                |
| 5      | 1:45 PM - 2:45 PM  | Optional period|

## Data Format

The timetable data is stored in CSV format with the following structure:

```
Branch,Day,Period1,Period2,Break,Period3,Period4,Period5
A1,Monday,KMS-PY-2-406-7,KMS-PY-2-406-7,RECESS,UMS-COA-301,UMS-COA-301,PSK-DM-301
```

Each class entry follows this format:
- `PROF-SUBJECT-ROOM`
- Example: `KMS-PY-2-406-7` means:
  - Professor: KMS
  - Subject: PY-2 (Python)
  - Room: 406-7

## Academic Calendar

The system includes a comprehensive academic calendar for the semester covering:

- 📗 Regular teaching days
- 📝 Test days for all subjects
- 🏖️ Holidays and festivals
- 📚 Reading holidays
- 🏫 Project evaluation periods
- 🔄 Semester breaks

All calendar dates are color-coded based on the type of academic activity.

## Subjects

The timetable covers the following subjects:

- **PY-2**: Python
- **FSD-2**: Full Stack Development
- **TOC**: Theory of Computation
- **COA**: Computer Organization and Architecture  
- **DM**: Discrete Mathematics

## How to Use

1. Visit [https://mbscitech.github.io/Sem4_TT/](https://mbscitech.github.io/Sem4_TT/) or open `timetable.html` in any modern web browser
2. View today's academic status at the top of the page
3. Click on the status panel to view the full semester calendar
4. Select your branch (A1-A9) from the dropdown
5. Navigate through different days of the week using the day buttons
6. View your complete schedule with time slots, professors, subjects, and room numbers

## Setup

The project is built with vanilla HTML, CSS, and JavaScript. No build step or installation is required.

1. Clone the repository:
   ```
   git clone https://github.com/MBSciTech/Sem4_TT.git
   ```

2. Open `index.html` in your browser or deploy the files to any web server

## Technologies Used

- HTML5
- CSS3 with custom properties (variables)
- Vanilla JavaScript (ES6+)
- Font Awesome icons
- CSV data format 
