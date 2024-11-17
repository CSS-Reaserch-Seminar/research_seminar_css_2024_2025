# Научно-Исследовательский Семинар: Методология и Методы Исследований в Социальных Науках

## Преподаватель
- **Имя:** [Евгений Седашов](https://www.hse.ru/staff/sedashov)
- **E-mail:** [esedashov@hse.ru](mailto:esedashov@hse.ru)

## Ассистенты
- [Григорий Кирюхов](https://www.hse.ru/staff/KirilHSE/), [@goffkir](https://t.me/goffkir)
- София Янис, [@sofia_yan](https://t.me/sofia_yan)

## Структура Репозитория

В данном репозитории будут храниться материалы семинара, включая примеры кода, решения задач и домашние задания.

### Папки и файлы

- `seminar_code/` — папка, в которой будет размещен код, рассматриваемый на семинарах. Здесь вы найдете примеры, которые помогут понять теоретические концепции и методы анализа данных, обсуждаемые на занятиях.
  
- `homework/` — папка с домашними заданиями. В ней будут храниться задания для самостоятельной работы. Выполнять конкретные задания вы будете используя приглашения.

- `final_project/` — папка для финального проекта. Здесь будут храниться материалы и инструкции для выполнения заключительного научного текста.

- `info_about_course` - папка с подробной информацией про курс.

## Как пользоваться этим репозиторием

Для работы с этим репозиторием потребуется базовое знание команд Git. Здесь описано, как клонировать репозиторий и получать обновления с помощью терминала. Если у вас нет установленного Git, его можно скачать и установить с официального сайта: [https://git-scm.com/](https://git-scm.com/).

### 1. Клонирование репозитория общего репозитория на компьютер

Чтобы загрузить весь репозиторий на свой компьютер, выполните следующие шаги:

- Откройте терминал (или командную строку на Windows).
- Перейдите в ту папку, в которой хотите сохранить репозиторий. Например, если хотите сохранить его на рабочем столе, используйте команду:
  ```bash
  cd ~/Desktop
  ```
- Создайте ключ:
  ```bash
  ssh-keygen
  ```
- Протыкивайте клавишу ENTER
- В выводе команды будет ссылка, где храниться публичный ключ (public key)
- Выведите публичный ключ в консоль командой
  ```bash
  cat <path_to_your_public_key>
  ```
- Далее скопируйте этот ключ и откройте [Github](https://github.com/settings/keys)
- Нажмите на New SSH key
- Вставьте ваш скопированный публичный ssh ключ в Раздел **key**, он должен начинаться с *ssh* быть в одной строке
  ```bash
  Пример: ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIP5n3Lkmy1XXt9APDmgYmHxODkBZNWJZmNPZzx+IBvI6 kiril@p415
  ```
- Вставьте следующую команду для клонирования репозитория
   ```bash
   git clone git@github.com:CSS-Reaserch-Seminar/research_seminar_css_2024_2025.git
   ```
- После выполнения команды на вашем компьютере появится папка с репозиторием, содержащая все материалы курса.

### 2. Ознакомьтесь с кодом из папки `seminar_code/`
Откройте папку репозитория, затем перейдите в папку seminar_code/, чтобы ознакомиться с примерами кода, которые будут рассмотрены на семинарах. Эти примеры помогут вам лучше понять материал.

### 3. Выполнение домашних заданий
Для выполнения домашних заданий используйте материалы из папки `homework/`. В этой папке вы найдете задачи и инструкции. Сохраняйте свои решения в соответствующих файлах, чтобы было проще отслеживать прогресс.

### 4. Получение обновлений с помощью команды `git pull`
Репозиторий может обновляться: сюда будут добавляться новые материалы, задания и примеры кода. Чтобы загрузить новые файлы или изменения, выполните следующие действия:
 - Откройте терминал и перейдите в папку с репозиторием. Если вы сохранили репозиторий на рабочем столе, команда будет выглядеть так:
   ```bash
    cd ~/Desktop/research_seminar_css_2024_2025
   ```
- Используйте команду git pull, чтобы получить последние обновления:
    ```bash
    git pull
    ```




