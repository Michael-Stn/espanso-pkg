<a id="top"></a>
# **🗃️ SNIPPETS**
Listado de Snippets disponibles segmentando por categorías.  

> Ver el [README](README.md)

<br>

* * *

### CATEGORIAS

* [Generales](#generales)
* [Javascript](#javascript)
* [GCP](#gcp)

* * *

<br>

<a id="generales"></a>
>## **Generales**

| Trigger  |        Replace       |
|:--------:|:--------------------:|
|  `:date` | \<día>/\<mes>/\<año> |

## [⬆️](#top)
<br>

<a id="javascript"></a>
>## **Javascript**

| Trigger  |        Replace         | Sección  |
|:--------:|:----------------------:|----------|
|  `:clog` | console.log();         | vanilla  |
|  `:logd` | this.logger.debug();   | mbaas    |
|  `:jdev` | npm run dev\n          | nodejs   |

## [⬆️](#top)
<br>

<a id="gcp"></a>
>## **GCP**

| Trigger   |              Replace                               | Sección |
|:---------:|:--------------------------------------------------:|---------|
|  `:gpods` | kubectl get pods\n                                 | kubectl |
|  `:gpodg` | kubectl get pods \| grep {{name}}\n                | kubectl |
|  `:gsvcs` | kubectl get services\n                             | kubectl |
|  `:gsvcg` | kubectl get services \| grep {{name}}\n            | kubectl |
|  `:gport` | kubectl port-forward svc/{{service}} {{port}}:80\n | kubectl |
|  `:glogs` | kubectl logs {{pod}} -f\n                          | kubectl |

## [⬆️](#top)