<h1>Agentic AI Skills Coach</h1>

What it does 
<br>
AI Skill Coach evaluates any visually or audibly verifiable skill—public speaking, pushup form, dribbling a basketball, interview delivery, you name it. The user enters a skill and records a short video. Our system then pulls expert technique standards from the web, analyzes the user’s performance using specialized vision, audio, and motion agents, and delivers instructor-like voice feedback with specific, actionable corrections. It behaves like a personalized coaching team watching you perform, scoring your form, identifying mistakes, and telling you exactly what to fix and how to improve.

How we built it
<br>
We built AI Skill Coach using a modular agentic architecture. LightPanda serves as our headless browser for live web scraping, collecting expert guides, biomechanical cues, coaching checklists, and common mistakes for any skill the user inputs. Redis stores this information for fast, low-latency retrieval. Anthropic’s Claude synthesizes the scraped data into structured evaluation rubrics and also performs multimodal analysis of the user’s video and audio. Our specialized agents—vision, audio, motion, scoring, and voice—each handle one aspect of human performance and collaborate to produce a unified evaluation. The frontend (built with a lightweight web framework) allows users to record or upload videos, while a voice generation layer turns technical analysis into natural, human-like coaching feedback.


Check out our hackathon submission:  https://devpost.com/software/ai-skill-coach

