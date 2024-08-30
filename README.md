
# Social Media Analytics & SocialSense

## Overview 🌐

This repository includes two related projects aimed at understanding and analyzing social media influence and sentiment:

1. **Social Media Analytics**: Analyzes key predictors of social influence using a dataset from Kaggle.
2. **SocialSense**: A real-time social media sentiment analyzer application utilizing advanced machine learning and natural language processing techniques.

## Social Media Analytics 📊

### Dataset

The analysis is based on the "Influencers in Social Networks" dataset available on Kaggle:

### Analysis Steps

1. **Data Wrangling**: Processed approximately 5,000 records to handle missing values and clean the data.
2. **Correlation Analysis**: Explored the relationships between variables to identify key predictors.
3. **Modeling**: Applied four machine learning models:
   - **Logistic Regression**
   - **Random Forest**
   - **K-Nearest Neighbours**
   - **XGBoost**
   
   The XGBoost model achieved the highest accuracy of 81%, with the best precision, recall, and F-measure scores of 79%.

### Key Predictors

The top 5 predictors of social influence according to the XGBoost model are:
- `A/B_listed_count`
- `A/B_follower_count`
- `A/B_network_feature_3`
- `A/B_retweets_received`
- `A/B_network_feature_2`

## SocialSense: Social Media Sentiment Analyzer 📈

### Tools & Technologies

- **React JS**: Frontend framework for building the user interface.
- **TensorFlow**: For creating and training deep learning models.
- **PyTorch**: Used for implementing and optimizing machine learning models.
- **NLP (Natural Language Processing)**: Enhances the model’s ability to understand context, sarcasm, and nuanced emotions in social media comments.

### Features

- **Real-time Sentiment Analysis**: Integrates machine learning models to analyze sentiment from social media comments as they are posted.
- **Contextual Understanding**: Uses NLP techniques to interpret context, sarcasm, and complex emotional expressions.

### Installation

To get started with both projects, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/Social-Media-Analytics-SocialSense.git
   cd Social-Media-Analytics-SocialSense
   ```

2. **Setup Social Media Analytics:**
   - Navigate to the `SocialMediaAnalytics` directory.
   - Install required dependencies: `pip install -r requirements.txt`
   - Run the analysis scripts.

3. **Setup SocialSense:**
   - Navigate to the `SocialSense` directory.
   - Install dependencies: `npm install`
   - Start the application: `npm start`

4. **Access the Application:**
   Open your browser and navigate to `http://localhost:3000` for the SocialSense application.

## Contributing 🤝

Contributions are welcome! Feel free to submit a Pull Request for improvements or new features.
