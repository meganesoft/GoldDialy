<template>
    <button>{{ name }}</button>
</template>

<script lang="ts">
import { Component,Vue} from 'nuxt-property-decorator';

@Component
export default class  PageButton extends Vue {
    name = 'PageButton'

}
</script>
