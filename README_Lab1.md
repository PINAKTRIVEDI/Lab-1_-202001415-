Q.1.The institute has been recently set up to provide state-of-the-art research facilities in the
field of Software Engineering. Apart from research scholars (students) and professors, it also
includes quite a large number of employees who work on different projects undertaken by
the institution. As the size and capacity of the institute is increasing with the time, it has been proposed to
develop a Library Information System (LIS) for the benefit of students and employees of the
institute. LIS will enable the members to borrow a book (or return it) with ease while sitting
at his desk/chamber. The system also enables a member to extend the date of his borrowing
if no other booking for that particular book has been made. For the library staff, this system
aids them to easily handle day-to-day book transactions. The librarian, who has
administrative privileges and complete control over the system, can enter a new record into
the system when a new book has been purchased, or remove a record in case any book is
taken off the shelf. Any non-member is free to use this system to browse/search books
online. However, issuing or returning books is restricted to valid users (members) of LIS only.
The final deliverable would be a web application (using the recent HTML 5), which should
run only within the institute LAN. Although this reduces security risk of the software to a
large extent, care should be taken no confidential information (eg., passwords) is stored in
plain text.


Answer:- Identifying the Functional and Non-Functional Requirements:

Functional Requirements:-

1.) A system should allow the librarian to add and remove new members.

2.) A system should allow the user to search for the books in the library based on the title, Author, Publication date, etc of the book according to their requirements.

3.) A system should show all the necessary details of the book to all the users whether a member or a non-member.

4.) The LIS system should allow a member to request, reserve, renew, or return a book if already borrowed. The member's request for borrowing a book should first be acknowledged by the librarian, and then the book can finally by borrowed by him/her.

5.) A system should ask for the username and password when a user wants to issue the book. The system checks whether the entered credentials match i.e. Password is correct or not, or whether the entered username exists or not.

6.) Librarian can add and manage the books.

7.)System should notify the user and librarian of the overdue books and calculate the fine for the overdue books when they are returned.

8.) The system should calculate the fine for overdue books on their return.

9.) After the book is borrowed, the system would show the location of the book in the library.

10.) If the book is already borrowed by any other user, then the system should not give an option of borrowing to the user and tell the user that the book is not available at the moment.

11.) For a particular user, the system should display a list of the currently borrowed books, books borrowed in the past, date of borrowing and returning books if the user wants the details of the history.

12.) The system should allow the librarian to enter a new record into the system when a new book has been purchased, or remove a record in case any book is taken off the shelf as and when required.

13.) For security, the system should ensure that the password is not completely plain text, and is 8 to 26(for example) characters long.

Non-Functional Requirements:-

1.) Accessibility:- The proposed system would be a GUI-based desktop application installed on the computing root node (server) running the application.

2.)  Ease of use - The system should make sure that the user can get relevant information with ease. The UI should be simple enough to be understood by everyone. It can be made even easy if there is provided an option for choosing different languages. 

3.) Accuracy - The system should ensure that the data stored about the books, and the fines calculates should be correct and consistent. 

4.) Maintainability - Updating information on the system should be made as easy as possible. The current system should work properly even if any changes are made. In case the system is required to be updated with new features, it should work properly.

5.) Performance - The system should respond to requests within two to three seconds.

6.) Reliability - The system should be available for the duration when the library operates. There should not occur any failure in the system during this particular time.

7.) Scalability - The system should not give an error and work reliably when more users are accessing the system.

8.) Portability -  It is possible to access the database in any system other than the system in which it is created.

9.) Security - The system would ask a user for a username and password for entering into the system. It should also make sure that it works on the institute LAN.

Q.2. Identify scope, features and non-functional aspects of the following problem.
Approximately 5% of the world population (or a staggering 466 million people) suffers from
disabling hearing loss. We set out to create an impactful solution for this community that
addresses some of their everyday needs. Our mobile application uses artificial intelligence to
recognize key sound events of interest to this community, such as car horns and babies,
where immediate alerts and continual logging are critical for the user. This app is optimized
for Android with low-latency so that it works in real-time for use.

Answer:- 

Scope:-
There are people in our society who are unable to communicate due to their hearing disability. A deaf person cannot live alone, it requires another person to support them. This application helps them to communicate with the outside world.

 Functional Requirements

1.) The system should ask to choose the resulting tone, e.g. bell tone, or car horns when a user wants immediate alerts.

2.) The system should also allow a choice of the output type i.e. whether it wants the output in the form of tone, vibration, or both tone and vibration.

3.) The system should allow editing, and deleting voice information, voice types, etc.

4.) The system should allow the user to choose between more than one voice requirement as a resulting tone for voice recognition.

5.) Users should choose where to send the information(alert) whether by telephone, email, or both.


Non - Functional Requirements

1.) The system should recognize any voice in the list without any fault. The Response of the system should be fast and error-free and the performance of the system should not decrease by time or usage.

2.) The system should be easy to learn and easy to use. It can provide a help page to all new users to make proper use of the system.

3.) The Admin and the user should get notified in case any error or system failure occurs.

4.) The system should support addition of new voices without changing old ones.

5.) The response time of any query should be small to make sure it fulfills the needs.

6.) The system should be compatible with all mobiles capable of running Android/IOS Programs.

7.) UI should be user-friendly and attractive and it should contain a lot of expressive images.
