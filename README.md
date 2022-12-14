# **ChecQPro - Automated Cheque Processing and Fraud Detection**

**INTRODUCTION:** Through this project, we are aiming to automate the process of cheque processing. In order to perform the task of cheque verification, we have developed a tool which acquires the cheque leaflet key components, essential for the task of cheque clearance using image processing and deep learning methods. These components include the bank branch code, cheque number, legal as well as courtesy amount, cheque date, account number, and signature patterns. 

## **Screenshots:**

### **Key Parameters of a Cheque**

**Account Number**

![image](https://storage.googleapis.com/cheque_info/1663672152352cq_account_num.jpg)

**Legal Amount**

![image](https://storage.googleapis.com/cheque_info/1663672152352cq_amount_in_words.jpg)

**Courtesy Amount**

![image](https://storage.googleapis.com/cheque_info/1663672152352cq_figure.jpg)

**Cheque Number**

![image](https://storage.googleapis.com/cheque_info/1663672152352cq_cheque_num.jpg)

**Cheque Date**

![image](https://storage.googleapis.com/cheque_info/1663672152352cq_date.jpg)

### **User Interface:**

![Screenshot (19)](https://user-images.githubusercontent.com/84037608/191278193-06a6d682-92b5-4ae4-a5a2-3fe3763fce29.png)

![Screenshot (20)](https://user-images.githubusercontent.com/84037608/191279204-5c03868d-1e9c-4b3c-aacc-fe57351a3188.png)

![Screenshot (21)](https://user-images.githubusercontent.com/84037608/191278176-58112a28-d607-4df3-8b4c-00976190ede3.png)

![Screenshot (22)](https://user-images.githubusercontent.com/84037608/191278183-bdcb68ec-95c9-46bc-aba9-94c1d4740e31.png)

![Screenshot (23)](https://user-images.githubusercontent.com/79203522/206662596-05990c08-60dc-46be-9b22-153047a260b3.png)

Tested the system:

![Screenshot (24)](https://user-images.githubusercontent.com/84037608/191279304-d73410b7-f218-47b6-9cad-7e5830d4ff28.png)

![Screenshot (25)](https://user-images.githubusercontent.com/84037608/191278208-9daf47b9-1ad7-46c0-91cc-5a92c8132d62.png)

### **MongoDB Database:**

![db](https://user-images.githubusercontent.com/58003520/191287127-c56ebbe3-fbce-4f16-8b22-ec4a82368648.jpg)

![db1](https://user-images.githubusercontent.com/58003520/191287139-496d0993-2b1f-44a7-81dd-e30cd9e8ad3e.jpg)

![db2](https://user-images.githubusercontent.com/58003520/191287143-acd61067-3e56-4444-86d8-c93745f42dce.jpg)

# Instructions:

## Prerequisites:
    1. Python3 should be installed on the system.
    2. Need an active internet connection.

## To run the project locally, follow the following steps:
    1. Setup a virtual environment:
        For ubuntu:
            1. sudo apt install virtualenv
            2. virtualenv -p python3 name_of_environment
            3. To activate: source name_of_environment/bin/activate
        For windows:
            1.	pip install virtualenv
            2.	python -m venv <path for creating virtualenv>
            3.	To activate: <virtualenv path>\Scripts\activate

    2. Clone the repository: git clone https://github.com/ekarth/AutomatedChequeProcessing
    3. Change the directory: cd AutomatedChequeProcessing
    4. Install the requirements: pip install -r requirements.txt
    5. Create service account on Google Cloud Platform and enable Vision API service.
    6. Create private key for the service account in JSON format.
    7. Rename JSON file to chequeprocessing.json and place the file in the root of the project.
    8. Follow official documentation to install Google Cloud SDK (refer https://cloud.google.com/sdk/docs/install-sdk).
    9. Run the server: python3 app.py
    
## ChecQPro Express Application:
  - This Flask app uses the ChecQPro Application as the **Frontend**, **Backend** and **Database** of the project.
  
## Please find the working video here:
https://drive.google.com/drive/folders/1mE3AYGGbV-LOd1vyaTXn13An6KXTqVv7?usp=share_link
  
  
  
  
  
