# Copybook — Distance-Learning Platform (MERN)

> [!WARNING]
> **DEPRECATED — OLD LEARNING PROJECT (2022).** Archived and no longer maintained. Kept public to show my early progress.
> For my current production work see [my GitHub profile](https://github.com/IgorJs2) — Metrocraft 2036 and Stalcraft LAB.

A Google Classroom-style web app for remote schooling. Teachers create classes, publish materials and homework, and grade answers; students join a class by code, submit homework and track their grades.

## Features
- Sign-up and login with JWT, password change and reset by email (Nodemailer)
- Create, join, leave and delete classes
- Class materials, homework assignments with file uploads (Multer), student answers
- Gradebook with charts (Chart.js)
- UI localization

## Tech stack
| Layer | Technologies |
|---|---|
| Frontend | React, Redux Toolkit, Redux Thunk, React Router, Chart.js, Materialize CSS |
| Backend | Node.js, Express, express-validator, JWT, bcrypt, Multer, Nodemailer |
| Database | MongoDB, Mongoose |
| Design | [Figma mockup](https://www.figma.com/file/qEtqRSHn6WyigFe7ELyVDj/Copybook?node-id=0%3A1) |

## Run locally
```bash
git clone https://github.com/IgorJs2/CopybookSite.git
cd CopybookSite
npm run modules      # installs client and server dependencies
# set your MongoDB URI in server/config/default.json
npm run start
```

> Credentials that appear in old commits belonged to throwaway test databases and are no longer valid.
