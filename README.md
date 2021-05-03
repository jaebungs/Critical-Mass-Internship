# Critical-Mass-Internship
Portfolio: https://www.jaebungpark.com/  
LinkedIn: https://www.linkedin.com/in/jae-park-frontend/  
  
  
## Work / Project Examples  

### 1. Cocktail Recipe App - JavaScript, React, Redux, Material UI, MongoDB, Node.js
DEMO: https://mymycocktails.netlify.app/  
Github: https://github.com/jaebungs/MyMy-Cocktails  

#### Features
 - Random cocktail picker with auto-complete.
 - Authenticate user using OAuth or regular email, password login.
 - Bookmark feature for signed-in users using JWT.
 - Search and filter by cocktail name and/or alcohol types.
 - Utilized Redux for state management.

I love having glasses of cocktails or beers on Friday evening.  
I felt searching for a cocktail recipe is tedious, so I created a website that offers easy and fast house cocktail search.  
  
Some UIs are designed by my friend using Figma. https://www.figma.com/file/BCNyk9EYjxjQnfTda2gCsK/Cocktail-shaker?node-id=0%3A1  
I initially created pixel-perfect components as the design above but changed the size later on.  
All built from scratch except the Google OAuth and JWT part. I used youtube videos to implement those since I haven't used them before.  
However, I researched about those and I conceptually and practically feel comfortable about those. 


### 2. Masonry generator - JavaScript, React, SCSS, Firebase
DEMO: https://commongooods-1609187154790.web.app/  
Github: https://github.com/jaebungs/gallery-with-admin  

#### Features
 - Multiple image upload and delete.
 - Drag and Drop to change image order.

One of my friends wanted to have a masonry-style gallery page to display some of her pottery work.  
I did the initial design. The design changed as I was reflecting my friend's opinion/request.  
There are some differences between the DEMO and the final version, like colour, link and image lazy loading.  

It is the first project that I built from scratch.  
My initial trial for storing images was utilizing Shopify website(Not possible without an upgrade) -> Then, Google Drive(Not good) -> Lastly, Firebase(Love it).  
It was challenging but fun to learn how to use Firebase by reading the Firebase documents and Stack Overflow posts.  
Firebase is a great tool, especially for a prototype, because it provides many back-end services out of the box.

### 3. Cocktail Recipe App V2 (in progress) - Next.js, JavaScript or TypeSciprt, React, Redux, MongoDB, Node.js, SCSS or Tailwind
I am re-building the Cocktail App using Next.js and different tech stacks.  
The purpose of re-building this is to add more features to make a more complex app, implement good practices that I missed, and learn new techs.  
Currently, I finished basic CRUD on the back-end and small parts of UI.  

## Inspiration
### 1. What made me to use Next.js for the next project?
##### https://www.jame.es/gatsby-vs-next-js-2021/ & Next.js's documents.
I heard about Gatsby for the first time in 2020 FITC event presented by Wes Bos (Full Stack Developer in Hamilton). I did not fully grasp what he said about Gatsby at that time because I was pretty new to programming.  
As I know more about the web, the importance of SEO, SSG(static site generation) and SSR(server-side rendering), I decided to build an app using Next.js or Gatsby.   
  
I choose Next.js because of the following reasons:   
**_First,_** Next.js support both SSG and SSR. I believe this is very powerful and provides flexibility as well as scalability.  It made me think that Next.js will be a good thing to add under my tool belt.   
**_Second,_** Next.js image processing and auto-optimization. I heard from somewhere and looked up the document. When I was building an image-heavy website (Masonry gallery), it made me think about performance for an app with millions of images. I like that Next.js support lazy loading by default, do not increase build time contrary to SSG, and its simple syntax <Image /> with flexible configuration.   
**_Last,_** Next.js official documentation was the most easily comprehensive docs that I ever read. Particularly, I liked the data fetch doc. It explains well when to use and how to use 'getServerSideProps(SSR)' and 'getStaticProps(SSG)'. In general, it was easy to read.  

   
### 2. TypeScript will make my life easier in the future.
##### Podcast Syntax. Epsiode 346, and others (324, 327, 348). https://syntax.fm/show/346/selling-and-shipping-t-shirts-with-typescript   
This show reminded me of when I was accidentally passing a nested arrays instead of an array of objects as a prop in React.  
Syntax eppisodes gave me a clear idea about TypeScript along with a real world usage.  
I remember Wes(one of the hosts) said a T-shirt order object has lots of properties. And it would've been hard to track which property takes which type without TypeScript.  
These episodes are great to familiarize the basics and benefits of TypeScript with real-world use cases.  
I often listen devloper or economic related podcasts.

## Focus
#### If you were given the time and resources to build/learn anything you wanted during your internship, where would you choose to focus your efforts?  
I always wanted to build a well-designed real-world project that handles complex data using JavaScript, JavaScript framework(preferably React) and CSS. I would love to work on both the front and back-end. It would be great if I can join a project from the beginning to the end.
I would want to spend a day or two shadowing an experienced developer, read company documents/guidelines alongside. It would be helpful to identify the company's development methodology, design or coding guide and workflow between developers, designers and clients. Knowing those would help me to find things I can contribute to and create a first pull request.

After work, I will spend extra time practicing as I've been doing over the past months. My goal is to create values for the company, so I would try my best to acquire the skills that your company needs as soon as possible.

## Code Challenge
#### Please make sure to refresh the sandbox browser if nothing shows. I found that it does not load JS properly sometimes.
#### Link: https://codesandbox.io/s/2021-internship-tjypr
