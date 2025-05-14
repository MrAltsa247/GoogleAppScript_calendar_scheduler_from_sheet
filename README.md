# GoogleAppScript_calendar_scheduler_from_sheet
This script reads a schedule from a Google Sheet and creates events in Google Calendar automatically. It also sets a reminder (notification) for each event. The purpose is to manage scheduling workflows using spreadsheets without manually opening Calendar.

📅 GoogleAppScript_calendar_scheduler_from_sheet
📋 Overview
This script reads a schedule from a Google Sheet and creates events in Google Calendar automatically. It also sets a reminder (notification) for each event. The purpose is to manage scheduling workflows using spreadsheets without manually opening Calendar.

✅ Features
Adds events to your selected Google Calendar

Pulls title, description, date, time, and duration from the spreadsheet

Sets a pop-up reminder before each event

Marks events as “Scheduled” to avoid duplicate insertions

📊 Spreadsheet Structure
Sheet name: CalendarSchedule
A: Event Title — Title for the calendar event

B: Description — Notes or explanation for the event

C: Date — The event date in format yyyy-mm-dd

D: Start Time — Time in 24-hour format HH:mm

E: Duration (min) — Duration of the event in minutes

F: Status — Will be marked as Scheduled after the script runs successfully

🧰 Setup Instructions
Create a Google Sheet and name a tab CalendarSchedule

Add headers: Event Title, Description, Date, Start Time, Duration (min), Status

Fill in your schedule data

Open Apps Script: Extensions > Apps Script

Paste the script below

Replace YOUR_CALENDAR_ID with your calendar’s ID (or leave blank for default calendar)

Run createCalendarEventsFromSheet()

Events will be added to Calendar and the row marked as “Scheduled”

