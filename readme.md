# PDF Database (cooler title here)

<!-- link to actual site https://conradbuck.github.io/simple-link-tree/ -->

Welcome to the PDF Database! Here is a collection of pictures and pdfs.

<style>
  .gallery {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    margin: 20px 0;
  }
  .gallery img {
    width: 100%;
    height: auto;
    aspect-ratio: 1 / 1; /* Forces images to be square */
    object-fit: cover;   /* Ensures the image is cropped appropriately */
    border: 1px solid #ccc;
    border-radius: 8px;
    box-shadow: 2px 2px 6px rgba(0, 0, 0, 0.1);
  }
</style>

<div class="gallery">
  <div class="gallery-item">
    <a href="documents/document1.pdf" target="_blank">    <!--## file location of pdf in github repo ##-->
      <img src="images/image1.jpg" alt="Topic 1 Preview"> <!--## file location of preview image within github repo ##-->
      <p>Cool stuff about Ni-20Cr machining</p>		  <!--## name of hyperlink ##-->
    </a>
  </div>
  <div class="gallery-item">
    <a href="https://again.framer.ai/" target="_blank">
      <img src="images/preview2.jpg" alt="Topic 2 Preview">
      <p>Link to external webpage about my lights</p>
    </a>
  </div>
  <div class="gallery-item">
    <a href="https://forms.gle/uWzb2qyrie8GGCes7" target="_blank">
      <img src="images/preview3.jpg" alt="Topic 3 Preview">
      <p>Join our mailing list (google forms link)</p>
    </a>
  </div>
  <div class="gallery-item">
    <a href="https://drive.google.com/file/d/1mzleKG7kpYIQpbF11vh0I8zP9OhVkrVN/view?usp=sharing" target="_blank">
      <img src="images/preview4-ship.jpg" alt="Topic 4 Preview">
      <p>Link to document on google drive</p>
    </a>
  </div>
  <div class="gallery-item">
    <a href="https://cdn-shop.adafruit.com/datasheets/WS2811.pdf" target="_blank">
      <img src="images/preview5.jpg" alt="Topic 5 Preview">
      <p>Link to pdf on random website</p>
    </a>
  </div>
<!-- commenting out image placement 6 to leave as references -->
<!--
  <div class="gallery-item">
    <a href="documents/document6.pdf" target="_blank">
      <img src="images/preview6.jpg" alt="Topic 6 Preview">
      <p>Topic 6</p>
    </a>
  </div>
-->

</div>

<!--

### Instructions for Contribution
1. Add your PDF document to the `documents` directory.
2. Add a preview image to the `images` directory.
3. Update this `README.md` file to include your new document and image in the format above.

-->
