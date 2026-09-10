<!DOCTYPE html>
<html lang="pt-BR" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kelli Martins | Corretora e Avaliadora de Imóveis</title>
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts: Poppins -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    
    <!-- Configuração de Cores Customizadas no Tailwind -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Poppins', 'sans-serif'],
                    },
                    colors: {
                        praia: {
                            50: '#f8f9fa',
                            areia: '#fdfbf7',
                            azul: '#0077B6',
                            azulclaro: '#00b4d8',
                            whatsapp: '#25D366',
                            whatsapphover: '#1ebd5a'
                        }
                    }
                }
            }
        }
    </script>
</head>
<body class="font-sans bg-praia-50 text-gray-800 antialiased relative">

    <!-- CABEÇALHO (NAVBAR) -->
    <header class="bg-white shadow-md fixed w-full z-40 top-0">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <div class="text-praia-azul font-bold text-xl tracking-wide flex flex-col">
                <span>Kelli Martins</span>
                <span class="text-xs text-gray-500 font-normal">Corretora de Imóveis • CRECI: 323425</span>
            </div>
            <a href="#contato" class="hidden md:inline-block bg-praia-azul hover:bg-praia-azulclaro text-white font-semibold py-2 px-6 rounded-full transition duration-300 shadow-md">
                Falar com Kelli
            </a>
        </div>
    </header>

    <!-- HERO SECTION (DESTAQUE) -->
    <section class="relative w-full h-screen bg-cover bg-center flex items-center justify-center mt-12" style="background-image: url('https://images.unsplash.com/photo-1499793983690-e29da59ef1c2?ixlib=rb-4.0.3&auto=format&fit=crop&w=2070&q=80');">
        <div class="absolute inset-0 bg-black bg-opacity-50"></div>
        <div class="relative z-10 text-center px-4 max-w-3xl">
            <h1 class="text-4xl md:text-6xl font-bold text-white mb-6 leading-tight drop-shadow-lg">
                Comprar, vender ou alugar no litoral nunca foi tão fácil.
            </h1>
            <p class="text-lg md:text-2xl text-gray-200 mb-10 drop-shadow-md">
                Faço o possível para tornar mais seguro o processo do seu imóvel.
            </p>
            <a href="#contato" class="bg-praia-whatsapp hover:bg-praia-whatsapphover text-white font-bold py-4 px-8 rounded-full text-lg transition duration-300 shadow-xl inline-flex items-center gap-2 transform hover:-translate-y-1">
                <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/></svg>
                Encontrar Meu Imóvel
            </a>
        </div>
    </section>

    <!-- SOBRE KELLI MARTINS -->
    <section class="py-20 bg-white" id="sobre">
        <div class="container mx-auto px-6 max-w-5xl text-center">
            <h2 class="text-3xl md:text-4xl font-bold text-praia-azul mb-6">Sua Corretora de Confiança</h2>
            <p class="text-gray-600 text-lg mb-8 leading-relaxed">
                Especialista no litoral, ofereço <strong>assessoria completa do início do processo até a entrega das chaves</strong>. Meu objetivo é garantir que sua experiência imobiliária seja transparente, segura e alinhada com os seus sonhos.
            </p>
            <div class="inline-flex items-center justify-center gap-4 bg-praia-50 py-3 px-6 rounded-lg border border-gray-200 shadow-sm">
                <span class="text-gray-700 font-semibold">CRECI-SP: 323425</span>
                <span class="text-gray-300">|</span>
                <span class="text-gray-700 font-semibold">CNAI: 58458</span>
            </div>
        </div>
    </section>

    <!-- SERVIÇOS (GRID) -->
    <section class="py-20 bg-praia-areia" id="servicos">
        <div class="container mx-auto px-6 max-w-6xl">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">Como posso te ajudar?</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
                <!-- Cards de Serviço (mantidos como antes) -->
                <div class="bg-white p-6 rounded-xl shadow-md hover:shadow-xl transition duration-300 hover:-translate-y-1 border-b-4 border-praia-azulclaro">
                    <div class="text-praia-azul text-4xl mb-4">🏡</div>
                    <h3 class="font-bold text-xl mb-2">Compra e Venda</h3>
                    <p class="text-gray-600 text-sm">As melhores opções de imóveis no litoral para você investir ou morar.</p>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-md hover:shadow-xl transition duration-300 hover:-translate-y-1 border-b-4 border-praia-azulclaro">
                    <div class="text-praia-azul text-4xl mb-4">🏖️</div>
                    <h3 class="font-bold text-xl mb-2">Aluguel</h3>
                    <p class="text-gray-600 text-sm">Trabalho com locação anual e aluguel de temporada com total segurança.</p>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-md hover:shadow-xl transition duration-300 hover:-translate-y-1 border-b-4 border-praia-azulclaro">
                    <div class="text-praia-azul text-4xl mb-4">📄</div>
                    <h3 class="font-bold text-xl mb-2">Financiamento</h3>
                    <p class="text-gray-600 text-sm">Assessoria em financiamento imobiliário e crédito para construção ou reforma.</p>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-md hover:shadow-xl transition duration-300 hover:-translate-y-1 border-b-4 border-praia-azulclaro">
                    <div class="text-praia-azul text-4xl mb-4">🔍</div>
                    <h3 class="font-bold text-xl mb-2">Avaliação / Crédito</h3>
                    <p class="text-gray-600 text-sm">Avaliação precisa de imóveis e opções de crédito com garantia de imóvel.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- FORMULÁRIO DE CONTATO -->
    <section class="py-20 bg-white" id="contato">
        <div class="container mx-auto px-6 max-w-4xl flex flex-col md:flex-row gap-12 items-center">
            
            <div class="w-full md:w-1/2">
                <h2 class="text-3xl font-bold text-gray-800 mb-6">Vamos encontrar o lugar perfeito!</h2>
                <p class="text-gray-600 mb-6">
                    Preencha o formulário ao lado com seu nome e objetivo. Você será redirecionado para o meu WhatsApp para continuarmos o atendimento de forma rápida e humanizada.
                </p>
                <div class="flex items-center gap-4 mt-8">
                    <div class="bg-praia-azulclaro text-white p-4 rounded-full">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path></svg>
                    </div>
                    <div>
                        <p class="text-gray-500 text-sm">Contato Direto</p>
                        <p class="text-xl font-bold text-gray-800">(13) 97425-0913</p>
                    </div>
                </div>
            </div>

            <div class="w-full md:w-1/2 bg-praia-areia p-8 rounded-2xl shadow-xl border-t-4 border-praia-azul">
                <h3 class="text-2xl font-bold text-gray-800 mb-6 text-center">Fale comigo no WhatsApp</h3>
                
                <form id="whatsappForm" class="space-y-5">
                    <div>
                        <label class="block text-sm font-semibold text-gray-700 mb-1">Seu Nome</label>
                        <input type="text" id="nome" required placeholder="Ex: João da Silva" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-praia-azulclaro focus:border-praia-azulclaro outline-none transition">
                    </div>

                    <div>
                        <label class="block text-sm font-semibold text-gray-700 mb-1">Qual o seu objetivo?</label>
                        <select id="interesse" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-praia-azulclaro focus:border-praia-azulclaro outline-none transition bg-white">
                            <option value="Comprar um imóvel">Comprar um imóvel</option>
                            <option value="Vender meu imóvel">Vender meu imóvel</option>
                            <option value="Aluguel de temporada">Aluguel de temporada</option>
                            <option value="Aluguel anual">Aluguel anual</option>
                            <option value="Financiamento / Construção">Financiamento / Construção</option>
                            <option value="Avaliação de imóvel">Avaliação de imóvel</option>
                            <option value="Outro assunto">Outro assunto</option>
                        </select>
                    </div>

                    <button type="submit" class="w-full bg-praia-whatsapp hover:bg-praia-whatsapphover text-white font-bold py-3 px-4 rounded-lg flex justify-center items-center gap-2 transition duration-300 shadow-md">
                        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/></svg>
                        Iniciar Atendimento
                    </button>
                    <p class="text-xs text-center text-gray-500 mt-2">
                        Ao enviar, você concorda com nossa <button type="button" onclick="openModal()" class="text-praia-azul underline hover:text-praia-azulclaro">Política de Privacidade</button>.
                    </p>
                </form>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="bg-gray-900 text-gray-300 py-10">
        <div class="container mx-auto px-6 grid grid-cols-1 md:grid-cols-3 gap-8 items-center text-center md:text-left">
            
            <div class="flex flex-col">
                <span class="text-white text-2xl font-bold tracking-wide">Kelli Martins</span>
                <span class="text-sm mt-1">Corretora e Avaliadora de Imóveis</span>
                <span class="text-xs text-gray-500 mt-2">CRECI-SP: 323425 | CNAI: 58458</span>
            </div>

            <div class="text-sm text-gray-400 flex flex-col items-center gap-2">
                <p>"Faço o possível para tornar mais fácil e seguro o processo do seu imóvel."</p>
                <!-- Botão que abre o modal da Política -->
                <button onclick="openModal()" class="text-praia-azulclaro hover:text-white underline text-xs transition">Ler Política de Privacidade</button>
            </div>

            <div class="flex flex-col items-center md:items-end gap-2">
                <a href="https://www.instagram.com/kellimartins014?stkn=NWptdXVzOXg2dnI5" target="_blank" class="flex items-center gap-2 text-gray-300 hover:text-white transition">
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zM12 0C8.741 0 8.333.014 7.053.072 2.695.272.273 2.69.073 7.052.014 8.333 0 8.741 0 12c0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98C8.333 23.986 8.741 24 12 24c3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98C15.668.014 15.259 0 12 0zm0 5.838a6.162 6.162 0 100 12.324 6.162 6.162 0 000-12.324zM12 16a4 4 0 110-8 4 4 0 010 8zm6.406-11.845a1.44 1.44 0 100 2.881 1.44 1.44 0 000-2.881z"/></svg>
                    @kellimartins014
                </a>
            </div>
        </div>
    </footer>

    <!-- MODAL POLÍTICA DE PRIVACIDADE -->
    <div id="privacyModal" class="fixed inset-0 z-50 hidden flex items-center justify-center bg-black bg-opacity-60 transition-opacity">
        <div class="bg-white rounded-2xl shadow-2xl w-11/12 max-w-2xl max-h-[80vh] overflow-y-auto p-6 md:p-8 relative">
            <!-- Botão Fechar -->
            <button onclick="closeModal()" class="absolute top-4 right-4 text-gray-500 hover:text-gray-800 transition">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path></svg>
            </button>
            
            <h2 class="text-2xl font-bold text-praia-azul mb-4 border-b pb-2">Política de Privacidade</h2>
            
            <div class="text-gray-600 text-sm space-y-4">
                <p>A sua privacidade é importante para nós. É política de <strong>Kelli Martins - Corretora de Imóveis</strong> respeitar a sua privacidade em relação a qualquer informação sua que possamos coletar neste site.</p>
                
                <h3 class="font-bold text-gray-800 text-base">1. Coleta de Dados</h3>
                <p>Solicitamos informações pessoais, como Nome, apenas quando o usuário preenche o formulário para iniciar um atendimento via WhatsApp. Esses dados são utilizados única e exclusivamente para personalizar e iniciar a conversa no aplicativo de mensagens.</p>
                
                <h3 class="font-bold text-gray-800 text-base">2. Armazenamento e Compartilhamento</h3>
                <p>Os dados inseridos no formulário <strong>não são armazenados em nenhum banco de dados</strong> do site. Eles são convertidos em um link e enviados diretamente para o WhatsApp da corretora. Não compartilhamos informações de identificação pessoal publicamente ou com terceiros, exceto quando exigido por lei.</p>
                
                <h3 class="font-bold text-gray-800 text-base">3. Consentimento (LGPD)</h3>
                <p>Ao utilizar nosso formulário e clicar em "Iniciar Atendimento", você concorda com a coleta do seu nome e intenção de busca para fins de contato comercial direto via WhatsApp, em conformidade com a Lei Geral de Proteção de Dados (Lei nº 13.709/2018).</p>
                
                <p class="italic mt-4">Esta política é efetiva a partir de Setembro de 2026.</p>
            </div>

            <div class="mt-8 text-right">
                <button onclick="closeModal()" class="bg-gray-200 hover:bg-gray-300 text-gray-800 font-semibold py-2 px-6 rounded-lg transition">
                    Entendi e Fechar
                </button>
            </div>
        </div>
    </div>

    <!-- JAVASCRIPT (WHATSAPP E MODAL) -->
    <script>
        // Lógica do WhatsApp
        document.getElementById('whatsappForm').addEventListener('submit', function(e) {
            e.preventDefault(); 
            const nome = document.getElementById('nome').value;
            const interesse = document.getElementById('interesse').value;
            const telefone = '5513974250913'; 
            const mensagem = `Olá, Kelli! Meu nome é ${nome} e cheguei através do seu site. Estou interessado(a) em: ${interesse}. Podemos conversar?`;
            const urlWhatsapp = `https://wa.me/${telefone}?text=${encodeURIComponent(mensagem)}`;
            window.open(urlWhatsapp, '_blank');
        });

        // Lógica do Modal (Política de Privacidade)
        const modal = document.getElementById('privacyModal');

        function openModal() {
            modal.classList.remove('hidden');
        }

        function closeModal() {
            modal.classList.add('hidden');
        }

        // Fechar modal clicando fora do quadro branco
        modal.addEventListener('click', function(e) {
            if (e.target === modal) {
                closeModal();
            }
        });
    </script>
</body>
</html>
