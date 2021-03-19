<template>
    <div class="main">
        <div class="calc-container">
            <div class="calc-results">
                <span class="result">0</span>
            </div>
            <div class="calc-buttons">
                <div class="num-buttons">
                    <span class="num-btn">7</span>
                    <span class="num-btn">8</span>
                    <span class="num-btn">9</span>
                    <span class="num-btn gray">/</span>
                </div>

                <div class="num-buttons">
                    <span class="num-btn">4</span>
                    <span class="num-btn">5</span>
                    <span class="num-btn">6</span>
                    <span class="num-btn gray">X</span>
                </div>

                <div class="num-buttons">
                    <span class="num-btn">1</span>
                    <span class="num-btn">2</span>
                    <span class="num-btn">3</span>
                    <span class="num-btn gray">-</span>
                </div>

                <div class="num-buttons">
                    <span class="num-btn zero">0</span>
                    <span class="num-btn gray">=</span>
                    <span class="num-btn gray">+</span>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Calc'
}
</script>

<style>
@import '../assets/css/app.css';
</style>