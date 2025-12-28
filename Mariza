<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<title>Para Mariza 💖</title>

<style>
  body {
    margin: 0;
    height: 100vh;
    background: radial-gradient(circle at bottom, #1b1b3a, #000);
    overflow: hidden;
    font-family: 'Arial', sans-serif;
    color: white;
    text-align: center;
  }

  /* Estrelas */
  body::before {
    content: "";
    position: absolute;
    inset: 0;
    background-image:
      radial-gradient(1px 1px at 10% 20%, white, transparent),
      radial-gradient(1px 1px at 30% 80%, white, transparent),
      radial-gradient(1px 1px at 50% 50%, white, transparent),
      radial-gradient(1px 1px at 70% 30%, white, transparent),
      radial-gradient(1px 1px at 90% 60%, white, transparent);
    background-size: 200px 200px;
    animation: estrelas 10s linear infinite;
    z-index: 0;
  }

  @keyframes estrelas {
    from { background-position: 0 0; }
    to { background-position: 200px 200px; }
  }

  /* Lua */
  .lua {
    width: 250px;
    height: 250px;
    background: #f5f3ce;
    border-radius: 50%;
    box-shadow: 0 0 80px #fff;
    margin: 40px auto 20px;
    z-index: 1;
    position: relative;
  }

  h1 {
    font-size: 3em;
    margin: 10px 0;
    background: linear-gradient(270deg, #ff69b4, #8a2be2);
    background-size: 400% 400%;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    animation: nome 3s infinite alternate;
  }

  @keyframes nome {
    from { background-position: 0% }
    to { background-position: 100% }
  }

  p {
    max-width: 800px;
    margin: auto;
    font-size: 1.3em;
    line-height: 1.6;
    padding: 20px;
    z-index: 1;
    position: relative;
  }

  #conteudo {
    display: none;
  }

  #senhaBox {
    position: absolute;
    inset: 0;
    background: black;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    z-index: 10;
  }

  input {
    padding: 10px;
    font-size: 1.1em;
    border-radius: 10px;
    border: none;
    margin-top: 10px;
  }

  button {
    margin-top: 15px;
    padding: 10px 25px;
    font-size: 1.1em;
    border-radius: 20px;
    border: none;
    background: pink;
    cursor: pointer;
  }
</style>
</head>

<body>

<div id="senhaBox">
  <h2>💖 Digite a senha 💖</h2>
  <input type="password" id="senha" placeholder="Senha">
  <button onclick="entrar()">Entrar</button>
</div>

<div id="conteudo">
  <div class="lua"></div>

  <h1>Mariza</h1>

  <p>
    te amo muito minha gatinha, isso foi só pra descontrair msm e reforçar que sou mt bobo por vc,
    e que eu quero voce na minha vida, que quero ser uma experiência boa.
    Quero que voce sinta td meu amor por vc, te fazer feliz vai ser a melhor missão
    que vou fzr questão de repetir tds os dias, te amo cada dia mais.
    <br><br>
    No nosso tempinho, do nosso jeitinho, vamos fazer tudo acontecer.
    Espero que seja você e com você os meus próximos dias felizes.
    <br><br>
    <strong>(ao seu lado)</strong><br>
    te amo neném 💕
  </p>
</div>

<script>
  function entrar() {
    const senha = document.getElementById("senha").value;
    if (senha === "gatinha") {
      document.getElementById("senhaBox").style.display = "none";
      document.getElementById("conteudo").style.display = "block";
    } else {
      alert("Senha incorreta 😢");
    }
  }
</script>

</body>
</html>
