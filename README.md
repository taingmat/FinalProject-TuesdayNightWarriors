SHINY APP LINK: https://taingmat.shinyapps.io/FinalProject-TuesdayNightWarriors/

# Purpose
Provide a way for users to compare phone specs visually to make an informed decision before purchasing a new device.

# Project Description:
For our final project we've made an interactive shiny app which allows users to compare specifications between different models of smartphones graphically. The app allows users to filter smartphones down to the ones that meet their preferred specs. It then provides up to 3 graphs comparing specifications of up to 3 smartphones the user would like to compare. A more detailed table about the phone specs simultaneously appears beneath the graphs.

# Target Audience
Our target audience is people looking to compare phones, be it to replace their own or simply to understand what the market is offering. To make an educated purchase, it is important for consumers to have access to detailed comparisons between models and specifications of smartphones. Our App will allow users to make informed decisions when choosing which phone best suits them, based on specifications that matter the most to them.

# About the Data:
The dataset of smartphone specifications is scraped from the website GSMArena by the user Arwin Neil Baichoo, and can be found on Kaggle. A limitation our dataset faces is that it hasn't been updated in 5 months, and given the rapid pace at which technology changes, this means users can't compare information about the most recent phones.

# Reformatting the Data:
The original dataset was atrocious, failing to follow consistent formatting within columns. As a result, we were required to reformat much of our data manually through excel and in R, to make certain specs Filterable/Comparable. For example, the current column 'internal ram' is recorded as the string "16 GB"", but we'd prefer it to be stored as the number "16" to make it easier to graph. In addition to that, some columns store multiple values in a single cell. For example, the 'primary_camera' column contains some values containing a single value in megapixels, while others include information about flash and autofocus capabilities.

A big part of this project was determining what information consumers are genuinely concerned with, and which ones are worth comparing by. For example we understood that it was worth being able to filter by CPU speed, but unnecessary to allow users to filter by display_type. As most users likely wouldn't understand the differences between the wide array of possible display types.


# Resources:
Phone Data: https://www.kaggle.com/arwinneil/gsmarena-phone-dataset/version/1
GSM Arena: https://www.gsmarena.com/
