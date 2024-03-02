<template>
    <div class="section">
        <div class="header">
            <h1>Pricing Plans</h1>
            <p>With affordable and flexible plans, you can Seiz however you like or need.</p>
        </div>
        <div class="packages">
            <div class="package">
                <h1 class="package-title">Basic</h1>
                <br>
                <ul>
                    <li>One Linked Account</li>
                    <li>Basic Functionality</li>
                </ul>
                <br><br>
                <span class="price">
                    800pkr @ month
                </span>
            </div>
            <div class="package">
                <h1 class="package-title">Pro</h1>
                <br>
                <ul>
                    <li>One Linked Account</li>
                    <li>Basic Functionality</li>
                </ul>
                <br><br>
                <span class="price">
                    800pkr @ month
                </span>
            </div>
            <div class="package">
                <h1 class="package-title">Pro Plus</h1>
                <br>
                <ul>
                    <li>One Linked Account</li>
                    <li>Basic Functionality</li>
                </ul>
                <br><br>
                <span class="price">
                    800pkr @ month
                </span>
            </div>
        </div>
    </div>
</template>

<style scoped>

.section {
    min-height: 100vh;
    width: 100%;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    background-image: url("../assets/bg_pricing.png");
    background-attachment: fixed;
}

.header {
    background-color: #f2a084;
    height: 30vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
}


.packages {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    flex-wrap: wrap;
    min-height: 70vh;
}
.packages .package {
    margin: 24px 0px;
}
.packages .package .package-title {
    color: gold;
}
.packages .package ul {
    margin-left: 20px;
    color: #fff;
}
.packages .package .price {
    background-color: #c3c3c3;
    padding: 8px 12px;
    border-radius: 4px;
}

@media screen and (max-width: 800px) {
    .packages {
        justify-content: center;
        width: 100%;
    }
    .packages .package {
        width: 90%;
        display: flex;
        flex-direction: column;
        align-items: center;
    }
}
</style>