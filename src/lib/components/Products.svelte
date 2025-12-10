<script>
  import SectionLabel from './SectionLabel.svelte';
</script>

<section class="bg-[#f5f5f5] px-6 py-24 border-t border-gray-200">
  <div class="max-w-[1400px] mx-auto grid grid-cols-1 lg:grid-cols-12 gap-12">
    <div class="lg:col-span-3">
      <SectionLabel label="Platform" />
    </div>
    
    <div class="lg:col-span-9">
      <div class="mb-16">
        <h2 class="font-serif text-4xl md:text-5xl text-gray-900 mb-2">
          One platform for all
        </h2>
        <h2 class="font-serif text-4xl md:text-5xl text-gray-400">
          advisor workflows
        </h2>
      </div>

      <div class="grid gap-0 border-t border-gray-200">
        <!-- Item 1 -->
        <div class="group grid grid-cols-1 md:grid-cols-12 gap-6 py-10 border-b border-gray-200 hover:bg-white transition-colors px-4 -mx-4">
          <div class="md:col-span-4">
            <div class="text-xs text-gray-400 mb-1">Core capability</div>
            <h3 class="text-2xl font-medium text-gray-900">Unified AI workflows</h3>
          </div>
          <div class="md:col-span-7">
            <p class="text-gray-500 leading-relaxed">
              Automate client onboarding, document processing, compliance checks, and routine communications through intelligent workflows that learn from your firm's processes.
            </p>
          </div>
          <div class="md:col-span-1 flex justify-end items-start pt-2">
            <svg class="w-6 h-6 text-gray-400 group-hover:text-black transition-all" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
          </div>
        </div>

        <!-- Item 2 -->
        <div class="group grid grid-cols-1 md:grid-cols-12 gap-6 py-10 border-b border-gray-200 hover:bg-white transition-colors px-4 -mx-4">
          <div class="md:col-span-4">
            <div class="text-xs text-gray-400 mb-1">Security & compliance</div>
            <h3 class="text-2xl font-medium text-gray-900">Enterprise-grade protection</h3>
          </div>
          <div class="md:col-span-7">
            <p class="text-gray-500 leading-relaxed">
              SOC 2 Type I certified with enterprise agreements from OpenAI and Anthropic. Your client data never trains our models—complete confidentiality guaranteed.
            </p>
          </div>
          <div class="md:col-span-1 flex justify-end items-start pt-2">
            <svg class="w-6 h-6 text-gray-400 group-hover:text-black transition-all" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
          </div>
        </div>

        <!-- Item 3 -->
        <div class="group grid grid-cols-1 md:grid-cols-12 gap-6 py-10 border-b border-gray-200 hover:bg-white transition-colors px-4 -mx-4">
          <div class="md:col-span-4">
            <div class="text-xs text-gray-400 mb-1">Integration</div>
            <h3 class="text-2xl font-medium text-gray-900">Works with your stack</h3>
          </div>
          <div class="md:col-span-7">
            <p class="text-gray-500 leading-relaxed">
              Seamlessly integrates with your existing CRM, portfolio management, and custodian systems. No rip-and-replace—just enhanced capabilities across your entire tech stack.
            </p>
          </div>
          <div class="md:col-span-1 flex justify-end items-start pt-2">
            <svg class="w-6 h-6 text-gray-400 group-hover:text-black transition-all" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
