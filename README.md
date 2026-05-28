#  BloodBridge: Optimizing Lifesaving Resources using RDS,EC2
 
Blood Bridge represents a transformative step forward in the realm of healthcare technology, specifically addressing the inefficiencies and risks prevalent in traditional blood bank management systems. By leveraging a robust, scalable, and secure cloud infrastructure powered by AWS, the platform not only digitizes blood inventory processes but also facilitates real-time coordination among critical stakeholders—donors, hospitals, and administrators. 

This project encompasses: 
•	A web-based interface for donor registration, hospital requests, and inventory dashboards. 
•	Backend services for handling request workflows, role-based access, and data processing. 
•	Integration with AWS cloud infrastructure for compute, storage, security, and analytics. 
•	A scalable and modular architecture to support future enhancements like AI-based demand prediction and mobile app integration. 

4. Significance 
Blood Bridge addresses the following pressing issues: 
•	Emergency blood shortages due to poor visibility and coordination. 
•	Manual data management leading to delays and inaccuracies. 
•	Lack of a real-time, secure, and unified system connecting all stakeholders. 
•	Limited technological adoption in small and medium blood centers. 

1.	Application Layer:  
•	Hosted on Amazon EC2 instances •  RESTful APIs using Node.js/Python  
2.	Data Layer:  
•	Amazon RDS: Relational data (users, hospitals) •  Amazon DynamoDB: Real-time blood stock data  
3.	Storage:  
•	Amazon S3: Reports, documents, images  
4.	Authentication:  
•	Amazon Cognito for secure login & session management  
5.	Monitoring:  
•	AWS CloudWatch for system logs  
•	AWS CloudTrail for API access tracking  
Architecture Flow:  
User > API Gateway > Lambda/EC2 > RDS/DynamoDB > S3

Features: 
•	Real-time Inventory Dashboard 
•	Donor Management System 
•	Request Fulfillment Workflow 
•	Role-Based Access (Donor, Hospital, Admin) 
•	Audit Logs and Monitoring 
•	Secure Data Handling 
Benefits: 
•	Faster blood availability 
•	Reduced wastage 
•	Improved emergency response 
•	Seamless coordination between stakeholders 

input :


<img width="759" height="355" alt="image" src="https://github.com/user-attachments/assets/2c629adf-624e-44ce-b8c5-ff0ed75c48db" />











<img width="755" height="350" alt="image" src="https://github.com/user-attachments/assets/95f3b958-0543-47de-91ab-47c0f2b5cdaa" />



vidio link :
https://drive.google.com/file/d/1eEnweue9p__DxKfv8lwQwMRSFZVoMtbA/view?usp=sharing



  

