<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header"><h1>Дневник погоды</h1></div>

                    <div class="card-body">
                        <table>
                            <tbody><tr>
                                <th  rowspan="2">Число</th>
                                <th  colspan="5"><label>День</label></th>
                                <th  colspan="5"><label>Вечер</label></th>
                            </tr>
                            <tr>
                                <th>Температура</th>
                                <th>Давление</th>
                                <th>Облачность</th>
                                <th>Явления</th>
                                <th>Ветер</th>
                                <th>Температура</th>
                                <th>Давление</th>
                                <th>Облачность</th>
                                <th>Явления</th>
                                <th>Ветер</th>
                            </tr>
                            </tbody><tbody>
                        <tr>
                            <td>1</td>
                            <td>+15</td>
                            <td>743</td>
                            <td>
                                <img src="https://st6.gismeteo.ru/static/diary/img/sun.png" alt="">
                            </td>
                            <td></td>
                            <td>
                                <span><img src="https://st8.gismeteo.ru/static/diary/img/w3.gif"alt=""><br>ЮВ 5м/с</span>
                            </td>
                            <td class="first_in_group positive">+9</td>
                            <td>743</td>
                            <td>
                                <img src="https://st5.gismeteo.ru/static/diary/img/sun.png"  alt=""></td>
                            <td></td>
                            <td><span><img src="https://st7.gismeteo.ru/static/diary/img/w3.gif" alt=""><br>ЮВ 5м/с</span></td>
                        </tr>
                        </tbody>
                        </table>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
<style>
.card-header{
    text-align: center;
}
table{
    border: black solid 1px;
    }
td,th{
    border: black solid 1px;
    text-align: center;
}
</style>
