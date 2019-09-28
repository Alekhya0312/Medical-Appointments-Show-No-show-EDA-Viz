# Medical-Appointments-Show-No-show-EDA-Viz


About the Data Set:

The dataset contains a list of patients suffering from one or more of hypertension, diabetes, alcoholism and handicap, all of them binary variables, along with patient information (gender, age, neighbourhood) and information about appointment and scheduling times. There is also a no_show column which tells us if the patient visited the doctor.

Dimensions - 110527 rows, 14 columns


Variables:

PatientId(Int) - Identification of a patient
AppointmentID - Identification of each appointment
Gender(Nominal) - Male/Female
ScheduledDay(DateTime) - The day someone called or registered the appointment
AppointmentDay(DateTime) - The day of the actual appointment
Age(Continous)-How old is the patient
Neighbourhood(Nominal) - Locality of the patient/clinic
Scholarship(Boolean) - 1(Received)/0(Not Received)
Hipertension(Boolean) - 1(Suffering)/0(Not Suffering)
Diabetes(Boolean) - 1(Suffering)/0(Not Suffering)
Alcoholism(Boolean) - 1(Suffering)/0(Not Suffering)
Handcap(Boolean) - 1(Handicap)/0(Not a Handicap)
SMS_received(Boolean) - 1 or more messages sent to the patient - 1(Recieved)/0(Not Recieved)
No-show - True/False
Business Case

Analyze data and know the impact of showing for appointments and receiving reminder SMS message. How many patients received an SMS and didn't show? What about the number of those who didn't show but also didn't receive a SMS. What are the other factors that affects the patient's no show?
