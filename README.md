# Sathyabama Marks & GPA Calculator

A mobile-friendly web app that estimates subject marks, grades and semester GPA for **B.E. CSE (AI & ML), Regulations 2023**, at Sathyabama Institute of Science and Technology.

**Live app:** https://cspranavadithya11.github.io/gpa-calculator/

> This is an unofficial student tool. Always confirm results with your department and official grade sheet.

## Features

- Subjects and credits for all 8 semesters
- Separate mark patterns for theory, practical, lab, project, training and skill courses
- Pass / reappear check
- Semester GPA estimate
- Elective and skill course selection
- Installable on your phone and works offline

## How to use

1. Choose your semester.
2. Tap a subject and enter your marks.
3. Tap **Calculate result**.
4. Tap **Add this result to semester GPA** and repeat for other subjects.

## Install on your phone

Open the live app once while online, then:

- **Android (Chrome):** menu > **Install app** or **Add to Home screen**
- **iPhone (Safari):** Share > **Add to Home Screen**

## Marking patterns (out of 100)

| Course type | Internal | External |
|---|---|---|
| Theory | CAE 1 + CAE 2 scaled to 40, assignment to 10 | End semester exam /100 scaled to 50 |
| Theory + Practical | Same as theory (50) | Lab assessment /50 + practical exam /50, scaled to 50 |
| Theory with Project | Same as theory (50) | Project report review /50 |
| Practical | Session-wise /30 + model exam /50 scaled to 20 | Practical exam /50 |
| Physics and Chemistry Lab | /25, scaled to 50 | /25, scaled to 50 |
| Project | Reviews /50 | Viva-voce /50 |
| Professional Training / Internship | None | External review /100 |
| Skill Enhancement | None | Exam /100 |

Mandatory Audit Courses are pass/fail and carry no credits.

## Pass rule and grades

To pass, you need at least **50/100 overall** and at least **30% in the end semester exam**.

| Marks | Grade | Points |
|---|---|---|
| 90-100 | A++ | 10 |
| 80-89 | A+ | 9 |
| 70-79 | B++ | 8 |
| 60-69 | B+ | 7 |
| 50-59 | C | 6 |
| Below 50 | RA | 0 |

**GPA** = sum of (credits x grade points) / sum of credits, counting passed courses only.

## Assumptions to verify

- **Professional Training:** the regulations show 100 external marks, while the curriculum table shows 50 + 50. The app follows the regulations.
- **Theory + Practical:** the 30% minimum is applied to the end semester practical exam.
- **Rounding:** totals such as 89.5 are not rounded up.

## Privacy

No account, database or analytics. Your marks are not saved or uploaded, and they disappear when you refresh or close the page.

## Built with

HTML, CSS and JavaScript, packaged as a Progressive Web App (PWA).

## Author

C S Pranav Adithya ([@cspranavadithya11](https://github.com/cspranavadithya11))