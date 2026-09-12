# Insta_zone
Problem: You post nail art randomly and don't know what time gets the most bookings. The Project: Build a post-performance predictor.


· What it does: Merges your Instagram post times/likes with your booking data to find the "Magic Posting Window."
· The Data Science: A simple correlation matrix + linear regression to predict how many bookings a post will generate based on (Time of Day, Day of Week, Hashtag Count, Number of Colors in the Photo).
· End-to-End: Download IG analytics CSV + booking CSV → Merge by Date → Train a linear model → Deploy a Streamlit form that says: "If you post this photo tomorrow at 6 PM with 8 hashtags, you'll likely get 3 new bookings."
