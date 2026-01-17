
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', sans-serif;
}

body {
    background: url("img/bg.jpg") no-repeat center/cover;
    color: white;
}

.bg-overlay {
    background: rgba(0,0,0,0.75);
    min-height: 100vh;
}

/* Navbar */
.navbar {
    padding: 15px;
    text-align: center;
    background: #0b0b0b;
}

.navbar span {
    color: #fbc531;
}

/* Game Menu */
.games {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 12px;
    padding: 15px;
}

.game-card {
    background: #111;
    border-radius: 12px;
    overflow: hidden;
    cursor: pointer;
    transition: 0.3s;
}

.game-card img {
    width: 100%;
    height: 120px;
    object-fit: cover;
}

.game-card p {
    padding: 8px;
    text-align: center;
    font-weight: bold;
}

.game-card:hover {
    transform: scale(1.05);
    box-shadow: 0 0 15px #fbc531;
}

/* Form */
.form {
    background: #111;
    margin: 15px;
    padding: 15px;
    border-radius: 12px;
}

.form h2 {
    margin-bottom: 10px;
    color: #fbc531;
}

.form input,
.form select {
    width: 100%;
    padding: 12px;
    margin-bottom: 10px;
    border-radius: 6px;
    border: none;
}

.form button {
    width: 100%;
    padding: 12px;
    background: linear-gradient(90deg, #fbc531, #e1a100);
    border: none;
    border-radius: 6px;
    font-size: 16px;
    font-weight: bold;
    cursor: pointer;
}

/* Footer */
footer {
    text-align: center;
    padding: 10px;
    font-size: 14px;
}
