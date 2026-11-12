# IdadeCerta
Site para identificação de idade para eventos
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Idade Certa | Diversão com responsabilidade</title>
<style>
:root{--purple:#792fc0;--deep:#1d1229;--lav:#f1e8fa;--ink:#291d35;--muted:#665c70}
*{box-sizing:border-box;scroll-behavior:smooth}
body{margin:0;font-family:Arial,Helvetica,sans-serif;color:var(--ink);background:#fff}
header{background:var(--deep);color:#fff;padding:18px 7%;display:flex;align-items:center;justify-content:space-between;gap:18px;flex-wrap:wrap}
.brand{font-size:25px;font-weight:900;letter-spacing:.5px}.brand span{color:#c995ff}
nav{display:flex;gap:20px;flex-wrap:wrap}nav a{color:#fff;text-decoration:none;font-size:14px}nav a:hover{color:#d4adff}
.hero{padding:76px 7%;background:linear-gradient(125deg,#21132e,#572287,#873bc5);color:#fff;display:grid;grid-template-columns:1.15fr .85fr;gap:38px;align-items:center}
.eyebrow{display:inline-block;border:1px solid #ffffff70;border-radius:30px;padding:8px 13px;font-size:12px;letter-spacing:1px}
h1{font-size:clamp(42px,7vw,68px);margin:18px 0 8px}.slogan{font-size:clamp(19px,3vw,25px);font-weight:700;color:#f0dcff}
.hero p{line-height:1.7;color:#f0e8f7;max-width:600px}
.btn{display:inline-block;margin-top:15px;padding:13px 21px;background:#fff;color:#6925a7;border-radius:30px;text-decoration:none;font-weight:700}
.pack{background:#fff;color:var(--ink);border-radius:20px;padding:26px;text-align:center;box-shadow:0 15px 40px #0004}
.pack h2{color:var(--purple);margin:0 0 8px}.pack small{color:var(--muted)}
.band{margin:14px auto;padding:15px 12px;border-radius:30px;max-width:250px;font-weight:800;letter-spacing:.5px}
.b18{background:#8239c4;color:#fff}.b16{background:#f4d44d;color:#302500}.b14{background:#e99ac7;color:#401832}
section{padding:68px 7%}.tint{background:var(--lav)}.dark{background:var(--deep);color:#fff}
h2.section-title{font-size:clamp(28px,4vw,38px);color:var(--purple);margin:0 0 16px}.dark h2.section-title{color:#d0a3ff}
.lead{max-width:850px;line-height:1.8;color:var(--muted);font-size:17px}.dark .lead{color:#e3d8ec}
.cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(210px,1fr));gap:20px;margin-top:28px}
.card{background:#fff;border-radius:15px;padding:24px;box-shadow:0 5px 20px #29133c12;border-bottom:4px solid var(--purple)}
.card h3{margin:0 0 10px;color:var(--purple)}.card p{margin:0;line-height:1.65;color:var(--muted)}
.dark .card{background:#30203e;border-color:#b77bea}.dark .card h3{color:#d6b1fa}.dark .card p{color:#eee5f5}
.steps{display:grid;grid-template-columns:repeat(auto-fit,minmax(190px,1fr));gap:18px;margin-top:28px}
.step{background:#fff;border-radius:14px;padding:22px}.num{font-size:28px;color:var(--purple);font-weight:900}.step h3{margin:10px 0}.step p{color:var(--muted);line-height:1.6}
.note{margin-top:22px;padding:16px;border-left:4px solid var(--purple);background:#fff;border-radius:8px;line-height:1.6}
.contact{background:linear-gradient(120deg,#6d28a8,#321644);color:#fff;text-align:center}.contact h2{color:#fff!important}.contact p{line-height:1.7}
footer{background:#120c19;color:#d7cadd;text-align:center;padding:24px;font-size:13px;line-height:1.7}
@media(max-width:720px){.hero{grid-template-columns:1fr;padding:58px 7%}header{justify-content:center}nav{justify-content:center}.pack{max-width:420px;width:100%;margin:auto}}
</style>
</head>
<body>
<header>
  <div class="brand">IDADE <span>CERTA</span></div>
  <nav>
    <a href="#problema">O problema</a>
    <a href="#solucao">A solução</a>
    <a href="#negocio">Como ganhamos</a>
    <a href="#contato">Contato</a>
  </nav>
</header>

<main>
  <div class="hero">
    <div>
      <span class="eyebrow">PULSEIRAS DE IDENTIFICAÇÃO PARA EVENTOS</span>
      <h1>Idade Certa</h1>
      <div class="slogan">Diversão com responsabilidade começa na entrada.</div>
      <p>Uma solução simples para ajudar festas e espaços privados a organizar a identificação visual dos convidados e reforçar o respeito às regras de idade.</p>
      <a class="btn" href="#solucao">Conheça a solução</a>
    </div>
    <div class="pack">
      <h2>Pulseiras Idade Certa</h2>
      <small>Embalagem com pulseiras separadas por categorias</small>
      <div class="band b18">IDADE CERTA · +18</div>
      <div class="band b16">IDADE CERTA · +16</div>
      <div class="band b14">IDADE CERTA · +14</div>
      <strong>Organização, respeito e cuidado.</strong>
    </div>
  </div>

  <section id="problema">
    <h2 class="section-title">O problema</h2>
    <p class="lead">A apresentação de documentação falsa em festas e lugares privados pode comprometer a segurança dos convidados e dificultar o trabalho de quem organiza o evento. Quando alguém utiliza documento adulterado ou informações falsas para tentar entrar em uma festa com restrição de idade, menores podem acabar expostos a ambientes inadequados e os organizadores podem perder o controle correto da entrada.</p>
    <div class="cards">
      <article class="card"><h3>Documentação falsa</h3><p>Documentos adulterados ou informações incorretas dificultam a confirmação da idade dos convidados.</p></article>
      <article class="card"><h3>Entrada desorganizada</h3><p>Sem um processo claro de conferência, a equipe pode ter dificuldade para identificar as categorias autorizadas.</p></article>
      <article class="card"><h3>Risco para menores</h3><p>A entrada em eventos incompatíveis com a idade pode expor adolescentes a situações inadequadas.</p></article>
    </div>
  </section>

  <section id="solucao" class="tint">
    <h2 class="section-title">A nossa solução</h2>
    <p class="lead">A Idade Certa oferece pulseiras coloridas que ajudam a equipe a reconhecer visualmente as categorias de convidados depois que um responsável confere a documentação verdadeira. A embalagem transparente facilita a organização e o acesso às pulseiras durante a entrada.</p>
    <div class="steps">
      <div class="step"><div class="num">01</div><h3>Conferência</h3><p>A equipe responsável verifica um documento verdadeiro e confirma a idade, seguindo as regras do evento e a legislação.</p></div>
      <div class="step"><div class="num">02</div><h3>Identificação</h3><p>O convidado recebe a pulseira correspondente à categoria para a qual foi autorizado.</p></div>
      <div class="step"><div class="num">03</div><h3>Organização</h3><p>A pulseira facilita a identificação visual durante o evento e ajuda a equipe a aplicar as regras de acesso.</p></div>
    </div>
    <div class="note"><strong>Importante:</strong> a pulseira não comprova idade, não detecta documentos falsos e não substitui a conferência de documento verdadeiro. As categorias e permissões devem respeitar a classificação etária e as regras legais aplicáveis.</div>
  </section>

  <section id="negocio" class="dark">
    <h2 class="section-title">Como ganhamos dinheiro?</h2>
    <p class="lead">O negócio ganha dinheiro produzindo e vendendo pacotes de pulseiras para estabelecimentos e organizadores de eventos. Podemos trabalhar com vendas diretas e parcerias de revenda.</p>
    <div class="cards">
      <article class="card"><h3>Venda direta</h3><p>Vendemos pacotes para salões de festas, buffets, produtores e organizadores de eventos. A receita vem da diferença entre o preço de venda e os custos de produção e operação.</p></article>
      <article class="card"><h3>Revendedores</h3><p>Parceiros compram os pacotes por um preço de atacado e revendem aos estabelecimentos. Eles ganham com a margem entre compra e revenda; a Idade Certa ganha com as vendas em volume.</p></article>
      <article class="card"><h3>Investidores</h3><p>O investimento pode financiar materiais, embalagens, divulgação e aumento da produção. O investidor pode negociar participação ou outra forma de retorno, conforme um acordo claro e os resultados reais do negócio.</p></article>
    </div>
  </section>

  <section id="contato" class="contact">
    <h2 class="section-title">Vamos conversar?</h2>
    <p>Quer conhecer as pulseiras, revender ou apoiar a Idade Certa?</p>
    <p><strong>Idade Certa — Diversão com responsabilidade começa na entrada.</strong></p>
    <a class="btn" href="mailto:contato@exemplo.com">Entre em contato</a>
    <p style="font-size:12px;margin-top:15px">Troque contato@exemplo.com pelo e-mail real do projeto.</p>
  </section>
</main>

<footer>
  © 2026 Idade Certa · Pulseiras de identificação para eventos.<br>
  A organização começa na entrada. A segurança depende de conferência responsável.
</footer>
</body>
</html>
