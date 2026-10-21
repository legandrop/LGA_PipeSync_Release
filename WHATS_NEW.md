# What's new in LGA PipeSync

## v1.023 (2026-10-20)

- **New:** Gantt readers: en el tab GANTT podés guardar la combinación de filtros como un preset con nombre y volver a ella con un click; si después cambiás algún filtro, el control lo marca y te deja actualizar el preset o volver a como estaba. (Studio only)
- **New:** Gantt readers: en el tab GANTT podés guardar la combinación de filtros como un preset con nombre y volver a ella con un click; si después cambiás algún filtro, el control lo marca y te deja actualizar el preset o volver a como estaba. (Client only)
- **Improved:** Shots users: al subir una versión ya no hay que tildar nada para que cuenten las horas que cargaste hoy en esa task: la ventana te avisa cuántas son y se suman solas a la versión. (Studio only)
- **Improved:** el tab ACTIVITY ahora se llama QUEUE: es el mismo de siempre, con las subidas y descargas a Wasabi.
- **Improved:** los botones de arriba a la derecha cambian de orden: PROD va antes que PLAYLIST, STATS a la derecha de GANTT y TOOLS antes que PROJECTS; Ctrl+Alt+flechas los recorre en ese mismo orden.
- **Improved:** el tab PLAYLIST muestra su título arriba a la izquierda, como PROD.
- **Improved:** en GANTT, PROD, SHOTS, REVIEW, PLAYLIST y STATS, un combo de filtro que esconde algo (un solo proyecto, algunas secuencias, un assignee) se pinta de rojo para que se note, y sin filtro dice «All projects», «All sequences» o «All assignees».
- **Fixed:** en el tab GANTT, los filtros vuelven a ir alineados a la derecha de la barra en vez de quedar pegados a Today.

## v1.022

- **New:** everyone now has the INBOX: your own to-do list, and the status changes of the tasks you are assigned to or watching. FOR YOU marks a task of yours that was sent to Corrections. (Studio only)
- **New:** everyone now has the INBOX: your own to-do list, and the status changes of every task in your projects. (Client only)
- **New:** Producers and admins: you can download a task's versions from Flow, or only the latest one, from the Prod tab's right-click menu. (Studio only)
- **New:** you can download a task's versions from Flow, or only the latest one, from the Prod tab's right-click menu. (Client only)
- **New:** Producers: you can download a shot's review versions from Flow from the Review tab, as admins already could. (Studio only)
- **New:** everyone can now download a shot's review versions from Flow, not only admins. (Client only)
- **New:** Gantt planners: the local planning assistant can work with several projects at once: review and capture an artist's schedule across two, three or all active projects, and prepare one proposal that moves tasks from different projects, shown together in your Gantt before you apply it. (Studio only)
- **New:** Gantt planners: the local planning assistant can work with several projects at once: review and capture an artist's schedule across two, three or all active projects, and prepare one proposal that moves tasks from different projects, shown together in your Gantt before you apply it. (Client only)
- **Improved:** the Prod tab's right-click menu uses color to show where each option takes you (Flow, NukeStudio, FileManagerS3) and which options mark or delete things.
- **Improved:** tasks are now assigned to the vendor's group instead of individual people, so anyone in that vendor can change their status in Flow. The assignee editors, Create task and the BID import offer the vendor's group. (Client only)
- **Improved:** Gantt planners: the Gantt shows one row per vendor, and dragging a task to a vendor's row assigns it to that vendor's group. (Client only)
- **Improved:** Project managers: Users & Access no longer saves an active vendor user without a Vendor Group, and the vendor audit lists the ones that have none. (Client only)

## v1.020

- **New:** Admins: you can download a shot's review versions from Flow straight from the Review tab. The window comes with only the latest version selected, Shift+Click downloads the latest version without opening it, and the row updates when the download ends. (Studio only)
- **New:** If Settings shows you NKS auto download but not NKS auto upload, you now also get an Upload Now button next to the NKS Download Now button, so you can send your NKS folders to Wasabi right away.
- **Improved:** In Log time, today now has two tabs: one to add time to your shots and general activities, and "Registrado hoy" to review and correct everything you already logged today in a full list. Clicking a shot's logged time takes you to its entries. (Studio only)
- **Improved:** Admins: Downloading versions from Flow now selects only the latest version, Shift+Click downloads it without opening the window, and the row updates when the download ends. (Client only)
- **Fixed:** The Log time window no longer appears inside a second dark panel; it opens as a single window. (Studio, macOS only)

## v1.019

- **New:** Log time supports repeated meetings and other activities with project selection and optional notes, plus supervision entries for reviewers; time fields accept combinations such as 8h 30m and 1d 4h. (Studio only)
- **New:** Shot assignee editors: Right-click an assignee in a Shot Card to edit the task's assignees and Watchers directly, using the same editor as PROD. (Studio only)
- **New:** Shot assignee editors: Right-click an assignee in a Shot Card to edit the task's assignees and Watchers directly, using the same editor as PROD. (Client only)
- **Improved:** Gantt planners: When some tasks changed in Flow after you moved them, Apply lists each one with what changed and lets you apply the rest, keeping those as temporary changes. (Studio only)
- **Improved:** Gantt planners: When some tasks changed in Flow after you moved them, Apply lists each one with what changed and lets you apply the rest, keeping those as temporary changes. (Client only)
- **Improved:** Log time now lists open shots with their current status for today's entries and lets you edit, move or remove earlier records before saving all changes together. (Studio only)
- **Improved:** Producers: The team hours summary compares this week and last week with explicit dates, logged and missing time, and daily details; totals over eight hours use workdays. (Studio only)
- **Improved:** Assignee editors: Viewer is now called Watcher. Removing an assignee also clears Watcher; assigning the person again keeps Watcher off until you explicitly select it. (Studio only)
- **Improved:** Assignee editors: Viewer is now called Watcher. Removing an assignee also clears Watcher; assigning the person again keeps Watcher off until you explicitly select it. (Client only)
- **Fixed:** Automatic updates install the new version again; before, PipeSync closed and reopened the version you already had. (macOS only)
- **Fixed:** Gantt planners: Apply no longer stops with an expected-values conflict when the batch moves tasks that are linked by dependencies in Flow. (Studio only)
- **Fixed:** Gantt planners: Apply no longer stops with an expected-values conflict when the batch moves tasks that are linked by dependencies in Flow. (Client only)
- **Fixed:** Gantt planners: After applying a planning proposal, the Gantt stays on the same dates instead of jumping elsewhere in the timeline. (Studio only)
- **Fixed:** Gantt planners: After applying a planning proposal, the Gantt stays on the same dates instead of jumping elsewhere in the timeline. (Client only)

## v1.018

- **New:** Assignee editors: Mark an assigned person as a Viewer to keep their access while identifying who is responsible for the task. (Studio only)
- **New:** Assignee editors: Mark an assigned person as a Viewer to keep their access while identifying who is responsible for the task. (Client only)
- **New:** Task information labels responsible people and Viewers separately, keeping access distinct from responsibility.
- **New:** Gantt planners: Compare each shot's recorded time with a selected quote and Flow's current estimate, keeping missing estimates and incomplete time records visible. (Studio only)
- **New:** Gantt planners: Compare each shot's recorded time with a selected quote and Flow's current estimate, keeping missing estimates and incomplete time records visible. (Client only)
- **New:** Cost analysts: Analyze declared internal rates, documented incurred costs and an internal budget with explicit sources, separately from client prices and assumptions. (Studio only)
- **New:** Cost analysts: Analyze declared internal rates, documented incurred costs and an internal budget with explicit sources, separately from client prices and assumptions. (Client only)
- **New:** Gantt planners: You can review overdue work and global artist queues, build a tentative Gantt with explicit capacity and effort assumptions, and share a planning context with a local assistant or through chat attachments. Gantt Exchange shows received changes and their exact approval before you apply them. (Studio only)
- **New:** Gantt planners: You can review overdue work and global artist queues, build a tentative Gantt with explicit capacity and effort assumptions, and share a planning context with a local assistant or through chat attachments. Gantt Exchange shows received changes and their exact approval before you apply them. (Client only)
- **New:** Gantt planners: Planning proposals appear as temporary drafts in your open Gantt, framed around the affected task and artist. You can refine them while keeping other manual changes. Only Apply All Changes in PipeSync confirms the current draft batch and sends it to Flow. (Studio only)
- **New:** Gantt planners: Planning proposals appear as temporary drafts in your open Gantt, framed around the affected task and artist. You can refine them while keeping other manual changes. Only Apply All Changes in PipeSync confirms the current draft batch and sends it to Flow. (Client only)
- **New:** Gantt planners: Save a planning proposal from the terminal and compare before/after images of the real Gantt. Drafts appear in violet, with shared assignees and optional dates preserved, before you apply them. (Studio only)
- **New:** Gantt planners: Save a planning proposal from the terminal and compare before/after images of the real Gantt. Drafts appear in violet, with shared assignees and optional dates preserved, before you apply them. (Client only)
- **New:** Gantt planners: You can capture the real Gantt from a terminal, framed by person, task or date, without opening a window. The image uses a copy of your planning database and Argentine holiday calendar. (Studio only)
- **New:** Gantt planners: You can capture the real Gantt from a terminal, framed by person, task or date, without opening a window. The image uses a copy of your planning database and Argentine holiday calendar. (Client only)
- **New:** Gantt planners: You can query the Gantt from a terminal without opening PipeSync: project and person status, task details, records to review and changes since a daily snapshot. Results are JSON with the evidence and missing data; the commands read copies of your local databases. (Studio only)
- **New:** Gantt planners: You can query the Gantt from a terminal without opening PipeSync: project and person status, task details, records to review and changes since a daily snapshot. Results are JSON with the evidence and missing data; the commands read copies of your local databases. (Client only)
- **New:** Reviewers: In the INBOX, right-click a status change to jump to that shot: Show shot in NukeStudio takes the open NukeStudio to it, and Show shot in FileManagerS3 opens the shot's folder in a FileManagerS3 tab. (Studio only)
- **New:** Reviewers: In the INBOX, right-click a status change to jump to that shot: Show shot in NukeStudio takes the open NukeStudio to it, and Show shot in FileManagerS3 opens the shot's folder in a FileManagerS3 tab. (Client only)
- **New:** Audit navigators: In the vendor audit, select a row and press Show in Prod tab to jump to that shot, already searched and selected. (Client only)
- **New:** Project managers: For a shot PipeSync has not synced because it has no tasks, the vendor audit's Show button turns green and opens it in Flow. (Client only)
- **New:** Admins: In the vendor audit, right-click > Delete shot lets you delete a shot that has no tasks. (Client only)
- **New:** Production managers: you can rename a shot from the PROD tab with right-click > Rename shot or F2: PipeSync renames it in Flow and moves its files in Wasabi and its folder on your computer to the new name. File names keep the old name, and other computers keep their old folder. (Studio only)
- **New:** Wasabi cleanup users: Wasabi Cleanup has a Next sequence button that scans the following sequence of the bucket without closing the window, and Rescan no longer resizes the window. (Studio only)
- **New:** Shots users: Log time: you can now log hours on your open tasks for any day of this week or last week without uploading a version, and log meetings separately, either for one project or as a General meeting. Open it by clicking the hours bar at the top of the Shots tab. (Studio only)
- **New:** Reviewers: Log time has a Supervision section to log the time you spend reviewing and supervising other people's work, for one project or as General. Its Completar button fills in the hours still missing to complete the day, without saving anything. (Studio only)
- **New:** If your time tracking is Required, PipeSync now reminds you half an hour before the end of the day if today's hours are not logged, and asks again the next morning if a day was left incomplete. Active people on the assignee list start at 8 hours a day with a 6 pm reminder. (Studio only)
- **New:** Team time users: Work Time in the Stats tab now lists the active team with logged versus expected hours per period, colored by status: green when complete, amber when hours are missing, red when nothing was logged or a period closed short. A summary on top filters the list, and each person's detail shows every day's status and the versions uploaded. Meetings and supervision hours are totaled for the team at the bottom. Eligible producers also get a short summary of who is behind each time you open PipeSync, with a checkbox to hide it until the next day. (Studio only)
- **New:** Team time users: In the Stats tab you can change who must log hours, their reminder time and time off without leaving Stats: use Edit in a person's Work Time detail. (Studio only)
- **New:** Project managers: Edit user has a Time tracking section to change who must log hours, their hours per day and reminder time, and to add time off, all in the same window. (Studio only)
- **New:** Keyshots now show a red diamond next to the shot name in the Shots, Review and PROD tabs. Hover it to see what it means.
- **New:** Production editors: In the PROD tab you can mark or unmark a shot as important from the right-click menu, the same flag as the Shot Priority button in HieroTools. Important shots now show their name in red in the PROD tab too, and with several rows selected the change applies to all their shots. (Studio only)
- **New:** Production editors: In the PROD tab you can mark or unmark a shot as important from the right-click menu. Important shots now show their name in red in the PROD tab too, and with several rows selected the change applies to all their shots. (Client only)
- **Improved:** After updating, release notes follow your current profile in Help and future update notices, so you see changes relevant to the features you can use.
- **Improved:** Gantt readers: Gantt Task Info keeps a fixed height while showing the shot image, colored task status, estimate and logged time together with each person's contribution; full notes and additional contributors open in a separate detail window. (Studio only)
- **Improved:** Gantt readers: Gantt Task Info keeps a fixed height while showing the shot image, colored task status, estimate and logged time together with each person's contribution; full notes and additional contributors open in a separate detail window. (Client only)
- **Improved:** Gantt readers: Viewers are excluded from current workload and Gantt assignment conflicts. (Studio only)
- **Improved:** Gantt readers: Viewers are excluded from current workload and Gantt assignment conflicts. (Client only)
- **Improved:** Gantt planners: Pending planning drafts detect responsibility changes before applying. (Studio only)
- **Improved:** Gantt planners: Pending planning drafts detect responsibility changes before applying. (Client only)
- **Improved:** Gantt readers: The Gantt shows the calendar interval as a faint band and recorded work on its actual dates, using eight-hour workdays. (Studio only)
- **Improved:** Gantt readers: The Gantt shows the calendar interval as a faint band and recorded work on its actual dates, using eight-hour workdays. (Client only)
- **Improved:** Gantt readers: The Gantt refreshes after Flow sync without interrupting your current view. (Studio only)
- **Improved:** Gantt readers: The Gantt refreshes after Flow sync without interrupting your current view. (Client only)
- **Improved:** Gantt planners: Your pending changes stay in place after Flow sync, without a prompt to decide what to do with drafts. Refresh DB still lets you keep or discard them manually. (Studio only)
- **Improved:** Gantt planners: Your pending changes stay in place after Flow sync, without a prompt to decide what to do with drafts. Refresh DB still lets you keep or discard them manually. (Client only)
- **Improved:** Gantt planners: Planning previews now show the selected task immediately, including tasks in Unassigned. Short visual transitions keep the full draft ready for review and stop when you edit, apply, reset, scroll or leave the Gantt; reduced motion shows the final state directly. (Studio only)
- **Improved:** Gantt planners: Planning previews now show the selected task immediately, including tasks in Unassigned. Short visual transitions keep the full draft ready for review and stop when you edit, apply, reset, scroll or leave the Gantt; reduced motion shows the final state directly. (Client only)
- **Improved:** Project managers: Re-importing a bid now assigns the existing vendor tasks that had no assignee to that vendor's users, and the preview shows it before you apply. (Client only)
- **Improved:** Project managers: Run audit in the Projects tab now opens a results window instead of a single line: a summary per vendor, every problem with the shots, tasks and people affected, and one-click fixes for shots missing their Vendor Group, vendor tasks without an assignee and vendor users without a Vendor Group. It also reports tasks left with disabled users, the versions and notes a vendor can no longer see, and who each shot without a vendor code belongs to. (Client only)
- **Improved:** Windows and dialogs no longer flash white for a moment when they open. (Windows only)
- **Improved:** The installer is much smaller (about 110 MB instead of 300 MB), so updates download faster, and PipeSync takes about 900 MB less disk space. (Windows only)
- **Improved:** Slate users: the Slate MXF tool in the Tools tab is now available to producers who also have access to Tools. (Studio, Windows only)
- **Improved:** Tools users: The Tools tab now adapts to the window width: in a narrower window the update cards and the Disk Cleanup actions rearrange instead of being cut off. (Studio only)
- **Improved:** Tools users: The Tools tab now adapts to the window width: in a narrower window the update cards and the Disk Cleanup actions rearrange instead of being cut off. (Client only)
- **Improved:** Project managers: The Projects tab now grows with the window, up to the same width as the Tools tab. You can drag any column border in its tables to resize it, and vendor codes and each user's projects rearrange to fit the width. (Studio only)
- **Improved:** Project managers: The Projects tab now grows with the window, up to the same width as the Tools tab. You can drag any column border in its tables to resize it, and vendor codes and each user's projects rearrange to fit the width. (Client only)
- **Improved:** Shots users: The hours bar in the Shots tab now shows today, your last working day and the week against your reference, and it no longer turns red first thing in the morning. (Studio only)
- **Improved:** Shots users: Uploading a version no longer forces you to enter time when you already logged the day; you can count those hours as the version's time instead. (Studio only)
- **Improved:** Project managers: Edit user is now a wide window organized in columns that fits on screen, and the assignee color is picked by clicking a single color dot. (Studio only)
- **Improved:** Tools users: The LGA Updates card in the Tools tab now offers LGA Mighty Tools in place of LGA OpenInNukeX, so you can install it from there and see when a new version is out. (Studio, macOS only)
- **Improved:** Tools users: The LGA Updates card in the Tools tab now offers LGA Mighty Tools in place of LGA OpenInNukeX, so you can install it from there and see when a new version is out. (Client, macOS only)
- **Improved:** PipeSync now checks for updates every few hours while it stays open, not only at startup. Remind me later waits one day instead of a week, and closing the update window won't ask again until you restart PipeSync.
- **Fixed:** Team time users: Availability in the Stats tab no longer shows negative available days when the deadline is in the past. (Studio only)
- **Fixed:** Project managers: Three tooltips in Edit user no longer show garbled characters. (Studio only)
- **Fixed:** Project managers: In Users & Access, a change saved right after another one is no longer lost silently: Edit user waits until the table is back in sync with Flow, and a save that Flow rejects now shows an error with its details. (Studio only)
- **Fixed:** Project managers: In Users & Access, a change saved right after another one is no longer lost silently: Edit user waits until the table is back in sync with Flow, and a save that Flow rejects now shows an error with its details. (Client only)
- **Fixed:** Stats no longer shows a task's logged hours as only its latest entry after a sync.
- **Fixed:** A task whose only time entry was deleted from another computer or from the Flow website no longer keeps showing that time after a sync.
- **Fixed:** Shots users: Uploading a version no longer counts its time as logged when Flow failed to register it; PipeSync now tells you so you can log it again. (Studio only)
- **Fixed:** Shots users: Uploading a version no longer counts its time as logged when Flow failed to register it; PipeSync now tells you so you can log it again. (Client only)
- **Fixed:** Assignee editors: Reassigning tasks to someone else no longer shows an "Assignees saved with warnings" message for every task. (Studio only)
- **Fixed:** Assignee editors: Reassigning tasks to someone else no longer shows an "Assignees saved with warnings" message for every task. (Client only)

## v1.016

- **Fixed:** When giving an artist Wasabi access failed halfway, the next task assignment or Wasabi policy sync now finishes it instead of leaving them without access to the shot. (Studio only)

## v1.015

- **New:** The update window now shows what's new before you install, and after an update you didn't see the app shows it once when it starts.
- **New:** In the Tools tab, each tool with an update in LGA Updates has a What's new button next to Update with its changes, Update All ends with a summary of what changed, and the startup notice about available updates says what's new in each tool.
- **New:** The Help tab has a What's new button with the release notes of every PipeSync version.
- **New:** The LGA Updates card in the Tools tab now lists LGA FrameRev, the screen capture and annotation app, so you can install it and see when a new version is out.
- **New:** Coordinators and reviewers: the Tools tab has a new Slate MXF tool that lists the tasks in Rev Dir, adds a slate frame in front of each delivery MXF and writes what you complete or correct back to Flow. (Studio, Windows only)
- **New:** Coordinators and admins: Shift+Click on the sync cloud opens a window to bring in projects that are not In Progress, such as Delivered ones, until you close the app. (Studio only)
- **New:** Admins: Shift+Click on the sync cloud opens a window to bring in projects that are not In Progress, such as Delivered ones, until you close the app. (Client only)
- **New:** Right-click a row in the PROD tab to open View notes and feedback for the task's versions, Show shot in NukeStudio to jump to it in the open NukeStudio, or Show shot in FileManagerS3 to open the shot's folder in a FileManagerS3 tab.
- **New:** Review Netflix and SL Approved task statuses are available after Review Dir in the status picker, the PROD table and the Gantt legend. (Client only)
- **Improved:** The LGA Updates card in the Tools tab shows each tool's summary from the LGA website in larger, easier to read text, with the full text in its info card.
- **Improved:** Coordinators and admins: Wasabi Cleanup reviews several shots at once, lets you pick any Wasabi bucket instead of a project, recognizes versions named with a space before the V and no longer keeps deleted versions on screen. (Studio only)
- **Improved:** Producers: you can now add comments to a version from its notes, as reviewers already could. (Studio only)
- **Improved:** Admins: you can now add comments to a version from its notes, as reviewers already could. (Client only)
- **Improved:** Admins: in Users & Access, choosing a Vendor Group also makes the person a member of that group in Flow, and changing it removes the old one. (Client only)
- **Improved:** The PROD tab's Task Name filter is now a dropdown like Assignees, Projects and Sequences, the PROD table's cursor no longer turns into a hand over editable cells, and the PLAYLIST tab opens with the most recently created playlist on top.
- **Fixed:** Tasks assigned to a whole Vendor Group now show that vendor's color in the PROD tab's Assignees column. (Client only)
- **Fixed:** The LGA Updates card in the Tools tab shows the version of LGA Shot Player that is actually installed, instead of an old one.
