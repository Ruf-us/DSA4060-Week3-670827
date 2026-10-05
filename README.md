## Project Overview
This repository contains a simple content-based movie recommender system built using Python and pandas. The system models user preferences using structured binary genre features weighted by explicit user ratings, calculates candidate recommendation scores via vector dot products, and returns Top-N unseen recommendations.

## Workflow Pipeline
Item Metadata → Item Profiles → User Ratings → User Profile → Candidate Scores → Remove Seen Items → Rank
Items → Top-N Recommendations
