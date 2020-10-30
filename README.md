# How many discourses in contemporary economics?
This repository contains original data and main results obtained due research on economics discourse structure. Department of Economics, Lomonosov MSU. 2020

- Discourse is an embedded field of science, where researchers agree with each other and do the same;
- In 2020 the Lomonosov MSU Department of Economics announced a grant for a research on economic science discourses;
- An empirical part of the research contains a contextual analysis of contemporary economics papers, regarding Covid-19 and its economic consequences;
- We use the Scopus database to find relevant articles on request "covid-19 economy". The total of %n% articles where obtained and we downloaded its' titles, abstracts, author information and references as .csv table;
- We use authors and references information to construct a network of authors, showing who cited who;
- After some data cleaning, we employ the Girvan-Newman algorithm to find clusters in the network structure.

As we guess this clusters could show us the discourse structure of contemporary economic science. In the center we could see big main structure, which connects a vast of authors (and papers). Bu there are many authors on a periphery, who is not connected to main structure.

From our primary Scopus dataset we get abstracts, titles and keywords of papers of authors presented in top 10 largest clusters in main sector and 3 big enough clusters from the periphery. This way we constructed 13 text corpora for every selected cluster. We employ "bag-of-words" model and create term-document matrix, weighted by tf-idf method. Weighted frequencies obtained where used to create word-clouds for every cluster.

Result is ambiguous.

\[Description is under construction\]
