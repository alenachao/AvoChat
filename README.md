# AvoChat - Codeology Spring 2024
Who knew bringing your favorite character to life could make a great CS project? In this project, you will build an AI Discord chatbot that speaks like your beloved character of choice. Learn about APIs, machine learning models, and project deployment on the way!

## The Members
Project Manager: Kerrine Tai\
Project Leaders: Alena Chao, Danny Tran\
Project Members: Amber Gupta, Angie Baik, Larissa Tsai, Shing Gao, Xina Wang

## Set up
1. Training Model\
You will need to run `model_train.ipynb` on the  `the-office_lines.csv` to output the necessary model. The model will need to be in the project directory at the same level as `model.py`

2.  Install Requirements
```
pip install -r requirements.txt
```
Additionally, you will need to [set up a Discord Bot](https://discord.com/developers/docs/reference) and have the api key copied for the next step.

3. Set environment variables in a `.env` file
```
DISCORD_TOKEN="YOUR_DISCORD_TOKEN"
```
4. Run it
```
python model.py
```
To have the bot running 24/7, our project members used [Google Cloud Platform](https://cloud.google.com/gcp?utm_source=google&utm_medium=cpc&utm_campaign=na-US-all-en-dr-bkws-all-all-trial-e-dr-1707554&utm_content=text-ad-none-any-DEV_c-CRE_665735450627-ADGP_Hybrid+%7C+BKWS+-+EXA+%7C+Txt-Core-Google+Cloud-KWID_43700077223807301-kwd-26415313501&utm_term=KW_google+cloud+platform-ST_google+cloud+platform&gad_source=1&gclid=CjwKCAjwl4yyBhAgEiwADSEjeAbDoZZEPWPR5PCUENjz5ggsrwrVk7ExZdCzPu-NDts15CNtgYgCEhoC_IYQAvD_BwE&gclsrc=aw.ds&hl=en).
