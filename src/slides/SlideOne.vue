<template>
  <GirlA image="a" direction="left">
    <strong> 1. Dados básicos: </strong> neste item estão registrados a finalidade da ação
    de auditoria; o período que ocorreu cada fase da auditoria; quais foram as
    unidades visitadas; o demandante da ação; o objeto e abrangência da
    auditoria; e identificações dos dirigentes, com seu respectivo cargo e
    período de exercício.
    <template v-slot:extra>
        <img  class="img-fluid" src="@/assets/pages/1.png" alt="">
    </template>
  </GirlA>
</template>

<script setup>
import GirlA from "@/components/GirlA.vue";
</script>
