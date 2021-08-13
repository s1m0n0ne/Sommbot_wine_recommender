# Sommbot_wine_recommender
This is the repository for Sommbot chatbot which can engage customers and make wine recommendations

# Sommbot_wine_recommender
This is the repository for Sommbot chatbot which can engage customers and make wine recommendations

This will showcase our project for the Artificial Intelligence Course done during the IBM-SGUnited Mid-career Pathways Programme for The Wine Sommelier Chatbot which was a collaborative work between Alvin Quek, Charlotte Queck, Eugene Ong and Seamus Wan. 

We have a presentation that covers our working process from Project Conceptualisation to Implementation, feel free to download the pdf to understand more. 

Skillsets which we had applied during the project were as follows : -

Planning to Building stage
Design Thinking
Cloud Architecture Planning
Data Science
Data Cleansing
Data Structuring
Artificial Intelligence
Watson Assistant
Watson Discovery

Software / Platforms which were applied during the project process : - 

1. Microsoft Excel - Xls, csv
2. Google Drive - Collaborative use on data editing 
4. Watson Studio - Collaborative use of Watson Assistant and Watson Discovery
5. Mural - Design thinking 

# Create an Action using Watson Assistant
By taking a no-code approach, this page includes a Watson Assistant workspace to demonstrate an implementation of a Wine Sommelier chatbot agent that can provide wine recommendations and specifics. To demonstrate how to test it with Watson Discovery Search Skill, we will set up a Watson Discovery that calls out to our Node.js server which interacts with Watson Assistant.

When the reader has completed this page, they will understand how to:
1. Create a Watson Assistant
2. Create a Watson Discovery Search Skill
3. Deploy Watson Assistant Chatbot on IBM Cloud to Wix Website 
4. Deploy Watson Assistant Chatbot on IBM Cloud to Whatsapp via Twilio
5. Interact with Watson Assistant
6. Use the conversation token to maintain the context
7. Leverage the content catalog for general, customer care, and bot control intents
8. Handle digressions during a conversation

# Inspiration
Our team hails from Singapore which is a cosmopolitan city in South-East Asia. Singapore is well-known for its good food and is rapidly developing into a wine hub. Good food accompanied by a great wine is something our team enjoys.
A food and beverage chatbot is something of a rarity among AI projects, so our team decided to challenge ourselves by working on a topic that everyone can relate to and enjoy.
We think that our chatbot has untapped potential and opportunities for further application. If you have any ideas, breakthroughs, or other interesting insights please post them.
We welcome constructive feedback and tips, and hope this chatbot inspires many more food and beverage chatbots!

# Contact Information
Alvin Quek: aq.impossible@gmail.com

Charlotte Queck:charlottequeck@gmail.com

Eugene Ong: eugene.ong0712@gmail.com

Seamus Wan: seamuswan@live.com
 
# Dataset Overview
We searched for food and beverage datasets on Kaggle and found the Wine Review dataset. We were looking for a medium-sized dataset that would require some data processing but did not require extensive data cleansing. 

The data was initially scraped from Wine Enthusiast Magazine during the week of June 15th, 2017 and again on November 22nd 2017. It comprises of 120,000 wine reviews in one csv file of about 53 MB:

Winemag-data-130k-v2.csv contains 12 columns and 129K+ rows of Wine Reviews scraped from Wine Enthusiast during November 22nd 2017
Each record in the dataset represents a single wine review from an online user of Wine Enthusiast Magazine
The following is a brief summary of the 10 different columns of data included in winemag-data-130k-v2.csv:

<img src="https://github.com/s1m0n0ne/Sommbot_wine_recommender/blob/main/images/wine%20dataset%20screenshot.png">

# Data Columns
1. Country - The country of origin of the wine.
2. Description - The description of the wine's flavor profile.
3. Designation - The vineyard where the wine's grapes are sourced.
4. Points - The number of points Wine Enthusiast Magazine rated the wine on a scale of 1-100.
5. Price - The cost for a single bottle of the wine.
5. Province - The province or state that the wine is from.
6. Region 1 - The wine growing area in a province or state (for example, Napa Valley in California).
7. Region 2 - (Optional) A more specific region in a wine growing area (for example, Rutherford inside Napa Valley).
8. Taster Name - Name of the Reviewer
9. Taster Twitter - Twitter handle of the Reviewer
10. Title - Name of the wine
11. Variety - The type of grapes used to make the wine (for example, Pinot Noir).
12. Winery - The winery that made the wine.

# Project Flow 
<img src="https://github.com/s1m0n0ne/Sommbot_wine_recommender/blob/main/images/Flow_ToolsForChatbot.png">
Diagram shows tools used for chatbot

Watson Assistant

Steps to create Watson Assistant Service:
1. Create Watson Assistant Service
2. Create an assistant
3. Create a dialog skill
4. Add intents from a content catalog
5. Build a Dialog
6. Add Your Skill to Your Assistant
7. Integrate the Assistant

# Tools
Watson Assistant

# Create Watson Assistant Service
Steps to create Watson Assistant Service:

1. Login into IBM Cloud: https://cloud.ibm.com
2. Click the Catalog tab.
3. Search for the Watson Assistant service and click tile under the AI heading.



4. Fill out the necessary information and click Create.
After you create a Watson Assistant service instance, you land on the Manage page of the Watson Assistant dashboard.
5. Click Launch Watson Assistant. If you're prompted to log in, provide your IBM Cloud credentials.
A new browser tab or window opens, and the Assistants page of Watson Assistant is displayed.
• An assistant named My first assistant is created for you automatically. An assistant is a cognitive bot to which you add skills that enable it to interact with your customers in useful ways.


1. Create Watson Assistant Service
2. Create an assistant
3. Create a dialog skill
4. Add intents from a content catalog
5. Build a Dialog
6. Add Your Skill to Your Assistant
7. Integrate the Assistant

