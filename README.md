# Self-Diagnosis-System
The Self-Diagnosis System can help regular people diagnose themselves based on the symptoms that the doctors specified to the system.

Structures used : 
Patient: Fullname, account, age, gender, disease_History (array of disease ID). 
Doctor : Fullname , account, diseases_added (array of disease ID )
Disease: Title, ID, general_info, symptoms (Array of strings), no_patients_diagnosed. 
Account: username, password. 

The system has two lists:
First, Doctor's menu:
(1) Display diseases
(2) View patient with certain disease
(3) Edit info
(4) Add symptom
(5) Add disease
(6) Log out
Second, Patient's menu:
(1) Find out your disease based on your symptoms 
(2) Display symptoms for a certain disease
(3) View diagnosis history
(4) Clear diagnosis history
(5) Log out
 
The Describtion of each menu:
Log In function (Username & Password). The program should know whether the user is a doctor or patient with only the provided username and password. 

o If the username corresponds to a doctor, the following list should be displayed: 
▪ Edit Info 
▪ Add disease 
▪ Add symptom to an existing disease
▪ Display all diseases. 
▪ View Patients with a certain disease 
o If the username corresponds to a patient, the following list should be displayed: 
▪ Find out your disease based on your symptoms 
▪ Display symptoms for a certain Disease 
▪ View diagnosis history 
▪ Clear diagnosis history 

General Notes: 
o All doctors have access to view diseases added by different doctors. 
o In order for a doctor to change / add a symptom, it must be to a disease they added. Otherwise, they don’t have access. 
o To diagnose a patient with a disease they must display at least 60% of the symptoms of that disease.
▪ If no exact disease can be found (with 60% match), the search will display “no exact match found” and the closest disease that matches the symptoms should be displayed under ( related diseases with the matching percentage) 
▪ If the symptoms match 0% of all diseases the search will display no matches found. 
o When a patient is diagnosed, the general info of the disease is shown. 

