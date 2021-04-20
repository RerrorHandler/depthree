<template>
    <div class=" container mx-auto text-white flex flex-row">
        <div class="flex flex-col text-xl mt-20">
            <span class="text-4xl mb-12">Наши Контакты</span>
            <span class="mb-12">Мы являемся мобильной студией и для удобства клиентов приедем<br> на встречу в любую часть города, либо встретим Вас в нашем уютном офисе.</span>
            <span class="mb-12">Если Вы с другого города, мы отработаем проект "онлайн".</span>
            <span class="mb-14">Оставь заявку на заказ дизайна или свяжись с нами по контактным телефонам.</span>
            <span class="mb-9">EMAIL / TEL  </span>
            <span class="mb-36">noirstudio@gmail.com / +7 771 761 11 64 (WhatsApp / Звонок)</span>
            
            <span class="mb-5">АДРЕС</span>
            <span class="mb-5">Гагарина 135, 2 этаж, 5 офис. Almaty / Kazakhstan</span>
            <div class="max-w-4xl mb-5" id="map">
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2906.8130766626937!2d76.89220165128658!3d43.234378587326916!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3883691f5a055555%3A0xf9dff1e57c1f3dbc!2z0JrQvtC70LvQtdC00LYgItOY0LTRltC70LXRgiIg0L_RgNC4INCa0LDRgdC_0LjQudGB0LrQvtC8INC-0LHRidC10YHRgtCy0LXQvdC90L7QvCDRg9C90LjQstC10YDRgdC40YLQtQ!5e0!3m2!1sru!2skz!4v1618124043507!5m2!1sru!2skz" width="896" height="555" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
            </div>
        </div>
        <div class="flex flex-col flex-nowrap mt-20 text-xl">
            <span class="text-4xl">Заказать дизайн</span>
            <div class="flex flex-row flex-nowrap ">
                <form>
                    <input id="input-field" placeholder="Ваше имя*" class=" placeholder-gray-50">
                    <input id="input-field" placeholder="Вид услуги*" class=" placeholder-gray-50"> 
                    <input id="input-field" placeholder="E-mail*" class=" placeholder-gray-50">
                    <input id="input-field" placeholder="Ваш город*" class=" placeholder-gray-50">
                    <button class="bg-white rounded-3xl text-black px-7 py-3">Подать заявку</button>
                </form>
                <form class="ml-10">
                    <span>Коментарий</span>
                    <textarea id="comments">

                    </textarea>
                </form>
            </div>
            <div class="flex flex-col items-center text-xl mt-20">
                <span class="text-3xl mb-8">Мы в Instagram</span>
                <span class="mb-8">Подписывайся и следи за новостями</span>
                <div class="flex flex-nowrap mb-4"><img src="../assets/inst.png"></div>
                <div class="flex space-x-6"><img src="../assets/fb.png"><img src="../assets/vk.png"><img src="../assets/telg.png"></div>
            </div>
        </div>
    </div>
</template>
<style>
#comments {
    resize: none;
    height: 182px;
    width: 350px;
    border-top: 0;
    border-left: 0;
    border-right: 0;
    border-bottom: 2px solid white;
    outline: none;
    background: transparent;    
}
#input-field {
    width: 350px;
    padding-top: 4px;
    padding-bottom: 4px;
    margin: 10px 0;
    border-top: 0;
    border-left: 0;
    border-right: 0;
    border-bottom: 2px solid white;
    outline: none;
    background: transparent;
}
#map {
    max-height: 555px;
}
</style>