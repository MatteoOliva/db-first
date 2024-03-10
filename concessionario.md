# automobili_del_concessionario

ID

| field        | TYPE        | ATTRIBUTES                                 | INDEXES     |
| ------------ | ----------- | ------------------------------------------ | ----------- |
| id           | int         | auto increment(not null, unsigned, unique) | primary key |
| marca        | varchar(25) | not null                                   |             |
| modello      | varchar(25) | unique, not null                           |             |
| cv           | smallint    | null unsigned                              |             |
| prezzo       | int         | not null, unsigned                         |             |
| acquistabile | char(2)     | not null default("si")                     |             |
| seconda mano | char(2)     | null                                       |             |
