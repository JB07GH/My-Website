<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website Practice JB</title>
</head>
<link rel="stylesheet" href="./MyWebStyle.css">
<body>
    <section>
        <nav>
            <img src="./FES.svg" class="logo" alt="">
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#discord">Discord</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
        <header>
           <div class="row">
             <div>
                <h1>Best place to learn frontend</h1>
                <p class="subheader">Go from being an absolute beginner to pro with a simplified process</p>
                <button>Start now</button>
            </div>
            <figure>
                <img src="./laptop.png" alt="Home page image">
            </figure>
        </div>
        </header>

    </section>
    <main>
<section id="about">
<h2>About</h2>
<div class="row">
<div class="section__description">
<div class="section__description--wrapper">
    <p class="section__description--para">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Eos voluptas dolore, quisquam delectus magnam minus ducimus tenetur facilis at cumque eum repellat sapiente totam architecto sequi obcaecati adipisci similique beatae.
    </p>
    <p class="section__description--para">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque modi cupiditate doloremque vitae obcaecati adipisci voluptatum. Unde optio nostrum deserunt accusamus iure autem quisquam, doloremque consectetur! Voluptatibus voluptatum quas rerum.
    </p>
</div>
<figure class="about__img--wrapper">
    <img src="./about.jpg" alt="">
</figure>
</div>
</div>
</section>
<section id="discord">
    <h2>Discord</h2>
    <div class="row">
    <div class="section__description"> 
    <figure class="about__img--wrapper">
        <img src="./discord.png" alt="">
    </figure>
    <div class="section__description--wrapper">
        <p class="section__description--para">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Asperiores sapiente quae, itaque nobis voluptatem consectetur? Ducimus laudantium atque magnam blanditiis corporis pariatur. Eius sapiente aperiam ea eligendi impedit, dolore tempore.
        </p>
        <p class="section__description--para">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur tempore maxime, aliquid totam similique rem asperiores esse incidunt cum? Ex ipsam numquam accusamus natus, repudiandae maiores dicta quis nemo velit?
        </p>
    </div>
</div>
</div>
</section>

<section id="contact">
    <h2>Contact</h2>
    <form action="">
        <span>Email</span>
        <input type="email" placeholder="jane@example.com">
        <span>Message</span>
        <textarea type="text" placeholder="Cool Website, let's get connected."></textarea>
    <button>Contact Us!</button>
    </form>
</section>

    </main>
    <footer>
        <img class="footer__logo" src="./FES.svg" alt="">
        <div class="footer__links">
            <a class="footer__link" href="#about"></a>
            <a class="footer__link" href="#discord"></a>
            <a class="footer__link" href="#contact"></a>
            <a class="footer__link" href="courses"></a>
        </div>
        <p>copyright Frontend Simplified
        </p>
    </footer>
</body>
</html>
