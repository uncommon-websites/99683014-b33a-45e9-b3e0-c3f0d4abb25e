<script>
  import SectionLabel from './SectionLabel.svelte';
  
  const testimonials = [
    {
      quote: "Nevis will completely transform our technology stack, updating it for the future with critical AI enabled features that will have a meaningful impact on how we do our jobs every day and service clients.",
      author: "Jim Rivers",
      title: "President",
      company: "United Capital"
    },
    {
      quote: "We've explored every so-called 'AI wealth tech', but Nevis stood out for being the real thing, a purpose-built, modern platform reimagining the advisor experience from the ground up.",
      author: "Dave Breslin",
      title: "Executive Vice President",
      company: "GC Wealth"
    },
    {
      quote: "Nevis leverages deep global experience to solve the real, firm-specific problems wealth managers face every day. Their leadership team's track record tackling complex, multinational operational challenges is a breath of fresh air.",
      author: "Brad Goodman",
      title: "Chief Operating Officer",
      company: "Apollon Wealth Management"
    },
    {
      quote: "Nevis are a true partner built for forward-thinking RIAs. The platform's depth and focus on workflow automation are exactly what we need.",
      author: "Michael Dodds",
      title: "President & Financial Advisor",
      company: "Dodds Wealth"
    }
  ];
</script>

<section class="bg-[#f5f5f5] px-6 py-24 border-t border-gray-200">
  <div class="max-w-[1400px] mx-auto">
    <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 mb-16">
      <div class="lg:col-span-3">
        <SectionLabel label="Testimonials" />
      </div>
      <div class="lg:col-span-9">
        <h2 class="font-serif text-4xl md:text-5xl text-gray-900">
          Trusted by leading wealth management firms
        </h2>
      </div>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
      {#each testimonials as testimonial}
        <div class="bg-white p-8 rounded-sm border border-gray-200 hover:border-gray-300 transition-colors">
          <p class="text-gray-700 leading-relaxed mb-6 text-lg">
            "{testimonial.quote}"
          </p>
          <div class="border-t border-gray-200 pt-4">
            <p class="font-medium text-gray-900">{testimonial.author}</p>
            <p class="text-sm text-gray-500">{testimonial.title}</p>
            <p class="text-sm text-gray-500">{testimonial.company}</p>
          </div>
        </div>
      {/each}
    </div>
  </div>
</section>
