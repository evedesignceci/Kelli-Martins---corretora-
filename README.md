<!DOCTYPE html>
<html lang="pt-BR" class="scroll-smooth">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Keli Martins | Corretora & Avaliadora Imobiliária</title>
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Google Fonts: Plus Jakarta Sans & Playfair Display -->
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
              50: '#fdfbf7',
              100: '#f7f2ea',
              200: '#eee3d3',
              300: '#e1cdb3',
              600: '#b89264',
              800: '#7c5a36',
            },
            ocean: {
              50: '#f0f9fa',
              100: '#d7f0f3',
              500: '#149ba8',
              600: '#0d7f8c',
              800: '#0b5059',
              900: '#073339',
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
        <span class="font-serif text-2xl tracking-tight text-coastal font-bold">Keli Martins</span>
        <span class="text-[11px] uppercase tracking-[0.18em] text-ocean-600 font-semibold -mt-1 flex items-center gap-1">
          <i data-lucide="scale" class="w-3 h-3"></i> Avaliação & Negócios no Litoral
        </span>
      </a>

      <nav class="hidden md:flex items-center gap-7 text-sm font-medium text-slate-600">
        <a href="#servicos" class="hover:text-ocean-600 transition">Atuação</a>
        <a href="#avaliacao" class="hover:text-ocean-600 transition">Avaliação Pericial</a>
        <a href="#imoveis" class="hover:text-ocean-600 transition">Imóveis</a>
        <a href="#sobre" class="hover:text-ocean-600 transition">Sobre</a>
      </nav>

      <a href="https://wa.me/5500000000000?text=Olá%20Keli,%20gostaria%20de%20um%20atendimento!" 
         target="_blank"
         class="inline-flex items-center gap-2 bg-coastal text-sand-50 text-xs sm:text-sm font-medium px-4 sm:px-5 py-2.5 rounded-full hover:bg-ocean-800 transition shadow-sm">
        <i data-lucide="message-circle" class="w-4 h-4 text-ocean-100"></i>
        <span>Falar com a Keli</span>
      </a>
    </div>
  </header>

  <!-- HERO SECTION: OS DOIS PILARES -->
  <section class="relative bg-gradient-to-b from-sand-100/80 via-sand-50 to-white py-14 lg:py-20 border-b border-sand-200/50">
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="grid lg:grid-cols-12 gap-10 items-center">
        
        <!-- Conteúdo Hero -->
        <div class="lg:col-span-7 space-y-6">
          <div class="inline-flex items-center gap-2 bg-white/80 border border-sand-200 px-3.5 py-1.5 rounded-full text-coastal text-xs font-semibold shadow-sm">
            <span class="w-2 h-2 rounded-full bg-emerald-500 animate-pulse"></span>
            <span>CRECI & CNAI Especializada em Imóveis Litorâneos</span>
          </div>

          <h1 class="text-4xl sm:text-5xl lg:text-[3.2rem] font-serif text-coastal leading-[1.15]">
            Segurança jurídica para <span class="italic text-ocean-600">avaliar</span>, vender e alugar no litoral.
          </h1>

          <p class="text-slate-600 text-base sm:text-lg leading-relaxed max-w-xl">
            Dupla assessoria especializada: laudos técnicos com valor real de mercado para o seu patrimônio e intermediação completa para compra, venda e locação à beira-mar.
          </p>

          <!-- Acesso Rápido aos 2 Serviços -->
          <div class="grid sm:grid-cols-2 gap-3 pt-2">
            <a href="#avaliacao" class="flex items-center gap-3 p-4 bg-white rounded-2xl border border-sand-200 shadow-sm hover:border-ocean-500 hover:shadow-md transition group">
              <div class="w-10 h-10 rounded-xl bg-ocean-50 text-ocean-600 flex items-center justify-center shrink-0 group-hover:bg-ocean-600 group-hover:text-white transition">
                <i data-lucide="clipboard-check" class="w-5 h-5"></i>
              </div>
              <div class="text-left">
                <h3 class="text-sm font-bold text-coastal">Avaliar meu Imóvel</h3>
                <p class="text-xs text-slate-500">PTAM, inventários e valor real</p>
              </div>
            </a>

            <a href="#imoveis" class="flex items-center gap-3 p-4 bg-white rounded-2xl border border-sand-200 shadow-sm hover:border-sand-600 hover:shadow-md transition group">
              <div class="w-10 h-10 rounded-xl bg-amber-50 text-amber-700 flex items-center justify-center shrink-0 group-hover:bg-sand-600 group-hover:text-white transition">
                <i data-lucide="key" class="w-5 h-5"></i>
              </div>
              <div class="text-left">
                <h3 class="text-sm font-bold text-coastal">Comprar ou Alugar</h3>
                <p class="text-xs text-slate-500">Imóveis selecionados na praia</p>
              </div>
            </a>
          </div>
        </div>

        <!-- Foto de Apresentação / Imagem Praiana com Selos -->
        <div class="lg:col-span-5 relative">
          <div class="relative mx-auto max-w-sm rounded-3xl overflow-hidden shadow-2xl border-4 border-white">
            <img src="https://images.unsplash.com/photo-1512917774080-9991f1c4c750?auto=format&fit=crop&w=800&q=80" 
                 alt="Casa de Praia e Consultoria Imobiliária" 
                 class="w-full h-[460px] object-cover">
            
            <div class="absolute inset-0 bg-gradient-to-t from-coastal/85 via-coastal/20 to-transparent flex flex-col justify-end p-6 text-white">
              <div class="flex flex-wrap gap-2 mb-2">
                <span class="text-[11px] bg-white/20 backdrop-blur-md px-2.5 py-1 rounded-md font-semibold border border-white/20">
                  CRECI Ativo
                </span>
                <span class="text-[11px] bg-ocean-500/80 backdrop-blur-md px-2.5 py-1 rounded-md font-semibold border border-white/20">
                  Perita Avaliadora (CNAI)
                </span>
              </div>
              <h3 class="text-xl font-serif font-bold">Keli Martins</h3>
              <p class="text-xs text-sand-100 mt-0.5">Precisão técnica no laudo e sensibilidade para encontrar o seu lar na praia.</p>
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- BLOCO 1: SEÇÃO EXCLUSIVA DE AVALIAÇÃO DE IMÓVEIS -->
  <section id="avaliacao" class="py-16 bg-white border-b border-sand-200/50">
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      
      <div class="bg-gradient-to-br from-sand-100/70 via-white to-sand-50 rounded-3xl p-8 sm:p-12 border border-sand-200/80 shadow-sm">
        <div class="grid lg:grid-cols-12 gap-8 items-center">
          
          <div class="lg:col-span-7 space-y-4">
            <span class="text-xs uppercase tracking-widest text-ocean-600 font-bold flex items-center gap-1.5">
              <i data-lucide="award" class="w-4 h-4"></i> Laudo Técnico Oficial
            </span>
            <h2 class="text-3xl font-serif font-bold text-coastal">
              Precisa saber o valor exato do seu patrimônio?
            </h2>
            <p class="text-slate-600 text-sm sm:text-base leading-relaxed">
              Como perita avaliadora imobiliária cadastrada no <strong>CNAI</strong>, elaboro o <strong>PTAM (Parecer Técnico de Avaliação Mercadológica)</strong> de acordo com as normas da ABNT. Indispensável para:
            </p>

            <ul class="grid sm:grid-cols-2 gap-2.5 text-xs sm:text-sm text-slate-700 pt-1">
              <li class="flex items-center gap-2">
                <i data-lucide="check-circle-2" class="w-4 h-4 text-ocean-600 shrink-0"></i>
                Venda sem prejuízo financeiro
              </li>
              <li class="flex items-center gap-2">
                <i data-lucide="check-circle-2" class="w-4 h-4 text-ocean-600 shrink-0"></i>
                Inventários e partilhas
              </li>
              <li class="flex items-center gap-2">
                <i data-lucide="check-circle-2" class="w-4 h-4 text-ocean-600 shrink-0"></i>
                Processos judiciais e divórcios
              </li>
              <li class="flex items-center gap-2">
                <i data-lucide="check-circle-2" class="w-4 h-4 text-ocean-600 shrink-0"></i>
                Garantias e financiamentos
              </li>
            </ul>

            <div class="pt-4">
              <a href="https://wa.me/5500000000000?text=Olá%20Keli,%20preciso%20de%20uma%20avaliação%20imobiliária%20(PTAM)" 
                 target="_blank"
                 class="inline-flex items-center gap-2 bg-ocean-600 hover:bg-ocean-800 text-white font-semibold px-6 py-3 rounded-xl text-sm transition shadow-md shadow-ocean-600/20">
                <i data-lucide="file-text" class="w-4 h-4"></i>
                <span>Solicitar Avaliação Mercadológica</span>
              </a>
            </div>
          </div>

          <div class="lg:col-span-5 bg-white p-6 rounded-2xl border border-sand-200 shadow-sm space-y-4">
            <div class="flex items-center gap-3 border-b border-sand-100 pb-3">
              <div class="w-10 h-10 rounded-full bg-ocean-50 text-ocean-600 flex items-center justify-center font-bold text-sm">
                1
              </div>
              <div>
                <h4 class="text-sm font-bold text-coastal">Vistoria e Levantamento</h4>
                <p class="text-xs text-slate-500">Análise estrutural, acabamento e localização</p>
              </div>
            </div>

            <div class="flex items-center gap-3 border-b border-sand-100 pb-3">
              <div class="w-10 h-10 rounded-full bg-ocean-50 text-ocean-600 flex items-center justify-center font-bold text-sm">
                2
              </div>
              <div>
                <h4 class="text-sm font-bold text-coastal">Pesquisa de Amostragem</h4>
                <p class="text-xs text-slate-500">Comparativo real com o mercado da praia</p>
              </div>
            </div>

            <div class="flex items-center gap-3">
              <div class="w-10 h-10 rounded-full bg-ocean-50 text-ocean-600 flex items-center justify-center font-bold text-sm">
                3
              </div>
              <div>
                <h4 class="text-sm font-bold text-coastal">Emissão do PTAM</h4>
                <p class="text-xs text-slate-500">Documento com fé pública e validade legal</p>
              </div>
            </div>
          </div>

        </div>
      </div>

    </div>
  </section>

  <!-- BLOCO 2: SEÇÃO DE VENDA & ALUGUEL (VITRINE PRAIANA) -->
  <section id="imoveis" class="py-20 bg-sand-100/50">
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      
      <div class="flex flex-col sm:flex-row sm:items-end justify-between mb-10 gap-4">
        <div>
          <span class="text-xs uppercase tracking-widest text-ocean-600 font-bold">Venda & Locação</span>
          <h2 class="text-3xl font-serif font-bold text-coastal mt-1">Imóveis Disponíveis no Litoral</h2>
        </div>
        
        <!-- Toggle Simples ou Filtro Visual -->
        <div class="inline-flex p-1 bg-white rounded-xl border border-sand-200 text-xs font-semibold">
          <button class="px-4 py-2 rounded-lg bg-coastal text-white shadow-sm">Todos</button>
          <button class="px-4 py-2 rounded-lg text-slate-600 hover:text-coastal">Para Venda</button>
          <button class="px-4 py-2 rounded-lg text-slate-600 hover:text-coastal">Para Alugar</button>
        </div>
      </div>

      <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-8">
        
        <!-- CARD 1: VENDA -->
        <div class="bg-white rounded-2xl overflow-hidden border border-sand-200 shadow-sm hover:shadow-xl transition-all duration-300 flex flex-col">
          <div class="relative h-56 bg-slate-200">
            <img src="https://images.unsplash.com/photo-1613490493576-7fde63acd811?auto=format&fit=crop&w=700&q=80" alt="Casa Pé na Areia" class="w-full h-full object-cover">
            <div class="absolute top-3 left-3 flex gap-2">
              <span class="bg-coastal text-sand-50 text-[11px] font-bold px-3 py-1 rounded-full uppercase tracking-wider">Venda</span>
              <span class="bg-white/95 backdrop-blur-md text-ocean-800 text-[11px] font-semibold px-2.5 py-1 rounded-full flex items-center gap-1">
                <i data-lucide="waves" class="w-3 h-3 text-ocean-600"></i> Pé na areia
              </span>
            </div>
          </div>
          <div class="p-6 flex flex-col flex-grow">
            <span class="text-xs text-sand-600 font-medium">Praia Nobre</span>
            <h3 class="text-lg font-bold text-slate-900 mt-1 mb-2 font-serif">Casa Térrea c/ Acesso Privativo</h3>
            <p class="text-2xl font-serif font-bold text-coastal mb-4">R$ 1.850.000</p>
            
            <div class="flex items-center justify-between text-xs text-slate-500 border-t border-sand-100 pt-4 mb-6">
              <span class="flex items-center gap-1.5"><i data-lucide="bed-single" class="w-4 h-4 text-ocean-600"></i> 4 Suítes</span>
              <span class="flex items-center gap-1.5"><i data-lucide="car" class="w-4 h-4 text-ocean-600"></i> 3 Vagas</span>
              <span class="flex items-center gap-1.5"><i data-lucide="maximize-2" class="w-4 h-4 text-ocean-600"></i> 320 m²</span>
            </div>

            <a href="https://wa.me/5500000000000?text=Olá%20Keli,%20tenho%20interesse%20na%20Casa%20Pé%20na%20Areia" 
               target="_blank"
               class="mt-auto block text-center py-2.5 rounded-xl border border-coastal/20 font-medium text-coastal hover:bg-coastal hover:text-white transition text-sm">
              Saber Mais
            </a>
          </div>
        </div>

        <!-- CARD 2: ALUGUEL / ANUAL OU TEMPORADA -->
        <div class="bg-white rounded-2xl overflow-hidden border border-sand-200 shadow-sm hover:shadow-xl transition-all duration-300 flex flex-col">
          <div class="relative h-56 bg-slate-200">
            <img src="https://images.unsplash.com/photo-1502672260266-1c1ef2d93688?auto=format&fit=crop&w=700&q=80" alt="Apartamento Vista Mar" class="w-full h-full object-cover">
            <div class="absolute top-3 left-3 flex gap-2">
              <span class="bg-ocean-600 text-white text-[11px] font-bold px-3 py-1 rounded-full uppercase tracking-wider">Locação</span>
              <span class="bg-white/95 backdrop-blur-md text-ocean-800 text-[11px] font-semibold px-2.5 py-1 rounded-full flex items-center gap-1">
                <i data-lucide="eye" class="w-3 h-3 text-ocean-600"></i> Vista Mar
              </span>
            </div>
          </div>
          <div class="p-6 flex flex-col flex-grow">
            <span class="text-xs text-sand-600 font-medium">Orla Central</span>
            <h3 class="text-lg font-bold text-slate-900 mt-1 mb-2 font-serif">Apartamento Varanda Gourmet</h3>
            <p class="text-2xl font-serif font-bold text-coastal mb-4">R$ 4.200 <span class="text-xs font-normal text-slate-500">/mês</span></p>
            
            <div class="flex items-center justify-between text-xs text-slate-500 border-t border-sand-100 pt-4 mb-6">
              <span class="flex items-center gap-1.5"><i data-lucide="bed-single" class="w-4 h-4 text-ocean-600"></i> 2 Quartos</span>
              <span class="flex items-center gap-1.5"><i data-lucide="bath" class="w-4 h-4 text-ocean-600"></i> 2 Banheiros</span>
              <span class="flex items-center gap-1.5"><i data-lucide="car" class="w-4 h-4 text-ocean-600"></i> 1 Vaga</span>
            </div>

            <a href="https://wa.me/5500000000000?text=Olá%20Keli,%20tenho%20interesse%20no%20Apartamento%20Locação" 
               target="_blank"
               class="mt-auto block text-center py-2.5 rounded-xl border border-coastal/20 font-medium text-coastal hover:bg-coastal hover:text-white transition text-sm">
              Saber Mais
            </a>
          </div>
        </div>

        <!-- CARD 3: VENDA -->
        <div class="bg-white rounded-2xl overflow-hidden border border-sand-200 shadow-sm hover:shadow-xl transition-all duration-300 flex flex-col">
          <div class="relative h-56 bg-slate-200">
            <img src="https://images.unsplash.com/photo-1545324418-cc1a3fa10c00?auto=format&fit=crop&w=700&q=80" alt="Cobertura Duplex" class="w-full h-full object-cover">
            <div class="absolute top-3 left-3 flex gap-2">
              <span class="bg-coastal text-sand-50 text-[11px] font-bold px-3 py-1 rounded-full uppercase tracking-wider">Venda</span>
              <span class="bg-white/95 backdrop-blur-md text-amber-800 text-[11px] font-semibold px-2.5 py-1 rounded-full flex items-center gap-1">
                <i data-lucide="sun" class="w-3 h-3 text-amber-500"></i> Jacuzzi
              </span>
            </div>
          </div>
          <div class="p-6 flex flex-col flex-grow">
            <span class="text-xs text-sand-600 font-medium">Praia do Sol</span>
            <h3 class="text-lg font-bold text-slate-900 mt-1 mb-2 font-serif">Cobertura Duplex Panorâmica</h3>
            <p class="text-2xl font-serif font-bold text-coastal mb-4">R$ 2.400.000</p>
            
            <div class="flex items-center justify-between text-xs text-slate-500 border-t border-sand-100 pt-4 mb-6">
              <span class="flex items-center gap-1.5"><i data-lucide="bed-single" class="w-4 h-4 text-ocean-600"></i> 3 Suítes</span>
              <span class="flex items-center gap-1.5"><i data-lucide="bath" class="w-4 h-4 text-ocean-600"></i> 4 Banheiros</span>
              <span class="flex items-center gap-1.5"><i data-lucide="maximize-2" class="w-4 h-4 text-ocean-600"></i> 210 m²</span>
            </div>

            <a href="https://wa.me/5500000000000?text=Olá%20Keli,%20tenho%20interesse%20na%20Cobertura%20Duplex" 
               target="_blank"
               class="mt-auto block text-center py-2.5 rounded-xl border border-coastal/20 font-medium text-coastal hover:bg-coastal hover:text-white transition text-sm">
              Saber Mais
            </a>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- SOBRE COM DESTAQUE PARA CRECI E CNAI -->
  <section id="sobre" class="py-20 bg-white">
    <div class="max-w-4xl mx-auto px-4 sm:px-6">
      <div class="flex flex-col md:flex-row items-center gap-10">
        <div class="w-48 h-48 rounded-full overflow-hidden shrink-0 border-4 border-sand-200 shadow-md">
          <img src="https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?auto=format&fit=crop&w=400&q=80" 
               alt="Keli Martins - Corretora e Avaliadora" 
               class="w-full h-full object-cover">
        </div>
        <div class="space-y-4 text-center md:text-left">
          <span class="text-xs uppercase tracking-widest text-ocean-600 font-bold">Quem Sou Eu</span>
          <h2 class="text-3xl font-serif font-bold text-coastal">Keli Martins</h2>
          <p class="text-slate-600 text-sm sm:text-base leading-relaxed">
            Atuo com dedicação exclusiva no mercado imobiliário litorâneo unindo duas frentes fundamentais: a <strong>avaliação técnica e criteriosa de patrimônios</strong> para garantir decisões financeiras assertivas e a <strong>intermediação de compra, venda e locação</strong> de imóveis com alto padrão de atendimento.
          </p>
          
          <div class="flex flex-wrap justify-center md:justify-start gap-4 pt-2 text-xs font-semibold">
            <div class="bg-sand-100 px-3 py-1.5 rounded-lg text-coastal border border-sand-200">
              CRECI: <span class="font-bold">000000-F</span>
            </div>
            <div class="bg-ocean-50 px-3 py-1.5 rounded-lg text-ocean-800 border border-ocean-100">
              CNAI: <span class="font-bold">00000</span> (Avaliadora Imobiliária)
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- CTA FINAL -->
  <section class="py-16 bg-coastal text-white text-center">
    <div class="max-w-3xl mx-auto px-4">
      <h2 class="text-3xl font-serif font-bold mb-4">Como posso te ajudar hoje?</h2>
      <p class="text-sand-200 text-sm sm:text-base mb-8 max-w-xl mx-auto">
        Quer avaliar seu imóvel com valor técnico de mercado ou está em busca do lugar perfeito para viver na praia?
      </p>
      <div class="flex flex-col sm:flex-row justify-center gap-3">
        <a href="https://wa.me/5500000000000?text=Olá%20Keli,%20preciso%20de%20um%20laudo%20de%20avaliação%20imobiliária!" 
           target="_blank"
           class="inline-flex items-center justify-center gap-2 bg-ocean-500 hover:bg-ocean-600 text-white font-semibold px-7 py-3 rounded-full transition shadow-lg">
          <i data-lucide="clipboard-check" class="w-4 h-4"></i>
          <span>Solicitar Avaliação</span>
        </a>
        <a href="https://wa.me/5500000000000?text=Olá%20Keli,%20quero%20conhecer%20imóveis%20para%20venda%20ou%20aluguel!" 
           target="_blank"
           class="inline-flex items-center justify-center gap-2 bg-emerald-500 hover:bg-emerald-600 text-white font-semibold px-7 py-3 rounded-full transition shadow-lg">
          <i data-lucide="message-circle" class="w-4 h-4"></i>
          <span>Falar sobre Imóveis</span>
        </a>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="bg-slate-900 text-slate-400 py-10 text-xs border-t border-slate-800">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 flex flex-col sm:flex-row items-center justify-between gap-4">
      <div>
        <p class="text-white font-serif font-bold text-sm">Keli Martins</p>
        <p class="text-slate-500 mt-0.5">Corretora de Imóveis (CRECI) & Avaliadora Imobiliária Mercadológica (CNAI)</p>
      </div>
      <div class="flex items-center gap-6">
        <a href="#avaliacao" class="hover:text-white transition">Avaliação</a>
        <a href="#imoveis" class="hover:text-white transition">Imóveis</a>
        <a href="#sobre" class="hover:text-white transition">Sobre</a>
      </div>
    </div>
  </footer>

  <!-- BOTÃO FLUTUANTE DO WHATSAPP -->
  <a href="https://wa.me/5500000000000?text=Olá%20Keli,%20estou%20no%20seu%20site%20e%20gostaria%20de%20tirar%20uma%20dúvida!" 
     target="_blank" 
     class="fixed bottom-6 right-6 z-50 bg-emerald-500 hover:bg-emerald-600 text-white p-3.5 rounded-full shadow-lg shadow-emerald-500/30 flex items-center justify-center transition-transform hover:scale-110"
     title="Conversar no WhatsApp">
    <i data-lucide="message-circle" class="w-6 h-6"></i>
  </a>

  <!-- Script para ativar ícones -->
  <script>
    lucide.createIcons();
  </script>
</body>
</html>
