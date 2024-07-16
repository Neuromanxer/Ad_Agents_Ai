# GPT AdCreator
Welcome to the GPT AdCreator project, an innovative tool designed to generate personalized advertisements tailored to user preferences. GPT AdCreator leverages the power of AI to craft compelling and targeted ads, revolutionizing how businesses connect with their audiences.

🔍 Overview

GPT AdCreator consists of several specialized agents in LangChain's new LangGraph Library:

Search Agent: Finds products and trends suitable for advertising.
Strategy Agent: Develops effective marketing strategies based on online trends.
Ad Creator Agent: Generates creative ad concepts, including visuals and messaging.
Critique Agent: Provides feedback and refines ad ideas for optimal performance.
Resources Agent: Provides learning resources for improving ad copy and creativity.
Pricing Agent: Assesses costs and pricing strategies for effective budget management.
Goal Agent: Sets and monitors advertising goals and metrics.
Each agent plays a crucial role in creating compelling advertisements that resonate with target audiences.

🌟 Features

Personalized Ads: Tailored ad content that matches user-defined preferences and business objectives.
Effective Strategies: Utilizes current market trends and strategies for impactful advertising.
Creative Designs: Produces visually appealing ads that capture attention.
Feedback Loop: Iterative process to refine and optimize ad content based on critiques and feedback.
Resource Integration: Access to external resources for continuous improvement in ad creativity and effectiveness.
🛠️ How It Works

Setting Parameters: Users define advertising goals, target audience, and preferred styles.
Automated Search: The Search Agent identifies suitable products and trends for promotion.
Strategy Development: The Strategy Agent formulates marketing strategies based on identified trends.
Ad Creation: The Ad Creator Agent generates initial ad concepts, incorporating visuals and messaging.
Feedback and Refinement: The Critique Agent provides feedback for refining ad content.
Finalization: Ads are finalized and prepared for deployment.
🚀 Getting Started

Prerequisites

Tavily API Key - Sign Up
LangChain Subscription - Sign Up
Installation

Clone the repo:


git clone https://github.com/yourusername/gpt-adcreator.git
Export your API Keys:


export TAVILY_API_KEY=<YOUR_TAVILY_API_KEY>
export LANGCHAIN_API_KEY=<YOUR_LANGCHAIN_API_KEY>
Install Requirements:


Copy code
python app.py
Open the app in your browser:

http://localhost:5000/

***Note to remember, the SearchAgent and the MulitAgent work seperately due to the contents of the SearchAgent. Simply input the output fo the SearchAgent into the MultiAgent for the Ad_Agents to do their job. 

Enjoy creating personalized and effective advertisements with GPT AdCreator!

🤝 Contributing

Interested in contributing to GPT AdCreator? We welcome contributions of all kinds! Check out our Contributor's Guide to get started.

🛡️ Disclaimer

GPT AdCreator is an experimental project provided "as-is" without any warranty. It's intended for personal use and not as a substitute for professional advertising services.

📩 Contact Us

For support or inquiries, please reach out to us:

Email: ethanhong110@gmail.com
Join us in transforming the landscape of digital advertising with GPT AdCreator!
