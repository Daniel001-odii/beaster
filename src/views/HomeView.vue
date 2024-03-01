<template>
  <div>
    <div class="hero w-full h-screen flex flex-col justify-center items-center">
    <!-- <img src="../assets/images/istockphoto-1618162842-612x612.jpg"> -->
      <div class="overlay h-full w-full bg-[#000000d1] absolute"></div>

      <div class="flex flex-col justify-center text-center text-white items-center p-8 gap-4 z-10">
        <div class="flex flex-row items-center">
          <img src="../assets/images/ebay_PNG6.png" class=" h-14">
          <img src="../assets/images/amazon.png" class=" h-14">
        </div>
        <h1 class="text-3xl">Ebay & Amazon Virtual Assistant</h1>
        <p class=" text-4xl font-bold">Hire Virtual Assistants<br/> to Maximize Your Store Sales, Conversions, and Profits</p>

        <button class="py-4 px-8 bg-yellow-400 text-black rounded-lg text-lg font-bold mt-3 hover:bg-yellow-500">Request a free quotation</button>
      </div>


    </div>


    <div class="flex flex-col justify-center items-center text-center min-h-96 p-8">
      
      <div>
          <h2 class=" capitalize">Ebay Virtual Assistant services</h2>
          <span class=" font-bold text-3xl">Your Off-Site eBay Expert<br/> That Looks After Every Aspect of Your eBay Business!</span>
      </div>

      <div class="flex flex-col md:flex-row gap-6 justify-center items-center pt-8 w-full">
        <div class="card_1 h-80 w-full md:w-64 rounded-lg">
        </div>
        <div class="flex flex-col text-left md:w-3/6">
          <p>
            In today's scenario where competition is unrelenting and businesses are increasingly finding it difficult to cope with the ever-changing guidelines of marketplaces, the services of an eBay virtual assistant have suddenly become nearly indispensable. If you are looking for a reliable and proficient eBay expert who is experienced in handling all kinds of eBay processes, you are at the right place and reading the right stuff. We can add instant value to your eBay business!
          </p>
          <div class="flex flex-row gap-3 mt-4">
            <button class=" border-transparent p-4 px-8 bg-gray-800 hover:bg-gray-900 text-white font-bold rounded-lg">Learn More</button>
            <button class="border  border-2 p-4 px-8 font-bold rounded-lg hover:bg-slate-200">Contact Us</button>
          </div>
        </div>
      </div>
     
    </div>

    <div class="flex flex-col justify-center items-center text-center min-h-96 p-8 bg-black text-white">
      
      <div>
          <h2 class=" capitalize">Best Offers</h2>
          <span class=" font-bold text-3xl">Why is Ebay virtual assistant relevant today?</span>
      </div>

      <div class="flex flex-col md:flex-row-reverse gap-6 justify-center items-center pt-8 w-full">
        <div class="card_2 h-80 w-full md:w-64 rounded-lg">
        </div>
        <div class="flex flex-col text-left md:w-3/6">
          <p>
            We understand that managing your store on eBay (more importantly, managing well) is a time-consuming task. Sometimes, it may even get a bit confusing, but you cannot do without it all the same. On a typical day, you might need to look after the administrative, financial, technical and/or creative aspects of your business, which have to be flawless as well. Managing both—the core aspects of your business and an eBay store—is not an easy task to accomplish, unless you have a professionally managed eBay listing virtual assistant at your disposal. This allows you to focus on the core activities of your business while we take care of your eBay store.
          </p>
        </div>
      </div>
     
    </div>

    
    <div class="flex flex-col justify-center items-center text-center min-h-96 p-8">
      
      <div>
          <h2 class=" capitalize">How do we help?</h2>
          <span class=" font-bold text-3xl">OUR EBAY EXPERT CAN HELP YOU WITH:</span>
      </div>
      <div class="flex flex-row flex-wrap justify-center gap-1 mt-6">
        <div v-for="text in help_texts" :key="text.id" >
          <div class="p-8 rounded-lg bg-slate-100 text-slate-700 font-bold w-fit hover:bg-slate-700 hover:text-white hover:cursor-pointer">{{ text }}</div>
        </div>
      </div>
     
    </div>

    <div class="flex flex-col justify-center items-center text-center min-h-96 p-8 bg-yellow-400">
      
      <div>
          <h2 class=" capitalize">Why hire us</h2>
          <span class=" font-bold text-3xl">Why hire ebay assistants from beaster?</span>
      </div>
      <div class="flex flex-col text-center mt-3 md:w-3/6">
          <p>
            Hire eBay VA from us to get complete eBay solutions right from eBay listing and inventory management to handling customer support, PPC campaigns, and SEO optimization.
          </p>
      </div>

      <div class="flex flex-row justify-center flex-wrap">
      <WhyCard>
        <template #title>
          TRACK RECORD AND EXPERIENCE
        </template>
        <template #icon>
          <i class="bi bi-receipt text-4xl"></i>
        </template>
        <template #content>
          We have an impressive track record when it comes to providing highly-effective eBay solutions. Our eBay experts have extensive experience in inventory management services and other end-to-end eCommerce solutions for around two decades. We know what works and what has the potential to work. We, as your off-site companion, work to provide seamless eBay support.
        </template>
      </WhyCard>

      <WhyCard>
        <template #title>
          EBAY & AMAZON-SPECIFIC SOLUTIONS
        </template>
        <template #icon>
          <i class="bi bi-boxes text-4xl"></i>
        </template>
        <template #content>
          Our eBay listing assistant specializes in a gamut of services such as creating meaningful titles, writing informative descriptions, cropping and resizing product images, inventory management, customer support, PPC campaign, payment assistance, etc. In short, you pay for the entire spectrum of eBay store maintenance services.
        </template>
      </WhyCard>

      <WhyCard>
        <template #title>
          DATA MANAGEMENT
        </template>
        <template #icon>
          <i class="bi bi-database-fill-check text-4xl"></i>
        </template>
        <template #content>
          Frankly, a good eBay listing assistant service means excellent data management, something we’re extremely good at. Data-driven eBay store management is effective and is expected to bring out more business for you. We, at Team4eCom, have eBay listing virtual assistant professionals who understand the value of keeping well-organized data in eBay listing that boosts the sale
        </template>
      </WhyCard>
</div>

       

    </div>

    <div class="flex flex-col justify-center items-center text-center min-h-96 p-8">
          <h2 class=" font-bold text-3xl">OPTIMIZE YOUR EBAY STORE FOR EFFECTIVE FUNCTIONING AT AFFORDABLE PRICES</h2>
          <button class="py-4 px-8 bg-yellow-400 text-black rounded-lg text-lg font-bold mt-3 hover:bg-yellow-500">Request a free quotation</button>
          
    </div>

    <SiteFooter/>
</div>

</template>
<script>
import WhyCard from '@/components/WhyCard.vue';
import SiteFooter from '@/components/SiteFooter.vue';


export default {
    name: "Home",
    data() {
        return {
            help_texts: [
                "ORGANIZING YOUR LISTING",
                "CLEARING LISTING BACKLOGS",
                "INVENTORY MANAGEMENT",
                "EBAY CUSTOMER",
                "SUPPORT",
                "OPTIMIZING YOUR OPERATING COST",
                "BOOSTING SALES AND INCREASING PRODUCTIVITY",
                "ORDER PROCESSING, INCLUDING REFUND/RETURNS",
                "FREEING UP MORE TIME TO LOOK AFTER OTHER ASPECTS OF YOUR BUSINESS",
            ]
        };
    },
    components: { WhyCard, SiteFooter }
}
</script>
<style scoped>
 
  .hero{
    background-image: url('../assets/images/hero1.jpg');
    background-position: center;
    background-size: cover;
  }

  .card_1{
    background-image: url('../assets/images/hero2.jpg');
    background-size: cover;
    background-position: center;
  }

  .card_2{
    background-image: url('../assets/images/hero3.jpg');
    background-size: cover;
    background-position: center;
  }
</style>