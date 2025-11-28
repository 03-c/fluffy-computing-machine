konkatynacja: "+" pozwala łączyć dwa teksty ze sobą (albo jeden tekst i jedną np. liczbę) <br>
przykłady: `"Hello " + "World!"`; `"Error: " + error`; `"number 9: " + 9 + "oraz 5: " + 5`

zmienne:
- `const` robi że nie da sie zmienić wartości zmiennej
- `let` pozwala na zmianę wartości

input/output:
- `console.log("meow")` napisze "meow" na konsoli. przydatne do debugowania
- `prompt("zapytanie")` prosi użytkownika o odpowiedź, która jest zwracana przez funkcje
- `alert(1)` wyśle komunikat do użytkownika o treści "1"
- `print()` poprosi przeglądarkę o wydrukowanie aktualnej strony (użytkownik musi zatwierdzić drukowanie)

klasy:
- dodawanie klasy do elementu: `[...].classList.add("className")` <br>
- usuwanie klasy z elementu: `[...].classList.remove("className")` <br>
- przełączanie klasy na elemencie: `[...].classList.toggle("className")` <br>
  <sup>jak element posiada klasę to ją usuwa, jak nie ma to dodaje</sup>

pętle:
- `for (const x of y) {}` - `y` jest listą, `x` będzie każdym elementem w tej liście
- `x.split(y)` - `x` jest tekstem, split dzieli go na części między każdym `y`. <br>
  np. `"meow,mrrp,purr".split(",")` -> `["meow", "mrrp", "purr"]`

style:
- `[element].style.[styl] = [wartość]` robi to samo co `[element] { [styl]: [wartość] }` by robiło w CSS

funkcje:
- `function name(arg1, arg2, arg3)` tworzy funkcje "name", która może otrzymać trzy argumenty.
  można zyskać wartość tych argumentów używając `arg1`, `arg2` i `arg3`.
  (nazwy są przykładowe, można nazwać dowolnie)
- `name("meow", 3, false)` wywołuje funkcje "name" z poniższymi argumentami: <br>
  \- `arg1` = "meow" <br>
  \- `arg2` = 3 <br>
  \- `arg3` = `false`
- `name()` wykonuje funkcje "name" bez argumentów, wszystkie argumenty będą zwracać `undefined`

daty:
- `new Date()` tworzy element daty z aktualnym czasem
- `.getTime()` zwraca ile milisekund upłynęło od 1 stycznia 1970 o godzinie 00:00:00

matematyka:
- `Math.floor(x)` - `x` jest liczbą, zostanie ona zaokrąglona do dołu (do jedynek)
- `Math.abs(x)` - `x` jest liczbą. funkcja konwertuje liczby negatywne na pozytywne
