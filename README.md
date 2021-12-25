# Esewa-Task
### create a web app to book an appointment at a bank with following content:
**A page with list of previous bookings and a button for book an appointment.**
**A page to book an appointment with the following details:**
- Name
- Upload a photo/document (Optional)
- Gender
- Email
- Phone Number
- Address
- Message
- Date
- Timeslots (30 mins range like 9:00-9:30am - only within office hours 10:00am to 5:00pm)
- Branch of Visit (Dropdown)
- Term and Condition (must agree to proceed)
Cancel an appointment - the list of appointments should have an option to cancel which must open a confirmation dialog.<br/>
Please use the following link as a point of reference to start. Feel free to add or remove to it. Please do express yourself.<br/>
https://www.figma.com/file/ucab4KgRr2EfSv7rUKtwbI/Mero-Booking?node-id=21%3A141<br/>

Steps:<br/>
Create angular project<br/>
```
ng new merobooking
```
Run app<br/>
```
ng serve -o
```
Add component <br/>
```
ng g c list
ng g c appointment
```
