# Exclusive Games Selection Strategy (Business Proposal)

*Matteo Fortier*

## Abstract

The goal of this project was to produce a project proposal on how games can be selected to be exclusives for the epic games store. The purpose of the proposal was to help Epic Games in acheiving their target of overtaking Steam whilst decreasing the number of exclusives they release. Data from the Steam Store API and Steam Spy API was used for the analysis of games. Excel and Tableau were used for the preliminary analysis of the dataset. Classification models and unsupervised learning models were suggested as the solution path for this problem. Powerpoint was used to pitch the proposal. 

## Design

Opportunity:

The Epic Games Store has successfully garnered a large active user base for their PC games distribution platform. However, the store had an average of 56 million monthly active users in 2020, which is only half as much as Steam's 120 million monthly active users ([Source](https://backlinko.com/steam-users)). As a result, the company has been following an "aggressive pursuit model", spending 1 billion dollars on securing exclusive games in 2019 ([Source](https://www.pcgamer.com/uk/epic-games-has-spent-at-least-dollar1-billion-on-exclusives/)). While the model has successfully gathered its current users, the enormous spending is unsustainable; Epic's largest source of revenue, Fortnite, is diminishing, and the store itself has yet to turn a profit ([Source](https://www.ign.com/articles/fortnite-made-9-billion-in-two-years-while-epic-games-store-has-yet-to-turn-a-profit)). A clear problem arises: How can Epic reduce spending whilst still maintaining growth? 

Impact:
By understanding what games are successful (average hours played, current active players) in the Steam Store, Epic Games can more intentionally target specific games, or categories of games, to have as exclusives on their platform.

Data science solution path:

- Classification model to predict whether a game will be successful regarding platform engagement (hours played). Epic can secure exclusives for existing games that the model predicts to be successful in engagement. Alternatively, Epic can use the model to predict engagement for upcoming/unreleased games to assess whether it is worth securing as an exclusive for the platform. 
- Unsupervised clustering to better understand the types of games that exist concerning their engagement. Epic can use such a model to ensure a wide variety of games that lead to successful engagement are available in their store, potentially allowing to secure active users from a larger pool of all gamers. 

Success Metric:

The ultimate goal for Epic would be to overtake Steam as the industry leader. From 2019 to 2020, Steam's MAU (Monthly Active Users) grew 26%, while Epic's MAU grew 75%. Therefore, the very desirable goal would be to maintain Epic's current growth rate whilst decreasing new exclusives. Otherwise, it would be optimal for Epic to maintain a growth rate higher than Steam (whilst also decreasing exclusives), allowing the platform to become the industry leader eventually.

## Data

The project used data from the Steam Store API and the Steam Spy API. The data includes information on engagement statistics such as average and median hours played in the past two weeks/all time. The data also includes various categorical and numerical features such as developer, publisher, genres/tags, price, rating. I was assumed that games with high hours played can be a proxy for potential increases in monthly active users, the growth metric for the store. 

## Algorithms

Excel was used to clean and combine data. Excel and Tableau was used to perform preliminary exploratory data analysis and visualisations. Pandas was was used to create dummy variables for certain categorical features.

## Tools

Pandas and Jupyter Notebook was used to ingest data from the APIs.

Excel was used to clean, aggregate and explore data. 

Tableau was used to explore and visalise findings. 

Powerpoint was used to deliver the pitch. 

## Communication

The project used powerpoint for the presentation.



