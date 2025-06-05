# Social Listening for Public Outrage
Team - Ram Potham, Adeniyi Joseph, Diana Rivera, Shreya Shukla

### Code for Compassion London 2025 Hackathon

https://forum.effectivealtruism.org/posts/Duu5JQLuJqntK4gyi/code4compassion-a-hackathon-transforming-animal-advocacy

**Project Idea** - Use natural language processing (NLP) to monitor media, social feeds, and news for moments of public outrage about factory farming (e.g., scandals, environmental damage, disease outbreaks) and send real-time alerts to the comms team to amplify.

Used **n8n** (https://n8n.io/) for orchestrating the workflow.

<img width="1192" alt="Screenshot 2025-06-04 at 3 33 21 pm" src="https://github.com/user-attachments/assets/64d341cc-1f8a-4e0a-bd4f-51c56eb6d8bc" />

This project leverages n8n, an open-source workflow automation tool, to orchestrate real-time monitoring of social media for animal abuse content. It uses a combination of Google Search (via Serper API), tweet scraping, and AI-driven classification to analyze posts. Each post is scored for sentiment, topic relevance, and an outrage score (0.0–1.0). When the outrage threshold (e.g., ≥ 0.5) is met, the system automatically sends alerts to communication teams for potential amplification. Currently, there are two email modes: real-time alerts and alerts with aggregated tweets. This enables timely and targeted response to high-impact public discourse.

<img width="699" alt="Screenshot 2025-06-04 at 4 41 56 pm" src="https://github.com/user-attachments/assets/b9802f7f-a73c-4055-9875-b4f48476e723" />





