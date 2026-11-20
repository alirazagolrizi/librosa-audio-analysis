# Audio Waveform & Spectrogram Analysis | تحلیل شکل موج و طیف‌نگار صوت

**Proposed GitHub repository name:** `librosa-audio-analysis`

## Purpose | هدف
Load user-supplied audio with librosa, plot waveform/spectrogram, and print spectral features.

تحلیل شکل موج و طیف‌نگار صوت: این مخزن یک نمونهٔ مستقل مبتنی بر یک سلول کد استخراج‌شده است؛ برای شرح کوتاه فارسی، هدف پروژه را در عنوان بالا ببینید.

## Prerequisites | پیش‌نیازها
Python 3.9+; librosa; matplotlib; Jupyter.

## Install | نصب
Use Python 3 and Jupyter. Install the packages listed in `requirements.txt` with:

```bash
python -m pip install -r requirements.txt
```

پایتون و Jupyter را نصب کنید؛ سپس وابستگی‌های `requirements.txt` را با دستور بالا نصب کنید. برخی وابستگی‌ها اختیاری یا وابسته به سیستم‌عامل/سخت‌افزار هستند.

## Run | اجرا
Open notebook.ipynb in Jupyter. Call the provided function with an available audio path.

فایل `notebook.ipynb` را در Jupyter باز کنید و یک سلول کد آن را اجرا کنید. ورودی‌ها و مسیرهای لازم در بخش محدودیت‌ها آمده‌اند.

## Limitations and input assets | محدودیت‌ها و ورودی‌ها
Requires audio files passed to show_wave_and_spectrogram; no audio assets are included. Supported formats depend on the local audio backend.

این نمونه‌ها صرفاً آموزشی‌اند و اجرای انتها‌به‌انتها در این بسته تضمین یا تأیید نشده است. ورودی/دادهٔ تخصصی یا سخت‌افزار در صورت نیاز باید جداگانه فراهم شود.
