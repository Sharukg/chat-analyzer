# WhatsApp Chat Analyzer 📊

### 📌 **Overview**
The WhatsApp Chat Analyzer is a web application built using Streamlit that enables users to upload their exported WhatsApp chat files and gain insightful visualizations about their chat activity, including message statistics, user activity patterns, and much more.

---

### 🎯 **Features**
- **Overall Chat Analysis:**
  - Total messages, words, media shared, and links shared.
- **User-Specific Insights:**
  - Activity trends across days, months, and years.
- **Visual Timelines:**
  - Monthly and daily activity visualizations.
- **Activity Maps:**
  - Weekly activity heatmaps and most active periods.
- **Top Contributors:**
  - Identifies the most active users and their message percentages.
- **WordCloud Generation:**
  - Highlights the most frequently used words.
- **Emoji Analysis:**
  - Displays the most used emojis and their percentages.
             
---

### ⚙️ **How It Works**
1. Export your WhatsApp chat as a `.txt` file.
   - Open WhatsApp, select the chat, click on options, and choose "Export Chat".
2. Upload the `.txt` file using the sidebar file uploader.
3. Select a user or "Overall" to analyze chat statistics.
4. Click **Show Analysis** to generate visualizations.

---

### 🚀 **Technologies Used**
- **Programming Language:** Python
- **Framework:** Streamlit
- **Data Visualization:**
  - Matplotlib
  - Seaborn
  - WordCloud
- **Libraries for Analysis:**
  - `pandas` for data manipulation.
  - `nltk` for natural language processing.
  - `emoji` and `collections` for emoji and word frequency analysis.

---

### 🛠️ **Setup Instructions**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/chat-analyzer.git
   cd chat-analyzer
