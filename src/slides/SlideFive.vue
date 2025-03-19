<template>
  <GirlA image="b" direction="right">
    <strong> 5. Destinatário da recomendação: </strong>
    item que contém o registro da pessoa jurídica que tem a atribuição de
    cumprir a legislação e sanar a impropriedade ou irregularidade.
    <template v-slot:extra>
      <img class="img-fluid" src="@/assets/pages/5-1.png" alt="" />
    </template>
  </GirlA>
  <div class="my-5"></div>
  <GirlA image="b" direction="left">
    Sobre este item é importante salientar que, na situação em que a equipe de
    auditoria imputar a responsabilidade de devolução de recursos públicos, irá
    detalhar, no item do relatório denominado
    <strong>Proposição de Devolução</strong>, os atos ilegais, ilegítimos ou
    antieconômicos; a identificação dos responsáveis pelo ressarcimento; e a
    quantificação do débito relativo a cada um dos responsáveis.
    <template v-slot:extra>
      <img class="img-fluid" src="@/assets/pages/5-2.png" alt="" />
    </template>
  </GirlA>
</template>

<script setup>
import GirlA from "@/components/GirlA.vue";
</script>
