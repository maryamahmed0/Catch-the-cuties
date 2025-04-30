# Catch-the-cuties
This is an educational image-based game developed to help children recognize objects interactively. The project includes computer vision, UI design, and game logic components.
The player selects a challenge type, then extracts specific objects from an image while considering an A* algorithm to evaluate how close their selection is to the target.


## 🔧 Technologies Used

- **Tkinter** – for building the main application interface and windows.
- **Figma** – for UI/UX design and prototyping.
- **YOLOv8** – for object detection in scene images.
- **OpenCV** – for image processing, object localization, and integration between detection and game logic.
- **Pygame** – for building the game logic and interaction.
- **A\* Algorithm** – to calculate the distance between the clicked and target objects, and provide feedback like “you’re close” or “you’re far” and the number of steps.

  
- ## 🔗 Additional Repositories

This project integrates several tools and libraries. You can find the Tkinter interface repository here:

- [Tkinter Interface Repository](https://github.com/ParthJadhav/Tkinter-Designer)  


## 📸 Demo Screenshots

Here are some screenshots demonstrating different stages of the game:

### 🟢 Game Start Screen
**The initial interface where the player can start the game.**

![Game Start](/images/start_screen.jpg)

---

### 📂 Category Selection
**The player is prompted to select a category of objects (e.g., fruits).**

![Category Selection](/images/category_screen.jpg)

---

### ✅ Correct Selection
**The child clicks on the correct object as prompted.**

![Correct Selection](/images/correct_choice.jpg)

---

### 🟡 Wrong but Close
**The child clicks on a wrong object, but it’s close to the target. A hint like "You’re close!" appears and the number of steps.**

![Wrong Close](/images/wrong_close_choice.jpg)

---

### 🔴 Wrong and Far
**The child clicks on a wrong object that is far from the target. The feedback shows "You’re far!" and the number of steps.**

![Wrong Far](/images/wrong_far_choice.jpg)

---

### 🎉 Final Congratulation Screen
**After correctly identifying all target objects, the child is rewarded with a final “Congratulations” screen.**

![Congrats Screen](/images/congrats.jpg)


## 👥 Team Members

- **Mariam Adham**
- **Maryam Ahmed**
- **Marwa Abu-Elkheir**



