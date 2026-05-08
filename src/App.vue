<script setup>
import Navbar from './components/Navbar.vue'
import Hero from './components/Hero.vue'
import Skills from './components/Skills.vue'
import Projects from './components/Projects.vue'
import Experience from './components/Experience.vue'
import Contact from './components/Contact.vue' // <-- Import
</script>

<template>
  <main class="bg-slate-900 min-h-screen font-sans">
    <Navbar />
    <Hero />
    <Skills />
    <Projects />
    <Experience />
    <Contact /> <!-- <-- Affichage -->
    
    <footer class="py-10 text-center text-slate-500 border-t border-slate-800">
      <p>© {{ new Date().getFullYear() }} Maguette Fall SEYE</p>
    </footer>
  </main>
</template>
