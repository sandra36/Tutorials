---
title: Use Service Ticket Intelligence and Jupyter Notebook to generate Clusters and Keywords in Service Requests
description: Train a machine learning model based on historical service requests in order to identify trends or patterns in new requests.
auto_validation: true
time: 40
tags: [tutorial>beginner, topic>machine-learning, topic>artificial-intelligence, topic>cloud, software-product>sap-business-technology-platform, software-product>sap-ai-business-services, software-product>service-ticket-intelligence, tutorial>free-tier]
primary_tag: topic>machine-learning
author_name: Juliana Morais
author_profile: https://github.com/Juliana-Morais
---

## Details
### You will learn
  - How to analyze datasets and upload the training data
  - How to train a machine learning model to generate clusters and keywords in service requests
  - How to identify trends or patterns in new requests based on the clusters and keywords you generated
  - How to evaluate the performance of your machine learning model

Service Ticket Intelligence provides machine learning functionalities to effectively deal with service requests. Thereby, the service offers three main functionalities:

1. The service is able to analyze the unstructured information in service requests and classify the requests into categories.

2. The service is able to recommend solutions for service requests based on historical data.

3. The service is able to identify in unstructured data trends or patterns in service tickets from the clusters and keywords you have generated.

This tutorial deals with clustering text in service requests. Find more details on the Service Ticket Intelligence features [here](https://help.sap.com/docs/SERVICE_TICKET_INTELLIGENCE/934ccff77ddb4fa2bf268a0085984db0/2f0e49ac91c24d54acb694d967e0cfc0.html).

---

[ACCORDION-BEGIN [Step 1: ](Open the Jupyter notebook)]

First, start your local Jupyter server.

The first page that you see shows the content of the repository that you cloned from GitHub in [Set Up Jupyter Notebook for Service Ticket Intelligence](cp-aibus-sti-jupyter-setup), including the notebooks, datasets and configuration file that you edited in the previous tutorial. To open the notebook for clustering, click **Clustering** to navigate into the folder.

![Jupyter Home](jupyter-home.png)

Next, click **Clustering_demo.ipynb** to open the notebook. You can recognize Jupyter notebooks by their `.ipynb` file extension.

![Open Notebook](open-notebook.png)

[DONE]
[ACCORDION-END]


[ACCORDION-BEGIN [Step 2: ](What is a Jupyter notebook)]

Jupyter Notebooks are interactive playgrounds to code and are often used in data science to explore datasets.

Notebooks contain a number of cells in a sequence whereas each cell mainly contains text or code but can also output diagrams and graphics. If cells contain code they can be executed.

The numbers in front of a cell tell the number of executed cells in this notebook. While the cell is being executed a `*` is printed instead of a number so you can tell if the operation is still running or already finished.

![Notebook Structure](notebook-structure.png)

Once you click into a cell, it is marked with a border so you can tell at which position in the notebook you are.

A cell can be executed by clicking the play button at the top. If you execute code then there will be additional output printed below the cell.

![Executing Cells](executing-cells.png)

[DONE]
[ACCORDION-END]


[ACCORDION-BEGIN [Step 3: ](Run the tutorial)]

As mentioned above, a notebook can also contain text. We made sure that there are sufficient explanations for every step in the notebook.

Go through the notebook by executing the cells and reading the explanations that are given. Come back here to complete the tutorial and test your understanding.

[DONE]
[ACCORDION-END]


[ACCORDION-BEGIN [Step 4: ](Test yourself)]

[VALIDATE_1]
[ACCORDION-END]
