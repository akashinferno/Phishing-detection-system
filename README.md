# URL Phishing Detection System

## Overview

The URL Phishing Detection System is a machine learning-based solution designed to identify phishing URLs based on various extracted features. By analyzing patterns commonly found in phishing links, the model helps in distinguishing between legitimate and fraudulent URLs.

## Features Used for Detection

The model is trained on several URL characteristics, including:

- Subdomain Level: Determines the depth of subdomains.
- Path Level: Measures the complexity of the URL path.
- URL Length: Analyzes the length of the URL.
- Number of Dashes: Counts the number of dashes in the URL.
- Number of Dashes in Hostname: Identifies dashes specifically in the hostname.
- Iframe or Frame Presence: Checks for embedded iframe or frame elements.
- Missing Title: Identifies webpages with missing title tags.
- Images Only in Form: Detects cases where images are only present within forms.
- Subdomain Level RT: Captures the subdomain level in real-time.
- URL Length RT: Analyzes URL length dynamically.
- Percentage of External Resource URLs RT: Measures external resource usage.
- Abnormal External Form Action Rate: Identifies abnormal form actions.
- External Meta Script Link Rate: Evaluates external script links.
- Percentage of External Null Self-Redirect Hyperlinks: Analyzes self-redirecting hyperlinks.

## Model Performance

The machine learning model was trained on these features and achieved an accuracy score of 0.98665 (F1 Score).





























