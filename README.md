# Twitch network analysis

The Twitch social network composes of users. A small percent of those users broadcast their gameplay or activities through live streams. In the graph model, users who do live streams are tagged with a secondary label Stream. Additional information about which teams they belong to, which games they play on stream, and in which language they present their content is present. You also know how many followers they had at the moment of scraping, the all-time historical view count, and when they created their user account. The most relevant information for network analysis is knowing which users engaged in the streamer’s chat. You can distinguish if the user who chatted in the stream was a regular user (CHATTER relationship), a moderator of the stream (MODERATOR relationship), or a VIP of the stream.

The network information was scraped between the 7th and the 10th of May 2021.

Following this [article](https://towardsdatascience.com/twitchverse-a-network-analysis-of-twitch-universe-using-neo4j-graph-data-science-d7218b4453ff) to understand how neo4j works.
