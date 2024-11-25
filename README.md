# Theme JTR 2.0 with PrimeNG

You find further information on this website: https://primeng.org/theming

If you want to style a PrimeNG component for the JTR 2.0 (https://github.com/Nalochen/jtr-2.0) you can use this repository.
This repository is a copy of the primeng theming repository except the "jtr"-folder is the specific JTR theme.

## How to use
1. Clone Repository
2. Run `npm install`
3. Create a new branch with the name of your ticket
4. Feel free to style the components in the variables-folder
5. When you are done, run `sass --update themes/jtr/primeng-theme.scss:themes/jtr/primeng-theme.css` to compile the scss to css.
   You can now just copy the primeng-theme.css file and paste it in the JTR Project where the old theme is located
6. Create a pull request and merge your branch into the main branch

## Things to come:

I am planning to set up a small angular project in this repository where all components are visible,
so that you can see how your changes affect the components.

Also, I want to directly link this repository to the JTR Repository, so that you don't have to copy the css file manually.

