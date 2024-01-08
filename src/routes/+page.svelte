<script lang="ts">
  import { browser } from '$app/environment';
  
  let domain = "";
  
  if (browser) {
    domain = window.location.hostname;
    domain = domain.replace("www.","");
  }
  domain = "tomasjanecek.cz";
</script>

<!-- Hire Us -->
<div class="max-w-[85rem] px-4 py-10 sm:px-6 lg:px-8 lg:py-14 mx-auto">
    <!-- Grid -->
    <div class="grid md:grid-cols-3 gap-12">
      <div class="lg:col-span-2">
        <h1 class="text-3xl font-bold text-gray-800 sm:text-2xl lg:text-4xl lg:leading-tight dark:text-white">
          <strong>{domain}</strong> je na prodej
        </h1>
        <p class="mt-1 md:text-lg text-gray-800 dark:text-gray-200">
          Máte zájem o koupi nebo pronájem této domény? Vyplňte formulář a my se vám ozveme zpět.
        </p>

        <div class="bg-gradient-to-tl from-orange-500 to-yellow-300 mt-7 mb-7 rounded-2xl">
          <div class="text-center p-20">
            <span class="block text-5xl font-bold text-gray-800 dark:text-white">{domain}</span>
          </div>
        </div>
  
        <div class="">
          <!-- Accordion -->
          <div class="hs-accordion-group">
            <div class="hs-accordion hs-accordion-active:bg-gray-100 rounded-xl p-6 dark:hs-accordion-active:bg-white/[.05] active" id="hs-basic-with-title-and-arrow-stretched-heading-one">
              <button class="hs-accordion-toggle group pb-3 inline-flex items-center justify-between gap-x-3 w-full md:text-lg font-semibold text-start text-gray-800 rounded-lg transition hover:text-gray-500 dark:text-gray-200 dark:hover:text-gray-400 dark:focus:outline-none dark:focus:ring-1 dark:focus:ring-gray-600" aria-controls="hs-basic-with-title-and-arrow-stretched-collapse-one">
                Jaká je cena domény?
                <svg class="hs-accordion-active:hidden block flex-shrink-0 w-5 h-5 text-gray-600 group-hover:text-gray-500 dark:text-gray-400" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m6 9 6 6 6-6"/></svg>
                <svg class="hs-accordion-active:block hidden flex-shrink-0 w-5 h-5 text-gray-600 group-hover:text-gray-500 dark:text-gray-400" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m18 15-6-6-6 6"/></svg>
              </button>
              <div id="hs-basic-with-title-and-arrow-stretched-collapse-one" class="hs-accordion-content w-full overflow-hidden transition-[height] duration-300" aria-labelledby="hs-basic-with-title-and-arrow-stretched-heading-one">
                <p class="text-gray-800 dark:text-gray-200">
                  Cena je určena na základě několika parametrů a rádi vám ji sdělíme během vyřízení vaší poptávky.
                </p>
              </div>
            </div>
      
            <div class="hs-accordion hs-accordion-active:bg-gray-100 rounded-xl p-6 dark:hs-accordion-active:bg-white/[.05]" id="hs-basic-with-title-and-arrow-stretched-heading-two">
              <button class="hs-accordion-toggle group pb-3 inline-flex items-center justify-between gap-x-3 w-full md:text-lg font-semibold text-start text-gray-800 rounded-lg transition hover:text-gray-500 dark:text-gray-200 dark:hover:text-gray-400 dark:focus:outline-none dark:focus:ring-1 dark:focus:ring-gray-600" aria-controls="hs-basic-with-title-and-arrow-stretched-collapse-two">
                Jak probíhá prodej?
                <svg class="hs-accordion-active:hidden block flex-shrink-0 w-5 h-5 text-gray-600 group-hover:text-gray-500 dark:text-gray-400" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m6 9 6 6 6-6"/></svg>
                <svg class="hs-accordion-active:block hidden flex-shrink-0 w-5 h-5 text-gray-600 group-hover:text-gray-500 dark:text-gray-400" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m18 15-6-6-6 6"/></svg>
              </button>
              <div id="hs-basic-with-title-and-arrow-stretched-collapse-two" class="hs-accordion-content hidden w-full overflow-hidden transition-[height] duration-300" aria-labelledby="hs-basic-with-title-and-arrow-stretched-heading-two">
                <p class="text-gray-800 dark:text-gray-200">
                  Po odsouhlasení finální ceny je vystavena fakturace a smlouva. Po úhradě fakturace bude doména převedena do vašeho vlastnictví.
                </p>
              </div>
            </div>
      
            <div class="hs-accordion hs-accordion-active:bg-gray-100 rounded-xl p-6 dark:hs-accordion-active:bg-white/[.05]" id="hs-basic-with-title-and-arrow-stretched-heading-three">
              <button class="hs-accordion-toggle group pb-3 inline-flex items-center justify-between gap-x-3 w-full md:text-lg font-semibold text-start text-gray-800 rounded-lg transition hover:text-gray-500 dark:text-gray-200 dark:hover:text-gray-400 dark:focus:outline-none dark:focus:ring-1 dark:focus:ring-gray-600" aria-controls="hs-basic-with-title-and-arrow-stretched-collapse-three">
                Mohu si doménu pronajmout?
                <svg class="hs-accordion-active:hidden block flex-shrink-0 w-5 h-5 text-gray-600 group-hover:text-gray-500 dark:text-gray-400" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m6 9 6 6 6-6"/></svg>
                <svg class="hs-accordion-active:block hidden flex-shrink-0 w-5 h-5 text-gray-600 group-hover:text-gray-500 dark:text-gray-400" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m18 15-6-6-6 6"/></svg>
              </button>
              <div id="hs-basic-with-title-and-arrow-stretched-collapse-three" class="hs-accordion-content hidden w-full overflow-hidden transition-[height] duration-300" aria-labelledby="hs-basic-with-title-and-arrow-stretched-heading-three">
                <p class="text-gray-800 dark:text-gray-200">
                  Ano. Je možné se domluvit na pronájmu domény. Doména pak přejde do vašeho vlastnictví po uplynutí "splátkového kalendáře".
                </p>
              </div>
            </div>
      
          </div>
          <!-- End Accordion -->
        </div>
  
      </div>
      <!-- End Col -->
  
      <div>
        <!-- Card -->
        <div class="flex flex-col border rounded-xl p-4 sm:p-6 lg:p-10 dark:border-gray-700">
          <h2 class="text-xl font-semibold text-gray-800 dark:text-gray-200">
            Vyplňte poptávkový formulář
          </h2>
  
          <form action="https://formspree.io/f/xvoeokyg" method="POST">
            <div class="mt-6 grid gap-4 lg:gap-6">
              <!-- Grid -->
              <div>
                <div>
                  <label for="hs-firstname-hire-us-1" class="block mb-2 text-sm text-gray-700 font-medium dark:text-white">Jméno a příjmení</label>
                  <input type="text" name="name" id="hs-firstname-hire-us-1" class="py-3 px-4 block w-full border  border-gray-200 rounded-lg text-sm focus:border-blue-500 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-slate-900 dark:border-gray-700 dark:text-gray-400 dark:focus:ring-gray-600">
                </div>
              </div>
              <!-- End Grid -->
  
              <div>
                <label for="hs-work-email-hire-us-1" class="block mb-2 text-sm text-gray-700 font-medium dark:text-white">E-mail</label>
                <input type="email" name="email" id="hs-work-email-hire-us-1" autocomplete="email" class="py-3 px-4 block w-full border border-gray-200 rounded-lg text-sm focus:border-blue-500 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-slate-900 dark:border-gray-700 dark:text-gray-400 dark:focus:ring-gray-600">
              </div>
              <input type="hidden" name="domain" value="{domain}" />
              <div>
                <label for="hs-about-hire-us-1" class="block mb-2 text-sm text-gray-700 font-medium dark:text-white">Vaše poznámka</label>
                <textarea id="hs-about-hire-us-1" name="note" rows="4" class="py-3 px-4 block w-full border border-gray-200 rounded-lg text-sm focus:border-blue-500 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-slate-900 dark:border-gray-700 dark:text-gray-400 dark:focus:ring-gray-600"></textarea>
              </div>
            </div>
            <!-- End Grid -->
  
            <div class="mt-6 grid">
              <button type="submit" class="w-full py-3 px-4 inline-flex justify-center items-center gap-x-2 text-sm font-semibold rounded-lg border border-transparent bg-blue-600 text-white hover:bg-blue-700 disabled:opacity-50 disabled:pointer-events-none dark:focus:outline-none dark:focus:ring-1 dark:focus:ring-gray-600">Odeslat poptávku</button>
            </div>
          </form>
        </div>
        <!-- End Card -->
      </div>
      <!-- End Col -->
    </div>
    <!-- End Grid -->
  </div>
  <!-- End Hire Us -->