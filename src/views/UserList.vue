<template>
    <div class="row">
    </div>
</template>

<script>
    import { db } from '../firebase';
    
    export default {
        data() {
            return {
                Users: []
            }
        },
        created() {
            
            console.log(db.firestore().collection('users'))
        },
        methods: {

        }
    }
</script>

<style>
    .btn-primary {
        margin-right: 12px;
    }
</style>