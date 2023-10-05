<script setup lang="ts">
</script>

<template>
  <div class="container mx-auto p-2">
    <!-- Phần đầu -->
    <div class="bg-[#EDEDED] h-[750px] rounded-2xl">
      <div class="flex justify-center">
        <!-- Text -->
        <div class="flex flex-col text-[24px]">
          <label class="mt-[60px] text-[24px] me-2 flex justify-end font-medium	">テンプレート選択</label>
          <label class="mt-[45px] text-[24px] me-2 flex justify-end">送付先</label>
          <label class="mt-[47px] text-[24px] me-2 flex justify-end font-medium	">タイトル</label>
          <label class="mt-[30px] mb-[308px] me-2 text-[24px] flex justify-end">本文</label>
          <label class="me-2 flex justify-end font-medium	">添付ファイル</label>
        </div>
        <!-- Thẻ input -->
        <div class="my-7 w-[910px]">
          <!-- Hàng 1 -->
          <div class="my-7">

        <input type="text" class="text-center placeholder-centerh h-[50px] w-[909px] p-2 border border-black text-[30px] placeholder-black" placeholder="---------------------------------">
          </div>
          <!-- Hàng 2 -->
          <div class="my-7">
            <textarea class="w-[908px] h-[50px] overflow-y-scroll	border border-black p-2 text-[30px] placeholder-black text-center placeholder-center" placeholder="○○○○○○○＠○○○○.com"></textarea>
          </div>
          <!-- Hàng 3 -->
          <div class="my-7">

            <input type="text" class="text-center placeholder-center h-[50px] w-[909px] p-2 border border-black text-[30px] placeholder-black" placeholder="○○○○">
          </div>
          <!-- Hàng 4 -->
          <div class="my-7">

            <textarea class="h-[298px] w-[908px] overflow-y-scroll border border-black p-2"></textarea>
          </div>
          <!-- Hàng 5 -->
          <div class="my-7">

            <textarea class="w-[908px] h-[50px] overflow-y-scroll	border border-black p-2 text-[35px] placeholder-[#17ace3] text-center placeholder-center" placeholder="---------------.pdf"></textarea>

          </div>
        </div>
      </div>
      <!-- Phần thân -->
    </div>

    <!-- Nút -->
    <div class="flex justify-center space-x-[150px] my-[50px] w-[1248px]">
      <button class="w-[236px] h-[50px] bg-[#9ee2f8] text-[24px] border border-black">送信</button>
      <button class="w-[236px] h-[50px] bg-[#f89ec4] text-[24px] border border-black">戻る</button>
    </div>

  </div>
</template>

<style scoped></style>
