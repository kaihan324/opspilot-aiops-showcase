# OpsPilot AIOps — نسخه نمایشی عمومی

**OpsPilot** یک پلتفرم عملیات زیرساخت با کمک AI است که داده‌های **Zabbix**، **VMware vCenter** و تست‌های فعال شبکه را کنار هم قرار می‌دهد و روی آن‌ها Incident Correlation، تحلیل علت محتمل، Playbook، Remediation Workflow، Approval، Verification و Audit می‌سازد.

> این Repository فقط برای نمایش عمومی پروژه است. سورس Production و جزئیات حساس زیرساخت در Repository خصوصی جداگانه نگهداری می‌شوند.

## قابلیت‌های اصلی

- معماری Multi-site / Multi-datacenter
- یکپارچه‌سازی با Zabbix
- جمع‌آوری Inventory و Health از VMware vCenter
- Active Diagnostics با ICMP و TCP
- Health Scoring و Evidence Normalization
- Incident Correlation
- Root-cause Classification با Confidence
- Playbook و Remediation Queue
- Human-in-the-loop برای تغییرات حساس
- Post-action Verification
- Audit History
- Telegram Control فارسی / انگلیسی
- Web Dashboard و Fleet Reporting
- AI Operator برای تحلیل Grounded
- Safe Degraded Mode در زمان مشکل Provider

## اصل طراحی

Zabbix و vCenter می‌گویند چه اتفاقی افتاده؛ OpsPilot تلاش می‌کند مشخص کند **چرا ممکن است اتفاق افتاده باشد، چه چیزی باید بعدی بررسی شود، چه اقدامی نیاز به تأیید انسانی دارد و آیا بعد از اقدام سیستم واقعاً بازیابی شده است یا نه**.

## نسخه

نسخه Showcase فعلی: **v4.1.3 — Bilingual Context Final**

## هدف این Repo

این Repo برای رزومه، GitHub، LinkedIn و مصاحبه فنی ساخته شده است و عمداً Secret، IP داخلی، Credential، توپولوژی واقعی شرکت، لاگ Production و سورس حساس را شامل نمی‌شود.