# vigilant_winner Flask Application

This is a Flask application.

## Installation

From source:

```bash
git clone https://github.com/Torugo/vigilant-winner vigilant_winner
cd vigilant_winner
make install
```

From pypi:

```bash
pip install vigilant_winner
```

## Executing

This application has a CLI interface that extends the Flask CLI.

Just run:

```bash
$ vigilant_winner
```

or

```bash
$ python -m vigilant_winner
```

To see the help message and usage instructions.

## First run

```bash
vigilant_winner create-db   # run once
vigilant_winner populate-db  # run once (optional)
vigilant_winner add-user -u admin -p 1234  # ads a user
vigilant_winner run
```

Go to:

- Website: http://localhost:5000
- Admin: http://localhost:5000/admin/
  - user: admin, senha: 1234
- API GET:
  - https://localhost:5000/api/v1/product/
  - https://localhost:5000/api/v1/product/1
  - https://localhost:5000/api/v1/product/2
  - https://localhost:5000/api/v1/product/3


> **Note**: You can also use `flask run` to run the application.
