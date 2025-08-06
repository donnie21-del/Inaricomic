# Inaricomic
My original comic – Inari: The Celestial Bloom
<img src="images/comingsoon.jpg" alt="Coming Soon">
<h1>Chapter 1 Coming Soon!</h1>
<p>Check back later to witness Inari’s first steps on the giants.</p>
body {
  background-color: #0a0a0a;
  color: #f9f9f9;
  font-family: 'Segoe UI', sans-serif;
  margin: 0;
  padding: 0;
  text-align: center;
}

header {
  background: linear-gradient(to right, #911414, #3d0000);
  padding: 30px 20px;
}

header h1 {
  margin: 0;
  font-size: 2.8em;
  color: gold;
}

nav {
  margin-top: 15px;
}

nav a {
  margin: 0 15px;
  color: #f9f9f9;
  text-decoration: none;
  font-weight: bold;
  transition: color 0.3s ease;
}

nav a:hover {
  color: crimson;
  text-shadow: 0 0 5px gold;
}

.fade-in {
  opacity: 0;
  animation: fadeIn 2s ease forwards;
}

@keyframes fadeIn {
  to { opacity: 1; }
}

img {
  width: 100%;
  max-width: 700px;
  height: auto;
  margin: 20px auto;
  display: block;
}

#loader {
  position: fixed;
  width: 100%;
  height: 100%;
  background: #0a0a0a;
  color: gold;
  font-size: 2em;
  display: flex;
  align-items: center;
  justify-content: center;
  z-index: 9999;
}
