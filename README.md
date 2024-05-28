# Sarbaz Gomnam

Sarbaz Gomnam یک ابزار تست نفوذ و امنیت وب است که طراحی شده است تا آسیب‌پذیری‌های شایع در وب‌سایت‌ها را تشخیص دهد و از جمله SQL Injection، XSS، Directory Traversal، و سایر آسیب‌پذیری‌های مهم امنیتی را بررسی کند.

## نقاط قوت

- قابلیت تشخیص چندین آسیب‌پذیری امنیتی اصلی مانند SQL Injection، XSS، و Directory Traversal.
- طراحی ساده و قابل استفاده برای تست‌های نفوذ مبتدی و حرفه‌ای.
- امکان افزودن آسیب‌پذیری‌های جدید و توسعه پذیری بالا.
- قابلیت تنظیم سریع و استفاده از پارامترهای سفارشی برای هر آسیب‌پذیری.

## پیش نیازها

- Python 3.x
- نصب کتابخانه‌های Python به وسیله دستور `pip install -r requirements.txt`

## روش استفاده

1. دانلود و نصب Python 3.x اگر نصب ندارید.
2. دانلود کد ابزار Sarbaz Gomnam از مخزن GitHub.
3. نصب پیش نیازهای ابزار با اجرای دستور `pip install -r requirements.txt`.
4. اجرای ابزار با دستور `python sarbaz_gomnam.py <آدرس_URL>` و جایگزینی `<آدرس_URL>` با URL وب‌سایت مورد نظر برای بررسی.

برای مثال:


python sarbaz_gomnam.py http://example.com


5. مشاهده نتایج بررسی آسیب‌پذیری‌ها در خروجی ترمینال.

