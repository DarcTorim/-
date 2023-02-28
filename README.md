# <div align="center"><h1>Поиск первой работы программистом</h1></div>



<h1>Как работать со скриптом</h1>


- Откройте браузер

- Перейдите на сайт hh.ru в раздел с подходящими вакансиями

- Откройте консоль разработчика



- Вставьте скрипт

<div align="center">

    (() => {
        let delay = 0;
        const jobs = document.querySelectorAll(".vacancy-serp-item__layout a.bloko-button");
        jobs.forEach(job => {
            setTimeout(() => {
                job.click();
            }, delay)
            delay += 2000
        })
    })();
                                      
</div>


- Нажмите Enter

<div align="center">После тестовых заданий и прочих всплывающих окон возвращайтесь к списку вакансий и снова запускайте скрипт</div>

<h1>Видео от урока</h1>

Чтобы понять смысл урока, посмотрите это объясняющее видео https://youtu.be/FgnLizSMt24

Источник разработанного кода: <b>Инди АйТи
