# Explaining Text Classification with Vertex Explainable AI
Machine learning models are complex systems, and developers require advanced tools to understand and explain (some of) their behavior. Vertex AI, Google Cloud's platform for end-to-end ML, has a specialized offering for model interpretability called Explainable AI.

In this repo, I'll create a TensorFlow model to classify text, upload it to Model Registry, and deploy it for online predictions with explainability enabled. I'll make predictions and explore the results of the explainability to help understand my model's behavior.

## Learning objectives
- Using Vertex AI Model Registry to load a custom-trained model and configure explanations
- Using Vertex AI Explainable AI to get feature-based explanations with the sampled Shapley method.
- Visualize explanations with matplotlib, and gather some model insights.
