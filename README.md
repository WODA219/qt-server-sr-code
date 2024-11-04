 исходные коды qt server and client
Исходный код qtanks с некоторыми изменениями . Код запутан, но я постепенно устраняю путаницу в том, что я хочу изменить. Таким образом, в будущем код станет более худже, но он никогда не будет полностью деобфускирован. 

## Компиляция
#### Подготовка SDK
Нам нужны два SDK: AIR SDK для отладки и FLEX SDK для компиляции.

Для компиляции вы должны использовать flex_sdk_4.6.0.23201. Его можно найти здесь: https://github.com/JamesMGreene/node-flex-sdk/blob/master/FlexSDKs.md После извлечения SDK вам следует заменить файл "flex_sdk_4.6.0.23201/frameworks/libs/air/airglobal.swc" на файл "this_repo/tools/airglobal.swc". Папка tools находится в этом репозитории. Папку Tools можно удалить после замены swc-файла.

Далее загрузите air SDK (https://airsdk.harman.com/download). Извлеките его, куда захотите.

Готово!!
Пе
скрины  фулл QTanks https://prnt.sc/HnwU1_cUFG-F
