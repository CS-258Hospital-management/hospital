# **IMPLEMENTATION MANUAL**
# **FOR**
# **E – HOSPITAL MANAGEMENT WEBSITE**
 


## CONTRIBUTORS:
1. Likhitha Kyatham (190001032)
2. Mididoddi Mounika (190001036)
3. Panapakala Pooja Sree (190001043)
4. Keren Tudu (190001023)
5. Peddamallu Bhuvana Sree (190001046)
---

# **CONTENTS:**
## 1.GENERAL INFORMATION
### 1.1 SYSTEM OVERVIEW
### 1.2 USER ACCESS REQUIREMENT
### 1.3 DESCRIPTION OF THE WEBSITE

## 2.GETTING STARTED
### 2.1 STEP BY STEP GUIDANCE TO USE WEBSITE

---

#  **1.GENERAL INFORMATION**
## **1.1 SYSTEM OVERVIEW**
E – Hospital Management System is a website which allows users to access a few  functionalities of the hospital, without physically visiting the hospital.This website is exceptionally of great use, especially during this pandemic time, when physically going out is not regarded as a safe option.

## **1.2 USER ACCESS REQUIREMENT**
Everyone can access this website. This website is free to use and everyone can experience the benefits of this website. A good internet connectivity and any operating system such as Windows,Linux,Mac  are the only requirements for accessing this website.

## **1.3 DESCRIPTION OF THE WEBSITE**
Through this website, a user can book appointments for vaccination, book appointments for visiting the doctor, book appointments for diagnosis of Diabetes or Blood Pressure.The user can also see their past medical reports.The user can also view all the medicines available in the pharmacy.

---

# **2.GETTING STARTED**
## **2.1 STEP BY STEP GUIDANCE TO USE WEBSITE**

### **1) LOGIN PAGE**
The very first page which appears on visiting our website is the login/sign up page.
Users can either login into the system by filling some credentials or by signing up, if the user is new.  A user can login into the system by entering his/her User ID and password and then press the login button.
For signing up into the website, the user has to enter User Name, Mobile Number,Email,Password and Address and then press the sign up button.

### **2)USER PROFILE**
After logging into the website, the user can see his/her profile page where the user’s Name,Email,Mobile Number and address will be displayed. Also on the left side of the  navigation bar, the user can see all the tabs which are Doctor,Appointments for Vaccine,Appointments for Diagnosis,Appointments for visiting doctors,Medicines,Past Results,Diabetes,BP and Billing

### **3)DOCTOR PROFILE PAGE**
After clicking on the doctor tab  on the left Navigation bar of User Profile, the doctor profiles page appears. In the doctor profiles page, the user can see all the profiles of doctors with their Name, Doctor ID, Specialization, Availability timing 

### **4)BOOK VACCINE APPOINTMENT PAGE**
After clicking on Appointments for vaccine button  on the left Navigation bar of User Profile, Book Vaccine Appointment Page appears.The user can see the dates available for booking vaccine,choose a date for vaccination and then click on add button.The user has successfully booked appointment for vaccination

### **5)BOOK DIAGNOSIS APPOINTMENT PAGE**
After clicking on Appointments for Diagnosis button  on the left Navigation bar of User Profile,Book Diagnosis Appointment Page appears.The user can enter the Test Name for which he/she wants diagnosis,then the user can select a particular data from available date for appointment and then click on add button.The user has successfully booked appointment for diagnosis

### **6)BOOK DOCTOR APPOINTMENT PAGE**
After clicking on Appointments for visiting Doctor button on the left Navigation bar of User Profile,Book Doctor Appointment Page appears.The user can see the Doctor ID,select a particular date  from available dates for visiting and then click on add button.The user has successfully booked appointment for visiting doctor

### **7)VIEW MEDICINES PAGE**
After clicking on the Medicines button on the left Navigation bar of the User Profile, view Medicines Page appears.The user can see the list of all the medicines including Medicine Name,Medicine ID,Stock Left and Last update of the medicines.

### **8)VIEW PAST RESULTS PAGE**
After clicking on the Past Results button on the left Navigation bar of the User Profile, view Past Results Page appears.The user can see all his/her  past results including Test Date,Test ID,Insulin level,PPSL,Sugar level,Diastolic Pressure and Systolic Pressure

### **9)VIEW DIABETES RESULT PAGE**
After clicking on the  Diabetes button on the left Navigation bar of the User Profile, view Diabetes Result Page appears.The user can see his/her Diabetes Result including Test ID,Test Date,Insulin Level,Sugar Level and PPSL

### **10)VIEW BP RESULT PAGE**
After clicking on the  BP button on the left Navigation bar of the User Profile, view BP Result Page appears.The user can see his/her BP Result including Test ID,Test Date,Diastolic Pressure and Systolic Pressure 

### **11)VIEW BILLINGS PAGE**
After clicking on the  Billings button on the left Navigation bar of the User Profile, view Bills Page appears.The user can see his/her List of Bills paid, Date on which Bills were paid and Amount Paid


## **2.2 STEP BY STEP GUIDANCE TO USE WEBSITE FOR ADMIN(admin in the current context refers to data entry operator)**

### **1) LOGIN PAGE**
As soon as we run the server and the website is opened,we find an option on the page called 'login as admin'.This option allows the admin to login using the credentials like email,password.For now, we have assumed that there is only one admin whose credentials are inbuilt while creating database.

### **2) HOME PAGE**
After the login process,admin is directed to the home page where he/she is shown different options like tests(with a drop down of diabetes,blood pressure),add prescriptions,add billings,add/update pharmacy stock,view profile change requests and change for both users and doctors.

### **3) TESTS PAGE**
If the admin clicks on 'tests' button,a drop-down appears with two options 'diabetes','blood pressure'.These buttons re-direct the user to respective pages where they are provided with forms to filling the data of test results'.For now we have only these two tests for diabetes and blood-pressure.the admin must ensure that the user id exists i.e., the user must be registered within the website or else they'll be redirected to the same page.Else if the forms' data is added successfully then they are shown successful message.

### **4)PATIENT PROFILE**
We have enabled the option for users to request for changes in their profile.Admin can view these requests when presses on the 'patient profile' button and can edit profiles.

### **4)DOCTOR PROFILE**
Admin can process the requests by doctors to change profiles. By using the 'doctor profile' button admin can edit profiles.

### **6)PHARMACY PAGE**
This page helps the admin in maintaining pharma detials.In this page we have two options called 'add,'update' where the admin can either update existing pharma stock using the medicine ID which is alloted uniquely to every medicine while adding or add new pharma with new ID.

### **7)PRESCRIPTIONS**
The admin can add any prescriptions for the existing users prescribed by doctors using user ID and doctor ID.

### **8)BILLINGS**
Admin can add the billing details of existing users for the future refernece by a user using user ID, each billing is given unique billing ID along with billing amount and billing date which can be accessed by user later.

**Thank You for visiting our website**
