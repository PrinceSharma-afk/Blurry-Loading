# Blurry Loading

A visually appealing web animation that simulates a progressive image reveal effect by gradually removing a blur while simultaneously increasing a loading percentage.  
This project demonstrates JavaScript DOM manipulation, CSS transitions, and timed animations.

## Live Demo
[Click here to view the project](https://princesharma-afk.github.io/Blurry-Loading/)

## Features
- **Progressive Blur Removal** – The background image starts heavily blurred and becomes clearer over time.
- **Loading Percentage Animation** – A counter starts from 0% and increments until 100%, synced with the blur effect.
- **Smooth Transitions** – Uses CSS filters and opacity for a polished, smooth animation.
- **Responsive Layout** – Works well on different screen sizes.

## How It Works
1. **JavaScript Timer (`setInterval`)**  
   A timer runs at a fixed interval (e.g., every 30ms), updating:
   - The loading percentage text.
   - The blur filter applied to the background.
   - The opacity of the text for a fade-out effect.

2. **Mapping Function**  
   A scaling function maps the loading percentage from:
   - 0–100 (percentage progress)  
   - To the corresponding blur range (e.g., 30px → 0px) and opacity (1 → 0).

3. **Stopping Condition**  
   Once the percentage reaches 100, the timer stops, leaving a fully clear image with no text overlay.

## Technologies Used
- **HTML** – Structure for the image container and loading text.
- **CSS** – Blur effect, layout styling, and smooth transitions.
- **JavaScript** – Logic for animation, percentage calculation, and DOM updates.

## Credits
- Background Image: [Unsplash](https://unsplash.com)  
- Inspired by modern CSS/JS animation techniques.

## License
This project is open-source and available under the [MIT License](LICENSE).
