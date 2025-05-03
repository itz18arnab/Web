
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Samosé</title>
<script src="https://cdn.tailwindcss.com/3.4.16"></script>
<script>tailwind.config={theme:{extend:{colors:{primary:'#e67e22',secondary:'#2ecc71'},borderRadius:{'none':'0px','sm':'4px',DEFAULT:'8px','md':'12px','lg':'16px','xl':'20px','2xl':'24px','3xl':'32px','full':'9999px','button':'8px'}}}}</script>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.6.0/remixicon.min.css">
<style>
:where([class^="ri-"])::before { content: "\f3c2"; }
body {
font-family: 'Poppins', sans-serif;
scroll-behavior: smooth;
background-color: #f9f5f0;
}
.playfair {
font-family: 'Playfair Display', serif;
}
.hero-section {
background-image: linear-gradient(to right, rgba(249, 245, 240, 0.8), rgba(249, 245, 240, 0.6)), url('https://readdy.ai/api/search-image?query=Professional%2520food%2520photography%2520of%2520two%2520perfectly%2520golden%2520crispy%2520samosas%2520artistically%2520placed%2520in%2520an%2520elegant%2520white%2520ceramic%2520bowl%2C%2520garnished%2520with%2520fresh%2520vibrant%2520green%2520cabbage%2520leaves%2520and%2520colorful%2520vegetables%2520in%2520the%2520bottom%2520left.%2520The%2520composition%2520features%2520dramatic%2520lighting%2C%2520creating%2520beautiful%2520shadows%2520and%2520highlights%2520that%2520emphasize%2520the%2520texture%2520of%2520the%2520samosas.%2520Shot%2520on%2520a%2520clean%2C%2520minimal%2520background%2520with%2520warm%2520tones&width=1920&height=800&seq=1006&orientation=landscape');
background-size: cover;
background-position: center;
min-height: 800px;
display: flex;
align-items: center;
}
.explore-section {
background-image: url('https://readdy.ai/api/search-image?query=Blurred%2520artistic%2520image%2520of%2520samosas%2520with%2520fresh%2520cabbage%2520in%2520a%2520white%2520ceramic%2520bowl%2520positioned%2520at%2520the%2520bottom%2520left.%2520The%2520image%2520has%2520a%2520clean%2C%2520vintage%2520aesthetic%2520with%2520soft%2520natural%2520lighting%2520and%2520a%2520neutral%2520beige%2520background%2520that%2520creates%2520an%2520elegant%2C%2520sophisticated%2520atmosphere&width=1200&height=800&seq=1002&orientation=landscape');
background-size: cover;
background-position: center;
}
.taste-section {
background-image: url('https://readdy.ai/api/search-image?query=Blurred%2520artistic%2520close-up%2520image%2520of%2520vibrant%2520red-orange%2520chutney%2520in%2520a%2520white%2520ceramic%2520bowl%2520on%2520a%2520wooden%2520table.%2520The%2520image%2520has%2520a%2520vintage%2520aesthetic%2520with%2520soft%2C%2520warm%2520lighting%2520creating%2520a%2520cozy%2520atmosphere.%2520The%2520background%2520is%2520neutral%2520and%2520slightly%2520out%2520of%2520focus%2520to%2520emphasize%2520the%2520rich%2520color%2520of%2520the%2520chutney&width=1200&height=800&seq=1003&orientation=landscape');
background-size: cover;
background-position: center;
}
.policy-section {
background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('https://readdy.ai/api/search-image?query=Aesthetic%2520blurred%2520image%2520of%2520Indian%2520spices%2520and%2520ingredients%2520arranged%2520on%2520a%2520dark%2520wooden%2520surface.%2520The%2520image%2520has%2520a%2520moody%2C%2520atmospheric%2520quality%2520with%2520low%2520lighting%2520that%2520creates%2520dramatic%2520shadows.%2520Subtle%2520hints%2520of%2520turmeric%2C%2520cumin%2C%2520and%2520coriander%2520are%2520visible%2C%2520creating%2520a%2520rich%2C%2520textured%2520background%2520that%2520evokes%2520the%2520essence%2520of%2520authentic%2520Indian%2520cuisine&width=1200&height=800&seq=1004&orientation=landscape');
background-size: cover;
background-position: center;
}
input:focus {
outline: none;
border-color: #e67e22;
}
.arrow {
position: relative;
}
.arrow:after {
content: '';
position: absolute;
width: 100px;
height: 2px;
background: #e67e22;
top: 50%;
right: -120px;
transform: translateY(-50%);
}
.arrow:before {
content: '';
position: absolute;
width: 10px;
height: 10px;
border-top: 2px solid #e67e22;
border-right: 2px solid #e67e22;
top: 50%;
right: -120px;
transform: translateY(-50%) rotate(45deg);
}
@media (max-width: 768px) {
.arrow:after, .arrow:before {
display: none;
}
}
</style>
</head>
<body>
<!-- Header -->
<header class="fixed top-0 left-0 w-full z-50 bg-transparent backdrop-blur-sm transition-all duration-300">
<div class="container mx-auto px-4 py-4 flex justify-between items-center">
<a href="#" class="text-3xl font-['Pacifico'] text-primary">Samosé</a>
<div class="flex items-center space-x-6">
<div class="w-10 h-10 flex items-center justify-center cursor-pointer hover:text-primary transition-colors">
<i class="ri-search-line ri-lg"></i>
</div>
<a href="#" class="w-10 h-10 flex items-center justify-center cursor-pointer hover:text-primary transition-colors">
<i class="ri-instagram-line ri-lg"></i>
</a>
<a href="#" class="w-10 h-10 flex items-center justify-center cursor-pointer hover:text-primary transition-colors">
<i class="ri-facebook-circle-line ri-lg"></i>
</a>
<div class="w-10 h-10 flex items-center justify-center cursor-pointer hover:text-primary transition-colors">
<i class="ri-more-2-line ri-lg"></i>
</div>
</div>
</div>
</header>
<!-- Hero Section -->
<section class="hero-section w-full">
<div class="container mx-auto px-4 py-20 w-full">
<div class="flex flex-col md:flex-row items-center w-full">
<div class="w-full md:w-1/2 mb-10 md:mb-0">
<h1 class="text-5xl md:text-7xl font-bold playfair mb-6 text-grey-800">Samosé</h1>
<p class="text-xl md:text-2xl mb-8 text-gray-700 max-w-lg">A perfect combination for the perfect one.</p>
<div class="mb-6">
<span class="text-2xl text-gray-500 line-through mr-3">₹500</span>
<span class="text-3xl font-bold text-primary">₹399</span>
</div>
<p class="text-lg text-gray-700 cursor-pointer hover:text-primary transition-colors">
Find out the offer for you →
<br><br>
<button class=" bg-primary text-white px-10 py-3 rounded-button text-lg font-medium hover:bg-opacity-90 transition-all whitespace-nowrap mb-8">Order</button>

</p>
</div>
</div>
</div>
</section>
<!-- Explore Section -->
<section class="explore-section py-20">
<div class="container mx-auto px-4">
<h2 class="text-4xl font-bold tracking-[.5em] text-center mb-16 text-gray-800">E X P L O R E</h2>
<div class="grid grid-cols-1 md:grid-cols-2 gap-10">
<div class="bg-white p-8 rounded shadow-lg">
<h3 class="text-2xl font-semibold mb-4 text-gray-800">Authentic Flavors</h3>
<p class="text-gray-700 mb-6">Our samosas are crafted using traditional recipes passed down through generations, ensuring an authentic taste experience with every bite.</p>
<div class="flex items-center">
<div class="w-12 h-12 flex items-center justify-center bg-primary bg-opacity-10 rounded-full mr-4">
<i class="ri-award-line ri-lg text-primary"></i>
</div>
<p class="text-gray-700">Premium quality ingredients</p>
</div>
</div>
<div class="bg-white p-8 rounded shadow-lg">
<h3 class="text-2xl font-semibold mb-4 text-gray-800">Handcrafted Excellence</h3>
<p class="text-gray-700 mb-6">Each samosa is meticulously handcrafted by our skilled chefs, ensuring perfect texture, flavor, and presentation every time.</p>
<div class="flex items-center">
<div class="w-12 h-12 flex items-center justify-center bg-primary bg-opacity-10 rounded-full mr-4">
<i class="ri-hand-heart-line ri-lg text-primary"></i>
</div>
<p class="text-gray-700">Made with love and care</p>
</div>
</div>
<div class="bg-white p-8 rounded shadow-lg">
<h3 class="text-2xl font-semibold mb-4 text-gray-800">Variety of Fillings</h3>
<p class="text-gray-700 mb-6">From classic potato and peas to innovative vegetable medleys and meat options, our diverse range of fillings caters to every palate.</p>
<div class="flex items-center">
<div class="w-12 h-12 flex items-center justify-center bg-primary bg-opacity-10 rounded-full mr-4">
<i class="ri-restaurant-line ri-lg text-primary"></i>
</div>
<p class="text-gray-700">Multiple flavors to choose from</p>
</div>
</div>
<div class="bg-white p-8 rounded shadow-lg">
<h3 class="text-2xl font-semibold mb-4 text-gray-800">Perfect Pairings</h3>
<p class="text-gray-700 mb-6">Enhance your samosa experience with our selection of homemade chutneys and dips, specially created to complement our samosas.</p>
<div class="flex items-center">
<div class="w-12 h-12 flex items-center justify-center bg-primary bg-opacity-10 rounded-full mr-4">
<i class="ri-goblet-line ri-lg text-primary"></i>
</div>
<p class="text-gray-700">Complementary chutneys included</p>
</div>
</div>
</div>
</div>
</section>
<!-- Taste Enchanter Section -->
<section class="taste-section py-20 relative">
<div class="container mx-auto px-4">
<div class="max-w-2xl mx-auto text-center">
<h2 class="text-4xl font-bold mb-8 text-gray-800 playfair relative inline-block arrow">Taste Enchanter</h2>
<p class="text-lg text-gray-700 mb-12">
Our samosas are more than just a snack – they're a culinary journey that transports you to the vibrant streets of India. Each crispy, golden triangle is filled with a perfect balance of spices and ingredients, creating a symphony of flavors that dance on your palate. Whether you're hosting a gathering or simply treating yourself, our samosas bring warmth and joy to every occasion.
</p>
<div class="grid grid-cols-1 md:grid-cols-3 gap-8">
<div class="bg-white p-6 rounded shadow-lg">
<div class="w-16 h-16 flex items-center justify-center bg-primary bg-opacity-10 rounded-full mx-auto mb-4">
<i class="ri-fire-line ri-2x text-primary"></i>
</div>
<h3 class="text-xl font-semibold mb-3 text-gray-800">Perfectly Spiced</h3>
<p class="text-gray-700">Expertly balanced spices that create a harmonious flavor profile without overwhelming heat.</p>
</div>
<div class="bg-white p-6 rounded shadow-lg">
<div class="w-16 h-16 flex items-center justify-center bg-primary bg-opacity-10 rounded-full mx-auto mb-4">
<i class="ri-leaf-line ri-2x text-primary"></i>
</div>
<h3 class="text-xl font-semibold mb-3 text-gray-800">Fresh Ingredients</h3>
<p class="text-gray-700">Locally sourced, seasonal ingredients that ensure maximum freshness and flavor in every bite.</p>
</div>
<div class="bg-white p-6 rounded shadow-lg">
<div class="w-16 h-16 flex items-center justify-center bg-primary bg-opacity-10 rounded-full mx-auto mb-4">
<i class="ri-heart-pulse-line ri-2x text-primary"></i>
</div>
<h3 class="text-xl font-semibold mb-3 text-gray-800">Health Conscious</h3>
<p class="text-gray-700">Options for baked samosas and health-focused fillings for the nutrition-minded customer.</p>
</div>
</div>
</div>
</div>
</section>
<!-- Policy Section -->
<section class="policy-section py-20">
<div class="container mx-auto px-4">
<h2 class="text-4xl font-bold mb-12 text-white text-center playfair">Policy</h2>
<div class="grid grid-cols-1 md:grid-cols-3 gap-8">
<div class="bg-white bg-opacity-90 p-8 rounded shadow-lg">
<div class="w-16 h-16 flex items-center justify-center bg-primary bg-opacity-10 rounded-full mb-6">
<i class="ri-truck-line ri-2x text-primary"></i>
</div>
<h3 class="text-xl font-semibold mb-4 text-gray-800">Delivery Policy</h3>
<ul class="text-gray-700 space-y-3">
<li class="flex items-start">
<i class="ri-check-line text-primary mr-2 mt-1"></i>
<span>Free delivery on orders above ₹999</span>
</li>
<li class="flex items-start">
<i class="ri-check-line text-primary mr-2 mt-1"></i>
<span>Delivery within 45 minutes or 10% off your next order</span>
</li>
<li class="flex items-start">
<i class="ri-check-line text-primary mr-2 mt-1"></i>
<span>Contactless delivery option available</span>
</li>
<li class="flex items-start">
<i class="ri-check-line text-primary mr-2 mt-1"></i>
<span>Temperature-controlled packaging for freshness</span>
</li>
</ul>
</div>
<div class="bg-white bg-opacity-90 p-8 rounded shadow-lg">
<div class="w-16 h-16 flex items-center justify-center bg-primary bg-opacity-10 rounded-full mb-6">
<i class="ri-refund-2-line ri-2x text-primary"></i>
</div>
<h3 class="text-xl font-semibold mb-4 text-gray-800">Refund Policy</h3>
<ul class="text-gray-700 space-y-3">
<li class="flex items-start">
<i class="ri-check-line text-primary mr-2 mt-1"></i>
<span>100% refund if you're not satisfied with the quality</span>
</li>
<li class="flex items-start">
<i class="ri-check-line text-primary mr-2 mt-1"></i>
<span>Report issues within 30 minutes of delivery</span>
</li>
<li class="flex items-start">
<i class="ri-check-line text-primary mr-2 mt-1"></i>
<span>Replacement option available for damaged items</span>
</li>
<li class="flex items-start">
<i class="ri-check-line text-primary mr-2 mt-1"></i>
<span>Refund processed within 3-5 business days</span>
</li>
</ul>
</div>
<div class="bg-white bg-opacity-90 p-8 rounded shadow-lg">
<div class="w-16 h-16 flex items-center justify-center bg-primary bg-opacity-10 rounded-full mb-6">
<i class="ri-shield-check-line ri-2x text-primary"></i>
</div>
<h3 class="text-xl font-semibold mb-4 text-gray-800">Quality Assurance</h3>
<ul class="text-gray-700 space-y-3">
<li class="flex items-start">
<i class="ri-check-line text-primary mr-2 mt-1"></i>
<span>FSSAI certified kitchen and ingredients</span>
</li>
<li class="flex items-start">
<i class="ri-check-line text-primary mr-2 mt-1"></i>
<span>Daily quality checks by our master chef</span>
</li>
<li class="flex items-start">
<i class="ri-check-line text-primary mr-2 mt-1"></i>
<span>Strict hygiene protocols followed by all staff</span>
</li>
<li class="flex items-start">
<i class="ri-check-line text-primary mr-2 mt-1"></i>
<span>Transparent kitchen policy - visit us anytime</span>
</li>
</ul>
</div>
</div>
</div>
</section>
<!-- About & Contact Section -->
<section class="py-20 bg-white">
<div class="container mx-auto px-4">
<div class="flex flex-col md:flex-row gap-12">
<div class="w-full md:w-1/2">
<h2 class="text-4xl font-bold mb-8 text-gray-800 playfair">About Us</h2>
<p class="text-gray-700 mb-6">
Welcome to Samosé – where tradition meets taste with a twist!

Proudly launched in the heart of Rampurhat, Samosé is redefining India’s favorite snack — the samosa — by infusing it with creativity, quality, and a modern touch. From classic potato fillings to exciting fusion flavors, every bite is crafted with love, hygiene, and bold inspiration.

Founded with the vision of bringing people together over crispy, flavorful samosas, we believe in celebrating culture, community, and culinary innovation. Whether you're grabbing a quick bite or sharing a box with friends, Samosé promises a delightful experience every time.

Join us on our journey from Rampurhat to the rest of the world — making the humble samosa a global star, one crunch at a time.</p>
<p class="text-gray-700 mb-6">
What started as a humble venture has now grown into a beloved brand with multiple locations across India. Despite our growth, we remain committed to our founding principles: using the finest ingredients, honoring traditional recipes, and creating food that brings joy to our customers.
</p>
<p class="text-gray-700">
Today, Samosé is more than just a food brand – we're a community that celebrates India's rich culinary heritage while embracing innovation and sustainability in everything we do.
</p>
</div>
<div class="w-full md:w-1/2 bg-gray-50 p-8 rounded shadow-lg">
<h2 class="text-4xl font-bold mb-8 text-gray-800 playfair">Stay Connected With Us</h2>
<form>
<div class="mb-6">
<label for="name" class="block text-gray-700 mb-2">Name</label>
<input type="text" id="name" class="w-full px-4 py-3 border border-gray-300 rounded focus:border-primary" placeholder="Your name">
</div>
<div class="mb-6">
<label for="mobile" class="block text-gray-700 mb-2">Mobile Number</label>
<input type="tel" id="mobile" class="w-full px-4 py-3 border border-gray-300 rounded focus:border-primary" placeholder="+91 98765 43210">
</div>
<div class="mb-6">
<label for="email" class="block text-gray-700 mb-2">Email</label>
<input type="email" id="email" class="w-full px-4 py-3 border border-gray-300 rounded focus:border-primary" placeholder="your.email@example.com">
</div>
<button type="submit" class="bg-primary text-white px-8 py-3 rounded-button font-medium hover:bg-opacity-90 transition-all whitespace-nowrap w-full">Submit</button>
</form>
</div>
</div>
</div>
</section>
<!-- Footer -->
<footer class="py-16 bg-gray-50">
<div class="container mx-auto px-4 text-center">
<h2 class="text-5xl font-['Pacifico'] text-primary mb-8">Thank You!!</h2>
<div class="flex justify-center space-x-8 mb-10">
<a href="#" class="w-12 h-12 flex items-center justify-center bg-primary bg-opacity-10 rounded-full hover:bg-opacity-20 transition-all">
<i class="ri-instagram-line ri-lg text-primary"></i>
</a>
<a href="#" class="w-12 h-12 flex items-center justify-center bg-primary bg-opacity-10 rounded-full hover:bg-opacity-20 transition-all">
<i class="ri-facebook-circle-line ri-lg text-primary"></i>
</a>
<a href="#" class="w-12 h-12 flex items-center justify-center bg-primary bg-opacity-10 rounded-full hover:bg-opacity-20 transition-all">
<i class="ri-twitter-line ri-lg text-primary"></i>
</a>
<a href="#" class="w-12 h-12 flex items-center justify-center bg-primary bg-opacity-10 rounded-full hover:bg-opacity-20 transition-all">
<i class="ri-whatsapp-line ri-lg text-primary"></i>
</a>
</div>
<p class="text-gray-600 mb-2">© 2025 Samosé. All rights reserved.</p>
<p class="text-gray-500 text-sm">
<a href="#" class="hover:text-primary transition-colors">Privacy Policy</a> •
<a href="#" class="hover:text-primary transition-colors">Terms of Service</a> •
<a href="#" class="hover:text-primary transition-colors">Cookie Policy</a>
</p>
<p class="text-gray-500 text-sm mt-8 text-right italic">See you soon!</p>
</div>
</footer>
<script>
document.addEventListener('DOMContentLoaded', function() {
const header = document.querySelector('header');
window.addEventListener('scroll', function() {
if (window.scrollY > 50) {
header.classList.add('bg-white', 'shadow-md');
header.classList.remove('bg-transparent');
} else {
header.classList.remove('bg-white', 'shadow-md');
header.classList.add('bg-transparent');
}
});
});
</script>
</body>
</html>
