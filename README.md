# Django_project

*Django projenizi başlatmak için aşağıdaki adımları izleyebilirsiniz:

*İlk adım olarak, Django'yu yüklemek için pip kullanarak aşağıdaki komutu çalıştırın:
pip install Django

*Django projesini oluşturmak için aşağıdaki komutu kullanın (proje_adı yerine projenizin adını belirtin):
django-admin startproject proje_adı

*Bu komut, Django projesini içeren bir ana dizin oluşturacak ve içinde aşağıdaki dosyaları içerecek:
proje_adı/
├── proje_adı/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── manage.py
└── venv/ (isteğe bağlı - sanal ortam klasörü)
*Şimdi Django projesi ana dizinine gidin:
cd proje_adı
*Bir uygulama (uygulama_adı) oluşturmak için aşağıdaki komutu kullanın (uygulama_adı yerine kendi uygulama adınızı kullanmalısınız):
python manage.py startapp uygulama_adı
*Son olarak, Django geliştirme sunucusunu başlatmak için aşağıdaki komutu çalıştırın:
python manage.py runserver
