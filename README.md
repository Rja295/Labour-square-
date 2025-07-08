body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: #f5f5f5;
  color: #333;
}
header .hero {
  position: relative;
}
header img {
  width: 100%;
  height: auto;
  display: block;
}
.overlay {
  position: absolute;
  top: 0; left: 0;
  width: 100%; height: 100%;
  background: rgba(0, 0, 64, 0.5);
  color: white;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 2rem;
}
.overlay h1 {
  font-size: 2.5rem;
}
.overlay p {
  font-size: 1.2rem;
}
.container {
  padding: 2rem;
  max-width: 800px;
  margin: auto;
}
form {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}
form input, form button {
  padding: 0.8rem;
  font-size: 1rem;
}
button {
  background: #007bff;
  color: white;
  border: none;
}
footer {
  background: #003366;
  color: white;
  text-align: center;
  padding: 1rem;
}