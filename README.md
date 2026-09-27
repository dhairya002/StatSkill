# StatSkill

> An AI-powered competency assessment system for India's Official Statistical System.

## Problem

Training programs for the Official Statistical System need a better way to assess whether officers have developed the required competencies.

A simple assessment score does not clearly show which specific skills an officer is weak in. Without competency-level analysis, it becomes difficult to identify the right training needed to improve those skills.

## Solution

StatSkill is an AI-powered competency assessment system that converts training material into multiple-choice assessment questions.

Each question is mapped to a specific competency. After the assessment, the system analyzes the results, identifies competency gaps, and recommends relevant training courses to help close those gaps.

## Features

- Upload PDF or text-based training material
- Generate competency-based multiple-choice questions
- Map questions to specific competencies
- Conduct an interactive assessment
- Calculate the overall assessment score
- Analyze performance across competency domains
- Identify competency gaps
- Recommend relevant training courses
- Export questions in QuML format
- Built-in sample questions as a fallback when AI generation is unavailable

## How It Works

1. **Upload Training Material** - Upload a PDF or text document.
2. **Generate Questions** - StatSkill reads the material and generates multiple-choice questions.
3. **Map Competencies** - Each question is tagged with the competency it assesses.
4. **Take the Assessment** - The learner answers the generated questions.
5. **Analyze Results** - The system calculates the overall score and domain-level performance.
6. **Identify Gaps** - Areas below the defined threshold are identified as competency gaps.
7. **Recommend Training** - Relevant courses are recommended based on identified gaps.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Google Gemini API
- PDF.js
- QuML / Sunbird assessment format



## SIH Problem Statement

**Problem Statement ID:** SIH26101

**Ministry:** Ministry of Statistics and Programme Implementation

**Hackathon:** Smart India Hackathon 2026

StatSkill is a prototype addressing the competency assessment requirements described in the SIH26101 problem statement.

## Team

**Team:** DevOOPS

**Institution:** Oreintal College Of Technology(OCT)

**Branch/Section:** CSE-B

**Year:** First Year

**Author:** Dhairya Agrawal


## Future Scope

- Connect StatSkill with live iGOT Karmayogi course catalogues
- Integrate live NSSTA training content
- Replace placeholder course links with direct course links
- Add secure backend-based AI API integration
- Add user authentication and role-based access
- Store assessment history and competency progress
- Provide dashboards for trainers and administrators
- Expand the competency framework and question bank
- Improve AI-generated question quality through expert review
