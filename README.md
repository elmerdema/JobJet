# Career Services Chatbot - "JobJet"

Dema, Elmer,  <br>


## Project description

JobJet is a robust career service chatbot designed to assist job seekers in finding the perfect job match. Leveraging the power of Rasa and Python, JobJet provides an intuitive and interactive conversational experience for users navigating the complex world of job hunting. In addition to Rasa and Python, Flask is employed to handle essential endpoints, enhancing the functionality and seamless integration of features. <br>


JobJet uses Flask to handle various endpoints:

- **Register:**
  - Endpoint: `/register`
  - Method: `POST`
  - Description: Allows users to register for JobJet.

- **Login:**
  - Endpoint: `/login`
  - Method: `POST`
  - Description: Handles user login for JobJet.

- **Job Lookup:**
  - Endpoint: `/job_lookup`
  - Method: `GET`
  - Description: Retrieves job information based on user queries.

- **Invite:**
  - Endpoint: `/invite`
  - Method: `POST`
  - Description: Sends job invitations to selected candidates.


## Installation

<!-- Descriptions of the used packages with versions, e.g. Python 3.10, rasa 3.6.12, ...

Description of the steps after cloning the MyGit repository (setting up a venv, installing the packages, test of the setup, ...). -->

### Requirements

- Python 3.10.13
- Rasa 3.6.12
- Rasa SDK 3.6.2

### Installation steps

1. Clone the repository
```
git clone https://mygit.th-deg.de/jz19337/speech-assistant.git
```
2. Create a virtual environment
```bash
python3 -m venv venv
```
3. Activate the virtual environment
```bash
.\venv\Scripts\activate
```
4. Install the requirements
```bash
pip install -r requirements.txt
```

## Basic Usage

How to start the chatbot after installation is complete (typically with `rasa run` and `rasa shell`)
```bash
rasa run
```

Example of a typical conversation
```
Hans: I would like to apply for some jobs


Deggster: Of course, Hans! What position would you like to apply?

[Deggster checks if the position exists]

Hans: I would like to apply for Web Developer positions


[ Deggster retrieves the job postings from Emma]


Deggster: Here are some developer job openings I found: Full Stack Developer, Junior Front-End Developer, Back-End Engineer. Would you like to apply for one of the following positions


Hans: Yes,I would like to apply for the Full Stack Position

[Deggster applies for the position]

Deggster: The application was successful.



```
```
Use Case 2: Recruiter Wants to Invite Working Students for an Interview

Otto: Hello, Deggster! I'm looking to invite a student for an interview


Deggster: Absolutely, Otto! What is the username of your student?


Otto: His username is jz1337

[Deggster check if the user exists]
[Deggster invites the user]

Deggster: The user has been successfully invited
```

## Implementation of the Requests

Requests are

- Check for right fit [DONE]
- 1 system persona and 3 user persona [DONE]
- At least 5 use cases [DONE]
- Find the technical prerequisites [DONE]
- For every persona at least 2 example dialogs [DONE]
- A dialog flow [DONE]
- Implementation in rasa (yaml and Python files)

## Work done


## References

- [Rasa Documentation](https://rasa.com/docs/rasa/)
- [Google Conversation Design](https://developers.google.com/assistant/conversation-design/)
- [Rasa Chatbot Tutorial](https://www.youtube.com/playlist?list=PL75e0qA87dlEjGAc9j9v3a5h1mxI2Z9fi)