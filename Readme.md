# Qur’an Circles Mobile App – Requirements Document

## 1. Introduction

This application facilitates the organization of Qur’an circles (halaqat) and tracks students’ progress in memorization and recitation. The system supports three main actors: **Group Owner**, **Sheikh**, and **Parent**. Students are not direct users but their progress is recorded and monitored.

## 2. Actors

* **Group Owner (Admin)**

  * Manages the group as a whole.
  * Has access to all circles, sheikhs, and student progress within their group.

* **Sheikh (Teacher)**

  * Creates and manages Qur’an circles.
  * Adds and assigns students to his circles.
  * Tracks and edits each student’s progress.
  * Adds daily notes/comments for each student.

* **Parent**

  * Monitors their child’s progress and daily notes.
  * Cannot edit or modify records.

## 3. Functional Requirements

### Group Owner

1. Create, update, and delete Qur’an circles.
2. Add or remove sheikhs.
3. Access and view all student records and notes.
4. Manage parent access to their children’s records.

### Sheikh

1. Create Qur’an circles under a group.
2. Add and remove students to/from a circle.
3. Record student progress (e.g., memorized surahs, recited ayat, excuses for a day, etc...).
4. Edit student progress history when needed.
5. Add daily notes/comments for each student.

### Parent

1. View their child’s progress history.
2. View notes added by the sheikh.
3. Receive updates or notifications about progress changes.

## 4. Non-Functional Requirements

1. **Usability**: Mobile-friendly, simple interface for sheikhs and parents.
2. **Scalability**: Support multiple groups, sheikhs, and parents without performance issues.
3. **Localization**: Arabic and English language support.
4. **Reliability**: Offline-first features for areas with poor internet connectivity.
5. **Portability**: Supports both ios and android


