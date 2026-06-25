# System Requirements

## Minimum Final Prototype Functionalities

These requirements define the minimum prototype functionalities that each ICT105 student group must address in the final prototype. The requirements are designed to be platform-independent and can align with different project topics, such as booking systems, reporting systems, inventory systems, learning platforms, dashboards, marketplace concepts, reminder systems, service request systems, or other IT-based solutions.

| Req ID | Minimum Prototype Functionality | What Students Must Show in Final Prototype | SmartTimetable Implementation |
| --- | --- | --- | --- |
| **FR-01** | **Clear problem-specific homepage or landing screen** | The prototype must clearly show the project title, target user, problem being solved, and main action the user can take. | Homepage stating "SmartTimetable" with a short line on the PDF timetable problem, target users (students/lecturers), and a "View My Schedule" button. |
| **FR-02** | **Primary user pathway** | The prototype must show how the main user moves through the system from start to finish. Example: open system → submit request → check status → receive result. | Homepage → schedule list → class detail view → (optional) report a mismatch → confirmation. |
| **FR-03** | **User input or data submission feature** | The system must allow users to submit information related to the selected case. Example: report item, book appointment, register event, submit complaint, add inventory, request service. | Report-a-mismatch form where a student flags a class as wrong, cancelled, or moved. |
| **FR-04** | **Data storage or record management** | Submitted data must be stored, displayed, or simulated through a database, spreadsheet, local storage, JSON file, Airtable, Firebase, Google Sheet, or another suitable tool. | Class schedule data and submitted reports stored in a simple database/spreadsheet (e.g. Firebase, Google Sheet, or local JSON). |
| **FR-05** | **View records / information list** | The prototype must allow users or admins to view existing records. Example: list of reports, bookings, products, requests, tasks, items, users, or service cases. | Weekly class schedule list view showing all classes with time, room, and course. |
| **FR-06** | **Search, filter, or category function** | The prototype must include a way to find relevant information. Example: search by keyword, filter by status, category, date, location, type, priority, or user group. | Search/filter by course code or room number. |
| **FR-07** | **Detail view for each record** | Users must be able to open or view more details about a selected item, request, booking, report, product, or case. | Click a class in the list to open its detail view (room, time, lecturer, status). |
| **FR-08** | **Status or progress tracking** | The system must show the status of a record. Example: pending, approved, rejected, completed, claimed, available, in progress, resolved, or closed. | Status label on each class: Confirmed, Room Changed, or Cancelled. |
| **FR-09** | **Admin or manager function** | The prototype must include at least one admin/manager-side function. Example: update status, approve request, edit record, delete invalid record, assign task, or manage submitted data. | Admin (or lecturer) function to update a class's status/details after a report or change comes in. |
| **FR-10** | **Basic validation and error prevention** | The system must prevent incomplete or incorrect input. Example: required fields, valid email format, date selection, duplicate warning, confirmation message, or simple error message. | Required fields on the report form (course, room, issue type); error shown if a required field is left blank. |
| **FR-11** | **Confirmation or feedback message** | After a user submits or updates data, the prototype must show feedback. Example: "Submission successful," "Request received," "Status updated," or "Please complete required fields." | "Report received" message shown after a student submits a mismatch report. |
| **FR-12** | **Dashboard, summary, or simple analytics view** | The prototype must include at least one summary screen. Example: total reports, pending requests, number of users, most common category, monthly submissions, inventory summary, or task status overview. | Simple admin summary showing total reports received and most-reported classes. |
| **FR-13** | **Basic user interface consistency** | Screens must use consistent layout, navigation, labels, buttons, and visual structure. The prototype should look like one complete system, not disconnected pages. | Same layout, color scheme, and navigation bar across homepage, schedule list, and detail view. |
| **FR-14** | **Mobile-friendly or responsive design consideration** | The prototype must show that the interface can reasonably work on a laptop or mobile screen, depending on the selected platform. | Schedule list and detail view tested to remain usable on a phone-sized screen, directly addressing the mobile readability complaint found in Lab 03 evidence. |
| **FR-15** | **Basic privacy and responsible data handling** | Students must avoid unnecessary sensitive data. If user data is collected, the prototype must show basic privacy awareness, such as limited fields, masked sample data, or clear data-use explanation. | Report form only collects class-related fields (course, room, issue type); no unnecessary personal data requested. |
| **FR-16** | **Final prototype traceability** | Every major prototype screen or feature must connect back to the Lab 04 requirements, user stories, and MVP feature list. Students must be able to explain why each feature exists. | Every feature in `/docs/mvp-feature-list.md` is linked to a user story in `/docs/user-stories.md`, which is linked to a requirement here and to evidence in `/docs/problem-notes.md`. |

---

## Minimum Technical Requirement

**SmartTimetable's chosen platform:** Web app prototype using HTML/CSS/JavaScript, with class and report data stored in a simple database or spreadsheet (e.g. Firebase or Google Sheet), consistent with the team's existing web development skills and the feasibility reasoning documented in `/docs/selected-opportunity.md`.

---

## Non-Functional Requirements

While the functional requirements above (FR-01 to FR-16) describe what the system must do, the non-functional requirements below describe how well the system must do it — qualities the prototype should demonstrate even at MVP scale.

| Req ID | Non-Functional Requirement | What This Means for SmartTimetable |
| --- | --- | --- |
| **NFR-01** | **Usability** | Students and lecturers should be able to find their schedule or report a mismatch within a few clicks, without needing instructions, since the current PDF is already difficult to use. |
| **NFR-02** | **Performance** | The schedule list and search/filter results should load and respond quickly (within a few seconds), so the tool feels faster than manually checking a PDF or RSU Connect. |
| **NFR-03** | **Reliability / Accuracy** | Once a class status is updated by an admin, it must display correctly and consistently every time the page is viewed, since the core problem being solved is trust in accurate information. |
| **NFR-04** | **Availability** | The prototype should be accessible whenever a student needs to check their schedule, including outside class hours, since schedule confusion can happen at any time of day. |
| **NFR-05** | **Maintainability** | The codebase and data structure should be simple and well-organized enough for all four team members to update or extend it across future labs, given the team's current GitHub experience level. |
| **NFR-06** | **Compatibility** | The prototype should work reasonably well on common devices students actually use — primarily mobile browsers, in addition to laptops — since most respondents in Lab 03 checked their schedule from their phones. |
| **NFR-07** | **Security / Privacy** | Even though no advanced cybersecurity implementation is required, the system should avoid exposing unnecessary personal data and should not allow arbitrary users to edit other students' submitted reports. |
| **NFR-08** | **Scalability (conceptual)** | The data structure should be designed so that, in principle, it could support a full semester's timetable and multiple faculties, even if the MVP only demonstrates a sample dataset. |
