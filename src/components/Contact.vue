<template>
  <section id="contact" class="py-20 bg-slate-900 text-white border-t border-slate-800">
    <div class="max-w-6xl mx-auto px-6">
      <div class="text-center mb-16">
        <h2 class="text-3xl font-bold mb-4">Parlons de votre <span class="text-blue-400">Projet</span></h2>
        <p class="text-slate-400">Disponible pour des opportunités en Full Stack ou des collaborations autour de l'IA.</p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
        <!-- Infos de contact -->
        <div class="space-y-8">
          <div class="flex items-start space-x-4">
            <div class="w-12 h-12 bg-blue-500/10 rounded-lg flex items-center justify-center text-blue-400">
              📧
            </div>
            <div>
              <h4 class="text-lg font-semibold">Email</h4>
              <p class="text-slate-400">maguettefseye@gmail.com</p>
            </div>
          </div>
          
          <div class="flex items-start space-x-4">
            <div class="w-12 h-12 bg-emerald-500/10 rounded-lg flex items-center justify-center text-emerald-400">
              📍
            </div>
            <div>
              <h4 class="text-lg font-semibold">Localisation</h4>
              <p class="text-slate-400">Dakar, Sénégal (Disponible en remote)</p>
            </div>
          </div>

          <!-- Liens Sociaux -->
          <div class="pt-6 flex space-x-4">
            <a href="https://www.linkedin.com/in/maguette-fall-seye/" target="_blank" class="p-3 bg-slate-800 rounded-full hover:bg-blue-600 transition-all">LinkedIn</a>
            <a href="https://github.com/mafallseye" target="_blank" class="p-3 bg-slate-800 rounded-full hover:bg-slate-700 transition-all">GitHub</a>
          </div>
        </div>

        <!-- Formulaire -->
     <form 
  name="contact" 
  method="POST" 
  data-netlify="true"
    action="/index.html"
>
          <!-- Cette ligne est invisible mais indispensable pour Netlify -->
          <input type="hidden" name="form-name" value="contact" />

          <div class="grid grid-cols-1 gap-6">
            <div>
              <label class="block text-sm font-medium text-slate-400 mb-2">Nom complet</label>
              <input type="text" name="name" required class="w-full bg-slate-800 border border-slate-700 rounded-lg px-4 py-3 text-white focus:outline-none focus:border-blue-500">
            </div>
            
            <div>
              <label class="block text-sm font-medium text-slate-400 mb-2">Email</label>
              <input type="email" name="email" required class="w-full bg-slate-800 border border-slate-700 rounded-lg px-4 py-3 text-white focus:outline-none focus:border-blue-500">
            </div>
            
            <div>
              <label class="block text-sm font-medium text-slate-400 mb-2">Message</label>
              <textarea name="message" rows="4" required class="w-full bg-slate-800 border border-slate-700 rounded-lg px-4 py-3 text-white focus:outline-none focus:border-blue-500"></textarea>
            </div>

            <button type="submit" class="w-full py-3 bg-blue-600 hover:bg-blue-700 rounded-lg font-bold shadow-lg shadow-blue-500/20 transition-all">
              Envoyer le message
            </button>
          </div>
        </form>
      </div>
    </div>
  </section>
</template>

<script setup>
// On laisse le script vide pour ne pas interférer avec l'envoi HTML standard
</script>
