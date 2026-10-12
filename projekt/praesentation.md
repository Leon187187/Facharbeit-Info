---
marp: true
paginate: true
style: |
  section {
    padding: 40px;
  }
  section.cover {
    position: relative;
    overflow: hidden;
    isolation: isolate;
    background-color: #82b0e5;
  }
  .cover-background {
    position: absolute;
    inset: 0;
    z-index: -1;
    pointer-events: none;
  }
  .cover-background img {
    position: absolute;
    width: 180px;
    height: 180px;
    object-fit: contain;
  }
  .cover-background img:nth-child(1) {
    top: 8%;
    left: 8%;
  }
  .cover-background img:nth-child(2) {
    bottom: 8%;
    left: 50%;
    transform: translateX(-50%);
  }
  .cover-background img:nth-child(3) {
    top: 8%;
    right: 8%;
  }
  .titel {
    position: absolute;
    inset: 0;
    z-index: 1;
    display: grid;
    place-items: center;
    box-sizing: border-box;
    padding: 80px;
    text-align: center;
  }
  .autor {
    position: absolute;
    bottom: 24px;
    left: 40px;
    margin: 0;
    color: #506579;
    font-family: inherit;
    font-size: 20px;
  }
---

<!-- _class: cover -->

<div class="cover-background" aria-hidden="true">
  <img src="bilder/WhatsApp.svg.png" alt="">
  <img src="bilder/Telegram.svg.png" alt="">
  <img src="bilder/Signal.svg.png" alt="">
</div>

<div class="titel">

# Welcher Messengerdienst bietet den besten Schutz für meine privaten Daten?

<p class="autor">Leon Weber</p>

</div>