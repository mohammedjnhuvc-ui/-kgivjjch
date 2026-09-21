# VodiWalker Full Panel

این بسته شامل نسخه کامل FastAPI پروژه VodiWalker است و قابلیت‌های اصلی پروژه GitHub را حفظ می‌کند: مدیریت لینک‌ها و اینباندها، ساخت کلاینت، لینک‌های VLESS برای TCP/WS، سابسکریپشن، گروه‌ها، دسته‌بندی‌ها، مدیریت ادمین، تنظیمات ربات، گزارش‌ها و API.

## اجرای محلی

```bash
python3 -m pip install -r requirements.txt
ADMIN_USERNAME=KKJNHHGV ADMIN_PASSWORD=09338845443 PORT=8000 uvicorn main:app --host 0.0.0.0 --port 8000
```

## نکته مهم استقرار

این پروژه FastAPI/Python است و با گزینه **Cloudflare Pages → Upload assets** اجرا نمی‌شود. برای اجرای کامل باید از Railway، Render، VPS یا یک سرویس Python استفاده شود. در Railway، فایل `railway.json` و `Dockerfile.txt` موجود است؛ متغیرهای محیطی `ADMIN_USERNAME` و `ADMIN_PASSWORD` را در تنظیمات سرویس ثبت کن.

## اعتبار ورود در این بسته

نام کاربری: `KKJNHHGV`

رمز: `09338845443`

برای محیط عمومی حتماً رمز را بعد از استقرار تغییر بده.
