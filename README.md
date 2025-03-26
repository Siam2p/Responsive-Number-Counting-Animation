# Responsive Number Counting Animation

This project showcases a responsive number counting animation using HTML, CSS, and JavaScript. The animation dynamically counts up to specified values, making it ideal for displaying key metrics such as meals delivered, happy customers, menu items, and five-star ratings.

## Project Overview

This lightweight and visually appealing feature enhances user engagement by smoothly animating numerical values as they appear on the screen. The animation is fully responsive, ensuring a seamless experience across devices.

## Features

- **Responsive Design**: The layout adjusts to various screen sizes using CSS media queries, ensuring a smooth experience on desktops, tablets, and mobile devices.
- **Counting Animation**: The numbers count dynamically from `0` to their target values, using JavaScript to create a smooth and natural effect.
- **Font Awesome Icons**: Stylish icons visually represent each metric, adding a modern and professional touch.

## Project Structure

The project consists of three core files:

- **index.html** – Defines the structure of the webpage.
- **style.css** – Styles the webpage, ensuring responsiveness and an attractive UI.
- **script.js** – Implements the counting animation logic.

## How It Works

1. Each metric has a `span.num` element with a `data-val` attribute that holds the target number.
2. JavaScript reads these values and smoothly increments the numbers until they reach their targets.
3. The animation duration is calculated dynamically based on the target values.

## Installation & Usage

1. **Download or Clone the Repository**
2. **Open `index.html` in a Web Browser**
3. **Watch the numbers animate dynamically**

## Dependencies

This project uses Font Awesome for icons, which is loaded via CDN:
```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
```

## Customization

- Modify the `data-val` attribute in `index.html` to change target values.
- Adjust styles in `style.css` to fit your design preferences.
- Fine-tune animation speed by modifying the interval settings in `script.js`.

## Browser Compatibility

This project works seamlessly on modern browsers, including:
- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari
- Opera

## Conclusion

This responsive number counting animation is a great way to display statistics and key figures dynamically. It adds a modern and interactive touch to any website, enhancing user engagement and visual appeal.

Feel free to customize and integrate it into your projects!

# Responsive-Number-Counting-Animation
