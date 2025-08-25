# Toeicify – TOEIC Listening & Reading Practice Platform

Toeicify is a mini web application designed to help learners master the **TOEIC Listening & Reading** test.
It provides realistic practice tests, progress tracking, flashcards, and personalized study insights, with an admin dashboard for exam management and system monitoring.

---

## Table of Contents
1. [Features](#features)
2. [Tech Stack](#tech-stack)
3. [Deployment](#installation)
4. [Background](#background)

---

## Features

### Authentication & User Management

* User registration and login
* Google OAuth integration
* Password recovery
* Account settings and profile management

### TOEIC Practice

* Take tests by **part** or **full exam**
* Automatic scoring with detailed explanations
* Track progress and review past attempts

### Learning Progress

* Personalized study dashboard
* Performance analytics across sections
* Goal tracking
* View History Exam Attempt

### Flashcards

* Vocabulary view, practice, test with flashcards
* Spaced repetition support
* Manage Vocabulary in Flashcard

### Notifications

* Real-time system notifications via **Firebase Cloud Messaging (FCM)**

### Admin Dashboard
* Manage exam, exam categories, exam part, and question in exam
* User management & role control
* Comprehensive statistics and analytics

---
## Tech Stack

* **Frontend:** [Next.js](https://nextjs.org/), [Tailwind CSS](https://tailwindcss.com/)
* **Backend:** [Spring Framework](https://spring.io/)
* **Database:** [PostgreSQL](https://www.postgresql.org/)
* **Cache:** [Redis](https://redis.io/)
* **Notifications:** [Firebase Cloud Messaging (FCM)](https://firebase.google.com/docs/cloud-messaging)
* **Object Storage:** S3-compatible cloud storage
* **Deployment:** [Docker](https://www.docker.com/), [Docker Compose](https://docs.docker.com/compose/)

---

## Deployment

The application is containerized with **Docker** and orchestrated via **Docker Compose** for easy deployment.

---
## Background
### Home
![Home](./screenshots/home.png)
### Login, Register, Forgot Password
![Login](./screenshots/login.png)
![Register](./screenshots/register.png)
![forgotPassword](./screenshots/forgotPassword.png)
![validateOTP](./screenshots/validateOTP.png)
![changePassword](./screenshots/changePassword.png)
### Search, Do, Submit, Check result Exam
![listExams](./screenshots/listExams.png)
![selectExam](./screenshots/selectExam.png)
![doExam](./screenshots/doExam.png)
![submitExam](./screenshots/submitExam.png)
![completeExam](./screenshots/completeExam.png)
![viewDetailExam](./screenshots/viewDetailExam.png)
![viewDetailExamQuestion](./screenshots/viewDetailExamQuestion.png)

### Profile, history attempt exam User
![historyExam](./screenshots/historyExam.png)
![profile](./screenshots/profile.png)

### Overview progress User
![progress](./screenshots/progress.png)

### Manage, view, practice, test Flashcard
![listFlashcard](./screenshots/listFlashcard.png)
![detailFlashcard](./screenshots/detailFlashcard.png)
![viewFlashcard](./screenshots/viewFlashcard.png)
![learnFlashcard](./screenshots/learnFlashcard.png)
![testFlashcard](./screenshots/testFlashcard.png)

### Admin Overview
![adminOverview](./screenshots/adminOverview.png)

### Manage Exam Category
![mExamCategory](./screenshots/mExamCategory.png)
![addExamCategory](./screenshots/addExamCategory.png)
![editExamCategory](./screenshots/editExamCategory.png)

### Manage Exam
![mExam](./screenshots/mExam.png)
![addExam](./screenshots/addExam.png)
![editExam](./screenshots/editExam.png)

### Manage Exam Detail: exam part, exam question
![mExamDetail](./screenshots/mExamDetail.png)
![mPartExam](./screenshots/mPartExam.png)
![addExamPart](./screenshots/addExamPart.png)
![mQuestion](./screenshots/mQuestion.png)
![viewQuestion](./screenshots/viewQuestion.png)
![addQuestion](./screenshots/addQuestion.png)
![editQuestion](./screenshots/editQuestion.png)
![deleteQuestion](./screenshots/deleteQuestion.png)
