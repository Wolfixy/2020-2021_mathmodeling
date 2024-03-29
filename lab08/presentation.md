---
## Front matter
lang: ru-RU
title: "Отчет по лабораторной работе №8"
subtitle: "Модель конкуренции двух фирм"
author: |
	Поленикова Анна Алексеевна
institute: |
	\inst RUDN University, Moscow, Russian Federation
date: 2021

## Formatting
toc: false
slide_level: 2
theme: metropolis
mainfont: Times New Roman
romanfont: Times New Roman
sansfont: Times New Roman
monofont: Times New Roman
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
pdf-engine: xelatex
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---

# Цель работы и задание

## Цель работы

Цель лабораторной работы №8 - ознакомление с моделью конкуренции двух фирм.


## Задание

Вариант 38

**Случай 1.** Рассмотрим две фирмы, производящие взаимозаменяемые товары
одинакового качества и находящиеся в одной рыночной нише. Считаем, что в рамках
нашей модели конкурентная борьба ведётся только рыночными методами. То есть,
конкуренты могут влиять на противника путем изменения параметров своего
производства: себестоимость, время цикла, но не могут прямо вмешиваться в
ситуацию на рынке («назначать» цену или влиять на потребителей каким-либо иным 
способом.) Будем считать, что постоянные издержки пренебрежимо малы, и в
модели учитывать не будем. В этом случае динамика изменения объемов продаж
фирмы 1 и фирмы 2 описывается следующей системой уравнений:

## Задание

$$\frac{dM_1}{d\Theta} = M_1 - \frac{b}{c_1}M_1 M_2 - \frac{a_1}{c_1} M_1^2 $$

$$ \frac{dM_2}{d\Theta} = \frac{c_2}{c_1} M_2 - \frac{b}{c_1} M_1 M_2 - \frac{a_2}{c_1} M_2^2$$ 

где $$ a_1 = \frac{p_{cr}}{\tau_1^2 \widetilde{p}1^2 Nq } $$ 
$$ a_2 = \frac{p_{cr}}{\tau_2^2 \widetilde{p}2^2 Nq } $$ 
$$ b = \frac{p_{cr}}{\tau_1^2 \widetilde{p}_1^2 \tau_2^2 \widetilde{p}_2^2 Nq} $$ 
$$ c_1 = \frac{p_{cr} - \widetilde{p}_1}{\tau_1 \widetilde{p}_1} $$ 
$$ c_2 = \frac{p_{cr} - \widetilde{p}_2}{\tau_2 \widetilde{p}_2} $$

Также введена нормировка $t = c_1 \Theta$.

## Задание

**Случай 2.** Рассмотрим модель, когда, помимо экономического фактора
влияния (изменение себестоимости, производственного цикла, использование
кредита и т.п.), используются еще и социально-психологические факторы –
формирование общественного предпочтения одного товара другому, не зависимо от
их качества и цены. В этом случае взаимодействие двух фирм будет зависеть друг
от друга, соответственно коэффициент перед $M_1M_2$ будет отличаться. Пусть в
рамках рассматриваемой модели динамика изменения объемов продаж фирмы 1 и
фирмы 2 описывается следующей системой уравнений:

## Задание

$$\frac{dM_1}{d\Theta} = M_1 - \frac{b}{c_1} M_1 M_2 - 
\frac{a_1}{c_1} M_1^2$$

$$ \frac{dM_2}{d\Theta} = \frac{c_2}{c_1} M_2 - 
(\frac{b}{c_1} + 0.00083)M_1 M_2 - 
\frac{a_2}{c_1} M_2^2 $$

Для обоих случаев рассмотрим задачу со следующими начальными условиями и
параметрами:

$$ M_0^1=3.9, M_0^2=2.9 $$ 
$$ p_{cr}=25, N=39, q=1 $$ 
$$ \tau_1=29, \tau_2=19 $$ 
$$ \widetilde{p}_1=6.9, \widetilde{p}_2=15.9 $$

## Задание

1. Постройте графики изменения оборотных средств фирмы 1 и фирмы 2 без
учета постоянных издержек и с веденной нормировкой для случая 1.
2. Постройте графики изменения оборотных средств фирмы 1 и фирмы 2 без
учета постоянных издержек и с веденной нормировкой для случая 2.

# Теоретическая справка

## Теоретическая справка

Для построения модели конкуренции хотя бы двух фирм необходимо
рассмотреть модель одной фирмы. Вначале рассмотрим модель фирмы,
производящей продукт долговременного пользования, когда цена его определяется
балансом спроса и предложения. Примем, что этот продукт занимает
определенную нишу рынка и конкуренты в ней отсутствуют.

## Теоретическая справка

Обозначим:

$N$ - число потребителей производимого продукта.

$S$ – доходы потребителей данного продукта. Считаем, что доходы всех потребителей одинаковы. Это предположение справедливо, если речь идет об одной рыночной нише, т.е. производимый продукт ориентирован на определенный слой населения.

$M$ – оборотные средства предприятия

$\tau$ - длительность производственного цикла

$p$ - рыночная цена товара

$\widetilde{p}$ - себестоимость продукта, то есть переменные издержки на производство единицы продукции

## Теоретическая справка

$\delta$ - доля оборотных средств, идущая на покрытие переменных издержек

$k$ - постоянные издержки, которые не зависят от количества выпускаемой продукции.

$Q(S/p)$ – функция спроса, зависящая от отношения дохода $S$ к цене $p$. Она
равна количеству продукта, потребляемого одним потребителем в единицу
времени.

## Теоретическая справка

Функцию спроса товаров долговременного использования часто
представляют в простейшей форме:

$$Q = q - k\frac{p}{S} = q(1 - \frac{p}{p_{cr}})$$

где $q$ – максимальная потребность одного человека в продукте в единицу 
времени. Эта функция падает с ростом цены и при $p = p_{cr}$ (критическая 
стоимость продукта) потребители отказываются от приобретения товара. 
Величина $p_{cr} = Sq/k$. Параметр $k$ – мера эластичности функции спроса по 
цене. Таким образом, функция спроса является пороговой (то есть, $Q(S/p) = 0$ 
при $p \geq p_{cr}$) и обладает свойствами насыщения.

## Теоретическая справка

Уравнения динамики оборотных средств можно записать в виде:

$$\frac{dM}{dt} = -\frac{M \delta}{\tau} + NQp - k = -\frac{M\delta}{\tau} + Nq(1 - \frac{p}{p_{cr}})p - k$$

Уравнение для рыночной цены $p$ представим в виде:

$$\frac{dp}{dt} = \gamma (-\frac{M\delta}{\tau \widetilde{p}} + Nq(1-\frac{p}{p_{cr}}) )$$

Первый член соответствует количеству поставляемого на рынок товара 
(то есть, предложению), а второй член – спросу.

## Теоретическая справка

Параметр $\gamma$ зависит от скорости оборота товаров на рынке. Как правило, 
время торгового оборота существенно меньше времени производственного цикла 
$\tau$. При заданном $M$ уравнение описывает быстрое стремление цены к 
равновесному значению цены, которое устойчиво.

В этом случае уравнение можно заменить алгебраическим соотношением

$$ -\frac{M\delta}{\tau \widetilde{p}} + Nq(1-\frac{p}{p_{cr}}) = 0$$

их которого следует, что равновесное значение цены $p$ равно

$$ p = p_{cr}(1 - \frac{M\delta}{\tau \widetilde{p} Nq})$$

## Теоретическая справка

Тогда уравнение динамики оборотных средств приобретает вид

$$\frac{dM}{dt} = -\frac{M \delta}{\tau}(\frac{p}{p_{cr}}-1) - M^2 ( \frac{\delta}{\tau \widetilde{p} })^2 \frac{p_{cr}}{Nq} - k$$

Оно имеет два стационарных решения, соответствующих условию $dM/dt=0$

$$ \widetilde{M_{1,2}} = \frac{1}{2} a \pm \sqrt{\frac{a^2}{4} - b}$$

где

$ a = Nq(1 - \frac{\widetilde{p}}{p_{cr}} \widetilde{p} \frac{\tau}{\delta}) $, $ b = kNq \frac{(\tau \widetilde{p})^2}{p_{cr}\delta ^2} $

## Теоретическая справка

Из чего следует, что при больших постоянных издержках (в случае $a^2 < 4b$) 
стационарных состояний нет. Это означает, что в этих условиях фирма не может 
функционировать стабильно, то есть, терпит банкротство. Однако, как правило, 
постоянные затраты малы по сравнению с переменными (то есть, $b << a^2$) и 
играют роль, только в случае, когда оборотные средства малы. При $b << a$ 
стационарные значения $M$ равны

$$ \widetilde{M_{+}} = Nq \frac{\tau}{\delta}(1 - \frac{\widetilde{p}}{p_{cr}})\widetilde{p}, \widetilde{M_{-}} = k\widetilde{p} \frac{\tau}{\delta(p_{cr} - \widetilde{p})} $$

## Теоретическая справка

Первое состояние $\widetilde{M_{+}}$ устойчиво и соответствует стабильному 
функционированию предприятия. Второе состояние $\widetilde{M_{-}}$ неустойчиво, 
так, что при $M < \widetilde{M_{-}}$ оборотные средства падают ($dM/dt < 0$), 
то есть, фирма идет к банкротству. По смыслу $\widetilde{M_{-}}$ 
соответствует начальному капиталу, необходимому для входа в рынок.

В обсуждаемой модели параметр $\delta$ всюду входит в сочетании с $\tau$. 
Это значит, что уменьшение доли оборотных средств, вкладываемых в 
производство, эквивалентно удлинению производственного цикла. Поэтому мы в 
дальнейшем положим: $\delta = 1$, а параметр $\tau$ будем считать временем 
цикла, с учётом сказанного.

# Выполнение лабораторной работы

## Решение для 1 случая

В результате выполнения программы были получены следующие результаты для 1 случая: (рис. -@fig:001)

![График для 1 случая](image/graph1.png){ #fig:001 width=70% }

## Решение для 2 случая

Для 2 случая был получен следующий график: (рис. -@fig:002)

![График для 2 случая](image/graph2.png){ #fig:002 width=70% }

# Выводы

## Выводы

В результате проделанной лабораторной работы была изучена модель конкуренции двух фирм.