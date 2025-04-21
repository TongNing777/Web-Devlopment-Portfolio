# DCS-325-Portfolio

This is my portfolio for the DCS325 Web Development course, which includes all the content I learned from this course.

There is an example file inside each folder, where I provide some code I wrote this semester, related to the topic.

Below, I also provide a menu for each folder, and  a brief discussion of what role that topic/tool/framework plays in developing a website.

At the end of the README.md, I answered the reflection questions.


## Sections

1. [HTML](./HTML/) - Basics of structuring web pages. HTML generally structures content in groups, such as `<header>`, `<main>`, and `<section>`, making the content easier to read by arranging the layouts.

2. [CSS](./CSS/) — CSS allows flexible styling across screen sizes and devices, improving the visual presentation of a webpage layout, colors, fonts, and spacing.

3. [JavaScript](./JavaScript/) — Adding interactivity and functionality. It allows developers to respond to user actions (e.g., clicks) and build features like sliders and carousels.

4. [ssh & scp](./ssh%20&%20scp/) - SSH provides secure access to remote servers. SSH keys improve security and eliminate the need to type passwords every time. SCP allows developers to securely transfer files (e.g., uploading websites).

5. [React](./React/) - React builds interactive components. Components (like `<Navbar />` or `<Card />`) make code reusable and easier to manage. React handles dynamic updates efficiently.

6. [Bootstrap](./Bootstrap/) - Bootstrap is a CSS framework with pre-styled components (e.g., buttons, navbars) and a grid system. It helps developers build responsive websites quickly without custom CSS.

7. [TailwindCSS](./TailwindCSS/) — It allows developers to style elements directly in their HTML/JSX using predefined class names (e.g., `p-4`, `bg-gray-100`). It's fast, flexible, and highly customizable. Compared to CSS, Tailwind CSS doesn't need to switch between HTML and CSS and allows consistent design using a design system.

8. [ShadCN UI](./ShadCN%20UI/) - ShadCN/UI provides ready-to-use, accessible components (like buttons and dialogs) built with Tailwind.

9. [User Experience (Krug)](./User%20Experience%20(Krug)/) - Steve Krug’s UX principles provide tips for making user-friendly websites. They emphasize simplicity, clarity, and navigation without confusing users.

10. [Accessibility](./Accessibility/) - Accessibility ensures websites are usable by everyone, including people with disabilities. This includes keyboard navigation, screen reader support, high color contrast, visual hierarchy, and breadcrumbs.

11. [Figma](./Figma/) - Figma is a design and prototyping tool to plan websites before coding visually. It helps define layouts, color schemes, and user flows, ensuring consistency and a better design.

12. [Cursor](./Cursor/) - Cursor is an AI-assisted code editor that helps generate and explain code. It enhances productivity by offering suggestions and debugging help during development, but developers still need to style and debug.

13. [Google Firebase for backend](./Google%20Firebase%20for%20backend/) - Firebase provides backend services like authentication, databases, and hosting. It lets front-end developers implement login systems and save user data.
    

## Reflection Questions
1. What was your experience in using React+Vite for building web apps compared to "rolling your own" using HTML, CSS, & JavaScript?
   
   I think using HTML, CSS, & JavaScript are the basics of web development. It taught me how to structure content, style layouts, and add interactivity.
   React+Vite builds on that foundation, making the development process faster and more organized. I could directly implement some components into my website by using Bootstrap and ShadCN/UI, which also makes my code cleaner and easier to manage.
   However, many files and coding languages are included, which sometimes confuse me. I think I still need to spend more time on the setup of React+Vite to better understand it and create the website using it.
   Overall, I found React + Vite more efficient for more modern or multi-page web apps, while plain HTML/CSS/JS is great for learning and small projects.
   
2. What are the primary takeaways you had from reading Krug's book and your corresponding analysis of sites?

   I have learned that it is important to keep the website concise and stay coherent between each web page to minimize users' cognitive process and guessing. It's important to minimize the amount of thinking users have to do — navigation, layout, and wording should be informative.
   One of the main ideas that stood out to me is how users tend to skim rather than read, and click based on visual cues or keywords. This reminded me of the implicit thinking processes users go through: they rely on instinct and speed, not deep analysis.
   Because of that, pages should stay consistent in structure and tone, so users don’t have to relearn how to interact with each part of the site.
   
3. What is the importance of accessibility (give a few explicit examples), and what steps can (and should) you take in assessing the accessibility of your site?

   Accessibility ensures that everyone, including people with disabilities, can use websites.
   Visually impaired users rely on screen readers to navigate a site. They miss essential content without proper semantic HTML and alt attributes on images.
   Keyboard-only users (e.g., those with motor disabilities) must be able to navigate without a mouse. Poor focus management or custom buttons can block access.
   Colorblind users may struggle to read text without contrasting the text and background.
   When assessing the accessibility, I examine the websites through navigation (using keyboards, language and texts (using a screen reader and language use), and colors (contrast and links).
   
4. In what ways did the different design sprints, and use of Figma, help you in thinking about what an end product should look like and how it should function?

   Using Figma during design sprints helped me visualize a website's structure, flow, and user interactions before writing any code. It also allowed me to experiment with layout ideas, test navigation patterns, and spot accessibility issues early on.
   Designing the layouts before coding helps me to consider accessibility and the users' experience, as I plan the content hierarchy and make sure headings and buttons are placed and labeled accessibly.
   Figma also makes collaboration easier, which allows designing the website first, I could get feedback on the design from others, make changes quickly before building, and make dividing the work easier.
   
5. What takeaways do you have from working with AI/LLMs through Cursor (or similar) in building web applications?

   I think Cursor is really helpful when building a website, making the process much faster by setting up the basic projects and adding more components through more detailed instructions provided.
   However, using Cursor also makes me rely on AI since it is very convenient and fast.
   Overall, I think Cursor is really helpful, but I still need to add more detailed changes and manual debugging to make the website prettier.
   
6. What was your favorite thing (or deemed most useful) that we covered this semester, and why?

   My favorite part of the course was designing our first website using HTML, CSS, and JavaScript. Even though we didn’t use many advanced components or complex logic at that stage, I could apply what I had learned and felt a real sense of achievement when I saw the      website in the browser. It made the fundamentals feel meaningful and rewarding.
   As we progressed, it was also exciting to add more components and features using tools like React and ShadCN/UI. While those libraries are incredibly useful and powerful, I appreciated how everything we built connected back to the basics. Learning to structure a       site from scratch helped me understand how frameworks like React enhance, rather than replace, core web development skills.

7. What do you wish we had covered, or had covered in more detail, and why?

   I wish we had spent more time on React and Tailwind CSS. I understand that both tools build on the basic elements of HTML, CSS, and JavaScript, but I still feel there’s a gap in fully connecting those foundations to more advanced usage. Sometimes I found myself unsure how to structure components effectively or which Tailwind utilities to use, especially when trying to make more complex layouts or interactions.
   Having more guided practice or deeper walkthroughs would’ve helped me feel more confident using React and Tailwind together.






