<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>para minha princesa ❤️</title>
<style>
  *{box-sizing:border-box;margin:0;padding:0}
  body{
    min-height:100vh;
    overflow-x:hidden;
    font-family:Georgia,"Times New Roman",serif;
    color:#fff;
    background:
      radial-gradient(circle at 20% 10%, #7b1838 0, transparent 28%),
      radial-gradient(circle at 80% 90%, #3d0c22 0, transparent 30%),
      linear-gradient(135deg,#160813,#350d20 55%,#12070e);
  }
  .hearts{position:fixed;inset:0;pointer-events:none;overflow:hidden;z-index:0}
  .heart{
    position:absolute;bottom:-60px;color:#ff8eae;font-size:22px;
    animation:rise linear infinite;opacity:.65;
    filter:drop-shadow(0 0 8px #ff477e);
  }
  @keyframes rise{
    from{transform:translateY(0) rotate(0deg);opacity:0}
    15%{opacity:.7} to{transform:translateY(-115vh) rotate(25deg);opacity:0}
  }
  .wrap{position:relative;z-index:1;max-width:900px;margin:auto;padding:35px 20px 70px}
  .hero{
    text-align:center;padding:55px 25px 40px;
    border:1px solid rgba(255,180,200,.3);border-radius:30px;
    background:rgba(255,255,255,.06);backdrop-filter:blur(10px);
    box-shadow:0 20px 70px rgba(0,0,0,.35);
  }
  .small{letter-spacing:4px;text-transform:uppercase;color:#ffb4c8;font-size:12px}
  h1{font-size:clamp(42px,9vw,78px);margin:16px 0 8px;color:#fff1f5;text-shadow:0 0 25px rgba(255,70,120,.45)}
  .subtitle{font-size:20px;color:#ffd8e2;line-height:1.6}
  .big-heart{font-size:72px;display:block;margin:15px auto;animation:pulse 1.7s infinite}
  @keyframes pulse{50%{transform:scale(1.12)}}
  .card{
    margin-top:28px;padding:34px;border-radius:25px;
    background:rgba(255,255,255,.07);border:1px solid rgba(255,190,205,.2);
  }
  .card h2{text-align:center;font-size:28px;color:#ffc4d3;margin-bottom:22px}
  .letter{font-size:19px;line-height:1.9;color:#ffe8ee}
  .quotes{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:15px;margin-top:20px}
  .quote{
    padding:22px;border-radius:18px;text-align:center;
    background:linear-gradient(145deg,rgba(255,105,145,.13),rgba(255,255,255,.05));
    border:1px solid rgba(255,160,185,.18);font-size:18px;line-height:1.5;
  }
  .quote span{display:block;font-size:24px;margin-bottom:8px}
  .button{
    display:block;margin:30px auto 0;padding:15px 25px;border:0;border-radius:999px;
    color:#fff;background:#a82b50;font-family:inherit;font-size:17px;cursor:pointer;
    box-shadow:0 8px 25px rgba(168,43,80,.35);transition:.2s;
  }
  .button:hover{transform:translateY(-2px);background:#c33a61}
  #surprise{display:none;text-align:center;margin-top:20px;color:#ffd6e0;font-size:19px;line-height:1.7}
  footer{text-align:center;margin-top:35px;color:#dca7b6;font-size:14px}
  @media(max-width:500px){.hero{padding:40px 18px}.card{padding:25px 20px}.letter{font-size:17px}}
</style>
</head>
<body>
<div class="hearts" aria-hidden="true">
  <i class="heart" style="left:5%;animation-duration:9s;animation-delay:0s">♥</i>
  <i class="heart" style="left:17%;animation-duration:12s;animation-delay:3s">♡</i>
  <i class="heart" style="left:31%;animation-duration:8s;animation-delay:1s">♥</i>
  <i class="heart" style="left:48%;animation-duration:11s;animation-delay:5s">♡</i>
  <i class="heart" style="left:64%;animation-duration:10s;animation-delay:2s">♥</i>
  <i class="heart" style="left:78%;animation-duration:13s;animation-delay:4s">♡</i>
  <i class="heart" style="left:92%;animation-duration:9s;animation-delay:6s">♥</i>
</div>

<main class="wrap">
  <section class="hero">
    <div class="small">feito com todo meu amor</div>
    <span class="big-heart">♥</span>
    <h1>para minha princesa</h1>
    <p class="subtitle">um cantinho só nosso, porque vc merece o mundo inteiro.</p>
  </section>

  <section class="card">
    <h2>uma pequena carta para vc</h2>
    <p class="letter">
      minha princesa, eu queria que vc pudesse enxergar o quanto é especial pra mim.
      eu amo cada detalhe seu, seu sorriso, seus olhos, seu jeito, sua voz e até
      aquelas pequenas coisas que talvez vc nem perceba. estar ao seu lado faz
      tudo ficar mais bonito. eu quero continuar vivendo momentos com vc,
      criando lembranças, realizando nossos sonhos e construindo nosso futuro juntos.
      <br><br>
      obrigado por existir na minha vida e por fazer meu coração escolher vc todos os dias.
      eu te amo mais do que consigo colocar em palavras. ❤️
    </p>
  </section>

  <section class="card">
    <h2>coisas que eu amo em vc</h2>
    <div class="quotes">
      <div class="quote"><span>♡</span>eu amo seu sorriso.</div>
      <div class="quote"><span>♡</span>eu amo seus olhos.</div>
      <div class="quote"><span>♡</span>eu amo seu cabelo.</div>
      <div class="quote"><span>♡</span>eu amo seu jeitinho.</div>
      <div class="quote"><span>♡</span>eu amo nossas conversas.</div>
      <div class="quote"><span>♡</span>eu amo simplesmente ter vc comigo.</div>
    </div>
    <button class="button" onclick="document.getElementById('surprise').style.display='block'">
      clique aqui, minha princesa ♡
    </button>
    <div id="surprise">se eu pudesse escolher de novo, em todas as vidas eu escolheria vc. ❤️</div>
  </section>

  <footer>feito especialmente para a pessoa que mora no meu coração ♡</footer>
</main>
</body>
</html>
