# Career Services Chatbot - "JobJet"

Dema, Elmer,  <br>


Repository: https://mygit.th-deg.de/jz19337/speech-assistant

## Project description

JobJet is a career service chatbot that helps job seekers find the right job. It is built using Rasa and Python. You can find the structure of the chatbot at https://mygit.th-deg.de/jz19337/speech-assistant/-/wikis/Home. The project structure is as follows: <br>

```
in progress...
```
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
(TODO: Add example conversation image)
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