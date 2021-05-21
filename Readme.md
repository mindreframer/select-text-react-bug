### REACT BUG

A HTML snippet is render vastly different in React than in plain HTML. Same CSS styles, same code (structure).

![BUG SCREENSHOT](Screenshot-span-react-bug.png?raw=true "BUG")

### HTML Version

```html
<h2>PLAIN HTML -> WORKS</h2>
<div class="text-lg w-full mb-4">
  <div class="text-parts">
    <div class="inline text-part">
      <span>In</span>
      <span>PARADISE</span>
      <span>X,</span>
      <span>Mr.</span>
      <span>Camp’s</span>
      <span>eighth-grade</span>
      <span>class</span>
      <span>consisting</span>
      <span>of</span>
      <span>26</span>
      <span>students</span>
      <span>was</span>
      <span>surveyed</span>
      <span>and</span>
      <span>34.6</span>
      <span>percent</span>
      <span>of</span>
      <span>the</span>
      <span>students</span>
      <span>reported</span>
      <span>that</span>
      <span>they</span>
      <span>had</span>
      <span>at</span>
      <span>least</span>
      <span>two</span>
      <span>siblings.</span>
      <span>The</span>
      <span>average</span>
      <span>eighth‑grade</span>
      <span>class</span>
      <span>size</span>
      <span>in</span>
      <span>the</span>
      <span>state</span>
      <span>is</span>
      <span>26.</span>
      <span>If</span>
      <span>the</span>
      <span>students</span>
      <span>in</span>
      <span>Mr.</span>
      <span>Camp’s</span>
      <span>class</span>
      <span>are</span>
      <span>representative</span>
      <span>of</span>
      <span>students</span>
      <span>in</span>
      <span>the</span>
      <span>state’s</span>
      <span>eighth-grade</span>
      <span>classes</span>
      <span>and</span>
      <span>there</span>
      <span>are</span>
      <span>1,800</span>
      <span>eighth-grade</span>
      <span>classes</span>
      <span>in</span>
      <span>the</span>
      <span>state,</span>
      <span>which</span>
      <span>of</span>
      <span>the</span>
      <span>following</span>
      <span>best</span>
      <span>estimates</span>
      <span>the</span>
      <span>number</span>
      <span>of</span>
      <span>eighth‑grade</span>
      <span>students</span>
      <span>in</span>
      <span>the</span>
      <span>state</span>
      <span>who</span>
      <span>have</span>
      <span>fewer</span>
      <span>than</span>
      <span>two</span>
      <span>siblings?</span>
    </div>
  </div>
</div>
```

### JSX Version

```jsx
<div className="text-lg w-full mb-4">
  <div className="text-parts">
    <div className="inline text-part">
      <span>In</span>
      <span>PARADISE</span>
      <span>X,</span>
      <span>Mr.</span>
      <span>Camp’s</span>
      <span>eighth-grade</span>
      <span>class</span>
      <span>consisting</span>
      <span>of</span>
      <span>26</span>
      <span>students</span>
      <span>was</span>
      <span>surveyed</span>
      <span>and</span>
      <span>34.6</span>
      <span>percent</span>
      <span>of</span>
      <span>the</span>
      <span>students</span>
      <span>reported</span>
      <span>that</span>
      <span>they</span>
      <span>had</span>
      <span>at</span>
      <span>least</span>
      <span>two</span>
      <span>siblings.</span>
      <span>The</span>
      <span>average</span>
      <span>eighth‑grade</span>
      <span>class</span>
      <span>size</span>
      <span>in</span>
      <span>the</span>
      <span>state</span>
      <span>is</span>
      <span>26.</span>
      <span>If</span>
      <span>the</span>
      <span>students</span>
      <span>in</span>
      <span>Mr.</span>
      <span>Camp’s</span>
      <span>class</span>
      <span>are</span>
      <span>representative</span>
      <span>of</span>
      <span>students</span>
      <span>in</span>
      <span>the</span>
      <span>state’s</span>
      <span>eighth-grade</span>
      <span>classes</span>
      <span>and</span>
      <span>there</span>
      <span>are</span>
      <span>1,800</span>
      <span>eighth-grade</span>
      <span>classes</span>
      <span>in</span>
      <span>the</span>
      <span>state,</span>
      <span>which</span>
      <span>of</span>
      <span>the</span>
      <span>following</span>
      <span>best</span>
      <span>estimates</span>
      <span>the</span>
      <span>number</span>
      <span>of</span>
      <span>eighth‑grade</span>
      <span>students</span>
      <span>in</span>
      <span>the</span>
      <span>state</span>
      <span>who</span>
      <span>have</span>
      <span>fewer</span>
      <span>than</span>
      <span>two</span>
      <span>siblings?</span>
    </div>
  </div>
</div>
```
