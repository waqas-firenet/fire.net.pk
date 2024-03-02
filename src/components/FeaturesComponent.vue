<template>

    <div class="section">
        <div class="section-title">
            <h1>Product Features</h1>
        </div>
        <div class="features-wrapper">
            <div class="features">
                <div class="feature">
                    <img src="https://placehold.co/200x200" alt="none" class="feature-image">
                    <span class="description">Smart Watch Compatibility</span>
                </div>
                <div class="feature">
                    <img src="https://placehold.co/200x200" alt="none" class="feature-image">
                    <span class="description">Smart Watch Compatibility</span>
                </div>
                <div class="feature">
                    <img src="https://placehold.co/200x200" alt="none" class="feature-image">
                    <span class="description">Smart Watch Compatibility</span>
                </div>
            </div>
            <div class="features">
                <div class="feature">
                    <img src="https://placehold.co/200x200" alt="none" class="feature-image">
                    <span class="description">Smart Watch Compatibility</span>
                </div>
                <div class="feature">
                    <img src="https://placehold.co/200x200" alt="none" class="feature-image">
                    <span class="description">Smart Watch Compatibility</span>
                </div>
                <div class="feature">
                    <img src="https://placehold.co/200x200" alt="none" class="feature-image">
                    <span class="description">Smart Watch Compatibility</span>
                </div>
            </div>
        </div>
    </div>

</template>

<style scoped>

.section {
    min-height: 100vh;
    width: 100%;
    padding: 30px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    background-image: url("../assets/bg_features.png");
    background-attachment: fixed;
    background-size: cover;
}
.section-title {
    margin: 24px 0px;
    font-size: 30px;
}
.features-wrapper {
    display: flex;
    justify-content: space-between;
    width: 90%;
    flex-wrap: wrap;
}

.features-wrapper .features {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}
.features-wrapper .features .feature {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 19px 0px;
}
.features-wrapper .features .feature img {
    width: 100px;
    height: 100px;
    aspect-ratio: 1;
    border-radius: 50%;
    border: 1px solid rgb(96, 165, 250);
}
.features-wrapper .features .feature span {
    margin-left: 24px;
    width: 100px;
}
</style>