# نسخه نصب‌شونده هم‌گام (PWA)

فایل اصلی شما دست‌نخورده در مسیر قبلی باقی مانده است:

`/home/user/hamgam-app/hamgam-mobile-clean.html`

این پوشه نسخه نصب‌شونده است:

`/home/user/hamgam-installable-pwa`

## نصب روی Chrome/Edge

PWA از `file://` کامل نصب نمی‌شود. از localhost اجرا کنید:

```bash
cd /home/user/hamgam-installable-pwa
python3 -m http.server 8080
```

بعد در مرورگر باز کنید:

```text
http://localhost:8080
```

سپس گزینه Install / نصب را بزنید.

## انتقال اطلاعات

اگر دیتای قبلی در نسخه فایل اصلی است:

1. از همان نسخه بکاپ کامل بگیرید.
2. نسخه PWA را نصب و باز کنید.
3. بکاپ را از تنظیمات وارد کنید.

بعد از یک بار بازشدن کامل، برنامه آفلاین کار می‌کند.
