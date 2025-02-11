# Full-Moon-Tracker
This is the code for the automation for my full moon tracker

Hi! The assignment was to create an automation using appscript and google Gemini. I recently got a telescope and I've been having people over every time there's a full moon to look at it through the telescope. It would be really useful if I could get notified when there's a full moon coming up so I can organize something without having to remember to check the full moon schedule (I keep forgetting to do that and not realizing there's a full moon coming up until the day before, so this process can get pretty rushed and stressful)

So, I decided to automate a full moon tracker. I started by creating the following spreadsheet:
<img width="1024" alt="Screenshot 2025-02-11 at 1 00 25 PM" src="https://github.com/user-attachments/assets/04295c56-f25b-4929-a127-c0c9e6169b77" />

A problem that I had to solve for was that full moons aren't on consistent schedules. They happen approximately every 29.5 days. I considered setting a reminder for every 28 days so I would know that I'm probably going to be reminded ahead of time, but this wouldn't be a true full moon tracker so I decided not to do that. The other issue is that the monthly full moon is on a different day of the month every year, so I can't just set a yearly reminder for the same full moon. So, I decided to create a spreadsheet with a list of every full moon of the year and run an automation for each individual full moon. In this way, the automation won't be confused by the "last reminded" date. Gemini helped me find Calendarific, which helps with calendar based APIs, so I was able to create an account and link it to my automation, giving the automation a place to check for future full moons. 

This automation will notify me the day before every full moon, checking Calendarific for full moon data and sending me an email telling me which full moon is coming up!
