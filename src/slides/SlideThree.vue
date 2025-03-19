<template>
  <GirlA image="a" direction="left">
    <strong>3. Acatamento da justificativa:</strong> neste item fica o registro
    se as justificativas foram acatadas total ou parcialmente, assim como o
    registro da não apresentação de justificativas. No caso de não acatamento,
    total ou parcial, e de não apresentação de justificativas são emitidas
    recomendações.
    <template v-slot:extra>
      <img class="img-fluid" src="@/assets/pages/3.png" alt="" />
    </template>
  </GirlA>
</template>

<script setup>
import GirlA from "@/components/GirlA.vue";
</script>
