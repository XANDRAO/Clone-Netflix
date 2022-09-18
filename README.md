# Clone-Netflix

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>
      Netflix Brasil - assistir séries online, assistir filmes online
    </title>
    <link rel="stylesheet" href="css/style.css" />
    <link rel="shortcut icon" href="favicon.ico" />
  </head>
  <body>
    <header class="header">
      <img src="https://user-images.githubusercontent.com/100946873/190888671-d0d1a6c1-3405-4bb7-ac9a-6e7e860e6ef8.svg" />
      <a href="#">Entrar</a>
    </header>
    <main class="main">
      <div class="main-child">
        <h1>Filmes, séries e muito mais. Sem limites.</h1>
        <span>Assista onde quiser. Cancele quando quiser.</span>
        <form class="form-cta">
          <input type="text" placeholder="Email" />
          <button>Vamos lá</button>
        </form>
        <p>
          Pronto para assistir? Informe seu email para criar ou reiniciar sua
          assinatura.
        </p>
      </div>
      <div class="gradient"></div>
    </main>
    <section class="section">
      <div class="container">
        <div class="grid">
          <div>
            <h1>Aproveite na TV.</h1>
            <p>
              Assista em Smart TVs, PlayStation, Xbox, Chromecast, Apple TV,
              aparelhos de Blu-ray e outros aparelhos.
            </p>
          </div>
          <div class="img-tv">
            <img src="https://user-images.githubusercontent.com/100946873/190888685-2091755e-2c21-46ba-9c06-f7a6a0750a67.png" alt="TV" />
            <video class="video-tv" autoplay playsinline muted loop>
              <source
                src="https://user-images.githubusercontent.com/100946873/190888666-b7b69ff1-4b58-4cab-952a-1f54393bbb0a.jpg"
                type="video/mp4"
              />
            </video>
          </div>
        </div>
      </div>
    </section>
    <section class="download section">
      <div class="container">
        <div class="grid">
          <div>
            <h1>Baixe séries para assistir offline.</h1>
            <p>
              Salve seus títulos favoritos e sempre tenha algo para assistir.
            </p>
          </div>
          <div class="img-tv">
            <img src="https://user-images.githubusercontent.com/100946873/190888666-b7b69ff1-4b58-4cab-952a-1f54393bbb0a.jpg" alt="El" />
          </div>
        </div>
      </div>
    </section>
    <section class="device-pile section">
      <div class="container">
        <div class="grid">
          <div>
            <h1>Assista quando quiser.</h1>
            <p>
              Assista no celular, tablet, smart TV ou notebook sem pagar a mais
              por isso.
            </p>
          </div>
          <div class="img-tv">
            <img src="https://user-images.githubusercontent.com/100946873/190888660-b7d7406a-5b5b-49c2-b8e1-915d3089dea9.png" alt="Device Pile" />
            <video class="video-tv" autoplay playsinline muted loop>
              <source
                src="https://user-images.githubusercontent.com/100946873/190888685-2091755e-2c21-46ba-9c06-f7a6a0750a67.png"
                type="video/mp4"
              />
            </video>
          </div>
        </div>
      </div>
    </section>
    <footer class="footer">
      <form class="form-cta">
        <input type="text" placeholder="Email" />
        <button>Vamos lá</button>
      </form>
      <p>Copyright © 2020 Netflix Brasil. Todos os direitos reservados.</p>
    </footer>
  </body>
</html>

* {
  margin: 0;
  padding: 0;
}

body {
  font-family: sans-serif;
  color: white;
}

img {
  display: block;
  max-width: 100%;
}

.container {
  max-width: 1130px;
  margin: 0 auto;
}

.header {
  position: absolute;
  z-index: 100;
  width: 100%;
  display: flex;
  justify-content: space-between;
  max-width: 1790px;
  top: 28px;
  left: 56px;
}

.header a {
  display: inline-block;
  background: #e50914;
  color: white;
  align-self: flex-start;
  padding: 8px 18px;
  text-decoration: none;
  border-radius: 3px;
}

.main {
  padding-top: 4rem;
  height: 785px;
  background: url("../img/bg.jpg") center;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  position: relative;
  box-sizing: border-box;
}

.main-child {
  z-index: 1;
  display: grid;
  justify-items: center;
}

.main h1 {
  font-size: 64px;
  max-width: 510px;
}

.main span {
  font-size: 26px;
  margin-top: 10px;
}

.form-cta {
  display: grid;
  grid-template-columns: 500px 250px;
  margin-top: 30px;
  margin-bottom: 10px;
}

.form-cta input {
  padding: 20px 10px;
  font-size: 18px;
  font-family: sans-serif;
}

.form-cta button {
  background: #e50914;
  outline: none;
  border: none;
  color: white;
  font-size: 30px;
  text-transform: uppercase;
  cursor: pointer;
}

.form-cta button::after {
  content: "";
  display: inline-block;
  width: 10px;
  height: 20px;
  background: url("../img/seta.svg");
  margin-left: 20px;
}

.form-cta button:hover {
  background: #f40612;
}

.main p {
  font-size: 19px;
}

.gradient {
  background: rgba(0, 0, 0, 0.4);
  background-image: linear-gradient(
    to top,
    rgba(0, 0, 0, 0.8) 0,
    rgba(0, 0, 0, 0) 60%,
    rgba(0, 0, 0, 0.8) 100%
  );
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
}

.section {
  background: black;
  padding: 3rem 0;
  border-top: 8px solid #222;
}

.section h1 {
  font-size: 50px;
  margin-bottom: 16px;
}

.section p {
  font-size: 26px;
}

.grid {
  display: grid;
  grid-template-columns: 1.1fr 1fr;
  align-items: center;
}

.img-tv {
  position: relative;
}

.img-tv img {
  position: relative;
  z-index: 1;
}

.video-tv {
  position: absolute;
  width: 400px;
  top: 80px;
  left: 70px;
}

.download .grid > div:first-child {
  order: 2;
}

.download .img-tv {
  order: 1;
}

.device-pile .video-tv {
  width: 340px;
  top: 45px;
  left: 100px;
}

.footer .form-cta {
  margin-top: 0;
}

.footer {
  padding: 4rem 0 2rem 0;
  border-top: 8px solid #222;
  background: black;
  text-align: center;
  display: grid;
  justify-items: center;
}

.footer p {
  margin-top: 2rem;
  color: #757575;
  font-size: 13px;
}
