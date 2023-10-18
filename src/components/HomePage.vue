<template>
<p class="typingEffect">
maria foster
</p>
</template>
<style scoped>
/*https://coderpad.io/blog/development/how-to-create-a-typewriter-effect-in-vue/*/
.typingEffect {
    width: 0;
    overflow: hidden; /* Ensure the text is not visible until the typewriter effect*/
    border-right: 2px solid white; /* The cursor*/
    font-size: 16px;
    white-space: nowrap; /* Keeps the text on a single line */
    animation: typing 2s forwards;
  }

  @keyframes typing {
  from { width: 0 }
  to { width: 100% }
}

@media (min-width: 1024px) {}
</style>
