# Lab 04 - User Persona

> SmartTimetable - Digital Class Schedule and Room FInder

## 1. Persona Name
Yu, Year 1 International Undergraduate Student

## 2. User Type
A freshman student struggling to keep track of shifting room assignments and last-minute schedule changes.

## 3. Background and Context
- Where does this user experience the problem?

  On campus when trying to locate classrooms, lecture rooms, or navigating between different university faculties.
  
- When does the problem usually happen?

  During the university week when classes and schedules are suddenly cancelled, rescheduled, or moved to different rooms.
  
- What digital tools does this user already use?

  Official university portals (RSU Connect, intranet, registration website), downloadable PDF timetables, Google Calendar, phone screenshots, and LINE group chats.

## 4. Goals
- What does the user want to achieve?

  To have a single, reliable source of truth for daily schedules that updates automatically.
  To avoid wasting time walking to the wrong classroom or showing up to a cancelled lecture.
  
- What would make the situation easier or faster for the user?
  
  To receive immediate, reliable alerts regarding sudden timetable or room changes directly on their phone.
  

## 5. Pain Points from Lab 03 Evidence
| Pain Point | Evidence ID / Respondent | Explanation |
|---|---|---|
| Outdated & Glitchy Portals | E01, E02 | EPortals like RSU Connect often fail to show room numbers or lag behind by displaying the previous semester's data during registration weeks. |
| Poor Mobile Usability | E05, E06 | Digital schedules are often just raw PDFs or fixed paper layouts. Viewing them forces awkward two-dimensional scrolling, pinching, and zooming on small screens. |
|Late or Buried Updates | E08, E10 | Room adjustments and cancellations are discovered too late because critical announcements get buried quickly in busy LINE group chats or verbal notices. |

## 6. Current Alternatives / Workarounds
| Current Alternative | Weakness / Limitation | Evidence |
|---|---|---|
| Official PDF Timetable & Portals | Entirely static. Completely fails to reflect real-time changes or sudden room double-bookings. | Screenshot of PDF / Timetable |
| Asking Peers / Lecturers in LINE | Highly informal and inconsistent. Relies on classmates or lecturers manually pushing updates, which clutters chat logs. | LINE / Class Chat Responses |
| Physical Verification | Requires the user to waste physical energy and time walking to the room just to check room details. | Intranet / Staff Responses |


## 7. Design Implications
- What should the system/app/platform support?

  The platform must dynamically override stale university data to provide an accurate, live-updating schedule view. It needs to support a flexible messaging integration—specifically utilizing LINE Official Account APIs or LINE Bots—to push instant notification alerts directly to students' preferred chat application alongside a mobile-friendly layout and calendar syncing.
  
- What should the team avoid?

  Avoid assuming all students face this issue with the same daily frequency, as findings show it ranges from "almost never" to "all the time." Do not build an overly rigid system that relies strictly on a single API without fallback manual validation
  
- Which user need is most important for the MVP?

  A highly responsive, mobile-readable digital timetable that aggregates schedule data cleanly and clearly flags any real-time cancellations or room adjustments.
