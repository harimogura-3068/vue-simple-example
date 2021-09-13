<template>
  <div class="about">
    <h1>This is an test page!!</h1>
    <TestComponent msg="Welcome to TestComponent" />
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import TestComponent from "@/components/TestComponent.vue";

@Options({
  components: {
    TestComponent,
  },
})
export default class Test extends Vue {}
</script>
