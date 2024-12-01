# Youtube Summarizer - LLM and GenAI

This project enables users to summarize YouTube videos using a user-friendly interface powered by Flask (backend), MongoDB (database), and a React-based frontend.

## Backend

In the terminal, go to backend directory and run the following command:
```bash
python app.py
```

This will activate the backend server which is developed using flask to connect with Mongodb server.

## Frontend

After activating backend, go to frontend directory.

In the terminal, run the following command:
```bash
npm run dev
```

It will open the localhost page in the browser.

## UI

The web page looks like this:
![image](https://github.com/user-attachments/assets/73bc652b-b525-4ec1-aa2b-a3a6f8e8f2b3)

The user can register and login to the account and use the service.

After logging in, user can paste the youtube link, and click summarize to get the summary of the video.
![image](https://github.com/user-attachments/assets/f87eae8b-11b7-41b8-8c78-98d9c4aa8530)

### Note

MongoDB Compass should be installed in the system and connected to localhost.
