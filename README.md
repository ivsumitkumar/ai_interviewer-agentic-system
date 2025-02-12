# AI Interviewer Agent

This project aims to automate the HR's task of conducting interviews. Once the candidate uploads their resume, it will call the HR agent, which works as the router LLM to call the necessary tools and agents required.

There are four different agents involved in this process:
- **HR Agent**: Acts as the router to call necessary tools and agents.
- **Resume Analyzer**: Analyzes the uploaded resumes.
- **Interview Caller**: Schedules and initiates the interview process.
- **Interviewer Agent**: Conducts the interview with the candidate.
- **Final Decision Maker Agent**: Makes the final decision based on the interview and resume analysis.

This system streamlines the interview process, making it more efficient and effective.