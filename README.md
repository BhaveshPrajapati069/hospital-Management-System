# hospital-Management-System

-> Languages and Technologies used

1) HTML5/CSS3
2) JavaScript (to create dynamically updating content)
3) Bootstrap (An HTML, CSS, and JS library)
4) XAMPP (A web server by Apache Friends)
5) Php
6) MySQL (An RDBMS that uses SQL)
7) TCPDF (to generate PDFs)



1)The ‘Home’ page consists of 3 modules:

1) Patient Module
2) Doctor Module
3) Admin Module


Patient Module:
      This module allows patients to create their account, book an appointment to see a doctor and see their appointment history. The registration page(in the home page itself) asks patients to enter their First Name, Last Name, Email ID, Contact Number, Password and radio buttons to select their gender.

  1. Book his/her appointment:

      Here, the patients can able to book their appointments to see a doctor. The appointment form requires patients to select the doctor that they want to see, Date and Time that they want to meet with the doctor. The consultancy fee will be shown accordingly to the patient as it was already determined by the doctor.

 2. View patients’ Appointment History:

       the patient can see their appointment history which contains Doctor Name, Consultancy Fee, Appointment Date and Time.


Doctor Module:
      The doctors can login into their account which can be done by toggling the tab from ‘Patient’ to ‘Doctor’.the login form for a doctor. Registration of a doctor account can be done only by admin. We will discuss more about this in Admin Module.Once the doctor clicking the ‘Login’ button, they will be redirected to their own dashboard.
doctor can able to see their appointments which has been booked by the patients.


Admin Module:
      This module is the heart of our project where an admin can see the list of all patients. Doctors and appointments and the feedback/queries received from the ‘Contact’ page. Also admin can add doctor too.Login into admin account can be done by toggling into admin tab of the Home page.

 1. View the list of all patients registered:

      Admin can able to view all the patients registered. This includes the patients’ First Name, Last Name, Email ID, Contact Number and Password.As like in doctor module, admin can also search for a patient by their contact number in the search box.

2. View the list of all doctors registered:

      Details of the doctors can also be viewed by the admin. This details include the Name of the doctor, Password, Email and Consultancy fees. Searching for a doctor can be done by using the doctor’s Email ID in the search box.

3. View the Appointment lists:

      Admin can also able to see the entire details of the appointment that shows the appointment details of the patients with their respective doctors. This includes the First Name, Last Name, Email and Contact Number of patients, doctor’s name, Appointment Date, Time and the Consultancy Fees

4. Add Doctor:

      Admin alone can add a new doctor since anyone can register as a doctor if we put this section on the home page. This form asks Doctor’s Name, Email ID, Password and his/her Consultancy Fees.

5. View User’s feedback/Queries:

      Admin is allowed to view the feedback/Query that has been given by the user in the ‘Contact’ page. This includes User’s Name, Email Id, Contact Number and the message(Feedback/ Query).


