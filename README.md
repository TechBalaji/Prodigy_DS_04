# Prodigy_DS_04

# 🌀 Sentiment Analysis and Prediction with Dynamic Visualizations 🌟

Welcome to the world of sentiment analysis and prediction! This repository is packed with mysterious insights into how textual data is processed and transformed into sentiment-based predictions. 🚀

---

## 🧩 **What's Inside?**

📊 **Datasets**:  
- [twitter_training.csv](https://github.com/user-attachments/files/18250470/twitter_training.csv) - Used for training and analysis.  
- [twitter_validation.csv](https://github.com/user-attachments/files/18250498/twitter_validation.csv) -  Used for validation and sentiment prediction.  

🎨 **Dynamic Visualizations**:  
- Advanced visualizations of sentiment distributions and company-specific sentiment trends.  
- Compare **actual vs predicted sentiments** seamlessly!

🔮 **Interactive Interface**:  
- Input your custom tweet and watch the magic unfold as the **TextBlob model** predicts the sentiment!  

---

## 🤔 **What Does This Program Do?**

1. Loads and processes two datasets (`twitter_training.csv` and `Twitter_validation.csv`).  
2. Applies **TextBlob**, a powerful sentiment analysis model, to predict sentiment types (Positive, Negative, Neutral, or Irrelevant).  
3. Enhances the `Twitter_validation.csv` file by appending a new column: `Predicted_Sentiment`.  
4. Visualizes the sentiment distributions dynamically using **Dash**.  
5. Provides an **interactive interface** to input tweets and get real-time sentiment predictions.  

---

## 📈 **Output Highlights**

✨ **Predicted Sentiments**: A new column, `Predicted_Sentiment`, is created in the validation dataset.  
✨ **Dynamic Graphs**: Visualize trends and patterns across actual and predicted sentiments.  
✨ **Interactive Results**: Input a tweet, and see its sentiment predicted instantly!  

---

## 🛠 **Libraries Used**

💻 **Core Libraries**:  
- `pandas` - For data manipulation and analysis.  
- `numpy` - For numerical operations.  

📊 **Visualization Tools**:  
- `plotly` - For dynamic and interactive graphs.  
- `dash` - To create a web-based interactive visualization interface.  

🤖 **Sentiment Analysis**:  
- `TextBlob` - For natural language processing and sentiment prediction.  

---

## 🔥 **What Have I Done?**

1. **Loaded the Data**  
   - Used two datasets: `twitter_training.csv` for analysis and `Twitter_validation.csv` for testing and predictions.  

2. **Analyzed the Data**  
   - Explored the sentiment distribution across companies and tweets.  
   - Visualized trends using **advanced bar charts** and other interactive plots.  

3. **Predicted Sentiments**  
   - Applied **TextBlob** to predict the sentiment type and appended this to the `Twitter_validation.csv` file.  

4. **Created an Interface**  
   - Developed a **Jupyter Notebook interface** to let users input tweets and see predicted sentiments in real-time.  

5. **Visualized the Data Dynamically**  
   - Built **company-wise sentiment visualizations** for both actual and predicted values.  
   - Compared **actual vs predicted sentiments** dynamically.  

---

## 🌟 **Sample Outputs**

### 📄 **Enhanced Validation Dataset**
| Sentiment_ID | Company              | Sentiment   | Tweet_TEXT                                                                                 |  Predicted_Sentiment  |
|--------------|----------------------|-------------|--------------------------------------------------------------------------------------------|-----------------------|
| 8312         | Microsoft            | Negative    | @Microsoft Why do I pay for WORD when it functions so poorly on my @SamsungUS Chromebook?  | Negative              |
| 5130         | GrandTheftAuto(GTA)  | Negative    | Oh shit I got 1 day to finish this fuk                                                     | Negative              |

## 📊 **Sample Visualizations on Twitter training Dataset**([twitter_training.csv](https://github.com/user-attachments/files/18250470/twitter_training.csv))

#### **Sentiment Distribution**
![Output_DS_04](https://github.com/user-attachments/assets/d085c411-9117-472a-a7aa-e21abd39dc60)![Output2_DS_04](https://github.com/user-attachments/assets/d01695e1-4184-486a-865a-d913613dfc35)

#### **Company-Wise Sentiment Trends**
![Output1_DS_04](https://github.com/user-attachments/assets/48f9f567-4ab8-4b75-a02c-a003b83a84ce)


#### **Interactive Interface for Predictions**
![Output1](https://github.com/user-attachments/assets/68c7b73c-a435-43e1-b9ea-8c570d7d5e70)

## **Sample Visualizations on Twitter Validation Dataset** ([twitter_validation.csv](https://github.com/user-attachments/files/18250693/twitter_validation.csv))


#### **Confusion Matrix:Actual vs Predicted**
![Output3_DS_04](https://github.com/user-attachments/assets/fba51eb9-fe28-4c78-b916-b3283fd89059)

#### **Sentiment Distribution(Actual)**
![Output4_DS_04](https://github.com/user-attachments/assets/57a3d38d-0745-4e8d-bf70-2c5f3a2db065)

#### **Sentiment Distribution(Predicted)**
!![Output5_DS_04](https://github.com/user-attachments/assets/70a442bb-4538-486c-9b85-a8166145163d)

#### **Company Wise Sentiment Distribution**
![output6](https://github.com/user-attachments/assets/69f3bb2c-0a5c-42ec-bcb1-608386c26abd)


## 🌐 **Explore It Yourself**

Clone this repository and explore the mystery behind sentiment analysis. 🕵️‍♂️ Who knows what you’ll uncover? 🌟   
