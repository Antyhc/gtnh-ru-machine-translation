# Плата переключателя

![Щёлк-щёлк.](item:computronics:computronics.ocParts@13)

Эту плату можно установить в серверную стойку. На её передней панели находятся четыре переключателя: их состояние можно проверять и изменять через компонент `switch_board`. Кроме того, каждое ручное или автоматическое переключение вызывает событие `switch_flipped`.

Событие `switch_flipped` выглядит следующим образом. Если синтаксис сигналов вам незнаком, обратитесь к [этому руководству](http://ocdoc.cil.li/component:signals).

`switch_flipped(boardAddress:string, index:number, newState:boolean)`
