# Volcano Eruption Prediction Using Machine Learning

## Project Overview

This project explores the use of machine learning to identify volcanic eruptive activity using historical earthquake data. It is based on the research paper *Predicting Eruptive Events at Volcanoes from Earthquake Data*, which studies the relationship between earthquakes and volcanic eruptions at Kīlauea volcano in Hawaii.

The goal is to investigate whether earthquake characteristics can help predict volcanic eruptive status and, if supported by the available data, estimate the time until an eruption begins.

## Problem Statement

Volcanic eruptions can pose significant risks to nearby communities. Changes in earthquake activity may provide useful information about volcanic unrest. This project investigates whether machine learning models can learn patterns from historical earthquake records to support the identification and forecasting of volcanic activity.

## Project Objectives

- Prepare and analyse historical earthquake data.
- Investigate earthquake characteristics associated with volcanic activity.
- Develop a machine learning model for volcanic eruptive-status classification.
- Evaluate model performance using appropriate metrics.
- Explore time-to-eruption regression if suitable data and sufficient time are available.

## Proposed Methodology

1. **Data Collection:** Obtain earthquake records and relevant historical eruption information.
2. **Data Preprocessing:** Clean the data, prepare input features and construct appropriate target labels.
3. **Model Development:** Begin with a Random Forest classifier and consider additional models where feasible.
4. **Model Evaluation:** Evaluate predictions on unseen data using suitable performance metrics.
5. **Result Analysis:** Interpret the findings, identify limitations and document possible improvements.

## Dataset

The project requires historical earthquake records containing information such as earthquake time, magnitude, depth, latitude and longitude, together with suitable eruption-history records.

The final dataset source, date range, number of records and preprocessing details will be documented after the dataset has been obtained and verified.

## Technologies

The planned implementation uses Python and relevant data analysis and machine learning libraries. The final dependencies will be documented in `requirements.txt`.

## Project Structure

The repository will contain the source code, data preparation workflow, evaluation results and project documentation. Its final structure will be updated as the implementation develops.

## Evaluation

The model will be evaluated using metrics appropriate to the prediction task. Classification metrics may include AUROC, Cohen's Kappa and a confusion matrix. If regression is implemented, evaluation may include root mean squared error (RMSE) and the coefficient of determination (\(R^2\)).

Actual results will be reported after the model has been trained and tested.

## Limitations

Machine learning predictions do not guarantee that a volcanic eruption will occur at a particular time. Results depend on data quality, target-label construction, the selected features and model performance on unseen data.

