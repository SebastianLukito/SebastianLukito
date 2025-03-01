# Hi there! 👋 I'm Sebastian Lukito

Welcome to my GitHub profile! Here, I love exploring **Python, AI, Web Development, and Data Science**.  

---

## 🏗 Work-Life Balance Function

```python
# A function to balance work and fun.
def work_life_balance(task: str, mood: str = 'neutral') -> str:
    """
    A function to encourage work-life balance with a fun twist.
    
    Args:
    - task (str): The task to complete.
    - mood (str): Your current mood. Default is 'neutral'.
    
    Returns:
    - str: A fun yet professional message to keep you motivated!
    """
    fun_emojis = {
        'happy': '😃',
        'neutral': '😌',
        'sad': '😞'
    }
    
    professional_advice = {
        'happy': "Great! But don't forget your responsibilities.",
        'neutral': "Stay balanced, don't overwork or overplay.",
        'sad': "Maybe take a short break and come back stronger."
    }
    
    if mood not in fun_emojis:
        return "Invalid mood! Please choose 'happy', 'neutral', or 'sad'."
    
    return (f"📝 Task to complete: {task} {fun_emojis[mood]}\n"
            f"💡 Advice: {professional_advice[mood]}")

# Example usage:
message = work_life_balance("Complete Python project", "happy")
print(message)
```
---
#🔥 About Me
🎓 Informatics Engineering Student @ Universitas Mercubuana  
💻 Passionate about Python, Web Development, and AI  
🛠 Currently working on Machine Learning & Automation Projects  
🌱 Learning Flask, CodeIgniter 3, and Full-Stack Development  
📌 Active in GDSC Mercubuana & Perpustakaan Jalanan Indonesia  
🚀 Aspiring Computer Scientist  
