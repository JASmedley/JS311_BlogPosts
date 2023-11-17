# JS311_BlogPosts
<h2>Class 6: November 9</h2>
<b>1. If a user attempts to create a resource that already exists—for example, an email address that’s already registered—what HTTP status code would you return?</b>
<p>403 - Already Exists</p>
<b>2. Consider a responsive site design that requires a full-width image in all responsive states. What would be the correct way to code this to ensure the page loads the smallest image required to fill the space?</b>
<p> Use a media query, apply it to the image as a background-image property. So you have an element, and instead of using an <code><img></code> element, the image is the background-image to that element.</p>
<b>3. When should you npm and when should you yarn?</b>
<p>You should use npm when you are running a node app, and yarn if you are knitting (or crocheting) a sweater, socks, a hat, etc.</p>
<b>4. How can you make sure your dependencies are safe?</b>
<p>By storing them in a databse and then pulling that database's access information into a .env file that is then stored in a gitignore so that even if the app is updated, the information for accessing the database is in a password protected database. Also just generally having good usernames and passwords. Also not making your database IPs public.</p>
<b>5. What are the differences between <code>CHAR</code> and <code>VARCHAR</code> data types (MySQL)?</b>
<p><code>CHAR</code> is a fixed-length character data type, so you need specify a length for the data. <code>VARCHAR</code>VARCHAR stands for variable character. It is a variable-length character data type, so it can store strings of varying lengths.</p>
<b>6.How else can the JavaScript code below be written using Node.Js to produce the same output?</b>
<code>  
    console.log("first");
    setTimeout(function() {
        console.log("second");
    }, 0);
    console.log("third");

    // Output:

    // first
    // third
    // second
</code>
<p>You can write 
<code>
    console.log("first");

setImmediate(function() {
    console.log("second");
});

console.log("third");
</code></p>

<h2>Class 4: November 2</h2>
<b>1.What do you find challenging about coding?</b>
<p>JavaScript, I think mostly understanding the syntax and how things relate to each other depending on their placement in the code. </p>
<b>2.Talk about a project that disappointed you. What would you change?</b>
<p>I don't love my current portfolio website, I was trying to add a radial progress bar (much like a timer) to my about page but it required more JavaScript than I knew how to do at the time. I think I'd like to go back some time and see if I can't do it now that I have improved JavaScript skills.</p>
<b>3.List three key things to consider when coding with SEO in mind.</b>
<p>Assuming you mean SEO as in Search Engine Optimization,
    <ol>
        <li>Having a schema markup in the HTML is important for indexing.</li>
        <li>Don't put body elements in the <code><head></code> section, because search engines will try and index that.</li>
        <li>Ensure image elements have [alt] attributes.</li>
    </ol>
    </p>
<b>4.List five or more ways you could optimize a website to be as efficient and scalable as possible.</b>
<ol>
    <li>Leverage the font-display CSS feature to ensure text is user-visible while webfonts are loading. </li>
    <li>Avoid enormous network payloads.</li>
    <li>Serve images in next-gen formats like WebP and AVIF which provide better compression than PNG or JPEG. This means faster downloads and less data consumption. </li>
    <li>Eliminate render-blocking services by delivering critical JS/CSS inline and deferring all non-critical JS/styles. </li>
    <li>Reduce unused JavaScript and defer loading scripts until they are required to decrease bytes consumed by network activity.</li>
</ol>

<h2>Class 2: October 26</h2>
<b>1. How do you organize your code? What are some suggestions you find on the web?</b>
<p>I try and use comments to help with my code, but mostly I leave a line of space between two different formulas and collapse everything when I'm done so that it's easier to look at.</p>
<b>2. Can you describe your workflow when you create a web page or web app?</b>
<p>Yes I can. And I will! First, I come up with a wireframe so I know the general structure. Then, I write the HTML to match that wireframe. I then add in the JavaScript code for functionality, and I finish with CSS for styling.</p>
<b>3. You can’t work out how to solve a coding problem, where do you find the answer? Why? How do you know?</b>
<p>I use a mixture of ChatGPT and W3 schools. I use ChatGPT because I can have a conversation with it to ask any unusual questions I have in a way that W3 schools can't interact with me. I use W3 schools for examples of running the code because it is an esteemed source.</p>
<b>4. What problems have you solved that didn’t involve you coding?</b>
<p>Most problems. I would say in all seriousness though, that thinking mathematically requires understanding more logical principles than coding principles. Like breaking down the thought process behind finding all the prime numbers in a huge sequence is something that requires more thought than code.</p>
<b>5. Talk about your preferred development environment. (What IDE or text editor you enjoy, and why?)</b>
<p>My favorite so far is VisualStudio code, mostly because it is robust, has many plugins to help adjust the syntax of your code, a GIT terminal built in, and also VS Code Pets - the nifty little plugin to play with your pets while you code.</p>
<b>6. How are you keeping up with the latest developments in web development?</b>
<p>Mostly via Keith in the Discord channel "Tech News".</p>
