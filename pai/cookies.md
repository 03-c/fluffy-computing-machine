ciasteczka wygaszają a localStorage nie, localStorage może więcej przechować

ustawianie ciasteczek: <br>
\- max-age: `document.cookie = "nazwa=wartość; max-age=[za ile ma wygaszać, w sekundach]"` <br>
\- expires: `document.cookie = "nazwa=wartość; max-age=[w jakiej milisekundzie po 1 stycznia 1970r. ma wygasznąć]"` <br>
zyskiwanie ciasteczek: `document.cookie` <br>
<sup>zwróci wszystkie ciasteczka w formacie "nazwa=wartość" oddzielone przez "; " (np. `meow=qwerty; mrrp=uiop`)</sup>

ustawianie localStorage: `localStorage.setItem("nazwa", "wartość")` <br>
zyskiwanie localStorage: `localStorage.getItem("nazwa")`

dodawanie klasy do elementu: `[...].classList.add("className")` <br>
usuwanie klasy z elementu: `[...].classList.remove("className")` <br>
przełączanie klasy na elemencie: `[...].classList.toggle("className")` <br>
<sup>jak element posiada klasę to ją usuwa, jak nie ma to dodaje</sup>

