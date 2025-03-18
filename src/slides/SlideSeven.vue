<template>
  <GirlA image="a" direction="left" class="mb-3">
    <strong> 7. Responsável: </strong> neste item contém o registro da pessoa
    física que, direta ou indiretamente, foi a responsável pela ação ou omissão
    que deu origem à constatação de não conformidade. Geralmente, é indicado
    quando consta Proposição de Devolução no Relatório.
    <template v-slot:extra>
      <img class="img-fluid" src="@/assets/pages/7.png" alt="" />
    </template>
  </GirlA>
</template>

<script setup>
import GirlA from "@/components/GirlA.vue";
</script>
