---
description: Laboratorio Android
---

# Termux: Unha terminal para gobernalos a todos

![](.gitbook/assets/image%20%2842%29.png)

## Termux: Unha terminal para gobernalos a todos

Chamádeme vello, pero eu non concibo un sistema operativo no que non poder escribir sobre unha terminal de comandos. As vantaxes son moitas, sobre todo se atopamos un emulador de terminal, para Android neste caso, que non necesite de root e que nos permita ampliar a súa funcionalidade usando o xestor de paquetes APT… Ese é TERMUX \( [https://termux.com/](https://termux.com/) \)

Termux é, en definitiva, un emulador de terminal para o noso Android que nos permitirá , por medio dunha shell, a execución de comandos Linux.

Para empezar, podemos instalalo e utilizalo no noso Android sen permisos de superusuario \( root\). No caso de que non ser superusuarios, debido ás restricións de acceso dun usuario estándar, non poderemos modificar determinados ficheiros de Sistema pero iso non será un impedimento para gozar dun terminal tremendamente operativo.

Pero empecemos polo principio:

Podemos descargalo directamente desde Google Play ou desde o repositorio de Software Libre F- DROID \(do que xa falamos con anterioridade nesta sección\).

Ligazón de Google Play: https://play.google.com/store/apps/details?ide=com.termux​

Ligazón de F- DROID: [https://f-droid.org/packages/com.termux/](https://f-droid.org/packages/com.termux/)​

Unha vez instalado, teremos unha icona no noso dispositivo que nos abre directamente a terminal de comandos.

![](.gitbook/assets/image%20%2810%29.png)

Basta executar “ help” para darnos conta das capacidades de Termux. Por se isto fose pouco, dispoñemos do conxunto de utilidades que nos proporciona Busybox \( [https://busybox.net/](https://busybox.net/) \) a “navalla suíza” de ferramentas UNIX para Android. Unha multitude de utilidades que nos farán a vida máis fácil desde a terminal de comandos.

![](.gitbook/assets/image%20%2820%29.png)

O meu primeiro impulso, ao ler a información proporcionada ao arrincar o terminal, foi executar apt para instalar “ screenfetch” \[pkg install screenfetch\] e “ Midnigth Commander” \[pkg install mc\] … e este é o resultado...

![](.gitbook/assets/image%20%286%29.png)

![](.gitbook/assets/image%20%2833%29.png)

As posibilidades de Termux son enormes… Podemos instalar Git, Perl, Python, Ruby, Node. js, rsync, OpenSSH, curl, wget, gcc, gnugp, emacs, nano, vim \(aínda que trae “vi” preinstalado e listo para utilizar\)… mesmo podemos montar un servidor ssh no propio dispositivo para poder conectarse desde o exterior \(sshd no porto 8022\). Ademais, se observamos que busybox quédasenos “curto” de comandos, podemos instalar coreutils \[pgk install coreutils\].

Para finalizar este breve percorrido polas \(enormes\) capacidades de Termux, hai que mencionar a posibilidade de ampliar a súa funcionalidade por medio de complementos. Os complementos de Termux son módulos instalables que conseguen dotar de mais funcionalidade á terminal de comandos.

Sirva como exemplo **Termux: API**, un complemento que permite, entre outras cousas, acceder a funcións do hardware de Android \(batería, cámara, control de SMS, acceso ao GPS, ...\)

![](.gitbook/assets/image%20%2815%29.png)

Outro interesante é Termux: Boot, que nos permite executar scripts cando arrinca o dispositivo.

En definitiva, Termux é un emulador de terminal de comandos Linux que nos permitirá ampliar o control sobre o noso dispositivo “pola vella”. Chamádeme vello, agora si.  
:-\)

