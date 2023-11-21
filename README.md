# Terribly Tiny Tales Assignment
<h3>Student name : Aniket Kumar</h3>
<h3>College : Lovely Professional University</h3>

<hr>
## Problem Statement

Develop a frontend in Reactjs or Nextjs, which does the following:

1. Renders a "profile screen" as follows: https://www.terriblytinytales.com/profile.jpeg (this is a sample screenshot taken from mobile view)

2. The profile data can be hardcoded in a local JSON and need not have a backend.

3. The screen when opened on different mobile types, should render consistently. This can be checked in Chrome Inspect in mobile view, by changing device types or on actual physical devices.

<hr style="color:green;">



<hr>
## Steps to run the project

1. Clone the repository.
2. Run `npm install` to install the dependencies.
3. Run `npm start` to run the project.
4. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.
5. Inspect the page and change the device type to view the responsiveness.

## Components

1. <b>App.js</b> - The main component which renders the All child components.

    Consists of 3 child components:
    1. Navbar
    2. Profile
    3. Posts

    Also consists 2 elements:
    1. Cover Image
    2. Posts Container UI


2. <b>Navbar.jsx</b> - The component which renders the Navbar.
3. <b>Profile.jsx</b> - The component which renders the Profile.
4. <b>Posts.jsx</b> - The component which renders the Posts.

## Fuunctionalities

1. The Navbar is fixed at the top of the page.
2. The Profile fetch and renders the profile data and show total number of followers, following and user reviews.
3. The Posts fetch and renders the posts data and show total number of posts along with like button which increments the number of likes on click.
4. The page is responsive and can be viewed on different mobile types.
