<template>
    <header class="flex justify-between border-b border-slate-300 px-8">
      <div class="flex items-center">
        <img src="/logo.png" class="m-10 gap-4">
        <div>
          <h2 class="text-xl">
            ClockStyle
          </h2>
        </div>
      </div>

      <ul class="flex items-center gap-8">
        <li class="flex items-center gap-3 cursor-pointer hover:text-orange-500">
          <img src="/cart.svg" alt="">
          <b>Корзина</b>
        </li>

        <li class="flex items-center gap-3 cursor-pointer hover:text-orange-500">
          <img src="/heart.svg" alt="">
          <b>Закладки</b>
        </li>
        <li class="flex items-center gap-3 cursor-pointer hover:text-orange-500">
          <img src="/profile.svg" alt="">
          <b>Профиль</b>
        </li>
      </ul>
    </header>
</template>