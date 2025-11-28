różnice: <br>
\- ciasteczka wygaszają a localStorage nie <br>
\- localStorage może więcej przechować

ustawianie ciasteczek: <br>
\- max-age: `document.cookie = "nazwa=wartość; max-age=[za ile ma wygaszać, w sekundach]"` <br>
\- expires: `document.cookie = "nazwa=wartość; max-age=[w jakiej milisekundzie po 1 stycznia 1970r. ma wygasznąć]"` <br>
zyskiwanie ciasteczek: `document.cookie` <br>
<sup>zwróci wszystkie ciasteczka w formacie "nazwa=wartość" oddzielone przez "; " (np. `meow=qwerty; mrrp=uiop`)</sup> <br>
sprawdzanie ciasteczek: Inspect Element (F12) > Application > Cookies > domena

ustawianie localStorage: `localStorage.setItem("nazwa", "wartość")` <br>
zyskiwanie localStorage: `localStorage.getItem("nazwa")` <br>
sprawdzanie localStorage: inspect element (F12) > Application > Local Storage > domena
