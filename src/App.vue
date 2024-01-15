<template>
  <header class="text-white px-[16px] lg:px-[100px] py-[44px] lg:py-[88px]">
    <ul class="flex mb-3">
      <li><a href="#" class=""><img src="./components/icons/Home.png" width="22px" alt="icon-home"></a></li>
      <span class="px-[16px] align-middle">/</span>
      <li class="mt-[-1px]"><a href="#"
          class="hover:text-[#CBCBCB] text-[18px] text-[#CBCBCB] font-normal self-center">Contact</a></li>
    </ul>
    <h1 class="text-[40px] font-semibold mb-2">Contact</h1>
    <p class="text-[16px] font-normal lg:w-[900px]">Heb je nog vragen of wil je gewoon even kletsen over voetbal? Neem
      contact op via een van de onderstaande opties en we staan je graag te woord. Ook ben je tijdens kantooruren van
      harte welkom bij ons op kantoor in Maarssen!</p>
  </header>
  <section class="px-[16px] lg:px-[120px] bg-[#006FEB] py-5 text-white grid grid-cols-2 lg:grid-cols-5 gap-4">
    <ul class="flex">
      <div class="mr-3"><img src="./components/icons/trophy-icon.svg" width="24px" alt="trophy-icon"></div>
      <div class="align-middle">
        <div class="font-light text-[14px] mt-[3px]"><span class="font-semibold">Voordeligste</span> aanbieder</div>
      </div>
    </ul>
    <ul class="lg:flex hidden">
      <div class="mr-3"><img src="./components/icons/contact-icon.svg" width="24px" alt="contact-icon"></div>
      <div class="align-middle">
        <div class="font-light text-[14px] mt-[3px]"><span class="font-semibold">24/7</span> noodnummer</div>
      </div>
    </ul>
    <ul class="lg:flex hidden">
      <div class="mr-3"><img src="./components/icons/delivery-icon.svg" width="24px" alt="delivery-icon"></div>
      <div class="align-middle">
        <div class="font-light text-[14px] mt-[3px]"><span class="font-semibold">Geen</span> extra kosten</div>
      </div>
    </ul>
    <ul class="flex">
      <div class="mr-3"><img src="./components/icons/people-icon.svg" width="24px" alt="people-icon"></div>
      <div class="align-middle">
        <div class="font-light text-[14px] mt-[3px]"><span class="font-semibold">Zitplaatsen</span> bij elkaar</div>
      </div>
    </ul>
    <ul class="lg:flex hidden">
      <div class="mr-3"><img src="./components/icons/service-icon.svg" width="24px" alt="service-icon"></div>
      <div class="align-middle">
        <div class="font-light text-[14px] mt-[3px]"><span class="font-semibold">10000+</span> tevreden klanten</div>
      </div>
    </ul>
  </section>
  <section class="px-[16px] lg:px-[100px] py-[20px] lg:py-[40px]">
    <h1 class="text-[32px] font-semibold mb-[25px] lg:mb-[40px]">Neem contact op</h1>
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-4">
      <div class="px-[24px] py-[24px] border-[1px] rounded-2xl mb-4">
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-4">
          <div>
            <label for="fullname" class="font-semibold">Naam</label>
            <div class="mt-2"><input class="border-2 rounded-md py-[16px] pl-[16px] w-full" type="text"
                placeholder="Naam"></div>
          </div>
          <div>
            <label for="fullname" class="font-semibold">Email</label>
            <div class="mt-2"><input class="border-2 rounded-md py-[16px] pl-[16px] w-full" type="text"
                placeholder="Email"></div>
          </div>
        </div>
        <div class="mt-[16px]">
          <div>
            <label for="fullname" class="font-semibold">Onderwerp</label>
            <div class="mt-2"><input class="border-2 rounded-md py-[16px] pl-[16px] w-full" type="text"
                placeholder="Onderwerp"></div>
          </div>
        </div>
        <div class="mt-[16px]">
          <div>
            <label for="fullname" class="font-semibold">Bericht</label>
            <div class="mt-2"><textarea class="border-2 rounded-md py-[16px] pl-[16px] w-full" rows="5"
                placeholder="Bericht"></textarea></div>
          </div>
        </div>
        <div class="mt-[40px]">
          <button class="bg-[#006FEB] text-white px-[32px] py-[12px] rounded-3xl">
            <div class="flex"><span class="text-[16px] font-semibold mr-2">Arrow Button</span> <img
                src="./components/icons/arrow-icon.svg" alt="arrow-icon"></div>
          </button>
        </div>
      </div>
      <div class="px-[5px] py-3 mb-4">
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-4 mb-[32px]">
          <div class="flex justify-between lg:inline">
            <div class="flex">
              <div class="w-6 mr-4">
                <img src="./components/icons/contact.svg" width="20x" alt="">
              </div>
              <h5 class="text-[#006FEB] font-semibold text-[16px]">TELEFOON</h5>
            </div>
            <div class="align-middle lg:inline">
              <h6 class="text-[18px] lg:ml-[42px] lg:mt-3">030-3690059</h6>
            </div>
          </div>
          <div class="flex justify-between lg:inline">
            <div class="flex">
              <div class="w-6 mr-4 mt-1">
                <img src="./components/icons/email.svg" width="26x" alt="">
              </div>
              <h5 class="text-[#006FEB] font-semibold text-[16px]">E-MAIL</h5>
            </div>
            <div class="align-middle lg:inline">
              <h6 class="text-[18px] lg:ml-[42px] lg:mt-3">info@voetbaltrips.com</h6>
            </div>
          </div>
        </div>
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-4 mb-[32px]">
          <div class="flex justify-between lg:inline">
            <div class="flex">
              <div class="w-6 mr-4">
                <img src="./components/icons/instagram.svg" width="25x" alt="">
              </div>
              <h5 class="text-[#006FEB] font-semibold text-[16px]">INSTAGRAM</h5>
            </div>
            <div class="align-middle lg:inline">
              <h6 class="text-[18px] lg:ml-[42px] lg:mt-3 underline text-[#006FEB]">@voetbaltrips</h6>
            </div>
          </div>
          <div class="flex justify-between lg:inline">
            <div class="flex">
              <div class="w-6 mr-4">
                <img src="./components/icons/facebook.svg" width="23px" alt="">
              </div>
              <h5 class="text-[#006FEB] font-semibold text-[16px]">FACEBOOK</h5>
            </div>
            <div class="align-middle lg:inline">
              <h6 class="text-[18px] lg:ml-[42px] lg:mt-3 underline text-[#006FEB]">Voetbaltrips.com</h6>
            </div>
          </div>
        </div>
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-4 mb-[32px]">
          <div class="flex justify-between lg:inline">
            <div class="flex">
              <div class="w-6 mr-4">
                <img src="./components/icons/office-bag.svg" width="24px" alt="">
              </div>
              <h5 class="text-[#006FEB] font-semibold text-[16px]">KVK-NUMMER</h5>
            </div>
            <div class="align-middle lg:inline">
              <h6 class="text-[18px] lg:ml-[42px] lg:mt-3">74415670</h6>
            </div>
          </div>
          <div class="flex justify-between lg:inline">
            <div class="flex">
              <div class="w-6 mr-4">
                <img src="./components/icons/tax.svg" width="25px" alt="">
              </div>
              <h5 class="text-[#006FEB] font-semibold text-[16px]">BTW-NUMMER</h5>
            </div>
            <div class="align-middle lg:inline">
              <h6 class="text-[18px] lg:ml-[42px] lg:mt-3">NL859888216B01</h6>
            </div>
          </div>
        </div>
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-4 mb-[32px]">
          <div class="flex justify-between lg:inline">
            <div class="flex">
              <div class="w-6 mr-4">
                <img src="./components/icons/loc.svg" width="20px" alt="">
              </div>
              <h5 class="text-[#006FEB] font-semibold text-[16px]">ONS ADRES</h5>
            </div>
            <div class="align-middle lg:inline">
              <h6 class="text-[18px] lg:ml-[42px] lg:mt-3">Bisonspoor 332, <br> 3605JT, Maarssen</h6>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <section class="h-max mx-[16px] lg:mx-[100px] mb-[10px] lg:my-[60px] bg-map">
  </section>

  <main>
    <TheWelcome />
  </main>
</template>
<script>
</script>
<style scoped>
header {
  background-image: url('./components/imgs/blur_bg.png');
  background-size: cover;
  background-position: center center;
}

.bg-map {
  background-image: url('./components/imgs/maps.png');
  background-size: cover;
  background-position: center center;
  height: 250px;
  border-radius: 10px;
}
</style>
