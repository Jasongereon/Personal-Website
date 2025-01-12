<nav>
    <div>Jason Cai</div>
    <div>Profile</div>
    <div>Projects</div>
    <div>Contact</div>
</nav>

<main>



    <article id="intro-myself">

        <figure>
            <img id="jason-cai-portrait" alt="">
        </figure>

        <div id="intro-main">

            <header>
                <h1>Jason Cai</h1>
            </header>

            <p>
                I am a design engineer based in Imperial College London specialising in
                product design, with a particular focus on the application of CMF
                (Colour, Material, and Finish).
            </p>

        </div>

    </article>

    <article id="skills">

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

    </article>

    <article>

        <header>
            <h1>Let's collaborate</h1>
        </header>

    </article>

</main>

<style>
    article#intro-myself {
        display: flex;

        align-items: center;
        justify-content: space-around;

        & > figure {
            outline: 1px solid red;
        }

        & > #intro-main {
            max-width: 20rem;
        }
    }

    img {
        display: block;
        max-width: 5rem;
    }
</style>
