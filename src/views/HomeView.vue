<template>
  <div class="card card-main">
    <div class="card-body">
      <div class="home">
        <GirlA class="mb-4" image="b" direction="right">
          Olá, cursista! Para nos auxiliar na estruturação dos achados da
          auditoria, na redação do Relatório Preliminar e na revisão do
          trabalho, por parte da supervisão técnica, nós elaboramos a
          <strong>Matriz de Achados</strong>. Clique no botão abaixo para
          visualizar o formato da tabela.
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