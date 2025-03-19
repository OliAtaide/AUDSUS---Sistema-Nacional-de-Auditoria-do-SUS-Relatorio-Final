<template>
  <GirlA image="c" direction="right">
    <strong> 4. Recomendação: </strong>
    neste item estão descritas as providências pertinentes para superar ou
    minimizar a constatação de não conformidade, contemplando a fundamentação
    legal. O propósito das recomendações é a melhoria do objeto auditado.
    <template v-slot:extra>
      <img class="img-fluid" src="@/assets/pages/4.png" alt="" />
    </template>
  </GirlA>
</template>

<script setup>
import GirlA from "@/components/GirlA.vue";
</script>
