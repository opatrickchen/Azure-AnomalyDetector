# Detect and visualize anomalies in your data with the Anomaly Detector API 

The Anomaly Detector API lets you monitor and detect abnormalities in your time series data without previous experience in machine learning. The API adapts by automatically identifying and applying the best fitting statistical models to your data, regardless of industry, scenario, or data volume. These python notebooks cover the following examples. 

### Latest-point anomaly detection 

Use previously seen data points to determine if the latest one in the data set is an anomaly. This example simulates using the Anomaly Detector API on streaming data by iterating over the data set and sending API requests at predetermined positions. By calling the API with each new data point you generate, you can monitor your data as it's created. 

### Batch anomaly detection 

Use a time series data set to detect any anomalies that might exist as a batch. This example sends example data sets in a single Anomaly Detector API request. |

![License](https://img.shields.io/badge/license-MIT-green.svg)

These python notebooks show you how to start detecting anomalies in your data with the Anomaly Detector API, and visualizing the information returned by it. 

## Prerequisites

A [Cognitive Services API account](../articles/cognitive-services/cognitive-services-apis-create-account.md) with access to the Anomaly Detector API. If you don't have an Azure subscription, you can [create an account](https://azure.microsoft.com/try/cognitive-services/) for free. You can get your subscription key and API endpoint from the [Azure portal](../articles/cognitive-services/cognitive-services-apis-create-account.md#access-your-resource) after creating your account, or [Azure website](https://azure.microsoft.com/try/cognitive-services/my-apis) after activating a free trial.

## Running the sample

1. Sign in, and click Clone, in the upper right corner.
2. **Uncheck the "public" option in the dialog box before completing the clone operation, otherwise your notebook, including any subscription keys, will be public.** 
3. Click **Run on free compute**
4. Select one of the notebooks for this sample, start with "Batch anomaly detection with Anomaly Detector API.ipynb"
5. Add your valid Anomaly Detector API subscription key to the `subscription_key` variable.
6. You may need to update the `endpoint` too if you created resource from other Azure regions. If you selected West US 2 when creating the resource, no need to change here.
7. On the top menu bar, click **Cell**, then **Run All**.

>**Warning: Uncheck the "public" option in the dialog box before completing the clone operation, otherwise your notebook, including any subscription keys, will be public.**

## Next steps

For more information, see the [Anomaly Detector API documentation](https://aka.ms/anomaly-detector-documentation). 