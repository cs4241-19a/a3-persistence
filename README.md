Assignment 3 - Persistence: Two-tier Web Application with Flat File Database, Express server, and CSS template
===

Due: September 16th, by 11:59 AM.

This assignnment continues where we left off, extending it to use the most popular Node.js server framework (express), a flat file database suitable for small applications (lowdb), and a CSS application framework / template of your choice (Boostrap, Material Design, Semantic UI, Pure etc.)


Baseline Requirements
---

Your application is required to implement the following functionalities:

- a `Server`, created using Express (no alternatives will be accepted for this assignment)
- a `Results` functionality which shows the entire dataset residing in the server's memory
- a `Form/Entry` functionality which allows users to add, modify, and delete data items (must be all three!) associated with their user name / account.
- Use of at least five [Express middleware packages](https://expressjs.com/en/resources/middleware.html). Explore! 
- Basic authentication using the [Passport middleware](http://www.passportjs.org) for Express (this counts as one of your five middleware packages). We encourage using the Local strategy, but OAuth (Open Authentication) can also be used for additional technical achievement. The course staff cannot help you with the various flavors of OAuth strategies. YOU MUST PROVIDE US WITH ACCOUNT CREDENTIALS TO LOGIN TO YOUR APPLICATION IF YOU USE OAUTH. The course staff cannot be expected to have credentials for any particular OAuth service.
- Persistent data storage in between server sessions. [lowdb](https://github.com/typicode/lowdb) is a suitable database package for this assignment and will be discussed in class.
- Use of a [CSS framework or template](https://github.com/troxler/awesome-css-frameworks). This should do the bulk of your styling/CSS for you and be appropriate to your application. For example, don't use [NES.css](https://nostalgic-css.github.io/NES.css/) (which is awesome!) unless you're creating a game or some type of retro 80s site.

Your application is required to demonstrate the use of the following concepts:

HTML:
- HTML input tags and form fields of various flavors (`<textarea>`, `<input>`, checkboxes, radio buttons etc.)
- HTML that can display all data *for a particular authenticated user*. Note that this is different from the last assignnment, which required the display of all data in memory on the server.

Note that it might make sense to have two simple pages for this assignment, one that handles login / authentication, and one that contains the rest of your application. For this assignment, it is acceptable to simply create new user accounts upon login if none exist, however, you must alert your users to this fact. If you're not using OAuth 

CSS:
- CSS styling should primarily be provided by your chosen template/framework. Oftentimes a great deal of care has been put into designing CSS templates; don't override their stylesheets unless you are extremely confident in your graphic design capabilities. The idea is to use CSS templates that give you a professional looking design aesthetic without requiring you to be a graphic designer yourself.

JavaScript:
- At minimum, a small amount of front-end JavaScript to get / fetch data from the server. See the [previous assignment](https://github.com/cs4241-19a/a2-shortstack) for reference.

Node.js:
- A server using Express, at least five pieces of Express middleware, and a persistent database (a flat file using lowdb is great).

Deliverables
---

Do the following to complete this assignment:

1. Implement your project with the above requirements. A good potential starting point is to use the "hello-express" project template inside of Glitch; this appears as an option when you hit the "New Project" button. Use the work you did in the last assignment as a reference to implement functionality, as well as the notes from class on 9/9 and 9/12.
2. If you developed your project locally, deploy your project to Glitch, and fill in the appropriate fields in your package.json file.
3. Test your project to make sure that when someone goes to your main page on Glitch, it displays correctly.
4. Ensure that your project has the proper naming scheme `a3-yourname` so we can find it.
5. Fork this repository and modify the README to the specifications below. You do not need to include any of your project files in this repo (we will see those on Glitch), you only need to update and commit the README file.
6. Create and submit a Pull Request to the original repo. Name the pull request using the following template: `a3-gitname-firstname-lastname`.

Sample Readme (delete the above when you're ready to submit, and modify the below so with your links and descriptions)
---

## Your Web Application Title

your glitch link e.g. http://a3-charlieroberts.glitch.me

Include a very brief summary of your project here. Images are encouraged, along with concise, high-level text. Be sure to include:

- the goal of the application
- challenges you faced in realizing the application
- what authentication strategy / database you chose to use and why (choosing one because it seemed the easiest to implement is perfectly acceptable)
- what CSS framework you used and why.
  - include any modifications to the CSS framework you made via custom CSS you authored.
- the five Express middleware packages you used and a short (one sentence) summary of what each one does.

## Technical Achievements
- **Tech Achievement 1**: I used OAuth authentication via the GitHub strategy
- **Tech Achievement 2**: I used over ten Express middleware packages, enabling me to create a server that...

### Design/Evaluation Achievements
- **Design Achievement 1**: I tested my application using screen reading software, and found that...
- **Design Achievement 2**: I followed best practices for accessibility, including providing alt attributes for images and using semantic HTML. There are no `<div>` or `<span>` elements in my document.
- **Design Achievement 3**: We tested the application with n=X users, finding that...
