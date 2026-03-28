<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ürün Satış Sayfası</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100">

  <!-- Header -->
  <header class="bg-white shadow p-4 flex justify-between items-center">
    <h1 class="text-2xl font-bold">Mağaza Adı</h1>
    <button class="bg-black text-white px-4 py-2 rounded">Sepet</button>
  </header>

  <!-- Product Section -->
  <section class="max-w-6xl mx-auto p-6 grid md:grid-cols-2 gap-8">
    <img src="https://via.placeholder.com/500" alt="Ürün" class="rounded-2xl shadow">
    <div>
      <h2 class="text-3xl font-bold mb-4">Ürün Adı</h2>
      <p class="text-gray-600 mb-4">Kısa ürün açıklaması buraya gelecek. Ürünün faydalarını anlat.</p>
      <p class="text-2xl font-semibold mb-6">₺999</p>
      <button class="bg-black text-white px-6 py-3 rounded-xl">Satın Al</button>
    </div>
  </section>

  <!-- Features -->
  <section class="bg-white py-10">
    <div class="max-w-5xl mx-auto grid md:grid-cols-3 gap-6 text-center">
      <div>
        <h3 class="font-bold text-lg">Hızlı Teslimat</h3>
        <p class="text-gray-500">Aynı gün kargo fırsatı</p>
      </div>
      <div>
        <h3 class="font-bold text-lg">Güvenli Ödeme</h3>
        <p class="text-gray-500">256-bit SSL koruma</p>
      </div>
      <div>
        <h3 class="font-bold text-lg">Kolay İade</h3>
        <p class="text-gray-500">14 gün iade garantisi</p>
      </div>
    </div>
  </section>

  <!-- Reviews -->
  <section class="max-w-5xl mx-auto p-6">
    <h2 class="text-2xl font-bold mb-6">Müşteri Yorumları</h2>
    <div class="space-y-4">
      <div class="bg-white p-4 rounded-xl shadow">
        <p>"Harika ürün, çok memnun kaldım!"</p>
        <span class="text-sm text-gray-500">- Ahmet</span>
      </div>
      <div class="bg-white p-4 rounded-xl shadow">
        <p>"Kalitesi beklediğimden iyi."</p>
        <span class="text-sm text-gray-500">- Ayşe</span>
      </div>
    </div>
  </section>

  <!-- CTA -->
  <section class="bg-black text-white text-center py-10">
    <h2 class="text-2xl font-bold mb-4">Fırsatı Kaçırma!</h2>
    <button class="bg-white text-black px-6 py-3 rounded-xl">Şimdi Satın Al</button>
  </section>

  <!-- Footer -->
  <footer class="text-center p-4 text-gray-500">
    © 2026 Tüm hakları saklıdır.
  </footer>

</body>
</html>
