# Strona ksi

### Konfiguracja

Konfiguracja strony znajduję się w pliku "\_config.yml". O znaczeniu pól konfiguracji można dowiedzieć się [tutaj](https://hexo.io/docs/configuration.html)

### Odpalanie strony lokalnie

Aby odpalić stronę lokalnie wystarczy pobrać repozytorium i wykonać następujące polecenia (należy mieć zainstalowany yarn i nodejs).

~~~
yarn install
yarn start
~~~

### Deploy

Deployment jest automatyczny i wystarczy wrzucić commita na branch master, a w ciągu pięciu mimnut uaktualniona strona znajdzie się na serwerze

### Dodawanie 

Aby dodać nowy post należy wykonać polecenie:

~~~
hexo new post [tytuł_posta]
~~~

Wtedy w katalogu source/\_posts pojawi się nowy plik nazywający się jak tytuł posta. Modyfikując ten plik modyfikujemy treść posta.
