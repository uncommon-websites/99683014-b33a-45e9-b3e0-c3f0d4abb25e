<script>
  import SectionLabel from './SectionLabel.svelte';
</script>

<section class="bg-[#f5f5f5] px-6 py-24">
  <div class="max-w-[1400px] mx-auto grid grid-cols-1 lg:grid-cols-12 gap-12">
    <div class="lg:col-span-3">
      <SectionLabel label="Why Echo" />
    </div>
    
    <div class="lg:col-span-9 grid grid-cols-1 md:grid-cols-2 gap-16">
      <div>
        <h2 class="font-serif text-3xl md:text-4xl leading-tight text-gray-900 mb-6">
          Echo helps projects reach a broader audience of real people from day 1
        </h2>
        <p class="text-gray-500 leading-relaxed">
          More than 85 private investing groups led by top VC firms and leading crypto investors — only available through Echo.
        </p>
      </div>
      
      <div class="flex gap-12 items-end pb-2">
        <div class="flex flex-col gap-1">
            <!-- Placeholder for stats if any specific numbers were there, screenshot shows labels -->
            <span class="text-xs text-gray-400">raised in private groups</span>
        </div>
        <div class="flex flex-col gap-1">
            <span class="text-xs text-gray-400">projects supported</span>
        </div>
      </div>
    </div>
  </div>
</section>
