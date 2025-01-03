<template>
  <div class="bg-[#0c0c0c]">
    <Container>
      <nav class="flex justify-between items-center">
        <NuxtLink to="/">
          <img src="/logo.png" class="w-28 mix-blend-hard-light" alt="">
        </NuxtLink>
        <ButtonsPrimary>Buy Now</ButtonsPrimary>
      </nav>

      <header class="py-12 flex items-center gap-4 relative">
        <div class="grid gap-8 absolute md:left-1/4">
          <NuxtLink class="link grid place-content-center items-center w-14 h-14">
            <img src="/x.svg" class="w-10 h-10" alt="">
          </NuxtLink>

          <NuxtLink class="link grid place-content-center items-center w-14 h-14">
            <img src="/dex.svg" class="w-10 h-10" alt="">
          </NuxtLink>
        </div>

        <img src="/01.png" class="mx-auto mix-overlay w-fit" alt="">
        
        <div class="grid gap-8 absolute right-0 md:right-1/4 ">
          <NuxtLink class="link grid place-content-center items-center w-14 h-14">
            <img src="/tg.svg" class="w-10 h-10" alt="">
          </NuxtLink>
          <NuxtLink class="link grid place-content-center items-center w-14 h-14">
            <img src="/coin.svg" class="w-10 h-10" alt="">
          </NuxtLink>
        </div>
      </header>

      <section class="py-12">
        <H1 class="text-white text-center mx-auto">About Us</H1>
        <P class="text-white mt-2 text-center mx-auto">Adding Sweetness on SUI chain, Join us and experience the SUItness of the SYRUP 😋
        </P>

        <ul class="grid md:grid-cols-2 lg:grid-cols-3 gap-6 mt-20 items-stretch place-content-center">
          <li class="link py-5 place-content-center">
            <h2 class="heading text-4xl text-center mx-auto">Name</h2>
            <P>Sui Syrup</P>
          </li>
          <li class="link py-5 lg:-mt-8 lg:mb-8">
            <h2 class="heading text-4xl text-center mx-auto">Ticker</h2>
            <P>$SYRUP            </P>
          </li>
          <li class="link py-5">
            <h2 class="heading text-4xl text-center mx-auto">Ownership</h2>
            <P>Renounced</P>
          </li>
          <li class="link py-5">
            <h2 class="heading text-4xl text-center mx-auto">LP</h2>
            <P>Burned</P>
          </li>
          <li class="link py-5 lg:-mb-8 lg:mt-8">
            <h2 class="heading text-4xl text-center mx-auto">Tax</h2>
            <P>0%</P>
          </li>
          <li class="link py-5">
            <h2 class="heading text-4xl text-center mx-auto">Supply</h2>
            <P>10,000,000</P>
          </li>
        </ul>
      </section>

      <section style="background: url('/02.jpg'); background-blend-mode: color-dodge; background-size: cover; background-repeat: no-repeat;" class="">

      </section>
    </Container>

  </div>
</template>
<style>
@import url(https://db.onlinewebfonts.com/c/94ca5b48616ca463f31d6bc2b281b8ab?family=SyrupScript-Regular);
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
.heading {
  font-family: "SyrupScript-Regular";
}

body {
  font-family: 'Poppins', sans-serif;
}

.link {background-image: linear-gradient(to right, #e52d27 0%, #700400  51%, #700400  100%)}
.link {
  text-align: center;
  transition: 0.5s;
  background-size: 200% auto;
  color: white;            
  box-shadow: 0 0 10px #e52d27;
  border-radius: 10px;
}
</style>