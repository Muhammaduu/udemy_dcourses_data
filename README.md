udemy_dcourses_data
Project Overview:

This project involves the analysis of Udemy course data using Python and Pandas. The dataset contains various details of Udemy courses, such as course ID, title, price, number of subscribers, number of lectures, course level, content duration, and subject. The goal is to extract insights and answer specific questions based on the data.

 Dataset:
The dataset contains the following columns:

course_id: Unique identifier for each course.

course_title: Title of the course.

is_paid: Whether the course is paid or free.

price: Price of the course (for paid courses).

num_subscribers: Number of subscribers enrolled in the course.

num_reviews: Number of reviews for the course.

num_lectures: Number of lectures in the course.

level: Course difficulty level (e.g., Beginner, Intermediate, Expert).

content_duration: Total duration of the course content (in hours).

published_timestamp: Date when the course was published.

subject: The subject category of the course (e.g., Business, Design, Development).

## Analysis Performed:
Q1: What are all different subjects that Udemy offers?

Extracted the unique subject categories available on Udemy.
Q2: Which subject has the maximum number of courses?

Identified the subject with the highest number of courses offered.
Q3: Show all paid courses.

Filtered the dataset to display only paid courses.
Q4: Show all free courses.

Filtered the dataset to display only free courses.
Q5: Which are the top 10 selling courses?

Sorted the courses based on the number of subscribers and displayed the top 10 courses.

Q6: Which are the least five selling courses?

Sorted the courses based on the number of subscribers and displayed the bottom five courses.
Q7: Show all Graphic Design courses with less than 100 subscribers.

Filtered the dataset to display all courses under the subject "Graphic Design" with fewer than 100 subscribers.

Q8: List all courses related to Python.

Filtered the dataset to display all courses that have "Python" in the course title.
Q9: What are the courses that were published in 2015?

Filtered the dataset to show courses published in the year 2015.

Q10: What is the maximum number of subscribers for each course level?

Grouped the dataset by course level and identified the maximum number of subscribers for each level (Beginner, Intermediate, Expert).
