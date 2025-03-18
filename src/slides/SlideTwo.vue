<template>
  <GirlA image="a" direction="right">
    <strong> 2. Introdução: </strong> neste item estão registrados a visão geral
    do objeto auditado, contemplando a finalidade e o escopo da atividade de
    auditoria; informações sobre a demanda e o demandante; o objetivo da
    atividade e as questões de auditoria formuladas.
    <template v-slot:extra>
      <img class="img-fluid" src="@/assets/pages/2.png" alt="" />
    </template>
  </GirlA>
</template>

<script setup>
import GirlA from "@/components/GirlA.vue";
</script>
