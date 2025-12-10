<script lang="ts">
  import { slide } from 'svelte/transition';
  
  interface FAQItem {
    question: string;
    answer: string;
  }

  const faqs: FAQItem[] = [
    { question: "How does Nevis protect our client data?", answer: "Nevis is SOC 2 Type I certified and maintains enterprise-level agreements with OpenAI and Anthropic. Your client data never trains or updates our AI models. We guarantee complete confidentiality and you maintain full control over all client information." },
    { question: "Will AI replace our advisors?", answer: "No. Nevis is built on the belief that financial advice will always be human-led. Our AI empowers advisors by handling administrative tasks, freeing them to focus on client relationships and strategic advice. We augment advisors, not replace them." },
    { question: "How long does implementation take?", answer: "Implementation timelines vary by firm size and existing tech stack, but most firms are up and running within 4-6 weeks. Our team works closely with you to ensure seamless integration with your current systems." },
    { question: "Does Nevis integrate with our existing systems?", answer: "Yes. Nevis is designed to work seamlessly with your existing CRM, portfolio management systems, and custodian platforms. We integrate with your tech stack rather than requiring a complete replacement." },
    { question: "What size firms is Nevis built for?", answer: "Nevis is purpose-built for RIAs and growing wealth management firms. We work with firms ranging from boutique practices to large multi-advisor organizations managing admin-heavy workflows." },
    { question: "How much time can advisors actually save?", answer: "Our platform automates up to 80% of typical advisor admin work. This includes client onboarding, document processing, compliance checks, and routine communications—freeing advisors to focus on client relationships and growing their practice." },
    { question: "What makes Nevis different from other wealth tech solutions?", answer: "Nevis is built by the team that scaled Revolut globally. We bring fintech execution speed and deep operational expertise to wealth management. Our unified AI workflows are purpose-built for advisors, not adapted from generic tools." }
  ];

  let openIndex: number | null = null;

  function toggle(index: number) {
    openIndex = openIndex === index ? null : index;
  }
</script>

<section class="bg-[#f5f5f5] px-6 py-24">
  <div class="max-w-[1400px] mx-auto grid grid-cols-1 lg:grid-cols-12 gap-12">
    <div class="lg:col-span-4">
      <h2 class="font-serif text-4xl text-gray-900 mb-6">
        Frequently asked questions
      </h2>
      <a href="/" class="text-sm text-gray-900 border-b border-gray-300 pb-0.5 hover:border-black transition-colors">Contact support</a>
    </div>
    
    <div class="lg:col-span-8">
      <div class="border-t border-gray-200">
        {#each faqs as faq, i}
          <div class="border-b border-gray-200">
            <button 
              class="w-full py-6 flex justify-between items-center text-left hover:bg-gray-50 transition-colors"
              on:click={() => toggle(i)}
            >
              <span class="text-lg text-gray-800">{faq.question}</span>
              <span class="text-2xl font-light text-gray-400 ml-4">
                {openIndex === i ? '−' : '+'}
              </span>
            </button>
            {#if openIndex === i}
              <div transition:slide class="pb-6 text-gray-500 leading-relaxed">
                {faq.answer}
              </div>
            {/if}
          </div>
        {/each}
      </div>
    </div>
  </div>
</section>
