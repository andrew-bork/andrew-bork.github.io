<script>
</script>

<div class="main-container">
    <div class="header-container">
        <div class="line2">Andrew Lin</div>
        <div class="line3">Full stack developer | Software Engineer</div>
        <br/>
        <div class="desc">
            I'm a coder. I code things. My projects mostly lie on the web, but sometimes I venture beyond.

            <div class="nav">
                <a href="#abt-me">About Me</a>
                <a href="#projects">Projects</a>
                <a href="#contact">Contact Me</a>
            </div>
        </div>
    </div>
    <div id="abt-me" class="full-screen-container">
        <h2>About Me <hr></h2>

        <div class="skills">
            <div>
                Here are the languages I've used:
                <ul>
                    <li>C/C++</li>
                    <li>Java</li>
                    <li>Python</li>
                    <li>Javascript</li>
                </ul>
            </div>
            <div>
                Here are some frameworks and libraries I have worked with:
                <ul>
                    <li>Svelte</li>
                    <li>React</li>
                    <li>OpenGL</li>
                    <li>Tensorflow</li>
                    <li>OpenCV</li>
                    <li>Socket.io</li>
                    <li>Express.js</li>
                </ul>
            </div>
        </div>
    </div>
    <div id="projects" class="full-screen-container">
        <h2>Projects <hr></h2>

        <div class="projects">
            <div>
                <a href="https://andrew-bork.github.io/orbit/" target="_blank">
                    <h3>Orbit Simulator</h3>
                    <img src="/assets/orbits.png" alt="orbits"/>
                </a>
                <p>&emsp;A simple n-body simulation using newtonian gravity.</p>
            </div>
            <div>
                <a href="https://andrew-bork.github.io/terrain/" target="_blank">
                    <h3>Terrain Generator</h3>
                    <img src="/assets/terrain.png" alt="terrain"/>
                </a>
                <p>&emsp;A old and simple terrain generator using the diamond square algorithm.</p>
            </div>
            <div>
                <a href="https://andrew-bork.github.io/erosion/" target="_blank">
                    <h3>Hydraulic Eroder</h3>
                    <img src="/assets/erode.png" alt="erode"/>
                </a>
                <p>&emsp;A newer and less simple terrain generator that can simulate the effects of rain.</p>
            </div>
            <div>
                <a href="https://github.com/andrew-bork/autonomous" target="_blank">
                    <h3>Makeshift Drone</h3>
                    <img src="/assets/drone.jpg" alt="drone"/>
                </a>
                <p>&emsp;A experiment into using the raspberry pi 3B as a drone flight controller.</p>
            </div>
            <!-- <div>
                <a href="https://github.com/andrew-bork/hackathon" target="_blank">
                    <h3>Handscript</h3>
                    <img src="/assets/orbits.png" alt="orbits"/>
                </a>
                <p>&emsp;A program to classify American Sign Language using Tensorflow.</p>
            </div>
            <div>
                <a href="https://github.com/andrew-bork/hackation-backend" target="_blank">
                    <h3>Handscript (Backend)</h3>
                    <img src="/assets/orbits.png" alt="orbits"/>
                </a>
                <p>&emsp;Backend to <a href="https://github.com/andrew-bork/hackathon" target="_blank">Handscript</a></p>
            </div> -->
            <!-- <div>
                <a href="https://github.com/andrew-bork/hackation-backend" target="_blank">
                    <h3>C++ Socket.io Server</h3>
                    <img src="/assets/orbits.png" alt="orbits"/>
                </a>
                <p>&emsp;A Socket.io server written in C++</p>
            </div> -->
        </div>
    </div>
    <div id="contact" class="full-screen-container">
        <h2>Contact Me</h2>
        <a href="mailto:bork.andrew.ryan@gmail.com" target="_blank">bork.andrew.ryan@gmail.com</a>
        <a href="https://github.com/andrew-bork" target="_blank">Github Repo</a>
    </div>
</div>



<style>
    .main-container {
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
        width: 100%;
        height: max-content;
    }

    .header-container {
        max-width: 60%;
        height: 100vh;
        display: flex;
        /* align-items: center; */
        justify-content: center;
        flex-direction: column;
    }

    .full-screen-container {
        max-width: 60%;
        width: fit-content;
        min-height: 100vh;
        display: flex;
        /* align-items: center; */
        justify-content: center;
        flex-direction: column;
    }
    .line2 {
        color: #cae9fadd;
        font-size: clamp(40px, 4vw, 64px);
        font-weight: 800;
    }
    .line3 {
        color: #cae9fa44;
        font-size: clamp(20px, 4vw, 32px);
        font-weight: 800;
        padding-left: 40px;
    }

    .desc {
        color: #f1f9fddf;
        font-size: 16px;
        font-weight: normal;
        max-width: 500px;
        line-height: 1.5em;

    }

    h2 {
        color: #f1f9fdfb;
    }
    div {
        color: #ffffffaa;
        font-family: 'Roboto', sans-serif;
    }

    ul {
        display: grid;
        grid-template-columns: 50% 50%;
        grid-auto-rows: auto;
        padding: 0;
    }
    ul>li {
        list-style-type: none;
        margin-bottom: 5px;
    }
    ul>li::before {
        content: "‣ ";
        color: #52f4dfdd;
    }
    .skills>div {
        margin: 20px 50px;
    }
    .skills {
        display: flex;
        flex-wrap: wrap;
    }

    .projects {
        display: grid;
        grid-template-columns: auto auto auto;
        grid-auto-rows: auto;
    }

    .projects>div {
        position: relative;
        margin: 50px;
    }
    .projects>div img{
        max-width: 100%;
    }
    a {
        color: #f1f9fdfb;
        text-decoration: none;
        transition: color .3s;
    }
    a:hover {
        color: #5abcedfb;
    }
    .projects p {
        font-size: 12px;
    }

    .nav {
        margin-top: 20px;
    }

    .nav a {
        border: 1px solid #f1f9fdfb;
        padding: 10px 20px;
        font-size: 18px;
        margin: 5px;
        border-radius: 3px;
        transition: color .3s, border-color .3s;
    }

    .nav a:hover {
        border-color: #5abcedfb;

    }
</style>
