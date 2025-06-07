# Webi

body {
  margin: 0;
  font-family: 'Open Sans', sans-serif;
  background-color: #f4f6f8;
  color: #1a1a1a;
}

header {
  background: url('header-bg.jpg') center/cover no-repeat;
  color: white;
  padding: 80px 20px;
  text-align: center;
}

header h1 {
  font-family: 'Poppins', sans-serif;
  font-size: 2.8em;
  margin: 0;
}

header p {
  font-size: 1.2em;
  margin: 10px 0 20px;
}

nav {
  background: #ffffff;
  padding: 10px 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.05);
}

nav a {
  color: #004aad;
  text-decoration: none;
  margin: 0 10px;
  font-weight: 600;
}

nav a:hover {
  text-decoration: underline;
}

section {
  padding: 40px 20px;
  max-width: 1000px;
  margin: auto;
}

h2 {
  color: #004aad;
  font-family: 'Poppins', sans-serif;
}

ul {
  padding-left: 20px;
}

.features {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
}

.features div {
  background: #ffffff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.05);
}

footer {
  background-color: #1a1a1a;
  color: white;
  text-align: center;
  padding: 20px;
}

.contact a {
  color: #004aad;
  text-decoration: none;
}

