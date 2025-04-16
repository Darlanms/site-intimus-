<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>Raiz Íntimus</title>
    <script src="https://cdn.tailwindcss.com"></script>
  </head>
  <body class="bg-neutral-950 text-white font-sans flex flex-col items-center justify-center min-h-screen px-4">

    <!-- Logo -->
    <img src="A_logo_design_for_the_luxury_underwear_brand_&quot;Raiz.png" alt="Logo Raiz Íntimus" class="w-48 mb-6 animate-fade-in"/>

    <!-- Slogan -->
    <h1 class="text-4xl font-bold tracking-wide text-center animate-fade-in">Essência. Conforto. Poder.</h1>

    <!-- Texto institucional -->
    <p class="mt-4 text-lg max-w-xl text-center text-neutral-300 animate-slide-up">
      A Raiz Íntimus nasce da elegância que habita o essencial. Cuecas e meias premium, pensadas para o homem que valoriza a origem, respeita a tradição e não abre mão do conforto e estilo.
    </p>

    <!-- Destaques -->
    <div class="mt-8 grid grid-cols-1 sm:grid-cols-3 gap-6 max-w-4xl text-center animate-slide-up">
      <div>
        <h2 class="text-xl font-semibold mb-2">🧵 Qualidade Artesanal</h2>
        <p class="text-neutral-400">Tecidos nobres, acabamentos feitos com excelência.</p>
      </div>
      <div>
        <h2 class="text-xl font-semibold mb-2">🕰️ Estilo Atemporal</h2>
        <p class="text-neutral-400">Designs retrô com atitude contemporânea.</p>
      </div>
      <div>
        <h2 class="text-xl font-semibold mb-2">🇧🇷 Identidade Nacional</h2>
        <p class="text-neutral-400">Raízes brasileiras em cada costura e detalhe.</p>
      </div>
    </div>

    <!-- Botão do Catálogo -->
    <a href="https://wa.me/55049988076934?text=Quero%20ver%20o%20cat%C3%A1logo%20da%20Raiz%20%C3%8Dntimus" 
       target="_blank"
       class="mt-10 inline-block bg-white text-black px-6 py-3 rounded-xl text-lg font-bold hover:bg-neutral-200 transition animate-slide-up">
      📲 Ver Catálogo Digital
    </a>

    <!-- Animações -->
    <style>
      @keyframes fade-in {
        from { opacity: 0 }
        to { opacity: 1 }
      }
      @keyframes slide-up {
        from { transform: translateY(40px); opacity: 0 }
        to { transform: translateY(0); opacity: 1 }
      }
      .animate-fade-in {
        animation: fade-in 1.2s ease-out;
      }
      .animate-slide-up {
        animation: slide-up 1s ease-out;
      }
    </style>

  </body>
</html>
