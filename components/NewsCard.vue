<template>
  <div class="border border-solid rounded-xl border-gray-300 font-arial w-full">
    <div
      class="h-36 w-full bg-center bg-cover rounded-t-xl"
      :style="`background-image: url(${base64Image})`"
    ></div>
    <div class="flex flex-col p-4">
      <img
        src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEIAAAAQCAMAAACVzFkmAAAAkFBMVEX///8AAADqAADvVF/rAB7ydn3sDSXwX2nxbXX8/PwKAADsGy73sLT//P2qqamZmJgxLS71mZ7r6ur1nqT+9PXwZG3vSFX2qK3ycXr0iZDb29uwr6/z8/O6ubrPzs784uTzgIgmIiOHhoZEQUL6y87tJjiAfn/Ew8T5xMdzcXJraWkaFRdLSUmQjo9hX2BSUFEWoqXGAAABaklEQVQ4ja1TDY+bMAx9piVHKE34OLqRBFpggyMp5f//uwuVuumknibRWUpkP8XPz4kD3K1iLMMrdjwnRZGcj5sJ3ncRyv0+xKncSrILwipgLCi8s43h+Bb9+BmFYVRlUfkAldZGjaPybiM0b0TNhcw9LqWC0DXqkQvRcC2FR8+oLkhOuw+UmQ/u1tEwNUNrqYalzqqa4jSlFJoGS2NPHcihJ51eZ5pRJWUQJmsjv3ZBlRV3DbSWHybc5pHyFVlioI9BN4CsorohysWSkwA3YMWeXU6Hw4GVb2yf/V4ThLtLcWmLbsEfCmfIEXkxNMku1ouAD6/5cwpa98EaO8v+C8UEwzls2ip7XfWNMu6fNpKTBF8bGRZFGpzzPua+d1ypMcOMmlp/LSlUn+fx7fl1Ni3R2HnNCrWLSUnXTtI5aazHRl+i82uG8sdu5ptHhTF/Xf7PwfATdXlttP7HgD++2ft2gpXjwg7F1uRPmI4hBfA0aVUAAAAASUVORK5CYII="
        class="mb-2"
        height="16"
        width="66"
        alt="CBC.ca"
      />
      <p class="text-blue-800 mb-5 break-words">{{ newsText }}</p>
      <div class="text-xs text-gray-600 mt-auto">1 hour ago</div>
    </div>
  </div>
</template>

<script>
export default {
    props: ['newsText', 'base64Image']
};
</script>

<style></style>
