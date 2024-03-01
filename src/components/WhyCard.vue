<template>
    <!-- <div> -->
    
        <div class="why_card w-72 flex flex-col items-center text-center p-5 gap-3">
          <slot name="icon">card icon here..</slot>
          <div class="flex flex-col gap-3">
            <h3 class="text-2xl font-bold">
                <slot name="title"></slot>
            </h3>
            <p>
              <slot name="content"></slot>
            </p>
          </div>
        </div>
</template>

<script>
    export default {
        name: "WhyCard",
        
    }
</script>

<style scoped>

</style>