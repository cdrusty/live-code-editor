
---

# PixelCode - An Online Code Editor

PixelCode is a simple online code editor that allows you to write and run HTML, CSS, and JavaScript code right in your web browser. It's a lightweight tool designed for quick code experimentation and testing.

### Live Demo - [PixelCode](https://pixelcode.vercel.app/* {
  margin: 0;
  padding: 0;
  font-family: 'Poppins', sans-serif;
  box-sizing: border-box;
}

body{
  background: #454545;
  color: #fff;
}

.container {
  width: 100%;
  height: 100vh;
  padding: 20px;
  display: flex;
}

textarea {
  width: 100%;
  height: 28%;
  background: #1f1f1f;
  color: #fff;
  padding: 10px 20px;
  border: 0;
  outline: 0;
  font-size: 18px;
}

iframe {
  width: 100%;
  height: 87%;
  background: #fff;
  border: 0;
  outline: 0;
}

label i {
  margin-left: 10px;
  margin-right: 10px;
}

label {
  display: flex;
  align-items: center;
  height: 30px;
  blackground: #000; 
}

@media (max-width: 768px) {
  .container {
    flex-direction: column;
  }
  .left, .right {
    flex-basis: 100%;
  }
  textarea {
    height: 30%;
  }
  iframe {
    height: 60%;
  }
  .container {
    height: 250vh;
  }
}
.left, .right {
  flex-basis: 50%;
  padding: 10px;
  box-sizing: border-box;
  margin-bottom: 20px;
}

#run-button {
  background: #0074d9;
  color: #fff;
  border: 0;
  padding: 10px 20px;
  font-size: 18px;
  cursor: pointer;
  transition: background 0.3s;
  display: flex;
  margin-bottom: 20px;
  right: 20px;  
  align-items: center;
  position: absolute;
  top: 10px; 
  left: 50%;
  transform: translateX(-50%);
  width: fit-content;
}

)

## Features

- Real-time code preview: See the output of your HTML and CSS code as you type.
- JavaScript execution: Write and execute JavaScript code to enhance your web projects.
- Responsive design: Works well on both desktop and mobile devices.
- Error handling: Easily identify and debug errors with the error console.
- Customizable: You can modify the code editor's appearance and functionality to suit your needs.

## Usage

1. Clone or download this repository to your local machine.
2. Open `index.html` in your web browser.
3. Use the code editor on the left to write HTML, CSS, and JavaScript code.
4. Click the "Run" button to see the output on the right.
5. Any errors will be displayed in the error console at the bottom.

## Customization

You can customize the editor by modifying the CSS and JavaScript code in `style.css` and `script.js`. Feel free to adjust the styling, add more features, or integrate external libraries as needed.

## Dependencies

- [Font Awesome](https://fontawesome.com/): Used for icons in the user interface.

## Credits

PixelCode is developed and maintained by [cdrusty]. Feel free to contribute or report issues on [GitHub](https://github.com/cdrusty/live-code-editor).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---