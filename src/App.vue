<script>
export default {
    data() {
        return {
            number:"XX.XX.XXXX"
        }
    }
}
</script>

<template>
<body class="profile">
    <div class="information">
        <div class="exit">
            <div>
                <p class="data" id="code">{{ number }}</p>
                <p class="data" id="code">XX:XX</p>
            </div>
            <button class="btex">Выход <img class="imgex" src="/src/assets/logout.png" alt=""></button>
        </div>
        <div class="blswitch">
            <label class="switch">
                    <input type="checkbox" class="switch__input" id="theme-button">
                    <span class="switch__slider"></span>
            </label>
        </div>
        <div class="name">
            <span class="fio">Фамилия Имя Отчество</span>
            <p class="data" id="number">{{ number }}</p>
            <p class="data">Tаб №: ГОКИ 0000</p>
            <P class="data">Проходчик IV разряда</P>
        </div>
        <div class="indication">
            <div class="circles">
                <h3>Инструктаж</h3>
                <div class="otmetka">
                    <div class="kryg" style="--p:100;"></div>
                    <img src="/src/assets/search.png" alt="">
                </div>
            </div>
            <div class="circles">
                <h3>Предсменный экзаменатор</h3>
                <div class="otmetka">
                    <div class="kryg" style="--p:100;"></div>
                    <img src="/src/assets/test.png" alt="">
                </div>
            </div>
            <div class="circles">
                <h3>Тестов выполнено</h3>
                <div class="otmetka">
                    <div class="kryg" style="--p:25;"></div>
                    <p class="chislo" id="testov">12</p>
                </div>
            </div>
            <div class="circles">
                <h3>Аттестация через</h3>
                <div class="otmetka">
                    <div class="kryg" id="atest" style="--p:15;"></div>
                    <p class="chislo" id="dney">3<br>дня</p>
                </div>
            </div>
        </div>
    </div>
    <div class="navigation">
        <div class="logossilka"><a href="https://www.pfsz.ru/" target="_blank"><img class="logo" src="/src/assets/logo.jpg" alt=""></a></div>
        <div class="blocbtn">
            <div class="topbtn">
                <button class="btn" id="job">
                    <p>Начать работу</p>
                    <img fill="#ffffff" src="/src/assets/jackhammer.png" alt="">
                </button>
                <button class="btn" id="mail">
                    <div id="notification" v-show="value !=0" value={{message}}></div>
                    <p>Уведомления</p>
                    <img src="/src/assets/email.png" alt="" id="mailimg">
                </button>
            </div>
            <div class="botbtn">   
                <button class="btn" id="course">
                    <p>Обучение</p>
                    <img src="/src/assets/book.png" alt="">
                </button>
                <button class="btn" id="achiev">
                    <p>Достижения</p>
                    <img src="/src/assets/achiv.png" alt="">
                </button>
            </div>    
        </div>

    </div>
</body>
</template>

<style scoped>

</style>
