# Pentest605 Channels

Clone repo nya
```bash
git clone https://github.com/joelcg/PT605-Channel-Django-App.git

```

Instal virtual environment
```bash
pip install virtualenv

```

Buat folder virtual environment
```bash
virtualenv namaenv

# Kalau gagal, coba ini
python -m virtualenv namaenv
```

Aktivasi virtual environment
```bash
namaenv\scripts\activate

```

Buat file secret key dengan nama secret.txt
```bash
echo iniadalahstringsecretbuatlahsedemikianrupaagartidaklemah > secret.txt

```

Instal dependencies
```bash
pip install -r requirements.txt

```

Migrasikan migrations ke sqlite db
```bash
python manage.py makemigrations
python manage.py migrate

```

Jalankan aplikasi web nya
```bash
python manage.py runserver

```

> Aplikasi web nya bisa diakses disini: http://127.0.0.1:8000/