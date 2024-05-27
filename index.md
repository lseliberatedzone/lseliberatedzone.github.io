---
layout: default
---

<h1 style="text-align: center;">LSE LIBERATED ZONE</h1>

On May 14th, the eve of the 76th anniversary of the Nakba, we started out encampment for Palestine. We are currentely occupying the the ground floor of the London School of Economics' (LSE) Bloom Building (formerly the Marshall Building), in ongoing protest at the university's financial complicity in the genocide of the Palestinian people. Central amongst the our demands is the issue of divestment. In line with LSESU Palestine Society's 116-page 'Assests in Apartheid Report' we call on the university to divest its £89 million worth of investments in crimes Against the Palestinian people, the arms trade, fossil fuels, and the financing of such egregious activities.

<button style="display: block; margin: 0 auto;"><a href="https://lsepalestine.github.io/documents/LSESUPALESTINE-Assets-in-Apartheid-2024-Web.pdf" target="_blank"><strong style="color: black;">Read divestment report</strong></a></button>

---

<h2 style="text-align: center;">OUR DEMANDS</h2>

<iframe src="https://lseliberatedzone.github.io/document/demands.pdf" width="100%" height="600px">
This browser does not support PDFs. Please download the PDF to view it: 
<a href="https://lseliberatedzone.github.io/document/demands.pdf">Download PDF</a>.
</iframe>

---

<h2 style="text-align: center;">EVENTS</h2>

![Event Image 1]({{ '/assets/img/event.jpg' | relative_url }} "Event Image 1")

---
<h2 style="text-align: center;">OUR DEMANDS</h2>

<div class="carousel">
    <button class="prev" onclick="moveSlide(-1)">❮</button>
    <div class="carousel-container">
        <iframe src="https://lseliberatedzone.github.io/document/1.PNG" class="carousel-slide"></iframe>
        <iframe src="https://lseliberatedzone.github.io/document/2.PNG" class="carousel-slide"></iframe>
        <iframe src="https://lseliberatedzone.github.io/document/3.PNG" class="carousel-slide"></iframe>
        <iframe src="https://lseliberatedzone.github.io/document/4.PNG" class="carousel-slide"></iframe>
        <iframe src="https://lseliberatedzone.github.io/document/5.PNG" class="carousel-slide"></iframe>
        <iframe src="https://lseliberatedzone.github.io/document/6.PNG" class="carousel-slide"></iframe>
        <iframe src="https://lseliberatedzone.github.io/document/7.PNG" class="carousel-slide"></iframe>
        <iframe src="https://lseliberatedzone.github.io/document/8.PNG" class="carousel-slide"></iframe>
        <iframe src="https://lseliberatedzone.github.io/document/9.PNG" class="carousel-slide"></iframe>
        <iframe src="https://lseliberatedzone.github.io/document/10.PNG" class="carousel-slide"></iframe>
    </div>
    <button class="next" onclick="moveSlide(1)">❯</button>
</div>

<style>
    .carousel {
        position: relative;
        width: 100%;
        max-width: 800px;
        margin: auto;
        overflow: hidden;
    }

    .carousel-container {
        display: flex;
        transition: transform 0.5s ease-in-out;
    }

    .carousel-slide {
        min-width: 100%;
        height: 600px;
        border: none; /* Remove iframe borders */
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
        document.querySelector('.carousel-container').style.transform = `translateX(${-slideIndex * 100}%)`;
    }
</script>
