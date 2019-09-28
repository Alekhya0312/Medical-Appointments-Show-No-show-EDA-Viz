# Medical-Appointments-Show-No-show-EDA-Viz

<b>Data Source :</b> Kaggle(https://www.kaggle.com/joniarroba/noshowappointments)<br>
<b>Kaggle Kernel of this notebook :</b> https://www.kaggle.com/alekhyabotta/medical-appointments-show-no-show-eda-viz

<h1>About the Data Set:</h1>

The dataset contains a list of patients suffering from one or more of hypertension, diabetes, alcoholism and handicap, all of them binary variables, along with patient information (gender, age, neighbourhood) and information about appointment and scheduling times. There is also a no_show column which tells us if the patient visited the doctor.

Dimensions - 110527 rows, 14 columns


<h1>Variables:</h1>

PatientId(Int) - Identification of a patient<br>
AppointmentID - Identification of each appointment<br>
Gender(Nominal) - Male/Female<br>
ScheduledDay(DateTime) - The day someone called or registered the appointment<br>
AppointmentDay(DateTime) - The day of the actual appointment<br>
Age(Continous)-How old is the patient<br>
Neighbourhood(Nominal) - Locality of the patient/clinic<br>
Scholarship(Boolean) - 1(Received)/0(Not Received)<br>
Hipertension(Boolean) - 1(Suffering)/0(Not Suffering)<br>
Diabetes(Boolean) - 1(Suffering)/0(Not Suffering)<br>
Alcoholism(Boolean) - 1(Suffering)/0(Not Suffering)<br>
Handcap(Boolean) - 1(Handicap)/0(Not a Handicap)<br>
SMS_received(Boolean) - 1 or more messages sent to the patient - 1(Recieved)/0(Not Recieved)<br>
No-show - True/False<br>

<h1>Business Case</h1>

Analyze data and know the impact of showing for appointments and receiving reminder SMS message. How many patients received an SMS and didn't show? What about the number of those who didn't show but also didn't receive a SMS. What are the other factors that affects the patient's no show?
