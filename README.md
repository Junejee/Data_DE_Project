Connect the Dots with End-to-end Data Engineering Project
ประยุกต์ใช้ความรู้ตลอดทั้ง Bootcamp มาลงมือทำจริงผ่านโจทย์ปัญหาทางธุรกิจแบบ End-to-end ตั้งแต่ การดึงข้อมูล การจัดเก็บข้อมูล การแปลงข้อมูล จนไปถึงการนำข้อมูลมาที่ได้มาใช้ในการแก้ไขปัญหาต่าง ๆ


<img width="2172" height="930" alt="image" src="https://github.com/user-attachments/assets/41b3925c-7551-4bc9-8cfd-f9a790d4a25a" />








End-to-end Project

Starting Airflow
Before we run Airflow, let's create these folders first:

mkdir -p ./dags ./config ./logs ./plugins ./tests ./dbt ./pyspark ./spark-events
On Linux, please make sure to configure the Airflow user for the docker-compose:

echo -e "AIRFLOW_UID=$(id -u)" > .env
See Setting the right Airflow user for more detail.
