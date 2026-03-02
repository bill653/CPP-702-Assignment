<!DOCTYPE html>
<html lang="en">

<head>
    <title>Billy | Personal Profile</title>
    <meta charset="UTF-8">
</head>

<body>

    <!-- HEADER -->
    <header>
        <h1>Billy's Personal Profile Website</h1>
        <p>Diploma in Business Information Technology Student</p>
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
                My name is Billy. I am pursuing a Diploma in Business Information Technology.
                I am passionate about technology and how it improves business operations.
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
                <li>HTML Structure</li>
                <li>Networking Fundamentals</li>
                <li>Computer Applications</li>
                <li>Business Communication</li>
            </ul>

            <h3>My Learning Journey</h3>
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
                    It is a markup language used to structure content on the web.
                    It does not style the page but gives meaning and organization.
                </p>
            </article>

            <article>
                <h3>Structural Elements</h3>
                <p><strong>&lt;html&gt;</strong> – Root of the document.</p>
                <p><strong>&lt;head&gt;</strong> – Contains metadata and title.</p>
                <p><strong>&lt;body&gt;</strong> – Contains visible content.</p>
                <p><strong>&lt;header&gt;, &lt;nav&gt;, &lt;main&gt;, &lt;section&gt;, &lt;article&gt;, &lt;footer&gt;</strong> – Semantic elements used for proper structure.</p>
            </article>

            <article>
                <h3>Text Formatting Elements</h3>
                <p><strong>&lt;h1&gt; to &lt;h6&gt;</strong> – Headings.</p>
                <p><strong>&lt;p&gt;</strong> – Paragraph.</p>
                <p><strong>&lt;strong&gt;</strong> – Important text.</p>
                <p><strong>&lt;em&gt;</strong> – Emphasized text.</p>
            </article>

            <article>
                <h3>Lists</h3>
                <p><strong>&lt;ul&gt;</strong> – Unordered list.</p>
                <p><strong>&lt;ol&gt;</strong> – Ordered list.</p>
                <p><strong>&lt;li&gt;</strong> – List item.</p>
            </article>

            <article>
                <h3>Links</h3>
                <p>
                    <strong>&lt;a&gt;</strong> – Used to create hyperlinks.
                    Example: <a href="https://www.kcau.ac.ke">Visit KCA University</a>
                </p>
            </article>

            <article>
                <h3>Images</h3>
                <p><strong>&lt;img&gt;</strong> – Used to display images.</p>
                <img src="profile.jpg" alt="My Profile Picture" width="150">
            </article>

            <article>
                <h3>Tables</h3>
                <p><strong>&lt;table&gt;</strong> – Creates a table.</p>
                <p><strong>&lt;tr&gt;</strong> – Table row.</p>
                <p><strong>&lt;th&gt;</strong> – Table heading.</p>
                <p><strong>&lt;td&gt;</strong> – Table data.</p>
            </article>

            <article>
                <h3>Forms</h3>
                <p><strong>&lt;form&gt;</strong> – Collects user input.</p>
                <p><strong>&lt;label&gt;</strong> – Describes input field.</p>
                <p><strong>&lt;input&gt;</strong> – Input field.</p>
                <p><strong>&lt;textarea&gt;</strong> – Multi-line text input.</p>
                <p><strong>&lt;button&gt;</strong> – Submits form.</p>
            </article>

        </section>

        <!-- CONTACT FORM -->
        <section id="contact">
            <h2>Contact Me</h2>

            <form>
                <label>Name:</label><br>
                <input type="text"><br><br>

                <label>Email:</label><br>
                <input type="email"><br><br>

                <label>Message:</label><br>
                <textarea rows="4" cols="30"></textarea><br><br>

                <button type="submit">Submit</button>
            </form>
        </section>

    </main>

    <!-- FOOTER -->
    <footer>
        <hr>
        <p>© 2026 Billy |HTML Document</p>
    </footer>

</body>
</html>
