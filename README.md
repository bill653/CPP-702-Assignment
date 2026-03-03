<!DOCTYPE html>
<html lang="en">

<head>
  <title>Billy | Turning Ideas into Digital Solutions</title>
    <meta charset="UTF-8">
</head>

<body>

    <!-- HEADER -->
    <header>
        <h1>Welcome to Billy's Digital World</h1>
    <img src="C:/Users/MicroTech Comp1/Pictures/Billy.jpeg"></img>
        <p>Passionate about Technology & Business Systems | Diploma in Business Information Technology</p>
       <hr>
    </header>

    <!-- NAVIGATION -->
    <nav>
        <h3>Navigation</h3>
        <ul>
            <li><a href="#about">About Me</a></li>
            <li><a href="#background">Background</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#html">HTML as One of My Core Skills</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
        <hr>
    </nav>

    <!-- MAIN CONTENT -->
    <main>

        <!-- ABOUT -->
        <section id="about">
            <h2>About Me</h2>
            <p>
 Hi, I’m Billy — a curious and ambitious Diploma in Business Information Technology student who loves turning ideas into digital solutions.
 I’m fascinated by how technology transforms ordinary businesses into smart, efficient, and innovative enterprises.
 For me, technology isn’t just about computers — it’s about solving problems, creating opportunities, and shaping the future of business.
            </p>
        </section>

        <!-- BACKGROUND -->
        <section id="background">
            <h2>Education Background</h2>

            <table border="1">
                <tr>
                    <th>Level</th>
                    <th>Institution</th>
                    <th>Year</th>
                </tr>
                <tr>
                    <td>DBIT</td>
                    <td>KCA University</td>
                    <td>2024 - Present</td>
              </tr>
              <tr>
                  <td>Computer Training</td>
                  <td>Afrotech Training Institute</td>
                  <td>2024</td>
               
                </tr>
                <tr>
                    <td>High School</td>
                    <td>Ramba Boys High School</td>
                    <td>2019-2023</td>
                </tr>
            </table>
        </section>

        <!-- SKILLS -->
        <section id="skills">
            <h2>My Skills</h2>

            <ul>
                <li>Computer Software Skills</li>
                <li>Networking Basics</li>
                <li>Professional Communication</li>
                <li>Webpage Layout & Design</li>
            </ul>

            <h3>Learning Experience</h3>
            <ol>
                <li>Learned basic computer skills</li>
                <li>Studied networking basics</li>
                <li>Started web development with HTML</li>
            </ol>
        </section>

        <!-- HTML SKILLS DOCUMENTATION -->
    <section id="html">
    <h2>HTML as One of My Core Skills</h2>

    <article>
        <h3>What is HTML?</h3>
        <p>
            HTML stands for HyperText Markup Language.
            WHAT IT IS: A markup language used to create web pages.
            WHAT IT IS USED FOR: Structuring content such as text, images, links, and tables.
            WHEN IT SHOULD BE USED: Whenever creating a webpage.
            HOW IT SHOULD BE USED CORRECTLY: By using proper opening and closing tags and following correct structure.
        </p>
    </article>

    <article>
        <h3>Structural Elements</h3>

        <p>
            <strong>&lt;html&gt;</strong><br>
            WHAT IT IS: The root element of an HTML document.<br>
            USED FOR: Wrapping all webpage content.<br>
            WHEN: Used once in every HTML document.<br>
            HOW: All other elements must be inside it.
        </p>

        <p>
            <strong>&lt;head&gt;</strong><br>
            WHAT IT IS: Metadata container.<br>
            USED FOR: Storing title, charset and links.<br>
            WHEN: Before the body element.<br>
            HOW: Should not contain visible content.
        </p>

        <p>
            <strong>&lt;body&gt;</strong><br>
            WHAT IT IS: Contains visible webpage content.<br>
            USED FOR: Displaying text, images, forms and tables.<br>
            WHEN: After the head element.<br>
            HOW: Only one body per page.
        </p>

        <p>
            <strong>&lt;header&gt;, &lt;nav&gt;, &lt;main&gt;, &lt;section&gt;, &lt;article&gt;, &lt;footer&gt;</strong><br>
            WHAT THEY ARE: Semantic structural elements.<br>
            USED FOR: Organizing content meaningfully.<br>
            WHEN: To structure different parts of a webpage.<br>
            HOW: Should be used according to their purpose (header for introduction, nav for navigation, footer for closing content).
        </p>
    </article>

    <article>
        <h3>Text Formatting Elements</h3>

        <p>
            <strong>&lt;h1&gt; to &lt;h6&gt;</strong><br>
            WHAT: Heading elements.<br>
            USED FOR: Defining titles and subtitles.<br>
            WHEN: To structure content hierarchy.<br>
            HOW: Use in correct order without skipping levels.
        </p>

        <p>
            <strong>&lt;p&gt;</strong><br>
            WHAT: Paragraph element.<br>
            USED FOR: Writing blocks of text.<br>
            WHEN: For normal content text.<br>
            HOW: Should not contain block elements like section or div.
        </p>

        <p>
            <strong>&lt;strong&gt;</strong><br>
            WHAT: Important text element.<br>
            USED FOR: Showing strong importance (usually bold).<br>
            WHEN: When content is important.<br>
            HOW: Should not be used only for decoration.
        </p>

        <p>
            <strong>&lt;em&gt;</strong><br>
            WHAT: Emphasis element.<br>
            USED FOR: Stressing text (usually italic).<br>
            WHEN: When emphasis changes meaning.<br>
            HOW: Used properly inside paragraphs.
        </p>
    </article>

    <article>
        <h3>Lists</h3>

        <p>
            <strong>&lt;ul&gt;</strong><br>
            WHAT: Unordered list.<br>
            USED FOR: Bullet lists.<br>
            WHEN: When order does not matter.<br>
            HOW: Must contain list items (&lt;li&gt;).
        </p>

        <p>
            <strong>&lt;ol&gt;</strong><br>
            WHAT: Ordered list.<br>
            USED FOR: Numbered lists.<br>
            WHEN: When order matters.<br>
            HOW: Must contain list items (&lt;li&gt;).
        </p>

        <p>
            <strong>&lt;li&gt;</strong><br>
            WHAT: List item.<br>
            USED FOR: Representing items in lists.<br>
            WHEN: Inside ul or ol.<br>
            HOW: Cannot be used outside a list.
        </p>
    </article>

    <article>
        <h3>Links</h3>

        <p>
            <strong>&lt;a&gt;</strong><br>
            WHAT: Anchor element.<br>
            USED FOR: Creating hyperlinks.<br>
            WHEN: Linking to another webpage or section.<br>
            HOW: Must include href attribute with a valid link.
             Example: <a href="https://www.kcau.ac.ke">Visit KCA University</a>
        </p>
    </article>

    <article>
        <h3>Images</h3>

        <p>
            <strong>&lt;img&gt;</strong><br>
            WHAT: Image element.<br>
            USED FOR: Displaying images.<br>
            WHEN: When visual representation is needed.<br>
            HOW: Must include src and alt attributes.
        </p>
    </article>

    <article>
        <h3>Tables</h3>

        <p>
            <strong>&lt;table&gt;</strong><br>
            WHAT: Table container.<br>
            USED FOR: Displaying structured data.<br>
            WHEN: Presenting tabular information.<br>
            HOW: Must contain rows (&lt;tr&gt;) and cells (&lt;th&gt;, &lt;td&gt;).
        </p>
    </article>

    <article>
    <h3>Forms</h3>

    <p>
        <strong>&lt;form&gt;</strong><br>
        WHAT: Form container.<br>
        USED FOR: Collecting user input.<br>
        WHEN: For registration or contact forms.<br>
        HOW: Should contain input fields and a submit button.
    </p>

    <section id="contact">
        <h2>Contact Me</h2>

        <form>
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name"><br><br>

            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email"><br><br>

            <label for="message">Message:</label><br>
            <textarea id="message" name="message" rows="4" cols="30"></textarea><br><br>

            <button type="submit">Submit</button>
        </form>
    </section>
</article>

</section>

    </main>

    <!-- FOOTER -->
    <footer>
        <hr>
        <p>© 2026 Billy | HTML Document</p>
    </footer>

</body>
</html>
