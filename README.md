# Development of Jeju Soil Bacteria-based AI Model (SBM) for Locating Buried Plastic Wastes in Hallasan Mountain, Jeju Island, South Korea

This project focuses on the development of a Jeju Soil Bacteria-based AI Model (SBM) to predict the location of buried plastic waste in Hallasan Mountain, Jeju Island, South Korea. By analyzing the optical density of soil bacteria that react to microplastics, the AI model predicts areas with high probability of buried plastic waste, providing a scalable and non-invasive solution to plastic waste management in UNESCO World Heritage Sites like Hallasan Mountain.

![Plastic Concentration](https://github.com/yerin16/soil-bacteria-ai-model/blob/main/images/plastic-concentration.png?raw=true)


## Table of Contents

- [Background](#background)
- [Features](#features)
- [Models](#models)
- [Result](#result)
- [Conclusion](#conclusion)


## Background
In 2019, over 2 tons of buried plastic waste, estimated to have been dumped over 30 years ago, were found in Hallasan Mountain, Jeju Island. This illegal dumping has significantly impacted the ecosystem and environment, raising concerns about public health and biodiversity. Traditional excavation methods are inefficient and could damage the fragile ecosystem of the mountain.

This project was initiated to develop a scalable, non-invasive method to locate buried plastic waste using soil bacteria from Jeju’s unique volcanic soil, which reacts sensitively to plastic contamination. By using an AI model trained on bacterial growth data, the project aims to predict the presence of plastic waste, offering an effective and eco-friendly solution to the waste management challenges in Hallasan Mountain.

## Features

- Jeju Soil Bacteria Analysis: Selects bacteria from Jeju soil that exhibit changes in population based on plastic concentrations.
- AI-Based Prediction Model: Utilizes an AI model trained on optical density data of bacteria to predict the presence of buried plastic waste with a probability between 0 and 1.
- Non-Invasive Plastic Detection: Provides a scalable method to locate buried plastic without disrupting the Hallasan Mountain ecosystem.

## Models

### 1. Bacteria Culturing and Data Collection
Jeju soil was collected, and bacteria that showed plastic sensitivity were selected and cultured. Optical density measurements were taken for six different bacteria species at various plastic concentrations, and the resulting data was used to train the AI model.

![Soil Sample](https://github.com/yerin16/soil-bacteria-ai-model/blob/main/images/soil-sample.png?raw=true)

![Bacteria Sample](https://github.com/yerin16/soil-bacteria-ai-model/blob/main/images/bacteria-sample.png?raw=true)

### 2. Soil Bacteria Model (SBM)
The SBM was trained using the optical density data of soil bacteria exposed to varying concentrations of plastic extract. The final model includes five layers and 128 nodes, and it returns a probability score based on the presence of plastic in the soil.

![Model Structure](https://github.com/yerin16/soil-bacteria-ai-model/blob/main/images/model-structure.png?raw=true)

## Result
The SBM model achieved significant results in predicting the presence of plastic waste in Jeju soil, with plastic detection accuracy increasing 10-fold for small amounts of plastic. The model was able to differentiate between Jeju soil and regular potting soil, confirming that the bacterial response is specific to Jeju soil.

## Conclusion
This project demonstrates the potential of using soil bacteria-based AI models to detect buried plastic waste in environmentally sensitive areas like Hallasan Mountain. The SBM model shows promise for large-scale, non-invasive detection of plastic contamination, reducing the need for destructive excavation methods. Future research will focus on expanding the dataset and improving the model’s accuracy, with the ultimate goal of applying this method to other regions.