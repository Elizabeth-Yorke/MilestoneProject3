# Project X Website

Welcome the Great Reads Website. This is a full stack website that allows users to manage a common dataset of book reviews. It contains a well designed relational database with a structure that allows users to store and manipulate data records about book reviews. This database allows users CRUD functionality, meaning they can create, locate, display, edit and delete records from the database. The website has a main navigation system and a structured layout. The website was built using HTML, CSS, JavaScript and Python. A number of frameworks and libraries including Flask, PostgreSQL and Materlialize were used in the creation of this project. Full details and attribution can be found in the Technologies and Credits sections, further down this documentation.

A live version of the site can be viewed from [here.](#)

Here is an image of the website, using the "Am I Responsive" site, showing what it looks like when viewed on different screen sizes:
![screenshot](#)

### Colour Scheme

The colours used for the website are listed below:
- #000000 Black
- #c62828 Red
- #ffeb3b Yellow
- #FFFFFF White

I chose these colours because they are eye catching but also provide a high contrast, making it easy for the users to read the content. This is particularly important given that this is a website about reading. The online colour contrast checker [WebAIM](https://webaim.org/resources/contrastchecker/) was used to varify the contrast between the colours chosen.

### Typography

The fonts used for the website are listed below:
- Kaushan [Google Fonts](https://fonts.googleapis.com/css2?family=Kaushan+Script&display=swap)
- Caveat [Google Fonts](https://fonts.googleapis.com/css2?family=Caveat:wght@400..700&family=Margarine&display=swap)
- Three

The heading fonts were chosen because they look a little bit like handwriting, as this is supposed to make the reader feel more like writing their own reviews.
The main script font was kept as simple as possible to ensure the easiest reading experience for the user.

### Database Structure

The relational database built into this project is designed to suit its function. Below is a description fo the database:

It contains a Books table. In the Books table, each book only has one number, one title, one author, and one number of votes affiliated with it. The number in the Votes column can be updated.

| Book_Number | Title | Author | Votes |
| --- | --- | --- | --- |

It contains a second, much larger related table, related to the first by Book_Number. This is the Reviews table. In the Reviews table, there can be many Reviews for the same book, but each review only has one Review_Author, one Last_Date_Edited and one Review_Number. Entries in the Review column and the Last_Date_Edited column can be updated. Entire rows of this table can be added and deleted.

| Book_Number | Review | Review_Author | Last_Date_Edited | Review_Number |
| --- | --- | --- | --- | --- |

It contains a third table, related to the second table by Review_Number. This is the Comments table. In the Comments table, there can be many Comments for each review, but each comment only has one Comment_Author, one Comment_Date and one Comment_Number. Entire rows of this column can be added and deleted by users.

| Review_Number | Comment | Comment_Author | Comment_Number |

## User Stories

### New Site Users

- As a new site user, I would like to be able to find reviews of books I am interested in.
- As a new site user, I would like to be able to read reviews of books I am interested in.

### Returning Site Users

- As a returning site user, I would like to be able to write and add book reviews of my own.
- As a returning site user, I would like to be able to quickly rate books that have already been reviewed by other people.

### Site Admin

- As a site administrator, I would like to be able to easily manage the database contained within the website.
- As a site administrator, I would like to be able to read and write book reviews as a site user.

### Site Owner

- As a site owner, I would like to be able to make money from people looking to buy books recommended by this website.
- As a site owner, I would like to be able to read and write book reviews as a site user.

## Wireframes

| Page | Phone | Tablet | Desktop |
| --- | --- | --- | --- |
| Home | --- | --- | --- |
| Read Reviews | --- | --- | --- |
| Write Reviews | --- | --- | --- |
| Login | --- | --- | --- |

## Features

### Existing Features

Special features of this website:
- Users are able to create and upload their own book reviews to the relational database.
- Users are able to edit and delete their own book reviews in the relational database.
- Users are able to find and read book reviews that are already on the relational database.
- Users are able to upvote and comment on book reviews that are already on the relational database.

### Future Features

Features I would like to add to this website:
- Links to websites selling each book that is reviewed, such that the site owner could conceivably earn money from people looking to buy the books.

## Technologies Used

- [HTML](https://en.wikipedia.org/wiki/HTML) programming language used for the front end.
- [CSS](https://en.wikipedia.org/wiki/CSS) programming language used for the front end.
- [JavaScript](https://en.wikipedia.org/wiki/JavaScript) programming language used for front end functionality.
- [Python](https://en.wikipedia.org/wiki/Python_(programming_language)) programming language used for back end functionality.
- [Flask](https://en.wikipedia.org/wiki/Flask_(web_framework)) a Python framework used for back end functionality.
- [PostgreSQL](https://en.wikipedia.org/wiki/PostgreSQL) relationational database management system used for managing the databases.
- [Git](https://en.wikipedia.org/wiki/Git) version control system used for version control.
- [Materialize](https://materializecss.com/) css and javaScript framework used for complex components such as the main navigation menu. 

## Tools Used

- [GitHub](https://github.com) used for secure online code storage.
- [GitHub Pages](https://pages.github.com) used for hosting the deployed front-end site.
- [Gitpod Enterprise](https://www.gitpod.io/docs/enterprise/overview) used as a cloud-based IDE for development.
- [Bootstrap](https://getbootstrap.com) used as the front-end CSS framework for modern responsiveness and pre-built components.

## Testing

This site is fully responsive. It works on different screen sizes and in different browsers. It meets all the standards for clean code and accessibility.
For details of the site testing process, please go to [TESTING.md](TESTING.md) file.

## Deployment

The site was deployed to GitHub Pages, by following these steps:
- Go to the [GitHub repository](#)
- Go to Settings 
- Go to the source section drop-down menu and select the **Main** Branch. 
- Click "Save".

The live link can be found [here](#)

### Local Deployment

#### Cloning

You can clone the repository by following these steps:

1. Go to the [GitHub repository](#) 
2. Locate the Code button above the list of files and click it 
3. Select if you prefer to clone using HTTPS, SSH, or GitHub CLI and click the copy button to copy the URL to your clipboard
4. Open Git Bash or Terminal
5. Change the current working directory to the one where you want the cloned directory
6. In your IDE Terminal, copy and paste (#)
7. Press Enter to create your local clone.

#### Forking

Forking a repository allows you to edit and add to it without changing the original repository.
You can fork this repository by following these steps:

1. Log in to GitHub and locate the [GitHub Repository](#)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. Once clicked, you should now have a copy of the original repository in your own GitHub account!

### Local VS Deployment

There are no notable differences between the local and the deploed websites.

## Credits

### Content

Here is a list of some of the websites that I used to help build the website.

| Source | Location | Notes |
| --- | --- | --- |


### Media

The images I used were from the following sites:

| Source | Location | Type | Notes |
| --- | --- | --- | --- |

The following sites were used to edit and compress the images:

| Source | Location | Type | Notes |
| --- | --- | --- | --- |
| [TinyPNG](https://tinypng.com) | entire site | image | tool for image compression |
| [PhotoPea](https://www.photopea.com) | entire site | image | tool for editing photos |

### Acknowledgements

- I would like to thank 

