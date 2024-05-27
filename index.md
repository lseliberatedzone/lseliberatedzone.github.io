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

<div class="slider">
    <iframe src="https://lseliberatedzone.github.io/document/1.PNG" class="slide"></iframe>
    <iframe src="https://lseliberatedzone.github.io/document/2.PNG" class="slide"></iframe>
    <iframe src="https://lseliberatedzone.github.io/document/3.PNG" class="slide"></iframe>
    <iframe src="https://lseliberatedzone.github.io/document/4.PNG" class="slide"></iframe>
    <iframe src="https://lseliberatedzone.github.io/document/5.PNG" class="slide"></iframe>
    <iframe src="https://lseliberatedzone.github.io/document/6.PNG" class="slide"></iframe>
    <iframe src="https://lseliberatedzone.github.io/document/7.PNG" class="slide"></iframe>
    <iframe src="https://lseliberatedzone.github.io/document/8.PNG" class="slide"></iframe>
    <iframe src="https://lseliberatedzone.github.io/document/9.PNG" class="slide"></iframe>
    <iframe src="https://lseliberatedzone.github.io/document/10.PNG" class="slide"></iframe>
</div>

<style>
    .slider {
        position: relative;
        width: 100%;
        height: 600px;
        overflow: hidden;
    }

    .slide {
        position: absolute;
        width: 100%;
        height: 100%;
        transition: opacity 1s ease-in-out;
        opacity: 0;
        border: none; /* Remove iframe borders */
    }

    .slide.active {
        opacity: 1;
    }
</style>

<script>
    let currentIndex = 0;
    const slides = document.querySelectorAll('.slide');

    function showSlide(index) {
        slides.forEach((slide, i) => {
            slide.classList.remove('active');
            if (i === index) {
                slide.classList.add('active');
            }
        });
    }

    function nextSlide() {
        currentIndex = (currentIndex + 1) % slides.length;
        showSlide(currentIndex);
    }

    setInterval(nextSlide, 3000); // Change slide every 3 seconds

    document.addEventListener('DOMContentLoaded', () => {
        showSlide(currentIndex);
    });
</script>
