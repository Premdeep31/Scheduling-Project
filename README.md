# Scheduling-Project
All the documents related to the Project
Appointment table creation:

create table Appointment (
Id int primary key,
Title varchar,
Appointment_Status varchar(20),
Appointment_Description varchar,
Appointment_Date date,
Start_Time time,
End_Time time,
Physician_Id int,
Patient_Id int,
Modified_Date date,
Modified_User int,
Reason varchar);
