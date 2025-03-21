<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Catherine's Module Lab</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 text-gray-800">

  <!-- 顶部导航栏 -->
  <nav class="bg-white shadow p-4 flex justify-between items-center">
    <h1 class="text-2xl font-bold">Catherine's Module Lab</h1>
    <div class="space-x-4">
      <a href="#about" class="hover:text-blue-600">关于我们</a>
      <a href="#modules" class="hover:text-blue-600">模块展示</a>
      <a href="#video" class="hover:text-blue-600">演示视频</a>
      <a href="#contact" class="hover:text-blue-600">联系</a>
    </div>
  </nav>

  <!-- 欢迎页 -->
  <section class="bg-gradient-to-r from-blue-200 to-purple-200 text-center py-20">
    <h2 class="text-4xl font-bold mb-4">欢迎来到模块创意世界</h2>
    <p class="text-lg">探索、创造、连接 —— 让模块成为你的创客起点</p>
  </section>

  <!-- 关于我们 -->
  <section id="about" class="max-w-4xl mx-auto py-16 px-4">
    <h3 class="text-3xl font-semibold mb-4">我们是谁？</h3>
    <p class="text-lg leading-relaxed">
      Catherine's Module Lab 是一个专注于模块化编程、机械拼装与STEM教育的青少年创新项目。我们通过创意模块、视频教学和3D可视化，帮助更多人进入创客的世界。
    </p>
  </section>

  <!-- 模块展示 -->
  <section id="modules" class="bg-white py-16 px-4">
    <div class="max-w-6xl mx-auto">
      <h3 class="text-3xl font-semibold mb-8 text-center">模块展示</h3>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <div class="bg-gray-50 p-4 rounded shadow text-center">
          <img src="https://via.placeholder.com/300x200" alt="模块1" class="mx-auto mb-4" />
          <p>控制板模块</p>
        </div>
        <div class="bg-gray-50 p-4 rounded shadow text-center">
          <img src="https://via.placeholder.com/300x200" alt="模块2" class="mx-auto mb-4" />
          <p>连接结构件</p>
        </div>
        <div class="bg-gray-50 p-4 rounded shadow text-center">
          <img src="https://via.placeholder.com/300x200" alt="模块3" class="mx-auto mb-4" />
          <p>轮子+支架组合</p>
        </div>
      </div>
    </div>
  </section>

  <!-- 视频演示 -->
  <section id="video" class="py-16 px-4 bg-gray-100">
    <div class="max-w-4xl mx-auto text-center">
      <h3 class="text-3xl font-semibold mb-6">模块功能演示</h3>
      <div class="aspect-w-16 aspect-h-9">
        <iframe class="w-full h-64 rounded shadow" src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allowfullscreen></iframe>
      </div>
    </div>
  </section>

  <!-- 联系我们 -->
  <section id="contact" class="bg-white py-16 px-4">
    <div class="max-w-2xl mx-auto text-center">
      <h3 class="text-3xl font-semibold mb-4">联系我</h3>
      <p>📧 邮箱：catherine.module.lab@example.com</p>
      <p>📍 微信 / 小红书：@Catherine模块工坊</p>
    </div>
  </section>

  <!-- 底部 -->
  <footer class="bg-gray-200 text-center py-6">
    <p>&copy; 2025 Catherine's Module Lab. All rights reserved.</p>
  </footer>

</body>
</html>
# module-website
