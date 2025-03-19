<template>
  <GirlA image="b" direction="left">
    <strong>1. Justificativa apresentada:</strong> item que contém a transcrição
    da manifestação do auditado em função das constatações de não conformidades.
    Nos casos em que o texto for muito grande, ou contiver documentos anexos, a
    equipe faz uma síntese objetiva dos argumentos ou novos fatos, bem como
    coloca o texto original como anexo, referenciando no corpo da justificativa.
    <template v-slot:extra>
      <img class="img-fluid" src="@/assets/pages/1.png" alt="" />
    </template>
  </GirlA>
</template>

<script setup>
import GirlA from "@/components/GirlA.vue";
</script>
