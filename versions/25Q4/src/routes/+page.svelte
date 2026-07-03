<script lang="ts">
  import logo from "$lib/assets/sentzel-wordmark.svg";
  import juxtaIcon from "$lib/assets/juxta-icon.png";
</script>

<!-- Hero -->
<section class="relative flex justify-center items-center min-h-screen bg-white">
  <img src={logo} alt="Sentzel Labs" class="h-16" />
  <div
    class="absolute left-1/2 -translate-x-1/2 top-[calc(50%+3rem)] bottom-10 flex flex-col items-center justify-evenly"
  >
    <span class="text-black text-xs leading-none">▪</span>
    <span class="text-black text-xs leading-none">▪</span>
    <span class="text-black text-xs leading-none">▪</span>
  </div>
</section>

<!-- Mission -->
<section class="flex flex-col bg-white pb-32 pt-0 px-8">
  <div class="max-w-2xl mx-auto text-center">
    <p class="text-gray-500 text-lg leading-relaxed">
      We create <span class="font-semibold text-gray-900"
        >player-centered technologies</span
      > that sense how players engage with games, capturing preferences, behaviors, and motivations
      to deliver truly personalized experiences.
    </p>
  </div>
  <div class="mx-auto text-center py-32">
    <a href="https://juxta.gg" class="flex flex-row items-center gap-5 m-5">
      <img src={juxtaIcon} alt="Juxta.gg" class="h-16" />
      Juxta.gg
    </a>
  </div>
</section>

<!-- Footer -->
<footer class="bg-white py-12 px-8">
  <div class="max-w-2xl mx-auto flex flex-col items-center gap-1">
    <a href="mailto:kadir@sentzel.com" class="text-xs text-gray-400 hover:text-gray-600"
      >kadir@sentzel.com</a
    >
    <p class="text-xs text-gray-400">&copy; {new Date().getFullYear()} Sentzel Labs</p>
  </div>
</footer>
