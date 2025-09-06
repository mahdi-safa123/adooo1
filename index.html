<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>متجر أدو | باقات ورد</title>
<style>
  body { font-family: "Tajawal", sans-serif; background:#fff6fb; margin:0; padding:0; color:#3c3c3c; }
  header { background:#f8cfe1; padding:20px; text-align:center; font-size:2em; font-weight:bold; color:#d63384; }
  .container { display:flex; flex-wrap:wrap; justify-content:center; padding:20px; }
  .card { background:#ffe9f3; border-radius:15px; margin:15px; width:250px; padding:15px; box-shadow:0 4px 6px rgba(0,0,0,0.1); text-align:center; }
  .card img { width:100%; border-radius:10px; }
  .card h3 { margin:10px 0 5px; }
  .card p { margin:5px 0; }
  .card input[type="number"] { width:60px; padding:5px; margin:10px 0; border-radius:5px; border:1px solid #d63384; text-align:center; }
  .card button { background:#d63384; color:white; border:none; padding:10px 15px; border-radius:10px; cursor:pointer; font-weight:bold; }
  .card button:hover { background:#b02a70; }
  .cart, .customer-form { background:#ffe9f3; padding:15px; border-radius:15px; margin:20px auto; max-width:500px; box-shadow:0 4px 6px rgba(0,0,0,0.1); text-align:center; }
  .cart h2, .customer-form h2 { color:#d63384; margin-bottom:15px; }
  .customer-form input, .customer-form textarea { width:90%; padding:10px; margin:10px 0; border-radius:5px; border:1px solid #d63384; }
  .customer-form button { background:#d63384; color:white; border:none; padding:10px 20px; border-radius:10px; cursor:pointer; font-weight:bold; }
  .customer-form button:hover { background:#b02a70; }
  footer { background:#f8cfe1; padding:20px; text-align:center; margin-top:30px; }
  footer a { color:#d63384; text-decoration:none; font-weight:bold; }
</style>
</head>
<body>

<header>متجر أدو | باقات ورد</header>

<div class="container">
  <div class="card">
    <img src="https://i.imgur.com/3dX1cZr.jpg" alt="باقة الحب الأحمر">
    <h3>باقة الحب الأحمر</h3>
    <p>سعر الوردة: 2000 دينار</p>
    <p>اختر عدد الورود:</p>
    <input type="number" min="1" value="1" id="rose1">
    <button onclick="addToCart('باقة الحب الأحمر', 2000, document.getElementById('rose1').value)">أضف إلى السلة</button>
  </div>

  <div class="card">
    <img src="https://i.imgur.com/6Iej2c3.jpg" alt="باقة الوردي الرائع">
    <h3>باقة الوردي الرائع</h3>
    <p>سعر الوردة: 2000 دينار</p>
    <p>اختر عدد الورود:</p>
    <input type="number" min="1" value="1" id="rose2">
    <button onclick="addToCart('باقة الوردي الرائع', 2000, document.getElementById('rose2').value)">أضف إلى السلة</button>
  </div>

  <div class="card">
    <img src="https://i.imgur.com/kT7S8T5.jpg" alt="باقة مختلطة الألوان">
    <h3>باقة مختلطة الألوان</h3>
    <p>سعر الوردة: 2000 دينار</p>
    <p>اختر عدد الورود:</p>
    <input type="number" min="1" value="1" id="rose3">
    <button onclick="addToCart('باقة مختلطة الألوان', 2000, document.getElementById('rose3').value)">أضف إلى السلة</button>
  </div>
</div>

<div class="cart" id="cart">
  <h2>عربة التسوق</h2>
  <p>لم يتم إضافة أي منتج بعد.</p>
  <p id="total"></p>
</div>

<div class="customer-form">
  <h2>بيانات الزبون</h2>
  <form id="checkoutForm" action="https://formspree.io/f/mayvokzy" method="POST" target="_blank">
    <input type="text" name="name" placeholder="الاسم الكامل" required>
    <input type="email" name="email" placeholder="البريد الإلكتروني" required>
    <textarea name="note" placeholder="ملاحظات أو عنوان التوصيل" required></textarea>
    <input type="hidden" name="cartDetails" id="cartDetailsInput">
    <button type="submit" onclick="prepareCheckout()">الدفع عبر PayPal / بطاقة</button>
  </form>
</div>

<footer>
  <p>للدعم والاستفسار: <a href="mailto:mahdiaaaccc@gmail.com">mahdiaaaccc@gmail.com</a></p>
</footer>

<script>
let cartItems = [];

function addToCart(name, price, quantity) {
  quantity = parseInt(quantity);
  if(quantity <= 0) return;
  cartItems.push({name, price, quantity});
  updateCart();
}

function updateCart() {
  const cartDiv = document.getElementById('cart');
  let html = '';
  let totalPrice = 0;
  if(cartItems.length === 0){
    html = '<p>لم يتم إضافة أي منتج بعد.</p>';
  } else {
    cartItems.forEach(item => {
      html += `<p>${item.name} - ${item.quantity} وردة = ${item.price * item.quantity} دينار</p>`;
      totalPrice += item.price * item.quantity;
    });
  }
  document.getElementById('total').innerText = totalPrice > 0 ? `المجموع الكلي: ${totalPrice} دينار` : '';
  cartDiv.innerHTML = '<h2>عربة التسوق</h2>' + html + '<p id="total">'+ (totalPrice > 0 ? `المجموع الكلي: ${totalPrice} دينار` : '') +'</p>';
}

function prepareCheckout() {
  if(cartItems.length === 0) {
    alert('لم تقم بإضافة أي منتج!');
    event.preventDefault();
    return;
  }
  const details = cartItems.map(i => `${i.name} - ${i.quantity} وردة = ${i.price*i.quantity} دينار`).join('\n');
  document.getElementById('cartDetailsInput').value = details;
  alert('سيتم إرسال بياناتك إلى بريدك الإلكتروني وسيتم تحويلك إلى PayPal للدفع.');
}
</script>

</body>
</html>
