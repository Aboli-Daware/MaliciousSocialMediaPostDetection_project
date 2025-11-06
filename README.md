# MaliciousSocialMediaPostDetection_project
# Malicious Social Media Post Detection using Machine Learning

This project is designed to automatically detect malicious, harmful, or offensive content posted on social media platforms. With the increasing spread of hate speech, cyberbullying and abusive language, there is an urgent need for automated and intelligent content moderation tools.  
This system uses Natural Language Processing (NLP) and a Transformer-based model (RoBERTa - Hate Speech Detection)to analyze messages in real-time and classify them as benign or malicious. Additionally, the system includes social features like chat, friend requests, profiles, and an Admin Dashboard for monitoring flagged content.

## Features
### Machine Learning & NLP
- Real-time malicious content detection
- Detection of abusive, vulgar, harmful, and hate-based messages
- Transformer-based RoBERTa model for high contextual accuracy

### User Module
- User Registration & Login Authentication
- Send / Accept Friend Requests
- Real-Time Chat System with highlighted malicious messages
- Update Profile & Change Profile Picture

### Admin Panel
- View all users & block suspicious accounts
- Review flagged messages
- Add, remove or categorize watched keywords
- User Non-Trust Score calculation based on behavior

  ### URL Scanning and Threat Detection
- Automatically extracts URLs from chat messages and posts.
- Uses an external API (VirusTotal) to check:
  - Phishing links
  - Malware hosting sites
  - Fraud & scam domains
  - Redirect / spam sites
- Users are immediately warned if a link is unsafe.


