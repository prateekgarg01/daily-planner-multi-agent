# Daily Planner AI App - Streamlit & Ollama Integration

# Overview
This is a simple daily planner application built with Python's Streamlit framework, integrated with Ollama's AI model to generate personalized daily schedules. The app uses an interactive user interface to collect sleep and work hours, and then generates a balanced daily plan that includes time for sleep, work, meals, workouts, and relaxation.

The app is designed to create an optimal daily routine based on the user's specific sleep and work preferences, making it ideal for users looking for help in managing their time more effectively.

# Features
Personalized Daily Plan: The app generates a balanced schedule based on user input for sleep and work hours.
AI Integration: Powered by the Ollama AI model to create schedules tailored to the user’s needs, such as work, food, rest, and workouts.
Interactive Interface: The app uses Streamlit to offer a clean and easy-to-use interface for input and output.

# Code Explanation
Ollama AI Integration: The generate_plan function uses the Ollama API to generate different parts of the daily plan (e.g., sleep, work, food, workout, and rest).
Interactive Sliders: The Streamlit app uses sliders to allow users to adjust their sleep and working hours.
Balanced Schedule: The create_daily_plan function calculates the available hours for activities based on sleep and work input, then requests AI-generated plans for each activity (work, sleep, food, workout, and rest).

# Example
After entering your sleep and work hours, the app will generate a daily schedule, for example:
Your Daily Plan:
1. Sleep Agent: You need 8 hours of sleep. Sleep well.
2. Work Agent: You work 8 hours today. Keep your focus.
3. Food Agent: Plan meals within the remaining available hours.
4. Workout Agent: You can workout for 2 hours.
5. Rest Agent: Enjoy some relaxation time after work and workout.
# Contributing
Feel free to fork this repository, open issues, or submit pull requests. Contributions are welcome!
