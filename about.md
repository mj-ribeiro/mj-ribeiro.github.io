---
layout: default
title: About
---

<style>
.about-container {
    display: flex;
    align-items: flex-start;
    justify-content: space-between;
    gap: 40px;
    margin-top: 30px;
    flex-wrap: wrap;
}

.about-text {
    flex: 1 1 600px;
    min-width: 280px;
}

.about-text h1 {
    margin-top: 0;
    margin-bottom: 20px;
    font-size: 2rem;
}

.about-text p {
    text-align: justify;
    line-height: 1.7;
    font-size: 1.05rem;
    margin-bottom: 18px;
}

.about-links {
    margin-top: 20px;
}

.about-links a {
    display: inline-block;
    margin-right: 15px;
    margin-bottom: 10px;
    padding: 10px 18px;
    text-decoration: none;
    border: 1px solid #333;
    border-radius: 6px;
    color: #333;
    font-weight: 500;
    transition: all 0.2s ease;
}

.about-links a:hover {
    background-color: #333;
    color: #fff;
}

.about-image {
    flex: 0 0 320px;
    max-width: 320px;
}

.about-image img {
    width: 100%;
    height: auto;
    border-radius: 10px;
    display: block;
    object-fit: cover;
    box-shadow: 0 4px 14px rgba(0,0,0,0.12);
}

@media (max-width: 768px) {
    .about-container {
        flex-direction: column;
    }

    .about-image {
        max-width: 100%;
    }
}
</style>

<div class="about-container">
    
    <div class="about-text">
        <h1>Welcome to my website!</h1>

        <p>
            I am an economist with a PhD in Applied Economics from FEARP-USP. I am currently based in Barcelona, Spain, where I conduct research with Professor Bruno Delalibera at the University of Barcelona.
        </p>

        <p>
            My main research interests include data science, machine learning, econometrics, macroeconomics, and computational economics. I am also interested in the economic impacts of automation and artificial intelligence.
        </p>

        <div class="about-links">
            <a href="http://buscatextual.cnpq.br/buscatextual/visualizacv.do?id=K8457340D4" target="_blank">Lattes</a>
            <a href="https://mj-ribeiro.github.io/cv.pdf" target="_blank">CV</a>
        </div>
    </div>

    <div class="about-image">
        <img src="/assets/img/me.jpeg" alt="Photo of Marcos Júnio Ribeiro">
    </div>

</div>