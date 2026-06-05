<!DOCTYPE html>
<html lang="pt-BR" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projeto Liberdade Digital | Renda Online Premium</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        deepBlack: '#050505',
                        neonGreen: '#A3FF12',
                        premiumGray: '#121212',
                        borderGray: '#1F1F1F',
                        softGray: '#A0A0A0'
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        mono: ['JetBrains Mono', 'monospace']
                    },
                    animation: {
                        'pulse-slow': 'pulse 4s cubic-bezier(0.4, 0, 0.6, 1) infinite',
                        'glow-pulse': 'glow 3s infinite alternate',
                        'marquee': 'marquee 25s linear infinite',
                    },
                    keyframes: {
                        glow: {
                            '0%': { opacity: '0.3', filter: 'blur(40px)' },
                            '100%': { opacity: '0.6', filter: 'blur(60px)' }
                        },
                        marquee: {
                            '0%': { transform: 'translateX(0%)' },
                            '100%': { transform: 'translateX(-50%)' }
                        }
                    }
                }
            }
        }
    </script>
    <!-- Google Fonts (Inter & JetBrains Mono) -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&family=JetBrains+Mono:wght@400;700&display=swap" rel="stylesheet">
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #050505;
            color: #ffffff;
            overflow-x: hidden;
        }
        /* Custom Scrollbar */
        ::-webkit-scrollbar {
            width: 6px;
        }
        ::-webkit-scrollbar-track {
            background: #050505;
        }
        ::-webkit-scrollbar-thumb {
            background: #1f1f1f;
            border-radius: 3px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #A3FF12;
        }
        /* Smooth glowing text */
        .neon-text-glow {
            text-shadow: 0 0 12px rgba(163, 255, 18, 0.3);
        }
    </style>
</head>
<body class="antialiased selection:bg-neonGreen selection:text-black">

    <!-- TOP BAR FIXED & ANIMATED -->
    <div class="fixed top-0 left-0 w-full z-50 bg-deepBlack/85 backdrop-blur-md border-b border-borderGray">
        <div class="overflow-hidden py-2.5 relative w-full">
            <div class="flex whitespace-nowrap animate-marquee text-xs font-mono tracking-wider text-neutral-300">
                <!-- Ticker items duplicated for infinite seamless scrolling -->
                <div class="flex items-center gap-12 pr-12">
                    <span class="flex items-center gap-2"><span class="inline-block w-2 h-2 rounded-full bg-red-500 animate-ping"></span> 🔥 23 novos alunos entraram hoje</span>
                    <span class="text-neonGreen">|</span>
                    <span class="flex items-center gap-2"><i class="fa-regular fa-clock text-neonGreen"></i> Oferta promocional disponível por tempo limitado</span>
                    <span class="text-neonGreen">|</span>
                    <span class="flex items-center gap-2"><i class="fa-solid fa-shield-halved text-neonGreen"></i> Acesso imediato após aprovação do pagamento</span>
                </div>
                <div class="flex items-center gap-12 pr-12">
                    <span class="flex items-center gap-2"><span class="inline-block w-2 h-2 rounded-full bg-red-500 animate-ping"></span> 🔥 23 novos alunos entraram hoje</span>
                    <span class="text-neonGreen">|</span>
                    <span class="flex items-center gap-2"><i class="fa-regular fa-clock text-neonGreen"></i> Oferta promocional disponível por tempo limitado</span>
                    <span class="text-neonGreen">|</span>
                    <span class="flex items-center gap-2"><i class="fa-solid fa-shield-halved text-neonGreen"></i> Acesso imediato após aprovação do pagamento</span>
                </div>
                <div class="flex items-center gap-12 pr-12">
                    <span class="flex items-center gap-2"><span class="inline-block w-2 h-2 rounded-full bg-red-500 animate-ping"></span> 🔥 23 novos alunos entraram hoje</span>
                    <span class="text-neonGreen">|</span>
                    <span class="flex items-center gap-2"><i class="fa-regular fa-clock text-neonGreen"></i> Oferta promocional disponível por tempo limitado</span>
                    <span class="text-neonGreen">|</span>
                    <span class="flex items-center gap-2"><i class="fa-solid fa-shield-halved text-neonGreen"></i> Acesso imediato após aprovação do pagamento</span>
                </div>
            </div>
        </div>
    </div>

    <!-- HERO SECTION WITH DEEP GRAPHICS -->
    <section class="relative min-h-screen pt-28 pb-20 flex flex-col justify-center items-center px-4 md:px-8 overflow-hidden">
        <!-- Ambient Neon Glow Blobs (Premium Fintech Atmosphere) -->
        <div class="absolute top-1/4 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[350px] sm:w-[500px] h-[350px] sm:h-[500px] bg-neonGreen/10 rounded-full filter blur-[100px] pointer-events-none animate-glow-pulse"></div>
        <div class="absolute bottom-10 right-10 w-[250px] h-[250px] bg-neonGreen/5 rounded-full filter blur-[80px] pointer-events-none"></div>

        <!-- Background grid lines reminiscent of modern trading terminals -->
        <div class="absolute inset-0 bg-[linear-gradient(to_right,#1f1f1f_1px,transparent_1px),linear-gradient(to_bottom,#1f1f1f_1px,transparent_1px)] bg-[size:4rem_4rem] [mask-image:radial-gradient(ellipse_60%_50%_at_50%_50%,#000_70%,transparent_100%)] opacity-20 pointer-events-none"></div>

        <div class="max-w-7xl w-full grid grid-cols-1 lg:grid-cols-12 gap-12 items-center relative z-10 mt-6 sm:mt-10">
            
            <!-- Left Side: Copywriting -->
            <div class="lg:col-span-7 flex flex-col justify-center text-left space-y-8">
                <!-- Tech Badge -->
                <div class="inline-flex items-center self-start gap-2 px-3 py-1.5 rounded-full bg-neutral-900 border border-neutral-800 text-xs font-mono text-neonGreen">
                    <span class="flex h-2 w-2 relative">
                        <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-neonGreen opacity-75"></span>
                        <span class="relative inline-flex rounded-full h-2 w-2 bg-neonGreen"></span>
                    </span>
                    SISTEMA DE MONETIZAÇÃO ATIVO v3.4
                </div>

                <!-- Giant Title -->
                <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold tracking-tight leading-[1.1] text-white">
                    VOCÊ NÃO PRECISA DEPENDER DE UM <span class="text-neonGreen underline decoration-2 underline-offset-8 neon-text-glow">ÚNICO SALÁRIO</span> PELO RESTO DA VIDA.
                </h1>

                <!-- Subtitle -->
                <p class="text-base sm:text-lg text-neutral-400 max-w-xl font-light leading-relaxed">
                    Descubra o método que está ajudando pessoas comuns a iniciar uma fonte de renda online utilizando apenas um celular e conexão com a internet.
                </p>

                <!-- Action Button -->
                <div class="flex flex-col sm:flex-row items-stretch sm:items-center gap-4">
                    <a href="https://pay.cakto.com.br/3ftpayw_915159" 
                       class="group relative inline-flex items-center justify-center px-8 py-5 text-base font-bold text-black bg-neonGreen rounded-lg overflow-hidden transition-all duration-300 hover:shadow-[0_0_35px_rgba(163,255,18,0.5)] active:scale-[0.98]">
                        <span class="absolute inset-0 w-full h-full bg-white/20 transform -skew-x-12 -translate-x-full group-hover:animate-none group-hover:translate-x-full transition-transform duration-1000 ease-out"></span>
                        QUERO COMEÇAR AGORA
                        <i class="fa-solid fa-arrow-right ml-3 transition-transform group-hover:translate-x-1"></i>
                    </a>
                </div>

                <!-- Trust Badges below Hero Button -->
                <div class="grid grid-cols-3 gap-3 pt-4 border-t border-borderGray max-w-lg">
                    <div class="flex items-center gap-2 text-xs font-mono text-neutral-400">
                        <i class="fa-regular fa-circle-check text-neonGreen text-sm"></i>
                        <span>Acesso imediato</span>
                    </div>
                    <div class="flex items-center gap-2 text-xs font-mono text-neutral-400">
                        <i class="fa-solid fa-shield-halved text-neonGreen text-sm"></i>
                        <span>Garantia de 7 dias</span>
                    </div>
                    <div class="flex items-center gap-2 text-xs font-mono text-neutral-400">
                        <i class="fa-solid fa-tags text-neonGreen text-sm"></i>
                        <span>Apenas R$ 67,90</span>
                    </div>
                </div>
            </div>

            <!-- Right Side: Interactive CSS iPhone mockup & blurred Cakto dashboard -->
            <div class="lg:col-span-5 relative flex justify-center items-center w-full min-h-[500px]">
                
                <!-- Blurred Cakto Dashboard Backdrop (CSS Generated to look ultra startup-techy) -->
                <div class="absolute inset-0 bg-neutral-950/40 rounded-3xl border border-neutral-900 overflow-hidden backdrop-blur-[6px] p-6 shadow-2xl scale-95 origin-center pointer-events-none">
                    <div class="flex justify-between items-center mb-6 border-b border-neutral-900 pb-4">
                        <div class="flex items-center gap-2">
                            <div class="w-3 h-3 rounded-full bg-red-500/60"></div>
                            <div class="w-3 h-3 rounded-full bg-yellow-500/60"></div>
                            <div class="w-3 h-3 rounded-full bg-green-500/60"></div>
                        </div>
                        <span class="text-[10px] font-mono text-neutral-500">cakto.com/dashboard/analytics</span>
                    </div>
                    <!-- Mock chart curves made with clean borders -->
                    <div class="space-y-4">
                        <div class="flex justify-between items-end h-28 pt-4">
                            <div class="w-8 bg-neutral-900 h-12 rounded"></div>
                            <div class="w-8 bg-neutral-900 h-20 rounded"></div>
                            <div class="w-8 bg-neutral-900 h-16 rounded"></div>
                            <div class="w-8 bg-neonGreen/20 h-24 border-t-2 border-neonGreen rounded"></div>
                            <div class="w-8 bg-neonGreen/30 h-28 border-t-2 border-neonGreen rounded"></div>
                        </div>
                        <div class="h-px bg-neutral-900 w-full"></div>
                        <div class="flex justify-between text-[10px] font-mono text-neutral-600">
                            <span>SEG</span><span>TER</span><span>QUA</span><span>QUI</span><span>SEX</span>
                        </div>
                        <div class="grid grid-cols-2 gap-4 pt-4">
                            <div class="bg-neutral-900/60 p-3 rounded-lg border border-neutral-800">
                                <span class="text-[9px] font-mono text-neutral-500 block uppercase">SALDO DISPONÍVEL</span>
                                <span class="text-sm font-bold text-white">R$ 14.892,10</span>
                            </div>
                            <div class="bg-neutral-900/60 p-3 rounded-lg border border-neutral-800">
                                <span class="text-[9px] font-mono text-neutral-500 block uppercase">CONVERSÃO DE LEAD</span>
                                <span class="text-sm font-bold text-neonGreen">89.4%</span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Foreground: Pure CSS iPhone 15 Pro displaying results dynamically -->
                <div class="relative w-[280px] h-[560px] bg-neutral-950 rounded-[45px] border-[6px] border-neutral-800 shadow-[0_25px_50px_-12px_rgba(0,0,0,0.8)] z-20 flex flex-col overflow-hidden ring-1 ring-white/10">
                    
                    <!-- Dynamic Island / Notch -->
                    <div class="absolute top-3 left-1/2 -translate-x-1/2 w-24 h-5 bg-black rounded-full z-30 flex items-center justify-between px-3">
                        <span class="w-1.5 h-1.5 rounded-full bg-neutral-900"></span>
                        <span class="w-5 h-1 bg-neutral-950 rounded-full"></span>
                    </div>

                    <!-- Screen Content -->
                    <div class="w-full h-full bg-[#0a0a0a] pt-10 px-4 flex flex-col justify-between text-white font-sans relative">
                        <!-- Custom mobile status icons -->
                        <div class="absolute top-3 left-6 right-6 flex justify-between text-[10px] font-mono text-neutral-400">
                            <span>15:23</span>
                            <div class="flex items-center gap-1">
                                <i class="fa-solid fa-signal"></i>
                                <i class="fa-solid fa-wifi"></i>
                                <i class="fa-solid fa-battery-three-quarters"></i>
                            </div>
                        </div>

                        <!-- Inner Header/Mock App Logo -->
                        <div class="flex justify-between items-center pt-2">
                            <span class="font-mono text-xs text-neonGreen tracking-tighter">LIBERDADE APP</span>
                            <span class="px-2 py-0.5 rounded-full bg-neonGreen/10 border border-neonGreen/30 text-[8px] font-mono text-neonGreen">LIVE UPDATE</span>
                        </div>

                        <!-- Main Screen Indicator -->
                        <div class="flex-1 flex flex-col justify-center items-center py-4 space-y-6">
                            <div class="text-center">
                                <p class="text-[10px] font-mono text-neutral-500 uppercase tracking-widest">FATURAMENTO DOS ALUNOS HOJE</p>
                                <h4 class="text-2xl font-black mt-1 text-white">R$ 38.490,00</h4>
                                <span class="text-[9px] font-mono text-neonGreen bg-neonGreen/5 px-2 py-0.5 rounded-full border border-neonGreen/20 inline-block mt-2">+124.5% esta semana</span>
                            </div>

                            <!-- Live notification push simulator (Animates dynamically every few seconds) -->
                            <div id="phone-notification" class="w-full bg-neutral-900/90 border border-neutral-800 p-3 rounded-xl shadow-lg transition-all duration-500 transform translate-y-0 opacity-100 scale-100">
                                <div class="flex items-start gap-2.5">
                                    <div class="w-6 h-6 rounded-full bg-neonGreen flex items-center justify-center text-black text-[10px]">
                                        <i class="fa-solid fa-wallet"></i>
                                    </div>
                                    <div class="flex-1">
                                        <div class="flex justify-between items-center">
                                            <span class="text-[9px] font-bold text-neutral-300">CAKTO PAYMENTS</span>
                                            <span class="text-[8px] font-mono text-neutral-500">agora mesmo</span>
                                        </div>
                                        <p class="text-[10px] text-white font-medium mt-0.5">Venda de R$ 67,90 realizada!</p>
                                        <p class="text-[8px] text-neutral-400">Comissão de R$ 54,32 aprovada.</p>
                                    </div>
                                </div>
                            </div>

                            <!-- Quick static elements -->
                            <div class="w-full bg-neutral-900/40 border border-neutral-900 p-3 rounded-xl">
                                <div class="flex justify-between text-[10px] text-neutral-500 pb-2 border-b border-neutral-900">
                                    <span>Últimas transações</span>
                                    <span>Ver todas</span>
                                </div>
                                <div class="space-y-2 pt-2">
                                    <div class="flex justify-between text-[9px]">
                                        <span class="text-neutral-300">Amanda S. via Pix</span>
                                        <span class="text-neonGreen font-bold font-mono">+R$ 67,90</span>
                                    </div>
                                    <div class="flex justify-between text-[9px]">
                                        <span class="text-neutral-300">Marcos O. via Cartão</span>
                                        <span class="text-neonGreen font-bold font-mono">+R$ 67,90</span>
                                    </div>
                                    <div class="flex justify-between text-[9px]">
                                        <span class="text-neutral-300">Juliana M. via Pix</span>
                                        <span class="text-neonGreen font-bold font-mono">+R$ 67,90</span>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Micro-footer inside iPhone -->
                        <div class="pb-3 text-center border-t border-neutral-900 pt-2">
                            <span class="text-[9px] font-mono text-neutral-600">Acesso via smartphone ou tablet</span>
                        </div>
                    </div>
                </div>

                <!-- Soft visual connector to anchor the phone -->
                <div class="absolute bottom-4 left-1/2 -translate-x-1/2 w-48 h-12 bg-neonGreen/10 rounded-full blur-xl pointer-events-none"></div>
            </div>

        </div>
    </section>

    <!-- FINANCIAL SIMULATOR WIDGET (FINTECH VIBE) -->
    <section class="py-12 bg-neutral-950 border-y border-neutral-900 px-4">
        <div class="max-w-4xl mx-auto text-center space-y-6">
            <span class="font-mono text-xs text-neonGreen tracking-widest uppercase">SIMULADOR INTEGRADO</span>
            <h3 class="text-2xl font-extrabold text-white">Quanto você gera se fizer apenas 1 venda por dia?</h3>
            <p class="text-neutral-400 text-sm max-w-lg mx-auto">Muitos acham difícil, mas a matemática do mercado digital é transparente. Veja o poder das comissões acumuladas.</p>
            
            <div class="bg-deepBlack border border-borderGray p-6 sm:p-8 rounded-2xl max-w-2xl mx-auto space-y-6">
                <div class="flex flex-col sm:flex-row justify-between gap-6">
                    <div class="text-left">
                        <label class="text-xs font-mono text-neutral-500 block uppercase">Vendas por dia</label>
                        <div class="flex items-center gap-4 mt-2">
                            <button onclick="updateSim(-1)" class="w-10 h-10 rounded-lg bg-neutral-900 border border-neutral-800 text-white hover:text-neonGreen font-bold flex items-center justify-center">-</button>
                            <span id="sim-sales-count" class="text-3xl font-bold font-mono text-white">1</span>
                            <button onclick="updateSim(1)" class="w-10 h-10 rounded-lg bg-neutral-900 border border-neutral-800 text-white hover:text-neonGreen font-bold flex items-center justify-center">+</button>
                        </div>
                    </div>
                    <div class="text-left sm:text-right flex flex-col justify-end">
                        <span class="text-xs font-mono text-neutral-500 block uppercase">Faturamento Diário Est.</span>
                        <span id="sim-daily" class="text-2xl font-bold text-white mt-1">R$ 67,90</span>
                    </div>
                </div>

                <div class="h-px bg-neutral-900"></div>

                <div class="grid grid-cols-2 gap-4">
                    <div class="p-4 bg-neutral-900/40 rounded-xl border border-neutral-900 text-left">
                        <span class="text-[10px] font-mono text-neutral-500 block">PROJEÇÃO MENSAL</span>
                        <span id="sim-monthly" class="text-xl sm:text-2xl font-bold text-neonGreen font-mono mt-1">R$ 2.037,00</span>
                    </div>
                    <div class="p-4 bg-neutral-900/40 rounded-xl border border-neutral-900 text-left">
                        <span class="text-[10px] font-mono text-neutral-500 block">PROJEÇÃO ANUAL</span>
                        <span id="sim-yearly" class="text-xl sm:text-2xl font-bold text-white font-mono mt-1">R$ 24.444,00</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ASYMMETRIC IMPACT BLOCKS SECTION (INSTEAD OF CARDS) -->
    <section class="py-24 relative px-4 md:px-8">
        <div class="max-w-7xl mx-auto">
            
            <div class="text-center md:text-left space-y-4 mb-16">
                <span class="text-xs font-mono text-neonGreen tracking-wider uppercase bg-neonGreen/5 px-3 py-1.5 rounded-full border border-neonGreen/20">A Realidade Financeira Atual</span>
                <h2 class="text-3xl sm:text-4xl lg:text-5xl font-extrabold tracking-tight max-w-3xl">
                    POR QUE TANTAS PESSOAS ESTÃO PROCURANDO UMA RENDA EXTRA?
                </h2>
                <p class="text-neutral-400 max-w-2xl font-light">
                    O modelo tradicional de trabalho está quebrando. O mercado mudou, e quem depende de um só contracheque está vulnerável.
                </p>
            </div>

            <!-- Intersecting Linear Flow (Completely replacing traditional grids) -->
            <div class="relative border-l border-neutral-800 ml-4 md:ml-12 space-y-16">
                
                <!-- Point 1 -->
                <div class="relative pl-8 sm:pl-12 group">
                    <div class="absolute -left-3.5 top-1.5 w-7 h-7 bg-neutral-950 border-2 border-neonGreen rounded-full flex items-center justify-center transition-all group-hover:bg-neonGreen group-hover:shadow-[0_0_15px_rgba(163,255,18,0.8)]">
                        <span class="text-[10px] font-bold text-white group-hover:text-black font-mono">01</span>
                    </div>
                    <div class="grid grid-cols-1 lg:grid-cols-12 gap-4 items-center">
                        <div class="lg:col-span-4">
                            <h4 class="text-xl font-bold text-white group-hover:text-neonGreen transition-colors">Salário que não acompanha o custo de vida</h4>
                        </div>
                        <div class="lg:col-span-8">
                            <p class="text-neutral-400 text-sm leading-relaxed">
                                A inflação real corrói o poder de compra diariamente. No final do mês, as contas sobem mas o holerite permanece estático. Ter uma fonte alternativa não é mais luxo, é sobrevivência básica.
                            </p>
                        </div>
                    </div>
                </div>

                <!-- Point 2 -->
                <div class="relative pl-8 sm:pl-12 group">
                    <div class="absolute -left-3.5 top-1.5 w-7 h-7 bg-neutral-950 border-2 border-neonGreen rounded-full flex items-center justify-center transition-all group-hover:bg-neonGreen group-hover:shadow-[0_0_15px_rgba(163,255,18,0.8)]">
                        <span class="text-[10px] font-bold text-white group-hover:text-black font-mono">02</span>
                    </div>
                    <div class="grid grid-cols-1 lg:grid-cols-12 gap-4 items-center">
                        <div class="lg:col-span-4">
                            <h4 class="text-xl font-bold text-white group-hover:text-neonGreen transition-colors">Dependência de uma única fonte de renda</h4>
                        </div>
                        <div class="lg:col-span-8">
                            <p class="text-neutral-400 text-sm leading-relaxed">
                                Se você tem apenas uma fonte de receita, está a exatamente uma demissão ou imprevisto de distância da escassez. Diversificar seu capital é a lei número 1 das finanças modernas.
                            </p>
                        </div>
                    </div>
                </div>

                <!-- Point 3 -->
                <div class="relative pl-8 sm:pl-12 group">
                    <div class="absolute -left-3.5 top-1.5 w-7 h-7 bg-neutral-950 border-2 border-neonGreen rounded-full flex items-center justify-center transition-all group-hover:bg-neonGreen group-hover:shadow-[0_0_15px_rgba(163,255,18,0.8)]">
                        <span class="text-[10px] font-bold text-white group-hover:text-black font-mono">03</span>
                    </div>
                    <div class="grid grid-cols-1 lg:grid-cols-12 gap-4 items-center">
                        <div class="lg:col-span-4">
                            <h4 class="text-xl font-bold text-white group-hover:text-neonGreen transition-colors">Pouco tempo para aproveitar a vida</h4>
                        </div>
                        <div class="lg:col-span-8">
                            <p class="text-neutral-400 text-sm leading-relaxed">
                                A rotina de trânsito e escritórios drena sua energia. Ao criar um ecossistema digital que roda direto do celular, você recupera horas valiosas do seu dia para focar no que realmente importa.
                            </p>
                        </div>
                    </div>
                </div>

                <!-- Point 4 -->
                <div class="relative pl-8 sm:pl-12 group">
                    <div class="absolute -left-3.5 top-1.5 w-7 h-7 bg-neutral-950 border-2 border-neonGreen rounded-full flex items-center justify-center transition-all group-hover:bg-neonGreen group-hover:shadow-[0_0_15px_rgba(163,255,18,0.8)]">
                        <span class="text-[10px] font-bold text-white group-hover:text-black font-mono">04</span>
                    </div>
                    <div class="grid grid-cols-1 lg:grid-cols-12 gap-4 items-center">
                        <div class="lg:col-span-4">
                            <h4 class="text-xl font-bold text-white group-hover:text-neonGreen transition-colors">Medo constante de perder o emprego</h4>
                        </div>
                        <div class="lg:col-span-8">
                            <p class="text-neutral-400 text-sm leading-relaxed">
                                A instabilidade econômica gera ansiedade generalizada. Ter o controle do seu próprio motor financeiro na internet devolve o sono tranquilo e a autonomia que você merece ter.
                            </p>
                        </div>
                    </div>
                </div>

                <!-- Point 5 -->
                <div class="relative pl-8 sm:pl-12 group">
                    <div class="absolute -left-3.5 top-1.5 w-7 h-7 bg-neutral-950 border-2 border-neonGreen rounded-full flex items-center justify-center transition-all group-hover:bg-neonGreen group-hover:shadow-[0_0_15px_rgba(163,255,18,0.8)]">
                        <span class="text-[10px] font-bold text-white group-hover:text-black font-mono">05</span>
                    </div>
                    <div class="grid grid-cols-1 lg:grid-cols-12 gap-4 items-center">
                        <div class="lg:col-span-4">
                            <h4 class="text-xl font-bold text-white group-hover:text-neonGreen transition-colors">Falta de perspectiva financeira</h4>
                        </div>
                        <div class="lg:col-span-8">
                            <p class="text-neutral-400 text-sm leading-relaxed">
                                Sem um teto escalável de ganhos, poupar migalhas parece inútil. O mercado digital de afiliados e infoprodutos não tem limites geográficos ou tetos salariais impostos por chefes.
                            </p>
                        </div>
                    </div>
                </div>

            </div>

        </div>
    </section>

    <!-- WHAT YOU WILL DISCOVER (PIPELINE ARCHITECTURE STYLE) -->
    <section class="py-24 bg-[#0a0a0a] border-y border-neutral-900 relative px-4 md:px-8">
        <div class="absolute top-0 right-1/4 w-[300px] h-[300px] bg-neonGreen/5 rounded-full filter blur-[100px] pointer-events-none"></div>

        <div class="max-w-7xl mx-auto">
            <div class="text-center space-y-4 mb-20">
                <span class="text-xs font-mono text-neonGreen tracking-widest uppercase">Grade Curricular Integrada</span>
                <h2 class="text-3xl sm:text-4xl lg:text-5xl font-extrabold tracking-tight">
                    DENTRO DO PROJETO LIBERDADE DIGITAL VOCÊ VAI DESCOBRIR:
                </h2>
                <p class="text-neutral-400 max-w-xl mx-auto font-light">
                    O passo a passo estruturado em módulos diretos ao ponto, sem enrolação teórica.
                </p>
            </div>

            <!-- Sleek Horizontal / Vertical pipeline of discoveries (Fintech/Dev style UI) -->
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-8 items-stretch">
                
                <!-- Left Column of Pipeline Elements -->
                <div class="space-y-6">
                    <!-- Discover 1 -->
                    <div class="flex items-start gap-4 p-5 rounded-2xl bg-deepBlack border border-neutral-900 hover:border-neonGreen/30 transition-all">
                        <div class="w-10 h-10 rounded-lg bg-neonGreen/10 border border-neonGreen/30 flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-compass text-neonGreen text-sm"></i>
                        </div>
                        <div>
                            <h4 class="text-base font-bold text-white">Como encontrar oportunidades digitais</h4>
                            <p class="text-xs text-neutral-400 mt-1">Identifique brechas lucrativas e segredos do ecossistema que a maioria ignora solenemente.</p>
                        </div>
                    </div>

                    <!-- Discover 2 -->
                    <div class="flex items-start gap-4 p-5 rounded-2xl bg-deepBlack border border-neutral-900 hover:border-neonGreen/30 transition-all">
                        <div class="w-10 h-10 rounded-lg bg-neonGreen/10 border border-neonGreen/30 flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-layer-group text-neonGreen text-sm"></i>
                        </div>
                        <div>
                            <h4 class="text-base font-bold text-white">Como escolher produtos com potencial</h4>
                            <p class="text-xs text-neutral-400 mt-1">Aprenda a mapear produtos campeões de vendas em qualquer nicho com alto índice de comissionamento.</p>
                        </div>
                    </div>

                    <!-- Discover 3 -->
                    <div class="flex items-start gap-4 p-5 rounded-2xl bg-deepBlack border border-neutral-900 hover:border-neonGreen/30 transition-all">
                        <div class="w-10 h-10 rounded-lg bg-neonGreen/10 border border-neonGreen/30 flex items-center justify-center shrink-0">
                            <i class="fa-brands fa-instagram text-neonGreen text-sm"></i>
                        </div>
                        <div>
                            <h4 class="text-base font-bold text-white">Como divulgar usando Instagram</h4>
                            <p class="text-xs text-neutral-400 mt-1">Transforme seu perfil (ou um perfil do zero) em um gerador passivo de tráfego e autoridade imediata.</p>
                        </div>
                    </div>

                    <!-- Discover 4 -->
                    <div class="flex items-start gap-4 p-5 rounded-2xl bg-deepBlack border border-neutral-900 hover:border-neonGreen/30 transition-all">
                        <div class="w-10 h-10 rounded-lg bg-neonGreen/10 border border-neonGreen/30 flex items-center justify-center shrink-0">
                            <i class="fa-brands fa-tiktok text-neonGreen text-sm"></i>
                        </div>
                        <div>
                            <h4 class="text-base font-bold text-white">Como utilizar o TikTok para alcance</h4>
                            <p class="text-xs text-neutral-400 mt-1">Algoritmo hackeado: as dinâmicas de engajamento do TikTok para alcançar milhares de pessoas organicamente.</p>
                        </div>
                    </div>
                </div>

                <!-- Right Column of Pipeline Elements -->
                <div class="space-y-6 flex flex-col justify-between">
                    <!-- Discover 5 -->
                    <div class="flex items-start gap-4 p-5 rounded-2xl bg-deepBlack border border-neutral-900 hover:border-neonGreen/30 transition-all">
                        <div class="w-10 h-10 rounded-lg bg-neonGreen/10 border border-neonGreen/30 flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-arrow-trend-up text-neonGreen text-sm"></i>
                        </div>
                        <div>
                            <h4 class="text-base font-bold text-white">Como transformar visualizações em vendas</h4>
                            <p class="text-xs text-neutral-400 mt-1">Crie funis invisíveis e roteiros magnéticos de copy que transformam meros cliques em dinheiro no bolso.</p>
                        </div>
                    </div>

                    <!-- Discover 6 -->
                    <div class="flex items-start gap-4 p-5 rounded-2xl bg-deepBlack border border-neutral-900 hover:border-neonGreen/30 transition-all">
                        <div class="w-10 h-10 rounded-lg bg-neonGreen/10 border border-neonGreen/30 flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-network-wired text-neonGreen text-sm"></i>
                        </div>
                        <div>
                            <h4 class="text-base font-bold text-white">Como criar um sistema simples de aquisição</h4>
                            <p class="text-xs text-neutral-400 mt-1">Instale um ecossistema de aquisição automatizado que funciona enquanto você dorme ou se diverte.</p>
                        </div>
                    </div>

                    <!-- Discover 7 -->
                    <div class="flex items-start gap-4 p-5 rounded-2xl bg-deepBlack border border-neutral-900 hover:border-neonGreen/30 transition-all">
                        <div class="w-10 h-10 rounded-lg bg-neonGreen/10 border border-neonGreen/30 flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-mobile-screen-button text-neonGreen text-sm"></i>
                        </div>
                        <div>
                            <h4 class="text-base font-bold text-white">Como organizar sua operação usando apenas o celular</h4>
                            <p class="text-xs text-neutral-400 mt-1">Sem PCs caros ou licenças absurdas. Gerencie faturamento, postagens e contatos do seu bolso.</p>
                        </div>
                    </div>

                    <!-- Call to action anchor linking naturally below discoveries -->
                    <div class="p-5 rounded-2xl bg-gradient-to-r from-neonGreen/10 to-transparent border border-neonGreen/20 flex flex-col sm:flex-row items-center justify-between gap-4">
                        <p class="text-xs font-mono text-neutral-300">Tudo unificado em uma plataforma clean e dinâmica.</p>
                        <a href="https://pay.cakto.com.br/3ftpayw_915159" class="text-xs font-bold text-neonGreen hover:underline flex items-center gap-1.5 uppercase">
                            Quero me inscrever <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- SOCIAL PROOF (NOTIFICATIONS / FEEDBACK STACK STYLE) -->
    <section class="py-24 relative px-4 md:px-8">
        <div class="max-w-6xl mx-auto">
            
            <div class="text-center space-y-4 mb-16">
                <span class="text-xs font-mono text-neonGreen tracking-wider uppercase">Registros no App</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-white">AVALIAÇÃO EM TEMPO REAL DOS ALUNOS</h2>
                <p class="text-neutral-400 max-w-lg mx-auto font-light">
                    Retorno autêntico e direto de pessoas comuns que aplicaram e destravam ganhos.
                </p>
            </div>

            <!-- Interlocking horizontal waterfall layout - Fintech/Slack style feeds -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                
                <!-- Review 1 -->
                <div class="p-6 bg-neutral-950 border border-neutral-900 rounded-2xl hover:border-neutral-800 transition-all flex flex-col justify-between space-y-6">
                    <div class="space-y-3">
                        <div class="flex items-center gap-1 text-neonGreen text-xs">
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                        </div>
                        <p class="text-sm text-neutral-300 font-medium">"Conteúdo direto ao ponto."</p>
                        <p class="text-xs text-neutral-400 leading-relaxed">Sem teoria barata. Ele realmente te pega pela mão e ensina como faturar direto com o celular.</p>
                    </div>
                    <div class="flex items-center gap-3 pt-4 border-t border-neutral-900">
                        <div class="w-8 h-8 rounded-full bg-neutral-900 border border-neutral-800 flex items-center justify-center font-bold text-xs text-neonGreen">AL</div>
                        <div>
                            <p class="text-xs font-bold text-white">Arthur L.</p>
                            <span class="text-[9px] font-mono text-neutral-500">Membro verificado</span>
                        </div>
                    </div>
                </div>

                <!-- Review 2 -->
                <div class="p-6 bg-neutral-950 border border-neutral-900 rounded-2xl hover:border-neutral-800 transition-all flex flex-col justify-between space-y-6">
                    <div class="space-y-3">
                        <div class="flex items-center gap-1 text-neonGreen text-xs">
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                        </div>
                        <p class="text-sm text-neutral-300 font-medium">"Finalmente entendi como funciona esse mercado."</p>
                        <p class="text-xs text-neutral-400 leading-relaxed">Já tinha feito outros cursos mas nenhum foi tão prático na dinâmica do Instagram e TikTok.</p>
                    </div>
                    <div class="flex items-center gap-3 pt-4 border-t border-neutral-900">
                        <div class="w-8 h-8 rounded-full bg-neutral-900 border border-neutral-800 flex items-center justify-center font-bold text-xs text-neonGreen">MD</div>
                        <div>
                            <p class="text-xs font-bold text-white">Mateus D.</p>
                            <span class="text-[9px] font-mono text-neutral-500">Membro verificado</span>
                        </div>
                    </div>
                </div>

                <!-- Review 3 -->
                <div class="p-6 bg-neutral-950 border border-neutral-900 rounded-2xl hover:border-neutral-800 transition-all flex flex-col justify-between space-y-6">
                    <div class="space-y-3">
                        <div class="flex items-center gap-1 text-neonGreen text-xs">
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                        </div>
                        <p class="text-sm text-neutral-300 font-medium">"Vale muito mais do que paguei."</p>
                        <p class="text-xs text-neutral-400 leading-relaxed">Por apenas 67 reais eu não achei que o suporte e o conteúdo seriam tão premium. Recomendo muito.</p>
                    </div>
                    <div class="flex items-center gap-3 pt-4 border-t border-neutral-900">
                        <div class="w-8 h-8 rounded-full bg-neutral-900 border border-neutral-800 flex items-center justify-center font-bold text-xs text-neonGreen">SM</div>
                        <div>
                            <p class="text-xs font-bold text-white">Sarah M.</p>
                            <span class="text-[9px] font-mono text-neutral-500">Membro verificado</span>
                        </div>
                    </div>
                </div>

                <!-- Review 4 -->
                <div class="p-6 bg-neutral-950 border border-neutral-900 rounded-2xl hover:border-neutral-800 transition-all flex flex-col justify-between space-y-6 md:col-span-1 lg:col-span-1">
                    <div class="space-y-3">
                        <div class="flex items-center gap-1 text-neonGreen text-xs">
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                        </div>
                        <p class="text-sm text-neutral-300 font-medium">"Explicação simples e prática."</p>
                        <p class="text-xs text-neutral-400 leading-relaxed">Para quem é totalmente iniciante e tem vergonha de aparecer, é a fórmula ideal.</p>
                    </div>
                    <div class="flex items-center gap-3 pt-4 border-t border-neutral-900">
                        <div class="w-8 h-8 rounded-full bg-neutral-900 border border-neutral-800 flex items-center justify-center font-bold text-xs text-neonGreen">TP</div>
                        <div>
                            <p class="text-xs font-bold text-white">Thiago P.</p>
                            <span class="text-[9px] font-mono text-neutral-500">Membro verificado</span>
                        </div>
                    </div>
                </div>

                <!-- Review 5 -->
                <div class="p-6 bg-neutral-950 border border-neutral-900 rounded-2xl hover:border-neutral-800 transition-all flex flex-col justify-between space-y-6 md:col-span-1 lg:col-span-2">
                    <div class="space-y-3">
                        <div class="flex items-center gap-1 text-neonGreen text-xs">
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                        </div>
                        <p class="text-sm text-neutral-300 font-medium">"Consegui colocar tudo em prática rapidamente."</p>
                        <p class="text-xs text-neutral-400 leading-relaxed">Tive resultados logo nas primeiras duas semanas de divulgação. A didática do professor é fantástica e vai direto ao ponto, economizando tempo e energia.</p>
                    </div>
                    <div class="flex items-center gap-3 pt-4 border-t border-neutral-900">
                        <div class="w-8 h-8 rounded-full bg-neutral-900 border border-neutral-800 flex items-center justify-center font-bold text-xs text-neonGreen">FB</div>
                        <div>
                            <p class="text-xs font-bold text-white">Felipe B.</p>
                            <span class="text-[9px] font-mono text-neutral-500">Membro verificado</span>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- PRESET OFERTA (PREMIUM CENTRAL BLOCK) -->
    <section class="py-24 relative px-4 md:px-8">
        <!-- Accent circles for offer spotlight focus -->
        <div class="absolute inset-x-0 top-1/2 -translate-y-1/2 w-full max-w-4xl mx-auto h-[350px] bg-neonGreen/10 rounded-full filter blur-[100px] pointer-events-none"></div>

        <div class="max-w-4xl mx-auto relative z-10">
            <!-- Modern outer container structure (Unified Fintech Box with subtle glowing edges) -->
            <div class="relative bg-deepBlack border-2 border-neonGreen/40 rounded-3xl overflow-hidden p-8 sm:p-12 shadow-[0_0_50px_rgba(163,255,18,0.15)] flex flex-col justify-center items-center text-center space-y-8">
                
                <!-- Micro Tag -->
                <span class="px-4 py-1.5 rounded-full bg-neonGreen/10 border border-neonGreen/30 text-[10px] font-mono tracking-wider text-neonGreen uppercase">
                    OFERTA ATIVA POR MENOS DE R$ 2,30 POR DIA
                </span>

                <!-- Main Offer Identity -->
                <div class="space-y-2">
                    <h3 class="text-3xl sm:text-5xl font-black text-white tracking-tight uppercase">PROJETO LIBERDADE DIGITAL</h3>
                    <p class="text-sm text-neutral-400 font-mono tracking-wide">Acesso Imediato ao Ecossistema de Geração de Renda</p>
                </div>

                <!-- High-tech linear inclusion breakdown checklist (instead of traditional layout cards) -->
                <div class="w-full max-w-lg grid grid-cols-1 sm:grid-cols-2 gap-3 text-left pt-6 border-y border-neutral-900 py-6">
                    <div class="flex items-center gap-2.5 text-xs text-neutral-300">
                        <i class="fa-solid fa-check text-neonGreen"></i>
                        <span>Acesso completo ao método</span>
                    </div>
                    <div class="flex items-center gap-2.5 text-xs text-neutral-300">
                        <i class="fa-solid fa-check text-neonGreen"></i>
                        <span>Método 100% atualizado</span>
                    </div>
                    <div class="flex items-center gap-2.5 text-xs text-neutral-300">
                        <i class="fa-solid fa-check text-neonGreen"></i>
                        <span>Suporte VIP da comunidade</span>
                    </div>
                    <div class="flex items-center gap-2.5 text-xs text-neutral-300">
                        <i class="fa-solid fa-check text-neonGreen"></i>
                        <span>Garantia oficial de 7 dias</span>
                    </div>
                </div>

                <!-- Pricing Dynamics -->
                <div class="flex flex-col items-center justify-center space-y-1">
                    <span class="text-sm font-mono text-neutral-500 line-through">De R$ 197</span>
                    <div class="flex items-baseline gap-2">
                        <span class="text-xs text-neutral-400 font-mono">Por apenas</span>
                        <span class="text-5xl sm:text-6xl font-black text-neonGreen tracking-tighter">R$ 67,90</span>
                    </div>
                    <span class="text-[10px] font-mono text-neutral-500 mt-1 uppercase">OU ATÉ 12X DE R$ 6,82 NO CARTÃO</span>
                </div>

                <!-- Button -->
                <div class="w-full max-w-md">
                    <a href="https://pay.cakto.com.br/3ftpayw_915159" 
                       class="group relative w-full inline-flex items-center justify-center px-8 py-5 text-base font-bold text-black bg-neonGreen rounded-lg overflow-hidden transition-all duration-300 hover:shadow-[0_0_35px_rgba(163,255,18,0.5)] active:scale-[0.98]">
                        <span class="absolute inset-0 w-full h-full bg-white/20 transform -skew-x-12 -translate-x-full group-hover:translate-x-full transition-transform duration-1000 ease-out"></span>
                        SIM, QUERO ENTRAR AGORA
                        <i class="fa-solid fa-wallet ml-3 text-sm"></i>
                    </a>
                </div>

                <!-- Payment Protections list -->
                <div class="flex flex-wrap items-center justify-center gap-6 text-neutral-500 text-[10px] pt-2">
                    <span class="flex items-center gap-1.5"><i class="fa-solid fa-lock text-neonGreen"></i> Ambiente 100% Criptografado</span>
                    <span class="flex items-center gap-1.5"><i class="fa-solid fa-bolt text-neonGreen"></i> Liberação Imediata</span>
                    <span class="flex items-center gap-1.5"><i class="fa-solid fa-shield-halved text-neonGreen"></i> Compra Segura</span>
                </div>

            </div>
        </div>
    </section>

    <!-- GUARANTEE BLOCK (SLIDE STYLE DETAILS) -->
    <section class="py-16 bg-[#080808] border-t border-neutral-900 relative px-4">
        <div class="max-w-4xl mx-auto flex flex-col md:flex-row items-center gap-8 md:gap-12">
            
            <!-- Guarantee Badge with dynamic pure CSS elements -->
            <div class="relative shrink-0 w-32 h-32 flex items-center justify-center rounded-full bg-neutral-950 border-2 border-neonGreen shadow-[0_0_20px_rgba(163,255,18,0.15)]">
                <div class="absolute inset-1.5 border border-dashed border-neutral-800 rounded-full"></div>
                <div class="text-center">
                    <span class="text-3xl font-black text-white block">7</span>
                    <span class="text-[10px] font-mono text-neonGreen uppercase tracking-wider block">Dias</span>
                </div>
            </div>

            <!-- Guarantee Copywriting -->
            <div class="flex-1 space-y-4 text-center md:text-left">
                <span class="text-[10px] font-mono text-neonGreen tracking-widest uppercase">RISCO ZERO GARANTIDO</span>
                <h4 class="text-xl sm:text-2xl font-extrabold text-white">Você terá 7 dias para avaliar o conteúdo</h4>
                <p class="text-sm text-neutral-400 leading-relaxed font-light">
                    Se por qualquer razão você sentir que o Projeto Liberdade Digital não é para você ou não preenche as suas expectativas, poderá solicitar reembolso integral dentro do prazo previsto, sem burocracia ou constrangimento. Nós assumimos todo o risco da sua decisão.
                </p>
            </div>

        </div>
    </section>

    <!-- FINAL CTA HEROIC SECTION -->
    <section class="py-28 relative px-4 md:px-8 text-center bg-deepBlack overflow-hidden">
        <!-- background dynamic glow -->
        <div class="absolute bottom-0 left-1/2 -translate-x-1/2 w-full max-w-5xl h-[200px] bg-neonGreen/5 rounded-full filter blur-[100px] pointer-events-none"></div>

        <div class="max-w-4xl mx-auto space-y-8 relative z-10">
            <span class="text-xs font-mono text-neonGreen tracking-wider uppercase bg-neonGreen/5 px-3 py-1.5 rounded-full border border-neonGreen/20">A Decisão É Sua</span>
            
            <h2 class="text-3xl sm:text-5xl lg:text-6xl font-black tracking-tight leading-none text-white uppercase">
                O melhor momento para começar foi ontem. <br class="hidden sm:inline" />
                <span class="text-neonGreen underline decoration-2 underline-offset-8 neon-text-glow">O segundo melhor momento é agora.</span>
            </h2>

            <p class="text-sm sm:text-base text-neutral-400 max-w-lg mx-auto font-light leading-relaxed">
                Pare de assistir ao sucesso alheio enquanto suas contas continuam chegando. Mude sua história financeira usando a tecnologia a seu favor hoje mesmo.
            </p>

            <div class="pt-6">
                <a href="https://pay.cakto.com.br/3ftpayw_915159" 
                   class="group relative inline-flex items-center justify-center px-8 py-5 text-base font-bold text-black bg-neonGreen rounded-lg overflow-hidden transition-all duration-300 hover:shadow-[0_0_35px_rgba(163,255,18,0.5)] active:scale-[0.98] w-full sm:w-auto">
                    <span class="absolute inset-0 w-full h-full bg-white/20 transform -skew-x-12 -translate-x-full group-hover:translate-x-full transition-transform duration-1000 ease-out"></span>
                    ENTRAR NO PROJETO LIBERDADE DIGITAL
                    <i class="fa-solid fa-arrow-right ml-3 transition-transform group-hover:translate-x-1"></i>
                </a>
            </div>

            <!-- final mini badges -->
            <div class="flex items-center justify-center gap-6 pt-8 text-[10px] text-neutral-500 font-mono">
                <span>R$ 67,90 À VISTA</span>
                <span>•</span>
                <span>ACESSO VITALÍCIO</span>
                <span>•</span>
                <span>SUPORTE DIRETO</span>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="py-12 border-t border-neutral-900 bg-deepBlack text-center text-neutral-600 px-4">
        <div class="max-w-4xl mx-auto space-y-4">
            <p class="text-xs font-mono tracking-widest text-neutral-500 uppercase">PROJETO LIBERDADE DIGITAL © 2026</p>
            <p class="text-[10px] leading-relaxed max-w-2xl mx-auto text-neutral-600">
                Os resultados apresentados no site são estimativas e experiências individuais de alunos, não garantindo que todos alcançarão o mesmo faturamento. A persistência, dedicação e execução prática são fundamentais para o sucesso.
            </p>
            <p class="text-[10px] text-neutral-700 font-mono">
                Desenvolvido com tecnologia e segurança por Cakto Payments.
            </p>
        </div>
    </footer>

    <!-- INTERACTIVE JAVASCRIPT FOR PHONE NOTIFICATIONS AND SIMULATOR -->
    <script>
        // Commission dynamic notifications array
        const names = ["Gabriel S.", "Rafaela M.", "Daniel O.", "Jessica K.", "Marcos F.", "Larissa T.", "Lucas B.", "Patricia C."];
        const amounts = ["R$ 67,90", "R$ 67,90", "R$ 135,80", "R$ 67,90", "R$ 67,90", "R$ 203,70"];
        
        const notifyBox = document.getElementById("phone-notification");
        
        // Dynamic push update animation
        function simulateNotification() {
            if (!notifyBox) return;

            // Fade out
            notifyBox.classList.remove("translate-y-0", "opacity-100", "scale-100");
            notifyBox.classList.add("translate-y-4", "opacity-0", "scale-95");

            setTimeout(() => {
                const randomName = names[Math.floor(Math.random() * names.length)];
                const randomAmount = amounts[Math.floor(Math.random() * amounts.length)];
                const currentHour = new Date().toLocaleTimeString('pt-BR', { hour: '2-digit', minute: '2-digit' });

                // Calculate commissions
                const numericAmount = parseFloat(randomAmount.replace("R$ ", "").replace(",", "."));
                const commission = (numericAmount * 0.8).toFixed(2).replace(".", ",");

                // Update contents
                notifyBox.querySelector("p.text-white").innerText = `Venda de R$ ${numericAmount.toFixed(2).replace(".", ",")} realizada!`;
                notifyBox.querySelector("p.text-neutral-400").innerText = `Comissão de R$ ${commission} aprovada para você.`;
                notifyBox.querySelector("span.text-neutral-300").innerText = `CAKTO PAYMENTS`;
                
                // Fade in
                notifyBox.classList.remove("translate-y-4", "opacity-0", "scale-95");
                notifyBox.classList.add("translate-y-0", "opacity-100", "scale-100");

            }, 500);
        }

        // Run notifications every 5 seconds
        setInterval(simulateNotification, 5000);

        // Earnings Simulator System Logic
        let currentSalesCount = 1;
        const commissionPerSale = 54.32; // Calculated on R$ 67,90 with typical 80% split

        function updateSim(direction) {
            currentSalesCount += direction;
            if (currentSalesCount < 1) currentSalesCount = 1;
            if (currentSalesCount > 25) currentSalesCount = 25; // Limit standard range

            const salesCounter = document.getElementById("sim-sales-count");
            const dailyFaturamento = document.getElementById("sim-daily");
            const monthlyProjecao = document.getElementById("sim-monthly");
            const yearlyProjecao = document.getElementById("sim-yearly");

            if (salesCounter && dailyFaturamento && monthlyProjecao && yearlyProjecao) {
                salesCounter.innerText = currentSalesCount;

                // Daily logic
                const dailyTotal = currentSalesCount * 67.90;
                dailyFaturamento.innerText = `R$ ${dailyTotal.toLocaleString('pt-BR', { minimumFractionDigits: 2, maximumFractionDigits: 2 })}`;

                // Monthly net profit logic (commission scale)
                const monthlyTotal = currentSalesCount * commissionPerSale * 30;
                monthlyProjecao.innerText = `R$ ${monthlyTotal.toLocaleString('pt-BR', { minimumFractionDigits: 2, maximumFractionDigits: 2 })}`;

                // Yearly net profit logic
                const yearlyTotal = monthlyTotal * 12;
                yearlyProjecao.innerText = `R$ ${yearlyTotal.toLocaleString('pt-BR', { minimumFractionDigits: 2, maximumFractionDigits: 2 })}`;
            }
        }
    </script>
</body>
</html>
