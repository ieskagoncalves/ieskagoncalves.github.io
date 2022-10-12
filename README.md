* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: "Noto Sans", sans-serif;
  text-decoration: none;
  list-style: none;
}

body {
  box-sizing: border-box;
}

header {
  align-items: center;
  width: 100%;
  height: 0 auto;
}

nav {
  max-width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 40px 20px;
}

.logo {
  padding: 10px;
}

ul {
  display: flex;
  align-items: center;
  gap: 20px;
  padding: 10px;
}

ul li a {
  color: #363636;
  font-family: "Noto Sans", sans-serif;
  font-weight: 500;
  font-size: 1.1rem;
  padding: 5px 10px;
}

/* Start Menu */
.introducao {
  max-width: 1200px;
  margin: 0 auto;
  padding: 10px;
  display: grid;
  grid-template-columns: 1fr 2fr;
  align-items: center;
  gap: 100px;
}

.img-left img {
  width: 320px;
  display: block;
  padding: 10px;
}

.text-right {
  grid-column: 2;
}

.text-right h1 {
  font-size: 4.3rem;
  line-height: 1.125;
  margin-bottom: 30px;
  position: relative;
}

.text-right h1::before {
  content: "";
  display: block;
  width: 130px;
  height: 100px;
  background: url("../img/detalhe.svg") no-repeat center;
  position: relative;
  top: 90px;
  right: 30px;
  z-index: -1;
}

.text-right p {
  color: #545454;
  font-size: 1.5rem;
}

/* Start Experiência */
.experiencia {
  max-width: 1200px;
  height: 100vh;
  margin: 0 auto;
  padding: 10px;
  display: grid;
  grid-template-columns: 1fr 2fr;
  align-items: center;
  gap: 100px;
}

.subtitulo {
  color: #e0e0e0;
  font-size: 7.5rem;
  word-break: break-all;
  line-height: 1.1;
}

.experiencia-text {
  color: #3f3f3f;
  font-size: 1.2rem;
  max-width: 40ch;
  margin-bottom: 60px;
}

.empresa {
  background: #f5f5f5;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 10px 20px;
  padding: 10px;
  margin-bottom: 20px;
  border-radius: 4px;
  position: relative;
}

.empresa::before {
  content: "";
  position: absolute;
  text-align: right;
  left: -4px;
  top: 10px;
  width: 4px;
  height: 20px;
  background: linear-gradient(#b6f829, #67dd0a);
}

.empresa-ano {
  position: absolute;
  top: 10px;
  left: -100px;
  width: 80px;
  text-align: right;
}

.empresa-titulo {
  font-size: 1.125rem;
  line-height: 1.1;
  font-weight: bold;
  padding-left: 10px;
}

.empresa-text {
  font-size: 0.9rem;
}

.empresa-habilidades {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.empresa-habilidades li {
  background-color: #fff;
  padding: 5px 10px;
  font-size: 0.9rem;
}

/* Start Formacao */
.formacao{
  background-color: #141414;
  max-width: 100%;
  height: 100vh;
  margin: 0 auto;
  padding: 30px;
  display: grid;
  grid-template-columns: 1fr 2fr;
  align-items: center;
  gap: 100px;
  position: relative;
}

.subtitulo-formacao {
  color: #000000;
  font-size: 7.5rem;
  word-break: break-all;
  line-height: 1.1;
}

.formacao-text {
  color: #a3a3a3;
  font-size: 1.2rem;
  max-width: 40ch;
  margin-bottom: 60px;
}

.formacao-text strong{
  color: #ffffff;
}

.faculdade-lista{
  display: grid;
  grid-template-columns: repeat(3, 1fr);
}

.faculdade{
  background-color: #000000;
  display: flex;
  flex-direction: column;
  padding: 20px;
  height: 200px;
}


.faculdade-text{
  color: #a3a3a3;
  font-size: 0.875rem;
  text-transform: uppercase;
  padding-bottom: 10px;
}

.faculdade-curso{
  font-weight: bold;
  flex: 1;
  font-size: 1.125rem;
  line-height: 1.4;
  margin-bottom: 40px;
  position: relative;
  color: #f5f5f5;
}

.faculdade-curso::before{
  content: "";
  position: absolute;
  text-align: right;
  width: 4px;
  height: 20px;
  left: -24px;
  background: linear-gradient(#b6f829, #67dd0a);
}