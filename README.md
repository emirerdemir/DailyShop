# Django Web Sitesi Teması

Bu proje, Django ile oluşturulmuş bir web sitesine özelleştirilmiş bir tema uygulanmıştır. Bu README dosyası, temanın nasıl kurulduğunu ve projeye nasıl katkıda bulunabileceğinizi açıklar.

## Özellikler

- [Belirtilen Tema Adı] teması ile görsel güncellemeler
- Responsive tasarım
- [Diğer önemli özellikler veya özelleştirmeler]

## Kurulum

1. **Depoyu klonlayın:**

    ```bash
    [git clone https://github.com/kullanici_adiniz/django-web-sitesi-temasi.git](https://github.com/emirerdemir/DailyShop)
    ```

2. **Gerekli paketleri yükleyin:**

    Projeyi çalıştırmak için bir sanal ortam oluşturup gerekli paketleri yükleyin.

    ```bash
    cd django-web-sitesi-temasi
    python -m venv venv
    source venv/bin/activate  # Windows için: venv\Scripts\activate
    pip install -r requirements.txt
    ```

3. **Statik dosyaları toplayın:**

    Temanın ve diğer statik dosyaların doğru bir şekilde yüklenmesi için aşağıdaki komutu çalıştırın.

    ```bash
    python manage.py collectstatic
    ```

4. **Veritabanını oluşturun ve migrate edin:**

    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

5. **Sunucuyu başlatın:**

    ```bash
    python manage.py runserver
    ```

    Sunucu, varsayılan olarak [http://localhost:8000](http://localhost:8000) adresinde çalışacaktır.

## Kullanım

Projede yapılan özelleştirmeler ve temanın nasıl uygulanacağı hakkında bilgi:

- Temanın görünüm ve davranışını değiştirmek için `templates` ve `static` klasörlerinde düzenlemeler yapabilirsiniz.
- Web sitesinin mevcut yapısında değişiklik yapmak için `views.py`, `models.py`, ve diğer Django bileşenlerini kullanabilirsiniz.
