# USC X 24 US Election Twitter/X Dataset

This repository contains multiple directories named `part_{part_number}`, where each part consists of chunk files prefixed with the timeline. Each chunk file contains 50,000 tweets related to the US election.

## Repository Structure

```
usc-x-24-us-election/
├── part_1/
│   ├── timeline_chunk_1.csv.gz
│   ├── timeline_chunk_2.csv.gz
│   └── ...
├── part_2/
│   ├── timeline_2_chunk_21.csv.gz
│   ├── timeline_2_chunk_22.csv.gz
│   └── ...
├── part_3/
│   ├── timeline_3_chunk_41.csv.gz
│   ├── timeline_3_chunk_42.csv.gz
│   └── ...
└── ...
```

## Cloning the Repository

To clone this repository, use the following command in your terminal:

```bash
git clone https://github.com/sinking8/usc-x-24-us-election.git
```

This will create a local copy of the repository on your machine.

## Data Description

- Each directory `part_{part_number}` contains chunk files that are prefixed with the timeline name.
- Each chunk file consists of **50,000 tweets** related to the US election, allowing for extensive data analysis and processing.

## Data Schema

| **Field Name**                  | **Data Type**          | **Description**                                                     |
|----------------------------------|-----------------------|---------------------------------------------------------------------|
| id                               | object                | Unique identifier for each entry.                                   |
| text                             | object                | Text content of the tweet.                                         |
| url                              | object                | URL associated with the tweet or content.                         |
| epoch                            | object                | Epoch timestamp when the tweet was created.                       |
| media                            | object                | Media content included in the tweet (images, videos, etc.).      |
| retweetedTweet                   | object                | Content of the retweeted tweet, if applicable.                    |
| retweetedTweetID                 | object                | ID of the retweeted tweet.                                         |
| retweetedUserID                  | object                | ID of the user who originally tweeted the retweeted content.      |
| id_str                           | object                | ID of the tweet as a string (alternative format).                 |
| lang                             | object                | Language of the tweet content.                                     |
| rawContent                       | object                | Raw unprocessed text of the tweet.                                 |
| replyCount                       | object                | Number of replies to the tweet.                                    |
| retweetCount                     | object                | Number of retweets.                                               |
| likeCount                        | object                | Number of likes.                                                  |
| quoteCount                       | object                | Number of quotes.                                                 |
| conversationId                   | object                | ID of the conversation the tweet is part of.                      |
| conversationIdStr                | object                | Conversation ID as a string.                                      |
| hashtags                         | object                | Hashtags included in the tweet.                                   |
| mentionedUsers                   | object                | Users mentioned in the tweet.                                     |
| links                            | object                | External links included in the tweet.                             |
| viewCount                        | object                | View count of the tweet.                                          |
| quotedTweet                      | object                | Content of the quoted tweet, if applicable.                       |
| in_reply_to_screen_name          | object                | Screen name of the user being replied to.                         |
| in_reply_to_status_id_str        | object                | ID of the tweet being replied to as a string.                     |
| in_reply_to_user_id_str          | object                | User ID of the user being replied to as a string.                 |
| location                         | object                | Location information of the tweet or user.                       |
| cash_app_handle                  | object                | Cash App handle mentioned in the tweet, if applicable.           |
| user                             | object                | User information or metadata.                                     |
| date                             | object                | Date of the tweet.                                                |
| _type                            | object                | Type of tweet (e.g., original, reply, retweet).                 |
| epoch_dt                        | datetime64[ns]       | Date and time in datetime format derived from epoch.              |
| user_id                         | float64              | ID of the user as a float.                                       |

## Usage

You can navigate to the relevant part directory and read the chunk files for further analysis. The structure allows you to process tweets in manageable chunks, facilitating easier handling of large datasets.

## Contact 
Please email ashwinb@usc.edu


## Memos
Check out our memo that provides a deeper insight into the dataset: Link


## License

This repository is licensed under [MIT License](LICENSE).

