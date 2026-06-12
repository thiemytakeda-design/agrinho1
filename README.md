html, body {
  margin: 0;
  padding: 0;
}
canvas {
  display: block;
} 
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Inter', sans-serif;
    line-height: 1.6;
    color: #333;
}

.container {
    max-width: 1280px;
    margin: 0 auto;
    padding: 0 20px;
}

/* Navbar */
.navbar {
    background: rgba(255, 255, 255, 0.97);
    position: fixed;
    top: 0;
    width: 100%;
    z-index: 1000;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
}

.logo h2 {
    color: #d32f2f;
    font-family: 'Playfair Display', serif;
}

.nav-links {
    display: flex;
    list-style: none;
    gap: 2rem;
}

.nav-links a {
    text-decoration: none;
    color: #222;
    font-weight: 500;
}

.nav-links a:hover {
    color: #d32f2f;
}

/* Hero */
.hero {
    height: 100vh;
    background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.75)), 
                url('https://images.unsplash.com/photo-1625246333195-78d9c38ad6c8?w=2000') center/cover no-repeat;
    display: flex;
    align-items: center;
    text-align: center;
    color: white;
}

.hero h1 {
    font-size: 4.2rem;
    line-height: 1.1;
    margin-bottom: 1rem;
}

.highlight {
    color: #ffeb3b;
    font-style: italic;
}

.slogan {
    font-size: 1.6rem;
    margin: 1.5rem 0;
    color: #ffccbc;
}

/* Alerta */
.alert {
    background: #d32f2f;
    color: white;
    text-align: center;
    padding: 20px 0;
    font-weight: 600;
}

/* Botão */
.btn-primary {
    background: #d32f2f;
    color: white;
    padding: 16px 40px;
    border: none;
    border-radius: 50px;
    font-size: 1.2rem;
    font-weight: 600;
    text-decoration: none;
    display: inline-block;
    transition: 0.4s;
}

.btn-primary:hover {
    background: #b71c1c;
    transform: translateY(-5px);
}

/* Sections */
.section {
    padding: 100px 0;
}

.bg-light {
    background-color: #f8f9fa;
}

.section-title {
    text-align: center;
    margin-bottom: 4rem;
}

.section-title h2 {
    font-size: 3rem;
    color: #d32f2f;
}

/* Stats */
.stats-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
    text-align: center;
}

.stat {
    background: white;
    padding: 2rem;
    border-radius: 16px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
}

.stat.red h3 {
    color: #d32f2f;
    font-size: 3.5rem;
}

/* Info Grid */
.info-grid {
    display: grid
