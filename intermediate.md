# restaurant table reserving app

- user
  - name: string
  - phone number: integer

- reservation
  - user: string
  - phone number: integer
  - guests: integer

- restaurant
  - tables available [ids]

- table
  - id: integer
  - availability:
    - datetime -> [ids]

# university backend

- student
  - name: string
  - email: string
  - password: string
  - classes:
    - class: string
    - grade: integer
