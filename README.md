# Django project
![App Screenshot](https://github.com/firengizz099/Django_project/blob/main/django1.jpg?raw=true)
1) Django projenizi başlatmak için aşağıdaki adımları izleyebilirsiniz:

2) İlk adım olarak, Django'yu yüklemek için pip kullanarak aşağıdaki komutu çalıştırın:
pip install Django

3) Django projesini oluşturmak için aşağıdaki komutu kullanın (proje_adı yerine projenizin adını belirtin):
django-admin startproject proje_adı

4) Bu komut, Django projesini içeren bir ana dizin oluşturacak ve içinde aşağıdaki dosyaları içerecek:
proje_adı/
├── proje_adı/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── manage.py
└── venv/ (isteğe bağlı - sanal ortam klasörü)
5) Şimdi Django projesi ana dizinine gidin:
cd proje_adı
6) Bir uygulama (uygulama_adı) oluşturmak için aşağıdaki komutu kullanın (uygulama_adı yerine kendi uygulama adınızı kullanmalısınız):
python manage.py startapp uygulama_adı
7) Son olarak, Django geliştirme sunucusunu başlatmak için aşağıdaki komutu çalıştırın:
python manage.py runserver
