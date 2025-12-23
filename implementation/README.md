
**پروژه COVID-Net برای تشخیص بیماری‌های ریه از تصاویر Chest X-Ray**

این پروژه بر اساس مقاله COVID-Net: A Tailored Deep Convolutional Neural Network Design for Detection of COVID-19 Cases from Chest X-Ray Images طراحی شده است. هدف این پروژه، استفاده از شبکه عصبی کانولوشنی عمیق برای تشخیص خودکار بیماری‌هایی مانند COVID-19، پنومونی و حالت طبیعی ریه‌ها از تصاویر Chest X-Ray است.

لینک مقاله اصلی: 
https://pmc.ncbi.nlm.nih.gov/articles/PMC9818579/

لینک گیت‌هاب پروژه مقاله: 
https://github.com/lindawangg/COVID-Net/tree/master

لینک ترجمه مقاله: 
https://drive.google.com/file/d/1Jo9D0cCdLxCAEHUhOz9-tuhYS-gTfXWa/view?usp=drive_link

**نحوه پیاده‌سازی**

برای پیاده‌سازی این پروژه، ابتدا مدل پیش‌آموزش‌دیده COVID-Net از گیت‌هاب مقاله دانلود شد و در محیط Google Colab بارگذاری گردید. این مدل با استفاده از بیش از ۱۳۰۰۰ تصویر Chest X-Ray آموزش داده شده است تا توانایی تشخیص بیماری‌های ریه شامل COVID-19، Pneumonia و Normal را داشته باشد. تصاویر ورودی به دو اندازه (۲۵۶×۲۵۶ و ۴۸۰×۴۸۰) preprocessed شده و سپس به شبکه داده شدند. نتایج پیش‌بینی مدل شامل File Name، Actual Label، Predicted Label، Confidence و Status بوده و در قالب DataFrame نمایش داده می‌شوند.

علاوه بر داده‌های اصلی مقاله، از سایت Kaggle نیز نمونه‌هایی از دیتاست https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database) COVID-19 Radiography Database) برداشته شد و مدل روی این نمونه‌ها نیز تست گردید. با استفاده از این تصاویر تست، دقت مدل از حدود ۵۰٪ به ۷۵٪ افزایش یافت.
این پیاده‌سازی به گونه‌ای طراحی شده که با اتصال Google Drive، تصاویر تست قابل آپلود و بررسی باشند و حتی از طریق لینک Google Colab می‌توان مدل را اجرا و نتایج را مشاهده کرد:

https://colab.research.google.com/drive/1bGs6EIouUzVZwrkMf5B78BRUkfZtNMLb?usp=sharing
