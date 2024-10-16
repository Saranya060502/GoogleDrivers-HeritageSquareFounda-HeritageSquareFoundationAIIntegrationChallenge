
# 2024_fall Hackathon Project

## Quick Links
- [Hackathon Details](https://www.ohack.dev/hack/2024_fall)
- [Team Slack Channel](https://opportunity-hack.slack.com/app_redirect?channel=team_10_googledrivers)
- [Nonprofit Partner](https://ohack.dev/nonprofit/QFPGmii2GmDPYrv5tjHA)
- [Problem Statement](https://ohack.dev/project/Ti4BEIpXMsrPWvrE8WC8)

## Creator
@Vesaun Shrestha (on Slack)

## Team "GoogleDrivers"
- Vesaun Shrestha https://github.com/vesaun
- Nathan So https://github.com/nthnco
- Saranya https://github.com/Saranya060502
<!-- Add all team members -->


## Getting Started
Instructions on how to set up and run your project locally.

```bash
git clone https://github.com/2024-Arizona-Opportunity-Hack/GoogleDrivers-HeritageSquareFounda-HeritageSquareFoundationAIIntegrationChallenge.git
cd GoogleDrivers-HeritageSquareFounda-HeritageSquareFoundationAIIntegrationChallenge
pip install openai
pip install Flask
pip install google-auth google-auth-oauthlib google-auth-httplib2
pip install google-api-python-client
pip install python-dotenv
pip install pypdf
pip install python-docx
pip install firebase-admin
```



## Inspiration
Docusort allows users to log in using their google email, and request files in a certain time frame or in a certain category.
No longer will you have to look through your documents and PDFs to find files related to your prompt, we will give them to you.
A problem that Heritage Square faced: A lack of a way to efficiently find the files they need to help them write and reply to those who use or give to their services.
As a result they were looking for an easy way to get files that could be suited to their needs, and thus make finding files more efficient. 

## What it Does
-Docusort allows the user to make a prompt such as "Give me accounting files from November 2020" and will return the links of the files they would like straight to them
-Gives easy access to pdf files and documents that they are seaching for, with room for error, which OpenAI will try and fill the gaps of knowledge as best as it can.
-A login feature using google drive, ensuring that no other user can access your files, thus providing security.
-An instruction's page clarifying the usage of the chat bot thus ensuring even the users with no prior knowledge of the technicality of the project could use it with no hussle.
-Associate files to the categories that we were given with a miscellaneous section.
-This gives Kari more time to help the community, and less time spent in her desk sorting through files.

## Challenges
-We ran into the challenge of finding the right database, due to our lack of experience in the field
-We also ran into the trouble of navigating Google Drive's APIs but we were able to persevere in the end and learn the calls.
-It costs money to maintain this, however, once we have set up the database and parsed through the files, OpenAI calls will go down significantly, so will Google Drive calls, thus allowing this to go on for longer

## Work Left
-For bigger goals, we need some more time, however the base model is ready to use now with some switches in API keys, whenever Kari wants to find some files falling in a certain category or date, she can use it now.


## Tech Stack
- Frontend: React.JS
- Backend: Flask, Python, Google OAuth 2.0
- Database: Firebase
- APIs: Google Drive, OpenAI

## Stretch Goals/Scalability
<!-- Add/modify as needed -->

- Due to the short time frame we were not able to complete all of the goals as we wanted, but our basic layout allows for massive scalability
- Stretch Goal 1: Implement AI into the prompt that allows you to ask for more abstract ideas with files, thus allowing more freedom and more suggestions to help you
- Stretch Goal 2: Since we already read through the files we parse, we could use OpenAI to pick key words out of files, which can then be of use for problem statement 1, since the AI will have context clues about every file going into the conversation with the user 

## Figma Designs
https://www.figma.com/design/0IMH0XPRifrdhROfrLTjfw/opprtunity-hack?node-id=0-1&node-type=canvas&t=m1IH1jr2QVpmC6Sa-0

![Screenshot 2024-10-13 010830](https://github.com/user-attachments/assets/5d88e832-a972-4586-82e9-94a106d5de7d)
![Screenshot 2024-10-12 194208](https://github.com/user-attachments/assets/eac3e94b-8771-4f75-b8a5-0560894fe7e8)

![Screenshot 2024-10-12 172358](https://github.com/user-attachments/assets/62da07df-3c4a-422c-8b67-ccc879b1c7aa)




## Your next steps
1. ✅ Add everyone on your team to your GitHub repo like [this video posted in our Slack channel](https://opportunity-hack.slack.com/archives/C1Q6YHXQU/p1605657678139600)
2. ✅ Create your DevPost project [like this video](https://youtu.be/vCa7QFFthfU?si=bzMQ91d8j3ZkOD03)
3. ✅ Use the [2024 DevPost](https://opportunity-hack-2024-arizona.devpost.com) to submit your project
4. ✅ Your DevPost final submission demo video should be 4 minutes or less
5. ✅ Review the judging criteria on DevPost

# What should your final Readme look like?
Your readme should be a one-stop-shop for the judges to understand your project. It should include:
- Team name
- Team members
- Slack channel
- Problem statement
- Tech stack
- Link to your DevPost project
- Link to your final demo video
- Any other information you think is important

You'll use this repo as your resume in the future, so make it shine! 🌟

Examples of stellar readmes:
- ✨ [2019 Team 3](https://github.com/2019-Arizona-Opportunity-Hack/Team-3)
- ✨ [2019 Team 6](https://github.com/2019-Arizona-Opportunity-Hack/Team-6)
- ✨ [2020 Team 2](https://github.com/2020-opportunity-hack/Team-02)
- ✨ [2020 Team 4](https://github.com/2020-opportunity-hack/Team-04)
- ✨ [2020 Team 8](https://github.com/2020-opportunity-hack/Team-08)
- ✨ [2020 Team 12](https://github.com/2020-opportunity-hack/Team-12)
