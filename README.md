# Task Manager (Laravel)
A lightweight, full-stack task management dashboard built with LARAVEL and MySQL. It lets a user create, track, and update tasks through a single-page style dashboard — complete with live stats, search, priority filtering, and status toggling — without a page reload for most actions.

Project Code: WST21-PM-2026-SF

Student Name: ALCOS MARY JANE

Course & Year: BSIT2

Database Used: MySQL

# Overview

The app follows a classic Laravel MVC structure: task records are stored in MySQL, served to the Blade view as JSON, and rendered client-side with vanilla JavaScript. All CRUD actions (create, edit, delete, status toggle) talk to Laravel routes via fetch() calls protected by the CSRF token, so the dashboard stays in sync with the database on every change.

# Features
- Add Task – Allows users to create and add a new task.

- View Tasks – Displays all the tasks that have been added.

- Edit Task – Allows users to change or update the details of an existing task.

- Delete Task – Removes a task that is no longer needed.

- Update Status – Allows users to change a task’s status, such as Pending or Completed.

## Setup
1. Clone the repo and run `composer install`.
2. Copy `.env.example` to `.env` and set your database credentials.
3. Run `php artisan key:generate`.
4. Run `php artisan migrate`.
5. Run `php artisan serve` and visit `http://127.0.0.1:8000`.

## Screenshots
<img width="1897" height="941" alt="image" src="https://github.com/user-attachments/assets/c3958b5a-4eb1-4a88-b705-4cb14b29ef02" />
<img width="1898" height="941" alt="image" src="https://github.com/user-attachments/assets/af465e34-b6dd-4cdf-889b-08301d546db2" />
<img width="1900" height="946" alt="image" src="https://github.com/user-attachments/assets/0a5ba386-eb04-456b-a789-b1e4672d23c9" />
<img width="1909" height="987" alt="image" src="https://github.com/user-attachments/assets/15960c9a-a1d2-4273-9139-95a1ae79cf7a" />





