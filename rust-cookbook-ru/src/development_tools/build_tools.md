# Инструменты времени компиляции

Этот раздел охватывает инструменты времени компиляции, или код который запускается до момента компиляции исходного кода крейта. По соглашению, код исполняемый во время сборки находится в файле **build.rs** и он часто называется "скриптом сборки". Распространённые случаи использования включают генерацию Rust кода и компиляцию связанного C/C++/asm кода. Смотрите [ документацию по этому вопросу] на crates.io для дополнительной информации.

{{#include build_tools/cc-bundled-static.md}}

{{#include build_tools/cc-bundled-cpp.md}}

{{#include build_tools/cc-defines.md}}

{{#include ../links.md}}


[ документацию по этому вопросу]: http://doc.crates.io/build-script.html