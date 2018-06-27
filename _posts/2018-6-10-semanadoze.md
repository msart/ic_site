---
layout: post
title:  "Semana 12"
date:   2018-06-10 00:00:00 +0200
---

## 2018-06-10

* &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Nessa semana fui na terça para Belo Horizonte participar do SysMus 2018, que é uma conferência internacional de musicologia sistemática onde fiquei a semana inteira. Apesar de ter tido pouco tempo para trabalhar no projeto em si, foram 3 dias de aprensentações que foram extremamente proveitosas para mim.
* &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Acabei aproveitando essa semana para finalizar a última implementação e gerar alguns testes que anteriormente foram discutidos na reunião do grupo sobre como deveria abordar. Gerei a resposta de fase dos filtros passa-baixas usando ordem 8 (pois dois filtros eram IIR, que são lentos para quando usamos uma ordem muito grande) com uma frequência de corte de 7500hz e uma banda de transição de 500hz, além de duas medidas de erro para um filtro ideal(Euclidiana e de Chebyshev) e o tempo médio de execução em 1000 tentativas. Apenas o algoritmo ABC que demora mais que não teve seu teste concluído por demorar mais pra executar.

* &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Tempo: 3hrs(implementações e resultados) +1hr(seminário do grupo de computação musical)  = 4hrs