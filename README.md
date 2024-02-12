# Neo4j integration tutorial

## <span style="color:#ff5f27;">🗒️ Architecture:</span>
2. **Feature Pipeline**: Collect and process data and insert into feature groups
3. **Training Pipeline**: build a feature view, training dataset split, train a model and save it in the Model Registry.
4. **Inference Pipeline**: retrieve a trained model from the model registry and use it for batch inference.

You will load data into the **Feature Store**, create `Feature Groups` from which you will make a `Feature View` and `Training Dataset`.

Then you will train a model to predict the distance between nodes.

## <span style="color:#ff5f27;">👮🏻‍♂️ Prerequisites</span>

To run this tutorial, you need an account on Hopsworks. You can create a new account at  [app.hopsworks.ai](https://app.hopsworks.ai).
In the notebook you will be prompted with a link to generate an API token to interact with your Hopsworks account.

## Concepts:
In order to understand the tutorials you need to be familiar with general concepts of Machine Learning and Python development. You may find some useful information in the [Hopsworks documentation.](https://docs.hopsworks.ai) 

## Feedbacks & Comments:
We welcome feedbacks and suggestions, you can contact us on any of the following channels:
- Our [Support Forum](https://community.hopsworks.ai/),
- Directly on this [github repository](https://github.com/logicalclocks/hopsworks-tutorials),
- Send us an email at info@hopsworks.ai 