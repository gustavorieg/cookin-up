<script lang="ts">
    export default {
        props: {
            categoria: { type: Object as PropType<ICategoria>, required: true}
        },
    }
</script>

<template>
    {{ categoria.nome  }}
    {{ categoria.imagem }}
</template>