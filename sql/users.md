[user] ma format `'nazwa_uzytkownika'@'host'`, np. `'admin'@'localhost'`

- `DROP USER [user]` usuwa użytkownika [user]
- `CREATE USER [user] IDENTIFIED BY '[password]'` tworzy użytkownika z hasłem [password]
- `GRANT [privileges] ON [database] TO [user]` daje permisje do [privileges] w bazie/bazach danych [database] dla użytkownika [user].
  - przykładowe permisje: `SELECT`, `INSERT`, `UPDATE`, `DELETE`, `CREATE` (tworzenie tabel i baz), `CREATE VIEW` (tworzenie widoków), `DROP` (usuwanie baz, tabel i widoków), `ALL PRIVILEGES` (wszystkie permisje)
  - nazwa bazy danych może mieć gwiazdki. przykłady: np. `*.*`, `employees.*`, `employees.managers`
  - np. `GRANT SELECT, INSERT, UPDATE ON employees.* TO 'manager'@'localhost'`
- `SHOW GRANTS FOR [user]` pokazuje permisje użytkownika [user]
- `ALTER USER [user] IDENTIFIED BY '[password]'` zmienia hasło [user] na [password]
- `FLUSH PRIVILEGES` odświeża uprawnienia użytkowników ([nie jest potrzebne jak używasz powyższych komend[[1]](https://stackoverflow.com/a/47155873))
