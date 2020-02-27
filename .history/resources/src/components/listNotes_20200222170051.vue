<template>
    <div class="listNotes">
        <ul>
            <li v-for:notes="row in notes">
                {{ row.title }}
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    name: 'listNotes',
    data: function () {
        return {
            notes : [
                { title : 'happy' ,
                  description : 'Ini isi notes' }
            ]
        }
    }
}
</script>

<style lang="">
    
</style>