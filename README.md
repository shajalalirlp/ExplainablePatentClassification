# ExplainablePatentClassification

State-of-the-art methods for multi-label patent classification rely on deep neural networks (DNNs), which are complex and often considered black-boxes due to their opaque decision-making processes. In this repository, We implemented several novel deep explainable patent classification frameworks by introducing layer-wise relevance propagation (LRP) to provide human-understandable explanations for predictions. Later they trained several DNN models, including Bi-LSTM, CNN, and CNN-BiLSTM, and propagate the predictions backward from the output layer up to the input layer of the model to identify the relevance of words for individual predictions. Considering the relevance score, they then generate explanations by visualizing relevant words for the predicted patent class. they conducted experiments on two datasets comprising two-million patent texts demonstrate high performance in terms of various evaluation measures. The explanations generated for each prediction highlight important relevant words that align with the predicted class, making the prediction more understandable. 
This code repository can also be applied for any other text classification tasks to generate explanation for the predictions made by deep learning models. The explanation can be generated as a word cloud where the larger font text indicates higher relevance with the predicted class.

Rleasse cite the following paper if you use this repo:
@inproceedings{shajalal2023unveiling,
  title={Unveiling Black-Boxes: Explainable Deep Learning Models for Patent Classification},
  author={Shajalal, Md and Denef, Sebastian and Karim, Md Rezaul and Boden, Alexander and Stevens, Gunnar},
  booktitle={World Conference on Explainable Artificial Intelligence},
  pages={457--474},
  year={2023},
  organization={Springer}
}

Paper Link: https://link.springer.com/chapter/10.1007/978-3-031-44067-0_24
