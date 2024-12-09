# Portfolio - Starter Files

## Original Project

This repo was originally created by [Kevin Powell](https://kevinpowell.co) to make a personal blog site for the [Codementor](https://www.codementor.io/) DevProjects Challenge, [Create a fast and secure blog using Jamstack](https://www.codementor.io/projects/web/create-a-fast-and-secure-blog-using-jamstack-c93coupnxb).

According to Kevin at the time, "You are free to use them however you want to get started with the challenge, if you'd like to start working on creating the site without worrying about the content itself."

## File Structure

The package.json file defines the 11ty and other dependent modules used to build the site.

The `src` folder contains files so that you can get your project up and running. That folder contains:

- The Nunjucks file index.njk defines the body for the main page
- Nunjucks files in the `_includes` folder to use as a base for the different page layouts.
- Sass files for styling the pages
- 3 portfolio articles in the `portfolio` folder
- images and a logo in the `assets` folder

The articles are written in Markdown, and include Front Matter. It is possible that you will have to modify these a little if you wish to use them.

## Original Tutorial

You are not using Netlify CMS for this project - Netlify no longer supports their CMS.

With that in mind, you can [watch this video](https://youtu.be/4wD00RT6d-g) to see how Kevin used Eleventy, Netlify, and Netlify CMS to create a full-featured blog site built entirely with static files.


## My Projects

### Poem Site

The **Poem Site** is a simple yet elegant web page that displays Paul Laurence Dunbar's poem "Remembered." The page is designed to create a calm and reflective mood that complements the poem’s theme.

#### Project Description

The Poem Site uses custom CSS for a clean, minimal layout. It includes an image of a dove to capture the essence of the poem. The typography is enhanced by Google Fonts, and the design includes a favicon featuring a feather to symbolize the poem's tone of memory and peace.

![Dove Image](../images/Dove(cropped).jpg)
![Feather Image](../images/Feather.jpg)

#### Features

- **Poem Presentation**: "Remembered" by Paul Laurence Dunbar, styled to enhance its theme.
- **Images**: A dove image that complements the poem's mood, and a feather favicon.
- **Responsive Design**: The page is fully responsive and adjusts to various screen sizes.

#### Technologies Used

- **HTML5**
- **CSS**: Custom styles for text and layout.
- **Google Fonts**: Typography to match the poems feel.
  
#### Build and Deployment

The project follows a static site generator structure with 11ty.

- **Codebase**: The code is located in the `src` folder, and the compiled page is located in the `public` folder.
- **Live Server**: The `settings.json` file in `.vscode` configures the server to run from the `public` folder.

#### Commands

- **Installation**: `npm install`
- **Development**: `npm start` (Runs 11ty)
- **Production Build**: `npm run build` (Builds for production)

#### Credits

- **Poem**: "Remembered" by Paul Laurence Dunbar. [Source](https://www.public-domain-poetry.com/poems/remembered)
- **Dove Image**: Photo by Motoki Tonn on [Unsplash](https://unsplash.com/photos/1hfCU3dGjjI).

---

This project serves as a demonstration of my ability to create visually impactful and responsive web pages that complement and enhance literary content.

### Color Project - CodePen

#### Color Project

- **Link**: [View CodePen Project](https://codepen.io/LyssaMA/pen/GRVrVqo)
- **Description**: This project demonstrates interactive design and functionality, showcasing my coding skills and creative approach.

---

### Design Project - Figma

#### Figma Design

- **Link**: [View Figma Design](https://www.figma.com/design/vI2aNCYYgSwbngzFxwxDNr/road-less-traveled?node-id=4-10&node-type=FRAME&t=dsNSXE52Iw3ynhsL-0)
- **Description**: A design mockup showcasing a user interface concept, demonstrating my design capabilities and understanding of user experience.

---