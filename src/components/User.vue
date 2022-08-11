<template>
<span className="user">
  <span className="name">{{user.name}}</span>
  <span classNane="handle">{{user.handle}}</span>
</span>
  
</template>

<script>
export default {
    name: "User",
    props: {
        user: Object,
    },
};
</script>

<style>

</style>