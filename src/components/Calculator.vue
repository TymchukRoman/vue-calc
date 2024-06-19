<template>
    <div class="calculator-root">
        <input />
        <div class="controls-container">
            <div class="number-buttons">
                <button>7</button>
                <button>8</button>
                <button>9</button>

                <button>4</button>
                <button>5</button>
                <button>6</button>

                <button>1</button>
                <button>2</button>
                <button>3</button>

                <button>0</button>
            </div>

            <div class="action-buttons">
                <button>+</button>
                <button>-</button>
                <button>*</button>
                <button>/</button>
                <button>=</button>
            </div>
        </div>
    </div>
</template>

<style scoped>
.calculator-root {
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
    gap: 30px;
    justify-content: center;
    align-items: center;
}

.controls-container {
    display: flex;
    gap: 30px;
}

.number-buttons {
    display: flex;
    gap: 10px;
    width: 230px;
    flex-wrap: wrap;
    justify-content: center;
}

.action-buttons {
    display: flex;
    gap: 10px;
    width: 150px;
    flex-wrap: wrap;
    align-self: start;
}

input {
    width: 400px;
    height: 40px;
}

button {
    width: 70px;
    height: 70px;
}
</style>
