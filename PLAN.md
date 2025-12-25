# Quiz Master System - PLAN.md

## Scope & Objective
Build a reliable, production-ready quiz tool where admin can create quizzes and user can take them.

## Architacture & Schema
- **Quiz**: `title:string`, `description:text`
- **Question**: `content:text`, `question_type:integer (enum)`,`quiz_id:integer`
- **Option**: `content:string`,`is_correct:boolean`,`question_id:integer`

## Assumptions
- To meet the 2 hours deadline, I'll use a secret URL or a simple "Admin" namespace rather than a full devise setup.

- There will be 2 types of questions which are MCQs and True/False.

- Using tailwind CSS for rapid and production-grade UI.

## Deployment 
- Hosting on Heroku 

## Database
- Using Postgres