Data Format
-----------

-   The provided data consists of compressed files capturing the gameplay of top performers from January 2021 to May 2022.

-   To utilize the data, you need to decompress the files, extracting JSON files containing in-game data.

-   If you encounter challenges in decompressing and transforming the JSON files, refer to the example notebook provided for guidance.

-   The dataset includes two types of games: LAN games (680 games) and Online games (878 games).

-   Each decompressed JSON file is approximately 70 to 80 MB in size, making it difficult to analyze entire games for analysis purposes.

-   We recommend starting with a portion of the data and gradually increasing the number of games for analysis, allowing for more manageable exploration and understanding of the dataset.

Data Description
----------------

Participants will have access to the following datasets:

1.  Frame Data:

    -   This dataset consists of time-series data snapshots at specific time points for both terrorists and counter-terrorists sides

    -   Each entry includes information such as the player's name, team, side, coordinates (x, y, z), velocity, view angles, health points, armor, active weapon, utilities, and various game-related flags (e.g., alive, blinded, defusing, planting)

2.  Kills Data:

    -   This dataset records information about kills made during gameplay

    -   Each entry includes details about both the attacker and the victim (name, team, side, coordinates, view angles) along with the kill type, such as a suicide, team kill, wallbang, first kill, headshot, or trade kill

3.  Damages Data:

    -   This dataset contains information about the damages inflicted by players during gameplay

    -   Information about damage dealt to health points, armor, hit group, distance, and other attributes is included

4.  Grenades Data:

    -   This dataset captures information about grenade usage during gameplay.

    -   Information such as player location, the throw and destroy times is provided.

5.  Weapon Fires Data:

    -   This dataset records instances of weapon firing during gameplay.

    -   Details such as shot time, location, weapon type, class, ammunition, zoom level, and other attributes are provided.

6.  Flashes Data:

    -   This dataset captures instances of flashbang usage during gameplay.

    -   Information such as player location, the throw and flash duration is provided.

-   For additional information on the data, kindly refer to the link provided by the original data provider: [Esports Trajectories & Actions (ESTA)](https://github.com/pnxenopoulos/esta).
