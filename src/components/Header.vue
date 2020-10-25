<template>
    <div>
        <b-nav class="header-style" tabs>
            <b-nav-item disabled><b>Vue Quiz App</b></b-nav-item>
            <b-nav-item disabled>Correct Answers : {{numCorrect}} Total Questions :10 / {{numTotal}}</b-nav-item>
        </b-nav>
    </div>
</template>

<script>
    export default{
        props:[
            'numCorrect',
            'numTotal'
        ]
    }
</script>
