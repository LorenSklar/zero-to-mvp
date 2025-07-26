<script>
  import Hero from '$lib/Hero.svelte';
  import IsThisForYou from '$lib/IsThisForYou.svelte';
  import HowItWorks from '$lib/HowItWorks.svelte';
  import Pricing from '$lib/Pricing.svelte';
  import WhyUs from '$lib/WhyUs.svelte';
  import WhatFoundersAreSaying from '$lib/WhatFoundersAreSaying.svelte';
  import MeetYourCoach from '$lib/MeetYourCoach.svelte';
  import BookCall from '$lib/BookCall.svelte';
  import Footer from '$lib/Footer.svelte';
</script>

<main>
  <section>
    <Hero />
  </section>
  <hr class="section-divider" />

  <section>
    <IsThisForYou />
  </section>
  <hr class="section-divider" />

  <section>
    <HowItWorks />
  </section>
  <hr class="section-divider" />

  <section>
    <Pricing />
  </section>
  <hr class="section-divider" />

  <section>
    <WhyUs />
  </section>
  <hr class="section-divider" />

  <section>
    <WhatFoundersAreSaying />
  </section>
  <hr class="section-divider" />

  <section>
    <MeetYourCoach />
  </section>
  <hr class="section-divider" />

  <section id="bookcall">
    <BookCall />
  </section>

  <Footer />
</main>
