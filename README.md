# PPlanner - Student Placement Planner 🎓

PPlanner is a responsive, multi-page front-end project designed for students managing their study tasks and preparing for college placements. It provides a clean, dark-mode interface for tracking to-do items, scheduling interviews, and setting reminders for placement-related events.

This project is built with pure HTML5 and CSS3, demonstrating modern layout techniques (Flexbox, Grid), CSS variables, and keyframe animations for interactive elements without using any JavaScript.



## Features

* Modern, Dark-Mode UI: A sleek, responsive design that looks great on all devices.
* Multi-Page Layout: A complete user flow with four distinct pages:
    * Login (index.html)
    * Sign Up (signup.html)
    * Main Dashboard (dashboard.html)
    * Placement Planner (planner.html)
* Interactive Task Dashboard:
    * A dynamic to-do list for managing study and prep tasks.
    * contenteditable fields allow users to type directly into task items.
    * Task templates for common activities like "Coding Problem Sprint" and "Resume Update."
    * CSS-driven progress bar.
* Dedicated Placement Planner:
    * A separate view for scheduling key events like pre-placement talks, online tests, and interviews.
    * Pure CSS Alerts: Clicking "Set Alert" triggers CSS keyframe animations for a ringing bell and a pop-up "toast" notification.
* Pure CSS Components: All interactive elements, hover effects, and toggles are built using only HTML and CSS.

## Pages Included

1.  Login (index.html): The landing page for returning users to log in.
2.  Sign Up (signup.html): A registration page for new users.
3.  Dashboard (dashboard.html): The main hub for managing daily to-do tasks, with slots to use pre-built templates.
4.  Planner (planner.html): A specialized page for scheduling placement-specific events with CSS-based alerts.
5.  Stylesheet (style.css): A single, comprehensive stylesheet using CSS variables, Flexbox, and Grid.

## Technologies Used

* HTML5: Semantic markup for structure and accessibility.
* CSS3:
    * CSS Variables: For easy theme management (colors, sizing).
    * Flexbox & CSS Grid: For robust, responsive layouts.
    * CSS Animations (@keyframes): Used to create the bell and toast-pop animations on the planner page.
    * Advanced Selectors: Using pseudo-classes like :checked to trigger UI changes without JavaScript.

## How to Use

This is a static front-end project. No build process is required.

1.  Clone the repository:
    sh
    git clone [https://github.com/your-username/pplanner.git](https://github.com/DeveshBhagwani/to-do-list.git)
    
2.  Navigate to the directory:
    sh
    cd pplanner
    
3.  Open the files in your browser:
     Open index.html to start from the login page.
     You can also open dashboard.html or planner.html directly to view those pages.

## Future Improvements

As a front-end template, this project is ready to be wired up to a back-end. Future steps could include:
* Integrating JavaScript to manage task state, save data to localStorage, and make the forms functional.
* Connecting the application to a back-end (like Node.js, Django, or Firebase) to handle user authentication and database storage.

## License

This project is open-source. Feel free to use it as a template for your own applications.
