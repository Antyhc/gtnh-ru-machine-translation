# Цифровой детектор

![Обнаруживает в цифровом виде.](block:computronics:computronics.detector)

Цифровой детектор обнаруживает вагонетку, проезжающую рядом с блоком, и создаёт событие Lua `minecart`, которое может принять компьютер. Детектор нужно подключить к компьютеру с правильной стороны.

Событие `minecart` имеет следующий вид. Если синтаксис сигналов вам незнаком, обратитесь к [этому руководству](http://ocdoc.cil.li/component:signals).

`minecart(detectorAddress:string, minecartType:string, minecartName:string [, primaryColor:number, secondaryColor:number, destination:string, ownerName:string])`

Если вагонетке не присвоено имя, `minecartName` может быть пустой строкой. Для локомотива также передаются его цвета, пункт назначения (либо пустая строка, если он не задан) и имя владельца (либо пустая строка, если владельца нет).
