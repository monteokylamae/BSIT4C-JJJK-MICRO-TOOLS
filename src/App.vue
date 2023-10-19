<script setup>
import { ref } from 'vue'

const course =ref('')

</script>
<template>

<select v-model="course">
    <option value="BSIT">BSIT</option>
    <option value="BSCS">BSCS</option>
    <option value="BSIS">BSIS</option>
</select>
<p>Course: {{course}} </p>

<p v-if="course== 'BSIT'">
<h1>Bachelor of Science Major in I miss you :3 </h1>
</p>

<p v-else> Relapse ka malala </p>



</template>


