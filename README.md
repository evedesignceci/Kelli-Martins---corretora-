<!DOCTYPE html>
<html lang="pt-BR" class="scroll-smooth">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kelli Martins | Corretora & Avaliadora de Imóveis em Santos - SP</title>
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Google Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700&family=Playfair+Display:ital,wght@0,600;0,700;1,400;1,600&display=swap" rel="stylesheet">
  <!-- Lucide Icons -->
  <script src="https://unpkg.com/lucide@latest"></script>
  
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['"Plus Jakarta Sans"', 'sans-serif'],
            serif: ['"Playfair Display"', 'serif'],
          },
          colors: {
            sand: {
              50: '#fdfbf7', 100: '#f7f2ea', 200: '#eee3d3',
              300: '#e1cdb3', 600: '#b89264', 800: '#7c5a36',
            },
            ocean: {
              50: '#f0f9fa', 100: '#d7f0f3', 500: '#149ba8',
              600: '#0d7f8c', 800: '#0b5059', 900: '#073339',
            },
            coastal: '#1b3842'
          }
        }
      }
    }
  </script>
</head>
<body class="bg-sand-50 text-slate-700 antialiased font-sans">

  <!-- NAVBAR -->
  <header class="sticky top-0 z-40 bg-sand-50/90 backdrop-blur-md border-b border-sand-200/60">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 h-20 flex items-center justify-between">
      <a href="#" class="flex flex-col">
        <span class="font-serif text-2xl tracking-tight text-coastal font-bold">Kelli Martins</span>
        <span class="text-[11px] uppercase tracking-[0.18em] text-ocean-600 font-semibold -mt-1 flex items-center gap-1">
          <i data-lucide="map-pin" class="w-3 h-3 text-rose-500"></i> Imóveis em Santos • SP
        </span>
      </a>
      <nav class="hidden md:flex items-center gap-7 text-sm font-medium text-slate-600">
        <a href="#bairros" class="hover:text-ocean-600 transition">Bairros de Santos</a>
        <a href="#servicos" class="hover:text-ocean-600 transition">Serviços</a>
        <a href="#atendimento" class="hover:text-ocean-600 transition text-ocean-600 font-bold">Atendimento WhatsApp</a>
        <a href="#avaliacao" class="hover:text-ocean-600 transition">Avaliação (CNAI)</a>
      </nav>
      <div class="flex items-center gap-2.5">
        <a href="https://www.instagram.com/kellimartins014?stkn=NWptdXVzOXg2dnI5" target="_blank" rel="noopener noreferrer" class="p-2.5 rounded-full border border-sand-200 text-slate-600 hover:text-rose-600 hover:border-rose-200 hover:bg-rose-50 transition">
          <i data-lucide="instagram" class="w-4 h-4"></i>
        </a>
        <a href="#atendimento" class="inline-flex items-center gap-2 bg-coastal text-sand-50 text-xs sm:text-sm font-medium px-4 sm:px-5 py-2.5 rounded-full hover:bg-ocean-800 transition shadow-sm">
          <i data-lucide="message-circle" class="w-4 h-4 text-ocean-100"></i>
          <span>(13) 97425-0913</span>
        </a>
      </div>
    </div>
  </header>

  <!-- HERO SECTION PERSONALIZADA PARA SANTOS/SP -->
  <section class="relative bg-gradient-to-b from-sand-100/80 via-sand-50 to-white py-12 lg:py-16 border-b border-sand-200/50">
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="grid lg:grid-cols-12 gap-10 items-center">
        
        <div class="lg:col-span-6 space-y-6">
          <div class="inline-flex items-center gap-2 bg-white/95 border border-sand-200 px-3.5 py-1.5 rounded-full text-coastal text-xs font-semibold shadow-sm">
            <span class="w-2 h-2 rounded-full bg-emerald-500 animate-pulse"></span>
            <span>CRECI-SP: 323425 • CNAI: 58458 • Especialista em Santos</span>
          </div>
          <h1 class="text-4xl sm:text-5xl font-serif text-coastal leading-[1.15]">
            Comprar, vender ou alugar em <span class="italic text-ocean-600">Santos</span> com total segurança.
          </h1>
          <p class="text-slate-600 text-base leading-relaxed">
            Assessoria imobiliária completa na Baixada Santista: do Gonzaga e Ponta da Praia ao Boqueirão e Embaré.
          </p>
          <div class="pt-1">
            <p class="text-xs uppercase tracking-wider font-bold text-slate-500 mb-2 flex items-center gap-1.5">
              <i data-lucide="compass" class="w-3.5 h-3.5 text-ocean-600"></i> Principais regiões de atuação:
            </p>
            <div class="flex flex-wrap gap-2 text-xs">
              <span class="bg-white px-3 py-1 rounded-lg border border-sand-200 text-slate-700 font-medium">Gonzaga</span>
              <span class="bg-white px-3 py-1 rounded-lg border border-sand-200 text-slate-700 font-medium">Ponta da Praia</span>
              <span class="bg-white px-3 py-1 rounded-lg border border-sand-200 text-slate-700 font-medium">Boqueirão</span>
              <span class="bg-white px-3 py-1 rounded-lg border border-sand-200 text-slate-700 font-medium">Embaré</span>
            </div>
          </div>
        </div>

        <!-- FORMULÁRIO SEGURO -->
        <div class="lg:col-span-6" id="atendimento">
          <div class="bg-white p-6 sm:p-8 rounded-3xl shadow-xl shadow-sand-300/40 border border-sand-200 relative">
            <div class="flex items-center justify-between mb-4 border-b border-sand-100 pb-3">
              <div>
                <h3 class="font-serif font-bold text-xl text-coastal">Atendimento em Santos</h3>
                <p class="text-xs text-slate-500">Campos com * são obrigatórios</p>
              </div>
              <div class="w-10 h-10 rounded-full bg-emerald-50 text-emerald-600 flex items-center justify-center">
                <i data-lucide="message-circle" class="w-5 h-5"></i>
              </div>
            </div>

            <form id="formZap" onsubmit="enviarParaWhatsApp(event)" class="space-y-4">
              <div>
                <label for="nome" class="block text-xs font-bold uppercase tracking-wider text-slate-600 mb-1">Seu Nome *</label>
                <div class="relative">
                  <div class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none text-slate-400"><i data-lucide="user" class="w-4 h-4"></i></div>
                  <input type="text" id="nome" required placeholder="Ex: Carlos Eduardo" class="w-full pl-9 pr-3 py-2.5 bg-sand-50/70 border border-sand-200 rounded-xl text-sm focus:outline-none focus:ring-2 focus:ring-ocean-500 transition">
                </div>
              </div>

              <div>
                <label for="telefone" class="block text-xs font-bold uppercase tracking-wider text-slate-600 mb-1">Seu WhatsApp *</label>
                <div class="relative">
                  <div class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none text-slate-400"><i data-lucide="phone" class="w-4 h-4"></i></div>
                  <input type="tel" id="telefone" required maxlength="15" placeholder="(13) 99999-9999" oninput="mascaraTelefone(this)" class="w-full pl-9 pr-3 py-2.5 bg-sand-50/70 border border-sand-200 rounded-xl text-sm focus:outline-none focus:ring-2 focus:ring-ocean-500 transition">
                </div>
              </div>

              <div>
                <label for="servico" class="block text-xs font-bold uppercase tracking-wider text-slate-600 mb-1">O que você precisa? *</label>
                <div class="relative">
                  <div class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none text-slate-400"><i data-lucide="help-circle" class="w-4 h-4"></i></div>
                  <select id="servico" required class="w-full pl-9 pr-3 py-2.5 bg-sand-50/70 border border-sand-200 rounded-xl text-sm text-slate-700 focus:outline-none focus:ring-2 focus:ring-ocean-500 transition appearance-none">
                    <option value="" disabled selected>Selecione uma opção...</option>
                    <option value="Comprar Imóvel">Quero Comprar um Imóvel</option>
                    <option value="Vender Imóvel">Quero Vender meu Imóvel</option>
                    <option value="Aluguel Anual">Aluguel Anual</option>
                    <option value="Aluguel de Temporada">Aluguel de Temporada</option>
                    <option value="Avaliação (PTAM)">Avaliação Oficial de Imóvel</option>
                    <option value="Financiamento/Crédito">Financiamento / Crédito</option>
                  </select>
                </div>
              </div>

              <div>
                <label for="bairro" class="block text-xs font-bold uppercase tracking-wider text-slate-600 mb-1">Bairro de interesse (Opcional)</label>
                <div class="relative">
                  <div class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none text-slate-400"><i data-lucide="map-pin" class="w-4 h-4"></i></div>
                  <input type="text" id="bairro" placeholder="Ex: Gonzaga, Ponta da Praia..." class="w-full pl-9 pr-3 py-2.5 bg-sand-50/70 border border-sand-200 rounded-xl text-sm focus:outline-none focus:ring-2 focus:ring-ocean-500 transition">
                </div>
              </div>

              <div>
                <label for="detalhes" class="block text-xs font-bold uppercase tracking-wider text-slate-600 mb-1">Mais detalhes (Opcional)</label>
                <textarea id="detalhes" rows="2" placeholder="Ex: Procuro apto 2 quartos..." class="w-full p-3 bg-sand-50/70 border border-sand-200 rounded-xl text-sm focus:outline-none focus:ring-2 focus:ring-ocean-500 transition resize-none"></textarea>
              </div>

              <button type="submit" class="w-full flex items-center justify-center gap-2 bg-emerald-500 hover:bg-emerald-600 text-white font-bold py-3.5 px-4 rounded-xl shadow-lg transition transform active:scale-[0.98]">
                <i data-lucide="send" class="w-4 h-4"></i>
                <span>Falar com Kelli no WhatsApp</span>
              </button>
            </form>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- RODAPÉ COMPACTO (Restante do site segue igual) -->
  <footer class="bg-slate-900 text-slate-400 py-8 text-xs border-t border-slate-800">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 flex flex-col sm:flex-row items-center justify-between gap-4">
      <div>
        <p class="text-white font-serif font-bold text-sm">Kelli Martins — Corretora e Avaliadora de Imóveis</p>
        <p class="text-slate-500 mt-0.5">CRECI-SP: 323425 • CNAI: 58458</p>
      </div>
      <div class="flex items-center gap-5">
        <a href="https://www.instagram.com/kellimartins014?stkn=NWptdXVzOXg2dnI5" target="_blank" rel="noopener noreferrer" class="hover:text-rose-400 transition flex items-center gap-1">
          <i data-lucide="instagram" class="w-4 h-4"></i> @kellimartins014
        </a>
      </div>
    </div>
  </footer>

  <script>
    lucide.createIcons();

    function mascaraTelefone(input) {
      let v = input.value.replace(/\D/g, "");
      if (v.length > 11) v = v.substring(0, 11);
      if (v.length > 10) { v = v.replace(/^(\d{2})(\d{5})(\d{4})/, "($1) $2-$3"); }
      else if (v.length > 5) { v = v.replace(/^(\d{2})(\d{4})(\d{0,4})/, "($1) $2-$3"); }
      else if (v.length > 2) { v = v.replace(/^(\d{2})(\d{0,5})/, "($1) $2"); }
      else if (v.length > 0) { v = v.replace(/^(\d{0,2})/, "($1"); }
      input.value = v;
    }

    // Função de Segurança: Previne XSS limpando caracteres perigosos antes de processar
    function sanitizar(texto) {
      const mapa = { '&': '&amp;', '<': '&lt;', '>': '&gt;', '"': '&quot;', "'": '&#x27;', '/': '&#x2F;' };
      return texto.replace(/[&<>"'/]/ig, (match) => (mapa[match]));
    }

    function enviarParaWhatsApp(event) {
      event.preventDefault();

      // Coleta e sanitiza os dados
      const nome = sanitizar(document.getElementById("nome").value.trim());
      const telefone = sanitizar(document.getElementById("telefone").value.trim());
      const servico = sanitizar(document.getElementById("servico").value);
      const bairro = sanitizar(document.getElementById("bairro").value.trim());
      const detalhes = sanitizar(document.getElementById("detalhes").value.trim());

      const apenasNumeros = telefone.replace(/\D/g, "");
      if (apenasNumeros.length < 10) {
        alert("Por favor, digite um número de WhatsApp válido.");
        return;
      }

      /* 
       * ==========================================
       * INTEGRAÇÃO FUTURA COM PLANILHA (WEBHOOK)
       * ==========================================
       * Quando for criar a planilha (Google Sheets via Google Apps Script ou Make/Zapier),
       * basta descomentar o bloco abaixo e colar sua URL.
       * Isso garante que os dados sejam salvos mesmo se o cliente fechar a aba do WhatsApp.
       */
      
      // fetch('URL_DO_SEU_WEBHOOK_AQUI', {
      //   method: 'POST',
      //   headers: { 'Content-Type': 'application/json' },
      //   body: JSON.stringify({ nome, telefone, servico, bairro, detalhes, data: new Date() })
      // }).catch(err => console.log('Erro ao salvar lead:', err));
      

      // NOVA MENSAGEM: Perspectiva do Cliente
      let mensagem = `Olá, Kelli! Vim pelo seu site e gostaria de atendimento.\n\n`;
      mensagem += `👤 *Meu Nome:* ${nome}\n`;
      mensagem += `🎯 *Eu preciso de:* ${servico}\n`;
      
      if (bairro) {
        mensagem += `📍 *Bairro de interesse:* ${bairro}\n`;
      }
      if (detalhes) {
        mensagem += `📝 *Mais detalhes:* ${detalhes}\n`;
      }

      const numeroZapKelli = "5513974250913";
      const urlZap = `https://wa.me/${numeroZapKelli}?text=${encodeURIComponent(mensagem)}`;
      
      // Abre o WhatsApp
      window.open(urlZap, "_blank");
    }
  </script>
</body>
</html>
