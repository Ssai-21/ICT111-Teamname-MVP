# Problem Notes

## Selected Case
SmartTimetable – Digital Class Schedule and Room Finder. This case focuses on validating whether the static PDF/printed timetable and existing university systems (RSU Connect, intranet) cause real, recurring problems for students, lecturers, and staff, and whether a real-time digital alternative would be adopted.

## Target Respondents
| Respondent Type | Why This Respondent Matters | Planned Number | Actual Number |
|---|---|---:|---:|
| Student | Primary daily user of the timetable; most directly affected by room/schedule changes | 15 | 18 |
| Lecturer | Manages class delivery and is affected by room conflicts and the need to communicate changes manually | 1 | 2 |
| Staff | Handles student questions about schedule changes and represents the administrative side of the problem | 1 | 1 |

## Observed / Reported Problem
The official PDF/printed timetable, along with related university systems such as RSU Connect and the registration website, does not reliably update in real time when a class is cancelled, a room is changed, or a room is double-booked. Several respondents also reported that RSU Connect itself showed outdated semester data or failed to display room information. Students and lecturers consistently described finding out about changes too late, often only after walking to the wrong room, arriving late, or showing up to a class that wasn't happening.

## Current Alternatives or Workarounds
| Workaround | Who Uses It? | Weakness / Pain | Evidence Source |
|---|---|---|---|
| Class group chat confirmation | Students | Messages get buried quickly; not everyone sees the update in time | "Have to confirm in class group chat"; "Group chat messages get buried and lost quickly" |
| Memorizing the schedule | Students | Breaks down immediately when any change occurs; no fallback | "I have it memorized"; mental notes that are later forgotten |
| Contacting or asking the lecturer directly | Students | Depends on lecturer being reachable; delays resolution | "Contacted the lecturer"; "Go to tell ajan"; "Ask Aj. to make sure which one is correct" |
| Checking RSU Connect / reg.rsu.ac.th / intranet | Students | Sometimes shows outdated semester data or doesn't display the room at all | "Showed last semester's [timetable]"; "Most of the time RSU connect bot doesn't show the room" |
| Manually relaying updates via LINE group | Lecturer | Time-consuming; relies on the lecturer remembering to notify everyone individually | "I informed the students via LINE group chat" |
| Verbal announcement in class | Lecturer | Not written down anywhere, so students who miss class never receive it | "Lecturer mentioned a class cancellation but the PDF didn't update" |
| Manual explanation to students at the office | Staff | Repetitive; staff repeats the same explanation to many students one by one | "Manually explained the same updates to many students individually" |
| Re-checking the website repeatedly | Students | Wastes time and is mentally tiring | "Entering the website again and again to watch the timetable" |
| Going to the student center in person | Students | Requires physically traveling somewhere just to confirm a schedule | "Go to student center" |

## Repeated Pain Points
| Pain Point | Number of Mentions | Example Evidence | Severity |
|---|---:|---|---|
| No automatic update for cancellations, postponements, or changes | 7 | "It doesn't update automatically when a class is canceled or postponed"; "It does not update automatically when there is a sudden change" | High |
| No advance notice of room changes or double-bookings | 5 | Room changed to a different building with no notice; room double-booked, lecturer had to relocate mid-session | High |
| Verbal/in-class announcements are never reflected in the PDF | 2 | Lecturer announced a cancellation in class but the PDF stayed the same, leading a student to an empty room | High |
| University systems (RSU Connect/intranet) show outdated or incomplete data | 3 | "Showed last semester's [timetable]"; "RSU connect bot doesn't show the room" | Moderate-High |
| Poor mobile usability of the PDF/printed format | 2 | "Poor mobile readability... viewing tiny tables on small screens forces awkward pinching, zooming" | Moderate |
| Repeated manual explanations needed from staff/lecturers | 1 | Staff repeating the same room-change explanation to multiple students individually | Moderate |
| General complaints about messiness/complexity of current system | 3 | "It messy"; "Current timetable is full [of] mistake and complicated"; "It's complicated" | Moderate |
| No issues experienced at all | 2 | "Never mismatch"; "None, I like current pdf timetable" | Low |

## Consequences
| Consequence | Example | Evidence Strength |
|---|---|---|
| Arrived late to class | Multiple students reported arriving late after confirming a room/time mismatch | Strong |
| Went to the wrong room | Reported by several students after a room change wasn't reflected in the PDF | Strong |
| Missed part or all of a class | A student went to a cancelled class where no one else showed up; another missed part of a lecture after a building change | Strong |
| Lost teaching time | Lecturer had to relocate an entire class mid-session due to a room double-booking | Strong |
| Wasted staff time | Staff repeatedly explained the same schedule change to multiple students individually | Moderate |
| Near-miss on an exam | A student almost went to the wrong exam room after a last-minute exam room change | Strong |
| Unnecessary trip to class | A student showed up for a class that turned out to be unnecessary due to an unaccounted-for holiday | Moderate |

## Notes for MVP Direction
The strongest and most repeated evidence points to one core need: a single, always-current source for schedule and room information that reflects cancellations, room changes, and double-bookings the moment they happen — this should be the MVP's primary focus rather than a secondary feature. Several respondents specifically distrust the existing RSU Connect/intranet system because it has shown outdated or incomplete data in the past, so the MVP should be positioned as more reliable and simpler than the current digital options, not just a replacement for the PDF. Push notifications were the most frequently requested trust-building feature, but a search function (by room or course code) and mobile-friendly readability were also repeatedly mentioned, suggesting the MVP should prioritize a clean, searchable mobile view first, with notifications as a fast-follow feature. A small number of respondents reported no real pain with the current system, so early testing should focus on users who already reported frequent schedule mismatches rather than assuming universal urgency. Lecturer and staff sample sizes remain small, so their workflow needs (e.g., an easy way to broadcast a change without relying on LINE) should be treated as a secondary validation target in Lab 04 rather than a confirmed MVP requirement yet.
