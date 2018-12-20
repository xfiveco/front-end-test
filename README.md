# Front-end Test Project

Convert the following designs to HTML/CSS/JS (pure front-end).

## Infinite scroll page

![inifnite scroll preview](https://github.com/xfiveco/front-end-test/blob/master/infinite-scroll.jpg?raw=true)

## Single article page

![single artivle preview](https://github.com/xfiveco/front-end-test/blob/master/single-article.jpg?raw=true)

## Requirements

1. Create project using [Chisel](https://www.getchisel.co/).
2. Make it responsive using your best judgement.
3. Use [ITCSS](https://www.xfive.co/blog/itcss-scalable-maintainable-css-architecture/) and [BEM](https://csswizardry.com/2015/08/bemit-taking-the-bem-naming-convention-a-step-further/) naming convention.
4. Create custom infinite scroll effect - use custom JavaScript (preferably the modern JS standards and APIs). Don't hesitate to use helpful NPM packages but **keep the JS bundle size low**.
5. Use this API to display posts: https://stormy-shelf-93141.herokuapp.com/ – `_page` and `_limit` query parameters are available.
6. You can add an animated transition between the infinite scroll page and the article page. Keep in mind it's an **optional requirement** though.
7. When scrolling, the top header should scroll up to the top of the page and then stick to the top.
8. We pay attention to both CSS and JS bundle sizes. Import just what you require and _not the whole package_.
9. We appreciate _a readable code_.
10. Avoid using huge commits hiding your progress. The initial commit should be a bare Chisel install. Feel free to work on a branch and use rebase to adjust your commits before submitting the final version.

## Design

Design is available in Figma at [https://www.figma.com/file/vt3EnhEv2BGCWtMW15tHl1/Xfive-Front-end-Test](https://www.figma.com/file/vt3EnhEv2BGCWtMW15tHl1/Xfive-Front-end-Test). If you haven't already, sign up for a free Figma account, so you can work with the design.

Prototype: [https://www.figma.com/proto/vt3EnhEv2BGCWtMW15tHl1/Xfive-Front-end-Test](https://www.figma.com/proto/vt3EnhEv2BGCWtMW15tHl1/Xfive-Front-end-Test)

## Supported browsers

Ensure that the elements work and display correctly in the following browsers:

- Firefox (latest version)
- Google Chrome (latest version)
- Microsoft Edge (latest version)
- Internet Explorer 11 – in this case **we don't require all the functionalities** as long as the page is readable

## Coding standards

When working on the project use consistent coding style. Follow what's already in Chisel - EditorConfig, stylelint, ESLint (see [Code Quality](https://www.getchisel.co/docs/development/code-quality/)), [ITCSS](https://www.getchisel.co/docs/development/itcss/), etc.

## Project Deadline

Ideally you'd finish the test project in 1 week. It shouldn't take you longer than 2 weeks.

## Quality Assurance

Use the following checklist to ensure high quality of the project.

### General

- Are all requirements set above met?
- Can the project be built using `npm run build` or `yarn build` without any errors and warnings?
- Is the page working without any JS errors?

### Browser check

- Does page display and work correctly in supported browsers?

### Coding Standards

- Is coding style (for HTML/CSS/JS) consistent?
