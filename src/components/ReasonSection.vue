<template>
    <div class="section">

        <h1 class="title">
            Time-wasting is an epidemic.<br>
            We're here to cure it.
        </h1>

        <div class="cards">

            <div class="card">
                <img class="icon" :src="checkCircle" alt="">
                <span class="text">
                    Too many apps vyuing<br>
                    your attention.
                </span>
                <span class="ytext">
                    Seize is a one-stop app<br>
                    that has all you ever need.<br>
                    Delete the rest.
                </span>
            </div>
            <div class="card">
                <img class="icon" :src="checkCircle" alt="">
                <span class="text">
                    Schedules all over<br>
                    the place.
                </span>
                <span class="ytext">
                    Using smart technology, Seiz syncs schedules across your messages, email and calendars.
                </span>
            </div>
            <div class="card">
                <img class="icon" :src="checkCircle" alt="">
                <span class="text">
                    Not enough time for things that matter.
                </span>
                <span class="ytext">
                    The TimeBloc feature suggests rest periods and focus times, for better productivity 
                    and balance.
                </span>
            </div>

        </div>

    </div>
</template>


<script>
import checkCircle from '@/assets/check-circle.png';

export default {
    data() {
        return {
            checkCircle: checkCircle
        }
    }
}

</script>

<style scoped>
.section {
    padding: 24px 0px;
    width: 100%;
    min-height: 100vh;
    background-color: #145ba0;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}

.section .icon {
    width: 32px;
}

.section .text {
    color: #fff;
}

.section .ytext {
    color: #fee600;
}

.section .title {
    color: #fee600;
    text-align: center;
    font-size: 30px;
}

.cards {
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 5% 0px;
    flex-wrap: wrap;
}

.cards .card {
    height: 160px;
    margin: 0px 14px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-evenly;
    text-align: center;
    width: 200px;
}
</style>