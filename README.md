# Index explorer for Windows 🪟

<a href="https://github.com/roby8martin/index-win/releases"><img src="https://img.shields.io/github/release/roby8martin/index-win?style=flat-square"></a>

## ⚙️ Funzioni
Questo repository se clonato sulla cartella del vostro ambente di sviluppo su **Windows** (Esempio dentro la cartella **htdocs** di [XAMPP](https://www.apachefriends.org/it/index.html)) permette di installare un interfaccia web per visualizzare le cartelle dei vostri siti web ma anche:
  - Link rapidi a:
    - [PhpMyAdmin 🗂️](https://www.phpmyadmin.net/),
    - [Php Info 🐘](https://www.php.net/manual/en/function.phpinfo.php),
  - **Indirizzo ip del vostro computer sempre visibile con la possibilià di generare un qrcode per aprire la pagina dai vostri disositivi mobili**,
  - Dark Mode 😎,
  - Easter Egg 🐣 🤭.

## 🧑‍💻 Requisiti
Una Macchina Windows con:
  - **XAMMP** (va bene sia la versione instalalta che quella stand alone).

Oppure un qualsiasi altro ambiete di sviluppo con all'interno:
  - **Apache o Nginx** come web server,
  - **Php** con la possiblità di eseguire lo script `shell_exec` o `exec`.

  **OPZIONALE**
  - **PhpMyAdmin** che sia rangiungibile dal percorso `localhost\phpmyadmin` (Si può modificare il percorso dal sito web).
  
## 🖥️ Come installarlo
Una volta **soddisfatti i requisiti**:
  - Usare il seguente script per l'installazione **automatica**:
  ```
  git clone https://github.com/roby8martin/index-win && cd index-win &&  move redirect.php ../index.php
  ```
  
  
  - Oppure eseguire lo script **manualmente**:
    - Clonate questo repository 
    ```
    git clone https://github.com/roby8martin/index-win
    ```

    - Entrate dentro la cartella **index-win**
    ```
    cd index-win
    ```

    - Spostate il file **redirect.php** e rinominatelo in **index.php**  nella radice della cartella dove mettete i vostri siti web (**htdocs** nel caso di XAMPP)
    ```
    move redirect.php ../index.php
    ```

## 🧑‍💻 Come usarlo
Per usarlo scrivete [http://localhost/](http://localhost/) sul vostro browser:
  - Selezionate dalla tabella il sito che volete aprire, premendo sul nome o sul pulsante blu,
  - Per aprire **PhpMyAdmin** usate il pulsante **giallo** che trovate sopra la tabella,
  - Per vedere le informazioni del vostro **PHP** usate il pusante **blu** (phpinfo)
  - Per ricaricare la pagina potete utilizare il pulsante **verde**.