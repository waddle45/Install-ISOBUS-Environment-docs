# blink_on_atom

\## Schritt_14:

Jetzt kann man Eclipse wirklich starten:

Nehmen Sie für das erste Projekt diesen Workspace:

C:\\git\\blink_on_atom\\eclipse-workspace

(außer sie haben vorhin auf D:\\git ausgecheckt>\`\_

```{image} https://user-images.githubusercontent.com/69573151/92934821-3effde00-f448-11ea-9631-7ec96373413a.png
```

\## Schritt_15:

Workbench --> Hide (rechts oben>\`\_

```{image} https://user-images.githubusercontent.com/69573151/124086686-9744b280-da51-11eb-847c-1629d53d2afb.png
```

\## Schritt_16:

```{image} https://user-images.githubusercontent.com/69573151/124086737-a4fa3800-da51-11eb-8438-b356d0efb55f.png
```

\## Schritt_17:

gehen Sie jetzt auf Import Projects

(Diesen Vorgang machen Sie später Analog für andere Projekte !!! Prägen Sie sich das ein !!!>\`\_

```{image} https://user-images.githubusercontent.com/69573151/92934978-74a4c700-f448-11ea-96b4-80fdf732a31d.png
```

```{image} https://user-images.githubusercontent.com/69573151/92935002-7cfd0200-f448-11ea-8178-a4531d733d4f.png
```

IMMER wenn man einen neuen Workspace aufmacht: (den man an diesem PC noch nie geöffnet hatte>\`\_
IMMER
siehe: \<<https://github.com/espressif/idf-eclipse-plugin/blob/master/README.md#installing-esp-idf-tools>

```{image} https://user-images.githubusercontent.com/69573151/92935162-b2095480-f448-11ea-8081-65189f5bf2a2.png
```

```{image} https://user-images.githubusercontent.com/69573151/124086854-c1967000-da51-11eb-897e-ae16f081ac62.png
```

```{image} https://user-images.githubusercontent.com/69573151/124086907-c9eeab00-da51-11eb-9069-77c69cac044e.png
```

YES

\## Schritt_18:

```{image} https://user-images.githubusercontent.com/69573151/124087513-5bf6b380-da52-11eb-905d-8f1383d09acc.png
```

C:\\Users\\Lehrer\\esp-idf-v4.3

C:\\Users\\Lehrer\\.espressif\\tools\\idf-git\\2.30.1\\cmd\\git.exe

C:\\Users\\Lehrer\\.espressif\\python_env\\idf4.3_py3.8_env\\Scripts\\python.exe

\## Schritt_20:

\<<https://github.com/espressif/idf-eclipse-plugin/blob/master/README.md#configuring-launch-target>

```{image} https://user-images.githubusercontent.com/69573151/124087774-a1b37c00-da52-11eb-9f06-1e4fdc2a4a59.png
```

```{image} https://user-images.githubusercontent.com/69573151/124087878-ba239680-da52-11eb-8555-cc85060ff2ce.png
```

\## Schritt_21

Drücken Sie dann erst den Hammer,

dann den "Play" Button.

```{image} https://user-images.githubusercontent.com/69573151/92991040-09f39a00-f4e1-11ea-9903-513d05ddba68.png
```

wenn jetzt folgendes erscheint:

```{image} https://user-images.githubusercontent.com/69573151/92991046-1a0b7980-f4e1-11ea-9ca7-68467df8ead0.png
```

dann öffnen Sie die Datei

```{image} https://user-images.githubusercontent.com/69573151/92991100-7b334d00-f4e1-11ea-9ce5-060e831d1e54.png
```

C:\\Users\\hoepffr\\esp-idf-v4.1\\tools\\idf_py_actions\\serial_ext.py

```{image} https://user-images.githubusercontent.com/69573151/92991095-6c4c9a80-f4e1-11ea-9eed-a64147547322.png
```

und ändern die Zahl 460800 ab in 1500000

```{image} https://user-images.githubusercontent.com/69573151/92991122-aa49be80-f4e1-11ea-8181-211d0d2cafcd.png
```

SPEICHERN nicht vergessen !

jetzt nochmal den PLAY Button drücken:

```{image} https://user-images.githubusercontent.com/69573151/92991156-057bb100-f4e2-11ea-918d-703a8cac8114.png
```

jetzt sollte es so aussehen,

und der ATOM sollte blinken.

machen Sie sich mit dem Programm vertraut.

\## Schritt_22

\<<https://github.com/espressif/idf-eclipse-plugin/blob/master/README.md#viewing-serial-output>

```{image} https://user-images.githubusercontent.com/69573151/92991167-1fb58f00-f4e2-11ea-824b-ba9b15978dec.png
```

```{image} https://user-images.githubusercontent.com/69573151/92991174-2c39e780-f4e2-11ea-82ce-e757c7c6df74.png
```

\## Programm verändern

verändern Sie zum Beispiel die CHASE_SPEED auf 10ms,

und schauen Sie was passiert.

machen Sie solche Änderungen noch ein paar mal, um mit dem Programm vertraut zu werden.
