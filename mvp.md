# MVP

*Matteo Fortier*

### Opportunity

The Epic Games Store has successfully garnered a large active user base for their PC games distribution platform. However, the store had an average of 56 million monthly active users in 2020, which is only half as much as Steam's 120 million monthly active users ([Source](https://backlinko.com/steam-users)). As a result, the company has been following an "aggressive pursuit model", spending 1 billion dollars on securing exclusive games in 2019 ([Source](https://www.pcgamer.com/uk/epic-games-has-spent-at-least-dollar1-billion-on-exclusives/)). While the model has successfully gathered its current users, the enormous spending is unsustainable; Epic's largest source of revenue, Fortnite, is diminishing, and the store itself has yet to turn a profit ([Source](https://www.ign.com/articles/fortnite-made-9-billion-in-two-years-while-epic-games-store-has-yet-to-turn-a-profit)). Thus Epic plans to decrease the number of exclusives it plans to secure each year, from 52 in 2021 to 36 in 2022. 

Hence, knowing which games are most likely to grow Epic's platform is valuable, seeing as they cannot continue buying every game that exists. Epic would prioritise which games they obtain exclusive rights to based on their predicted impact on the platform. 

### Desired Business Impact

The ultimate goal for Epic would be to overtake Steam as the industry leader. From 2019 to 2020, Steam's MAU (Monthly Active Users) grew 26%, while Epic's MAU grew 75%. Therefore, the very desirable goal would be to maintain Epic's current growth rate whilst decreasing new exclusives. Otherwise, it would be optimal for Epic to maintain a growth rate higher than Steam (whilst also decreasing exclusives), allowing the platform to become the industry leader eventually.

Best case growth metric: MAU increase of 75+%

Optimal case growth metric: MAU increase of 26+%

### Solution Path

Public data on Steam Store games are easily accessible via various APIs, namely the Steam Store API and Steamspy API. 

The data includes information on engagement statistics such as average and median hours played in the past two weeks/all time. The data also includes various categorical and numerical features such as developer, publisher, genres/tags, price, rating. 

https://www.kaggle.com/nikdavis/steam-store-games

With the above data, the following analyses are possible:

- Classification model to predict whether a game will be successful regarding platform engagement (hours played). Epic can secure exclusives for existing games that the model predicts to be successful in engagement. Alternatively, Epic can use the model to predict engagement for upcoming/unreleased games to assess whether it is worth securing as an exclusive for the platform. 
- Unsupervised clustering to better understand the types of games that exist concerning their engagement. Epic can use such a model to ensure a wide variety of games that lead to successful engagement are available in their store, potentially allowing to secure active users from a larger pool of all gamers. 

![figure 1](</figure 1.png>)

![figure 2](</figure 2.png>)

### Impact Hypothesis

By understanding what games are successful (average hours played, current active players) in the Steam Store, Epic Games can more intentionally target specific games, or categories of games, to have as exclusives on their platform.

### Potential Pitfalls

- The current growth rate of 75% cannot be maintained without the current spending on exclusives. 
- Growth rate isn't only related to which exclusives exist on the platform, but also the usability of the platform. (Built-in chat, friends lists, user profile - All of which have been polished throughout years on the Steam platform)
