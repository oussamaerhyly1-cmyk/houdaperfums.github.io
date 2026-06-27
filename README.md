<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>متجر العطور الفاخرة | أصالة وفخامة</title>
    <style>
        /* التنسيق العام للموقع */
        * { box-sizing: border-box; margin: 0; padding: 0; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
        body { background-color: #fcfbf7; color: #2c2520; }
        
        /* الهيدر (رأس الصفحة) */
        header { background-color: #1a1512; color: #fff; padding: 40px 20px; text-align: center; border-bottom: 3px solid #d4af37; }
        header h1 { font-size: 32px; color: #d4af37; font-weight: bold; }
        header p { font-size: 16px; margin-top: 10px; color: #ccc; font-style: italic; }

        /* حاوية عرض المنتجات */
        .container { max-width: 1200px; margin: 40px auto; padding: 0 20px; }
        
        /* نظام الشبكة لتوزيع العطور بشكل متجاوب */
        .products-grid { 
            display: grid; 
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); 
            gap: 30px; 
        }
        
        /* كارت العطر الشخصي */
        .card { background: #fff; border: 1px solid #e6dfd5; border-radius: 12px; padding: 25px; text-align: center; box-shadow: 0 4px 10px rgba(0,0,0,0.03); transition: transform 0.3s; }
        .card:hover { transform: translateY(-5px); }
        
        /* أيقونة مؤقتة بديلة للصور */
        .card .emoji { font-size: 60px; margin-bottom: 15px; display: block; }
        
        /* تفاصيل العطر */
        .card h3 { font-size: 22px; color: #1a1512; margin-bottom: 10px; }
        .card .description { font-size: 14px; color: #666; margin-bottom: 20px; height: 45px; line-height: 1.5; }
        .card .price { font-size: 20px; font-weight: bold; color: #8c7853; margin-bottom: 20px; }
        
        /* زر الطلب عبر الواتساب */
        .btn-buy { display: inline-block; background-color: #d4af37; color: #1a1512; text-decoration: none; padding: 12px 25px; border-radius: 25px; font-weight: bold; transition: background 0.3s; width: 100%; }
        .btn-buy:hover { background-color: #1a1512; color: #d4af37; border: 1px solid #d4af37; }

        /* الفوتر (أسفل الصفحة) */
        footer { background-color: #1a1512; color: #888; text-align: center; padding: 25px; margin-top: 60px; font-size: 13px; border-top: 1px solid #d4af37; }
    </style>
</head>
<body>

    <header>
        <h1>قصر العطور الفاخرة</h1>
        <p>نجمع لك أندر النوتات العطرية لتناسب ذوقك الرفيع</p>
    </header>

    <div class="container">
        <div class="products-grid">
            
            <div class="card">
                <span class="emoji">✨</span>
                <h3>عطر العود الملكي</h3>
                <p class="description">مزيج ساحر من العود الكمبودي الفاخر مع لمسات دافئة من الورد الطائفي الصافي.</p>
                <p class="price">350 ريال سعودي</p>
                <a href="https://wa.me/123456789?text=أهلاً،%20أود%20طلب%20عطر%20العود%20الملكي" target="_blank" class="btn-buy">اطلب عبر الواتساب</a>
            </div>

            <div class="card">
                <span class="emoji">🌸</span>
                <h3>مسك الفانيلا النقي</h3>
                <p class="description">عطر يومي ناعم يجمع بين نقاء المسك الأبيض وحلاوة فانيلا مدغشقر الهادئة.</p>
                <p class="price">220 ريال سعودي</p>
                <a href="https://wa.me/123456789?text=أهلاً،%20أود%20طلب%20عطر%20مسك%20الفانيلا" target="_blank" class="btn-buy">اطلب عبر الواتساب</a>
            </div>

            <div class="card">
                <span class="emoji">👑</span>
                <h3>عطر سحر الشرق</h3>
                <p class="description">عطر رسمي غامض ومثير يتكون من العنبر النادر، التوابل الدافئة، والجلد الفاخر.</p>
                <p class="price">410 ريال سعودي</p>
                <a href="https://wa.me/123456789?text=أهلاً،%20أود%20طلب%20عطر%20سحر%20الشرق" target="_blank" class="btn-buy">اطلب عبر الواتساب</a>
            </div>

        </div>
    </div>

    <footer>
        <p>&copy; 2026 قصر العطور الفاخرة. جميع الحقوق محفوظة. مستضاف عبر GitHub Pages.</p>
    </footer>

</body>
</html># houdaperfums.github.io
