# InboxGraph

InboxGraph is a property graph representation of mail server archive data, in which message collections are presented in a higher-dimensional space than is possible with traditional user interfaces with linear timestamped constraints.

RFC-822 message parsing is used to extract message trajectories between servers and network participants, forming a metadata-rich lattice of vertices and edges inside a directed graph. Asymmetrical relationships between participants are used to calculate Address Rank measurements of information flow importance and to partition the graph into best-fitting communities, opening new channels for organizational optimization. Additional layers of natural language processing and data export to open formats permit further interactive exploration, querying, and discovery of deeper associations within the graph.

<img width="1071" alt="Screenshot" src="https://user-images.githubusercontent.com/25379378/87357241-6d307280-c518-11ea-974b-23d20c8225de.png">

[View Mathematica Notebook](https://iryanbell.github.io/inboxgraph/)
