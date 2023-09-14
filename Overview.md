**1\. Background**
==================

E-sports transforms online gaming into a spectator sport and is projected to grow to USD 6.75 billion by 2023. In this competition, participants will have the opportunity to leverage a comprehensive dataset from the popular shooter game Counter Strike Global Offensive, 

### 1.1. About Counter Strike Global Offensive (CSGO)

Counter-Strike Global Offensive is a highly competitive team-based first-person shooter developed by Valve Corporation. Despite being released back in 2012, it continues to attract 800,000 to 900,000 monthly active players from all around the world.

![CSGO Map Mirage (Source: TOBYSCS)](https://api.datameka.com:8080/media/uploads/user/b799266d-430e-4b9e-baf4-95635ed2aa16/DRipKdE6Fv69JcGk5F5VLg.webp)

The game is played between two teams, the terrorists and the counter-terrorists, consisting of 5 players each. Teams start from designated areas on the map. The terrorists' goal is to plant the bomb at either site A or B. Once planted, the bomb will explode in 45 seconds. Each round lasts for 2 minutes. Counter-terrorists must stop the terrorists from planting the bomb by eliminating them or defusing the bomb within a 10-second timeframe to prevent the explosion.

-   **Objective of terrorists** Plant and blow a time bomb at specific locations on the map

-   **Objective of counter-terrorists** Prevent the bomb from being planted or defuse it if already planted.

-   **Alternate win condition** Eliminate the entire opposing team before the objective is completed.

### 1.2. Video Resources About CSGO

Please watch the videos for detailed game explanations and actual gameplay!

**2\. Problem Statement**
=========================

The goal of this competition is to discover valuable insights from the provided CSGO dataset. While there are potential use cases such as predicting the winning team, predicting player trajectories, and identifying winning strategies, participants are **NOT limited to these specific tasks**. Participants are encouraged to generate their own ideas on how the data can be used to create valuable insights into player behavior, team dynamics, and winning strategies, which will help to improve the in-game experience. 

### 2.1. Ideas for the potential use case

**Calculate the winning probability in real-time**

Many factors play a crucial role in determining the outcome of a Counter-Strike match. Consequently, it can be challenging for the audience to discern which team has the upper hand. Unlike humans, AI excels at extracting evidence from multiple factors and swiftly predicting the team likely to emerge victorious. Therefore, one potential application of the dataset is to train a real-time winning prediction model that supervises the audience to know the dominating team in the ongoing quickly.

![One potential use case of the dataset is to train a real-time winning prediction model that supervises the audience to quicly know the dominating team in the ongoing match.](https://api.datameka.com:8080/media/csgo_image_1.gif)

**Identify common areas on the map where player deaths occur**

Where are the common death locations? Using the "kills" logs of the provided CSGO data, we can plot the locations where the death occurs for terrorists and counter-terrorists each. Below is a heatmap displaying death locations on a map called "Mirage".

![Heatmap of common death locations on Mirage](https://api.datameka.com:8080/media/uploads/user/b799266d-430e-4b9e-baf4-95635ed2aa16/hY9jnptHyXAszNqP2z8bwX.webp)

![Actual game play and death locations](https://api.datameka.com:8080/media/csgo_image_2.gif)

Upon visual examination, we observe a high concentration of player deaths around bombsite A, located at the bottom middle part of the map and the middle connector area. The close proximity of these locations implies that bomb site A is a spot for close-distance combat engagements. In contrast, bombsite B, positioned at the top left corner of the map, seems to offer opportunities for more long-range shooting encounters and diverse tactical approaches.

3\. Submission
==============

Participants are required to submit their idea in the form of an **Article**. The article should include the following components:

-   **Explanation Your Presented Ideas**

    -   Present your ideas and any novel discoveries derived from the data. Please write more than 150 words (about 1 paragraph) for the explanation.

-   **Visualizations**

    -   Utilize visualizations effectively to convey the results and insights.

-   **Code Snippets**

    -   Model Building: If you perform any modeling analysis, please include the steps for data preprocessing, model building, and model result validation in your submission.

    -   Visualization Code: Please include the code used to generate the visual assets in your submission.

Please note that each participant is allowed to submit only one blog article. If you have multiple ideas, we encourage you to consolidate them into a single comprehensive article and organize them accordingly.

**4\. Evaluation**
==================

### 4.1. Method: Voting

After the final submission, all participants and the DataMeka panel will have the opportunity to publicly view and evaluate the blog posts submitted by participants. Each individual, including regular participants and DataMeka panel members, can **click on upvote** for the articles they find insightful. 

-   Regular participants' votes will be counted as 1.

-   DataMeka panel members' votes will be counted as 5.

Once the evaluation period is over, the top three articles with the highest number of votes will be selected, and the authors or teams behind those articles will be recognized and rewarded.

### 4.2. Team Submission

Please note that for team participants, all individual members can submit their articles. However, only the article with the highest number of votes among the team members' submissions will be selected and considered as the team's official submission.

**5\. Prize**
=============

A total prize pool of 500 SGD will be distributed among the top participants as follows:  

-   **First Prize**: 250 SGD 

-   **Second Prize**: 150 SGD 

-   **Third Prize**: 100 SGD 

**6\. Timeline**
================

-   **12 June 2023 -** Pre-enrollment

-   **19 June 2023 **- Submission starts

-   **25 Aug 2023** - Submission deadline

-   **1 Sep 2023** - Winner announcement

**7\. Acknowledgement **
========================

DataMeka acknowledges and appreciates Peter Xenopoulos for sharing the [ESTA data](https://github.com/pnxenopoulos/esta) and creating the [awpy](https://awpy.readthedocs.io/en/latest/parser_output.html) Python package. Their contributions have provided data enthusiasts with exciting opportunities to explore high-quality in-game data and enabled DataMeka to host this competition.
