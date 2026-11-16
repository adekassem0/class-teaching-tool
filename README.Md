# ClassMate – Web-based Teaching Tool

> Course: Introduction to Software Engineering (OOP, OOD) | Assignment: Ex2 – Vibe Coding & Deep Designing

## 1. Problem Statement
Current online tools for teaching are fragmented, complicated, and not
LLM-ready. Lecturers and students need a simpler, better tool that works
directly in class, from a smartphone browser, with no installation.

## 2. Goal
Design (and implement a KISS demo of) an end-to-end web application for
teaching in class. This assignment is a **design challenge**; the
implementation is secondary and existing code is preferred.

## 3. Scope

### In scope (features)
1. **Attendance (highest priority):** students mark attendance
   automatically or with minimal effort; the lecturer can estimate attendance
   (e.g., photo of the class + automatic student count) and export an
   online/offline spreadsheet with the details.
2. **Real-time / offline feedback:** students can comment and raise
   suggestions.
3. **Quick polls:** lecturers create on-the-spot (KISS) polls about the
   current material.
4. **ML class-video summary:** summary of a recorded lecture
   (Zoom / Meet / Google Classroom).
5. **Homework deep review (LLM):** students and teachers get a deep review of
   homework, including comparison to other students' work.

### Out of scope
- Integration with Moodle or Zoom
- Personal data (e.g., national ID numbers)

### Requirements
- Works in class as a real live demo
- KISS: a simple, web-based smartphone app for students

## 4. Team / Author
- Name: Adi Kassem
- GitHub: [@adekassem0](https://github.com/adekassem0)

## 5. Tech Stack (draft)
| Layer | Choice |
|---|---|
| Frontend | Responsive web app (HTML/JS) |
| Backend | Python (FastAPI/Flask) |
| Database | SQLite |
| AI | LLM API + computer-vision model for counting |

## 6. Repository Structure (planned)

```text
docs/    - tools report, SoW, SRS, use cases, design, testing, conclusion
src/     - demo application
tests/   - tests
assets/  - diagrams and screenshots
```

## 7. Deliverables & Status
- [x] Repository + README
- [ ] Tools report
- [ ] SoW
- [ ] SRS
- [ ] Use cases
- [ ] Components
- [ ] Class & sequence diagrams
- [ ] Testing strategy
- [ ] Demo implementation
- [ ] In-class demo
- [ ] Conclusion

## 8. Deadline
25/11/2026
