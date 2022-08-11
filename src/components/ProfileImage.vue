<template>
    <img :src="profileImage" alt="profile-image" className="profile">
  
</template>

<script>
export default {
    name: "ProfileImage",
    props: {
        profileImage: String,
    }
}
</script>

<style>

</style>