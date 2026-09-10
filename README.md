# 🌟 SentimentSense AI – Customer Feedback Sentiment Analyzer

## 📌 Project Overview

**SentimentSense AI** is a simple AI-powered web application that analyzes customer feedback and identifies whether the feedback expresses a **Positive or Negative sentiment**.

The application uses a pre-trained **DistilBERT Transformer model from Hugging Face** and provides an interactive interface using **Streamlit**.

It can help businesses quickly understand customer opinions and identify areas that may require improvement.

## 🎯 Objectives

* Analyze customer feedback automatically.
* Identify Positive and Negative opinions.
* Display the confidence score of the prediction.
* Help businesses understand customer satisfaction.
* Provide a simple and user-friendly feedback analysis system.
* Demonstrate the practical use of NLP and Transformer models.

## ⭐ Key Features

* 📝 Simple customer feedback input
* 🤖 AI-based sentiment prediction
* 😊 Positive and 😞 Negative classification
* 📊 Confidence percentage
* ⚡ Fast prediction using a pre-trained model
* 💻 Interactive Streamlit interface
* 🔍 No separate model training required
* 📈 Useful for understanding customer experience

## 🛠️ Technologies Used

| Technology                | Purpose                             |
| ------------------------- | ----------------------------------- |
| Python                    | Main programming language           |
| Streamlit                 | Web application interface           |
| Hugging Face Transformers | Pre-trained NLP model               |
| DistilBERT                | Sentiment classification            |
| PyTorch                   | Model backend                       |
| VS Code                   | Development environment             |
| Git & GitHub              | Version control and project hosting |

## 🤖 AI Model

The project uses:

**Model:** `distilbert-base-uncased-finetuned-sst-2-english`

DistilBERT is a smaller and faster version of BERT that can understand the meaning and context of English text.

The model is fine-tuned using the **SST-2 (Stanford Sentiment Treebank)** dataset and classifies text into:

* **POSITIVE**
* **NEGATIVE**

The model also provides a confidence score for its prediction.

## 🔄 Application Workflow

```text
Customer Feedback
       ↓
Streamlit Interface
       ↓
Input Validation
       ↓
Hugging Face Pipeline
       ↓
DistilBERT Model
       ↓
Sentiment Prediction
       ↓
Confidence Score
       ↓
Customer Experience Insight
```

## 📋 How It Works

### 1. Customer Input

The customer enters feedback or a review into the text area.

**Example:**

> "The product quality was excellent and the delivery was very fast."

### 2. Input Validation

The application checks whether the user has entered any feedback.

If the input is empty, a warning message is displayed.

### 3. Sentiment Analysis

The feedback is sent to the Hugging Face sentiment-analysis pipeline.

### 4. AI Prediction

The DistilBERT model analyzes the text and predicts whether the sentiment is Positive or Negative.

### 5. Confidence Score

The application calculates the model's confidence and displays it as a percentage.

### 6. Result Display

The result is shown directly on the Streamlit webpage.

## 💬 Customer Experience Use Cases

SentimentSense AI can be useful for analyzing:

* 🛍️ Product reviews
* 📦 Delivery feedback
* ☎️ Customer service feedback
* 🏨 Hotel reviews
* 🍔 Restaurant reviews
* 📱 App reviews
* 🛒 E-commerce feedback
* 🎓 Student feedback
* 💻 Service reviews

## 📊 Example

### Positive Feedback

**Input:**

> "The customer service was excellent and the staff were very helpful."

**Output:**

```text
Sentiment: POSITIVE
Confidence: 99.XX%
```

### Negative Feedback

**Input:**

> "The delivery was late and the product arrived damaged."

**Output:**

```text
Sentiment: NEGATIVE
Confidence: XX.XX%
```

## 💡 Customer Experience Insights

The sentiment results can help businesses:

### 1. Identify Customer Satisfaction

A high number of positive reviews can indicate that customers are satisfied with the product or service.

### 2. Detect Customer Problems

Negative feedback can help businesses identify problems such as:

* Poor service
* Delayed delivery
* Product quality issues
* Difficult customer support
* Pricing concerns

### 3. Improve Customer Engagement

Businesses can respond to negative feedback quickly and engage positively with satisfied customers.

### 4. Track Feedback Trends

Sentiment results can be collected over time to understand whether customer satisfaction is improving or declining.

## 🚀 Practical Improvement Strategies

Based on customer sentiment, businesses can:

* Respond quickly to negative feedback.
* Thank customers for positive reviews.
* Identify frequently reported problems.
* Improve products and services based on customer opinions.
* Personalize customer communication.
* Monitor customer satisfaction regularly.
* Use feedback trends to support business decisions.

## 📁 Project Structure

```text
sentiment-analysis/
│
├── app.py
├── requirements.txt
└── README.md
```

### `app.py`

Contains the Streamlit interface, model loading, input validation, sentiment prediction, and result display.

### `requirements.txt`

Contains the Python packages required to run the application.

### `README.md`

Contains project documentation, installation instructions, features, and usage information.

## ⚙️ Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/sentiment-analysis.git
```

### Step 2: Navigate to the Project Folder

```bash
cd sentiment-analysis
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Run the Application

```bash
streamlit run app.py
```

The application will open in the browser through the local Streamlit URL.

## ⚠️ Limitations

* Supports only Positive and Negative sentiments.
* Designed primarily for English text.
* May have difficulty understanding sarcasm.
* Complex or unclear sentences may produce unexpected results.
* Confidence scores should not always be treated as absolute certainty.
* Customer feedback containing multiple opinions may be difficult to classify correctly.

## 🔮 Future Enhancements

The project can be improved by adding:

* Neutral sentiment detection
* Multi-language support
* CSV batch analysis
* Sentiment history
* Sentiment charts and dashboards
* Customer satisfaction trends
* Aspect-based sentiment analysis
* Online deployment
* API integration
* Automatic feedback categorization

## 🎓 Learning Outcomes

Through this project, the following concepts are demonstrated:

* Natural Language Processing
* Sentiment Analysis
* Transformer-based AI
* Hugging Face Transformers
* DistilBERT
* AI model inference
* Streamlit application development
* Python programming
* Confidence score interpretation
* Git and GitHub

## 🏁 Conclusion

**SentimentSense AI** demonstrates how Artificial Intelligence and Natural Language Processing can be used to analyze customer feedback automatically. By identifying customer sentiment and providing prediction confidence, the application can support businesses in understanding customer satisfaction, identifying problems, and improving customer engagement.
