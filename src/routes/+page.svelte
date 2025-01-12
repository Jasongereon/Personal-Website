<nav>
    <a>Jason Cài</a>
    <a>Profile</a>
    <a>Projects</a>
    <a href="#contacts">Contact</a>
</nav>

<hr>

<main>

    <article id="intro-myself">

        <figure class="left">
            <img id="jason-cai-portrait" src="/jason-cai-portrait.jpg" alt="">
        </figure>

        <div class="right">

            <header>
                <h1>Jason Cài</h1>
            </header>

            <p>
                I am a design engineer based in Imperial College London specialising in
                product design, with a particular focus on the application of CMF
                (Colour, Material, and Finish).
            </p>

        </div>

    </article>

    <hr class="middle">

    <article id="skills">

        <div class="left">

        </div>


        <div class="right">

            <header>
                <h1>Skills</h1>
            </header>

            <ul>
                <li>Mechanical Design</li>
                <li>UI/UX Design</li>
                <li>3D Modelling</li>
                <li>Finite Element Analysis</li>
                <li>Computational Fluid</li>
                <li>User Research</li>
                <li>Market Analysis</li>
                <li>Branding & Identity</li>
            </ul>

        </div>

    </article>

    <hr class="middle">

    <article id="lets-colab">

        <svg id="hand-point-down" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512"><!--!Font Awesome Free 6.7.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2025 Fonticons, Inc.--><path d="M64 448l0-177.6c5.2 1 10.5 1.6 16 1.6l16 0 0 32 0 144c0 8.8-7.2 16-16 16s-16-7.2-16-16zM80 224c-17.7 0-32-14.3-32-32c0 0 0 0 0 0l0-24c0-66.3 53.7-120 120-120l48 0c52.5 0 97.1 33.7 113.4 80.7c-3.1-.5-6.2-.7-9.4-.7c-20 0-37.9 9.2-49.7 23.6c-9-4.9-19.4-7.6-30.3-7.6c-15.1 0-29 5.3-40 14c-11-8.8-24.9-14-40-14l-40 0c-13.3 0-24 10.7-24 24s10.7 24 24 24l40 0c8.8 0 16 7.2 16 16s-7.2 16-16 16l-40 0-40 0zM0 192s0 0 0 0c0 18 6 34.6 16 48l0 208c0 35.3 28.7 64 64 64s64-28.7 64-64l0-82c5.1 1.3 10.5 2 16 2c25.3 0 47.2-14.7 57.6-36c7 2.6 14.5 4 22.4 4c20 0 37.9-9.2 49.7-23.6c9 4.9 19.4 7.6 30.3 7.6c35.3 0 64-28.7 64-64l0-64 0-24C384 75.2 308.8 0 216 0L168 0C75.2 0 0 75.2 0 168l0 24zm336 64c0 8.8-7.2 16-16 16s-16-7.2-16-16l0-48 0-16c0-8.8 7.2-16 16-16s16 7.2 16 16l0 64zM160 272c5.5 0 10.9-.7 16-2l0 2 0 32c0 8.8-7.2 16-16 16s-16-7.2-16-16l0-32 16 0zm64-24l0-40c0-8.8 7.2-16 16-16s16 7.2 16 16l0 48 0 16c0 8.8-7.2 16-16 16s-16-7.2-16-16l0-24z"/></svg>

        <header>
            <h1>Let's collaborate</h1>
        </header>

        <div id="contacts">

            <div>
                <img src="" alt="">
                <div>
                    <a href="mailto:yc3422@ic.ac.uk">
                        Email
                    </a>
                </div>
            </div>

            <div>
                <img src="" alt="">
                <div>
                    <a href="tel:+447536161373">
                        UK
                    </a>
                </div>
            </div>

            <div>
                <img src="" alt="">
                <div>
                    <a href="tel:+8615251918466">
                        China
                    </a>
                </div>
            </div>

            <div>
                <img src="" alt="">
                <div>
                    <a href="">
                        LinkedIn
                    </a>
                </div>
            </div>

        </div>

    </article>

</main>

<hr class="middle">

<style lang="scss">
    @import "font.css";

    :global(body) {
        background-color: #1B1B1B;
        margin: 0;
    }

    a {
        color: unset;
        text-decoration: none;
    }

    main {
        font-family: futura-light, sans-serif;
    }

    header {
        font-family: futura-book, sans-serif;
    }

    nav {
        display: flex;
        justify-content: space-around;

        font-family: futura-book, sans-serif;
        font-size: 2rem;
        color: rgb(253, 220, 149);

        & > a {
            padding: 1rem 2rem;
        }
    }

    hr {
        background-color: black;
        height: 1px;
        margin: 0 3rem 3rem 3rem;
        border: none;

        &.middle {
            margin: 3rem;
        }
    }

    article {
        & {
            color: rgb(253, 220, 149);
            font-size: 1.2rem;
        }

        & header {
            color: rgb(255, 184, 0);
            font-size: 2.5rem;
        }
    }

    article#intro-myself {
        display: flex;
        justify-content: space-around;

        & > figure {
            margin-block: 0;
            margin-inline: 0;

            & > img {
                margin: 0 auto;
                display: block;
                width: 25rem;
            }
        }

        & > .right > p {
            max-width: 25rem;
        }

        & > .left {
            flex: 3;
        }

        & > .right {
            flex: 2;
        }
    }

    article#skills {
        display: flex;
        justify-content: space-around;

        & ul {
            list-style: none;
            padding-inline-start: 0;

            & > li {
                font-size: 1.5rem;
                margin: 0.5rem;
            }
        }

        & > .left {
            flex: 3;
        }

        & > .right {
            flex: 2;
        }
    }

    article#lets-colab {
        & > #hand-point-down {
            display: block;
            margin: 0 auto;
            width: 4rem;

            & path {
                fill: white;
            }
        }

        header {
            text-align: center;
        }

        & > #contacts {
            max-width: 40rem;
            margin: 0 auto;

            display: flex;
            justify-content: space-around;

            & a {
                font-family: futura-book, sans-serif;
            }
        }
    }
</style>
