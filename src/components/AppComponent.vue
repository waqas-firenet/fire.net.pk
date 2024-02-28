<template>
    <div class="section">
        <div class="mobile">
            <img :src="mobile" alt="Mobile" class="mobileImage">
        </div>
        <div class="description">
            <h1 class="title">
                Interactive Dashboard
            </h1>
            <div class="about">
                <span>User Friendly App</span>
                <ul>
                    <li>You can generate ticket.</li>
                    <li>You can change package request.</li>
                    <li>You can check your bill history.</li>
                    <li>You can check your current status anywhere.</li>
                </ul>
            </div>
            <button class="btn">
                Download Now
            </button>
        </div>
    </div>
</template>

<script>
import Mobile from '@/assets/mobile.png';
export default {
    data() {return {mobile: Mobile}}
}
</script>

<style scoped>

.section {
    background-color: #f2a084;
    min-height: 100vh;
    padding: 24px 0px;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}
.section .mobile {
    width: 30%;
}
.section .mobile .mobileImage {
    width: 70%;
}
.section .description {
    width: 70%;
    height: 60vh;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
.section .description .title {
    font-size: 52px;
    letter-spacing: 4px;
    text-decoration: underline;
    text-underline-offset: 8px;
}
.section .description .btn {
    padding: 8px 12px;
    border-radius: 8px;
    background-color: #c3c3c3;
    color: #000;
    width: 160px;
    border: none;
    font-weight: bolder;
    font-size: 18px;
} 

@media screen and (max-width: 800px) {
    .section {
        flex-direction: column;
    }
    .section .mobile,
    .section .description {
        width: 100%;
        display: flex;
        justify-content: center;
    }
    .section .description {
        align-items: center;
        justify-content: space-between;
        text-align: center;
        padding: 14px 24px;
    }
    .section .description .about {
        text-align: left;
    }
    
}

</style>