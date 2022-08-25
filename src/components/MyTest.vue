<template>
    <div>
        <h1>My test</h1>
        <h2>{{ myName}}</h2>
    </div>
</template>

<script>
export default {
    name: "MyTest",
    data(){
        return {
            myName: 'My name is Orlando'
        }
    }
}
</script>