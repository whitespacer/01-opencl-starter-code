# 01-opencl. Двухмерная свертка

Условия лабораторной находится в файле lab1.pdf.  
Вопросы можно задавать по почте silakov@gmail.com и в telegram: @whitespacer.    
Те, кому интересно, могут реализовать первую лабораторную с использованием локальной памяти. Но это не является обязательным требованием.  

Ссылка на репозиторий с лекциями: https://github.com/whitespacer/opencl_lections  
Ссылка на репозиторий с примерами c лекции: https://github.com/whitespacer/opencl_samples  

*Note*: в данной лабораторной нельзя использовать автоматическое вычисление размера work group.  
*Note 2*: в некоторых версиях драйвера Intel для OpenCL есть баг, который приводит к access violation при попытке получить список девайсов для платформы Intel. Самое простое решение, подходящее для лабораторной, это пропустить intel платформу при инициализации программы.  
