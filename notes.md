# These are some important notes related to each topic each day.

## Day 1:

- Get keys pressed in js using event keydown, keyup or keypress
- Get ascii code of pressed key with event.keyCode
- ES6 formatting
  ```
  `div[data-key="${code}"]`
  ```
- Add css classes in javascript using .classList.add("classname")
- datasets can be used in js as `this.dataset.dataname` where dataname is declared in HTML as an attribute `data-dataname="anything"`

## Day 2:

- use window.setInterval(functioname, timeoutMS) to call a function after every given number of timeout.

## Day 3:

### CSS Variables

- Declaring and using CSS variables
  ```
    :root{
        --base: yellow;
        --spacing: 10px;
        --blur: 10px;
    }
    img {
        padding: var(--spacing);
        background: var(--base);
        filter: blur(var(--blur));
      }
  ```
- Accessing CSS variables
  ```
  document.documentElement.style.setProperty(--`${this.name}` , this.value)
  ```

## Day 4:

- filter() : returns array of object under some condition specified in function.
- map() : returns array from an object where you want a specific part of object like first name or last name.
- sort() : sorts the array . takes a compare function as an argument and in that function we pass first and second value of object and compare them on certain value and return 1 or -1.
- reduce() : it takes two params accumulator and reducer . Helpful in creating dictionary from array with key value pairs.
