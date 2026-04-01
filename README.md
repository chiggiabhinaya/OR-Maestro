 OR Surgery Scheduling Optimization

 Project Overview
This project focuses on optimizing hospital operation room (OR) scheduling using constraint programming. The goal is to efficiently assign surgeries to available operating rooms while minimizing total time and avoiding overlaps.



Objectives
- Optimize surgery scheduling
- Reduce idle time in operating rooms
- Prevent scheduling conflicts
- Improve hospital efficiency



Technologies Used
- Python
- OR-Tools (Google Optimization Library)
- Pandas
- Power BI (Dashboard)



 Methodology
1. Data preparation using pandas
2. Constraint model built using OR-Tools CP-SAT
3. Scheduling optimization applied
4. Output stored in CSV format
5. Visualization created using Power BI



 Output
- Optimized surgery schedule
- Start and end time for each surgery
- Room allocation



 Dashboard
<img width="1329" height="749" alt="dashboard" src="https://github.com/user-attachments/assets/d14c941a-9b7b-42d8-9bb3-710a9d98fa38" />



How to Run
```bash
pip install ortools pandas
python model.py
