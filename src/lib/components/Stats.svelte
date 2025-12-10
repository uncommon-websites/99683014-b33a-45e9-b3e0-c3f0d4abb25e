<script>
  import SectionLabel from './SectionLabel.svelte';
</script>

<section class="bg-white px-6 py-24">
  <div class="max-w-[1400px] mx-auto">
    <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 mb-16">
      <div class="lg:col-span-3">
        <SectionLabel label="Recognition" />
      </div>
      <div class="lg:col-span-9">
        <h2 class="font-serif text-4xl md:text-5xl text-gray-900 mb-4">
          The fastest growing tech startup in wealth management
        </h2>
        <p class="text-gray-500 text-lg leading-relaxed max-w-2xl">
          Featured in Bloomberg and backed by the world's leading investors, Nevis is building the future of advisor technology.
        </p>
      </div>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-3 gap-8 border-t border-gray-200 pt-12">
      <div class="flex flex-col gap-2">
        <div class="text-5xl font-bold text-gray-900">$40M</div>
        <div class="text-sm text-gray-500">Series A funding from Sequoia, Ribbit, and Iconiq Capital</div>
      </div>
      
      <div class="flex flex-col gap-2">
        <div class="text-5xl font-bold text-gray-900">SOC 2</div>
        <div class="text-sm text-gray-500">Type I certified with enterprise-grade security standards</div>
      </div>
      
      <div class="flex flex-col gap-2">
        <div class="text-5xl font-bold text-gray-900">50M+</div>
        <div class="text-sm text-gray-500">Advisors globally in our addressable market</div>
      </div>
    </div>

    <div class="mt-16 p-8 bg-gray-50 rounded-sm border border-gray-200">
      <div class="flex items-start gap-4">
        <div class="flex-shrink-0 mt-1">
          <svg class="w-6 h-6 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path>
          </svg>
        </div>
        <div>
          <p class="text-gray-600 italic leading-relaxed mb-2">
            "Sequoia Bets on AI Startup to Ease Wealth Advisers' Grunt Work"
          </p>
          <p class="text-xs text-gray-500">Bloomberg, December 1, 2025</p>
        </div>
      </div>
    </div>
  </div>
</section>
