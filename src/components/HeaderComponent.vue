<template>

<div class="section">
    
    <div class="header">
        <img src="../assets/logo.png" alt="logo" class="logo">
        <div class="heading">
            <span>FIRE.NET.PK</span>
            <span>SERVICES</span>
        </div>
    </div>

    <div class="description">
        <h1>Get Your High Speed Internet Connection</h1>
        <div class="btn">Learn More</div>
    </div>

</div>

</template>

<script>
</script>

<style scoped>
.section {
    background-image: url("../assets/bg_header.png");
    background-attachment: fixed;
    background-size: cover;
    width: 100%;
    min-height: 100vh;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}

.header {
    padding: 0px;
    display: flex;
    align-items: center;
}
.header .logo {
    width: 100px;
}
.header .heading {
    display: flex;
    flex-direction: column;
    /* align-items: center; */
    font-weight: bolder;
    font-size: 20px;
}
.header .heading span:last-child {
    opacity: 0.5;
}


.description {
    font-size: 40px;
    width: 50%;
    padding: 24px;
    margin: 14px 0px;
}
.description .btn {
    font-size: 16px;
    margin: 14px 0px;
    padding: 10px 16px;
    background-color: rgba(100, 100, 100, 0.5);
    width: 100px;
    text-align: center;
    border-radius: 8px;
}


@media screen and (max-width: 800px) {
    .description {
        padding: 10px;
        text-align: center;
        font-size: 32px;
        width: 90%;
        display: flex;
        flex-direction: column;
        align-items: center;
    }
}
</style>