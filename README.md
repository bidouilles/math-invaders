# **Maths Invaders Ultimate 🚀✖️**

**Maths Invaders Ultimate** is a retro-style arcade space shooter designed to make learning multiplication tables addictive and fun for children. Built entirely in a single HTML file using the HTML5 Canvas API, it combines "juicy" game mechanics with educational drills.

## **🎮 Game Features**

* **Arcade Gameplay:** Pilot a spaceship and destroy asteroids containing the correct answers to multiplication problems.  
* **Adaptive Difficulty:** The game speeds up and introduces more enemies as the score increases.  
* **Combo System:** Chain correct answers to increase your multiplier and score points faster.  
* **Power-ups:** Unlock special abilities during gameplay:  
  * 🛡️ **Shield:** Destroys enemies on impact without losing a life.  
  * 🔫 **Double Shot:** Fires two bullets at once for better crowd control.  
  * ❤️ **Extra Life:** Restores a lost heart.  
* **Selectable Tables:** Choose specifically which multiplication tables (2 through 10\) to practice via the main menu.  
* **Revision Mode:** A "Cheat Mode" that highlights the correct answer in green. Scores achieved in this mode are not saved to the High Score table.  
* **Juicy Visuals:** Includes screen shake, particle explosions, neon glow effects, and dynamic ship banking.  
* **Responsive Design:** Works on Desktop (Mouse) and Mobile/Tablet (Touch controls).

## **🕹️ How to Play**

### **Controls**

* **Desktop:** Move your mouse to steer the ship. Click to shoot.  
* **Mobile/Tablet:** \* **Drag** anywhere on the screen to move the ship.  
  * **Tap** quickly to shoot.  
  * **Multitouch:** You can hold one finger to move and tap with another to rapid-fire.

### **Rules**

1. A multiplication question appears at the top (e.g., 6 x 7).  
2. Asteroids will fall with various numbers.  
3. **Shoot the asteroid** that contains the correct answer (42).  
4. **Avoid shooting wrong answers** (Lose 1 Life ❤️).  
5. **Do not let the correct answer pass** the bottom of the screen (Lose 1 Life ❤️).  
6. Survive as long as possible and beat the High Score\!

## **🛠️ Installation & Usage**

This game is a **Single File Application**. It requires no installation, no server, and no external assets (images or sounds are generated programmatically).

1. Download the maths\_invaders.html file.  
2. Open the file in any modern web browser (Chrome, Firefox, Safari, Edge).  
3. Enjoy\!

## **💻 Technical Details**

* **Language:** HTML5, CSS3, Vanilla JavaScript (ES6+).  
* **Rendering:** HTML5 \<canvas\> 2D Context.  
* **Audio:** Web Audio API (All sound effects are synthesized in real-time; no .mp3 or .wav files required).  
* **Storage:** Uses localStorage to persist the High Score on the device.

## **📱 Mobile Optimization**

The game includes specific event listeners for touchstart, touchmove, and touchend to differentiate between:

* **Aiming:** Dragging the finger without firing.  
* **Shooting:** Short taps (\<250ms).
