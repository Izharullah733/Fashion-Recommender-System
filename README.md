# Fashion-Recommender-System


![Fashion Recommender](https://img.shields.io/badge/Streamlit-Python%20App-red)
![AI](https://img.shields.io/badge/AI-Hybrid%20Recommender-blue)
![Status](https://img.shields.io/badge/Status-Live%20Demo-green)

## 🎯 Overview

An intelligent hybrid fashion recommendation system that combines multiple AI techniques to provide personalized clothing suggestions. The system analyzes user preferences and behavior to recommend fashion items that match individual style preferences.





## 🏗️ System Architecture

### Hybrid Recommendation Approach:

| Component | Weight | Description |
|-----------|---------|-------------|
| **Collaborative Filtering** | 50% | Learns from user behavior patterns and similarities |
| **Content-Based Filtering** | 30% | Analyzes product features and descriptions |
| **Popularity-Based** | 20% | Includes trending and highly-rated items |

## 📊 Performance Metrics

- **Precision**: Optimized for relevant recommendations
- **Recall**: Comprehensive item coverage
- **F1-Score**: 0.197 (Balanced metric)

## 🛠️ Technical Stack

- **Backend**: Python
- **Machine Learning**: Scikit-learn
- **Web Framework**: Streamlit
- **Deployment**: Ngrok tunneling suing deployment.ipynb (upload four file (fashion_recommender_app.py, clothing_reviews_train_featured.csv, filtered_train_data.pkl, optimized_hybrid_recommender.pkl))

## 📁 Dataset

The system uses a comprehensive fashion dataset including:

- **Dresses**: Multiple categories and styles
- **Tops**: Knits, Blouses, and other upper wear
- **Item Metadata**: Product features and descriptions

### Sample Data Points:
- 1078 - Dresses (Dresses)
- 872 - Knits (Tops) 
- 1094 - Dresses (Dresses)
- 1110 - Dresses (Dresses)

## 🎮 How to Use

1. **Access the Application**
   - Visit the live demo URL
   - Wait for the interface to load completely

2. **Build Your Preferences**
   - Browse through available fashion items
   - Click on items you like or would wear
     <img width="939" height="438" alt="image" src="https://github.com/user-attachments/assets/84254045-625c-4fb8-bc87-3f081a45b034" />
   - System tracks your preferences in real-time

3. **Get Recommendations**
   - Click "Get Personalized Recommendations"
   - Receive AI-curated fashion suggestions
   - Explore different item categories

4. **Refine Results**
   - Continue interacting with items
   - System adapts to your changing preferences

## 💡 Key Features

- ✅ **Personalized Suggestions**: Tailored to individual taste
- ✅ **Multiple AI Techniques**: Hybrid approach for better accuracy
- ✅ **Real-time Interaction**: Immediate feedback and updates
- ✅ **User-Friendly Interface**: Simple click-based interaction
- ✅ **Trend Integration**: Includes popular and trending items

<img width="916" height="397" alt="image" src="https://github.com/user-attachments/assets/0e28491f-af80-4386-afea-79b99130305e" />
<img width="932" height="423" alt="image" src="https://github.com/user-attachments/assets/129be52b-2755-41d8-9e2e-60388bc0d313" />
<img width="941" height="434" alt="image" src="https://github.com/user-attachments/assets/054db56e-0250-4232-a330-3155b29e92b0" />
<img width="953" height="439" alt="image" src="https://github.com/user-attachments/assets/cfba362a-879b-44ab-acb1-a420cff715be" />
<img width="938" height="431" alt="image" src="https://github.com/user-attachments/assets/35bf814b-05ac-4f44-9a41-d827564c8528" />





## 🔧 Installation (Local Development)

```bash
# Clone repository
git clone https://github.com/yourusername/fashion-recommender.git

# Navigate to project directory
cd fashion-recommender

# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run app.py
