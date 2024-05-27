---
layout: default
---

<h1 style="text-align: center;">LSE LIBERATED ZONE</h1>

On May 14th, the eve of the 76th anniversary of the Nakba, we started out encampment for Palestine. We are currentely occupying the the ground floor of the London School of Economics' (LSE) Bloom Building (formerly the Marshall Building), in ongoing protest at the university's financial complicity in the genocide of the Palestinian people. Central amongst the our demands is the issue of divestment. In line with LSESU Palestine Society's 116-page 'Assests in Apartheid Report' we call on the university to divest its £89 million worth of investments in crimes Against the Palestinian people, the arms trade, fossil fuels, and the financing of such egregious activities.


---

<h2 style="text-align: center;">CAMP STATEMENTS</h2>
<button style="display: block; margin: 0 auto;"><a href="https://lseliberatedzone.github.io/document/Statement_LSE_Encampment_22_May_2024.pdf" target="_blank"><strong style="color: black;">Statement 22 May</strong></a></button>

<button style="display: block; margin: 0 auto;"><a href="https://lseliberatedzone.github.io/document/Statement_LSE_Encampment_27_May_2024.pdf" target="_blank"><strong style="color: black;">Statement 27 May</strong></a></button>

---
<h2 style="text-align: center;">OUR DEMANDS</h2>

<div class="carousel">
    <button class="prev" onclick="moveSlide(-1)">❮</button>
    <div class="carousel-container">
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/1.PNG" alt="Slide 1"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/2.PNG" alt="Slide 2"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/3.PNG" alt="Slide 3"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/4.PNG" alt="Slide 4"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/5.PNG" alt="Slide 5"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/6.PNG" alt="Slide 6"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/7.PNG" alt="Slide 7"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/8.PNG" alt="Slide 8"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/9.PNG" alt="Slide 9"></div>
        <div class="carousel-slide"><img src="https://lseliberatedzone.github.io/document/10.PNG" alt="Slide 10"></div>
    </div>
    <button class="next" onclick="moveSlide(1)">❯</button>
</div>

<style>
    .carousel {
        position: relative;
        width: 100%;
        height: 100%;
        margin: auto;
        overflow: hidden;
    }

    .carousel-container {
        display: flex;
        transition: transform 0.5s ease-in-out;
        width: 100%; /* 540px * 10 images */
    }

    .carousel-slide {
        flex-shrink: 0;
        width: 100%;
        height: 100%;
        border: none; /* Remove iframe borders */
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .carousel-slide img {
        max-width: 100%;
        max-height: 100%;
        object-fit: contain; /* Ensures the image fits within the slide */
    }

    .prev, .next {
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        background-color: rgba(0, 0, 0, 0.5);
        color: white;
        border: none;
        padding: 10px;
        cursor: pointer;
        z-index: 10;
    }

    .prev {
        left: 10px;
    }

    .next {
        right: 10px;
    }
</style>

<script>
    let slideIndex = 0;

    function moveSlide(n) {
        const slides = document.querySelectorAll('.carousel-slide');
        slideIndex = (slideIndex + n + slides.length) % slides.length;
        document.querySelector('.carousel-container').style.transform = `translateX(${-slideIndex * 100}%)`; // Adjust this value to your image width
    }
</script>
