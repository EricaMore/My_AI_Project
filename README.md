# 🤖💪 FitBuddy – Your AI-Powered Personal Fitness Coach

**Building AI course project**

---

## Summary

FitBuddy is an AI-powered personal fitness coach that provides personalized workout plans and health tips based on your fitness level, goals, and feedback — helping users stay active, healthy, and consistent with ease.

---

## Background

### The Problem

In today's world, staying active is harder than ever. Millions of people face barriers such as:

* Lack of time or motivation  
* No access to gyms or trainers  
* High cost of personalized coaching  
* Confusion about how and what to train  

### Why It Matters

The World Health Organization reports over 1.4 billion adults worldwide are not physically active enough. Inactivity is a risk factor for obesity, mental health issues, and chronic diseases.

### Personal Motivation

I designed FitBuddy to be the kind of coach I wish I had: available 24/7, affordable, empathetic, and smart enough to adjust to my progress.

---

## How is it used?

FitBuddy is accessed via a mobile app or website. It works in 4 steps:

1. **Onboarding**: The user provides basic data (age, goals, schedule, preferences).  
2. **Plan Generation**: FitBuddy creates a tailored weekly workout plan.  
3. **Interaction**: Users receive reminders and use the chatbot to give feedback or ask for alternatives.  
4. **Adaptation**: The AI adapts plans based on user behavior and outcomes.

<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Fitness_AI_Companion_App.png" width="500" alt="FitBuddy AI App Interface">

**User types:**  
- Beginners or inactive users  
- People with time or budget constraints  
- Users who prefer home workouts  
- Individuals with specific goals (e.g. weight loss, rehab)

---

## Data sources and AI methods

### Data Sources

- [UCI Human Activity Recognition Dataset](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones)  
- User input: age, weight, preferences, feedback  
- Future: wearable integration (Fitbit, Garmin, Apple Watch)

### AI Techniques

| Task | Method |
|------|--------|
| Workout classification | Supervised learning (Random Forest, SVM) |
| Adaptive planning | Reinforcement learning |
| Chat support | NLP (transformer-based dialog models) |

```python
# Simple workout suggestion logic
def suggest_workout(level, goal):
    if level == "beginner" and goal == "weight_loss":
        return "Walk 30 minutes + bodyweight circuit (3 rounds)"
    elif level == "intermediate":
        return "Full body strength training (push/pull/legs)"
    elif level == "advanced":
        return "HIIT session + progressive overload plan"
Sample dashboard view
Below is a mockup of what the user dashboard could look like:

<img src="https://upload.wikimedia.org/wikipedia/commons/1/17/Fitness_AI_dashboard_mockup.png" width="500" alt="FitBuddy Dashboard Mockup">
Challenges
❌ Does not replace a licensed medical or physiotherapy service

🔍 Dependent on accurate and consistent user data

⚠️ Requires strong data privacy and ethical use protocols

🧠 Bias in model training if data is not inclusive

What next?
Planned developments:

Wearable integration (real-time feedback and tracking)

Emotional intelligence in chatbot replies (via sentiment analysis)

Multilingual support (Italian, Spanish, Hindi)

Partnerships with gyms, health coaches, and insurers

Needed support:

Data scientists with healthcare AI experience

UX designers for mobile experience

Cloud engineers for backend deployment

Volunteer users for beta testing and feedback

Acknowledgments
This project was created as part of the Building AI course

Data source: UCI Human Activity Recognition Dataset

Libraries: Scikit-learn, TensorFlow, Hugging Face Transformers

Inspired by: Freeletics, Noom, FitOn

Image credits:

"Fitness AI Companion App" / CC BY-SA 4.0

"Fitness Dashboard Mockup" / CC BY 2.0











