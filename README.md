# 🤖 workflows-n8n-tutorial | n8n Automation Tutorials and Practice

**آموزش و تمرین اتوماسیون با n8n (فارسی و انگلیسی)**

[![GitHub license](https://img.shields.io/github/license/shahramsamar/workflows-n8n?style=for-the-badge)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/shahramsamar/workflows-n8n?style=for-the-badge)](https://github.com/shahramsamar/workflows-n8n/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/shahramsamar/workflows-n8n/network/members?style=for-the-badge)](https://github.com/shahramsamar/workflows-n8n/network/members)

---

## درباره این ریپازیتوری | About This Repository

این ریپازیتوری مجموعه‌ای از **Workflowهای (گردش‌کارهای) نمونه** برای پلتفرم اتوماسیون **n8n** است. هدف اصلی، فراهم کردن یک **محیط آموزشی و تمرینی عملی** برای یادگیری n8n و ساخت اتوماسیون‌های قدرتمند **بدون نیاز به کدنویسی** است.

This repository is a collection of **example workflows** for the **n8n** automation platform. The main goal is to provide a **practical learning and practice environment** for mastering n8n and building powerful **no-code** automations. 🚀

---

## ساختار پوشه‌ها | Folder Structure

فایل‌های Workflow به صورت JSON ذخیره شده‌اند و بر اساس سطح دشواری و کاربرد دسته‌بندی شده‌اند:

Workflows are stored as JSON files, categorized by difficulty level and primary use case for your convenience:

| پوشه (Folder) | سطح سختی (Difficulty) | کاربرد اصلی (Primary Use Case) |
| :--- | :--- | :--- |
| **`01-Beginner-Essentials`** | آسان / Easy | برای شروع و آشنایی با مفاهیم پایه‌ای n8n و اولین ورک‌فلوها (مثل مدیریت داده ساده). |
| **`02-Intermediate-Logic`** | متوسط / Medium | پروژه‌های کمی پیچیده‌تر با استفاده از منطق‌های شرطی، حلقه‌ها و پردازش داده‌های JSON. |
| **`03-Advanced-AI-Integrations`** | پیشرفته / Advanced | مثال‌هایی برای ادغام با هوش مصنوعی (LLMs)، Agentها و اتوماسیون‌های داده‌محور حرفه‌ای. |
| **`99-Personal-Custom-Workflows`** | متغیر / Variable | ورک‌فلوهای خاص و شخصی‌سازی شده برای حل مسائل منحصر به فرد یا پروژه‌های شخصی. |

---

## چگونه شروع کنیم؟ | How to Get Started

### ۱. نصب و راه‌اندازی n8n | 1. Installation and Setup
قبل از شروع، باید n8n را نصب کنید. ساده‌ترین راه استفاده از نسخه ابری n8n یا نصب **Self-Host** از طریق **Docker** است.

You need to have n8n running. The easiest ways are using the n8n Cloud version or installing a **Self-Host** instance via **Docker**.

### ۲. وارد کردن Workflowها | 2. Importing Workflows
برای استفاده از هر یک از ورک‌فلوهای موجود:
1.  به پوشه مورد نظر بروید و فایل **JSON** مربوط به Workflow را دانلود کنید.
2.  در محیط n8n خود، روی آیکون **"New"** و سپس **"Import Workflow"** کلیک کنید.
3.  فایل JSON را بارگذاری کرده و دکمه **"Import"** را بزنید.

To use any of the workflows in this repo:
1.  Navigate to the relevant folder and download the Workflow **JSON** file.
2.  In your n8n interface, click the **"New"** icon and then **"Import Workflow"**.
3.  Upload the JSON file and click **"Import"**.

### ۳. تنظیم Credentials | 3. Setting up Credentials
تقریباً تمام ورک‌فلوها نیاز به **Credentials** (اطلاعات احراز هویت، مانند API Key) دارند. پس از وارد کردن Workflow، حتماً روی نودهایی که نیاز به تنظیمات دارند، کلیک کرده و Credentials خود را وارد یا تعریف نمایید.

Almost all workflows require **Credentials** (like API Keys). After importing, make sure to click on any nodes that need configuration and enter or define your required Credentials to establish the external connections.

---

## مشارکت | Contribution
از هر گونه مشارکت شما برای بهبود این ریپازیتوری استقبال می‌کنیم! لطفاً با ارسال یک **Pull Request** ورک‌فلوهای جدید، اصلاح شده، یا توضیحات بهتر را به این مجموعه اضافه کنید.

We welcome contributions to improve this repository! Please feel free to submit a **Pull Request** with new, improved workflows, or better documentation.

---

## مجوز | License
این پروژه تحت مجوز **MIT** منتشر شده است. برای جزئیات بیشتر به فایل [LICENSE](LICENSE) مراجعه کنید.

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

---

**Built with 🧡 for the n8n community**
