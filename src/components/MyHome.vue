<template>
    <div>
        <h1>Home</h1>
        <h2>{{ myName}}</h2>
    </div>
</template>

<script>
export default {
    name: 'MyHome',
    data(){
        return {
            myName: 'My name is Orlando'
        }
    }
}
</script>