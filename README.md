<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Falcone Next — Inteligência que transforma negócios</title>
  <meta name="description" content="Consultoria — Inteligência que transforma negócios. Estratégia, tecnologia e execução para acelerar resultados." />
  <meta property="og:title" content="Falcone Next" />
  <meta property="og:description" content="Inteligência que transforma negócios." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="https://images.unsplash.com/photo-1551836022-d5d88e9218df?q=80&w=1600&auto=format&fit=crop" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
  <!-- Tailwind via CDN (prático para um site simples) -->
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    :root { --brand: #2563eb; }
    html { scroll-behavior: smooth; }
    body { font-family: Inter, system-ui, -apple-system, Segoe UI, Roboto, Ubuntu, Cantarell, Noto Sans, 'Helvetica Neue', Arial, 'Apple Color Emoji', 'Segoe UI Emoji'; }
    .hero-bg { background: radial-gradient(1200px 400px at 10% 10%, rgba(37,99,235,.15), transparent),radial-gradient(1000px 500px at 90% 10%, rgba(14,165,233,.15), transparent); }
  </style>
</head>
<body class="bg-white text-slate-800">
  <!-- Header -->
  <header class="sticky top-0 z-40 backdrop-blur bg-white/70 border-b border-slate-200">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 flex items-center justify-between h-16">
      <a href="#" class="font-extrabold text-xl tracking-tight">Falcone<span class="text-blue-600"> Next</span></a>
      <nav class="hidden md:flex items-center gap-6 text-sm font-medium">
        <a href="#sobre" class="hover:text-blue-600">Sobre</a>
        <a href="#servicos" class="hover:text-blue-600">Serviços</a>
        <a href="#portfolio" class="hover:text-blue-600">Cases</a>
        <a href="#contato" class="px-3 py-1.5 rounded-lg bg-blue-600 text-white hover:bg-blue-700 transition">Contato</a>
      </nav>
      <button aria-label="Abrir menu" class="md:hidden p-2" onclick="document.getElementById('mobile').classList.toggle('hidden')">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6"><path fill-rule="evenodd" d="M3.75 5.25a.75.75 0 0 1 .75-.75h15a.75.75 0 0 1 0 1.5H4.5a.75.75 0 0 1-.75-.75Zm0 6a.75.75 0 0 1 .75-.75h15a.75.75 0 0 1 0 1.5H4.5a.75.75 0 0 1-.75-.75Zm0 6a.75.75 0 0 1 .75-.75h15a.75.75 0 0 1 0 1.5H4.5a.75.75 0 0 1-.75-.75Z" clip-rule="evenodd" /></svg>
      </button>
    </div>
    <div id="mobile" class="md:hidden hidden border-t border-slate-200">
      <div class="max-w-6xl mx-auto px-4 py-3 flex flex-col gap-3 text-sm">
        <a href="#sobre" onclick="this.closest('#mobile').classList.add('hidden')">Sobre</a>
        <a href="#servicos" onclick="this.closest('#mobile').classList.add('hidden')">Serviços</a>
        <a href="#portfolio" onclick="this.closest('#mobile').classList.add('hidden')">Cases</a>
        <a href="#contato" class="px-3 py-1.5 rounded-lg bg-blue-600 text-white w-max" onclick="this.closest('#mobile').classList.add('hidden')">Contato</a>
      </div>
    </div>
  </header>

  <!-- Hero -->
  <section class="hero-bg">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 py-20 sm:py-28">
      <div class="grid md:grid-cols-2 gap-10 items-center">
        <div>
          <h1 class="text-4xl sm:text-5xl font-extrabold tracking-tight leading-tight">Inteligência que transforma negócios.</h1>
          <p class="mt-5 text-lg text-slate-600">Consultoria para estratégia, eficiência e crescimento. Atuamos com dados, processos e tecnologia para acelerar resultados.</p>
          <div class="mt-8 flex gap-3">
            <a href="#contato" class="px-5 py-3 rounded-xl bg-blue-600 text-white font-semibold hover:bg-blue-700">Fale com a Falcone Next</a>
            <a href="#servicos" class="px-5 py-3 rounded-xl border border-slate-300 font-semibold hover:bg-slate-50">Ver serviços</a>
          </div>
        </div>
        <div class="relative">
          <div class="aspect-video rounded-2xl shadow-2xl overflow-hidden border border-slate-200">
            <img src="https://images.unsplash.com/photo-1542744173-8e7e53415bb0?q=80&w=1600&auto=format&fit=crop" alt="Reunião de negócios" class="w-full h-full object-cover" />
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Sobre -->
  <section id="sobre" class="py-16 sm:py-24">
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="max-w-3xl">
        <h2 class="text-3xl sm:text-4xl font-bold">Sobre a Falcone Next</h2>
        <p class="mt-4 text-slate-600">A Falcone Next é uma consultoria focada em transformar negócios por meio de inteligência, dados e tecnologia. Atendemos empresas no Brasil e no exterior, com abordagem prática e orientada a resultados.</p>
        <ul class="mt-6 grid sm:grid-cols-2 gap-3 text-sm">
          <li class="flex items-start gap-3"><span class="mt-1 inline-block w-2 h-2 rounded-full bg-blue-600"></span> Estratégia, processos e dados</li>
          <li class="flex items-start gap-3"><span class="mt-1 inline-block w-2 h-2 rounded-full bg-blue-600"></span> Projetos sob medida</li>
          <li class="flex items-start gap-3"><span class="mt-1 inline-block w-2 h-2 rounded-full bg-blue-600"></span> Atuação remota e presencial</li>
          <li class="flex items-start gap-3"><span class="mt-1 inline-block w-2 h-2 rounded-full bg-blue-600"></span> Atendimento em português</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- Serviços -->
  <section id="servicos" class="py-16 bg-slate-50">
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <h2 class="text-3xl sm:text-4xl font-bold">Serviços</h2>
      <div class="mt-8 grid md:grid-cols-3 gap-6">
        <div class="p-6 bg-white rounded-2xl border border-slate-200 shadow-sm">
          <h3 class="font-semibold text-lg">Estratégia & Planejamento</h3>
          <p class="mt-2 text-sm text-slate-600">Diagnóstico, direcionadores de crescimento e roadmap de execução.</p>
        </div>
        <div class="p-6 bg-white rounded-2xl border border-slate-200 shadow-sm">
          <h3 class="font-semibold text-lg">Eficiência Operacional</h3>
          <p class="mt-2 text-sm text-slate-600">Revisão de processos, indicadores e automação para reduzir custos.</p>
        </div>
        <div class="p-6 bg-white rounded-2xl border border-slate-200 shadow-sm">
          <h3 class="font-semibold text-lg">Dados & Tecnologia</h3>
          <p class="mt-2 text-sm text-slate-600">Métricas, dashboards e integrações para decisões melhores e mais rápidas.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Cases / Portfólio -->
  <section id="portfolio" class="py-16">
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <h2 class="text-3xl sm:text-4xl font-bold">Resultados recentes</h2>
      <div class="mt-8 grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
        <figure class="rounded-2xl overflow-hidden border border-slate-200">
          <img src="https://images.unsplash.com/photo-1552581234-26160f608093?q=80&w=1600&auto=format&fit=crop" alt="Equipe em reunião" class="w-full h-48 object-cover" />
          <figcaption class="p-4 text-sm">Plano de crescimento para PME — +22% em 6 meses</figcaption>
        </figure>
        <figure class="rounded-2xl overflow-hidden border border-slate-200">
          <img src="https://images.unsplash.com/photo-1521737604893-d14cc237f11d?q=80&w=1600&auto=format&fit=crop" alt="Mesa de negócios" class="w-full h-48 object-cover" />
          <figcaption class="p-4 text-sm">Redesenho de processos — -18% de custos operacionais</figcaption>
        </figure>
        <figure class="rounded-2xl overflow-hidden border border-slate-200">
          <img src="https://images.unsplash.com/photo-1553877522-43269d4ea984?q=80&w=1600&auto=format&fit=crop" alt="Painel de dados" class="w-full h-48 object-cover" />
          <figcaption class="p-4 text-sm">Dashboard executivo — decisão em tempo real</figcaption>
        </figure>
      </div>
    </div>
  </section>

  <!-- Contato -->
  <section id="contato" class="py-16 bg-slate-50">
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="grid md:grid-cols-2 gap-10 items-start">
        <div>
          <h2 class="text-3xl sm:text-4xl font-bold">Fale com a gente</h2>
          <p class="mt-4 text-slate-600">Converse sobre o seu desafio e receba uma proposta sem compromisso.</p>
          <ul class="mt-6 text-sm text-slate-700">
            <li class="mt-2"><strong>WhatsApp:</strong> <a class="text-blue-600 hover:underline" href="https://wa.me/5511997117561" target="_blank" rel="noopener">(11) 9 9711‑7561</a></li>
          </ul>
        </div>
        <form class="bg-white p-6 rounded-2xl border border-slate-200 shadow-sm" onsubmit="event.preventDefault(); alert('Obrigado! Sua mensagem foi enviada (simulação).'); this.reset();">
          <label class="block text-sm font-medium">Nome
            <input required class="mt-1 w-full rounded-lg border border-slate-300 px-3 py-2" placeholder="Seu nome" />
          </label>
          <label class="block text-sm font-medium mt-4">Email
            <input required type="email" class="mt-1 w-full rounded-lg border border-slate-300 px-3 py-2" placeholder="voce@email.com" />
          </label>
          <label class="block text-sm font-medium mt-4">Mensagem
            <textarea required class="mt-1 w-full rounded-lg border border-slate-300 px-3 py-2" rows="4" placeholder="Conte rapidamente seu desafio"></textarea>
          </label>
          <button class="mt-5 px-4 py-2 rounded-xl bg-blue-600 text-white font-semibold hover:bg-blue-700">Enviar</button>
          <p class="mt-3 text-xs text-slate-500">Formulário de demonstração. Para receber mensagens reais, use um serviço como Formspree, Getform ou crie um backend.</p>
        </form>
      </div>
    </div>
  </section>

  <!-- Rodapé -->
  <footer class="py-10 border-t border-slate-200">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 flex flex-col sm:flex-row items-center justify-between gap-4">
      <p class="text-sm text-slate-600">© <span id="ano"></span> Falcone Next. Todos os direitos reservados.</p>
      <a href="#" class="text-sm text-blue-600 hover:underline">Voltar ao topo</a>
    </div>
  </footer>

  <script>
    document.getElementById('ano').textContent = new Date().getFullYear();
  </script>
</body>
</html>
