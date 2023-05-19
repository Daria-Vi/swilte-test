<svelte:head>
    <title>Сайт ЧДВ</title>
</svelte:head>

<div class="container">
    <div class="info">
        <div class="animate-background">
            <div class="container info-container">
                <div class="info-text">
                    <h1>
                        <p class="animate-text-1">Добро пожаловать на персональный сайт преподавателя</p>
                        <p class="text-2">Чипиштановой Дарьи Викторовны</p>
                    </h1>
                </div>
                <h2 class="subtitle">
                    <p>Посетив страницы сайта, Вы узнаете немного обо мне, </p>
                    <p>познакомитесь с результатами моей педагогической деятельности, </p>
                    <p>с актуальной информацией о рабочих моментах, </p>
                    <p>а также посмотрите, как со мной можно связаться. </p>
                </h2>
                <div style="color:black" class="scroll-button animate-scroll" tabindex="0">
                    <a href="/about">Начнём...</a>
                    <div class="arrow">→</div>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="background-div" />

<style>
    .info {
        text-align: center;
        position: relative;
    }
    .info-container {
        height: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        text-align: left;
        align-items: start;
    }
    .container {
        max-width: 1400px;
        margin: 190px 0 0 2.5rem;
    }
    .info h1 {
        font-size: 4rem;
        margin: 0;
    }
    .info h1 p {
        position: relative;
        font: inherit;
        margin: 0;
        text-align: left;
        line-height: 130%;
        width: fit-content;
        font-weight: 800;
        letter-spacing: -0.03em;
    }
    .info h2 {
        max-width: 65ch;
        font-weight: 200;
        margin-top: 0.5rem;
    }
    .background-div {
        background-color: #f8d196;
        width: 100%;
        height: 56vh;
        margin: -295px auto;
    }
    .info .info-text {
        position: relative;
    }
    .scroll-button {
        display: flex;
        border: none;
        outline: none;
        cursor: pointer;
    }
    .scroll-button .arrow {
        margin-left: 0.5rem;
    }
</style>
