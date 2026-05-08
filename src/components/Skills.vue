<template>
  <section id="skills" class="py-20 bg-slate-900 text-white">
    <div class="max-w-6xl mx-auto px-6">
      <h2 class="text-3xl font-bold mb-12 text-center">Expertises <span class="text-blue-400">Techniques</span></h2>
      
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <!-- Backend -->
        <div class="p-6 rounded-2xl bg-slate-800/50 border border-slate-700 hover:border-blue-500/50 transition-all">
          <div class="w-12 h-12 bg-blue-500/10 rounded-lg flex items-center justify-center mb-4">
            <span class="text-2xl">🐘</span>
          </div>
          <h3 class="text-xl font-semibold mb-3">Back-end</h3>
          <ul class="text-slate-400 space-y-2">
            <li>Expert PHP & Laravel</li>
            <li>Architecture d'API REST</li>
            <li>Inertia.js & MySQL</li>
          </ul>
        </div>

        <!-- Frontend -->
        <div class="p-6 rounded-2xl bg-slate-800/50 border border-slate-700 hover:border-emerald-500/50 transition-all">
          <div class="w-12 h-12 bg-emerald-500/10 rounded-lg flex items-center justify-center mb-4">
            <span class="text-2xl">⚡</span>
          </div>
          <h3 class="text-xl font-semibold mb-3">Front-end</h3>
          <ul class="text-slate-400 space-y-2">
            <li>Vue.js 3 (Composition API)</li>
            <li>Tailwind CSS / Bootstrap</li>
            <li>Interface réactive & UX</li>
          </ul>
        </div>

        <!-- IA & Innovation -->
        <div class="p-6 rounded-2xl bg-slate-800/50 border border-slate-700 hover:border-purple-500/50 transition-all">
          <div class="w-12 h-12 bg-purple-500/10 rounded-lg flex items-center justify-center mb-4">
            <span class="text-2xl">🤖</span>
          </div>
          <h3 class="text-xl font-semibold mb-3">IA & Innovation</h3>
          <ul class="text-slate-400 space-y-2">
            <li>Intégration API OpenAI</li>
            <li>Prompt Engineering</li>
            <li>Automatisation de processus</li>
          </ul>
        </div>
      </div>
    </div>
  </section>
</template>
