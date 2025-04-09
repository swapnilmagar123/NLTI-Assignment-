
Task 1

We'll build a content-based recommendation system using cosine similarity. The idea is to match aspirants to mentors (CLAT toppers) based on their profiles, focusing on features such as:

Preferred subjects

Target colleges

Current preparation level

Learning style

We'll simulate a dataset of both mentors and aspirants and compute similarity between an aspirant's profile and mentor profiles.

Brief Explanation of the Approach
We use content-based filtering that relies on matching aspirant profiles to mentor profiles based on similarity. By encoding profiles using vectorization (e.g., one-hot encoding or TF-IDF), we compute similarity scores and return the top 3 mentors with the highest match score using cosine similarity.



Bonus: How It Improves with Feedback
Over time, the system can be improved using:

User feedback loop: Let aspirants rate their mentor matches (e.g., 1–5 stars), and use collaborative filtering to refine future recommendations.

Tracking interactions: Monitor chats or sessions and apply reinforcement learning to boost mentors with good outcomes.

Weighted similarity: Learn feature weights (e.g., subject match is more important than prep level) from user feedback.

task 2
