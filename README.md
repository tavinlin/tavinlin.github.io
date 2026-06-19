# Portfolio Website

This website was built using HTML, CSS, and some Javascript. I use Microsoft's **Live Preview** extension in Visual Studio Code run and develop the website locally. Use whichever server you feel comfortable using.

## Editing and Building the Website

This website uses **TailwindCSS** to build the CSS. You will need to have **NPM** installed on your computer.

1. Run `git clone https://github.com/tavinlin/tavinlin.github.io.git` on the terminal/command prompt
2. Then `cd tavinlin.github.io`
3. Create a file called **input.css** in the **css** folder
4. Open the **input.css** file and add `@import "tailwindcss";` on the first line then save and close.
5. Run `npm install` to install everything in the **package.json**
6. Run `npx @tailwindcss/cli -i ./css/input.css -o ./css/main.css --watch` to have **TailwindCSS CLI** continuosly check any class change in the HTML file and update **main.css**