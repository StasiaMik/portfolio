# Определение возраста покупателей

## 📌 Описание проекта  
Сетевой супермаркет «Хлеб-Соль» внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы:
- Анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы;
- Контролировать добросовестность кассиров при продаже алкоголя.

## 🎯 Задача  
Разработать модель, которая по фотографии определяет приблизительный возраст человека. Использовать **свёрточную нейронную сеть** и добиться **MAE ≤ 8** на тестовой выборке.  

## 📊 Результаты  
✅ **Модель обучена успешно**: MAE на тестовой выборке составило **7.3**.  
- Анализ данных показал, что большинство снимков относятся к возрастной группе **20-41 лет**.  
- Модель подходит для **анализа покупательской активности** и персонализированных предложений.  

## 🚀 Улучшения  
🔹 **Увеличение объема данных** и использование **аугментации (Albumentations)**.  
🔹 **Регуляризация:** увеличение dropout, уменьшение числа эпох, фиксация слоёв сети.  
🔹 **Альтернативные методы:** предобученные модели, сравнение фото с паспортом.  

🔗 **Ссылка на проект:** [Перейти к проекту](https://github.com/StasiaMik/portfolio/blob/main/project_computer_vision/project_CV.ipynb) 
