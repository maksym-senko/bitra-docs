<p align="center">
  <img src="https://github.com/maksym-senko/bitra-docs/blob/main/assets/src/LiteOS/RUI3_C08/Screenshot_20260812-043730_Telegram.png" width="100%" alt="LiteOS RUI C08 Banner">
</p>

# Lite OS RUI C.08

* **Android:** 12.1
* **Статус:** Stok Mod IN
* **Дата билда:** 04.12.2022
* **Мейнтейнер:** @ᴹᴿ D E L T A

---

<details>
<summary><b>  Список изменений </b></summary>

<br>

**Безопасность:**
* Патч безопасности от сентября 2022.

**Производительность и накопитель:**
* Добавлены реальные драйверы Adreno 530 (максимальная версия для Realme UI).
* Отключено шифрование FBE для повышения скорости чтения/записи.
* Отключены принудительные OTA-обновления.
* Отключена проверка целостности загрузки (Device Boot Integrity Check) — `vbmeta`-патчинг не требуется.

**Деблоатинг:**
* Вырезано более 140 приложений, фоновых трекеров и плагинов.
* Удалены стандартный Google Dialer, Google Messages и тяжелый софт Google.
* Magisk убран из прошивки (устанавливается отдельно).

**Модули и кастомизация (Extras):**
* В комплект входят варианты звонилок: Motorola Dialer (Magisk-модуль с автоответчиком) или Realme Dialer (APK).
* Доступна возможность установки драйвера Adreno 655 через magisk_overlayfs.
* Совместимость с LSposed + Lucky Tool.

**Поддержка модулей оптимизации:** 
* Efficient-UC-Thermals-V2 (термолимиты).
* KillLogger_1.9_V7 (отключение логов).
* qti-mem-opt-v7.1 (оптимизация ОЗУ) и Zygisk SafetyNetFix (для банковских приложений).

</details>

<details>
<summary><b> Инструкция по установке</b></summary>

<br>

1. Загрузитесь в кастомное рекавери (Recovery).
2. Выполните форматирование данных (`Format Data` через ввод `yes`).
3. Прошейте нужный firmware и образ SuperPartition.img.
4. Выполните `Wipe Dalvik / ART Cache`.
5. Перезагрузитесь в систему.

</details>

<details>
<summary><b> Скачать</b></summary>

<br>

* [SourceForge](https://sourceforge.net/projects/rui-lite-os/files/RUI3-android-12/RUI3_LITE_OS_C08.zip/download)

</details>