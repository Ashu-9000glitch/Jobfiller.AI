# Jobfiller.AI
JobFiller.AI
JobFiller.AI is a desktop AI assistant that helps users fill job application forms faster by scanning form fields, understanding the question, and generating tailored answers based on the user’s profile and the company’s job description.
It runs as a small overlay on the bottom-left of the screen, keeps answers ready to copy, and automatically copies the generated response to the clipboard so the user only needs to press Ctrl + V.
________________________________________
What it does
•	Stores your profile details once, so you do not need to enter them again and again.
•	Lets you upload your resume inside the app for better AI responses.
•	Scans job descriptions and application forms using OCR.
•	Uses the Gemini API to generate answers tailored to the job description.
•	Automatically copies answers to the clipboard for quick pasting.
•	Supports a Quick Fill Mode that answers basic profile-based fields from the local database without calling AI every time.
________________________________________
Why I built it
Filling out job applications manually is repetitive and time-consuming.
Most applications ask the same questions again and again, such as name, email, phone number, education, LinkedIn, and work history.
JobFiller.AI reduces this effort by:
•	answering profile-based questions locally,
•	using AI only when needed,
•	and keeping the workflow fast, simple, and distraction-free.
________________________________________
How it works
1.	User fills profile details once inside the app.
2.	User uploads resume.
3.	User scans the job description, and the AI understands the context.
4.	User opens the application form.
5.	User clicks on scan.
6.	User clicks on text field
7.	The app matches the field and shows the answer.
8.	The answer is copied automatically to clipboard.
9.	User pastes it directly using Ctrl + V.
________________________________________
Quick Fill Mode
JobFiller.AI includes a Quick Fill Mode to reduce dependence on AI.
In this mode:
•	basic fields like name, email, phone, LinkedIn, GitHub, portfolio, address, and education are answered from the local profile database,
•	company-specific or open-ended questions like “Why do you want to join us?” are answered by AI,
•	making the process faster and more reliable.
________________________________________
Screenshots
1. Main Overlay
 <img width="939" height="586" alt="image" src="https://github.com/user-attachments/assets/87a8bf4b-6e6e-421b-b2af-542550df3d5d" />

2. Profile Setup
 <img width="906" height="1283" alt="image" src="https://github.com/user-attachments/assets/17de118e-ce80-4321-af95-becf6b286363" />
<img width="788" height="716" alt="image" src="https://github.com/user-attachments/assets/b2875b1d-6615-4a42-98a9-538a556d3b8a" />

 
3. Job Description Scan
 


<img width="939" height="586" alt="image" src="https://github.com/user-attachments/assets/fe764623-9cfa-4989-af65-2f66a9f9cda5" />



4. Form Field Scan  
 

<img width="939" height="586" alt="image" src="https://github.com/user-attachments/assets/a58bce69-1be8-40df-8844-9ae700defb7d" />


<img width="788" height="716" alt="image" src="https://github.com/user-attachments/assets/cc8c81c7-d507-4014-8013-47a70462bac6" />



5. Auto Copy to Clipboard
 
<img width="939" height="558" alt="image" src="https://github.com/user-attachments/assets/c35b68db-add8-490d-bbdd-f1455858e429" />


6. Answers from Profile
 
<img width="569" height="229" alt="image" src="https://github.com/user-attachments/assets/4a53247b-43bf-4a44-8770-f69e5b88a829" />


7. Answers from AI
   

<img width="615" height="340" alt="image" src="https://github.com/user-attachments/assets/60d9cf39-16eb-42ab-9501-a2ba4b07139f" />

<img width="939" height="586" alt="image" src="https://github.com/user-attachments/assets/ee9cc48f-633e-4610-a6a2-72a54155ec30" />


________________________________________
Tech Stack
•	Python
•	PyQt6
•	Gemini API
•	OCR
•	Fuzzy Matching
•	Clipboard Automation
•	Local Profile Database
________________________________________
Key Features
•	Floating bottom-left overlay
•	One-time profile setup
•	Resume upload support
•	JD-aware AI responses
•	Local answer matching for common fields
•	Auto-copy to clipboard
•	Quick Fill Mode
•	Faster job application filling
________________________________________
Impact
JobFiller.AI helps reduce repetitive form-filling work, improves speed, and makes job applications less frustrating.
It is designed to save time, reduce manual effort, and let users focus more on applying than copying the same information repeatedly.
________________________________________
Future Improvements
•	Better form-field detection
•	Smarter JD parsing
•	Browser extension support
•	Multi-profile support
•	More robust offline fallback

