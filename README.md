# 💕 Love Funny Website

A playful and interactive web application that creates a fun "proposal" experience with a twist! This website features an engaging user interface where clicking "No" leads to multiple attempts to change your mind, complete with animated GIFs and a mischievous button that tries to escape.

## ✨ Features

- **Interactive Proposal Flow**: Start with a simple question and navigate through different responses
- **Persuasive "No" Pages**: Multiple pages that try to convince you to say "Yes" when you click "No"
- **Escape Button**: On the final "No" page, the button moves randomly when you try to hover over it (you can't escape saying "Yes"!)
- **Animated GIFs**: Uses Tenor GIFs to add visual appeal and humor to each page
- **Responsive Design**: Clean, modern UI with a romantic pink color scheme
- **Mobile-Friendly**: Works seamlessly on all device sizes

## 🎯 How It Works

1. **Main Page** (`index.html`): Asks "Do you love me?" with Yes/No options
2. **Yes Path**: Clicking "Yes" takes you to a celebration page with a happy message
3. **No Path**: Clicking "No" takes you through a series of pages:
   - `no1.html`: First attempt to reconsider
   - `no2.html`: Second attempt with more persuasion
   - `no3.html`: Final attempt where the "No" button tries to escape by moving randomly when hovered

## 🛠️ Technologies Used

- **HTML5**: Structure and content
- **CSS3**: Styling with flexbox for responsive layout
- **JavaScript**: Interactive button movement functionality
- **Tenor GIF API**: Embedded animated GIFs

## 📁 Project Structure

```
love-funny-website/
├── index.html      # Main landing page
├── yes.html        # Success page when "Yes" is clicked
├── no1.html        # First "No" response page
├── no2.html        # Second "No" response page
├── no3.html        # Final "No" response page (with moving button)
├── style.css       # Main stylesheet
├── script.js       # JavaScript for button movement
└── README.md       # This file
```

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd love-funny-website
   ```

2. Open `index.html` in your web browser:
   ```bash
   # Using a simple HTTP server (recommended)
   python -m http.server 8000
   # Then visit http://localhost:8000
   
   # Or simply double-click index.html to open in your browser
   ```

3. Start the fun! Click through the pages and try to click "No" on the final page 😉

## 🎨 Customization

- **Colors**: Modify the `background-color` in `style.css` to change the theme
- **Messages**: Edit the text content in any HTML file to personalize messages
- **GIFs**: Replace Tenor GIF IDs in the HTML files to use different animations
- **Button Behavior**: Adjust the random movement logic in `script.js`

## 📝 Notes

- The website requires an internet connection to load Tenor GIFs
- The moving button effect uses JavaScript event listeners and CSS positioning
- All pages are self-contained and can be customized independently

## 💝 Use Cases

- Fun proposal or confession website
- Valentine's Day surprise
- Birthday or anniversary gift
- Just for laughs with friends!

## 📄 License

This project is open source and available for personal use and modifications.

---

Made with ❤️ and a lot of code 😄
