[index.html](https://github.com/user-attachments/files/27414475/index.html)
<!DOCTYPE html>
<html lang="ar" dir="rtl">
    
<div class="top-announcement">
    <div class="container">
        <div class="ticker">
            <span>🔥 خصومات تصل لـ 50% على تشكيلة الصيف</span>
            <span>🚚 شحن مجاني لأي طلب فوق 1000 جنيه</span>
            <span>💻 وصل حديثاً: كروت شاشة RTX فئة 50</span>
        </div>
    </div>
</div>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SUN STORE | المتجر الشامل</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <nav class="navbar">
            <div class="container">
                <div class="logo">SUN <span>STORE</span></div>
                <ul class="nav-links">
                    <li><a href="#home">الرئيسية</a></li>
                    <li><a href="#products">المنتجات</a></li>
                    <li><a href="#about">من نحن</a></li>
                    <li><a href="#services">خدماتنا</a></li>
                    <li><a href="#pricing">الباقات</a></li>
                    <li><a href="#contact">اتصل بنا</a></li>
                </ul>
                <div class="nav-icons">
                    <i class="fas fa-search"></i>
                    <div class="cart-btn" onclick="toggleCart()">
                        <i class="fas fa-shopping-cart"></i>
                        <span id="cart-count">0</span>
                    </div>
                </div>
            </div>
        </nav>
    </header>

    <section id="home" class="hero">
        <div class="hero-content">
            <h1>عالم الموضة والتقنية في مكان واحد</h1>
            <p>استمتع بأفضل العروض الحصرية على التيشرتات وأحدث قطع الهاردوير لعام 2026.</p>
            <div class="hero-btns">
                <a href="#products" class="btn primary">تسوق الآن</a>
                <a href="#about" class="btn secondary">تعرف علينا</a>
            </div>
        </div>
    </section>

    <section class="features">
        <div class="container grid-4">
            <div class="feature-item">
                <i class="fas fa-truck"></i>
                <h3>شحن سريع</h3>
                <p>توصيل لجميع محافظات مصر خلال 48 ساعة.</p>
            </div>
            <div class="feature-item">
                <i class="fas fa-shield-alt"></i>
                <h3>ضمان حقيقي</h3>
                <p>ضمان استبدال واسترجاع لمدة 14 يوم.</p>
            </div>
            <div class="feature-item">
                <i class="fas fa-headset"></i>
                <h3>دعم 24/7</h3>
                <p>فريقنا معك دائماً للإجابة على استفساراتك.</p>
            </div>
            <div class="feature-item">
                <i class="fas fa-credit-card"></i>
                <h3>دفع آمن</h3>
                <p>طرق دفع متعددة تناسب الجميع.</p>
            </div>
        </div>
    </section>

    <section id="products" class="products-section">
        <h2 class="section-title">أحدث المنتجات</h2>
        <div class="container grid-4" id="products-container">
            <div class="product-card">
                <div class="badge">جديد</div>
                <img src="https://via.placeholder.com/250" alt="منتج">
                <h3>تيشرت صيفي مميز</h3>
                <div class="price">350 ج.م</div>
                <button class="add-to-cart">أضف للسلة</button>
            </div>
            <div class="product-card">
                <img src="https://via.placeholder.com/250" alt="منتج">
                <h3>بنطلون جينز سليم</h3>
                <div class="price">550 ج.م</div>
                <button class="add-to-cart">أضف للسلة</button>
            </div>
            <div class="product-card">
                <img src="https://via.placeholder.com/250" alt="منتج">
                <h3>كارت شاشة RTX 5090</h3>
                <div class="price">اتصل للسعر</div>
                <button class="add-to-cart">أضف للسلة</button>
            </div>
            <div class="product-card">
                <img src="https://via.placeholder.com/250" alt="منتج">
                <h3>ساعة ذكية Ultra</h3>
                <div class="price">1200 ج.م</div>
                <button class="add-to-cart">أضف للسلة</button>
            </div>
        </div>
    </section>

    <section id="about" class="about-section">
        <div class="container grid-2">
            <div class="about-img">
                <img src="https://via.placeholder.com/500x300" alt="About Sun Store">
            </div>
            <div class="about-text">
                <h2>لماذا SUN STORE؟</h2>
                <p>بدأنا كفكرة بسيطة لتوفير احتياجات الشباب المصري من ملابس وهاردوير بأفضل جودة وأقل سعر.</p>
                <ul>
                    <li><i class="fas fa-check"></i> خامات قطنية 100%</li>
                    <li><i class="fas fa-check"></i> هاردوير أصلي بضمان محلي</li>
                    <li><i class="fas fa-check"></i> دعم فني تقني متخصص</li>
                </ul>
            </div>
        </div>
    </section>

    <section id="pricing" class="pricing-section">
        <h2 class="section-title">باقات العضوية</h2>
        <div class="container grid-3">
            <div class="price-box">
                <h3>الباقة العادية</h3>
                <div class="amt">مجاناً</div>
                <ul>
                    <li>خصومات دورية</li>
                    <li>نشرة أخبار المنتجات</li>
                    <li class="off">شحن مجاني</li>
                </ul>
                <button class="btn">اشترك الآن</button>
            </div>
            <div class="price-box featured">
                <h3>الباقة الذهبية</h3>
                <div class="amt">200 ج.م/شهر</div>
                <ul>
                    <li>خصم 10% دائم</li>
                    <li>شحن مجاني لأي مكان</li>
                    <li>هدايا في أعياد الميلاد</li>
                </ul>
                <button class="btn">اشترك الآن</button>
            </div>
            <div class="price-box">
                <h3>باقة الـ VIP</h3>
                <div class="amt">500 ج.م/شهر</div>
                <ul>
                    <li>خصم 20% دائم</li>
                    <li>أولوية في القطع النادرة</li>
                    <li>معاينة المنتجات قبل صدورها</li>
                </ul>
                <button class="btn">اشترك الآن</button>
            </div>
        </div>
    </section>

    <section class="team">
        <h2 class="section-title">مؤسسو المتجر</h2>
        <div class="container grid-3">
            <div class="member">
                <img src="https://via.placeholder.com/150" alt="Member">
                <h4>محمد سيد</h4>
                <p>المؤسس والمبرمج الرئيسي</p>
            </div>
            </div>
    </section>

    <section id="contact" class="contact-section">
        <div class="container">
            <h2 class="section-title">تواصل معنا</h2>
            <div class="grid-2">
                <div class="contact-info">
                    <div class="info-box">
                        <i class="fas fa-map-marker-alt"></i>
                        <p>القاهرة، مصر</p>
                    </div>
                    <div class="info-box">
                        <i class="fas fa-phone"></i>
                        <p>+20 123 456 789</p>
                    </div>
                    <div class="info-box">
                        <i class="fas fa-envelope"></i>
                        <p>info@sunstore.com</p>
                    </div>
                </div>
                <form class="contact-form">
                    <input type="text" placeholder="الاسم بالكامل" required>
                    <input type="email" placeholder="البريد الإلكتروني" required>
                    <textarea placeholder="رسالتك هنا..." rows="5"></textarea>
                    <button type="submit" class="btn primary">إرسال الرسالة</button>
                </form>
            </div>
        </div>
    </section>

    <div id="cartModal" class="cart-modal">
        <div class="cart-content">
            <span class="close" onclick="toggleCart()">&times;</span>
            <h2>سلتك الحالية</h2>
            <div id="cart-items">
                </div>
            <hr>
            <div class="total">الإجمالي: <span id="totalPrice">0</span> جنيه</div>
            <button class="checkout-btn">تأكيد الطلب</button>
        </div>
    </div>

    <footer class="main-footer">
        <div class="container grid-4">
            <div class="footer-about">
                <div class="logo">SUN <span>STORE</span></div>
                <p>وجهتك الأولى للتسوق الإلكتروني في مصر، نجمع بين الأناقة والقوة التقنية.</p>
            </div>
            <div class="footer-links">
                <h4>روابط سريعة</h4>
                <ul>
                    <li><a href="#">سياسة الخصوصية</a></li>
                    <li><a href="#">الشروط والأحكام</a></li>
                    <li><a href="#">الأسئلة الشائعة</a></li>
                </ul>
            </div>
            <div class="footer-social">
                <h4>تابعنا على</h4>
                <div class="social-icons">
                    <a href="#"><i class="fab fa-facebook"></i></a>
                    <a href="#"><i class="fab fa-instagram"></i></a>
                    <a href="#"><i class="fab fa-tiktok"></i></a>
                </div>
            </div>
            <div class="footer-newsletter">
                <h4>اشترك في جديدنا</h4>
                <input type="email" placeholder="ايميلك هنا">
                <button class="btn secondary">اشترك</button>
            </div>
        </div>
        <div class="copyright">
            <p>&copy; 2026 جميع الحقوق محفوظة لـ SUN STORE - تطوير محمد سيد</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
<aside class="filter-sidebar">
    <h3>تصفية المنتجات</h3>
    <div class="filter-group">
        <h4>القسم</h4>
        <label><input type="checkbox" name="cat" value="tshirt"> تيشرتات</label>
        <label><input type="checkbox" name="cat" value="pants"> بنطلونات</label>
        <label><input type="checkbox" name="cat" value="gpu"> هاردوير</label>
    </div>
    <div class="filter-group">
        <h4>السعر</h4>
        <input type="range" min="100" max="50000" id="priceRange">
        <div class="price-labels">
            <span>100 ج.م</span>
            <span>50,000 ج.م</span>
        </div>
    </div>
</aside>
<section class="testimonials">
    <div class="container">
        <h2 class="section-title">قالوا عن SUN STORE</h2>
        <div class="grid-3">
            <div class="testimonial-card">
                <div class="stars">⭐⭐⭐⭐⭐</div>
                <p>"أفضل خامة تيشرتات اشتريتها في مصر، والتوصيل كان سريع جداً."</p>
                <div class="user-info">
                    <img src="https://ui-avatars.com/api/?name=Ahmed+Ali" alt="User">
                    <span>أحمد علي</span>
                </div>
            </div>
            </div>
    </div>
</section>
<section class="faq">
    <div class="container">
        <h2 class="section-title">الأسئلة الشائعة</h2>
        <div class="accordion">
            <div class="accordion-item">
                <div class="accordion-header" onclick="toggleFAQ(this)">
                    <span>إزاي أقدر أختار المقاس المظبوط؟</span>
                    <i class="fas fa-chevron-down"></i>
                </div>
                <div class="accordion-body">
                    <p>عندنا جدول مقاسات دقيق لكل منتج في وصف الصفحة، وتقدر تكلمنا واتساب نساعدك.</p>
                </div>
            </div>
            </div>
    </div>
</section>
<a href="https://wa.me/20123456789" class="whatsapp-float" target="_blank">
    <i class="fab fa-whatsapp"></i>
    <span class="tooltip">محتاج مساعدة؟ تواصل معنا</span>
</a>
<div id="skeleton-container" class="grid-4">
    <div class="skeleton-card">
        <div class="skeleton-img"></div>
        <div class="skeleton-text"></div>
        <div class="skeleton-text short"></div>
    </div>
    </div>
    <section class="flash-sale">
    <div class="container">
        <div class="sale-banner">
            <div class="sale-text">
                <h2>عروض الصيف الكبرى! ☀️</h2>
                <p>خصم يصل إلى 60% ينتهي خلال:</p>
                <div id="countdown" class="timer">
                    <div><span id="days">00</span>يوم</div>
                    <div><span id="hours">00</span>ساعة</div>
                    <div><span id="minutes">00</span>دقيقة</div>
                </div>
            </div>
            <div class="sale-image">
                <img src="https://via.placeholder.com/300x200?text=Discount+Offer" alt="Sale">
            </div>
        </div>
    </div>
</section>
<button class="quick-view-btn" onclick="openQuickView(1)">
    <i class="fas fa-eye"></i> معاينة سريعة
</button>

<div id="quickViewModal" class="modal">
    <div class="modal-content">
        <span class="close" onclick="closeModal()">&times;</span>
        <div class="product-details-grid">
            <div class="prod-img">
                <img id="modalImg" src="" alt="">
            </div>
            <div class="prod-info">
                <h2 id="modalTitle">اسم المنتج</h2>
                <p id="modalPrice" class="price"></p>
                <div class="sizes">
                    <span>المقاس:</span>
                    <button>S</button><button>M</button><button>L</button><button>XL</button>
                </div>
                <button class="btn-main">إضافة للسلة</button>
            </div>
        </div>
    </div>
</div>
<button class="quick-view-btn" onclick="openQuickView(1)">
    <i class="fas fa-eye"></i> معاينة سريعة
</button>

<div id="quickViewModal" class="modal">
    <div class="modal-content">
        <span class="close" onclick="closeModal()">&times;</span>
        <div class="product-details-grid">
            <div class="prod-img">
                <img id="modalImg" src="" alt="">
            </div>
            <div class="prod-info">
                <h2 id="modalTitle">اسم المنتج</h2>
                <p id="modalPrice" class="price"></p>
                <div class="sizes">
                    <span>المقاس:</span>
                    <button>S</button><button>M</button><button>L</button><button>XL</button>
                </div>
                <button class="btn-main">إضافة للسلة</button>
            </div>
        </div>
    </div>
</div>
<div class="chat-widget" id="chatWidget">
    <div class="chat-header" onclick="toggleChatBody()">
        <span>تحدث معنا مباشرة</span>
        <i class="fas fa-comments"></i>
    </div>
    <div class="chat-body" id="chatBody">
        <div class="msg bot">أهلاً بك في SUN STORE! كيف يمكنني مساعدتك؟</div>
        <div class="chat-input">
            <input type="text" placeholder="اكتب رسالتك...">
            <button><i class="fas fa-paper-plane"></i></button>
        </div>
    </div>
</div>
