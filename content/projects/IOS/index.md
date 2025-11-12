---
title: '🧠 YouAre — iOS App for Building Self-Assertion and Confidence'
summary: 'This app is designed to help people improve self-assertion.'
date: '2025-03'
image:
  filename: featured.png
  focal_point: 'Smart'
  preview_only: false
---

## 🌟 Inspiration

This app is designed to **help people improve self-assertion**.  
We were inspired by the challenges many face in building confidence and overcoming fear of judgment — which often causes anxiety and self-doubt.  

**YouAre** encourages users to reflect on and collect their daily experiences in a positive, rewarding way, helping them gain clarity, confidence, and resilience against misjudgment.

---

## 💡 What It Does

Users build their confidence by **collecting daily evidence** — small but meaningful experiences that affirm their beliefs and growth.

Each belief (like *Healthy*, *Kind*, or *Creative*) is represented by a **colored shape block with an emoji**.  
Users can tap a block to enter its detail view, see all their evidence entries, and navigate through reflections using swipe gestures.

Long-pressing allows adding new blocks or evidence.  
The app also supports **daily reflections**, letting users choose three key elements of their day and celebrating completion with a **confetti animation** 🎉.  

If users forget a block’s meaning, they can switch to **dark mode**, where each block displays its emoji for quick recall.

---

## 📖 Story & Education Page

The *Story* section provides educational and emotional support — covering:
- **Self-definition and identity**
- **Body positivity and beauty diversity**
- **Relationships and acceptance**
- **LGBTQ+ inclusivity**
- **The developer’s personal story**

This narrative helps users see that **self-assertion and authenticity** are lifelong practices.

![Essence Page](images/essence2.png)
![Story Page](images/orange.png)

---

## 🛠️ How We Built It

Built with **Swift** and **SwiftUI**, the app uses a clean **View-Model architecture** to efficiently manage data and UI updates.  
We also integrated a **local confetti animation API** for a joyful user experience.

![Home View](images/home.png)
![Add Block View](images/add_block.png)
![Add Evidence View](images/gallery.png)

---

## ⚙️ Challenges We Faced

One of the toughest parts was implementing the **selection tracking system**.  
Initially, the yellow highlight stroke wasn’t dynamically attached to selected elements.  
We solved this by introducing:
- a `selectedBlockID` variable, and  
- an `isSelected` flag bound to UI updates in real time.

This created a responsive and fluid reflection experience.

---

## 🏆 Accomplishments

✅ Built a **smooth daily reflection experience**  
✅ Added a **confetti celebration** for motivation  
✅ Designed a **responsive selection tracking** system  
✅ Ensured the app works **fully offline**  

![Celebration Screen](images/contra.png)

---

## 📚 What We Learned

Through this project, we learned how to:
- Manage **dynamic UI state** using SwiftUI bindings  
- Implement **real-time selection logic**  
- Integrate **animations smoothly**  
- Debug complex UI placement issues  

We also learned how visual feedback and interaction design can powerfully shape **users’ confidence journeys**.

---

## 🎥 App Demo

<iframe width="640" height="360"
  src="https://www.youtube.com/embed/AwFMyipYiP4"
  title="YouAre App Demo"
  frameborder="0"
  allowfullscreen>
</iframe>

---

### ✨ More Screens

| | | |
|---|---|---|
| ![Essence](images/essence2.png) | ![Healthy Page](images/gallery(1).png) |

---

**Created with ❤️ using Swift & SwiftUI**  
*Empower yourself, one block at a time.*