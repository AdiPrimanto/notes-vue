<template>
    <div class="listNotes">
        <ul>
            <li v-for="row in notes">
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
ul {
     list-style-type: none;
     padding: 0;
     margin:0px;
}
.btn-note {
     text-align: left;
     border: none;
     border-bottom: 1px solid gainsboro;
     padding: 0px 15px;
     cursor: pointer;
     outline: none;
     background: #f7f7f7;
     height: 150px;
     width: 100%;
}
.btn-note:hover {
     background:#eaeaea;
}
.btn-note label{
     display:block;
     color: #444444;
     font-size: 1.5em;
     margin-bottom: 15px;
}
.btn-note span{
    color: #545454;
}
</style>