<script lang="ts">
  import logo from "$lib/assets/sentzel-wordmark.svg";
  import juxtaIcon from "$lib/assets/juxta-icon.png";
</script>

<main class="flex flex-col h-screen bg-white">
  <!-- Hero -->
  <section class="flex flex-1 justify-center items-center min-h-0 px-8">
    <div class="max-w-2xl">
      <img src={logo} alt="Sentzel Labs" class="h-16" />
      <p class="mt-8 text-gray-500 text-lg leading-relaxed">
        Experience something unforgettable.
      </p>
      <a href="https://juxta.gg" class="mt-12 flex flex-row items-center gap-5">
        <img src={juxtaIcon} alt="Juxta.gg" class="h-16" />
        Juxta.gg
      </a>
    </div>
  </section>

  <!-- Footer -->
  <footer class="px-8 pb-8">
    <div class="max-w-2xl mx-auto flex flex-row items-center gap-4">
      <p class="text-xs text-gray-400">&copy; {new Date().getFullYear()} Sentzel Labs</p>
      <a href="mailto:kadir@sentzel.com" class="text-xs text-gray-400 hover:text-gray-600"
        >kadir@sentzel.com</a
      >
    </div>
  </footer>
</main>
