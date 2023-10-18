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
    animation: typing 2s steps(30) forwards, blink 1s infinite;

  }

@keyframes typing {
  from { width: 0 }
  to { width: 100% }
}

@keyframes blink {
  0%, 45% {
    border-color: transparent;
  }
  50%, 100% {
    border-color: white;
  }
}

@media (min-width: 1024px) {}
</style>
