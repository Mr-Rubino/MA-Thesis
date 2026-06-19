# MA-Thesis
Code used in the MA Thesis: Mapping FIMI and DIMI Narratives on Telegram: An Analysis of Dutch-Language Defensive Publics

# Modularity-Class-Info
The code in this file was used after the network analysis was done with Gephi, and the data exported into a CSV file. Using in-degree, it calculates statistics on modularity classes and top domains within each modularity class.

# Barchart
This code was used to generate a bar chart of top channels within each BERTopic

# Topic-Splitting
The code in this file takes the parquet file with all messages, with topic label, and splits these messages by a preset number of channels. This code also generated network graphs for each individual topic, to allow network research to be done within specific topics instead of on all messages at once.
