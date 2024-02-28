<template>
    <div class="section">
        <div class="image-section">
            <img :src="ContactImage" alt="Contact">
        </div>
        <div class="content-section">
            <h1 class="title">
                Get In Touch
            </h1>
            <p class="address">
                Qazal bash road Main bazar bib pakdaman<br>
                042-36292609<br>
                042-36292610<br>
            </p>
            <p class="links">
                admin@fire.net.pk<br>
                https://fire.net.pk<br>
                https://billing.fire.net.pk
            </p>
            <div class="social">
                <img :src="socialImages">
            </div>
        </div>
    </div>
</template>


<script>
import ContactImage from '@/assets/footer.png';
import socialImages from '@/assets/social.png';
export default {
    data() { return { ContactImage, socialImages } }
}
</script>


<style scoped>
.section {
    background-color: #f2a084;
    min-height: 100vh;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    display: flex;
    justify-content: space-between;
}

.section .image-section {
    width: 30%;
}

.section .image-section img {
    width: 100%;
    height: 100vh;
}

.section .content-section {
    width: 60%;
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    /* align-items: center; */
    padding: 24px 30px;
    text-align: left;
}

.section .content-section .title {
    font-size: 62px;
}
.section .content-section .social img {
    width: 100px;
}


@media screen and (max-width: 768px) {
    .section {
        flex-direction: column;
    }
    .section .image-section {
        width: 100%;
    }
    .section .image-section img {
        height: auto;
    }
    .section .content-section {
        padding: 24px;
        width: 80%;
        height: 75vh;
    }
}

</style>