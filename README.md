# Animation

CSS animation is a technique to create dynamic visual effects in web pages using CSS properties, enhancing user experience and interactivity.

![ghost](https://github.com/stefanoturcarelli/animation/assets/67341828/855030c9-a804-46ef-93b9-81084623d12b)

# Buttons

![Media1-ezgif com-video-to-gif-converter](https://github.com/stefanoturcarelli/css-animation/assets/67341828/f7337398-1650-4762-ac3a-f5690c694e80)



```html
<button class="btn btn-1">Button 1</button>
```

```css
.btn {
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  -o-appearance: none;
  -ms-appearance: none;
  background: none;
  border: none;
  cursor: pointer;
  outline: none;
  padding: 20px 40px;
  border-radius: 8px;
  font-size: 28px;
  font-weight: 600;
  transition: all 0.3s ease;
  color: #212121;
}

.btn-1 {
  background: linear-gradient(to right, transparent 50%, #212121 50%);
  color: #212121;
  border: 3px solid #212121;
  background-size: 200%;
  background-position: -0%;
}

.btn-1:hover {
  color: #f8f8f8;
  background-position: -100%;
}
```
