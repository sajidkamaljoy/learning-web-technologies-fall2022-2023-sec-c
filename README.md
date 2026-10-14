# Learning Web Technologies (Fall 2022-2023, Section C)

> **Note:** this project was originally developed under my earlier GitHub account, [sajid43677/learning-web-technologies-fall2022-2023-sec-c](https://github.com/sajid43677/learning-web-technologies-fall2022-2023-sec-c), and was moved to this account in October 2026.

Lab tasks and the course project for the Web Technologies course at AIUB, by Shajid Kamal Joy. The work moves from plain HTML and XML to PHP with MySQL.

## Contents

| Folder | What's inside |
|---|---|
| `LAB TASK MID/` | HTML and XML basics: a form split across pages (name, email, gender, degree, blood group, date of birth), an HTML CV, a two-page HTML site, XML files (`employees`, `products`, `students`), and a PHP login, registration and change-password flow |
| `LAB TASK Final/LAB TASK 1` | PHP product CRUD: add, display, edit and delete |
| `LAB TASK Final/LAB TASK 2` | The same idea restructured with controller, model and view folders |
| `LAB TASK Final/LAB TASK FINAL` | Final lab: admin and user areas, profile and password change, with a `db.php` data layer |
| `Project/` | First version of a **Software Development Management System**: one PHP page per role (admin, client, manager, analyzer, developer, tester, technical writer) storing data in text files |
| `project final/` | The project rebuilt with MVC folders (`controller`, `models`, `views`) and a database. The finished version is in the repo `Software-Development-Management-System`. |

## Tech stack

HTML, CSS, XML, PHP and MySQL, with some JavaScript.

## Run it

1. Install XAMPP (or any PHP and MySQL stack) and copy this folder into `htdocs`.
2. For the database-backed tasks, create the MySQL database and tables the code expects, and set the credentials in the relevant `db.php`. The SQL files are not included.
3. Open the task you want, for example `http://localhost/<folder>/LAB TASK MID/LAB TASK 4/login.php`.

The `HTML` and `XML` tasks need no server. Open them directly in a browser.
