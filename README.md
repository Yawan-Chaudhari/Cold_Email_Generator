# 📧 Cold Mail Generator
Cold email generator for services company using groq, langchain and streamlit. It allows users to input the URL of a company's careers page. The tool then extracts job listings from that page and generates personalized cold emails. These emails include relevant portfolio links sourced from a vector database, based on the specific job descriptions.

![image](https://github.com/user-attachments/assets/15b1c1b6-0c7f-4340-842b-419120d461da)

# Architecture Diagram

![image](https://github.com/user-attachments/assets/6b14d610-270d-4f1c-a335-bc81340ca972)

# Set-up

1. To get started we first need to get an API_KEY from here: https://console.groq.com/keys. Inside app/.env update the value of GROQ_API_KEY with the API_KEY you created.
2. To get started, first install the dependencies using:

`pip install -r requirements.txt`

3. Run the streamlit app:

`streamlit run app/main.py`





