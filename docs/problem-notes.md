# Problem Notes

## Selected Case
SmartTimetable – Digital Class Schedule and Room Finder. This case focuses on validating whether the static PDF/printed timetable causes real, recurring problems for students, lecturers, and staff, and whether a real-time digital alternative would be adopted.

## Target Respondents
| Respondent Type | Why This Respondent Matters | Planned Number | Actual Number |
|---|---|---:|---:|
| Student | Primary daily user of the timetable; most directly affected by room/schedule changes | 10 | 12 |
| Lecturer | Manages class delivery and is affected by room conflicts and the need to communicate changes manually | 3 | 2 |
| Staff | Handles student questions about schedule changes and represents the administrative side of the problem | 2 | 1 |

## Observed / Reported Problem
The official PDF/printed timetable does not update automatically when a class is cancelled, a room is changed, or a room is double-booked. Students and lecturers consistently find out about these changes too late — often only after walking to the wrong room or starting a class without students present. Both groups currently rely on informal communication (group chats, verbal announcements, asking around) to make up for the timetable's lack of real-time accuracy.

## Current Alternatives or Workarounds
| Workaround | Who Uses It? | Weakness / Pain | Evidence Source |
|---|---|---|---|
| Class group chat confirmation | Students | Messages get buried quickly; not everyone sees the update in time | Survey response 1, 4 |
| Asking the lecturer directly | Students | Depends on lecturer being reachable; delays resolution | Survey response 6, 12 |
| Memorizing the schedule | Students | Breaks down immediately when any change occurs; no fallback | Survey response 9 |
| Manually relaying updates via LINE group | Lecturer | Time-consuming; relies on the lecturer remembering to notify everyone individually | Survey response 12 |
| Verbal announcement in class | Lecturer | Not written down anywhere, so students who miss class never receive it | Survey response 8 |
| Manual explanation to students at the office | Staff | Repetitive; staff repeats the same explanation to many students one by one | Survey response 5 |
| Checking university intranet/RSU Connect timetable | Student | Sometimes shows outdated semester data instead of the current one | Survey response 14 |

## Repeated Pain Points
| Pain Point | Number of Mentions | Example Evidence | Severity |
|---|---:|---|---|
| Timetable does not update for cancellations or changes | 6 | "It doesn't update automatically when a class is canceled or postponed" | High |
| No advance notice of room changes | 4 | "No way to know about room changes," led to walking to the wrong building | High |
| Verbal/in-class announcements are not recorded anywhere | 2 | Lecturer mentioned a cancellation but the PDF was never updated, so the student went to an empty class | High |
| Repeated manual explanations needed from staff/lecturers | 2 | Staff repeating the same room-change explanation to multiple students individually | Moderate |
| Outdated semester data shown in existing intranet system | 1 | Timetable on RSU Connect showed the previous semester instead of the current one | Moderate |
| No issues experienced at all | 3 | A few respondents reported "Almost never" facing problems and rated improvement low (2–6 out of 10) | Low |

## Consequences
| Consequence | Example | Evidence Strength |
|---|---|---|
| Arrived late to class | Student walked to the wrong building after an unannounced room change | Strong |
| Missed part or all of a class | Student went to a class that had been cancelled, with no one else present | Strong |
| Lost teaching time | Lecturer had to relocate an entire class mid-session due to a room double-booking | Strong |
| Wasted staff time | Staff repeatedly explained the same schedule change to multiple students individually | Moderate |
| Near-miss on an exam | Student almost went to the wrong room for an exam after a late room change | Strong |

## Notes for MVP Direction
The MVP should prioritize solving the most strongly evidenced pain point first: real-time visibility into cancellations, room changes, and double-bookings, since this is where the clearest, most severe consequences were reported (lateness, missed classes, lost teaching time). Push notifications were the most frequently requested feature, but the team should keep the MVP simple — a searchable, always-current schedule view may be sufficient before adding notification infrastructure. Since a minority of respondents reported no real pain with the current system, the MVP should be tested specifically with users who reported frequent issues rather than assuming universal need. Lecturer and staff sample sizes were small, so the team should treat their workflow needs (e.g. a simple way to broadcast a change without relying on LINE) as a secondary validation target for Lab 04 rather than a confirmed requirement yet.
