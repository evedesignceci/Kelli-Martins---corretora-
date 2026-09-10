<!DOCTYPE html>
<html lang="pt-BR" class="scroll-smooth">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Keli Martins | Corretora de Imóveis</title>
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Google Fonts: Inter & Playfair Display para toque premium -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Playfair+Display:wght@600;700&display=swap" rel="stylesheet">
  <!-- Lucide Icons -->
  <script src="https://unpkg.com/lucide@latest"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
            serif: ['Playfair Display', 'serif'],
          },
          colors: {
            brand: {
              50: '#f8fafc',
              100: '#f1f5f9',
              800: '#1e293b',
              900: '#0f172a',
              gold: '#c59d5f',
              goldDark: '#a37e42'
            }
          }
        }
      }
    }
  </script>
</head>
<body class="bg-gray-50 text-slate-800 antialiased">

  <!-- NAVBAR -->
  <header class="sticky top-0 z-40 bg-white/90 backdrop-blur-md border-b border-gray-100">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 h-20 flex items-center justify-between">
      <a href="#" class="flex flex-col">
        <span class="font-serif text-2xl tracking-tight text-slate-900 font-bold">Keli Martins</span>
        <span class="text-xs uppercase tracking-widest text-brand-gold font-semibold -mt-1">Corretora de Imóveis</span>
      </a>

      <nav class="hidden md:flex items-center gap-8 text-sm font-medium text-slate-600">
        <a href="#imoveis" class="hover:text-slate-900 transition">Imóveis</a>
        <a href="#diferenciais" class="hover:text-slate-900 transition">Por que escolher</a>
        <a href="#sobre" class="hover:text-slate-900 transition">Sobre</a>
      </nav>

      <a href="https://wa.me/5500000000000?text=Olá%20Keli,%20gostaria%20de%20saber%20mais%20sobre%20os%20imóveis!" 
         target="_blank"
         class="inline-flex items-center gap-2 bg-slate-900 text-white text-sm font-medium px-5 py-2.5 rounded-full hover:bg-slate-800 transition shadow-sm">
        <i data-lucide="message-circle" class="w-4 h-4 text-brand-gold"></i>
        <span>Falar no WhatsApp</span>
      </a>
    </div>
  </header>

  <!-- HERO SECTION -->
  <section class="relative bg-gradient-to-b from-white to-slate-100 py-16 lg:py-24 border-b border-gray-100">
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="grid lg:grid-cols-12 gap-12 items-center">
        
        <!-- Texto Principal -->
        <div class="lg:col-span-7 space-y-6">
          <div class="inline-flex items-center gap-2 bg-amber-50 border border-amber-200/60 px-3 py-1.5 rounded-full text-amber-800 text-xs font-semibold">
            <i data-lucide="sparkles" class="w-3.5 h-3.5"></i>
            <span>Assessoria Imobiliária Completa</span>
          </div>

          <h1 class="text-4xl sm:text-5xl font-serif text-slate-900 leading-tight">
            Encontre o imóvel ideal para <span class="text-brand-gold italic">viver momentos</span> inesquecíveis.
          </h1>

          <p class="text-slate-600 text-base sm:text-lg leading-relaxed max-w-xl">
            Venda e locação com transparência, segurança jurídica e atendimento focado no que você e sua família realmente precisam.
          </p>

          <!-- Filtro Rápido / Simulação -->
          <div class="bg-white p-4 sm:p-5 rounded-2xl shadow-lg shadow-slate-200/50 border border-slate-100 max-w-xl">
            <div class="grid sm:grid-cols-3 gap-3">
              <div>
                <label class="text-xs font-semibold text-slate-500 uppercase tracking-wider">Finalidade</label>
                <select class="w-full mt-1.5 p-2.5 bg-slate-50 border border-slate-200 rounded-lg text-sm focus:outline-none focus:border-slate-800">
                  <option>Comprar</option>
                  <option>Alugar</option>
                </select>
              </div>
              <div>
                <label class="text-xs font-semibold text-slate-500 uppercase tracking-wider">Tipo</label>
                <select class="w-full mt-1.5 p-2.5 bg-slate-50 border border-slate-200 rounded-lg text-sm focus:outline-none focus:border-slate-800">
                  <option>Apartamento</option>
                  <option>Casa / Sobrado</option>
                  <option>Comercial</option>
                </select>
              </div>
              <div class="flex items-end">
                <a href="#imoveis" class="w-full flex items-center justify-center gap-2 bg-brand-gold hover:bg-brand-goldDark text-white font-medium p-2.5 rounded-lg text-sm transition">
                  <i data-lucide="search" class="w-4 h-4"></i>
                  <span>Buscar</span>
                </a>
              </div>
            </div>
          </div>
        </div>

        <!-- Card Visual / Imagem Destacada -->
        <div class="lg:col-span-5 relative">
          <div class="relative mx-auto max-w-sm rounded-3xl overflow-hidden shadow-2xl border-4 border-white">
            <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=800&q=80" 
                 alt="Imóvel Moderno" 
                 class="w-full h-[440px] object-cover">
            <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent flex flex-col justify-end p-6 text-white">
              <span class="text-xs bg-brand-gold px-2.5 py-1 rounded-md font-semibold self-start mb-2">Destaque</span>
              <h3 class="text-xl font-serif font-bold">Casa Alto Padrão</h3>
              <p class="text-xs text-slate-200 mt-1">Conforto, segurança e área de lazer completa.</p>
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- DIFERENCIAIS -->
  <section id="diferenciais" class="py-16 bg-white">
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="grid md:grid-cols-3 gap-8">
        
        <div class="flex items-start gap-4 p-5 rounded-xl border border-slate-100 hover:border-slate-200 transition">
          <div class="w-12 h-12 rounded-xl bg-amber-50 flex items-center justify-center shrink-0 text-brand-gold">
            <i data-lucide="shield-check" class="w-6 h-6"></i>
          </div>
          <div>
            <h4 class="font-semibold text-slate-900 mb-1">Segurança Contratual</h4>
            <p class="text-sm text-slate-500 leading-relaxed">Assessoria minuciosa em documentação e vistorias para locação ou compra sem surpresas.</p>
          </div>
        </div>

        <div class="flex items-start gap-4 p-5 rounded-xl border border-slate-100 hover:border-slate-200 transition">
          <div class="w-12 h-12 rounded-xl bg-amber-50 flex items-center justify-center shrink-0 text-brand-gold">
            <i data-lucide="heart-handshake" class="w-6 h-6"></i>
          </div>
          <div>
            <h4 class="font-semibold text-slate-900 mb-1">Atendimento Humanizado</h4>
            <p class="text-sm text-slate-500 leading-relaxed">Você fala direto com a corretora, recebendo atenção personalizada do início ao pós-chaves.</p>
          </div>
        </div>

        <div class="flex items-start gap-4 p-5 rounded-xl border border-slate-100 hover:border-slate-200 transition">
          <div class="w-12 h-12 rounded-xl bg-amber-50 flex items-center justify-center shrink-0 text-brand-gold">
            <i data-lucide="key-round" class="w-6 h-6"></i>
          </div>
          <div>
            <h4 class="font-semibold text-slate-900 mb-1">Agilidade na Locação</h4>
            <p class="text-sm text-slate-500 leading-relaxed">Processos desburocratizados e suporte na análise de cadastro de locatários e proprietários.</p>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- LISTA DE IMÓVEIS (VITRINE) -->
  <section id="imoveis" class="py-20 bg-slate-50">
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      
      <div class="flex flex-col sm:flex-row sm:items-end justify-between mb-12 gap-4">
        <div>
          <span class="text-xs uppercase tracking-widest text-brand-gold font-bold">Oportunidades</span>
          <h2 class="text-3xl font-serif font-bold text-slate-900 mt-1">Imóveis em Destaque</h2>
        </div>
        <p class="text-sm text-slate-500 max-w-xs">Confira algumas das melhores opções para venda e locação disponíveis no momento.</p>
      </div>

      <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-8">
        
        <!-- CARD 1: VENDA -->
        <div class="bg-white rounded-2xl overflow-hidden border border-slate-200/80 shadow-sm hover:shadow-md transition flex flex-col">
          <div class="relative h-56 bg-slate-200">
            <img src="https://images.unsplash.com/photo-1545324418-cc1a3fa10c00?auto=format&fit=crop&w=700&q=80" alt="Apartamento" class="w-full h-full object-cover">
            <span class="absolute top-3 left-3 bg-slate-900 text-white text-xs font-bold px-3 py-1 rounded-full uppercase tracking-wider">Venda</span>
          </div>
          <div class="p-6 flex flex-col flex-grow">
            <span class="text-xs text-slate-400 font-medium">Bairro Nobre</span>
            <h3 class="text-lg font-bold text-slate-900 mt-1 mb-2">Apartamento com Sacada Gourmet</h3>
            <p class="text-2xl font-serif font-bold text-slate-900 mb-4">R$ 420.000</p>
            
            <div class="flex items-center gap-4 text-xs text-slate-500 border-t border-slate-100 pt-4 mb-6">
              <span class="flex items-center gap-1.5"><i data-lucide="bed-single" class="w-4 h-4"></i> 2 Quartos</span>
              <span class="flex items-center gap-1.5"><i data-lucide="bath" class="w-4 h-4"></i> 1 Suíte</span>
              <span class="flex items-center gap-1.5"><i data-lucide="car" class="w-4 h-4"></i> 1 Vaga</span>
            </div>

            <a href="https://wa.me/5500000000000?text=Olá%20Keli,%20tenho%20interesse%20no%20Apartamento%20com%20Sacada" 
               target="_blank"
               class="mt-auto block text-center py-2.5 rounded-xl border border-slate-300 font-medium text-slate-700 hover:bg-slate-900 hover:text-white hover:border-slate-900 transition text-sm">
              Mais Detalhes
            </a>
          </div>
        </div>

        <!-- CARD 2: ALUGUEL -->
        <div class="bg-white rounded-2xl overflow-hidden border border-slate-200/80 shadow-sm hover:shadow-md transition flex flex-col">
          <div class="relative h-56 bg-slate-200">
            <img src="https://images.unsplash.com/photo-1512917774080-9991f1c4c750?auto=format&fit=crop&w=700&q=80" alt="Casa" class="w-full h-full object-cover">
            <span class="absolute top-3 left-3 bg-brand-gold text-white text-xs font-bold px-3 py-1 rounded-full uppercase tracking-wider">Locação</span>
          </div>
          <div class="p-6 flex flex-col flex-grow">
            <span class="text-xs text-slate-400 font-medium">Condomínio Fechado</span>
            <h3 class="text-lg font-bold text-slate-900 mt-1 mb-2">Casa Aconchegante c/ Quintal</h3>
            <p class="text-2xl font-serif font-bold text-slate-900 mb-4">R$ 2.800 <span class="text-xs font-normal text-slate-500">/mês</span></p>
            
            <div class="flex items-center gap-4 text-xs text-slate-500 border-t border-slate-100 pt-4 mb-6">
              <span class="flex items-center gap-1.5"><i data-lucide="bed-single" class="w-4 h-4"></i> 3 Quartos</span>
              <span class="flex items-center gap-1.5"><i data-lucide="bath" class="w-4 h-4"></i> 2 Banheiros</span>
              <span class="flex items-center gap-1.5"><i data-lucide="car" class="w-4 h-4"></i> 2 Vagas</span>
            </div>

            <a href="https://wa.me/5500000000000?text=Olá%20Keli,%20tenho%20interesse%20na%20Casa%20Aconchegante" 
               target="_blank"
               class="mt-auto block text-center py-2.5 rounded-xl border border-slate-300 font-medium text-slate-700 hover:bg-slate-900 hover:text-white hover:border-slate-900 transition text-sm">
              Mais Detalhes
            </a>
          </div>
        </div>

        <!-- CARD 3: VENDA -->
        <div class="bg-white rounded-2xl overflow-hidden border border-slate-200/80 shadow-sm hover:shadow-md transition flex flex-col">
          <div class="relative h-56 bg-slate-200">
            <img src="https://images.unsplash.com/photo-1502672260266-1c1ef2d93688?auto=format&fit=crop&w=700&q=80" alt="Studio" class="w-full h-full object-cover">
            <span class="absolute top-3 left-3 bg-slate-900 text-white text-xs font-bold px-3 py-1 rounded-full uppercase tracking-wider">Venda</span>
          </div>
          <div class="p-6 flex flex-col flex-grow">
            <span class="text-xs text-slate-400 font-medium">Centro</span>
            <h3 class="text-lg font-bold text-slate-900 mt-1 mb-2">Studio Compacto e Moderno</h3>
            <p class="text-2xl font-serif font-bold text-slate-900 mb-4">R$ 260.000</p>
            
            <div class="flex items-center gap-4 text-xs text-slate-500 border-t border-slate-100 pt-4 mb-6">
              <span class="flex items-center gap-1.5"><i data-lucide="bed-single" class="w-4 h-4"></i> 1 Quarto</span>
              <span class="flex items-center gap-1.5"><i data-lucide="bath" class="w-4 h-4"></i> 1 Banheiro</span>
              <span class="flex items-center gap-1.5"><i data-lucide="maximize-2" class="w-4 h-4"></i> 38 m²</span>
            </div>

            <a href="https://wa.me/5500000000000?text=Olá%20Keli,%20tenho%20interesse%20no%20Studio%20Compacto" 
               target="_blank"
               class="mt-auto block text-center py-2.5 rounded-xl border border-slate-300 font-medium text-slate-700 hover:bg-slate-900 hover:text-white hover:border-slate-900 transition text-sm">
              Mais Detalhes
            </a>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- SOBRE A CORRETORA -->
  <section id="sobre" class="py-20 bg-white border-t border-slate-100">
    <div class="max-w-4xl mx-auto px-4 sm:px-6">
      <div class="flex flex-col md:flex-row items-center gap-10">
        <div class="w-44 h-44 rounded-full overflow-hidden shrink-0 border-4 border-amber-100 shadow-md">
          <img src="https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?auto=format&fit=crop&w=400&q=80" 
               alt="Keli Martins" 
               class="w-full h-full object-cover">
        </div>
        <div class="space-y-4 text-center md:text-left">
          <span class="text-xs uppercase tracking-widest text-brand-gold font-bold">Quem sou eu</span>
          <h2 class="text-3xl font-serif font-bold text-slate-900">Keli Martins</h2>
          <p class="text-slate-600 text-sm leading-relaxed">
            Sou especialista em conectar pessoas ao lugar certo para morar ou investir. Seja para alugar com tranquilidade ou adquirir seu imóvel próprio, presto uma assessoria completa com transparência, suporte jurídico e dedicação exclusiva.
          </p>
          <div class="pt-2 text-xs font-semibold text-slate-500">
            CRECI: <span class="text-slate-800 font-bold">000000-F</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="bg-slate-900 text-slate-400 py-10 text-sm border-t border-slate-800">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 flex flex-col sm:flex-row items-center justify-between gap-4">
      <div class="text-center sm:text-left">
        <p class="text-white font-serif font-bold">Keli Martins Corretora de Imóveis</p>
        <p class="text-xs text-slate-500 mt-0.5">Todos os direitos reservados.</p>
      </div>
      <div class="flex items-center gap-6 text-xs">
        <a href="#imoveis" class="hover:text-white transition">Imóveis</a>
        <a href="#sobre" class="hover:text-white transition">Sobre</a>
        <a href="https://wa.me/5500000000000" target="_blank" class="hover:text-white transition">Contato</a>
      </div>
    </div>
  </footer>

  <!-- BOTÃO FLUTUANTE DO WHATSAPP (Ótimo para Mobile UX) -->
  <a href="https://wa.me/5500000000000?text=Olá%20Keli,%20estou%20no%20seu%20site%20e%20gostaria%20de%20tirar%20uma%20dúvida!" 
     target="_blank" 
     class="fixed bottom-6 right-6 z-50 bg-emerald-500 hover:bg-emerald-600 text-white p-3.5 rounded-full shadow-lg shadow-emerald-500/30 flex items-center justify-center transition-transform hover:scale-105"
     title="Conversar no WhatsApp">
    <i data-lucide="message-circle" class="w-6 h-6"></i>
  </a>

  <!-- Inicializa os ícones -->
  <script>
    lucide.createIcons();
  </script>
</body>
</html>
