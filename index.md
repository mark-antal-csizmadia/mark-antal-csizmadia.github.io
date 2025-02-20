---
layout: default
---

## Hey there!

**Hey** there, thanks for dropping by! This is my minimal personal website.

Formally, I am a machine learning engineer with six years of experience and demonstrated success in building and productionizing machine learning and recommendation systems using TensorFlow, PyTorch, AWS, GCP, Python, and LLMs.

Informally, I make neural nets go brrr.

I am from Budapest, Hungary, and I live in Stockholm, Sweden. I have also studied and worked in Manchester, United Kingdom.


## Work Experience

* **Machine Learning Engineer** at [Sellpy](https://www.sellpy.com/) - Stockholm, Sweden, _Dec. 2022 - Ongoing_
    * Integrating Generative AI models into the company's core system that extracts, stores, and serves data about product features with the aim to achieve more accurate and scalable product processing with less human supervision. For this, I use LLMs, multimodal models, vector databases, and vector and hybrid search algorithms.
    * I work a lot with machine learning, deep learning, and neural networks in the context of recommendation systems, and classification and regression problems such as product feature classification, product pricing.
    * I also work quite a bit with data engineering (ETL pipelines) and cloud infrastructure (Infrastructure As Code).
    * Day to day, I mostly use Python, TensorFlow, PyTorch, Google Cloud (BigQuery, Vertex AI), AWS (Kinesis, S3, Batch, Lambda, ECS, ECR, SQS, API Gateway, Bedrock, CloudFormation), LangChain, Langfuse, Qdrant, OpenAI API, Docker, Sentry, PostgreSQL, Apache Airflow, Git, Scikit-learn, Apache Spark, FastAPI.
* **Machine Learning Engineer** at [Ecobloom](https://ecobloom.se/) - Stockholm, Sweden, _Aug. 2020 - Dec. 2022_
    * Developed large scale, distributed data processing  infrastructure and deep learning pipelines for plant leaf detection and stress recognition on Google Cloud Platform. Built with: Cloud Pub/Sub, Cloud Functions, Cloud SQL, BigQuery, Dataflow / Apache Beam, Cloud Data Fusion, Vertex AI, and PyTorch.
* **Research and Development Engineer** at [Nexperia](https://www.nexperia.com/) - Manchester, United Kingdom, _Sep. 2018 - Aug. 2019_
    * I developed semiconductor design process simulation software in Python, and extracted actionable insights from raw manufacturing data using statistical techinques.


## Education

* [**KTH Royal Institute of Technology**](https://www.kth.se/en), Master of Science (MSc) in Machine Learning - Stockholm, Sweden, _Aug. 2020 - Jul. 2022_
    * In my [research thesis](https://urn.kb.se/resolve?urn=urn:nbn:se:kth:diva-320781), I worked on semi-supervised deep learning to increase object detection efficiency with scarce annotations. My aim was to
    demonstrate the feasibility of improving object detection performance with the [Unbiased Teacher for Semi-Supervised Object Detection](https://arxiv.org/abs/2102.09480) algorithm in plant leaf detection and possible stress recognition when few annotations are available. The improved performance reduced the amount of required annotated data for this task, this reduced annotation costs and thereby increased usage for this real-world tasks. This research was supervised by Prof. Josephine Sullivan, and performed for Ecobloom.
    * I was a teaching Assistant for [DD2424 Deep Learning in Data Science](https://www.kth.se/student/kurser/kurs/DD2424).
    * My favourite modules were: Advanced Deep Learning, Advanced Machine Learning, Artificial Neural Networks and Deep Architectures, Deep Learning in Data Science, Machine Learning, Artificial Intelligence, Data Mining, Data-Intensive Computing, Probabilistic Graphical Models, and Speech and Speaker Recognition.
* [**University of Manchester**](https://www.manchester.ac.uk/), Bachelor of Engineering (BEng) in Electronic Engineering First-Class Honours - Manchester, United Kingdom, _Sep. 2016 - Jun. 2020_
    * My final year project was titled ["Real-Time Object Detection with Deep Learning on an Embedded GPU System"](https://www.youtube.com/watch?v=wdFlkIhmTVQ), and was supervised by Prof. Hujun Yin.


## Technologies and Programming Languages

* Python
* Docker
* TensorFlow/PyTorch/Scikit-learn
* Generative AI APIs such as Vertex AI, OpenAI API, and AWS Bedrock
* LangChain
* Amazon Web Services / AWS (Kinesis, S3, Batch, Lambda, ECS, ECR, SQS, API Gateway, CloudFormation)
* Google Cloud Platform / GCP (Cloud Pub/Sub, Cloud Functions, Cloud SQL, BigQuery, Dataflow / Apache Beam, Cloud Data Fusion, Vertex AI)
* PostgreSQL / SQL
* Qdrant / Pinecone (vector database)
* Langfuse (LLM logging)
* Apache Spark / Dask / Apache Beam for distributed data processing
* FastAPI / Flask for API development
* Apache Airflow for ETL pipelines and ML Operations workflows
* Git / GitHub
* Sentry for error tracking
* MLflow for model tracking
* Jupyter Notebooks
* NumPy / Pandas / Matplotlib / Seaborn etc.
* Unix / Linux

I also have experience with:
* Retrieval-augmented generation (RAG), RAG with Knowledge Graph (Neo4j), RAG Evaluations (Ragas), OSS models (using Ollama) via pro-bono consulting
* Reinforcement Learning (RL) and bandit algorithms with Stable-Baselines3 for algorithmic trading

## Pet projects

* [re-sln](https://github.com/mark-antal-csizmadia/re-sln)
    * Re-implementation of the paper titled ["Noise against noise: stochastic label noise helps combat inherent label noise"](https://openreview.net/forum?id=80FMcTSZ6J0) from ICLR 2021.
    * Reproduces the results of the paper.
* [nn-blocks](https://github.com/mark-antal-csizmadia/nn-blocks)
    * Following Andrej Karpathy's example, I implemented a bunch of neural network blocks from scratch in Python and NumPy (strictly no TensorFlow or PyTorch allowed), to understand how neural networks work under the hood.
* [tsboi](https://github.com/mark-antal-csizmadia/tsboi)
    * Time-series forecasting of crypto currency exchange rates with XGBoost and Transformers.
    * Deploying models with MLflow.
    * Fun project to learn about time series forecasting, financial data, and MLflow.
* Algorithmic trading with Reinforcement Learning using Stable-Baselines3
    * I worked on an algorithmic trading application with friends, where we trained XGBoost and Transformer-based time series neural networks to predict crypto currency exchange rates, and used Reinforcement Learning (RL) to optimise trading strategies.
    * We built data processing pipelines to fetch, process, and store Kline Candlestick Data, Order Book Data, etc. from Binance for many crypto currency pairs.
    * We then trained RL models to learn trading strategies given various primary and secondary objectives, such as maximising profit, minimising risk, maximising Sharpe ratio, etc.
        * One important feature was the predicted exchange rate at so many time steps ahead, for which we used XGBoost and Transformers.
    * This project was a lot of fun, but we never published it because we never actually found a strategy that consistently beat the market. I learned a lot, though, about evaluating RL models which is a really different problem from evaluating supervised models.
    * If one was to start with a similar project, I would recommend reading some of the best papers on the topic of RL evaluation (in my opinion): [Deep Reinforcement Learning that Matters](https://arxiv.org/pdf/1709.06560), [Empirical Design in Reinforcement Learning](https://arxiv.org/pdf/2304.01315), the best blog post: [Rliable: Better Evaluation for Reinforcement Learning - A Visual Explanation](https://araffin.github.io/post/rliable/), and to play around with the best RL library: [Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3).
* [NeRFs](https://arxiv.org/abs/2003.08934) for 3D reconstruction
    * I am playing around with [MLX](https://github.com/ml-explore/mlx) and spending time in implementing some NeRF-based algorithms
    * The reasons I am using MLX (Apple's array framework for Apple silicon) is becauase I think the unified memory model (i.e. no need to move tensors between CPU and GPU) makes it a great tool for ML.
* Generative AI apps with NextJS, Supabase, and Generative AI APIs
    * For example, I once built but never published an app where users could create puzzle games, for example, similar to NYT's Connections with the aid of Generative AI (mostly Gemini). Using Generative AI in my opinion is a great use case for this as it's hard to come up with new puzzles but fun with a little help. Users could share and play these games with friends, see leaderboards, popular games, etc.

I have a bunch of smaller projects on my [GitHub](https://github.com/mark-antal-csizmadia).

## Contact

You can reach me at my email (mark.antal.csizmadia@gmail.com) or LinkedIn ([linkedin.com/in/mark-antal-csizmadia](https://www.linkedin.com/in/mark-antal-csizmadia/))
