# ml-planning

Repository used by the Watson Machine Learning team for tracking & planning

# Roadmap and Requirements
The Machine Learning roadmap is defined on an Aha board maintained by Offering Management.

[Aha Roadmap](https://bigblue.aha.io/products/ML/feature_cards)

[Box Folder](https://ibm.ent.box.com/folder/21779425598)

# Milestone Epic Views
[AI Sphere July](https://github.ibm.com/NGP-TWC/ml-planning#boards?labels=ai%20sphere,july2018,epic&repos=84379)

# Pre-req
Please install the Zen-hub plug in required to view our Kanban boards and other features.  Download the plug in for either Chrome or Firefox [here](https://zenhub.innovate.ibm.com/setup/download)

# Team Squads

| Squad Name | Squad Scope | Squad Leader |
| -------- | ---------- | ------------- |
| Training | Provide the integrated ML experience for model development and training including HPO,Cross Validation, Experiments, data split, auto feature engineering CADS (auto modeling). Functionality delivered in Spark and additional pipelines like scikit learn/conda and streams | Lucian Cioranu | 
| Bluemix Service | Provide the BlueMix integration of WML pipelines for both scoring and training. Focusing on app developer persona and rapid integration int applications | Kamila Baron-Palucka |
| Deployment | This service will provide capabilities including Retraining the Model and Monitoring the model performance leading to continuous Model feedback | Rafal Bigaj | 
| Scoring | Provides end point capabilities to score ML artifacts in Batch, Streaming and Online modes. | Tamil Narayanaswamy | 
| Core services | Ingest Integration, Repo, Token, Libraries, Run time Integration (Scikit learn) | Janakiraman Krishnamurthy | 
| Continuous Integration | Continuous Integration, Automation | Shashank Vagarali| 
| Model Visualization | Provide introspection into models and explain plans on execution and decision making. Critical for gaining TRUST on models within organization. Critical part of monitoring for WML | Todd Peterson |
| Modeler Flows |  ML Canvas to allow building and running analytics pipelines and training ML models | Dominika Oliver | 
| Deep Learning editor | Part of the Modeler Flows experience, the Deep Learning Editor(AKA Darviz) allows users to visually create a Neural Network definition which can be saved to the ML Repository for Training withing the service | Rafal Bigaj | 

# Guilds

A Guild is a group of people that form a community of interest across the full organization to share knowledge, tools, code, and practices.

| Guild Name | Scope | Leader | Reporting | Members |
| -------- | ---------- | ------------- | -------- | -------- |
| Architecture | Drive Architecture direction across WML | Marius Danciu| Anthony Casaletto | Marius Danciu, Gopi Varadarajulu, Rafal Bigaj, Vinod Muthusamy, Robert Duncan, Donald Pierucci |
| Performance | Drive Performance Strategy across WML | Basker Shanmugam| Vinod Khader | Basker Shanmugam, Lukasz Cmielowski, Andrew Thompson, Niall McCarroll |
| Metrics | Drive Metric collection and reporting | Rafal Bigaj | Vinod Khader | Rafal Bigaj, Shashank Vagarali, Andrew Thompson |
| QA | Drive Test strategy across WML | Lukasz Cmielowski | Anthony Casaletto | Lukasz Cmielowski, Andrew Thompson, Diana Tesedean, Yugandhra Rayanki |
| Operations | Drive Operations strategy across WML including Continuous Integration, Runbooks | Shashank Vagarali | Vinod Khader | Shashank Vagarali, Daniel Ryszka, Mihai Sarto, Andrew Thompson  |
| Security | Security reviews and strategy across WML | Rafal Bigaj | Anthony Casaletto | Rafal Bigaj, Gopi Varadarajulu |
| NFR | NFR reviews and strategy across WML | Gopi Varadarajulu | Vinod Khader | Gopi Varadarajulu |

## Making guilds effective
There are a set of principles that each guild needs to folow up.

1. Guilds typically discuss in more depth technical aspects, of their domain, that are generally applicable to all squads. However guilds need to clearly forumulate the outcomes of that effort and make concrete proposals before implementing them. 

2. Technical proposals of different guilds needs to be communicated to the Architecure guild. Use wml-architecture slack channel to make such communications.

3. There is a need for cross-guild communication. For instance security guild may need something implemented but that may affect performance thus involving the performance and architecture guilds is recommended. 

# WML clusters

- FVT: wml-fvt.ml.test.cloud.ibm.com
- DEV: wml-dev.ml.test.cloud.ibm.com
- SVT: wml-svt.ml.test.cloud.ibm.com
- PERF: wml-perf.ml.test.cloud.ibm.com
- YS1-PROD: us-south.ml.test.cloud.ibm.com
- LYS1-PROD: eu-gb.ml.test.cloud.ibm.com
- YP-PROD: us-south.ml.cloud.ibm.com
- LYP-PROD: eu-gb.ml.cloud.ibm.com


# Swagger pages
- Implemented public v3 API - http://watson-ml-v3-api.mybluemix.net
- Implemented private v3 API - http://watson-ml-v3-api-private.mybluemix.net
- Implemented private v2 API - http://watson-ml-v2-api-private.mybluemix.net
- APIs in design that will eventually become public - http://watson-ml-design-api.mybluemix.net
- APIs in desgin for private use only - http://watson-ml-design-api-private.mybluemix.net

### APIs promotion path
- design-api -> private - > public
- design-api-private -> private
