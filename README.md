# moshify-website
A responsive website for a server company.

The website mock-up was already created, but I was able to analyze more about the layout by using Affinity Design. I plan on learning more about using this
and other Affinity products to build my own web mock-ups with more ease.

I learned how to write CSS with BEM in mind, working from the bottom up! I had some experience building from the top down, but this was made much more sense!
I felt I had greater control and had a better grasp of the idea of reusability of objects I created. I started by making components first, then building sections at a time, with a final
completion of the website by incorporating all of the sections. After this, I learned of the importance of testing each component and section individually (especially for
formatting and alignment errors) before putting it all together. Nonetheless, I was able to troubleshoot finding the error with Chrome Dev Tools. Afterwards, I incorporated css animations by including a script in the markup from Michal Snik (https://michalsnik.github.io/aos/) which made the website seem even more
polished.

Things I went over:
- color palette
- typography
- links
- badges
- lists
- icons
- buttons
- inputs/input groups
- cards/plans
- grouping objects/media objects
- absolute positioning of icons
- optimizing images (Cloud Convert for creating web-friendly images and ResponsiveBreakPoints.com for sizing)

Creating sections out of all the components!
- grid system
- testimonial section
- callout
- collapsibles
- blocks
- navigation bars
- hero section


After using Live Server on Visual Studio Code to successfully "test-out" my new website, I moved on to learning about search engine optimization (SEO) with the resource
ogp.me (Open Graph Protocol). I plan on learning more about this but what I implemented the most were meta tags in the head. Prior to building for production, I used validator.w3.org for validating my HTML
mark-up and jigsaw.w3.org for validating my CSS file.

Next, my work needed to be build for production using build tools to combine/minimize files and optimize images in order to reduce requests to the server (thereby improving efficiency/speed).
I initially used npm but transitioned to using yarn. I used Parcel in order to build my development project first to ensure things were still working smoothly, then I used progressed to building
the product-ready version. When doing this, the output files kept getting created into the root folder instead of the dist directory (which I had expected). I plan to explore this
at a later time in order to make my files look more neat and organized.

A GitHub repo was created and my project was pushed to the cloud. I then signed of for a free Netlify account to hose and deploy made website by joining it with my GitHub account. After configuring
all of the settings, I was able to view my webpage!

https://youthful-blackwell-015d85.netlify.app/

Lastly, I learned about measuring sit performace with web.dev measure to get an idea of how well the website is performing and what things I can do to improve the way people interact
with my website.

This was a great learning process; I used Code With Mosh (Mosh Hamedani) to learn about Web Development from start to end! Onward to my own website!
