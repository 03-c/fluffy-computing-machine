- `mysqldump -u [user] [nazwa bazy]` wydrukuje eksport bazy danych
- `mysqldump -u [user] [nazwa bazy] > [name]` zrobi eksport bazy danych do pliku [name] <br>
  np. `mysqldump -u root employees > backup.sql`
- `mysql -u [user] [nazwa bazy] < backup.sql` importuje bazę z eksportu znajdującym się w `backup.sql`
