# 🎊 Add Your Wedding Photos

## How to Use Your Own Wedding Photos

1. **Add Your Photos** 📸
   - Place your wedding photos in this folder (`public/photos/`)
   - Name them like: `wedding-1.jpg`, `wedding-2.jpg`, etc.
   - Supported formats: `.jpg`, `.jpeg`, `.png`, `.webp`

2. **Update the Carousel** ✏️
   - Open `src/App.jsx`
   - Find the `photos` array (around line 5)
   - Each object should have:
     - `image`: path to your photo (e.g., `/photos/wedding-1.jpg`)
     - `title`: caption for the photo
     - `subtitle`: description for the photo

3. **Example:**
   ```javascript
   const photos = [
     {
       image: '/photos/your-photo-1.jpg',
       title: 'Getting Ready',
       subtitle: 'The morning preparations',
     },
     {
       image: '/photos/your-photo-2.jpg',
       title: 'The Ceremony',
       subtitle: 'Our beautiful vows',
     },
     // Add more photos...
   ];
   ```

4. **Update Story Section** 👰
   - In the Story section, change `/photos/wedding-5.jpg` to your favorite photo

5. **Run the App** 🚀
   - Open terminal in `wedding-carousel` folder
   - Run: `npm run dev`
   - Visit: `http://localhost:5173`

## Tips
- Use high-quality photos (at least 1200px wide recommended)
- The carousel auto-rotates every 4.5 seconds
- Click the dots at the bottom to navigate manually
- Hover over gallery images for a zoom effect

Enjoy your beautiful wedding carousel! 💕
