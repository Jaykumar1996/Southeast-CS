# Southeast-CS
The SEMO CS application should provide users with an interactive way to learn about the Computer Science Department at Southeast Missouri State University. It needs to be simple to navigate and easy to find answers to the most common questions prospective students have. The application should include features to make the department look as appealing as possible to possible students. It needs to showcase the accomplishments of students and staff, accreditations, vast curriculums offered, and facilities and resources available to students within the department. 

# API
The Southeast CS API is the primary way of interacting with the database.The API is written in Python 3.7. It is dependent on two frameworks: Django and Django REST Framework. The API is RESTful, constantly running and waiting for requests. It sends and receives data in JSON format. Southeast CS API has 23 endpoints, each of them interacting with the data in the database in a unique way. Here are the 23 endpoints: add-admin, validate-admin, get-all-admins, add-announcement, get-announcement-by-id, get-all-announcements, edit-announcement-by-id, remove-announcement-by-id, add-event, get-event-by-id, get-all-events, edit-event-by-id, remove-event-by-id, add-course, get-course-by-id, get-all-courses, edit-course-by-id, remove-course-by-id, add-contact, get-contact-by-id, get-all-contacts, edit-contact-by-id, and remove-contact-by-id. 

If you need to create new records, edit existing records, or delete existing records, then hitting specific API endpoints is the easiest way of achieving your goals. Both the Southeast CS Admin Panel and the Southeast CS mobile app use the API to interact with the database.
 

