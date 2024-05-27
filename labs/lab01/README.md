Домашние задание №1
# Проектирование адресного пространства
## Цель
1. Собрать схему CLOS
2. Распределить адресное пространство

> Схема
> 
> ![image](https://github.com/ghlitoxa/OTUS-COD-Citadel-2024-05/assets/170517262/7b1917cd-17aa-468e-bdb8-bffb2af50bc1)

==============================================================
### Ответ на 1

![Аннотация 2024-05-24 065642](https://github.com/ghlitoxa/OTUS-COD-Citadel-2024-05/assets/170517262/b40d6327-12d3-441e-85aa-fef21b8c4e88)

### Ответ на 2

Name|Lo1
---|---
Spine1 | 10.0.1.1/16
Spine2 | 10.0.2.1/16

Name|Lo2
---|---
Leaf1	| 10.0.0.1/32
Leaf2	| 10.0.0.2/32
Leaf3	| 10.0.0.3/32

Name|p2p service
---|---
p2p Spine → Leaf1	| 10.1.1.1/31
p2p Spine → Leaf1	| 10.1.2.1/31
p2p Spine → Leaf2	| 10.1.1.2/31
p2p Spine → Leaf2	| 10.1.2.2/31
p2p Spine → Leaf3	| 10.1.1.3/31
p2p Spine → Leaf3	| 10.1.2.3/31
