<template>
<nav class="fnav">
    <div class="brand nav-left">
        <img src="@/assets/logo.png" alt="logo" height="20px">
        <span class="title">FriendsMind</span>
    </div>
</nav>
</template>
<script>
export default {
    name: 'fnav',
}
</script>
<style lang="scss">

.fnav{
    position: fixed;
    width: 100%;
    top: 0; left: 0;
    background-color: #f4dd5a;
    display: flex;
    align-items: flex-start;
}
</style>
