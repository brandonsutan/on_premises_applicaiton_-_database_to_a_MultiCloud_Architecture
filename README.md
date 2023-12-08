<details>
<summary>My carousel image</summary>
<script>
var keepTime = 2000; // time to keep each image in milliseconds
var images = ["/img/AWS_IAMusers.jpeg", "/img/AWS_s3bucket.jpeg", "img/destroy.jpeg", "/img/GKE_cluster.jpeg", "/img/GKE_deployment.jpeg", "/img/homepage.jpeg", "/img/recordspage.jpeg", "/img/SQLdatabse.jpeg"]; // array of image URLs
var index = 0; // index of the current image
var img = document.createElement("img"); // create an image element
img.src = images[index]; // set the initial image source
img.alt = "My carousel image"; // set the alternative text for the image
img.style.width = "500px"; // set the image width
img.style.height = "300px"; // set the image height
document.body.appendChild(img); // append the image to the document body
function updateCarousel() {
  index = (index + 1) % images.length; // increment the index and wrap around
  img.src = images[index]; // update the image source
  setTimeout(updateCarousel, keepTime); // call this function again after keepTime
}
setTimeout(updateCarousel, keepTime); // start the carousel
</script>
</details>
