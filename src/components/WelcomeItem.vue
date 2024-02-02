<template>
  <div class="mt-8 flex relative">
    <i class="flex place-items-center place-content-center w-[50px] h-[50px] border rounded-md">
      <slot name="icon"></slot>
    </i>
    <div class="flex-1 ml-12">
      <h3 class="text-xl">
        <slot name="heading"></slot>
      </h3>
      <slot></slot>
    </div>
  </div>
</template>
