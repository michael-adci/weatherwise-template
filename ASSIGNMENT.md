---
title: "WeatherWise: Simple Weather Advisor"
author: "Michael Borck"
---

## Assignment Overview

This assignment focuses on developing your AI collaboration skills by creating a Weather Advisor application. While the actual program is relatively simple (answering questions like "Should I take an umbrella today?"), the primary learning objective is to demonstrate effective AI interaction techniques in the development process.

## Requirements

### Core Features
1. Use the WeatherWrapper from the hands-on-ai package to get weather data
2. Create a simple menu with pyinputplus to let users:
   - Enter their location
   - Ask practical weather questions in plain English
   - Exit the program
3. Parse natural language questions and generate helpful responses

### Required Functions

```python
def get_weather_data(location, days=2):
    """Get weather data using the WeatherWrapper"""
    # Use the hands-on-ai WeatherWrapper here
    pass
    
def parse_weather_question(question):
    """Figure out what the user is asking about the weather"""
    # Extract location, time period, and what they want to know
    pass
    
def generate_weather_response(parsed_question, weather_data):
    """Create a helpful answer to the user's question"""
    # Respond to questions like "Should I take an umbrella?"
    pass
```

### Example Questions to Support
- "Will it rain today in [location]?"
- "Should I take an umbrella tomorrow?"
- "Will it be cold this weekend?"
- "Is it a good day for a picnic?"
- "What should I wear today based on the weather?"

## Notebook Structure
Organize your Google Colab notebook with these sections:
1. Setup and Imports
2. Weather Data Functions
3. Question Processing Functions
4. User Interface
5. Main Program
6. Examples and Testing

## AI Interaction Requirements (Main Focus)

Document your AI-assisted development process thoroughly:

1. **AI Conversations**: Include 4 text files showing how you:
   - Explored how to use the WeatherWrapper
   - Developed the natural language processing for weather questions
   - Improved the user interface with AI assistance
   - Refined the code by challenging the AI's initial solutions

2. **Before/After Examples**: Show 3 examples of:
   - Initial AI-generated code
   - Your specific follow-up prompts that led to improvements
   - The improved code
   - Your explanation of why your prompting strategy was effective

3. **Intentional Prompting Strategies**: Demonstrate at least 4 of these techniques:
   - Asking the AI to explain its code before accepting it
   - Challenging the AI on edge cases (e.g., "What if the user asks about weather from last week?")
   - Requesting specific improvements to the code structure
   - Breaking down complex problems into smaller steps
   - Testing the AI's understanding of the WeatherWrapper's capabilities
   - Getting the AI to evaluate different approaches to parsing questions

## Submission

1. GitHub repository with:
   - Your Colab notebook (.ipynb) with the complete Weather Advisor application
   - README.md explaining your approach to AI collaboration
   - 4 AI conversation text files (.txt) showing your development process
   - A reflection document (300-400 words) discussing:
     - Which AI prompting strategies were most effective
     - How you improved upon the AI's initial solutions
     - What you learned about effectively collaborating with AI tools

2. Submit the GitHub repository link to the LMS by May 16, 2025

## Grading (30 points total)
| Category | Points | Description |
|----------|--------|-------------|
| Functionality | 4.5 points | Correctly answers practical weather questions |
| Code Quality | 3 points | Clean, well-documented code |
| User Experience | 4.5 points | Easy to use with helpful responses |
| AI Interaction Quality | 12 points | Quality of prompts, conversations, and AI collaboration strategy |
| Intentional Prompting | 6 points | Evidence of effectively guiding the AI toward better solutions |

*Note: The primary focus of this assignment is demonstrating effective AI collaboration skills, not just getting a working program.*

Keep your solution focused on helping users make practical daily decisions based on the weather!
