<script>
  export let active = "How It Works";
</script>

<header class="sticky top-0 z-50 w-full border-b border-gray-100 bg-white/95 backdrop-blur-sm">
  <div class="mx-auto flex h-16 max-w-7xl items-center justify-between px-4 sm:px-6 lg:px-8">
    <div class="flex items-center gap-8">
      <a href="/" class="flex items-center gap-2">
        <svg width="32" height="32" viewBox="0 0 97 97" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path opacity="0.3" d="M96.9121 67.6667V29C96.9121 12.9837 84.0179 0 68.1121 0H29.7121L0.912109 29H53.7121C61.665 29 68.1121 35.4919 68.1121 43.5V96.6667L96.9121 67.6667Z" fill="black"/>
          <path d="M0.912113 29L0.912109 67.6667C0.912108 83.6829 13.8063 96.6667 29.7121 96.6667H68.1121L96.9121 67.6667H48.9121C38.3082 67.6667 29.7121 59.0109 29.7121 48.3333V0L0.912113 29Z" fill="black"/>
        </svg>
        <span class="text-2xl font-bold tracking-tight font-sans">Kubence</span>
      </a>
      
      <nav class="hidden md:flex items-center gap-6">
        {#each ["How It Works", "Benefits", "Safety", "Contact"] as item}
          <a href="#{item.toLowerCase().replace(/\s+/g, '-')}" class="text-sm font-medium text-gray-600 hover:text-gray-900 transition-colors">
            {item}
          </a>
        {/each}
      </nav>
    </div>

    <div class="flex items-center gap-4">
      <a href="https://portal.kubence.com" class="text-sm font-medium text-gray-900 hover:text-gray-700">
        Portal Login
      </a>
      <a href="#waitlist" class="rounded-full bg-black px-4 py-2 text-sm font-medium text-white hover:bg-gray-800 transition-colors">
        Join Waitlist
      </a>
    </div>
  </div>
</header>
