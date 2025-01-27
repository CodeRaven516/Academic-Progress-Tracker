# Academic-Progress-Tracker
It is a Google Chrome extension that generates a live browser activity report to track academic progress for students in remote learning environments. The extension should be able to record and analyze the students' online activity on their Chrome browsers and provide detailed reports on their progress. The reports should include data on time spent on different websites, active tabs, and mouse activity. The ideal candidate should have experience in Chrome extension development and knowledge of HTML, CSS, JavaScript, and browser APIs. 

* It should have a centralized dashboard as the content script that serves as the hub for all extension features and a live activity log summary showing the time a student spends on websites and online activities throughout the day/week/month for parents to monitor to ensure academic integrity, productivity, and monitorization.
* Activity Log must-haves:
* Designed to look similar to the Apple iPhone screen time activity log (bar chart showing time spent on different sites)
* categorize websites based on educational, entertainment, or other classifications of websites
* cannot be altered, edited, or changed (even is window history is cleared) by the student. It needs to be viewable for the parent to go in and see their progress whenever.
* There needs to be a login system with the gmail authentication (made with firebase ideally) that the student can log into the home extension when opening the extension and their activity log will record their chrome window activity (with granted permissions accordingly).
* Implement a feature that sends an activity log summary for the day to a parent’s email or phone number (input section for that in the dashboard). Perhaps an SMS messaging API for this feature implementation.
* Same feature could allow the child to send a prewritten message to parent if they are stuck on work (button on dashboard that says “I need help!”) and it will send that message via SMS text message or email to the parent.
* audience: 4th-8th grade homeschool students with parents as teachers
* Interface design must-haves:
* simple and visually appealing interface that is easily navigable for young students to use

Relevant skills:
- Google Chrome extension development
- HTML
- CSS
- JavaScript
- Browser APIs
