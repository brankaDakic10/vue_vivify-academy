<template>
<div>
<h1>Contact List</h1>
<ul class="list-group">
    <li class="list-group-item"
     v-for="(contact ,key) in contacts" 
     :key="key">{{contact.name}}</li>


</ul>
</div>
</template>

<script>
export default {
 props:['contacts']
}
</script>