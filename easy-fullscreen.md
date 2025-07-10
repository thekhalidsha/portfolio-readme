# 🧩 easy-fullscreen

> A simple and lightweight React component for creating **fullscreen sliding sections** – horizontally or vertically.  
> 📦 [View on NPM](https://www.npmjs.com/package/@thekhalidsha/easy-fullscreen)

---

## 🚀 About the Project

**easy-fullscreen** is a custom-built React component designed for creating immersive, slide-based experiences. Whether you're building a modern portfolio, a landing page, or a digital presentation, this component makes it easy to structure your site into fullscreen slides that **slide smoothly one at a time**, either **vertically or horizontally**, mimicking swipe-based transitions.

Built with customization in mind, you can easily control direction, dimensions, dot navigation, and more.

---

## 📦 Installation

```bash
npm install @thekhalidsha/easy-fullscreen
```

---

## ✨ Features

- ✅ **Fullscreen slide transitions**  
- ✅ **Horizontal or vertical swipe effect**  
- ✅ **Slide navigation dots with color and position controls**  
- ✅ **Responsive and lightweight**  
- ✅ **Perfect for portfolios, presentations, and landing pages**  
- ✅ **Easy to integrate** – plug and play component  

---

## 🧑‍💻 Usage

```jsx
import EasyFullScreen from '@thekhalidsha/easy-fullscreen';

const App = () => {
  return (
    <div>
      <EasyFullScreen
        direction="horizontal"
        SliderWidth="100vw"
        SliderHeight="100vh"
        showDots={true}
        dotColor="gray"
        activeDotColor="blue"
        navDotsPosition="top"
        className=""
        SlideHeight=""
        SlideWidth=""
      >
        <div>
          <h2>Slide 1</h2>
          <p>This is the first slide.</p>
        </div>
        <div>
          <h2>Slide 2</h2>
          <p>This is the second slide.</p>
        </div>
        <div>
          <h2>Slide 3</h2>
          <p>This is the third slide.</p>
        </div>
      </EasyFullScreen>
    </div>
  );
};

export default App;
```

---

## 👨‍💻 Author

**Mohammed Khalid**  
*Full Stack Developer (ReactJs/Dango) (PHP as well!)*  
📍 Kerala, India  
📧 thekhalidsha@gmail.com

---

## 📝 License

This project is open source and free to use under the MIT License.  
Feel free to use it in personal or commercial projects. Star the package on NPM if you find it useful!

---