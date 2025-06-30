# The Psychology of Button Design: A Beginner's Research Project

## 📘 Study Overview

This beginner-friendly research project explores how the **shape of a button’s corners** influences user interaction. The hypothesis: *Rounded buttons feel more inviting and are clicked more often than sharp-edged ones.*

- **Duration**: 1 week
- **Methods**: Manual observation, simple surveys, basic prototyping  
- **Tools**: Basic HTML/CSS, Google Forms, pen & paper

---

## ❓ The Problem

While browsing websites, I noticed I was more drawn to some buttons than others. Rounded buttons felt *friendlier*, while sharp ones felt *harsh*.  
This led to my research question:

> **Do rounded buttons actually make people more likely to click, or is it just personal preference?**

---

## 🔍 Research Findings

### 📚 Online Research

- **Curved vs. Sharp**: Humans naturally prefer curves—they feel safer and more organic.
- **Bouba/Kiki Effect**: People link rounded sounds/shapes with warmth and sharp ones with harshness.
- **Emotional Cues**: Rounded = positive/relaxed; Sharp = serious/tensed.

### 📊 Competitive Analysis

Rounded buttons dominate in:
- Instagram, Spotify, Netflix
- Mobile banking and e-commerce apps (for action-oriented buttons)

---

## 🧪 Experiment Method

I built a small HTML webpage with two buttons for comparison:

- **Button A**: Sharp corners (`border-radius: 0px`)
- **Button B**: Rounded corners (`border-radius: 8px`)

### 👨‍👩‍👧‍👦 Testing

- **In-person** (15 people): Guerrilla testing using a laptop screen  
- **Online** (Google Forms): 23 responses

**Prompt Questions**:
1. Which button would you be more likely to click?
2. Why?
3. How does each one make you feel?

---

## 📈 Discoveries

- **73%** preferred the rounded button  
- **Common words for Rounded**: Friendly, Approachable, Modern  
- **Common words for Sharp**: Professional, Serious, Cold  

**Observation**: People looked at and clicked rounded buttons faster.

---

## 🧠 Technical Explanation

1. **Evolutionary Psychology**: Sharp = danger, Round = safety
2. **Cognitive Load**: Rounded shapes are easier to process
3. **Emotional Triggers**: Curves relax users
4. **Familiarity**: Physical buttons (e.g., elevator buttons) are usually rounded

**Age Factor**: Older users (45+) tended to prefer sharp buttons due to perceived professionalism.

---

## ✅ Recommendations

### Use **Rounded Buttons** when:
- Targeting users under 35
- Designing fun or casual apps
- Driving feel-good actions (buy, sign-up)
- Creating mobile interfaces

### Use **Sharp Buttons** when:
- Building formal or corporate sites
- Targeting older demographics
- Needing to convey authority or precision

---

## 🧾 Demo HTML Page

Below is the HTML code used for testing:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Button Design Test</title>
  <style>
    .sharp-button {
      border-radius: 0px;
      background: #007AFF;
      color: white;
      padding: 15px 30px;
      border: none;
      cursor: pointer;
      font-size: 16px;
    }

    .rounded-button {
      border-radius: 8px;
      background: #007AFF;
      color: white;
      padding: 15px 30px;
      border: none;
      cursor: pointer;
      font-size: 16px;
    }

    body {
      font-family: sans-serif;
      display: flex;
      gap: 20px;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background-color: #f5f5f5;
    }
  </style>
</head>
<body>

  <button class="sharp-button">Sharp Button</button>
  <button class="rounded-button">Rounded Button</button>

</body>
</html>
