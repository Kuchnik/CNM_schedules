# Monthly schedule for Kaiser midwives

## Project overview

My wife, who is a Certified Nurse Midwife (CNM) suggested that I create a schedule routine 
for her team at Kaiser. It is too much stress for a current scheduler doing it manually in Excel,
and their boss thinks about creating an electronic fair schedule to eliminate emotions and complains. 
I created this routine layer by layer, in which midwives are scheduled to work day and night 12 hour 
shifts at the hospital and regular 8 hour days in clinic, balancing night and day calls and evenly 
spreading workers throughout the week. The program takes care of day off requests and makes sure exact 
40 hour week schedules.

The program has two files: scheduler.ipynb and calendar_padding.ipynb (calendar.ipynb previously)
1) Run scheduler7.ipynb functions: creates schedule for the next 26 weeks starting a specified date;
2) Run calendar_padding to create a visual calendar for the whole team of CNMs with a dropdown
  menue to highlight one worker at a time.

## Share the calendar

1) Save the html file on Google Drive
2) Create a site on drvx.net:
   - GoDrive
   - index.html
   - Google Drive link
   - Project name (e.g. February)
   - Create 4 number security pin
   - Create website


## Uploading history
09.11.2026
- schedule1: only hospital day and night shift schedule; requests for days off
- schedule2: day and night shifts are split equally; added clinic days
- schedule3: introduced half clinic days
- schedule4: added validation routine for days off
- schedule5: compensated for hour deficit during the following week
- schedule6: part time (20 hr weeks) workers (Cezanne)
- schedule7: balance days and nights for Cezanne's calls; 
             balance CNMs evenly between clinic days
- schedule7: make day and calls back to back for each worker
              in the manner they are currently doing;
            special routine for Cezanne call scheduling to make sure
            she has equal days and nights and spraed across the week
- calendar_padding: modify routine to display trailing and leading days 
                of the month
              