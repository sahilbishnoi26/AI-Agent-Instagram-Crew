# AI-Agent-Instagram-Crew
AI agents created using CrewAI and DeepSeek R1 via Grok to search the internet and Instagram to automate Instagram content creation. The agents specialize in market research, content strategy, visual content generation, and copywriting to streamline social media management.

## Features
- **Market Researcher Agent**: Analyzes industry trends, competitor activities, and popular hashtags on Instagram.
- **Content Strategist Agent**: Develops a content calendar based on market insights.
- **Visual Creator Agent**: Generates detailed image descriptions for AI-based content creation.
- **Copywriter Agent**: Crafts engaging captions with SEO-friendly keywords and hashtags.
- **Automated Workflow**: Agents collaborate seamlessly to produce high-quality social media content.

## Technologies Used
- **CrewAI**: Framework for agent orchestration and task automation.
- **LangChain**: Used for integrating AI-powered tools and search functions.
- **Serper API**: Enables real-time internet search capabilities.

## Installation
1. **Clone the Repository**  
   - `git clone https://github.com/your-username/AI-Agent-Instagram-Crew.git`  
   - `cd AI-Agent-Instagram-Crew`

2. **Create and Activate a Virtual Environment**  
   - On Windows:  
     - `python -m venv venv`  
     - `venv\Scripts\activate`
   - On macOS/Linux:  
     - `python3 -m venv venv`  
     - `source venv/bin/activate`

3. **Install Dependencies**  
   - `pip install -r requirements.txt`

4. **Set Up Environment Variables**  
   - Create a `.env` file in the root directory and add the required API key:
     ```ini
     SERPER_API_KEY=your_api_key_here
     GROQ_API_KEY=your_groq_api_key_here
     ```

## Usage
1. **Configure Agents and Tasks**  
   - Modify `agents.yaml` and `tasks.yaml` to customize roles and tasks.

2. **Run the Project**  
   - `python src/instagram/main.py`

3. **Interact with the Agents**  
   - Enter the Instagram page description and the topic of the week when prompted.
   - The agents will execute their assigned tasks and generate output files.

4. **View Results**  
   - Open the generated markdown files:
     - `market_research.md`
     - `visual-content.md`
     - `final-content-strategy.md`

## Troubleshooting
- **Issue**: Missing Dependencies  
  - **Solution**: Ensure all dependencies are installed using `pip install -r requirements.txt`.
- **Issue**: API Key Not Found  
  - **Solution**: Ensure the `.env` file is properly set up and sourced.
- **Issue**: Script Execution Failure  
  - **Solution**: Confirm the virtual environment is activated and all required libraries are installed.

This AI-powered system automates Instagram content creation efficiently—enhancing strategy, engagement, and workflow!

