<p align="center">
  <img src="https://github.com/maksym-senko/bitra-docs/blob/main/assets/src/ColorOS/Port_Find-X5-Pro/8291ced4-40fb-4a3c-981e-a91e39dcc668.jpeg" width="100%" alt="ColorOS v4.1 Banner">
</p>

# Color OS 12.1 (с OPPO Find X5 Pro)

* **Android:** 12.1
* **Статус:** Unofficial Port
* **Дата билда:** 03.05.2022
* **Мейнтейнер:** 没有心不受伤

---

<details>
<summary><b>  Список изменений </b></summary>

<br>

* Основано на китайской прошивке RUI3 C05.
* Лимит приложений, заблокированных в фоновом режиме, увеличен до 999.
* Удалено виртуальное расширение памяти (по умолчанию изменено на 6 ГБ ZRAM).
* Удалена динамическая частота обновления (Dynamic Refresh Rate).
* Изменено управление температурой для предотвращения троттлинга и падения кадров.
* Удален системный "мусор" (браузеры, встроенная реклама, приложения музыки и видео).
* Настройка строки состояния, размытие и выравнивание.
* Размер значков по умолчанию установлен на 7, размер значков сторонних тем — на 70.

</details>

<details>
<summary><b> Требования </b></summary>

* Установленная стоковая прошивка RUI3 Android 12.

</details>

<details>
<summary><b> Известные ошибки </b></summary>

<br>

* Магазин тем не может менять шрифт (используйте сторонние модули для замены шрифта).

</details>

<details>
<summary><b> Инструкция по установке</b></summary>

<br>

1. Создайте папку на ПК и распакуйте туда файлы TWRP и прошивки.
2. Переведите выключенный телефон в режим Fastboot (зажмите Зажим Громкости Вниз + Питание).
3. Подключите телефон к ПК.
4. **Важно**: Перезагрузитесь в Fastboot режим именно через меню TWRP Fastboot (обычный Fastboot телефона может вызывать ошибки отсутствия разделов).
5. Выполните следующие команды в терминале ПК:

`javascript
fastboot flash boot boot.img`
`fastboot.exe --disable-verity --disable-verification flash vbmeta vbmeta.img`
`fastboot flash recovery recovery.img`
`fastboot reboot fastboot`
`fastboot flash my_bigball my_bigball.img`
`fastboot flash my_carrier my_carrier.img`
`fastboot flash my_company my_company.img`
`fastboot flash my_engineering my_engineering.img`
`fastboot flash my_heytap my_heytap.img`
`fastboot flash my_manifest my_manifest.img`
`fastboot flash my_preload my_preload.img`
`fastboot flash my_product my_product.img`
`fastboot flash my_region my_region.img`
`fastboot flash my_stock my_stock.img`
`fastboot flash odm odm.img`
`fastboot flash product product.img`
`fastboot flash system system.img`
`fastboot flash system_ext system_ext.img`
`fastboot flash vendor vendor.img`
`fastboot -w`
`fastboot reboot`

</details>

<details>
<summary><b> Скриншоты</b></summary>

<br>

<p align="center">
  <img src="https://github.com/maksym-senko/bitra-docs/blob/main/assets/src/ColorOS/Port_Find-X5-Pro/e0b636c4-cf1f-4756-a8e7-72ef5ab958f3.jpeg" height="200">
  <img src="https://github.com/maksym-senko/bitra-docs/blob/main/assets/src/ColorOS/Port_Find-X5-Pro/ae3766ed-3cda-4da2-a355-d1e87f0a06ba.jpeg" height="200">
  <img src="https://github.com/maksym-senko/bitra-docs/blob/main/assets/src/ColorOS/Port_Find-X5-Pro/98414a95-58f7-4d06-ae9c-3d8477b6bc76.jpeg" height="200">
</p>

<p align="center">
  <img src="https://github.com/maksym-senko/bitra-docs/blob/main/assets/src/ColorOS/Port_Find-X5-Pro/5a9658ee-c83a-48b4-8d9f-6d9c1acd91bd.jpeg" height="200">
  <img src="https://github.com/maksym-senko/bitra-docs/blob/main/assets/src/ColorOS/Port_Find-X5-Pro/578bbb90-80b7-485f-b5ce-51faf3fe0141.jpeg" height="200">
  <img src="https://github.com/maksym-senko/bitra-docs/blob/main/assets/src/ColorOS/Port_Find-X5-Pro/255456bc-f5e6-4b7c-9dca-882e6cd5f503.jpeg" height="200">
</p>

</details>

<details>
<summary><b> Скачать</b></summary>

<br>

* [Google Drive](https://drive.google.com/file/d/1yveaQ_UHD54c2Dl2KleCMEAVO0TWQDaK/view?usp=sharing)
* [Pixeldrain](https://pixeldrain.com/u/NnsZ2yvQ)
* [Huggingface](https://huggingface.co/datasets/spitfirert/bitra-archive/resolve/24f8011c62d57b0a83eec0fccbf17652c32c89f7/ROMs/Android-12/ColorOS/v12.1_03.05.2022/ColorOS12_port_bitra.zip)
* [Internet archive](https://archive.org/download/bitra-archive/ROMs/Android-12/ColorOS/v12.1_03.05.2022/ColorOS12_port_bitra.zip)

</details>