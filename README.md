# Tutorly-A-Student-Tutor-Matching-Platform
Tutorly is a no-code web application built on Bubble.io that connects students with tutors. It allows students to post tuition offers and tutors to apply, manage applications, and communicate—all through an intuitive dashboard.
# Tutorly – A Student-Tutor Matching Platform

Tutorly is a no-code platform built using [Bubble.io](https://bubble.io), designed to streamline the process of finding and hiring tutors for academic needs. With a focus on user-friendly design, it enables students to post tuitions and receive tutor applications. Tutors can apply, update their profiles, and interact via chat.

## 🔑 Features

- 🎯 Tuition Posting by Students
- 🧑‍🏫 Tutor Applications & Profiles
- 💬 Built-in Chat System
- 📄 Document Upload & Verification
- 🌆 Area Filtering (e.g., Islamabad neighborhoods)
- 🧠 Custom Workflows (OTP verification, role-based logic)
- 📚 Subject, Field of Study, and Test Option Sets

## 🧰 Built With

- 🔧 [Bubble.io](https://bubble.io) – No-code visual development
- 🧠 Custom Workflows for role & logic management
- 🗃️ Dynamic database structure for users, tutors, students, and tuition data

## ⚙️ Data Types Overview

- **User (Default):**
  - Fields: `email`, `isStudent`, `isTutor`, `linkedStudent`, `linkedTutor`

- **Tutor:**
  - Fields: `User`, `Education Details`, `Teaching Subjects`, `Fields of Study`, `City`, `Documents`

- **Student:**
  - Fields: `User`, `PostedTuitions`, `PersonalDetails`

- **Tuition:**
  - Fields: `Student`, `Subject`, `City`, `Area`, `Description`, `Status`, `TutorAppliedList`, `Image`

- **Conversation/Chat (if applicable):**
  - Fields: `Student`, `Tutor`, `Messages`, `Status`

## 📊 Option Sets

- **Application Status:** `Pending`, `Shortlisted`, `Rejected`, `Accepted`
- **Fields of Study:** `Engineering`, `Medical`, `Business`, `Arts`, etc.
- **Tests:** `IELTS`, `SAT`, `GRE`, etc.
- **Subjects:** `Math`, `Physics`, `Biology`, etc.
- **Cities & Areas:** Currently Islamabad

## 🚀 How It Works

1. **Students** post tuitions.
2. **Tutors** browse and apply.
3. **Students** view applications and can `shortlist`, `accept`, or `reject`.
4. Both can initiate chat once connected.
