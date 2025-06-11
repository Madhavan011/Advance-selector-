# Advance-selector-
/* General Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background-color: #f4f4f4;
  color: #222;
  padding: 20px;
  line-height: 1.6;
}

/* Skip link for accessibility */
.skip-link {
  position: absolute;
  left: -999px;
  top: auto;
  width: 1px;
  height: 1px;
  overflow: hidden;
}

.skip-link:focus {
  position: static;
  width: auto;
  height: auto;
  margin-bottom: 10px;
  background: #222;
  color: #fff;
  padding: 10px;
  display: inline-block;
  z-index: 1000;
}

/* Header */
header {
  background-color: #005f73;
  color: #fff;
  padding: 20px;
  text-align: center;
  border-radius: 8px;
}

nav {
  margin-top: 10px;
}

nav a {
  color: #fff;
  margin: 0 10px;
  text-decoration: none;
  font-weight: bold;
}

nav a:hover {
  text-decoration: underline;
}

/* Main Content */
main {
  background: #ffffff;
  padding: 20px;
  margin-top: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  max-width: 800px;
  margin-left: auto;
  margin-right: auto;
}

h2 {
  color: #0a9396;
  margin-bottom: 10px;
}

/* Footer */
footer {
  margin-top: 30px;
  background-color: #005f73;
  color: #fff;
  padding: 15px;
  text-align: center;
  border-radius: 8px;
}

/* Responsive */
@media (max-width: 600px) {
  nav a {
    display: block;
    margin: 10px 0;
  }

  main {
    padding: 10px;
  }
}
