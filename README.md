# SUMIT-KIRANA-STORES-
Online kirana store 
<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#087443">
<title>SUMIT KIRANA STORE | ऑनलाइन किराना</title>
<style>
:root{--green:#087443;--green2:#0ca65c;--light:#f2fbf5;--ink:#17231c;--muted:#647268;--orange:#ff9d2e;--line:#e1eee5}
*{box-sizing:border-box}body{margin:0;font-family:system-ui,-apple-system,"Noto Sans Devanagari",Arial,sans-serif;background:#f6f8f6;color:var(--ink)}
header{background:linear-gradient(120deg,#065b35,#0ca65c);color:white;padding:18px 16px 20px;border-radius:0 0 24px 24px}
.top{max-width:1000px;margin:auto;display:flex;justify-content:space-between;align-items:center;gap:12px}.brand{font-weight:900;font-size:clamp(18px,4vw,25px);letter-spacing:.2px}.sub{font-size:12px;opacity:.9;margin-top:3px}.pill{background:#ffffff20;border:1px solid #ffffff45;padding:8px 11px;border-radius:999px;font-size:12px;white-space:nowrap}
.hero{max-width:1000px;margin:18px auto 0;background:#ffffff15;border:1px solid #ffffff35;border-radius:18px;padding:17px}.hero h1{font-size:clamp(23px,5vw,34px);line-height:1.2;margin:0 0 8px}.hero p{margin:0;color:#e9fff0;font-size:14px}.hero .tag{display:inline-block;background:#fff;color:#087443;font-weight:800;border-radius:7px;padding:5px 9px;margin-bottom:10px;font-size:12px}
main{max-width:1000px;margin:auto;padding:16px 14px 95px}.benefits{display:grid;grid-template-columns:repeat(3,1fr);gap:9px;margin:0 0 20px}.benefit{background:white;border:1px solid var(--line);border-radius:13px;padding:12px 8px;text-align:center;font-size:12px;font-weight:700}.benefit span{display:block;font-size:21px;margin-bottom:4px}
.section-title{display:flex;align-items:center;justify-content:space-between;gap:12px;margin:22px 0 12px}.section-title h2{font-size:20px;margin:0}.section-title small{color:var(--muted)}
.tools{display:flex;gap:8px;margin-bottom:13px}.tools input,.tools select{min-width:0;border:1px solid #d7e5db;border-radius:12px;padding:12px;background:white;font:inherit}.tools input{flex:1}
.products{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:12px}.card{background:white;border:1px solid var(--line);border-radius:16px;overflow:hidden;box-shadow:0 3px 12px #12351a08}.product-art{height:125px;background:linear-gradient(135deg,#e4f8e8,#fff3dc);display:grid;place-items:center;font-size:58px}.card-body{padding:12px}.card h3{margin:0 0 5px;font-size:16px}.desc{color:var(--muted);font-size:12px}.price{font-size:18px;font-weight:900;color:var(--green);margin:8px 0 10px}.price small{font-size:11px;font-weight:500;color:var(--muted)}.add{width:100%;border:0;border-radius:10px;background:var(--green);color:white;font-weight:800;padding:11px;font:inherit;font-size:14px;cursor:pointer}.add:active,.primary:active{transform:scale(.98)}
.panel{background:white;border:1px solid var(--line);border-radius:17px;padding:15px;margin-top:18px}.cart-row{display:flex;align-items:center;gap:10px;padding:10px 0;border-bottom:1px solid #edf2ee}.cart-row:last-child{border-bottom:0}.cart-emoji{font-size:28px}.cart-info{flex:1;min-width:0}.cart-info strong{display:block}.cart-info small{color:var(--muted)}.qty{display:flex;align-items:center;gap:9px}.qty button{border:1px solid #d7e5db;background:#f7fbf8;border-radius:8px;width:30px;height:30px;font-size:18px;color:var(--green)}
.totals{border-top:1px dashed #d5e3d8;margin-top:10px;padding-top:10px}.total-line{display:flex;justify-content:space-between;margin:7px 0}.grand{font-size:20px;font-weight:900;color:var(--green)}.primary,.secondary{display:block;width:100%;border:0;border-radius:12px;padding:13px 12px;font:inherit;font-weight:800;cursor:pointer;margin-top:10px}.primary{background:#16a34a;color:white}.secondary{background:#fff5e8;color:#854d0e;border:1px solid #ffdfb4}.hint{font-size:12px;line-height:1.6;color:var(--muted)}
.contact-grid{display:grid;grid-template-columns:1fr;gap:10px}.contact-item{background:var(--light);border-radius:12px;padding:12px;font-size:14px}.contact-item strong{display:block;margin-bottom:4px}.footer{background:#073e27;color:#eaffef;padding:20px 16px;text-align:center;font-size:12px}.sticky{position:fixed;bottom:0;left:0;right:0;background:#ffffffee;backdrop-filter:blur(10px);padding:10px 14px calc(10px + env(safe-area-inset-bottom));border-top:1px solid var(--line);display:flex;justify-content:center;z-index:5}.sticky button{max-width:1000px;width:100%;background:#087443;color:white;border:0;border-radius:13px;padding:13px;font:inherit;font-weight:900}
.empty{text-align:center;color:var(--muted);padding:20px}.badge{font-size:11px;background:#e8f8ed;color:#087443;padding:4px 7px;border-radius:999px;font-weight:800}
@media(min-width:600px){.products{grid-template-columns:repeat(3,minmax(0,1fr))}.product-art{height:155px}.contact-grid{grid-template-columns:1fr 1fr}.benefits{gap:14px}.benefit{font-size:14px;padding:16px}}
@media(min-width:850px){.products{grid-template-columns:repeat(4,minmax(0,1fr))}.product-art{height:165px}main{padding-top:22px}}
</style>
</head>
<body>
<header>
  <div class="top">
    <div><div class="brand">🛒 SUMIT KIRANA STORE</div><div class="sub">हर घर की जरूरत, अब आपके मोबाइल पर</div></div>
    <div class="pill">🏠 होम डिलीवरी</div>
  </div>
  <div class="hero">
    <span class="tag">ताज़ा सामान • उचित कीमत</span>
    <h1>आपका रोज़मर्रा का सामान,<br>अब घर बैठे मँगाएँ!</h1>
    <p>सामान चुनें, मात्रा तय करें और WhatsApp पर अपना ऑर्डर भेजें।</p>
  </div>
</header>
<main>
  <div class="benefits">
    <div class="benefit"><span>🌿</span>रोज़मर्रा का सामान</div>
    <div class="benefit"><span>💰</span>साफ़ कीमतें</div>
    <div class="benefit"><span>🛵</span>होम डिलीवरी</div>
  </div>
  <section id="shop">
    <div class="section-title"><h2>हमारे प्रोडक्ट</h2><span class="badge">7 सामान</span></div>
    <div class="tools">
      <input id="search" type="search" placeholder="🔎 सामान खोजें..." aria-label="सामान खोजें">
      <select id="sort" aria-label="कीमत के अनुसार"><option value="default">क्रम</option><option value="low">कम कीमत</option><option value="high">ज़्यादा कीमत</option></select>
    </div>
    <div class="products" id="products"></div>
  </section>
  <section class="panel" id="cart">
    <div class="section-title" style="margin-top:0"><h2>🛍️ आपका कार्ट</h2><small id="cartCount">0 सामान</small></div>
    <div id="cartItems"><div class="empty">अभी कार्ट खाली है। ऊपर से सामान जोड़ें।</div></div>
    <div class="totals">
      <div class="total-line"><span>सामान का कुल</span><strong id="subtotal">₹0</strong></div>
      <div class="total-line"><span>डिलीवरी शुल्क</span><strong id="deliveryFee">दुकानदार बताएगा</strong></div>
      <div class="total-line grand"><span>कुल सामान कीमत</span><span id="total">₹0</span></div>
      <p class="hint">डिलीवरी शुल्क, उपलब्धता और अंतिम बिल की पुष्टि दुकान WhatsApp पर करेगी।</p>
      <button class="primary" onclick="sendOrder()">🟢 WhatsApp पर ऑर्डर भेजें</button>
      <button class="secondary" onclick="clearCart()">कार्ट खाली करें</button>
    </div>
  </section>
  <section class="panel" id="contact">
    <div class="section-title" style="margin-top:0"><h2>📍 दुकान की जानकारी</h2></div>
    <div class="contact-grid">
      <div class="contact-item"><strong>🏪 दुकान</strong>SUMIT KIRANA STORE<br>मालिक: NIRANJAN SHARMA</div>
      <div class="contact-item"><strong>📞 WhatsApp / फोन</strong><a href="https://wa.me/918092001254" target="_blank" rel="noopener">8092001254 पर संपर्क करें</a></div>
      <div class="contact-item"><strong>📌 पता</strong>AT NAGDAHARI, POST–DHOLBAZZA BAZAR, RUPAULI, PURNEA, BIHAR</div>
      <div class="contact-item"><strong>💳 भुगतान</strong>UPI और Cash<br><span class="hint">UPI भुगतान से पहले दुकान से पुष्टि करें।</span></div>
    </div>
    <p class="hint">नोट: इस वेबसाइट में अभी ऑनलाइन पेमेंट गेटवे नहीं जुड़ा है। ऑर्डर WhatsApp पर भेजा जाता है; भुगतान का तरीका दुकान से तय करें।</p>
  </section>
</main>
<div class="sticky"><button onclick="document.getElementById('cart').scrollIntoView({behavior:'smooth'})">🛒 कार्ट देखें • <span id="stickyTotal">₹0</span></button></div>
<footer class="footer">© <span id="year"></span> SUMIT KIRANA STORE • धन्यवाद, फिर आइए! 💚</footer>
<script>
const WHATSAPP_NUMBER = "918092001254"; // भारत का country code + दुकान का नंबर
const products = [
  {id:1,name:"आटा",price:210,unit:"किलो",emoji:"🌾",desc:"गेहूँ का आटा"},
  {id:2,name:"चावल",price:100,unit:"किलो",emoji:"🍚",desc:"रोज़मर्रा का चावल"},
  {id:3,name:"सरसों तेल",price:180,unit:"किलो",emoji:"🫙",desc:"खाना बनाने के लिए"},
  {id:4,name:"नमक",price:20,unit:"किलो",emoji:"🧂",desc:"रसोई का जरूरी सामान"},
  {id:5,name:"बासमती चावल",price:80,unit:"किलो",emoji:"🍚",desc:"बासमती चावल"},
  {id:6,name:"धनिया",price:200,unit:"किलो",emoji:"🌿",desc:"धनिया मसाला"},
  {id:7,name:"मिर्च",price:140,unit:"किलो",emoji:"🌶️",desc:"मिर्च मसाला"}
];
let cart = {};
const money = n => "₹" + n.toLocaleString("en-IN");
function renderProducts(){
  const query = document.getElementById("search").value.trim().toLowerCase();
  const sort = document.getElementById("sort").value;
  let list = products.filter(p => (p.name+" "+p.desc).toLowerCase().includes(query));
  if(sort==="low") list.sort((a,b)=>a.price-b.price);
  if(sort==="high") list.sort((a,b)=>b.price-a.price);
  const root = document.getElementById("products");
  if(!list.length){root.innerHTML='<div class="empty">कोई सामान नहीं मिला।</div>';return;}
  root.innerHTML = list.map(p=>`
    <article class="card">
      <div class="product-art" role="img" aria-label="${p.name}">${p.emoji}</div>
      <div class="card-body">
        <h3>${p.name}</h3><div class="desc">${p.desc}</div>
        <div class="price">${money(p.price)} <small>/ ${p.unit}</small></div>
        <button class="add" onclick="addToCart(${p.id})">＋ कार्ट में जोड़ें</button>
      </div>
    </article>`).join("");
}
function addToCart(id){cart[id]=(cart[id]||0)+1;renderCart();}
function changeQty(id,delta){cart[id]=(cart[id]||0)+delta;if(cart[id]<=0)delete cart[id];renderCart();}
function clearCart(){cart={};renderCart();}
function renderCart(){
  const ids=Object.keys(cart).filter(id=>cart[id]>0);
  const root=document.getElementById("cartItems");
  if(!ids.length)root.innerHTML='<div class="empty">अभी कार्ट खाली है। ऊपर से सामान जोड़ें।</div>';
  else root.innerHTML=ids.map(id=>{
    const p=products.find(x=>x.id===Number(id)),q=cart[id];
    return `<div class="cart-row"><div class="cart-emoji">${p.emoji}</div><div class="cart-info"><strong>${p.name}</strong><small>${money(p.price)} / ${p.unit} • ${money(p.price*q)}</small></div><div class="qty"><button aria-label="कम करें" onclick="changeQty(${p.id},-1)">−</button><strong>${q}</strong><button aria-label="बढ़ाएँ" onclick="changeQty(${p.id},1)">+</button></div></div>`;
  }).join("");
  const count=ids.reduce((s,id)=>s+cart[id],0);
  const sum=ids.reduce((s,id)=>s+products.find(p=>p.id===Number(id)).price*cart[id],0);
  document.getElementById("cartCount").textContent=count+" सामान";
  document.getElementById("subtotal").textContent=money(sum);
  document.getElementById("total").textContent=money(sum);
  document.getElementById("stickyTotal").textContent=money(sum);
}
function sendOrder(){
  const ids=Object.keys(cart).filter(id=>cart[id]>0);
  if(!ids.length){alert("पहले कार्ट में सामान जोड़ें।");return;}
  const lines=ids.map(id=>{const p=products.find(x=>x.id===Number(id));return `• ${p.name} — ${cart[id]} ${p.unit} × ${money(p.price)} = ${money(p.price*cart[id])}`;});
  const sum=ids.reduce((s,id)=>s+products.find(p=>p.id===Number(id)).price*cart[id],0);
  const message=[
    "नमस्ते SUMIT KIRANA STORE!",
    "मुझे ये सामान ऑर्डर करना है:",
    "",
    ...lines,
    "",
    `सामान की कुल कीमत: ${money(sum)}`,
    "डिलीवरी शुल्क और अंतिम बिल कृपया बताएं।",
    "भुगतान: UPI या Cash (पुष्टि के अनुसार)",
    "",
    "ग्राहक का नाम:",
    "डिलीवरी का पूरा पता:",
    "मोबाइल नंबर:"
  ].join("\n");
  window.open("https://wa.me/"+WHATSAPP_NUMBER+"?text="+encodeURIComponent(message),"_blank");
}
document.getElementById("search").addEventListener("input",renderProducts);
document.getElementById("sort").addEventListener("change",renderProducts);
document.getElementById("year").textContent=new Date().getFullYear();
renderProducts();renderCart();
</script>
</body>
</html>
