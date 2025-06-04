# วิธี Clone
## ให้โหลดทุกไฟล์ไปจากนั้นรันคำสั่งใน terminal
### สร้าง environment สำหรับติดตั้ง package pip
code/python -m venv venv 
### จากนั้น activate ใช้งาน venv
.\venv\Scripts\activate
### จากนั้นติดตั้ง package
pip install glob2 pandas plotly timm torch streamlit opencv-python
### และรันใน venv เพื่อเปิดเว็บ
python -m streamlit run app.py
