Q&A:

1. What is a Neural Network?
- A computational model with layers of interconnected nodes (neurons) that process inputs through weighted connections and activation functions to learn patterns and make predictions.

2. Structured Data vs unstructured data?
- Structured data has fixed format (tables, databases with rows/columns). Unstructured data has no predefined format (images, text, audio, video) and requires more complex processing.

3.1. Sigmoid Function
Formula, range
A: Formula: σ(z) = 1 / (1 + e^(-z)). Range: (0, 1). Used for binary classification output layers to output probabilities.

3.2. tanh function
A: Formula: tanh(z) = (e^z - e^(-z)) / (e^z + e^(-z)). Range: (-1, 1). Zero-centered, preferred over sigmoid for hidden layers due to better gradient flow.

4. RNNs (Recurrent Neural Networks) are good for data with a temporal component?
- RNNs maintain hidden states that carry information from previous time steps, making them suitable for sequential data like time series, NLP, and speech recognition.
