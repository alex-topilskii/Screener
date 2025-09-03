# 🎯 Competency Screener

A modern, interactive web application for conducting competency assessments with a Tinder-style swipe interface. Perfect for evaluating skills across different domains and experience levels.

## 🌐 Live Demo

**Try it now:** [https://alex-topilskii.github.io/Screener/](https://alex-topilskii.github.io/Screener/)

## ✨ Features

### 📱 **Intuitive Swipe Interface**
- **Tinder-style gestures**: Swipe left (No), right (Yes), or up (Don't know)
- **Smooth animations**: Beautiful card transitions with rotation effects
- **Multi-platform support**: Works on desktop, tablet, and mobile devices
- **Visual feedback**


## 📝 YAML Format

The application uses YAML files to define competency frameworks. Here's the expected structure:

```yaml
domains:
  - name: "Hard Skills"
    competencies:
      - id: android_basics
        levels:
          junior:
            skills:
              - "Knowledge in Android SDK"
              - "Kotlin programming"
              - "Constraint Layout"
          middle:
            skills:
              - "Advanced Android SDK"
              - "Coroutines"
              - "MVVM architecture"
          senior:
            skills:
              - "Project architecture design"
              - "Code review expertise"
  - name: "Soft Skills"
    competencies:
      - id: communication
        levels:
          junior:
            skills:
              - "Clear verbal communication"
          middle:
            skills:
              - "Technical decision advocacy"
```
