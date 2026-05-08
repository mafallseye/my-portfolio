<template>
  <nav class="fixed top-0 w-full z-50 bg-slate-900/80 backdrop-blur-md border-b border-slate-800">
    <div class="max-w-6xl mx-auto px-6 h-16 flex items-center justify-between">
      <!-- Logo / Nom -->
      <div class="text-xl font-bold bg-clip-text text-transparent bg-gradient-to-r from-blue-400 to-emerald-400">
        MF.SEYE
      </div>

      <!-- Liens de navigation -->
      <div class="hidden md:flex space-x-8 text-sm font-medium text-slate-300">
        <a href="#skills" class="hover:text-blue-400 transition-colors">Compétences</a>
        <a href="#projects" class="hover:text-blue-400 transition-colors">Projets</a>
        <a href="#experience" class="hover:text-blue-400 transition-colors">Parcours</a>
      </div>

      <!-- Bouton Contact -->
      <a href="mailto:maguettefseye@gmail.com" 
         class="px-5 py-2 bg-blue-600 hover:bg-blue-700 text-white text-sm rounded-full transition-all shadow-lg shadow-blue-500/20">
        Me contacter
      </a>
    </div>
  </nav>
</template>
