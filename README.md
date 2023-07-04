
### Dataset Collection
The dataset for this project if from the California Traffic Collision Data set, which contains information about every traffic collision from 2001 to 2020 in the state of California. The dataset is publicly available from The State of California, which maintains a database of traffic collisions called the Statewide Integrated Traffic Records System (SWITRS). The data is extensive, containing 9.46 million rows at 6.21 GB in total.
##### Source: 
[Dataset on Zenodo](https://zenodo.org/record/4284843#.ZFQM6i9BxQI)

### Dataset Description

The database switrs.sqlite contains four tables as shown;

<!-- Raw HTML Table Start -->
<table>
  <caption>SWITRS.SQLITE</caption>
  <thead>
    <tr>
      <th>Case_ids(9.46M)</th>
      <th>Collisions(9.46M)</th>
      <th>Parties(18.7M)</th>
        <th>Victims(9.6M)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>2 columns </td>
      <td>75 columns</td>
      <td>31 Columns</td>
        <td>11 Columns</td>
    </tr>
  </tbody>
</table>
<!-- Raw HTML Table End -->

### Steps to Follow for the prediction task in this project

1. **Data Collection**: Downloading the California Traffic Collision Data set from the provided reference.
2. **Data Preprocessing**: Cleaning the dataset, handle missing values, and perform any necessary data transformations.
3. **Exploratory Data Analysis**: Exploring the dataset to gain insights into the distribution of variables and identify any patterns or correlations.
4. **Feature Selection**: Selecting relevant features that are likely to contribute to collisions based on domain knowledge and exploratory analysis.
5. **Data Split**: Spliting the dataset into training and testing sets for model development and evaluation.
6. **Model Development**: Choosing a suitable machine learning model for predicting collisions based on the selected features.
7. **Model Training**: Training the chosen model on the training data.
8. **Model Evaluation**: Evaluating the performance of the trained model using appropriate evaluation metrics.
9. **Results and Conclusion**: Summarizing the findings of the analysis and discuss the most important factors contributing to collisions in California.

## Resources

Here are some resources that might be helpful for this project:

- [Apache Spark-Python Documentation](https://spark.apache.org/docs/2.1.2/api/python/index.html)
