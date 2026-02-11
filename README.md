# intership-2026
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Complete HTML Elements Showcase</title>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Complete HTML Elements Showcase</h1>
        <p>A comprehensive example of all requested HTML elements in a single page</p>
        <hr>
    </header>
    
    <!-- Navigation Menu -->
    <nav>
        <h2>Page Navigation</h2>
        <ul>
            <li><a href="#headings-paragraphs">1. Headings & Paragraphs</a></li>
            <li><a href="#text-formatting">2. Text Formatting</a></li>
            <li><a href="#hyperlinks">3. Hyperlinks</a></li>
            <li><a href="#lists">4. Lists</a></li>
            <li><a href="#multimedia">5. Images & Multimedia</a></li>
            <li><a href="#iframe">6. Iframe & Tags</a></li>
            <li><a href="#tables">7. Tables</a></li>
            <li><a href="#forms">8. Forms</a></li>
        </ul>
        <hr>
    </nav>
    
    <main>
        <!-- Section 1: Heading and Paragraph -->
        <section id="headings-paragraphs">
            <h2>1. Headings and Paragraphs</h2>
            
            <h1>This is a Main Heading (H1)</h1>
            <p>This is a paragraph that follows the main heading. HTML provides six levels of headings, from H1 (most important) to H6 (least important). Headings help create a clear document structure and improve accessibility.</p>
            
            <h2>This is a Subheading (H2)</h2>
            <p>This paragraph follows an H2 heading. Each section of content should have a clear heading to organize information logically.</p>
            
            <h3>This is an H3 Heading</h3>
            <p>Smaller headings like H3 are used for subsections within larger sections.</p>
            
            <h4>This is an H4 Heading</h4>
            <p>H4 headings are used for further nested content sections.</p>
            
            <h5>This is an H5 Heading</h5>
            <p>H5 headings are less common but available for deep nesting.</p>
            
            <h6>This is an H6 Heading</h6>
            <p>H6 is the smallest heading level available in HTML.</p>
            <hr>
        </section>
        
        <!-- Section 2: Text Formatting -->
        <section id="text-formatting">
            <h2>2. Text Formatting Examples</h2>
            
            <p>This paragraph contains <b>bold text</b> and <strong>strong text</strong>.</p>
            
            <p>This paragraph contains <i>italic text</i> and <em>emphasized text</em>.</p>
            
            <p>This paragraph contains <u>underlined text</u> and <ins>inserted text</ins>.</p>
            
            <p>This paragraph contains <s>strikethrough text</s> and <del>deleted text</del>.</p>
            
            <p>This paragraph contains <mark>highlighted text</mark> using the mark tag.</p>
            
            <p>This paragraph contains <small>smaller text</small> and regular sized text.</p>
            
            <p>This paragraph contains <sup>superscript text</sup> and <sub>subscript text</sub>.</p>
            
            <p>This paragraph contains <code>inline code</code> and <kbd>keyboard input</kbd>.</p>
            
            <p>This paragraph contains a <abbr title="HyperText Markup Language">HTML</abbr> abbreviation.</p>
            
            <p>This paragraph contains a <q>short quotation</q> inside it.</p>
            
            <blockquote>
                This is a blockquote. It's used for longer quotations that should stand out from the main text.
                <cite>- Author Name</cite>
            </blockquote>
            
            <pre>
This is preformatted text.
It preserves   spaces,
line breaks,
and     indentation.
            </pre>
            
            <p>The chemical formula for water is H<sub>2</sub>O.</p>
            <p>Einstein's famous equation is E = mc<sup>2</sup>.</p>
            <hr>
        </section>
        
        <!-- Section 3: Hyperlinks -->
        <section id="hyperlinks">
            <h2>3. Hyperlinks</h2>
            
            <h3>External Links</h3>
            <ul>
                <li><a href="https://www.google.com" target="_blank">Google (opens in new tab)</a></li>
                <li><a href="https://www.wikipedia.org">Wikipedia (opens in same tab)</a></li>
                <li><a href="https://www.github.com" target="_blank" rel="noopener noreferrer">GitHub</a></li>
            </ul>
            
            <h3>Internal Links (Anchor Links)</h3>
            <ul>
                <li><a href="#headings-paragraphs">Jump to Headings & Paragraphs</a></li>
                <li><a href="#tables">Jump to Tables</a></li>
                <li><a href="#forms">Jump to Forms</a></li>
            </ul>
            
            <h3>Link with Title Attribute</h3>
            <p><a href="https://www.example.com" title="Visit Example Website">Hover over this link to see the title</a></p>
            
            <h3>Email and Phone Links</h3>
            <ul>
                <li><a href="mailto:example@email.com">Send an Email</a></li>
                <li><a href="tel:+1234567890">Call Us: +1 234 567 890</a></li>
                <li><a href="mailto:someone@example.com?subject=Website%20Inquiry&body=Hello%20there!">Email with pre-filled subject and body</a></li>
            </ul>
            
            <h3>Download Link</h3>
            <p><a href="sample.pdf" download>Download Sample PDF</a> (Note: This link won't work without an actual file)</p>
            <hr>
        </section>
        
        <!-- Section 4: Lists -->
        <section id="lists">
            <h2>4. Lists (Ordered and Unordered)</h2>
            
            <h3>Ordered List (Numerical)</h3>
            <ol>
                <li>First item in ordered list</li>
                <li>Second item in ordered list</li>
                <li>Third item in ordered list</li>
                <li>Fourth item in ordered list</li>
            </ol>
            
            <h3>Ordered List with Roman Numerals</h3>
            <ol type="I">
                <li>Item I</li>
                <li>Item II</li>
                <li>Item III</li>
                <li>Item IV</li>
            </ol>
            
            <h3>Ordered List with Letters</h3>
            <ol type="A">
                <li>Item A</li>
                <li>Item B</li>
                <li>Item C</li>
                <li>Item D</li>
            </ol>
            
            <h3>Unordered List (Bulleted)</h3>
            <ul>
                <li>First bullet point</li>
                <li>Second bullet point</li>
                <li>Third bullet point</li>
                <li>Fourth bullet point</li>
            </ul>
            
            <h3>Unordered List with Different Bullet Styles</h3>
            <ul>
                <li type="square">Square bullet</li>
                <li type="circle">Circle bullet</li>
                <li type="disc">Disc bullet (default)</li>
            </ul>
            
            <h3>Nested Lists</h3>
            <ul>
                <li>Main item 1
                    <ul>
                        <li>Sub-item 1.1</li>
                        <li>Sub-item 1.2</li>
                    </ul>
                </li>
                <li>Main item 2
                    <ol>
                        <li>Sub-item 2.1</li>
                        <li>Sub-item 2.2</li>
                    </ol>
                </li>
                <li>Main item 3</li>
            </ul>
            
            <h3>Definition List</h3>
            <dl>
                <dt>HTML</dt>
                <dd>HyperText Markup Language - the standard language for creating web pages</dd>
                
                <dt>CSS</dt>
                <dd>Cascading Style Sheets - used for styling HTML documents</dd>
                
                <dt>JavaScript</dt>
                <dd>A programming language used to create interactive web pages</dd>
            </dl>
            <hr>
        </section>
        
        <!-- Section 5: Images and Multimedia -->
        <section id="multimedia">
            <h2>5. Images and Multimedia</h2>
            
            <h3>Images</h3>
            <p>Image with alt text (using placeholder):</p>
            <img src="https://via.placeholder.com/400x200" alt="Placeholder image 400x200 pixels" width="400" height="200">
            
            <p>Image with caption:</p>
            <figure>
                <img src="https://via.placeholder.com/300x150" alt="Another placeholder image" width="300" height="150">
                <figcaption>Fig. 1 - A placeholder image with caption</figcaption>
            </figure>
            
            <h3>Audio</h3>
            <p>Audio player (with placeholder source):</p>
            <audio controls>
                <source src="audio.mp3" type="audio/mpeg">
                <source src="audio.ogg" type="audio/ogg">
                Your browser does not support the audio element.
            </audio>
            
            <h3>Video</h3>
            <p>Video player (with placeholder source):</p>
            <video width="400" controls>
                <source src="movie.mp4" type="video/mp4">
                <source src="movie.ogg" type="video/ogg">
                Your browser does not support the video tag.
            </video>
            
            <h3>Image as a Link</h3>
            <a href="https://www.example.com">
                <img src="https://via.placeholder.com/150x100" alt="Clickable placeholder image" width="150" height="100">
            </a>
            <p>Click the image above to visit example.com</p>
            <hr>
        </section>
        
        <!-- Section 6: Iframe and Tags -->
        <section id="iframe">
            <h2>6. Iframe and Other Tags</h2>
            
            <h3>Iframe (Embedding External Content)</h3>
            <p>Embedded Google Map:</p>
            <iframe 
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3024.2219901290355!2d-74.00369368400567!3d40.71312937933185!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89c25a23e28c1191%3A0x49f75d3281df052a!2s150%20Park%20Row%2C%20New%20York%2C%20NY%2010007%2C%20USA!5e0!3m2!1sen!2s!4v1618326166405!5m2!1sen!2s" 
                width="600" 
                height="450" 
                style="border:0;" 
                allowfullscreen="" 
                loading="lazy">
            </iframe>
            
            <p>Embedded YouTube Video:</p>
            <iframe 
                width="560" 
                height="315" 
                src="https://www.youtube.com/embed/dQw4w9WgXcQ" 
                title="YouTube video player" 
                frameborder="0" 
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                allowfullscreen>
            </iframe>
            
            <h3>Other HTML Tags</h3>
            
            <p>Address tag: <address>123 Street, City, Country</address></p>
            
            <p>Time tag: The meeting is at <time datetime="2023-10-15T09:00">9 AM on October 15, 2023</time></p>
            
            <p>Meter tag: Disk usage: <meter value="6" min="0" max="10">6 out of 10</meter></p>
            
            <p>Progress tag: Loading: <progress value="75" max="100">75%</progress></p>
            
            <p>Details and Summary tag:</p>
            <details>
                <summary>Click to expand for more information</summary>
                <p>This is additional content that is hidden by default but can be revealed by clicking the summary.</p>
            </details>
            
            <p>Dialog tag (Note: This requires JavaScript to open):</p>
            <dialog id="myDialog">
                <p>This is a dialog box.</p>
                <button onclick="document.getElementById('myDialog').close()">Close</button>
            </dialog>
            <button onclick="document.getElementById('myDialog').showModal()">Open Dialog</button>
            <hr>
        </section>
        
        <!-- Section 7: Tables -->
        <section id="tables">
            <h2>7. Tables</h2>
            
            <h3>Basic Table</h3>
            <table border="1">
                <tr>
                    <th>Name</th>
                    <th>Age</th>
                    <th>City</th>
                </tr>
                <tr>
                    <td>John Doe</td>
                    <td>28</td>
                    <td>New York</td>
                </tr>
                <tr>
                    <td>Jane Smith</td>
                    <td>32</td>
                    <td>Los Angeles</td>
                </tr>
                <tr>
                    <td>Bob Johnson</td>
                    <td>45</td>
                    <td>Chicago</td>
                </tr>
            </table>
            
            <h3>Table with Caption and Structure</h3>
            <table border="1">
                <caption>Monthly Sales Report</caption>
                <thead>
                    <tr>
                        <th>Month</th>
                        <th>Product A</th>
                        <th>Product B</th>
                        <th>Product C</th>
                        <th>Total</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>January</td>
                        <td>$1,200</td>
                        <td>$800</td>
                        <td>$1,500</td>
                        <td>$3,500</td>
                    </tr>
                    <tr>
                        <td>February</td>
                        <td>$1,500</td>
                        <td>$900</td>
                        <td>$1,800</td>
                        <td>$4,200</td>
                    </tr>
                    <tr>
                        <td>March</td>
                        <td>$1,800</td>
                        <td>$1,200</td>
                        <td>$2,000</td>
                        <td>$5,000</td>
                    </tr>
                </tbody>
                <tfoot>
                    <tr>
                        <th>Quarter Total</th>
                        <th>$4,500</th>
                        <th>$2,900</th>
                        <th>$5,300</th>
                        <th>$12,700</th>
                    </tr>
                </tfoot>
            </table>
            
            <h3>Table with Rowspan and Colspan</h3>
            <table border="1">
                <tr>
                    <th rowspan="2">Name</th>
                    <th colspan="2">Contact Information</th>
                    <th rowspan="2">Department</th>
                </tr>
                <tr>
                    <th>Email</th>
                    <th>Phone</th>
                </tr>
                <tr>
                    <td>Alice Brown</td>
                    <td>alice@example.com</td>
                    <td>(123) 456-7890</td>
                    <td>Marketing</td>
                </tr>
                <tr>
                    <td>Charlie Davis</td>
                    <td>charlie@example.com</td>
                    <td>(987) 654-3210</td>
                    <td>Engineering</td>
                </tr>
            </table>
            <hr>
        </section>
        
        <!-- Section 8: Forms -->
        <section id="forms">
            <h2>8. Forms</h2>
            
            <form action="#" method="post">
                <h3>Contact Form</h3>
                
                <fieldset>
                    <legend>Personal Information</legend>
                    
                    <label for="name">Full Name:</label><br>
                    <input type="text" id="name" name="name" required placeholder="Enter your full name"><br><br>
                    
                    <label for="email">Email Address:</label><br>
                    <input type="email" id="email" name="email" required placeholder="Enter your email"><br><br>
                    
                    <label for="phone">Phone Number:</label><br>
                    <input type="tel" id="phone" name="phone" placeholder="(123) 456-7890"><br><br>
                    
                    <label for="dob">Date of Birth:</label><br>
                    <input type="date" id="dob" name="dob"><br><br>
                    
                    <label for="age">Age:</label><br>
                    <input type="number" id="age" name="age" min="1" max="120" placeholder="Enter your age"><br><br>
                    
                    <label>Gender:</label><br>
                    <input type="radio" id="male" name="gender" value="male">
                    <label for="male">Male</label><br>
                    <input type="radio" id="female" name="gender" value="female">
                    <label for="female">Female</label><br>
                    <input type="radio" id="other" name="gender" value="other">
                    <label for="other">Other</label><br><br>
                </fieldset>
                
                <fieldset>
                    <legend>Additional Information</legend>
                    
                    <label for="country">Country:</label><br>
                    <select id="country" name="country">
                        <option value="">Select a country</option>
                        <option value="us">United States</option>
                        <option value="ca">Canada</option>
                        <option value="uk">United Kingdom</option>
                        <option value="au">Australia</option>
                        <option value="other">Other</option>
                    </select><br><br>
                    
                    <label for="interests">Interests (select multiple):</label><br>
                    <select id="interests" name="interests" multiple size="4">
                        <option value="tech">Technology</option>
                        <option value="sports">Sports</option>
                        <option value="music">Music</option>
                        <option value="travel">Travel</option>
                        <option value="reading">Reading</option>
                        <option value="cooking">Cooking</option>
                    </select><br>
                    <small>Hold Ctrl (or Cmd on Mac) to select multiple options</small><br><br>
                    
                    <label>Skills (check all that apply):</label><br>
                    <input type="checkbox" id="html" name="skills" value="html">
                    <label for="html">HTML</label><br>
                    <input type="checkbox" id="css" name="skills" value="css">
                    <label for="css">CSS</label><br>
                    <input type="checkbox" id="js" name="skills" value="js">
                    <label for="js">JavaScript</label><br>
                    <input type="checkbox" id="python" name="skills" value="python">
                    <label for="python">Python</label><br><br>
                    
                    <label for="favcolor">Favorite Color:</label><br>
                    <input type="color" id="favcolor" name="favcolor" value="#3498db"><br><br>
                    
                    <label for="website">Website URL:</label><br>
                    <input type="url" id="website" name="website" placeholder="https://example.com"><br><br>
                    
                    <label for="file">Upload Resume:</label><br>
                    <input type="file" id="file" name="file"><br><br>
                    
                    <label for="range">Experience Level:</label><br>
                    <input type="range" id="range" name="range" min="0" max="10" value="5">
                    <span id="rangeValue">5</span><br><br>
                    
                    <label for="message">Message:</label><br>
                    <textarea id="message" name="message" rows="5" cols="50" placeholder="Enter your message here..."></textarea><br><br>
                </fieldset>
                
                <fieldset>
                    <legend>Form Actions</legend>
                    
                    <input type="reset" value="Reset Form">
                    <input type="submit" value="Submit Form">
                    <button type="button">Just a Button (no action)</button>
                </fieldset>
            </form>
            
            <h3>Search Form</h3>
            <form action="https://www.google.com/search" method="get" target="_blank">
                <label for="search">Google Search:</label>
                <input type="search" id="search" name="q" placeholder="Search Google...">
                <input type="submit" value="Search">
            </form>
            <hr>
        </section>
    </main>
    
    <footer>
        <h2>Page Footer</h2>
        <p>This page demonstrates all requested HTML elements:</p>
        <ol>
            <li>Headings and Paragraphs</li>
            <li>Text Formatting</li>
            <li>Hyperlinks</li>
            <li>Lists (Ordered and Unordered)</li>
            <li>Images and Multimedia</li>
            <li>Iframe and Other Tags</li>
            <li>Tables</li>
            <li>Forms</li>
        </ol>
        
        <p><a href="#top">Back to Top</a></p>
        
        <p>&copy; 2023 HTML Showcase. All elements are for demonstration purposes.</p>
    </footer>
</body>
</html>
