<template>
  <GirlA image="a" direction="left" class="mb-3">
    <strong> 7. Responsável: </strong> neste item contém o registro da pessoa
    física que, direta ou indiretamente, foi a responsável pela ação ou omissão
    que deu origem à constatação de não conformidade. Geralmente, é indicado
    quando consta Proposição de Devolução no Relatório.
    <template v-slot:extra>
      <img class="img-fluid" src="@/assets/pages/7_responsavel.png" alt="" />
    </template>
  </GirlA>
  <GirlA image="c" direction="right">
    E aqui terminamos a elaboração do Relatório Preliminar. A fim de contribuir
    para a qualidade e eficiência da auditoria, o relatório é encaminhado para
    Ana, nossa supervisora técnica, e para um setor específico do Denasus, que
    realiza uma revisão minuciosa. Após este procedimento, o Relatório
    Preliminar será encaminhado para o gestor na Secretaria Municipal de Saúde
    de Feliz Passeio.
  </GirlA>
</template>

<script setup>
import GirlA from "@/components/GirlA.vue";
</script>
