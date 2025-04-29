# student-csv

- An AWS EC2 instance (Amazon Linux 2 or Ubuntu)
- Python 3 installed (`sudo yum install python3 -y`)
- A CSV file named `students.csv` in the same directory

1. SH into your EC2 instance 
ssh -i your-key.pem ec2-user@your-ec2-ip
Upload the script and CSV file
From your local terminal:
scp -i your-key.pem analyze_grades.py students.csv
Run the script
python3 analyze_grades.py students.csv 75
