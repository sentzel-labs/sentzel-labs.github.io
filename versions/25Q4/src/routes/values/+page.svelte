<script lang="ts">
  import logo from "$lib/assets/sentzel-wordmark.svg";

  const values = [
    {
      name: "Tailor.",
      text: "We get to know each person, with their permission, and shape every experience around them. We fit people without boxing them in, so there is always room for a surprise.",
    },
    {
      name: "Charm.",
      text: "Everything we make earns people's time. It should be enjoyable, delightful, and worth retelling. We aim for great moments and great endings, not for hours played.",
    },
    {
      name: "Honor.",
      text: "We tell people what we learn and why. We listen, act on what they ask, and protect their privacy and data. We never use what we know to push people into spending or staying.",
    },
  ];
</script>

<svelte:head>
  <title>Values · Sentzel Labs</title>
</svelte:head>

<main class="flex flex-col min-h-screen bg-white">
  <section class="flex flex-1 items-center px-8 py-16">
    <div class="w-full max-w-2xl mx-auto">
      <a href="/"><img src={logo} alt="Sentzel Labs" class="h-16" /></a>
      <h1 class="mt-12 text-gray-900 text-2xl font-semibold">Values</h1>
      <div class="mt-8 flex flex-col gap-8">
        {#each values as value}
          <p class="text-gray-500 text-lg leading-relaxed">
            <strong class="text-gray-900 font-semibold">{value.name}</strong>
            {value.text}
          </p>
        {/each}
      </div>
    </div>
  </section>

  <footer class="px-8 pb-8">
    <div class="max-w-2xl mx-auto flex flex-row items-center gap-4">
      <p class="text-xs text-gray-400">&copy; {new Date().getFullYear()} Sentzel Labs</p>
      <a href="/" class="text-xs text-gray-400 hover:text-gray-600">Home</a>
      <a href="mailto:kadir@sentzel.com" class="text-xs text-gray-400 hover:text-gray-600"
        >kadir@sentzel.com</a
      >
    </div>
  </footer>
</main>
