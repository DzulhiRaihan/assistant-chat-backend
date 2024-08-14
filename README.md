# Virtual Asstant Chat (Backend)

## SETUP DATABASE
Database yang digunakan dalam aplikasi ini adalah postgreSQL yang bisa di setup melalui link dibawah ini 

```
https://supabase.com/
```

kemudian untul tabel yang dibutuhkan adalah sebagai berikut 

<img src="demo\Screenshot 2024-08-15 025957.png">
<img src="demo\Screenshot 2024-08-15 030037.png">

## INSTALASI (Locally Running)

**Step 1 :**

Menginstal dependency yang dibutuhkan dengan menggunakan perintah 

```
pip install -r requirement.txt
```
**Step 2 :**

Mempersiapkan autentikasi untuk database yang di tampung dalam file .env

```
DATABASE_URL= "your-database-url"
SUPABASE_PROJECT_URL = "your-supabase-project-url
SUPABASE_API_KEY = "your-supabase-api-key"
```
**Step 3 :**

Menayalakan server python flask