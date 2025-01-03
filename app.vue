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
          <NuxtLink to="https://x.com/suisyrup?t=ReGN1G2tL6azS1hMhZU_gA&s=09" class="link grid place-content-center items-center w-14 h-14">
            <img src="/x.svg" class="w-10 h-10" alt="">
          </NuxtLink>

          <NuxtLink class="link grid place-content-center items-center w-14 h-14">
            <img src="/dex.svg" class="w-10 h-10" alt="">
          </NuxtLink>
        </div>

        <img src="/01.png" class="mx-auto mix-overlay w-fit" alt="">
        
        <div class="grid gap-8 absolute right-0 md:right-1/4 ">
          <NuxtLink to="https://t.me/Sui_Syrup" class="link grid place-content-center items-center w-14 h-14">
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

        <ul class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 mt-20 lg:items-stretch place-content-center">
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

      <section class="py-24 grid lg:grid-cols-2 items-center">
        <img src="/05.jpg" class="mx-auto mix-blend-screen" alt="">

        <div>
          <H1 class="text-white text-center mx-auto">How to Buy</H1>
          <div class="flex gap-12 text-primary mt-6">
            <div class="flex relative justify-center text-white">
              <div data-aos="fade-left" class="bg-primary w-0.5 h-full -mr-5"></div>
              <ul class="flex flex-col gap-6 justify-around h-full w-full">
                <li data-aos="fade-left" data-aos-delay="100" class="flex gap-6">
                  <div class="bg-primary heading min-w-10 h-10 w-10 rounded-full grid place-content-center text-white text-xl">01</div>
                  <div>
                    <h4 class="heading text-2xl">Create a Sui Wallet</h4>
                    <TypographyP>Download Sui Wallet or your wallet of choice from the app store or google play store for free. Desktop users, download the google chrome extension by going to sui.app.
                    </TypographyP>
                  </div>
                </li>
                <li data-aos="fade-left" data-aos-delay="100" class="flex gap-6">
                  <div class="bg-primary heading min-w-10 w-10 h-10 rounded-full grid place-content-center text-white text-xl">02</div>
                  <div>
                    <h4 class="heading text-2xl">Get Some SUI</h4>
                    <TypographyP>Have SUI in your wallet to switch to $SEAL. If you don't have any SUI , you can buy SUI from an exchange or cross chain swap and send it to your wallet.
                    </TypographyP>
                  </div>
                </li>
                <li data-aos="fade-left" data-aos-delay="100" class="flex gap-6">
                  <div class="bg-primary heading min-w-10 w-10 h-10 rounded-full grid place-content-center text-white text-xl">03</div>
                  <div>
                    <h4 class="heading text-2xl">Go to BlueMove</h4>
                    <TypographyP>Connect to BlueMove. Go bluemove.net in google chrome or on the browser inside your Sui Wallet. Connect your wallet. Paste the $SEAL token address into BlueMove swap and confirm the swap. When Sui Wallet prompts you for a wallet signature, sign.
                    </TypographyP>
                  </div>
                </li>
                <li data-aos="fade-left" data-aos-delay="100" class="flex gap-6">
                  <div class="bg-primary heading min-w-10 w-10 h-10 rounded-full grid place-content-center text-white text-xl">04</div>
                  <div>
                    <h4 class="heading text-2xl">Buy $SYRUP</h4>
                    <TypographyP>Paste the token address (CA) into BlueMove and switch SUI for $SEAL. There's zero taxes so you don't need to worry.
                    </TypographyP>
                  </div>
                </li>
                <li data-aos="fade-left" data-aos-delay="100" class="flex gap-6">
                  <div class="bg-primary heading min-w-10 w-10 h-10 rounded-full grid place-content-center text-white text-xl">05</div>
                  <div>
                    <h4 class="heading text-2xl uppercase">Withdraw Your Winnings</h4>
                    <TypographyP>After a successful bet, withdraw your earnings quickly and securely via the platform's available payment options.
                    </TypographyP>
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </div>
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