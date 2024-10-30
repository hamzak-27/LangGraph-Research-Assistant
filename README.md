# LangGraph-Research-Assistant

LangGraph Research Assistant is an AI-driven tool designed to support research processes by generating AI analyst personas, conducting literature surveys, and identifying research gaps. This project uses LangGraph, LangChain, and OpenAI's GPT API for creating dynamic, structured analyst personas who review and analyze research topics iteratively, providing insights and identifying emerging trends.

**Features:**
- AI Analyst Personas: Automatically generates analyst personas based on research topics. Each persona has a defined role, affiliation, and expertise area, offering specialized insights.
- Literature Survey: Ingests research documents and provides a summarized literature survey with categorized themes.
- Gap Analysis: Identifies underexplored areas by comparing findings in the literature to existing knowledge bases, flagging unique or insufficiently addressed topics.
Memory and Checkpointing: Uses LangGraph's state management and memory-saving tools to maintain continuity in analysis, allowing iterative updates.

**Usage**
- Generate Analyst Personas: Run the main script to generate personas based on the provided research topic and feedback.

- Conduct a Literature Survey: Add research documents to be ingested, categorized, and summarized for the literature survey.

- Identify Research Gaps: The system will highlight any research gaps by comparing themes and findings to existing knowledge.
