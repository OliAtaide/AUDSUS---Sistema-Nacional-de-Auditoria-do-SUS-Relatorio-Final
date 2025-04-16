<template>
  <div class="card card-main">
    <div class="card-body">
      <div class="home">
        <GirlA class="mb-4" image="b" direction="right">
          Olá, cursista! Estamos elaborando o Relatório Final. Já analisamos as
          justificativas apresentadas. Vou explicar agora para você os
          principais itens textuais que caracterizam o Relatório Final.
          <br />
          Primeiro, saiba que o Relatório Final contém na íntegra o Relatório
          Preliminar, sendo acrescido dos seguintes itens:
        </GirlA>
      </div>
    </div>
  </div>

  <NavButtons id="0" :prev="false" :next="true"></NavButtons>
</template>

<script setup>
// @ is an alias to /src
import GirlA from "@/components/GirlA.vue";
import NavButtons from "@/components/NavButtons.vue";
</script>
