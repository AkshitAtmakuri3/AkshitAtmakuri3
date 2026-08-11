# Akshit Atmakuri

MSc Business Analytics at Warwick Business School. BSc Computer Science, First Class, from The University of Manchester.

I work on the modelling side of commercial decisions: credit risk, pricing, capacity allocation, and the data infrastructure underneath them. Before that, computer vision and robotics.

## Optimisation and pricing

**[Revenue Management and Pricing Optimisation](https://github.com/AkshitAtmakuri3/revenue-management-pricing-optimisation)**
Integer programming model allocating a 300 generator rental fleet across four durations over a 52 week season. Lifts modelled revenue 10.0%, from £4.65M to £5.12M, and load factor from 73.4% to 78.9%.
`Python` `PuLP` `CBC`

**[Tournament Scheduling Optimisation](https://github.com/AkshitAtmakuri3/tournament-scheduling-optimisation)**
Constraint programming for a 48 team tournament: a group draw respecting seeding pots and confederation caps, match scheduling against a spectator interest index, and stadium assignment under capacity limits.
`Python` `Pyomo` `CBC`

## Credit risk and prediction

**[Credit Risk and Loan Approval Modelling](https://github.com/AkshitAtmakuri3/credit-risk-loan-approval-modelling)**
Segments LendingClub borrowers into four risk bands and sets a separate approval threshold for each, instead of one global cutoff. Recall on the high risk segment reaches 82.6% against 63.1% for a logistic baseline.
`PyTorch` `scikit-learn` `SMOTE` `R`

**[Customer Credit Application Prediction](https://github.com/AkshitAtmakuri3/customer-credit-application-prediction)**
Six classifiers benchmarked on 100k credit applications across 200 features with a 10% positive class. Best ROC-AUC 0.893, with an explicit threshold search showing the 0.5 default was wrong for every model.
`XGBoost` `LightGBM` `scikit-learn`

## GenAI and applied machine learning

**[RAG over the EU AI Act](https://github.com/AkshitAtmakuri3/rag-eu-ai-act)**
Three question answering systems compared head to head: no retrieval, dense RAG, and hybrid dense plus BM25. Includes a scraper that deliberately excludes AI generated summaries so the corpus cannot contaminate the evaluation.
`sentence-transformers` `FAISS` `BM25` `Transformers`

**[Applied ML and GenAI Portfolio](https://github.com/AkshitAtmakuri3/applied-ml-genai-portfolio)**
Ten projects: PyTorch classifiers, semantic search with a Gradio interface, TabPFN against gradient boosting, prompting strategies, 10-K risk comparison, and vision language models for document and image extraction.
`PyTorch` `sentence-transformers` `TabPFN` `Gemini` `Gradio`

**[LLM Inventory Planning Pipeline](https://github.com/AkshitAtmakuri3/llm-inventory-planning-pipeline)**
Warehouse replenishment planner with a check and repair loop. A deterministic checker validates the generated plan against an answer key, and failures trigger scoped re-extraction rather than full regeneration.
`Claude` `Pydantic` `openpyxl`

## Data engineering and statistics

**[E-commerce Database Design and SQL Analytics](https://github.com/AkshitAtmakuri3/ecommerce-database-design-sql-analytics)**
Normalised 14 table SQLite schema, a synthetic generator producing 11,206 referentially valid records, and SQL analyses of revenue, cart abandonment and subscription churn. All integrity checks pass.
`SQL` `SQLite` `Faker`

**[Statistical Modelling in R](https://github.com/AkshitAtmakuri3/statistical-modelling-r)**
Regression with a mean centred interaction term, interpreted at representative percentiles rather than left as a raw coefficient.
`R` `tidyverse` `emmeans`

## Computer vision and systems

**[Computer Vision Based Third-View Robot Control](https://github.com/AkshitAtmakuri3/cv-third-view-robot-control)**
Final year dissertation, awarded a distinction. Autonomous TurtleBot3 navigation combining GMapping SLAM with a custom OpenCV visual servoing controller that finds a target and avoids obstacles from HSV colour segmentation alone.
`ROS Noetic` `OpenCV` `Gazebo`

**[Computer Vision Projects](https://github.com/AkshitAtmakuri3/computer-vision-projects)**
Harris corner detection written from scratch and benchmarked against ORB, stereo depth estimation, and OpenCV image processing in C++.
`OpenCV` `C++` `NumPy`

**[CNN Training Experiments](https://github.com/AkshitAtmakuri3/cnn-training-experiments)**
Depth, dropout and learning rate sweeps on CIFAR-10, three runs per configuration so that configuration effects can be separated from run variance.
`TensorFlow` `Keras`

**[Air Quality Classification](https://github.com/AkshitAtmakuri3/air-quality-classification)**
Linear classification via gradient descent implemented by hand, with a learning rate sensitivity study on multisensor readings.
`NumPy` `scikit-learn`

**[Socket Client and Server](https://github.com/AkshitAtmakuri3/distributed-systems-client-server)**
TCP client and server with a hand rolled stateful application protocol, written directly against sockets.
`Python` `TCP`

## Toolkit

**Languages** Python, SQL, R, C++
**Data** PostgreSQL, SQLite, ETL, data modelling, Git, Excel
**Machine learning** scikit-learn, PyTorch, TensorFlow, XGBoost, LightGBM, NLP, LLMs, RAG
**Analysis and BI** Statistical analysis, A/B testing, optimisation modelling, Tableau, Power BI, Matplotlib

## Contact

[LinkedIn](https://www.linkedin.com/in/akshit-atmakuri/) | akshitatmakuri3@gmail.com

Some of these projects were team projects. Each repository states plainly which were collaborative and what I contributed.

These repositories are also mirrored at [@AkshitAtmakuri](https://github.com/AkshitAtmakuri).
