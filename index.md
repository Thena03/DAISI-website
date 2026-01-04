---
layout: base
title: Home
permalink: /
---
<!-- Title -->
<div class="md:w-1/2 mx-auto mb-12">
  <h1 class="text-4xl md:text-5xl font-bold text-green-400 text-center mb-4">
    DAISI Resources
  </h1>
  <h2 class="text-sm md:text-base font-medium text-center text-slate-400">
    Resources created for DAISI students by Athena Amancio-Alsobrook
  </h2>
</div>

<!-- Resource Cards -->
<div class="grid grid-cols-1 md:grid-cols-2 gap-8">

  <!-- LearnR -->
  <div class="bg-slate-900 p-6 rounded-xl border border-slate-800 hover:border-green-400 transition">
    <img
      src="{{ '/static/LearnR.gif' | relative_url }}"
      class="rounded-lg mb-4 border border-slate-800"
      alt="LearnR Coding"
    >

   <h4 class="text-xl font-semibold text-slate-100 mb-2">
      LearnR Coding
    </h4>

  <p class="text-slate-400 mb-4 text-sm leading-relaxed">
      An educational platform designed to make R programming practical, intuitive,
      and accessible for learners at all levels.
    </p>

  <a
      href="https://learnrcoding.com"
      target="_blank"
      class="inline-block mt-auto px-5 py-2 rounded-lg text-sm font-medium
             border border-green-400 text-green-400
             hover:bg-green-400 hover:text-slate-900 transition"
    >
      Visit Website
    </a>
  </div>

  <!-- Excelerate -->
  <div class="bg-slate-900 p-6 rounded-xl border border-slate-800 hover:border-green-400 transition">
    <img
      src="{{ '/static/exceled.png' | relative_url }}"
      alt="Excelerate preview"
      class="rounded-lg mb-4 border border-slate-800 w-full object-cover"
    >

   <h3 class="text-xl font-semibold text-slate-100 mb-2">
      Excelerate
    </h3>

  <p class="text-slate-400 mb-4 text-sm leading-relaxed">
      Designed to be a resource for individuals looking to improve their data skills using Excel.
    </p>

   <a
      href="https://thena03.github.io/ExcelEd/"
      class="inline-block text-sm font-medium text-green-400 hover:underline"
    >
      Visit Website →
    </a>
  </div>

</div>
