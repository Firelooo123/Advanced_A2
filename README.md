# MediMatch

## Project overview
* This solution is used to help detect medication labels on pills or prescriptions for elderly people. This labels will be translated with a built in translator to translate the information into the 4 common mother tongues of Singapore. They can then use a chatbot to explain the instructions to them. Through this, we hope to reduce medical non-adherence and allow the elderly to be more independent instead of relying on others to read and learn the medication labels

## Project Setup
For our project, here is the setup of our project. The app is hosting on streamlit website.

Visual Code:
1. Install Python 3.8+ in visual code
2. Download the 'website' folder
3. Create a virtual environement
4. Activate the environment
5. install dependencies ('pip install -r requirements.txt')
6. Run streamlit website! (streamlit run home.py)

## Project content
1. Website: This can be used in both mobile and on a laptop, due to the responsive nature of streamlit.
   css folder
   images folder
   best.pt (YOLO model)
   home.py (home-page)
   medications.csv (mock database)
   requirements.txt

## Features:
1. Chatbot that explains medical instructions with inbuilt translator.
2. MediMatch Model extracts medication info from medication label and adds to a database for user to check.
3. Allows user to check their medication history

### Model Used Citation:
1. Yolo (https://docs.ultralytics.com/)

### Take Note:
1. Dataset is sensitive as it has sensitive information of family member names, so if u would like the dataset, please contact one of the team members

## Contributing Members
1. Jeremy Yeo
2. Callum Fu
3. Marcus Ong
