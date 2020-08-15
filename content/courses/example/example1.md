---
title: Example Page 1
linktitle: Tips 1-2
toc: true
type: docs
date: "2019-05-05T00:00:00+01:00"
draft: false
menu:
  example:
    parent: Example Topic
    weight: 1

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 1
---

In this tutorial, I'll share my top 10 tips for getting started with Academic:

## Tip 1

## IntroducciÃ³n

Te sugiero ver el siguiente **tutorial** y luego aplicar los comandos de esta :

<iframe width="560" height="315" src="https://www.youtube.com/embed/-p02G7NXlSk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Pasos previos

Solicitamos nuestra base de datos:

```{r}
library(rio)
baseSOSS="https://github.com/DataPolitica/salidas/raw/master/Data/trabajadores.sav"
trabajadores=import(baseSOSS)
```

Identificamos las variables que tenemos:

```{r}
names(trabajadores)
```

### Generamos nuestro modelo de regresiÃ³n

```{r}
modelo1=lm(salario_actual~salario_inicial,data=trabajadores)
summary(modelo1)
```

Para realizar el anÃ¡lisis debemos seguir los pasos de nuestro flujograma:







.


## Tip 2
.
