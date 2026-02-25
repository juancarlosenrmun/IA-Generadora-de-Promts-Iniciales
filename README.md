# IA Generadora de Promts Iniciales
>Proyecto realizado por Juan Carlos Enríquez Muñoz

## Motivación
A lo largo de la carrera me he ecnontrado en la situación de usar distintos agentes para realizar diversas actividades. No obstante, para que un agente inteligente funcione correctamente es necesario un buen **promt incial**, al cuál hay que dedicarle cierto tiempo para que sea lo más descriptivo posible. 

Aunque pudieramos dedicarle todo el tiempo del mundo, podríamos pasar por alto cierto aspectos necesarios para que el agente funcione correcta, es por ello que esta IA te lleva por camino procedimental e iterativo para que el promt se ajuste perfectamente a tu idea, e incluso corregir el promt en caso de que sea necesario.

## Descripción

Una vez comenzado el proceso, la IA empezara preguntando por una breve descripción de lo que se desea hacer con el nuevo agente, así como su área principal.

Seguidamente, la IA comenzara a hacer preguntas para afinar el proposito del agente de modo que quede lo más detallado posible.

Finalmente, la IA pregunta si es necesario que el usuario suba ficheros adicionales y alguna indicaciones de uso.

Como resultado se muestra una vista previsa y, en caso de aceptarse, genera el fichero markdown. En caso contrario, la IA pide que se mencione los errores y, en caso de ser necesario, realiza más preguntas

## Modo de Uso

En primer lugar tenemos que crear una nueva conversacion en nuestro _ChatBot_ de preferencia, en mi caso _Gemini_.

En este chat tendremos que pasar el [promt](IA_Generador_Promts.md) que os incluyo en el repositorio.

Una vez la IA haya analizado el promt inicial podremos comenzar el proceso.

Finalmente, cuando hayamos obtenido nuestro fichero _markdown_ tendremos que copiarlo y pegarlo en una nueva conversación. A partir de ahí, ese chat será ideal para usarlo en el ámbito decidido, e incluso avisara si pedimos algo fuera de él.

## Notas
* Se usa ficheros _markdown_ para exportar los promts puesto que es el formato que usa la IAs para mandar sus mensajes.

