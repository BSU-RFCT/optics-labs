# Лабораторные работы по оптике (2 курс)

| Лабораторная работа | Тема | Сделана | Исходник | PDF | Замечания |
|---|---|---|---|---|---|
| 1 | Изучение линз и оптических систем | ✅ | [1.tex](lab1/1.tex) | [lab1.pdf](https://github.com/BSU-RFCT/optics-labs/releases/download/latest/lab1.pdf) | Нет измерений для толстой линзы №3 |
| 2 | | ❌ | | | |
| 3 | Интерференция света в тонких плёнках | ✅ | [3.tex](lab3/3.tex) | [lab3.pdf](https://github.com/BSU-RFCT/optics-labs/releases/download/latest/lab3.pdf) | Длины волн на 8–10% ниже табличных |
| 4 | Интерферометр Рэлея | ✅ | [4.tex](lab4/4.tex) | [lab4.pdf](https://github.com/BSU-RFCT/optics-labs/releases/download/latest/lab4.pdf) | |
| 5 | Спектроскоп с призмой | ✅ | [5.tex](lab5/5.tex) | [lab5.pdf](https://github.com/BSU-RFCT/optics-labs/releases/download/latest/lab5.pdf) | Измерена одна призма, нет ширины основания `t` |
| 6 | | ❌ | | | |
| 7 | | ❌ | | | |
| 8 | | ❌ | | | |
| 9 | | ❌ | | | |
| 10 | | ❌ | | | |
| 11 | | ❌ | | | |
| 12 | | ❌ | | | |
| 13 | | ❌ | | | |
| 14 | | ❌ | | | |
| 15 | | ❌ | | | |

PDF собираются автоматически при каждом пуше в `main` и публикуются в [релизе `latest`](https://github.com/BSU-RFCT/optics-labs/releases/tag/latest).

## Сборка

Каждая работа лежит в своей папке `labN`. Для сборки отчёта нужны TeX Live и `latexmk`:

```bash
cd lab1 && latexmk -pdf 1.tex
```
