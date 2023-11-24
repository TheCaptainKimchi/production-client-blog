# Introduction

Over the past handful of months (working maybe once or twice a week; 10/10/2023), I've been developing a full-stack application for an online event hosting webapp with a focus around esports. What makes this site unique is its focus on providing supporting tools for the organizers through a robust and dynamic API. One of the primary tools for this site is the ability to display frequently updating match/event results without having to manually configure any of the details.

Although the project is still in its infancy, I look to journal the progress as each piece gets updated and give sneak peeks on to the tools behind the application.

## About the developer

Hello! My name is Raul, a Software Engineer based out of Vancouver, BC. With a lifelong passion for Software and tech in general, I've been working with tech as young as 6 years old (2001) when our family got our first laptop. With no YouTube, Google, or any search-engines (that I knew of at the time), I would spend the next few years playing around with the laptop installing various games, updating and setting up software for our family, and just learning about how the web worked.

Fast forward to today (2023-11-23) and I now have coming close to three decades of experience around intermediate to advance technologies. Being a self-taught developer, I started with tools such as Python building webapps with HTML/CSS and Flask for three years. In 2023, I completed my diploma for Software Engineering and became up to date with the latest design trends focusing on becoming a full-stack developer. Some of the skills I specialize in are:

    HTML, CSS, Bootstrap, JavaScript, TypeScript, jQuery, Node, Vite, React, React Native, Electron, Express, WordPress, Wix, SQL, MySQL, PostgreSQL, PHP, Agile Development, Scrum, Document Object Model (DOM), Restful APIs, User Authentication, OAuth, Heroku, AWS, GitHub, Git, Jest, Knex, Python, Linux

With more being added everyday! I am currently learning Vue.js and native app development including desktop and mobile.

My goals are to work and develop with an amazing team and add my lifelong experience and passion to create amazing ideas! To close the gap on my missing full-time experience, completing the Software Engineering program helped vault my experience leap years ahead of where it was previously at and allowed me to work with cross-collaborative teams on several hackathon projects and a warehouse inventory web application. Along with the completion of the diploma, I have also been taking freelance work for various organizations and clients further enhancing my skillset and gaining valuable professional exerience.

I'm always looking to connect with other developers either to learn or teach so feel free to check out any of my socials below and reach out:

LinkedIn
https://www.linkedin.com/in/raulcalero/

GitHub
https://github.com/TheCaptainKimchi

Twitter
https://twitter.com/_CaptainKimchi

## 2023-11-23

1. Project Goals

Currently, the project has its base framework built out with a focus on fully completing its core elements. These core elements consist of: database built with postgreSQL, API server built with node.js/express, and a bare bones client built on Electron.TS.

2. Projected Tools

The tools this project is looking to create are: a web/native client for users to host, coordinate, and organize events, a production support tool that accesses the API to display dynamically updating details to simplify production for organizers, a marketplace for organizers to search/hire talents such as caster, observer, organizer, and other various skillsets an event may require.

Once the above phase (Phase 1) has been completed, the basic structure of the site will be laid out with the focus on Phase 2 being refinement. After user testing of the webapp, feedback on where to improve will be collected and updated based on user needs.

Phase 3 will be focused on the addition of a new tool to provide deep-analysis of gameplay starting with the game Valorant. Utilizing a previous project of collecting up-to-date match data, a database of matches have been stored with insight tools currently in development.

3. Server - Current Status

The server is currently fully built utilizing key tools such as Node.js, Knex, and PostgreSQL. The REST API displays most of everything required at this state with a focus on: Events (List of events and their status), Matches (List of matches and their status), Users (User list for login features and unique state rendering on client), Event:Id (Page details), Overlays (Collection of pre-made overlays), and more based on future needs.

The server is currently in the local build stages with future plans to host on AWS on an Ubuntu Linux server.

4. Client - Current Status

The client is where the bulk of the work is being laid out as this will be the front facing aspect users interact with. The client is split in to three sections: Events, Production, and User Dashboard.

Currently, only the Events section has been worked and an example may be seen below at the rough design of the client. This design is not the final look as the main goal is to get the project operational with a future focus on design changes later on.

![](<https://github.com/TheCaptainKimchi/production-client-blog/blob/d760b8a4dd4583d20db9e960efc548cc9f9123c3/2023-11-23%2010-01-51%20(1).gif>)
