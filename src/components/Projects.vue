<template>
  <section id="projects" class="py-20 bg-slate-900 text-white border-t border-slate-800">
    <div class="max-w-6xl mx-auto px-6">
      <div class="mb-12">
        <h2 class="text-3xl font-bold mb-4">Projets <span class="text-blue-400">Récents</span></h2>
        <p class="text-slate-400 text-lg">Sélection de mes travaux en développement et intégration d'IA.</p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <!-- Boucle dynamique sur les projets -->
        <div v-for="(project, index) in projects" :key="index" 
             class="group relative bg-slate-800/40 border border-slate-700 rounded-2xl overflow-hidden hover:border-blue-500/50 transition-all">
          <div class="p-8">
            <h3 class="text-2xl font-bold mb-4 group-hover:text-blue-400 transition-colors">
              {{ project.title }}
            </h3>
            <p class="text-slate-400 mb-6 leading-relaxed">
              {{ project.description }}
            </p>
            
            <!-- Liste des technos -->
            <div class="flex flex-wrap gap-2 mb-8">
              <span v-for="tech in project.stack" :key="tech"
                    class="px-3 py-1 bg-slate-700/50 rounded-full text-xs font-medium border border-slate-600">
                {{ tech }}
              </span>
            </div>

            <a v-if="project.link" :href="project.link" target="_blank" 
               class="text-blue-400 font-semibold inline-flex items-center hover:underline">
              Voir le projet <span class="ml-2">→</span>
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import { projects } from '../data.js' // On importe tes données ici
</script>
