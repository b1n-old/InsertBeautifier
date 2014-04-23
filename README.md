SQL Insert Beautifier plugin for Eclipse.

Turns this:
``` sql
INSERT INTO customer (id, name, home_phone, work_phone, city, address) VALUES (42, 'John Doe', null, '(+55-11) 9.9999.9999', 'Gothan City', '23, Elm Street');
```

Into this:
``` sql
INSERT INTO customer (id,       name, home_phone,             work_phone,          city,          address) VALUES
                     (42, 'John Doe',       null, '(+55-11) 9.9999.9999', 'Gothan City', '23, Elm Street');
```

