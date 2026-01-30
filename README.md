# Section Connection

**AI-assisted messaging platform for college students taking the same course in different sections.**  
This tool helps students share ideas, compare different teaching styles, and improve overall comprehension through peer collaboration.

Section Connection features a **clean, responsive React-based chat interface**, a PostgreSQL backend for persistent messaging, and an AI chatbot for additional support when peers cannot answer questions.


## Features

- **Real-time messaging**: Users can join course-specific chatrooms and communicate with peers across sections.  
- **AI-assisted responses**: Integrated AI chatbot provides help for questions that peers cannot answer.  
- **Database-backed persistence**: PostgreSQL stores user data and chat messages, ensuring continuity of conversations.  
- **Modular front-end components**: React components such as `MessageList`, `MessageItem`, and `MessageInput` provide maintainable, reusable code.  
- **API connectivity**: Frontend communicates with backend through a simple, extensible API workflow.  
- **Agile Scrum methodology**: Development followed sprints, with **daily stand-up meetings**, **user stories** to guide progress.
- **Version control**: GitHub used for collaborative coding and feature tracking.

## Installation

1. Install dependencies and start the front-end:

   npm install
   npm start
   
  This launches the app in a local browser window.

2. Set up the PostgreSQL database:

  Import dump.sql to initialize tables:

    psql -U <username> -d <database_name> -f dump.sql
    
  Once initialized, chat messages will be saved and accessible across sessions.

## My Contribution

Designed and implemented the React front-end interface, including modular and reusable components for messaging.

Built the PostgreSQL database structure and integrated backend connectivity to store and retrieve messages and user data.

Connected frontend and backend via API endpoints to enable seamless real-time messaging and AI interaction.

Led implementation of features using Agile Scrum methodology: worked with user stories, participated in daily stand-ups, and completed tasks iteratively within structured sprints.

Gained hands-on experience with JavaScript, React, CSS, PostgreSQL, and full-stack development practices, preparing for future scalable applications.

## Project Goals

Facilitate student collaboration across course sections and teaching styles.

Integrate AI assistance to provide automated support when peer knowledge is insufficient.

Demonstrate full-stack development best practices, Agile methodology, and user-story-driven implementation.

Build a scalable foundation for future enhancements and deployment.
