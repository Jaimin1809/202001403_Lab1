# Jaimin
## Name : Jaimin Baurasi

## Id: 202001403

### Lab :1 

Software Engineering 

### Q.1. Identify FRs and NFRs:
The institute has been recently set up to provide state-of-the-art research facilities in the field of Software Engineering. Apart from research scholars (students) and professors, it also includes quite a large number of employees who work on different projects undertaken by the institution.

As the size and capacity of the institute are increasing with time, it has been proposed to develop a Library Information System (LIS) for the benefit of students and employees of the institute. LIS will enable the members to borrow a book (or return it) with ease while sitting at their desks/chambers. The system also enables a member to extend the date of his borrowing if no other booking for that particular book has been made. For the library staff, this system aids them in easily handling day-to-day book transactions. The librarian, who has administrative privileges and complete control over the system, can enter a new record into the system when a new book has been purchased, or remove a record in case any book is taken off the shelf. Any non-member is free to use this system to browse/search books online. However, issuing or returning books is restricted to valid users (members) of LIS only. The final deliverable would be a web application (using the recent HTML 5), which should run only within the institute LAN. Although this reduces the security risk of the software to a large extent, care should be taken that no confidential information (eg., passwords) is stored in plain text.

### Functional Requirements:
- Members should able to do tasks such as borrowing a book online, returning a book online, able to extend the deadline.
- All of the necessary details about the book must be displayed on a system.
- The system should ask users for their usernames and password when they want to issue a book. The system checks whether entered data is accurate, such as whether a password was accurately entered or whether a username was entered. 
- The system should show this data for a user if they ask for a list of the books they are now borrowing, the books they have previously borrowed, the date they were borrowed, and the books they have returned. 
- The system ought to calculate the fine for the overdue books when they are returned and notify the user and librarian of the overdue books. 
- The librarian should be able to add a newly purchased book and its record to the system. 
- the librarian should be able to remove the book and its record in case any book took off the system. 
- Any non-member should have access to online book searches. 
- The history of transactions ought to be accessible to library employees. 
- Operational member data should be able to be maintained by the system.





### Non-Functional Requirements: 
- The system should be secure so that non-members can't do the borrowing. 
- The system should have a large capacity to store required records of books because of the large number of books and members. 
- The system should be able to respond back quickly to any requested operation. 
- The system should able be to maintain its performance when a large number of members are using System. 
- The system should be able to be within the institute LAN only. 
- The system should recover quickly after the disaster. 

### Q.2. Identify the scope, features, and non-functional aspects of the following problem.
Approximately 5% of the world population (or a staggering 466 million people) suffers from disabling hearing loss. We set out to create an impactful solution for this community that addresses some of their everyday needs. Our mobile application uses artificial intelligence to recognize key sound events of interest to this community, such as car horns and babies, where immediate alerts and continual logging are critical for the user. This app is optimized for Android with low latency so that it works in real-time for use.

### Scope :

- Any non-member should have access to online book searches.
- The history of transactions ought to be accessible to library employees.
- Operational member data should be able to be maintained by the system.
- Android-powered smartphones can use it.

### Features :
- The programme will also operate in the background.
- Incoming sounds will trigger an alert from the application.
- Additionally, the audio recording needs to be properly logged in readable format.
- When the application detects the sounds of urgent circumstances, it will notify the user.
- If a critical emergency is found and the user doesn't answer, notify friends and family.
- Application latency must be very low (2 ms around).


### Non-Functional Requirements:
- Non-functional qualities include user friendliness and accessibility for people with hearing loss.
- Performance and dependability to ensure the app operates in real-time.
- security to protect consumer data and privacy.
- Scalability, which ensures that the product can support many users.
- A range of Android updates and device support.
