body {
  margin: 0;
  font-family: 'Inter', sans-serif;
  background: #f7f7f7;
  color: #333;
}

header {
  background: white;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  padding: 1rem 2rem;
  position: sticky;
  top: 0;
  z-index: 1000;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav h1 {
  font-family: 'Great Vibes', cursive;
  font-size: 2rem;
  color: darkmagenta;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 1.5rem;
}

nav a {
  text-decoration: none;
  font-weight: bold;
  color: #333;
}

section {
  padding: 4rem 2rem;
  max-width: 800px;
  margin: auto;
}

.poem {
  background: #fff;
  padding: 1.5rem;
  margin: 1rem 0;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.signature {
  text-align: right;
  font-family: 'Great Vibes', cursive;
  font-size: 1.2rem;
  margin-top: 1rem;
}

footer {
  text-align: center;
  padding: 2rem;
  background: #eee;
}
