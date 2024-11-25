<script>

</script>

<template>
  <header>
    <nav class="flex items-center justify-center gap-2 px-24 py-2 mb-4 text-#D8A034 text-16px duration-1000 hover:text-gray-400">
      <img src="../assets/img/couponLogo_1.png" class="h-16" alt="">
      <h1 class="font-bold">#心心</h1>
    </nav>
    <picture class="pos-relative h-144 w-full">
      <div class="pos-absolute top-48 left-36 flex flex-col gap-0">
        <h2 class="bg-gray-400 p-4 text-white m-0">#一份窩心的早餐</h2>
        <p class="bg-#D8A034 text-3xl pl-4 pr-32 py-4 text-white font-bold m-0 inline-block">你一訂喜歡</p>
      </div>
      <img src="../assets//img/qrcode.png" class="qr-code pos-absolute top-36 right-36 w-80 rounded-3xl" alt="">
      <img src="../assets/img/banner.jpeg" class="w-full h-144 rounded-3xl object-cover block" alt="">
    </picture>
  </header>
</template>
<style>
.qr-code{
    right:0;
    animation-name:qr;
    animation-duration:2s;
}
@keyframes qr{
    from{
        right:0;
        opacity: 0;
    }
    to{
        right:144px;
        opacity: 1;
    }
}
</style>