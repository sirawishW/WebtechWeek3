<template>
    <div>
        <pokemon-table></pokemon-table>
        <pokemon-create-form></pokemon-create-form>
    </div>
</template>

<script>
import PokemonCreateForm from '@/components/PokemonCreateForm'
import PokemonTable from '@/components/PokemonTable.vue'
export default {
    components: {
        PokemonCreateForm,
        PokemonTable
    },
}
</script>

<style>

</style>