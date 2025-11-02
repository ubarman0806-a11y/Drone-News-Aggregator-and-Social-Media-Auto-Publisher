🛰️ Drone-News-Aggregator-and-Social-Media-Auto-Publisher
The Drone News Aggregator and Social Media Auto-Publisher is an n8n workflow, using automation to streamline how drone and UAV technology news is disseminated and published online, gathering and republishing the latest articles from trusted drone news sites every day and drafting and posting social media posts directly to LinkedIn using AI - this all saves time and keeps the online presence consistent.

This project was conceived as part of my internship to provide an example of real-world automation and AI used for content marketing.

🚀 Features

🕓 Daily Automation – Fetches fresh drone and UAV articles every morning at 9 AM (IST).

📰 Smart Aggregation – Pulls from multiple Google News RSS feeds (Drone, UAV Technology, DGCA India).

🤖 AI Content Creation – Uses OpenAI GPT (via n8n LangChain) to craft professional, engaging posts.

🧹 Duplicate Filtering – Skips previously posted articles using Google Sheets history tracking.

🖼️ Image Fetching – Retrieves article images or generates relevant descriptions for visuals.

💬 Auto Publishing – Posts directly to LinkedIn, with optional integration for X (Twitter).

📊 Data Logging – Saves posted article details in Google Sheets for recordkeeping.

🧠 Tech Stack
Component	Description
n8n	Automation and orchestration engine
Google News RSS	Source for drone-related news
OpenAI GPT-4o-mini	AI post generation
Google Sheets API	Logging and article tracking
LinkedIn API	Automated post publishing
Twitter API (optional)	Optional posting integration
🧩 Setup Instructions

Clone this repository

git clone https://github.com/rishi-1103/drone-news-aggregator-and-social-media-auto-publisher.git

cd drone-news-aggregator-and-social-media-auto-publisher


Open in n8n

Import the workflow JSON file (Drone News Aggregator and Social Media Auto-Publisher.json).

Configure your credentials for:

Google Sheets.

LinkedIn OAuth.

(Optional) Twitter.

OpenAI API.

Customize Feeds (optional).

Modify the RSS URLs in the Workflow Configuration node for your preferred topics.

Activate the Workflow.

Set the workflow to active in n8n to trigger it automatically every day at 9 AM.


📈 Example Output

Generated LinkedIn Post Example:
🚀A major leap for 'Make in India' in defence. Larsen & Toubro is partnering with US-based General Atomics to build advanced MALE drones right here in India.

This partnership is set to manufacture Medium Altitude Long Endurance (MALE) RPAS in India. The deal leverages L&T's extensive engineering and system integration capabilities with GA-ASI's world-class operational expertise.

hashtag#Drones hashtag#MakeInIndia hashtag#AtmanirbharBharat hashtag#Defence hashtag#LarsenAndToubro

Read More

https://lnkd.in/gnEQXpRn

learn more: https://www.linkedin.com/posts/drone-news_drones-makeinindia-atmanirbharbharat-activity-7390751756420378624-4dwV

💡 Purpose

This project was created for internship demonstration purposes — showcasing workflow automation, AI-powered content generation, and API integration within a real-world digital marketing use case.

⚠️ Notice

This repository has no license and is not intended for commercial use.
All integrations (LinkedIn, Google, OpenAI) are used for educational and demonstration purposes only.

👨‍💻 Author

Subhadeep Barman

B.Tech Artificial Intelligence & Machine Learning

📍 India

LinkedIn: https://www.linkedin.com/in/subhadeep-barman-254a38215/
