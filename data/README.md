# Data
-   The data set that I chose comes from Tidy Tuesday 2025-02-04 and is all about the Simpsons, which is a very popular adult animated sitcom. This data was originally from The Simpsons Dataset on Kaggle. The data set contains four tables each highlighting a different aspect of the show. The tables include characters, episodes, locations, and script lines. The data is very large (with the show having so many seasons), with the character data frame including 6722 rows and script lines data frame containing 31793 rows.

Link to original data set: <https://www.kaggle.com/datasets/prashant111/the-simpsons-dataset>

Link to TidyTuesday: <https://github.com/rfordatascience/tidytuesday/tree/main/data/2025/2025-02-04>

# Codebook for Dataset

Codebook sourced from TidyTuesday <https://github.com/rfordatascience/tidytuesday/tree/main/data/2025/2025-02-04>

# `simpsons_characters.csv`

| variable        | class     | description                                 |
|:----------------|:----------|:-------------------------------------------|
| id              | double    | Unique identifier for each character record.          |
| name            | character | Full name associated with the character record.       |
| normalized_name | character | Lowercase version of the character name.           |
| gender          | character | Gender associated with the character record.          |

# `simpsons_episodes.csv`

| variable               | class     | description                                         |
|:-----------------------|:----------|:---------------------------------------------------|
| id                     | double    | Unique identifier for each episode record.                 |
| image_url              | character | URL linking to the image associated with the episode record. |
| imdb_rating            | double    | IMDb rating for the episode. |
| imdb_votes             | double    | Number of votes received on IMDb for the episode. |
| number_in_season       | double    | Episode number within the season. |
| number_in_series       | double    | Episode number within the series. |
| original_air_date      | date      | Date the episode originally aired. |
| original_air_year      | double    | Year the episode originally aired. |
| production_code        | character | Code used in production to identify the episode. |
| season                 | double    | Season number of the episode. |
| title                  | character | Title of the episode. |
| us_viewers_in_millions | double    | Number of viewers in the U.S. in millions. |
| video_url              | character | URL linking to the video associated with the record. |
| views                  | double    | Total number of views recorded for the episode video URL. |

# `simpsons_locations.csv`

| variable        | class     | description                                 |
|:----------------|:----------|:-------------------------------------------|
| id              | double    | Unique identifier for each location.        |
| name            | character | Name of the location.                       |
| normalized_name | character | Lowercase version of the location name.  |

# `simpsons_script_lines.csv`

| variable           | class     | description                                              |
|:-------------------|:----------|:--------------------------------------------------------|
| id                 | double    | Unique identifier for each script line. |
| episode_id         | double    | Identifier for the episode in which the line appears. |
| number             | double    | Sequential number of the line within the episode. |
| raw_text           | character | The original text of the script line. |
| timestamp_in_ms    | double    | Timestamp of the line in milliseconds. |
| speaking_line      | logical   | Indicates whether the line is spoken by a character. |
| character_id       | double    | Identifier for the character speaking the line. |
| location_id        | double    | Identifier for the location where the line is spoken. |
| raw_character_text | character | Original text of the character's name. |
| raw_location_text  | character | Original text of the location name. |
| spoken_words       | character | Words spoken by the character in the line. |
| normalized_text    | character | Lowercase version of the script line. |
| word_count         | double    | Number of words in the line. |
