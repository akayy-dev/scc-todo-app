# Create a venv
```sh
python3 -m venv ./.venv
```
# Activate the venv
```sh
source ./.venv/bin/activate
```

# Install dependencies
```sh
pip install fastapi requests sqlite3
```

# Create the todos table
```sql
CREATE TABLE todos (id INTEGER PRIMARY KEY AUTOINCREMENT, todo TEXT NOT NULL);
```

# Insert into todos table
```sql
INSERT INTO todos (todo) VALUES ("Learn FastAPI");
```

# List todos
```sql
SELECT * FROM todos;
```
