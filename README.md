# Customer Sentiment Watchdog - A Dual Dashboard Project

*Team:* Team NueroNet 🚀
*Event:* Hackathon Project

## 📄 Project Overview

The Customer Sentiment Watchdog is a comprehensive, dual-dashboard web application designed for sentiment analysis. Built from scratch for a hackathon, this project provides two distinct views for monitoring and analyzing customer feedback: a high-level, multi-platform overview and a focused, deep-dive analysis tool. The entire application runs on the front-end using vanilla JavaScript, HTML, and Tailwind CSS.

---

## ✨ Key Features

This project is split into two interconnected dashboards:

### Dashboard 1: Real-Time Overview (page1.html)

This dashboard provides a "mission control" view for monitoring sentiment across multiple platforms in a simulated real-time environment.

* *Simulated Real-Time Feeds*: The dashboard automatically updates with new comments from six different platforms: Twitter, Amazon, Instagram, Google Playstore, Google, and Reddit.
* *Nuanced Emotion Detection: Each comment is analyzed by a custom JavaScript engine that identifies a wide range of emotions, including **Excitement, Satisfaction, Confusion, Disappointment, Frustration,* and *Anger*.
* *Live Alerts Panel*: Critical negative feedback is automatically flagged and pushed to a dedicated "Alerts" panel, ensuring urgent issues are never missed.
* *Manual Analysis Tool*: Users can input any text to get an instant sentiment analysis.
* *Overall Trend Chart*: A live-updating line chart visualizes the positive vs. negative sentiment trends over time, providing a clear big-picture view.

### Dashboard 2: Advanced Analysis & Star Rating (page2.html)

This dashboard is a specialized tool designed for a deeper, more direct analysis of individual messages, converting sentiment into an actionable star rating.

* *Tone-to-Star Conversion*: The core feature analyzes messages and assigns a 0-5 star rating based on the detected tone.
* *Focused Tone Analysis: The analysis engine uses regular expressions to classify messages into four distinct tones: **Happy, Moderate, Sad,* and *Angry*.
* *Live Bar Chart*: A bar chart updates in real-time to track the total count of each detected tone, offering a clear summary of the overall mood.
* *Message Volume Tracking*: A line chart tracks the total number of messages analyzed over time, visualizing user engagement with the tool.

---

## 🛠 Technologies Used

* *HTML5*: For the structure of both dashboards.
* *Tailwind CSS*: For all styling and creating a responsive layout.
* *Vanilla JavaScript*: For all client-side logic, including the sentiment analysis engines, DOM manipulation, and chart updates.
* *Chart.js*: For creating the dynamic and responsive charts on both dashboards.

---

## 🚀 How to Use

1.  Download the page1.html and page2.html files.
2.  Open page1.html in your web browser to start.
3.  The dashboard will begin simulating new comments automatically.
4.  Use the link at the top to navigate to "Dashboard 2" for the advanced analysis tool.
