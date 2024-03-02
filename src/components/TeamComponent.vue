<template>
    <div class="section">
        <h1 class="title">Our Team</h1>
        <div class="team-cards">
            <div class="card">
                <img src="https://placehold.co/100x100" alt="image">
                <h2>Name</h2>
                <p>Startup Founder</p>
            </div>
            <div class="card">
                <img src="https://placehold.co/100x100" alt="image">
                <h2>Name</h2>
                <p>Startup Founder</p>
            </div>
            <div class="card">
                <img src="https://placehold.co/100x100" alt="image">
                <h2>Name</h2>
                <p>Startup Founder</p>
            </div>
        </div>
    </div>
</template>


<style scoped>

.section {
    min-height: 100vh;
    width: 100%;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-evenly;
}

.section .team-cards {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    flex-wrap: wrap;
}

.section .team-cards .card {
    display: flex;
    flex-direction: column;
    padding: 20px;
    border-radius: 4px;
    background-color: #f2a084;
    max-height: 100px !important;
    width: 200px;
    margin: 24px 32px;
}
.section .team-cards .card img {
    width: 100px;
    aspect-ratio: 1;
    border-radius: 50%;
    margin-top: -80px;
    margin-left: 25%;
}

@media screen and (max-width: 800px) {
    .section .team-cards .card {
        margin: 46px 0;
    }
}

</style>