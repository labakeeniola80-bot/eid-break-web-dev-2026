# Reflection Journal

## Class 01 - The 2026 Web Ecosystem

### THEORY

Question 1 - HTML & Browser Understanding
Understanding how the browser turns HTML into a webpage is important because it helps me know what happens behind the scenes when a website loads. The browser first reads the HTML file and creates a DOM Tree, which represents all the elements on the page. It then creates a Render Tree to determine what should be displayed. After that, the browser performs Layout, where it calculates the size and position of elements. Finally, it paints everything on the screen for the user to see.

As a web development student, understanding this process helps me know what is happening behind the scenes when a webpage loads. If a page is slow or something is not displaying properly, I can have a better idea of where the problem may be coming from. It also reminds me to write clean HTML and CSS so that websites can load faster and give users a better experience.

Question 2 - HTTP/3 and QUIC
HTTP/3 uses QUIC instead of TCP because it makes internet communication faster and more reliable. In the older system (TCP), when data is being sent to a website, if there is any small delay or lost packet, everything may have to wait before continuing, which slows down the experience.

QUIC improves this by allowing multiple streams of data to move at the same time without blocking each other. This means that if one part of the data has an issue, other parts can still continue loading. It also reduces connection delay when opening websites.

In 2026, this matters because most users depend on mobile internet, which is not always stable. QUIC helps websites load faster, reduces buffering when watching videos, and gives a smoother browsing experience even on weak networks. This improves user satisfaction and overall performance of modern web applications.

Question 3 - Website Analysis
One website that shows poor use of semantic HTML is some older designed blog or news websites that mainly use div elements instead of proper semantic tags like header, main, article, and footer.

From my experience, I notice that the page structure is not clearly organized. For example, headings are not properly arranged, and important content is mixed together without clear sections. This makes it harder to understand the layout of the page, especially for accessibility tools like screen readers.

Another clue is that buttons and links sometimes do not have clear labels or proper structure, which affects usability. This shows that the website is not built with semantic HTML in mind, and it can affect both accessibility and SEO performance.

### PRODUCT THINKING

Question 1 - Semantic HTML & SEO Thinking
Semantic HTML helps search engines like Google understand the structure and meaning of a webpage. When building a blog for a famous chef, using tags like <article>, <header>, <main>, and <aside> helps organize the content clearly.

The <header> tag shows the title and navigation of the blog, while <main> contains the most important content on the page. Each recipe or blog post can be placed inside an <article> tag so that search engines can understand that each one is a separate piece of content. The <aside> tag can be used for related posts, ads, or extra information that is not the main focus.

This structure helps search engines identify what is important on the page, which improves SEO and makes the content more likely to appear in search results. It also improves accessibility for users and screen readers, making the website easier to understand and use.

Question 2 - Edge Computing
Edge computing brings data processing closer to the user instead of relying on a distant central server. In a real-time multiplayer game, this is very important because it reduces delay (latency) between a player’s action and the game response.

The most important benefit is low latency, which makes actions like moving, jumping, or shooting respond instantly. It also improves smooth gameplay because players do not experience lag caused by long-distance communication with servers. Another benefit is better performance during high traffic since data is processed closer to users in different locations.

Overall, edge computing improves user experience by making multiplayer games faster, smoother, and more responsive, which is very important for competitive gaming.

### ENGINEERING BEST PRACTICE

Question 1 - Divs Everywhere
I partially disagree with the statement that using divs everywhere is fine because it may work visually, but it creates problems in structure and long-term development.

Using only div elements makes the HTML meaningless to browsers and assistive technologies. For accessibility, screen readers rely on semantic tags like header, main, article, and button to understand the structure of a page. Without them, users with disabilities may have a poor experience.

From an SEO perspective, search engines depend on semantic HTML to understand what content is important. If everything is wrapped in divs, it becomes harder for search engines to properly rank the page.

It also affects code maintainability because when the project becomes large, it becomes difficult to understand the purpose of each section. Developers working in teams will struggle to read and update the code.

Using semantic HTML improves clarity, accessibility, SEO, and teamwork, which makes it a better practice than using divs everywhere.


## Class 02 - Typography & Information Hierarchy

### THEORY

Question 1 - Difference between <em> and <i>
The difference between <em> and <i> is that <em> is used to show emphasis or importance in a sentence, while <i> is only used for styling text in italics without changing its meaning.

For example, I use <em> when I want to stress a word in a sentence like “I really need to understand JavaScript,” where “really” is emphasized to show importance. On the other hand, <i> can be used for words like foreign terms or book titles where the meaning of the sentence does not change, but the text is styled differently.

The main difference is that <em> affects meaning and is important for accessibility tools like screen readers, while <i> is only for visual styling.

Question 2 - Screen Reader Behaviour
Screen readers treat certain HTML elements specially because they provide meaning and structure to a webpage, which helps users who cannot see the screen understand the content better.

One example is heading elements (<h1> to <h6>). Screen readers announce them as headings so users can understand the structure of the page and quickly move between sections.

Another example is the <button> element. Screen readers announce it as a button so users know it is clickable and can perform an action.

The <nav> element is also important because it represents navigation sections of a website. Screen readers announce it as a navigation region, allowing users to easily jump to menus and links.

These behaviors exist because browsers are designed to improve accessibility and help users interact with websites more effectively.

Question 3 - ARIA Labels
ARIA labels are used to improve accessibility when there is no visible text for screen readers to understand an element. However, they should not replace proper semantic HTML.

An example of when to use aria-label is on icon-only buttons, such as a search icon or a close button. In this case, the icon does not contain readable text, so an aria-label like "Search button" or "Close menu" helps screen reader users understand its purpose.

On the other hand, if the problem is caused by incorrect HTML structure, such as using div elements instead of proper button or heading tags, the correct solution is to fix the HTML rather than relying on aria-label. Semantic HTML should always be the first choice because it provides meaning to both browsers and assistive technologies.

Therefore, aria-label is a helpful tool but should only be used as a supplement, not a replacement for proper HTML structure.

### ACCESSIBILITY REFLECTION
 
Question 1 - Accessibility Testing
I tested the accessibility of a public website and checked how it behaves when using only the keyboard.

When I used the Tab key to navigate through the page, I noticed that some parts of the website were reachable, but the focus movement was not always smooth or clearly visible. In some cases, it was difficult to know which element was currently selected because the focus indicator was not strong enough.

I also checked form elements and noticed that some input fields did not have clearly visible labels, which could make it difficult for users to understand what information is required.

Overall, the website has basic accessibility support, but it still needs improvement in areas such as focus visibility, proper labeling of form elements, and smoother keyboard navigation to make it more user-friendly for all users.

### PRODUCT THINKING

Question 1 - API Documentation Structure
When designing a technical documentation page for an API, I would structure the information in a clear hierarchy so that developers can easily scan and find what they need.

The <h1> tag would be used for the main title of the documentation, such as the API name. This gives users an immediate understanding of what the page is about.

The <h2> tags would be used for main sections like Authentication, Endpoints, Error Handling, and Getting Started. These sections help organize the documentation into clear parts.

The <h3> tags would be used for more detailed information under each section, such as specific endpoint descriptions, request examples, response formats, and parameter explanations.

This structure improves readability, makes the documentation easier to navigate, and helps developers quickly find the exact information they need without confusion.


## Class 03 - Modern Assets & Linking

### THEORY
 
Question 1 - Image Optimization
To optimize a 5 MB PNG image for a production website, I would follow several steps to reduce its size while maintaining good quality.

First, I would convert the image from PNG to modern formats like WebP or AVIF because they provide better compression and smaller file sizes without losing much quality.

Second, I would compress the image using tools like TinyPNG or Squoosh to further reduce the file size while maintaining acceptable visual quality.

Third, I would resize the image to match the actual display size needed on the website instead of using a large unnecessary resolution.

Finally, I would use responsive image techniques to serve different image sizes for different devices, ensuring that mobile users download smaller files while desktop users receive higher quality images.

These steps improve website loading speed, reduce data usage, and enhance overall user experience.

Question 2 - srcset
The srcset attribute allows a browser to choose the most appropriate image size for a user's device. Instead of sending the same image to everyone, different image versions can be provided for different screen sizes and resolutions.

I would use srcset when a website needs to display images on multiple devices such as phones, tablets, and desktop computers. This helps improve performance and reduce unnecessary data usage.

For example, an online store may have a product image available in large, medium, and small sizes. Without srcset, a mobile user might download a very large desktop image even though their screen is small. This would make the page load more slowly and use more mobile data.

By using srcset, the browser can automatically select the smaller image for mobile users and the larger image for desktop users. This improves loading speed, saves bandwidth, and creates a better user experience.

Question 3 - Security and External Links
When a link uses target="_blank", it opens a new browser tab. Without rel="noopener", the new tab may be able to access and interact with the original page that opened it.

This can create a security risk because a malicious website could potentially redirect the original page to a fake website or perform unwanted actions. This type of attack is sometimes called tabnabbing.

Using rel="noopener" prevents the newly opened page from accessing the original page. It creates a safer separation between the two tabs.

In simple terms, it is like allowing a visitor into a separate room without giving them access to the rest of your house. This helps protect users from certain security threats and is considered a best practice when using target="_blank".

### ENGINEERING THINKING

Question 1 - Product Image Optimization Strategy
If I needed to display 50 product images on a webpage, I would focus on performance and user experience.

First, I would use lazy loading so that images only load when users scroll close to them. This reduces the amount of data downloaded when the page first opens and improves loading speed.

Second, I would use modern image formats such as WebP or AVIF because they provide good quality while keeping file sizes small.

Third, I would use a Content Delivery Network (CDN) to serve images from locations closer to users. This helps reduce loading time and improves performance for visitors in different regions.

Finally, I would use responsive image techniques so that mobile users receive smaller images while desktop users receive larger versions when needed.

Combining these strategies would help the page load faster, reduce bandwidth usage, and provide a smoother experience for users.


## Class 04 - Modern Forms & User Experience

### THEORY

Question 1 - Client-Side vs Server-Side Validation
When a user enters an invalid email address, client-side validation checks the input before the form is submitted. The browser immediately displays an error message and allows the user to correct the mistake without sending data to the server. This creates a faster and more user-friendly experience.

With server-side validation, the form is submitted first, and the server checks whether the email is valid. If the email is incorrect, the server rejects the submission and returns an error message. Although this process is slower, it provides stronger security because server-side checks cannot be bypassed easily.

Both validation methods are important. Client-side validation improves user experience by providing instant feedback, while server-side validation protects the application from invalid or malicious data. Using both together creates a secure and reliable form experience.

Question 2 - The Autocomplete Attribute

The autocomplete attribute helps browsers remember and automatically fill information that users have entered before. This makes forms easier and faster to complete.

Some common autocomplete values are:

1. Name – used for a person's full name.
2. Email – used for an email address.
3. Tel – used for a phone number.
4. Street-Address – used for a home or delivery address.
5. New-Password – used when a user is creating a new password.

Using autocomplete improves user experience because it reduces typing, saves time, and helps users avoid mistakes when filling out forms.

### PRODUCT THINKING

Question 1 - Multi-Step Job Application Form

If I am building a multi-step job application form, I will make sure the user's progress is saved after every step. If the internet goes off at step 4, the user should not lose all the information already entered.

I will save the data temporarily so that when the internet comes back, the user can continue from where they stopped. I will also show a clear message telling the user that there is a network problem instead of making them think the website is broken.

I will validate each step before moving to the next one so that mistakes can be corrected early. This will make the form easier to use and reduce frustration for users.

Question 2 - Native Select vs Custom Dropdown

I would use a native select element when I need a simple and reliable dropdown. It is easier to build, works well on mobile devices, and has good accessibility support for screen readers and keyboard users.

I would use a custom dropdown when the design needs extra features like icons, search, or a special appearance that the normal select element cannot provide.

However, custom dropdowns take more time to develop and test. They can also create accessibility problems if they are not built properly.

For most simple forms, I think the native select element is the better choice because it is easier to maintain and provides a better user experience.

### ENGINEERING BEST PRACTICE

Question 1 - Accessible Password Input

A good password input should help users create a strong password without making the process difficult. I would add a strength meter that shows whether the password is weak, medium, or strong as the user types.

I would also display a checklist showing the requirements, such as having at least 8 characters, one uppercase letter, one number, and one special symbol. As each requirement is met, the user can easily see their progress.

There should be a show and hide password button so users can check what they have typed. This button should work with both the keyboard and screen readers.

I would also use clear labels and error messages so that all users, including people using assistive technology, can understand and complete the form easily.


## Class 05 - The CSS Engine — Box Model & Specificity

### THEORY

Question 1 - CSS Box Model and Margin Collapse

The CSS box model is made up of four parts: content, padding, border, and margin. The content is the main information inside the element. Padding creates space around the content, the border surrounds the padding, and the margin creates space between one element and another.

If one div has a margin-bottom of 20px and another div below it has a margin-top of 30px, the space between them will be 30px, not 50px. This happens because of margin collapsing, where the browser uses the larger of the two margins instead of adding them together.

Question 2 - CSS Specificity

CSS specificity is the system the browser uses to decide which style should be applied when more than one rule targets the same element. Different selectors have different weights.

For the given selectors:

.header nav ul li a = 14
nav a.active = 12
.nav-links a = 11

The selector .header nav ul li a has the highest specificity score, so its style will be applied. Understanding specificity helps developers avoid confusion and reduces the need to write unnecessary CSS rules.

Question 3 - The CSS Cascade

The CSS cascade is the process the browser uses to decide which style should be applied when multiple CSS rules affect the same element. It considers things like specificity and the order in which the rules are written.

For example, if I accidentally write two different colours for the same paragraph, understanding the cascade helps me know why one colour is being used instead of the other. This can save me from writing extra CSS because I can simply find and correct the rule that is already overriding the others.

Understanding the cascade makes debugging easier and helps keep CSS code cleaner and more organized.

### ENGINEERING THINKING

Question 1 - Padding and Box-Sizing

When I add padding to an element, it can become wider than expected because the browser adds the padding to the original width of the element. This is the default behaviour when using the content-box model.

For example, if an element has a width of 100px and I add 10px padding on both sides, the total width becomes 120px.

A simple solution is to use box-sizing: border-box;. This makes the browser include the padding and border inside the specified width, so the overall size of the element does not increase unexpectedly.

Using box-sizing: border-box; helps make layouts easier to manage and prevents sizing problems.

Question 2 - Content-Box vs Border-Box

To show the difference between content-box and border-box, I would create two boxes with the same width and add the same amount of padding and border to both.

The first box would use content-box, where the padding and border increase the total size of the element.

The second box would use border-box, where the padding and border are included inside the specified width.

This simple comparison makes it easy to see why many developers prefer border-box for building layouts because it gives more predictable sizing.


## Class 06 - Flexbox Mastery

### THEORY

Question 1 - Flex Properties (Grow, Shrink, Basis)

Flex-basis is the initial size of an element before any extra space is distributed. It is like the starting point.

Flex-grow controls how much an element can expand when there is extra space available. Elements with higher flex-grow values take more space.

Flex-shrink controls how much an element reduces when there is not enough space. Elements with higher flex-shrink values reduce faster than others.

A simple analogy is sharing a pizza. Flex-basis is the initial slice each person gets, flex-grow is how extra pizza is shared, and flex-shrink is how slices reduce when the pizza is not enough.

Question 2 - When align-items: stretch does not work

align-items: stretch does not always work as expected when the child elements already have a fixed height or size. In that case, the browser will not stretch them because the size has already been defined.

For example, if a flex container has a fixed height and the child elements also have their own height set, the stretching effect will not be visible. This is because the fixed height overrides the stretching behavior.

Also, when elements contain large content like images or long text, the stretching effect may not be noticeable because the content controls the size.

Understanding this helps in debugging layout problems when working with Flexbox.

### ENGINEERING THINKING

Question 1 - Flexbox Navigation Bar Layout

To create a navigation bar with a logo on the left, menu items in the center, and a sign-in button on the right, I would use Flexbox.

The main container would use display: flex and justify-content: space-between to separate the left, center, and right sections.

The logo stays on the left side, the sign-in button stays on the right side, and the navigation links are placed inside a separate center container. This center container is also styled with flexbox to keep the items in a row.

This structure ensures that the center navigation remains properly centered on the page even if the logo or button size changes.

Using Flexbox in this way makes the layout flexible, responsive, and easy to maintain.

Question 2 - Instagram Header Layout (Flexbox)

To recreate the Instagram header, I would use Flexbox to arrange the items in a single horizontal row.

The layout would be divided into three parts: the logo on the left, the navigation icons in the center, and the profile or extra actions on the right.

On larger screens, all navigation items such as Home, Search, Explore, Reels, Messages, Notifications, Create, and Profile would be visible. Flexbox helps align them properly in a row and keep spacing consistent.

On smaller screens, I would hide the full navigation menu and replace it with a hamburger icon to improve mobile usability. This makes the design responsive and prevents overcrowding on small devices.

Using Flexbox makes it easy to align items, distribute space, and adjust the layout for different screen sizes.


## Class 07 - CSS Grid & Layout Complexity

### THEORY

Question 1 - When to use CSS Grid over Flexbox

CSS Grid is better than Flexbox when building full page layouts that require both rows and columns. Flexbox works in one direction, but Grid allows control in both directions at the same time.

I would choose CSS Grid in situations like creating a full website layout with header, sidebar, main content, and footer because it makes it easy to organize the page structure.

It is also useful for dashboard designs where different sections like charts, cards, and panels need to be arranged neatly in rows and columns.

Another example is image galleries or magazine-style layouts where items have different sizes and need flexible positioning.

Overall, CSS Grid is best for complex layouts, while Flexbox is better for simple one-direction layouts.

Question 2 - grid-template-areas

grid-template-areas is a CSS Grid feature that allows you to create layouts using named sections instead of positioning elements with numbers. It makes the layout easier to read and understand because you can visually design the structure like a map.

For example, instead of calculating columns and rows using grid lines, I can simply define areas like header, sidebar, main content, and footer.

This method is more readable and easier to maintain, especially for complex layouts. It makes it clear where each part of the page belongs.

I would use grid-template-areas when building full page layouts because it improves clarity compared to using only grid-template-columns.


### ENGINEERING THINKING

Question 1 - Magazine Layout using CSS Grid

To build a magazine layout, I would first sketch the structure using a simple design. The hero article would take the full width at the top. Below it, two secondary articles would be placed side by side. After that, there would be one wide article spanning the full width, and finally three small articles arranged in a row.

I would use CSS Grid to create this layout because it makes it easy to control rows and columns at the same time.

The fr unit is useful because it divides available space into flexible parts. For example, 1fr means one fraction of the space, and it helps create responsive layouts without using fixed sizes.

Compared to percentages and auto, fr is more flexible because it automatically adjusts based on available space.

Question 2 - Responsive Dashboard Layout

For a responsive dashboard, I would use CSS Grid to arrange the sidebar, main content, and right panel. On large screens, all three sections would be visible side by side.

On smaller screens, the layout would automatically adjust by reducing the sidebar or moving sections to fit the available space. This creates a better experience for mobile users.

Using features like minmax() allows each section to have a minimum and maximum size, while auto-fit helps the layout automatically adjust based on the screen size.

I like this approach because it creates a flexible layout without needing many media queries, making the code easier to maintain.


## Class 08 - Tailwind CSS Fundamentals

### THEORY

Question 1 - Utility-first philosophy

Utility-first means using small, single-purpose classes directly in HTML instead of writing separate CSS classes for every component. In Tailwind, styles are applied using utility classes like padding, margin, colors, and text size directly in the HTML.

The creator of Tailwind chose this approach because it makes development faster and reduces the need to constantly switch between HTML and CSS files. It also removes the problem of naming classes and helps maintain consistency in design.

Although it can make HTML look crowded, it improves speed of development and reduces custom CSS complexity.

Question 2 - Tailwind JIT Compiler

The Just-In-Time (JIT) compiler in Tailwind generates CSS only when it is needed. Instead of loading a large file with many unused styles, it creates styles based on the classes used in the project.

This reduces the final CSS file size in production because only the required utilities are included. For example, if I use a class like bg-red-500, Tailwind generates only that style instead of including all possible color classes.

This improves website performance, reduces load time, and makes the project more efficient.

### PRODUCT THINKING

Question 1 - Response to Tailwind “ugly HTML” complaint

If a teammate says Tailwind makes HTML look ugly, I would explain that the goal is not visual beauty in the code but productivity and consistency.

Even though the HTML looks longer, it becomes easier to understand what styles are applied without switching between HTML and CSS files. This improves readability during development.

It also improves maintainability because everything is in one place, making it easier to update styles quickly.

Tailwind also ensures design consistency by using a fixed system of spacing, colors, and sizes, so the entire project stays uniform.

Finally, it improves performance because it reduces unnecessary custom CSS and produces optimized output in production.

### ENGINEERING THINKING

Question 1 - Tailwind Card Component

To build a card component in Tailwind, I would create a simple box that displays content like an image, title, and description.

In the default state, the card has normal padding, border, and background color.

On hover, I would add a slight upward movement and increase the shadow to make it feel interactive and responsive.

For a featured card, I would make it slightly larger and add a different border color to highlight its importance compared to other cards.

This approach helps improve user experience by making important items stand out and making the interface more interactive.


## Class 09 - Advanced Tailwind & Responsive Design

### THEORY

Question 1 - Tailwind Breakpoints System

Tailwind uses a breakpoint system to apply different styles depending on screen size. This helps make websites responsive across mobile, tablet, and desktop devices.

The md: prefix means that the style will only apply when the screen size reaches the medium breakpoint and above. For smaller screens, the style will not apply.

To create a custom breakpoint, I would define a new screen size in the Tailwind configuration file. For example, I can set a custom breakpoint for 1200px and give it a name like xl2. After that, I can use it in my classes like xl2:text-xl.

This system makes responsive design easier and more flexible.

Question 2 - Arbitrary values in Tailwind

Arbitrary values in Tailwind are used when we need a custom value that is not available in the default utility classes. For example, w-[123px] allows me to set a specific width that is not included in the standard spacing scale.

I would use arbitrary values when I need a quick one-time custom style that is not reused often. However, if a value is used multiple times in a project, it is better to add it to the Tailwind configuration file to keep the design consistent.

This approach gives flexibility while still allowing good structure and maintainability in the project.

### ENGINEERING BEST PRACTICE

Question 1 - Dark mode and design system in Tailwind

To support both light and dark themes in a design system, Tailwind provides a dark mode feature using the dark: prefix. This allows different styles to be applied depending on the selected theme.

For example, I can set a default background color for light mode and then define a different background color for dark mode using dark:bg-black. This makes it easy to switch themes without writing separate CSS files.

To keep CSS output minimal, I would reuse consistent design tokens such as primary colors, background colors, and text colors throughout the project instead of creating random styles. This ensures consistency across the entire design system.

Using Tailwind dark mode helps create a flexible and maintainable interface that supports both light and dark themes efficiently.

Question 2 - Responsive Landing Page using Tailwind

To build a responsive landing page, I would divide the page into four main sections: hero section, features section, pricing section, and footer.

The hero section contains the main heading and a call-to-action button. It is designed to grab the user's attention first.

The features section displays three columns describing the product. On smaller screens, the layout becomes a single column, while on larger screens it becomes multiple columns using Tailwind breakpoints.

The pricing section shows three pricing plans, which are stacked on mobile devices and displayed in a row on larger screens.

The footer contains basic information and links.

I would use Tailwind breakpoints like sm, md, and lg to control how the layout changes across different screen sizes. This ensures the website is fully responsive and works well on all devices.


## Class 10 - Memory & Variables

### THEORY

Question 1 - let, const, and var

var, let, and const are used to declare variables in JavaScript but they behave differently.

var has function scope and can be redeclared and updated. It is also hoisted which can lead to unexpected behavior, so it is rarely used in modern JavaScript.

let has block scope and can be updated but cannot be redeclared in the same scope. It is safer and more commonly used.

const also has block scope but cannot be reassigned after declaration. However, if it is an object or array, its internal values can still be modified because only the reference is constant, not the content.

Hoisting means variables are moved to the top of their scope during execution. var becomes undefined when hoisted, while let and const cannot be accessed before initialization due to the temporal dead zone.

Question 2 - Temporal Dead Zone (TDZ)

The Temporal Dead Zone is the time between when a variable is created and when it is actually declared in the code. During this time, variables declared with let and const cannot be accessed.

For example, if I try to use a variable before declaring it, JavaScript will show an error instead of returning undefined. This helps prevent hidden bugs in the code.

The TDZ exists to make JavaScript safer by forcing developers to declare variables before using them.

Question 3 - Memory Heap vs Stack

In JavaScript, memory is divided into stack and heap.

The stack stores simple data types like numbers and strings. It works in a last-in-first-out order and is very fast.

The heap stores complex data types like objects and arrays. These are stored in a larger memory space and accessed through references.

In the given code, variables like name and age are stored in the stack. The scores array is stored in the heap, while the stack only holds a reference to it.

When the function greet is called, it is added to the stack, and after execution, the result is also stored in the stack.

Understanding stack and heap helps in knowing how JavaScript manages memory efficiently.

### PRODUCT THINKING

Question 1 - Calculator App (const vs let decision)

In a calculator application, most values need to change as the user interacts with it. Therefore, let is more suitable for most cases.

The display value should use let because it changes whenever the user types a new number or performs a calculation.

The operator should also use let because the user can choose different operations like addition, subtraction, multiplication, or division before calculating.

The previous operand should use let because it updates every time a new calculation is performed.

const is only suitable for values that do not change, but in a calculator most values are dynamic.


## Class 11 - Control Flow & Comparison

### THEORY

Question 1 - == vs ===

== is a loose comparison operator that compares values after converting them to the same type. This can sometimes lead to unexpected results.

=== is a strict comparison operator that compares both value and data type without conversion. It is safer and more reliable.

Using == can cause bugs because JavaScript may convert values automatically. For example, 0 == false returns true even though they are different types. This can lead to wrong logic in programs.

Because of this, === is preferred in most cases to avoid hidden errors.

Question 2 - Optional Chaining (?.)

Optional chaining is a feature in JavaScript that allows us to safely access deeply nested object properties without causing an error if a property does not exist.

It works by stopping the code execution at the point where a value is undefined and returning undefined instead of crashing the program.

For example, user?.profile?.name will not throw an error even if profile does not exist inside user.

However, overusing optional chaining can hide real bugs in the code. If a value is expected to always exist but optional chaining is used, it may mask a problem instead of fixing it.

Question 3 - Nullish Coalescing (??) vs OR (||)

The nullish coalescing operator (??) is used to return the right-hand value only when the left-hand value is null or undefined.

The OR operator (||) returns the right-hand value when the left-hand value is any falsy value such as 0, empty string, false, null, or undefined.

The main difference is that || can incorrectly replace valid values like 0 or empty string, while ?? only replaces null or undefined.

For example, if a score is 0, using || would incorrectly replace it with a default value, but ?? would correctly keep the value 0. 

### ENGINEERING THINKING

Question 1 - User Input Validation

When validating user input, I would first check that the name field is not empty because it is required.

For age, I would use typeof to make sure the value is a number and also check that it is between 18 and 99.

For email, I would verify that it follows a valid email format before accepting it.

The preferences object is optional, so I would use optional chaining to safely access nested properties without causing errors if they do not exist. I would also use nullish coalescing to provide default values when necessary.

By handling each case carefully, the application can avoid crashes and provide clear feedback to the user.

Question 2 - Grade Calculator

A grade calculator should collect multiple test scores and calculate the final average based on their assigned weights.

After calculating the result, the system can use logical and conditional operators to determine whether the student passed or failed.

It should also assign a letter grade based on the final score. For example, scores of 90 and above can receive an A, while lower scores receive other grades according to the grading system.

If the average score is 90 or above, the student can also qualify for distinction.

The calculator should handle unusual cases properly, such as missing scores or invalid values, to ensure accurate results.


## Class 12 - Functions & Functional Programming

### THEORY

Question 1 - Function Declaration and Function Expression

A function declaration is a function that is defined using the function keyword directly. It is hoisted, which means it can be called before it appears in the code.

A function expression is a function that is assigned to a variable. It cannot be used before the variable is declared because it depends on the variable declaration.

The difference in hoisting helps developers understand why some functions work before they are written while others produce errors.

Question 2 - Pure Functions

A pure function is a function that always returns the same output when given the same input. It does not depend on or change any external data.

Developers value pure functions because they are easier to understand, test, and debug. Since they behave predictably, they reduce the chances of unexpected errors.

An example of a function that is not pure is one that changes a global variable or depends on information outside the function. Such a function may produce different results even when the input stays the same.

Using pure functions helps make code more reliable and easier to maintain.

Question 3 - Callbacks and Higher-Order Functions

A callback is a function that is passed into another function and is executed after a particular task is completed. It allows different parts of a program to work together.

A higher-order function is a function that accepts another function as an argument or returns a function as a result. This makes code more flexible and reusable.

Callbacks and higher-order functions are fundamental to JavaScript because they are widely used in event handling, array methods, and asynchronous programming. They help developers write cleaner and more organized code.


### PRODUCT THINKING

Question 1 - Math Utility Library

If I am building a calculator app, I would create several pure functions to handle different calculations.

Addition: takes two numbers and returns their sum.
Subtraction: takes two numbers and returns the difference.
Multiplication: takes two numbers and returns the product.
Division: takes two numbers and returns the result of dividing one by the other.
Square Root: takes one number and returns its square root.

These functions are pure because they always produce the same output for the same input and do not change external data.

Making them pure makes the code easier to test, debug, and maintain because their behavior is predictable.

### ENGINEERING THINKING

Question 1 - Compose Function and Reduce

A compose function combines multiple functions so that the output of one function becomes the input of the next one. This allows several operations to be performed in an organized sequence.

The idea behind compose(f, g, h)(x) is that the value first passes through one function, then the next, until the final result is produced.

Instead of using a loop to apply each function one after another, reduce() can also be used to combine the functions into a single process. This can make the code cleaner and easier to manage.

Learning about compose functions and reduce() helped me understand how JavaScript can solve problems using smaller reusable functions.


## Class 13 - Data Structures — Arrays & Objects

### THEORY

Question 1 - Arrays and Objects

I would use an array when I need to store a list of related items. Arrays are useful when the order of the data is important and I want to work with multiple values together.

I would use an object when I need to store detailed information about a single item using properties and values.

For example, a list of product names can be stored in an array, while information about one product such as its name, price, and category is better stored in an object.

Objects make it easier to organize and access related information, while arrays are better for collections of data.

Question 2 - Destructuring with Nested Objects

Destructuring is a JavaScript feature that allows developers to extract values from objects and arrays more easily.

When working with nested objects, it helps access deeply stored information without writing long chains of property names repeatedly.

For example, an API response may contain user information, profile details, and address data inside one another. Destructuring allows me to pick only the values I need, such as the user's name or city, in a simpler way.

Using destructuring makes the code cleaner, easier to read, and easier to maintain.

### ENGINEERING THINKING

Question 1 - Array Data Operations

To work with the orders data, I used array methods like filter, reduce, and map to manipulate and organize the information.

To find all orders by Alice, I filtered the array based on the customer name. To calculate her total spending, I first filtered her orders and then used reduce to sum up the total values.

To get unique food items, I combined all items using flatMap and then removed duplicates using a Set.

To group orders by status, I used reduce to organize the orders into categories such as delivered and pending.

These array methods make it easier to handle and process structured data in JavaScript.

Question 2 - Product Search and Filter Feature

To build a product search and filter system, I would use an array of products and apply different array methods to manipulate the data.

For searching by name, I would use filter() and convert both the product name and search input to lowercase to make it case-insensitive.

To filter by price range, I would check if the product price is within the minimum and maximum values provided by the user.

To filter by category, I would use filter() again to return only products that match the selected category.

To sort products by price, I would use the sort() method in either ascending or descending order depending on user preference.

Finally, I would combine all filters together so that users can search, filter, and sort at the same time for better user experience.


## Class 14 - DOM Manipulation & Events

### THEORY

Question 1 - Event Bubbling vs Capturing

Event bubbling and event capturing describe the direction in which an event is handled in the DOM.

In event bubbling, the event starts from the target element and moves upward to its parent elements. This is the most commonly used method in web development.

In event capturing, the event starts from the top parent element and moves down to the target element. It is less commonly used but can be useful in specific cases where early event handling is needed.

Understanding both helps in controlling how events behave in a webpage.

Question 2 - Event Delegation

Event delegation is a technique in JavaScript where a single event listener is added to a parent element instead of adding multiple listeners to each child element.

This works because events bubble up from child elements to their parent, allowing the parent to detect which child was clicked.

Event delegation is better than attaching listeners to each child because it improves performance and reduces memory usage, especially when dealing with many elements or dynamically added items.

For example, in a todo list, instead of adding a click event to each todo item, I would add one event listener to the parent list and detect which item was clicked.

Question 3 - innerHTML vs createElement

Using innerHTML allows HTML content to be inserted directly into a webpage. However, it can be dangerous because it may allow malicious code injection if the input is not trusted. This is known as a security risk called XSS (Cross-Site Scripting).

On the other hand, createElement and textContent are safer because they build elements step by step and treat content as plain text instead of executable code.

Because of this, createElement is preferred when working with user input to avoid security issues and make the application safer.

### ENGINEERING THINKING

Question 1 - Todo List Application

To build a todo list, I would create an input field and an add button for users to enter tasks. The tasks would then be displayed in a list format on the page.

Each todo item would have options to edit or delete it. To ensure data persistence, I would store the todos in localStorage so that the data remains available even after refreshing the page.

I would also handle empty inputs by preventing users from adding blank tasks. To avoid security risks such as XSS, I would avoid using innerHTML for user input and instead use safer methods like textContent.

Additionally, I would limit very long text entries to prevent layout issues and ensure a good user experience.

### PRODUCT THINKING

Question 1 - Real-time Collaboration Todo App

In a real-time todo application, the DOM must update instantly when users add, edit, or delete tasks so that all users see the same data at the same time.

When multiple users are working together, conflicts can happen. For example, one user may delete a task while another user is still editing it.

To handle this, I would consider solutions such as locking the item while it is being edited, using a last-write-wins strategy where the most recent update is accepted, or showing a warning message when an item has been removed while another user is editing it.

These approaches help ensure that the user interface remains consistent and prevents confusing behavior.


## Class 15 - Personal Dashboard Project

### PERSONAL REFLECTION

Question 1 - Personal Reflection

The hardest part of the personal dashboard project was understanding how to combine different features like localStorage, DOM manipulation, and event handling together in one project.

I learned that debugging is not about guessing, but about checking step by step. I realized that using console.log helps me understand where the problem is coming from instead of feeling confused.

I also learned that small mistakes like wrong variable names or missing brackets can break the whole project, so I need to check my code carefully.

Question 2 - How I Got Unstuck

When I got stuck during the project, I tried different ways to solve the problem step by step.

Sometimes I used Google to search for similar problems and see how other developers solved them. Other times, I checked documentation to better understand how certain functions or methods work.

I also watched tutorials again when I did not fully understand something. Breaking the problem into smaller parts helped me understand it better instead of trying to solve everything at once.

What worked best for me was testing small parts of the code at a time and using console.log to see what was happening.

Question 3 - Code Organisation and Improvements

My code organisation was average because I was still learning how to structure a full project properly. Some parts of my code were grouped well, but other parts were not clearly separated.

If I started over, I would organise my code better by separating different features into smaller sections and keeping my functions more structured.

I would also make my variable names clearer so that anyone reading my code can understand it easily. In addition, I would test my code more frequently while building instead of writing too much before testing.

This would help me reduce errors and improve the overall quality of my project.

Question 4 - localStorage Usage

I used localStorage to save user data such as tasks in the dashboard so that the data remains available even after refreshing the page.

I chose localStorage because it is simple to use and does not require a backend server. It allows data to persist directly in the browser.

Another alternative could have been using a backend database, but that would require more advanced setup and server-side knowledge.

Using localStorage was suitable for this project because it helped me understand how data persistence works in frontend development.

### ENGINEERING BEST PRACTICE

Question 1 - Engineering Best Practice

3 Things I Did Well

I was able to build a working dashboard with basic functionality like adding and removing tasks.
I used localStorage to make sure data does not disappear after refreshing the page.
I tried to organize my code into different parts instead of writing everything in one place.

3 Things I Would Improve

I would improve my code structure by separating functions more clearly for better readability.
I would use more meaningful variable names to make my code easier to understand
I would test my code more frequently while building to reduce errors early.

Peer Review

If I review a classmate’s project, I would check:

Structure: Is the code well organized?
Readability: Can I understand the code easily?
Error handling: Does it handle wrong inputs or unexpected actions?
Improvement: I would suggest breaking large functions into smaller ones and improving naming clarity.

## Class 16 - The Event Loop & Promises

## Class 17 - Async/Await & Fetch API

## Class 18 - Intermediate Project — Movie Finder

## Code-Portfolio

## Self-Assessment

Before this break, I knew:
 HTML basics
 CSS basics
 very little JavaScript

During this break, I learned:
 JavaScript fundamentals
 DOM and events basics
 array methods and functions

I'm still confused about:
 advanced JavaScript logic
 building full projects alone

My growth areas:
 JavaScript practice
 problem solving
 project building

One thing I'll do differently in the next project:
 practice more daily instead of rushing before deadline

