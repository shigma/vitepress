# پیوندهای قبلی و بعدی {#prev-next-links}

شما می‌توانید متن و پیوند برای صفحات قبلی و بعدی را سفارشی‌سازی کنید (نمایش داده شده در پایین صفحه مستندات). این مفید است اگر می‌خواهید متن دیگری را در این قسمت نمایش دهید که با آنچه در نوار کناری دارید، متفاوت باشد. همچنین، ممکن است مفید باشد که فوتر را غیرفعال کنید یا به یک صفحه لینک کنید که در نوار کناری شما وجود ندارد.

## prev

- نوع: `string | false | { text?: string; link?: string }`

- جزئیات:

  مشخص می‌کند متن/لینکی که برای لینک به صفحه قبلی نمایش داده خواهد شد. اگر این را در frontmatter تنظیم نکنید، متن/لینک از تنظیمات نوار کناری استخراج خواهد شد.

- مثال‌ها:

  - برای فقط سفارشی‌سازی متن:

    ```yaml
    ---
    prev: 'شروع کنید | مارک‌داون'
    ---
    ```

  - برای سفارشی‌سازی هم متن و هم لینک:

    ```yaml
    ---
    prev:
      text: 'مارک‌داون'
      link: '/guide/markdown'
    ---
    ```

  - برای مخفی کردن صفحه قبلی:

    ```yaml
    ---
    prev: false
    ---
    ```

## next

مشابه `prev` اما برای صفحه بعدی.
