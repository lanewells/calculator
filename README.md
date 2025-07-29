# Calculator

Competencies: HMTL, CSS, Javascript functions, and DOM

## User Stories

1. A user should be able to select numbers so that they can do things with them.
2. A user should be able to add numbers together.
3. A user should be able to subtract numbers.
4. A user should be able to divide numbers.
5. A user should be able to multiply numbers together.
6. A user should be able to see the output.
7. A user should be able to clear all operations and start from 0.

## Setup

Create a directory in your student lab folder called `calculator`.

Within `calculator` setup an `index.html` `app.js` and `style.css` and get your code wired up.

## Design your calculator.

1. Before you type out your HTML, draw out how you want your calculator to look and start thinking about how to structure your html. Don't spend more than 10 minutes thinking through this part, but put something on paper before you code. This is your chance to create a wireframe.

2. Think about where the input and output needs to be (buttons and display screen).

## Write the html needed for the calculator

1. Now that you have your wireframe drawn, use it to write the html needed for your calculator.

2. Think about using ids and/or classes to help you select your elements.

## Initial CSS

If you want to keep things simple, start by putting a border around all of your divs:

```
div {
    border: 1px solid black;
}
```

- Set a height and width on your elements

## JS: Things to think about

1. Think about how you are going to store the state of the calculator. What kind of information do you need to track?

2. When the user clicks a button, how are you going to get which number or operation they clicked? When they click a certain button, what code are you going to have to run?

3. Try not to use a separate event handler for each button. What could you use for the numbers to by grab the value from the clicked element?

## More

1. Add a `clear` button that will clear your screen and start over at zero.

2. Wouldn't it be nice if the user could use their keyboard? How can you set even listners on a `keyup` or `keydown`?

3. Once you have the basics of the calculator working, look back at your code. You want to make it [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself). Start to refactor your code to take out unneeded parts or implement something in a better way.

4. What other operations can you add to the calculator? If you have time, implement them. If you don't have time, but have some ideas, add comments to your code about what you'd like to add. How might you implement them? Is your code friendly to adding in new operations if another developer came in to add something to your code?

5. Can you save the results somewhere? Look into `localStorage`
