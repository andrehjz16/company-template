<template>
  <div class="flex flex-col h-screen w-screen">
    <!--
      Navigation Bar

      PARAMETERS
      :logoURL  (URL for Logo)
    -->
    <NaviWrapper
      imgURL="https://www.google.com/url?sa=i&url=https%3A%2F%2Fcommons.wikimedia.org%2Fwiki%2FFile%3AMercedes-Benz_Logo_2010.svg&psig=AOvVaw0T9bn2Dk4XFXX1nM8fDB2_&ust=1596115388448000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCKiWwODH8uoCFQAAAAAdAAAAABAD"
    ></NaviWrapper>

    <div class="flex-1">
      <div class="flex">
        <Nuxt class="w-full h-screen overflow-y-auto"/>
      </div>
    </div>
    <FooterWrapper/>
  </div>
</template>
<script>
export default {};
</script>