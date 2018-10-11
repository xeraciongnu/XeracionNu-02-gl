---
description: Desenvolvemento Web con R
---

# Shiny

![](.gitbook/assets/image%20%2823%29.png)

## Shiny

### **Que é Shiny?**

A visualización de datos xoga un papel vital na vida dun Científico de Datos. É máis fácil visualizar datos e relacións complexos que descifralos a partir de follas de cálculo ou de táboas.

Se pensamos na linguaxe R, existen diversas librerías que permiten de forma máis ou menos sinxela visualizar os datos dunha forma elegante. Ter que facer, programar, código unha e outra vez para xerar os gráficos, pode chegar a converterse nunha tarefa esgotadora e aburrida. Este tipo de problemas podería solucionarse creando gráficos dinámicos e interactivos. Esta solución a ofrece Shiny.

![](.gitbook/assets/image%20%2818%29.png)

Shiny é un paquete de R creado en 2012 por Rstudio \(GPLv3\) para desenvolver aplicacións Web utilizando R. Unha das características mais recoñecidas de R é que permite facer excelentes representacións gráficas, pois Shiny permite crear facilmente aplicacións web interactivas \(apps\) que permiten aos usuarios interactuar cos seus datos sen ter que manipular o código. Non se requiren coñecementos de HTML, JavaScript ou CSS para empregar Shiny, só coñecer R.

Na páxina web [https://shiny.rstudio.com/tutorial/](https://shiny.rstudio.com/tutorial/) preséntanse varios tutoriais de uso de Shiny cos seguintes artigos. O máis importante co programador debe coñecer é o seguinte:

· Partes básicas dunha aplicación Shiny

· Como construír unha aplicación Shiny

· Como executar unha aplicación Shiny

· Como obter axuda

· ….

### **Estrutura dunha aplicación Shiny**

As aplicacións con Shiny teñen dúas compoñentes:

1. **unha secuencia de comandos de interface de usuario**: a interface de usuario \(ui\) controla o deseño e o aspecto da aplicación: ui.R.

Este arquivo crea a interface de usuario nunha aplicación shiny. Proporciona interactividade á aplicación tomando a entrada do usuario e mostrando dinamicamente a saída xerada na pantalla.

2. **unha secuencia de comandos de servidor** o script server.R ten as instrucións que o equipo necesita para construír a aplicación, é dicir, contén a serie de pasos para converter a entrada dada polo usuario na saída desexada que se mostrará.

### **Executar unha aplicación Shiny**

· Cada aplicación Shiny ten a mesma estrutura: como mínimo dous scripts de R gardados no mesmo directorio: ui.R e server.R.

· Cada aplicación terá o seu propio directorio único.

· Executar unha aplicación Shiny, proporcionando o nome do directorio á función runApp.

· Si a aplicación está no directorio my\_app, empregaríase o seguinte código:

library\(shiny\)

runApp\("my\_app"\)

Poñamos en práctica o breve esquema anterior:

O primeiro que hai que facer se non se ten instalado o paquete é descargalo de internet, coa seguinte instrucción como calquera outro:

install.packages \("shiny" \)

e de seguido o cargamos:

library\(shiny\)

Como a maior parte dos paquetes en R, soen traer unha serie de exemplos de uso do mesmo. Neste caso o paquete Shiny trae once exemplos que demostran como funciona Shiny. E cada un deles é unha aplicación Shiny autónoma.

Para crear ou configurar unha aplicación Shiny dende RStudio os pasos que hai que seguir son os seguintes:

1. Crear un directorio chamado myapp/ para a túa aplicación.

2. Crear un novo proxecto en RStudio

3. Seleccione o tipo como aplicación web Shiny

4. Crea dous scripts en RStudio chamados ui.R e server.R.

5. Cada arquivo debe codificarse por separado

6. Gardar o script de aplicacion.R dentro dese directorio.

7. Iniciar á aplicación cos runApp de teclado de runApp ou RStudio.

8. Saír da aplicación Shiny facendo clic en escape.

![](.gitbook/assets/image%20%2853%29.png)

### **Publicar a aplicación Shiny na Web**

As aplicacións Shiny creadas para que sexan accesibles e usables por calquera outra persoa teñen que estar implementadas na web. Pode aloxar a aplicación en "[Shinyapps.io](http://www.shinyapps.io/)". Proporciona unha plataforma gratuíta como servicio \(PaaS\) para o despregue de aplicacións Shiny, con algunhas restricións, como solo 25 horas de uso en un mes, espazo de memoria limitado, etc.

Outra posibilidade é empregar un servidor propio para implementar aplicacións Shiny.

Os pasos para usar Shiny na nube son os seguintes:

1. Rexistrarse previamente [shinyapps.io](http://www.shinyapps.io/)

2. Ir as Ferramentas en RStudio.

3. Abrir as opcións globais.

4. Pestana de publicación aberta

5. Administrar a súa conta

### **Vantaxes e desvantaxes de Shiny**

Hai moitas outras ferramentas de visualización de datos. De seguido se enumeran unha serie de **vantaxes**:

- Tempo de resposta eficiente: o tempo de resposta da aplicación Shiny é moi pequeno, vai depender fundamentalmente do modelo empregado para mostrar os resultados.

- Automatización completa da aplicación: unha aplicación Shiny pódese automatizar para realizar un conxunto de operacións para producir a saída desexada en función da entrada.

- Non é preciso ter coñecementos de HTML, CSS ou JavaScript.

- Pode empregarse para mostrar datos máis complexos como estruturas 3D, mapas, etc.

- Código aberto: Crear e obter unha aplicación Shiny en liña é gratuíto, se desexa implementar a súa aplicación na versión gratuíta de [shinyapps.io](http://www.shinyapps.io/)

**Desvantaxes**:

- Require actualizacións oportunas: as funcións utilizadas na aplicación ás veces vólvense obsoletas con versións de paquetes máis novos, é necesario actualizar a aplicación Shiny cada vez. Pero a isto xa estamos acostumados.

- Restrición do tráfico na versión gratuíta: na versión gratuíta de [shinyapps.io](http://www.shinyapps.io/), só obtén 25 horas activas da súa aplicación por mes por conta.

Na seguinte ligazón [https://shiny.rstudio.com/articles/cheatsheet.html](https://shiny.rstudio.com/articles/cheatsheet.html) se pode consultar unha guía de referencia rápida para crear aplicacións Shiny con algúns trucos útiles.

