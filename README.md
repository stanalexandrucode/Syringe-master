## Story

There is a simple forum website which is vulnerable to SQL injection.
First run the starter code and try to hack it! After you managed to break the site your task will be to find and eliminate its vulnerabilities.

## What are you going to learn?

You will learn and practice how to do the following things:
- Attack a site that is vulnerable to SQL injection (Do not try it on a live website!!)
- Defend your site from SQL injection attacks

## Tasks


1. Run the starter code and make an SQL injection attack! You can use any destructive commands (e.g. drop the table) as the database is on your own computer. (In live environment please do not use this kind of attacks!)

    - There is an `attack.txt` in the repo containing the harmful input text that student used for breaking the website with SQL injection.

2. Fix the security hole in the code (correct the code to resist SQL injections). Keep in mind that frameworks usually contain solution for common situations.

    - Student has a secure code which can insert new comments into the `comment` table.
    - When loading the main page comments are showing exactly the way they were typed by the user. (So the website does not remove any parts of the comments when saving.)


## General requirements


None

## Hints

- You can find an sql file with the sample data in the data folder in the git repo. To use it, create a new database for this project and use `psql` to execute the SQL commands in that file.

## Starting repository

> **For your information**: Unfortunately, GitHub Classroom has an unstable service regarding repository creation and imports. If your repository fails to create or there are issues with code imports you can do the following steps:
>
> 1. Wait. Sometimes it gets done after 1-2 hours.
> 2. Write to your mentors to do it manually for you.
>
> In the meantime, we are working on an own solution to replace GitHub Classroom. We plan to have it in the first quarter of 2020.


Click here to clone your own Git repository:
https://classroom.github.com/a/gIlQxqdW

## Background materials

- :exclamation: [SQL injection](https://learn.code.cool/full-stack/#/../pages/web-security/sql-injection)

## Acceptance review

You will need this only at review time, **after** completing the project.
[Use this form](https://forms.gle/tCBkXXvAtHRPDWSj8) to record the review you provide for your peer.