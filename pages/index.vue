<template>
    <div>
        <MenuNav/>
        <UContainer>
            <UTable :columns="columns" :rows="repas" />
        </UContainer>
        
    </div>
</template>

<script setup lang="ts">

const repas = [{
    day: 'Lundi',
    midi: 'Repas 1 ',
    soir: 'Repas 2 '
},{
    day: 'Mardi',
    midi: 'Repas 1 ',
    soir: 'Repas 2 '
},{
    day: 'Mercredi',
    midi: 'Repas 1 ',
    soir: 'Repas 2 '
},{
    day: 'Jeudi',
    midi: 'Repas 1 ',
    soir: 'Repas 2 '
},{
    day: 'Vendredi',
    midi: 'Repas 1 ',
    soir: 'Repas 2 '
},{
    day: 'Samedi',
    midi: 'Repas 1 ',
    soir: 'Repas 2 '
},{
    day: 'Dimanche',
    midi: 'Repas 1 ',
    soir: ' '
}]

const columns = [{
  key: 'day',
  label: 'Jours '
}, {
  key: 'midi',
  label: 'Midi'
  }, {
  key: 'soir',
  label: 'Soir'
}]

//const selectedColumns = ref([...columns])





</script>

<style scoped>

</style>