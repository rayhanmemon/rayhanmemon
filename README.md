### 👋 Hi, I’m Rayhan!
### Below are descriptions of the two noteworthy projects I'm most proud of: [Prozody](https://www.prozody.com/) and [MyChapter](https://github.com/rayhanmemon/myChapter)

## Prozody ([View Here](https://www.prozody.com/))

### **Background:**
- A web-based audio editor that enables authors to narrate, edit and master their own audiobooks at home.

- This is a private project, as I built it as a side business and incubated through the renowned [Next Canada](https://www.nextcanada.com/) accelerator. 

### **Technical Overview:**

- Front-End
  - Built in React with material UI components
  - Features a custom PDF reader so users can scroll through their manuscript while they narrate
  - Functions as a text-based audio editor (users edit their audio like editing text)
- Transcription Microservice
  - Used for real-time transcription of an author's narration while they are recording
  - Python/Django server with WebSocket connection to front-end for bidirectional streaming
  - Streams audio to Google Cloud's Speech-to-Text API and 
- Back-End
  - Node.js/Express server
  - Used for reading from and writing to MongoDB and AWS S3 for file/data storage
  - Task Queuing with Bull and Caching with Redis
  - Seperate worker for handling CPU-intensive audio processing with FFMPEG
- Databases
  - MongoDB database for user/project data
  - AWS S3 for audio file storage
  - Auth0 for authentication

## MyChapter ([View Here](https://github.com/rayhanmemon/myChapter))

This is an

<!---
rayhanmemon/rayhanmemon is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
