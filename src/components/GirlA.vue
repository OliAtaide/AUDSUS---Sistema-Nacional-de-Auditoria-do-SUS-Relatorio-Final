<template>
  <div class="container w-75">
    <div class="row" :class="'row-' + props.direction">
      <div class="col-3 d-flex align-items-start">
        <img
          class="img-fluid mx-auto"
          :src="require('@/assets/girl_' + props.image + '.png')"
          alt=""
        />
      </div>
      <div class="col d-flex flex-column gap-4">
        <div
          class="popover bs-popover-auto w-100"
          :class="'popover-' + props.direction"
          role="tooltip"
          :data-popper-placement="props.direction"
        >
          <div class="popover-arrow" style=""></div>
          <div class="popover-body">
            <slot></slot>
          </div>
        </div>

        <slot name="extra"></slot>
      </div>
    </div>
  </div>
</template>

<script setup>
import { defineProps } from "vue";
const props = defineProps(["image", "direction"]);
</script>
