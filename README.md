# portifolio

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Meu Portfólio</title>

<style>
    body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background-color: #333;
  color: #ffffff;
  text-align: center;
  padding: 20px 0;
}

section {
  padding: 15px;
  background-color: gray;
}

form {
  display: flex;
  flex-direction: column;
}

input,
textarea {
  margin-bottom: 10px;
  padding: 5px;
}

button {
  padding: 8px 20px;
  background-color: #333;
  color: #fff;
  border: none;
  cursor: pointer;
}

button:hover {
  background-color: #555;
}

</style>
  
</head>
<body>
  <header>
    <h1>Guilherme Fuchter dos Santos</h1>
  </header>
  
  <section id="about">
    <h2>Sobre mim</h2>
    <p> fazendo o curso da stackx<p>
  </section>
  
  <section id="projects">
    <h2>Atualmente</h2>
    <div class="project">
      <h3>Trabalho</h3>
      <p>Estagiario na empresa Softplan</p>
    </div>
    <div class="project">
      <h3>Estudo</h3>
      <p>Cursando engenharia de software<p>
    </div>
  </section>
  
  <section id="contact">
    <h2>Entre em Contato</h2>
    <form id="contact-form">
      <input type="text" id="name" placeholder="Nome" required>
      <input type="email" id="email" placeholder="Email" required>
      <textarea id="message" placeholder="Assunto" required></textarea>
      <button type="submit">Enviar</button>
    </form>
    <div id="error-message"></div>
  </section>


  

  <script src="script.js"></script>
</body>
</html>
