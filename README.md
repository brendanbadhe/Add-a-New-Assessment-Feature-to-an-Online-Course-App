# Online Course App - Assessment Feature

This repository contains a Django-based Online Course application, enhanced with a new assessment feature. The project demonstrates full-stack development skills by integrating models, templates, and views for course exams and submissions.

## Features

- **Question, Choice, and Submission Models**: Models for exam questions, possible choices, and user submissions.
- **Admin Integration**: Create and manage courses, lessons, questions, and choices via the Django admin site.
- **Course Details & Exam Section**: Course detail page displays lessons and an exam section with questions and choices.
- **Exam Submission & Evaluation**: Users can submit exam answers; results are calculated and displayed with pass/fail feedback.
- **Bootstrap UI**: Modern, responsive templates for course details and exam results.

## Setup Instructions

1. **Clone the repository**

   ```
   git clone https://github.com/brendanbadhe/Add-a-New-Assessment-Feature-to-an-Online-Course-App.git
   cd Add-a-New-Assessment-Feature-to-an-Online-Course-App
   ```

2. **Install dependencies**:

   ```
   pip install -U -r requirements.txt
   ```

3. **Run migrations**:

   ```
   python manage.py makemigrations
   python manage.py migrate
   ```

4. **Create a superuser**:

   ```
   python manage.py createsuperuser
   ```

5. **Start the development server**:

   ```
   python manage.py runserver
   ```

## ER Diagram

The following ER diagram illustrates the relationships between models for the assessment feature:

![Onlinecourse ER Diagram](static/media/course_images/onlinecourse_app_er.png)
