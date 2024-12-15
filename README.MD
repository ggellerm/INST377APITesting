TITLE: Federal Job Search Assistant for College Students 

Names: Megan Cha, Grace Gellerman, Collin Guo, Carlos Lopez Cento, Abraham Olaleye

Description: 
Searching for a job is a difficult task that most, if not all, working-age adults face, especially if you are a student also juggling part-jobs or extracurriculars. 
There are often problems with information overload or asymmetry on existing job platforms where they present too many options like some social media features and unrelated job categories. 
This can become overwhelming for individuals who do not know where or how to search for desirable jobs effectively. 
To address this difficulty, we hope to assist young professionals and students by creating an easier job board experience, targeting college students in particular. 

We would like to make a database for jobs only. Our database will connect with the skills API to provide job recommendations aligned with the student`s skill sets, ensuring they can easily discover roles matching their experience and education. 
This will operate similarly to existing platforms, such as LinkedIn and Handshake, but exclude other features that may be distracting and detracting such as social media aspects and event advertisements.

The following API will be used to help with our database. 
https://github.com/workforce-data-initiative/skills-api/wiki/API-Overview
This API would be suitable for use in applications and uses like recommendation systems, workforce training tools, and/or platforms that match workers to relevant job opportunities and openings based on their skills. 
This API helps us access to standardized, up-to-date information about job roles, skills, and their relationships across industries. 

Description of target browsers:
The main stakeholders in this case are the students themselves, hiring managers and agents, employers, career centers, and educational institutions who would want a platform tailored to their students` needs. 
Our target browsers are the students who are in search for federal jobs. 
This is an appealing sector and industry as it addresses many disciplines while offering a wide variety of jobs requiring many different skills.
Given our context, among the university students, we believe that this tool will be the most useful for third or fourth year students (such as ourselves) as they are directly starting to think about employment after college.
Not everyone has access to these resources or how to use them, so we aim to help bridge these barriers and ease anxieties with our program.

Link to Developer Manual: 
<a href="/Users/abrahamolaleye/Documents/GitHub/INST377APITesting/README.MD">Developer Manual</a>

## Prerequisites
Before you begin, ensure you have the following installed:

1. [Node.js](https://nodejs.org/) (Version 14 or higher recommended)
2. [npm](https://www.npmjs.com/) (Node Package Manager, installed alongside Node.js)
3. Supabase account and credentials (for database integration)

## Steps to Install

1. **Clone the repository**
   ```bash
   git clone <rehttps://github.com/ggellerm/INST377APITesting.gitpository-url>
   
   ```

2. **Install dependencies**
   Run the following command to install all required dependencies listed in `package-lock.json`:
   ```bash
   npm install
   ```

3. **Environment Configuration**
   - Create a `.env` file in the root directory.
   - Add the following environment variables with your Supabase credentials:
     ```env
     SUPABASE_URL=your_supabase_url
     SUPABASE_KEY=your_supabase_key
     PORT=3000
     ```

4. **Verify Installation**
   Run the following command to verify the application runs without errors:
   ```bash
   node script.js
   ```
   If everything is configured correctly, you should see relevant logs in the console.

---




[README.MD]: EADME.M