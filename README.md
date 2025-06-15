<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CryptoEarnHub - Зарабатывай с криптовалютой</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-900 text-white font-sans">
  <header class="bg-gray-800 shadow p-4 flex justify-between items-center">
    <h1 class="text-2xl font-bold">CryptoEarnHub</h1>
    <nav class="space-x-4">
      <a href="#earn" class="hover:underline">Заработать</a>
      <a href="#swap" class="hover:underline">Обмен</a>
      <a href="#donate" class="hover:underline">Донаты</a>
      <a href="#login" class="hover:underline">Вход</a>
    </nav>
  </header>

  <section class="text-center py-20 px-4 bg-gradient-to-b from-gray-900 to-black">
    <h2 class="text-4xl font-bold mb-4">Платформа для заработка криптовалюты</h2>
    <p class="text-lg text-gray-300 mb-8">Выполняй задания, получай крипту, обменивай, выводи. Всё в одном месте.</p>
    <a href="#earn" class="bg-yellow-500 text-black font-semibold py-2 px-6 rounded hover:bg-yellow-400 transition">Начать зарабатывать</a>
  </section>

  <section id="earn" class="py-16 px-6">
    <h3 class="text-3xl font-bold mb-6 text-center">💼 Заработок на заданиях</h3>
    <div class="grid md:grid-cols-3 gap-6">
      <div class="bg-gray-800 p-6 rounded-xl shadow">
        <h4 class="text-xl font-semibold mb-2">📺 Смотри видео</h4>
        <p class="text-gray-400">Просматривай рекламные ролики и получай криптовалюту.</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl shadow">
        <h4 class="text-xl font-semibold mb-2">📱 Устанавливай приложения</h4>
        <p class="text-gray-400">Скачивай партнёрские приложения и получай бонусы.</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl shadow">
        <h4 class="text-xl font-semibold mb-2">📢 Подписки и лайки</h4>
        <p class="text-gray-400">Подписывайся на соцсети и зарабатывай.</p>
      </div>
    </div>
  </section>

  <section id="swap" class="py-16 px-6 bg-gray-800">
    <h3 class="text-3xl font-bold mb-6 text-center">🔁 Обмен криптовалюты</h3>
    <p class="text-center text-gray-300">Быстрый обмен токенов: USDT, MyCallyve, BNB, BTC.</p>
    <!-- Здесь будет API подключения к обменнику -->
  </section>

  <section id="donate" class="py-16 px-6">
    <h3 class="text-3xl font-bold mb-6 text-center">🎁 Донаты и поддержка</h3>
    <p class="text-center text-gray-300 mb-6">Создай страницу и получай донаты в криптовалюте. Поддержка медиа, анимации и стрим-виджетов.</p>
    <div class="text-center">
      <a href="#" class="bg-green-500 text-white py-2 px-6 rounded hover:bg-green-400">Создать страницу донатов</a>
    </div>
  </section>

  <section id="login" class="py-16 px-6 bg-gray-800">
    <h3 class="text-3xl font-bold mb-6 text-center">🔐 Вход или регистрация</h3>
    <form action="/login" method="POST" class="max-w-md mx-auto bg-gray-900 p-6 rounded-xl shadow space-y-4">
      <div>
        <label class="block mb-1">Email</label>
        <input type="email" name="email" required class="w-full px-4 py-2 rounded bg-gray-800 text-white border border-gray-700 focus:outline-none">
      </div>
      <div>
        <label class="block mb-1">Пароль</label>
        <input type="password" name="password" required class="w-full px-4 py-2 rounded bg-gray-800 text-white border border-gray-700 focus:outline-none">
      </div>
      <div class="flex justify-between items-center">
        <button type="submit" class="bg-yellow-500 text-black font-semibold py-2 px-6 rounded hover:bg-yellow-400">Войти</button>
        <a href="/register" class="text-sm text-yellow-400 hover:underline">Нет аккаунта?</a>
      </div>
    </form>
  </section>

  <footer class="bg-gray-800 text-center p-4 mt-10 text-gray-400">
    © 2025 CryptoEarnHub. Все права защищены.
  </footer>
</body>
</html>

