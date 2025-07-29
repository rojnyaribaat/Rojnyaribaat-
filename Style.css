/* style.css - Professional News Site */

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Arial', sans-serif;
}

body {
  background: #f5f5f5;
  color: #333;
  line-height: 1.6;
}

/* Header */
header {
  background: #c4002f;
  color: #fff;
  padding: 15px;
  text-align: center;
}
header .logo {
  font-size: 28px;
  font-weight: bold;
}
header nav {
  margin-top: 10px;
}
header nav a {
  color: #fff;
  text-decoration: none;
  margin: 0 10px;
  font-weight: bold;
}
header nav a:hover {
  text-decoration: underline;
}

/* Breaking News */
.breaking-news {
  background: #ffcc00;
  display: flex;
  align-items: center;
  overflow: hidden;
}
.breaking-news .ticker-title {
  background: #c4002f;
  color: #fff;
  padding: 8px 12px;
  font-weight: bold;
}
.breaking-news .ticker {
  white-space: nowrap;
  animation: scrollText 20s linear infinite;
  padding: 8px;
  font-weight: bold;
  color: #000;
}
@keyframes scrollText {
  0% { transform: translateX(100%); }
  100% { transform: translateX(-100%); }
}

/* Ad Banner */
.ad-banner {
  background: #e0e0e0;
  text-align: center;
  padding: 15px;
  margin: 20px auto;
  width: 90%;
  border: 1px dashed #aaa;
}

/* Section Titles */
section h2 {
  width: 90%;
  margin: 20px auto 10px;
  border-left: 5px solid #c4002f;
  padding-left: 10px;
  font-size: 22px;
}

/* News Grid */
.news-grid {
  width: 90%;
  margin: auto;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 20px;
}

.news-grid article {
  background: #fff;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  transition: 0.3s;
}

.news-grid article:hover {
  transform: translateY(-5px);
}

.news-grid img {
  width: 100%;
  height: 180px;
  object-fit: cover;
}

.news-grid h3 {
  font-size: 18px;
  padding: 10px;
  color: #222;
}

.news-grid p {
  padding: 0 10px 15px;
  color: #555;
  font-size: 14px;
}

/* Footer */
footer {
  background: #222;
  color: #ccc;
  text-align: center;
  padding: 20px;
  margin-top: 30px;
}
footer a {
  color: #ffcc00;
  text-decoration: none;
  margin: 0 5px;
}
footer a:hover {
  text-decoration: underline;
}

/* Responsive */
@media (max-width: 600px) {
  header nav {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
  }
  .breaking-news .ticker-title {
    font-size: 14px;
  }
  .news-grid img {
    height: 150px;
  }
}