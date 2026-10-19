# 📸 Insta_Zone

Turning Instagram activity into booking intelligence.
<img src="JD-ux72/Insta_zone/Insta zone .jpg"/>


Insta_Zone is a data-science project built for Exquisite Bliss Boutique to answer a simple business question:

«When should we post to turn attention into actual bookings?»

Instead of posting nail art randomly and hoping it performs, Insta_Zone connects Instagram content performance with booking data to uncover patterns between when a post is published, how it is presented, and the bookings that follow.

---

🎯 The Problem

Social media engagement doesn't always translate into customers.

A post might receive plenty of likes but generate few bookings, while another post with less engagement could lead to more appointments.

Insta_Zone therefore focuses on the metric that matters to the business:

📅 Bookings generated after a post.

---

🧠 What It Does

The project combines:

- 📊 Instagram analytics
- 📅 Booking records
- 🕐 Time of day
- 📆 Day of week
- #️⃣ Hashtag count
- 🎨 Number of colours in the nail-art photo

The datasets are merged by date and analysed to identify the "Magic Posting Window" — the posting conditions most associated with increased bookings.

---

🔬 Data Science

The analysis follows a simple end-to-end pipeline:

Instagram CSV + Booking CSV
↓
Data Cleaning & Date Alignment
↓
Feature Engineering
↓
Correlation Analysis
↓
Linear Regression
↓
Booking Prediction
↓
Streamlit Decision Tool

The regression model estimates expected bookings from the characteristics of a planned post.

Example

«Post tomorrow at 6 PM with 8 hashtags and a photo containing 4 colours → estimated booking response: ~3 bookings.»

The goal isn't simply to predict a number.

It's to turn social-media data into a business decision.

---

🖥️ The Product

Insta_Zone is deployed as an interactive Streamlit application where a user can enter the details of a planned post and receive an estimated booking outcome.

Instead of asking:

«"When should we post?"»

the business can ask:

«"What does the data suggest we should post, and when?"»

---

🛠️ Tech Stack

Python · Pandas · Scikit-learn · Matplotlib/Seaborn · Streamlit

---

💡 Business Impact

Insta_Zone demonstrates how a small business can move from:

Random posting → Data-informed marketing → Better booking decisions.

It turns social media from a collection of engagement metrics into a source of customer intelligence.

---

✨ Built as part of the Exquisite Bliss Boutique Data Science Portfolio

Insta_Zone — Where content meets customer intelligence.
