---
description: >-
  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
  incididunt ut labore et dolore magna aliqua. Quis risus sed vulputate odio.
  Ultrices in iaculis nunc sed augue. Libero en
---

# Experiment 1

<style>
    .image-container {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-around;
    }

    .image-container div {
        flex: 0 0 50%; /* This will make each div take up 50% of the width */
        box-sizing: border-box; /* Include padding and borders in the element's total width and height */
        padding: 10px; /* Add some space around each image */
        text-align: center;
    }

    .image-container img {
        max-width: 100%;
        height: auto;
        border-radius: 15px;
    }

    @media (max-width: 600px) {
        .image-container div {
            flex: 0 0 100%; /* Full width on smaller screens */
        }
    }
</style>

<div class="image-container">
    <div>
        <img src="1.png" alt="Image 1">
        <p>Text for Image 1</p>
    </div>
    <div>
        <img src="2.png" alt="Image 2">
        <p>Text for Image 2</p>
    </div>
    <div>
        <img src="3.png" alt="Image 3">
        <p>Text for Image 3</p>
    </div>
    <div>
        <img src="4.png" alt="Image 4">
        <p>Text for Image 4</p>
    </div>
</div>
