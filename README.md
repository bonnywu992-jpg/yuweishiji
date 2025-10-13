<!DOCTYPE html>
<html lang="zh-TW">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>渝味食記 - 四川濃香型辣椒醬</title>
<style>
* { margin: 0; padding: 0; box-sizing: border-box; }
body { font-family: 'Microsoft JhengHei', Arial, sans-serif; background: linear-gradient(135deg, #d32f2f 0%, #f44336 100%); min-height: 100vh; padding: 20px; }
.container { max-width: 800px; margin: 0 auto; background: white; border-radius: 20px; box-shadow: 0 20px 60px rgba(0,0,0,0.3); overflow: hidden; }
.header { background: linear-gradient(135deg, #b71c1c 0%, #d32f2f 100%); color: white; padding: 40px 30px; text-align: center; }
.header h1 { font-size: 2.5em; margin-bottom: 10px; text-shadow: 2px 2px 4px rgba(0,0,0,0.2); }
.header p { font-size: 1.1em; opacity: 0.95; }
.ig-link { display: inline-block; margin-top: 10px; padding: 8px 20px; background: rgba(255,255,255,0.2); border-radius: 20px; color: white; text-decoration: none; transition: background 0.3s; }
.ig-link:hover { background: rgba(255,255,255,0.3); }
.product-section { padding: 40px 30px; }
.product-card { background: linear-gradient(135deg, #fff5f5 0%, #ffebee 100%); border-radius: 15px; padding: 30px; border: 3px solid #f44336; }
.product-header { display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; margin-bottom: 20px; }
.product-name { font-size: 1.8em; color: #b71c1c; font-weight: bold; }
.product-price { font-size: 1.6em; color: #d32f2f; font-weight: bold; }
.special-badge { display: inline-block; background: #ff6b6b; color: white; padding: 5px 15px; border-radius: 20px; font-size: 0.9em; margin-left: 10px; }
.highlight { background: #fff3bf; padding: 15px; border-radius: 10px; margin: 15px 0; border-left: 4px solid #f44336; }
.highlight strong { color: #b71c1c; }
.form-group { margin: 20px 0; }
.form-group label { display: block; margin-bottom: 8px; color: #333; font-weight: bold; }
.form-group input, .form-group select, .form-group textarea { width: 100%; padding: 12px; border: 2px solid #ddd; border-radius: 8px; font-size: 1em; transition: border-color 0.3s; }
.form-group input:focus, .form-group select:focus, .form-group textarea:focus { outline: none; border-color: #f44336; }
.quantity-control { display: flex; align-items: center; gap: 15px; }
.quantity-control button { width: 40px; height: 40px; border: none; background: #f44336; color: white; font-size: 1.5em; border-radius: 8px; cursor: pointer; transition: background 0.3s; user-select: none; }
.quantity-control button:hover { background: #d32f2f; }
.quantity-control button:active { transform: scale(0.95); }
.quantity-control input { width: 80px; text-align: center; font-size: 1.2em; font-weight: bold; pointer-events: none; }
.total-section { background: #f8f9fa; padding: 20px; border-radius: 10px; margin: 20px 0; transition: all 0.3s ease; }
.total-row { display: flex; justify-content: space-between; margin: 10px 0; font-size: 1.1em; }
.total-row.final { font-size: 1.5em; font-weight: bold; color: #b71c1c; border-top: 2px solid #ddd; padding-top: 10px; margin-top: 15px; }
.notice { background: #fff3bf; padding: 15px; border-radius: 10px; margin: 20px 0; text-align: center; font-weight: bold; color: #b71c1c; border: 2px dashed #ffa94d; transition: all 0.3s ease; }
.submit-btn { width: 100%; padding: 18px; background: linear-gradient(135deg, #b71c1c 0%, #d32f2f 100%); color: white; border: none; border-radius: 12px; font-size: 1.3em; font-weight: bold; cursor: pointer; transition: transform 0.2s, box-shadow 0.2s; margin-bottom: 10px; }
.submit-btn:hover { transform: translateY(-2px); box-shadow: 0 8px 20px rgba(183, 28, 28, 0.4); }
.submit-btn:disabled { background: #ccc; cursor: not-allowed; transform: none; }
.success-message { background: #d3f9d8; padding: 20px; border-radius: 10px; margin: 20px 0; text-align: center; color: #2b8a3e; font-weight: bold; border: 2px solid #51cf66; }
.error-message { background: #ffe3e3; padding: 20px; border-radius: 10px; margin: 20px 0; text-align: center; color: #b71c1c; font-weight: bold; border: 2px solid #f44336; }
.store-section { background: #f8f9fa; padding: 15px; border-radius: 10px; margin-top: 10px; border: 2px solid #e9ecef; }
.store-region { margin-bottom: 15px; }
.store-region:last-child { margin-bottom: 0; }
.store-region label { font-size: 0.95em; color: #495057; margin-bottom: 5px; display: block; }
#addressGroup { display: none; }
</style>
</head>
<body>
<div class="container">
  <div class="header">
    <h1>🌶️ 渝味食記 🌶️</h1>
    <p>四川濃香型辣椒醬</p>
    <a href="https://www.instagram.com/yuweishiji" target="_blank" class="ig-link">📷 追蹤我們的 Instagram</a>
  </div>

  <div class="product-section">
    <div class="product-card">
      <div class="product-header">
        <div>
          <span class="product-name">四川濃香型辣椒醬</span>
          <span class="special-badge">🔥 麻辣鮮香</span>
        </div>
        <div class="product-price">NT$ 250 / 罐</div>
      </div>

      <div class="highlight">
        <strong>手工製作、無添加防腐劑,開封後需冷藏保存 ⚠️</strong>
      </div>

      <form id="orderForm">
        <div class="form-group">
          <label>購買數量</label>
          <div class="quantity-control">
            <button type="button" id="btnMinus">−</button>
            <input type="number" id="qty" value="1" min="1" readonly>
            <button type="button" id="btnPlus">+</button>
          </div>
        </div>

        <div class="notice" id="freeShipNotice">🎉 購買10罐(含)以上免運費!</div>

        <div class="form-group"><label>姓名 *</label><input type="text" id="name" required></div>
        <div class="form-group"><label>電話 *</label><input type="tel" id="phone" required placeholder="例:0912345678"></div>
        <div class="form-group"><label>Email *</label><input type="email" id="email" required></div>
        
        <div class="form-group">
          <label>取貨方式 *</label>
          <select id="pickup" required>
            <option value="">請選擇取貨方式</option>
            <option value="7-11">7-11 超商取貨</option>
            <option value="全家">全家超商取貨</option>
            <option value="宅配">宅配</option>
            <option value="面交">面交 (請先私訊IG確認)</option>
          </select>
        </div>

        <div class="form-group" id="storeSelectGroup" style="display:none;">
          <label>選擇門市 *</label>
          <div class="store-section" id="storeSection"></div>
        </div>

        <div class="form-group" id="addressGroup">
          <label id="addressLabel">收貨地址 *</label>
          <textarea id="address" rows="3" placeholder="請填寫完整地址"></textarea>
        </div>

        <div class="form-group">
          <label>匯款帳號後5碼 *</label>
          <input type="text" id="accountLast5" maxlength="5" pattern="[0-9]{5}" required placeholder="請填寫5位數字">
        </div>
        <div class="form-group">
          <label>備註</label>
          <textarea id="note" rows="2" placeholder="其他需求或備註"></textarea>
        </div>

        <div class="total-section">
          <div class="total-row"><span>小計:</span><span id="subtotalDisplay">NT$ 250</span></div>
          <div class="total-row"><span>運費:</span><span id="shippingDisplay">NT$ 130</span></div>
          <div class="total-row final"><span>總計:</span><span id="totalDisplay">NT$ 380</span></div>
        </div>

        <button type="submit" class="submit-btn" id="submitBtn">確認訂購</button>
        <div id="message"></div>
      </form>
    </div>
  </div>
</div>

<script>
const WEB3FORMS_ACCESS_KEY='63c8b2d8-bddb-46cb-b683-e3c0becf31bf';
const MERCHANT_EMAIL='bonnywu992@gmail.com';
var PRICE=250, SHIPPING_DELIVERY=160, SHIPPING_STORE=130, FREE_SHIPPING_QTY=10;

// 門市資料 - 三層結構: 城市 > 區域 > 門市
const storeData = {
  '7-11': {
    '台北市': {
      '信義區': ['信義A門市', '信義B門市', '信義C門市'],
      '中山區': ['中山A門市', '中山B門市', '中山C門市'],
      '大安區': ['大安A門市', '大安B門市', '大安C門市'],
      '松山區': ['松山A門市', '松山B門市'],
      '士林區': ['士林A門市', '士林B門市'],
      '內湖區': ['內湖A門市', '內湖B門市'],
      '南港區': ['南港A門市', '南港B門市'],
      '文山區': ['文山A門市', '文山B門市']
    },
    '新北市': {
      '板橋區': ['板橋A門市', '板橋B門市', '板橋C門市'],
      '新莊區': ['新莊A門市', '新莊B門市', '新莊C門市'],
      '中和區': ['中和A門市', '中和B門市'],
      '永和區': ['永和A門市', '永和B門市'],
      '三重區': ['三重A門市', '三重B門市'],
      '新店區': ['新店A門市', '新店B門市'],
      '土城區': ['土城A門市', '土城B門市'],
      '蘆洲區': ['蘆洲A門市', '蘆洲B門市']
    },
    '桃園市': {
      '中壢區': ['中壢A門市', '中壢B門市', '中壢C門市'],
      '平鎮區': ['平鎮A門市', '平鎮B門市'],
      '八德區': ['八德A門市', '八德B門市'],
      '龜山區': ['龜山A門市', '龜山B門市'],
      '桃園區': ['桃園A門市', '桃園B門市', '桃園C門市'],
      '龍潭區': ['龍潭A門市', '龍潭B門市'],
      '大溪區': ['大溪A門市', '大溪B門市']
    },
    '台中市': {
      '西屯區': ['西屯A門市', '西屯B門市', '西屯C門市'],
      '北屯區': ['北屯A門市', '北屯B門市', '北屯C門市'],
      '南屯區': ['南屯A門市', '南屯B門市'],
      '中區': ['中區A門市', '中區B門市'],
      '東區': ['東區A門市', '東區B門市'],
      '南區': ['南區A門市', '南區B門市'],
      '北區': ['北區A門市', '北區B門市'],
      '西區': ['西區A門市', '西區B門市']
    },
    '台南市': {
      '東區': ['東區A門市', '東區B門市', '東區C門市'],
      '中西區': ['中西區A門市', '中西區B門市'],
      '北區': ['北區A門市', '北區B門市'],
      '南區': ['南區A門市', '南區B門市'],
      '安平區': ['安平A門市', '安平B門市'],
      '永康區': ['永康A門市', '永康B門市', '永康C門市'],
      '新營區': ['新營A門市', '新營B門市']
    },
    '高雄市': {
      '左營區': ['左營A門市', '左營B門市', '左營C門市'],
      '三民區': ['三民A門市', '三民B門市', '三民C門市'],
      '鳳山區': ['鳳山A門市', '鳳山B門市', '鳳山C門市'],
      '苓雅區': ['苓雅A門市', '苓雅B門市'],
      '前鎮區': ['前鎮A門市', '前鎮B門市'],
      '楠梓區': ['楠梓A門市', '楠梓B門市'],
      '小港區': ['小港A門市', '小港B門市'],
      '岡山區': ['岡山A門市', '岡山B門市']
    }
  },
  '全家': {
    '台北市': {
      '信義區': ['信義A店', '信義B店', '信義C店'],
      '中山區': ['中山A店', '中山B店', '中山C店'],
      '大安區': ['大安A店', '大安B店', '大安C店'],
      '松山區': ['松山A店', '松山B店'],
      '士林區': ['士林A店', '士林B店'],
      '內湖區': ['內湖A店', '內湖B店'],
      '南港區': ['南港A店', '南港B店'],
      '文山區': ['文山A店', '文山B店']
    },
    '新北市': {
      '板橋區': ['板橋A店', '板橋B店', '板橋C店'],
      '新莊區': ['新莊A店', '新莊B店', '新莊C店'],
      '中和區': ['中和A店', '中和B店'],
      '永和區': ['永和A店', '永和B店'],
      '三重區': ['三重A店', '三重B店'],
      '新店區': ['新店A店', '新店B店'],
      '土城區': ['土城A店', '土城B店'],
      '蘆洲區': ['蘆洲A店', '蘆洲B店']
    },
    '桃園市': {
      '中壢區': ['中壢A店', '中壢B店', '中壢C店'],
      '平鎮區': ['平鎮A店', '平鎮B店'],
      '八德區': ['八德A店', '八德B店'],
      '龜山區': ['龜山A店', '龜山B店'],
      '桃園區': ['桃園A店', '桃園B店', '桃園C店'],
      '龍潭區': ['龍潭A店', '龍潭B店'],
      '大溪區': ['大溪A店', '大溪B店']
    },
    '台中市': {
      '西屯區': ['西屯A店', '西屯B店', '西屯C店'],
      '北屯區': ['北屯A店', '北屯B店', '北屯C店'],
      '南屯區': ['南屯A店', '南屯B店'],
      '中區': ['中區A店', '中區B店'],
      '東區': ['東區A店', '東區B店'],
      '南區': ['南區A店', '南區B店'],
      '北區': ['北區A店', '北區B店'],
      '西區': ['西區A店', '西區B店']
    },
    '台南市': {
      '東區': ['東區A店', '東區B店', '東區C店'],
      '中西區': ['中西區A店', '中西區B店'],
      '北區': ['北區A店', '北區B店'],
      '南區': ['南區A店', '南區B店'],
      '安平區': ['安平A店', '安平B店'],
      '永康區': ['永康A店', '永康B店', '永康C店'],
      '新營區': ['新營A店', '新營B店']
    },
    '高雄市': {
      '左營區': ['左營A店', '左營B店', '左營C店'],
      '三民區': ['三民A店', '三民B店', '三民C店'],
      '鳳山區': ['鳳山A店', '鳳山B店', '鳳山C店'],
      '苓雅區': ['苓雅A店', '苓雅B店'],
      '前鎮區': ['前鎮A店', '前鎮B店'],
      '楠梓區': ['楠梓A店', '楠梓B店'],
      '小港區': ['小港A店', '小港B店'],
      '岡山區': ['岡山A店', '岡山B店']
    }
  }
};

var qtyInput=document.getElementById('qty');
var btnPlus=document.getElementById('btnPlus');
var btnMinus=document.getElementById('btnMinus');
var subtotalDisplay=document.getElementById('subtotalDisplay');
var shippingDisplay=document.getElementById('shippingDisplay');
var totalDisplay=document.getElementById('totalDisplay');
var freeShipNotice=document.getElementById('freeShipNotice');
var pickupSelect=document.getElementById('pickup');
var storeSelectGroup=document.getElementById('storeSelectGroup');
var addressGroup=document.getElementById('addressGroup');
var storeSection=document.getElementById('storeSection');
var selectedStore = '';
var citySelect, districtSelect, storeSelect;

function generateOrderId(){
    var now=new Date();
    var year=now.getFullYear();
    var month=String(now.getMonth()+1).padStart(2,'0');
    var day=String(now.getDate()).padStart(2,'0');
    var random=Math.floor(Math.random()*10000).toString().padStart(4,'0');
    return 'YW'+year+month+day+random;
}

function updatePrice(){
    var qty=parseInt(qtyInput.value);
    if(isNaN(qty)||qty<1){ qty=1; qtyInput.value=1; }
    var subtotal=PRICE*qty;
    var pickupMethod=pickupSelect.value;
    var shipping=0;
    
    // 根據取貨方式計算運費
    if(pickupMethod === '宅配'){
        shipping = (qty>=FREE_SHIPPING_QTY) ? 0 : SHIPPING_DELIVERY;
    } else if(pickupMethod === '7-11' || pickupMethod === '全家'){
        shipping = (qty>=FREE_SHIPPING_QTY) ? 0 : SHIPPING_STORE;
    } else if(pickupMethod === '面交'){
        shipping = 0;
    } else {
        // 預設超商運費
        shipping = (qty>=FREE_SHIPPING_QTY) ? 0 : SHIPPING_STORE;
    }
    
    var total=subtotal+shipping;
    subtotalDisplay.textContent='NT$ '+subtotal;
    
    if(shipping === 0){
        if(pickupMethod === '面交'){
            shippingDisplay.textContent='免運費 (面交) ✓';
        } else {
            shippingDisplay.textContent='免運費 ✓';
        }
    } else {
        shippingDisplay.textContent='NT$ '+shipping;
    }
    
    totalDisplay.textContent='NT$ '+total;

    if(pickupMethod === '面交'){
        freeShipNotice.textContent='🎉 面交免運費!';
        freeShipNotice.style.background='#d3f9d8';
    } else if(qty<FREE_SHIPPING_QTY){
        var left=FREE_SHIPPING_QTY-qty;
        freeShipNotice.textContent='再買 '+left+' 罐即可免運 🎁';
        freeShipNotice.style.background='#fff3bf';
    } else {
        var savedAmount = (pickupMethod === '宅配') ? SHIPPING_DELIVERY : SHIPPING_STORE;
        freeShipNotice.textContent='🎉 已達免運門檻!恭喜省下 NT$ '+savedAmount+' 運費!';
        freeShipNotice.style.background='#d3f9d8';
    }
}

function renderStoreOptions(pickupMethod) {
    storeSection.innerHTML = '';
    selectedStore = '';
    
    if (!storeData[pickupMethod]) return;
    
    var stores = storeData[pickupMethod];
    
    // 創建城市選擇
    var cityDiv = document.createElement('div');
    cityDiv.className = 'store-region';
    var cityLabel = document.createElement('label');
    cityLabel.textContent = '選擇城市';
    cityDiv.appendChild(cityLabel);
    
    citySelect = document.createElement('select');
    citySelect.className = 'form-group';
    citySelect.style.width = '100%';
    citySelect.style.marginTop = '5px';
    var cityDefault = document.createElement('option');
    cityDefault.value = '';
    cityDefault.textContent = '請選擇城市';
    citySelect.appendChild(cityDefault);
    
    Object.keys(stores).forEach(function(city) {
        var option = document.createElement('option');
        option.value = city;
        option.textContent = city;
        citySelect.appendChild(option);
    });
    cityDiv.appendChild(citySelect);
    storeSection.appendChild(cityDiv);
    
    // 創建區域選擇
    var districtDiv = document.createElement('div');
    districtDiv.className = 'store-region';
    var districtLabel = document.createElement('label');
    districtLabel.textContent = '選擇區域';
    districtDiv.appendChild(districtLabel);
    
    districtSelect = document.createElement('select');
    districtSelect.className = 'form-group';
    districtSelect.style.width = '100%';
    districtSelect.style.marginTop = '5px';
    districtSelect.disabled = true;
    var districtDefault = document.createElement('option');
    districtDefault.value = '';
    districtDefault.textContent = '請先選擇城市';
    districtSelect.appendChild(districtDefault);
    districtDiv.appendChild(districtSelect);
    storeSection.appendChild(districtDiv);
    
    // 創建門市選擇
    var storeDiv = document.createElement('div');
    storeDiv.className = 'store-region';
    var storeLabel = document.createElement('label');
    storeLabel.textContent = '選擇門市';
    storeDiv.appendChild(storeLabel);
    
    storeSelect = document.createElement('select');
    storeSelect.className = 'form-group';
    storeSelect.style.width = '100%';
    storeSelect.style.marginTop = '5px';
    storeSelect.disabled = true;
    var storeDefault = document.createElement('option');
    storeDefault.value = '';
    storeDefault.textContent = '請先選擇區域';
    storeSelect.appendChild(storeDefault);
    storeDiv.appendChild(storeSelect);
    storeSection.appendChild(storeDiv);
    
    // 城市選擇事件
    citySelect.addEventListener('change', function() {
        var selectedCity = this.value;
        districtSelect.innerHTML = '';
        storeSelect.innerHTML = '';
        storeSelect.disabled = true;
        selectedStore = '';
        
        var districtDefault = document.createElement('option');
        districtDefault.value = '';
        districtDefault.textContent = '請選擇區域';
        districtSelect.appendChild(districtDefault);
        
        var storeDefault = document.createElement('option');
        storeDefault.value = '';
        storeDefault.textContent = '請先選擇區域';
        storeSelect.appendChild(storeDefault);
        
        if (selectedCity && stores[selectedCity]) {
            districtSelect.disabled = false;
            Object.keys(stores[selectedCity]).forEach(function(district) {
                var option = document.createElement('option');
                option.value = district;
                option.textContent = district;
                districtSelect.appendChild(option);
            });
        } else {
            districtSelect.disabled = true;
        }
    });
    
    // 區域選擇事件
    districtSelect.addEventListener('change', function() {
        var selectedCity = citySelect.value;
        var selectedDistrict = this.value;
        storeSelect.innerHTML = '';
        selectedStore = '';
        
        var storeDefault = document.createElement('option');
        storeDefault.value = '';
        storeDefault.textContent = '請選擇門市';
        storeSelect.appendChild(storeDefault);
        
        if (selectedCity && selectedDistrict && stores[selectedCity][selectedDistrict]) {
            storeSelect.disabled = false;
            stores[selectedCity][selectedDistrict].forEach(function(store) {
                var option = document.createElement('option');
                option.value = selectedCity + '-' + selectedDistrict + '-' + store;
                option.textContent = store;
                storeSelect.appendChild(option);
            });
        } else {
            storeSelect.disabled = true;
        }
    });
    
    // 門市選擇事件
    storeSelect.addEventListener('change', function() {
        selectedStore = this.value;
    });
}

pickupSelect.addEventListener('change', function() {
    var method = this.value;
    
    if (method === '7-11' || method === '全家') {
        storeSelectGroup.style.display = 'block';
        addressGroup.style.display = 'none';
        renderStoreOptions(method);
    } else if (method === '宅配') {
        storeSelectGroup.style.display = 'none';
        addressGroup.style.display = 'block';
        document.getElementById('addressLabel').textContent = '收貨地址 *';
        document.getElementById('address').placeholder = '請填寫完整地址';
    } else if (method === '面交') {
        storeSelectGroup.style.display = 'none';
        addressGroup.style.display = 'block';
        document.getElementById('addressLabel').textContent = '面交地點 *';
        document.getElementById('address').placeholder = '請填寫面交地點(需先透過IG確認)';
    } else {
        storeSelectGroup.style.display = 'none';
        addressGroup.style.display = 'none';
    }
    
    updatePrice();
});

btnPlus.addEventListener('click',function(e){e.preventDefault();qtyInput.value=parseInt(qtyInput.value)+1;updatePrice();});
btnMinus.addEventListener('click',function(e){e.preventDefault();if(parseInt(qtyInput.value)>1){qtyInput.value=parseInt(qtyInput.value)-1;updatePrice();}});

document.getElementById('orderForm').addEventListener('submit',async function(e){
    e.preventDefault();
    var submitBtn=document.getElementById('submitBtn');
    var messageDiv=document.getElementById('message');

    var phone=document.getElementById('phone').value.trim();
    var account=document.getElementById('accountLast5').value.trim();
    var pickupMethod=document.getElementById('pickup').value;
    var addressInput=document.getElementById('address').value.trim();
    
    if(!/^09\d{8}$/.test(phone)){ messageDiv.innerHTML='<div class="error-message">❌ 請輸入正確手機號碼(例:0912345678)</div>'; return; }
    if(!/^\d{5}$/.test(account)){ messageDiv.innerHTML='<div class="error-message">❌ 帳號後5碼必須是5位數字</div>'; return; }
    
    var finalAddress = '';
    if (pickupMethod === '7-11' || pickupMethod === '全家') {
        if (!selectedStore) {
            messageDiv.innerHTML='<div class="error-message">❌ 請選擇門市</div>';
            return;
        }
        finalAddress = selectedStore;
    } else if (pickupMethod === '宅配' || pickupMethod === '面交') {
        if (addressInput.length < 5) {
            messageDiv.innerHTML='<div class="error-message">❌ 請填寫完整地址或地點</div>';
            return;
        }
        finalAddress = addressInput;
    } else {
        messageDiv.innerHTML='<div class="error-message">❌ 請選擇取貨方式</div>';
        return;
    }

    submitBtn.disabled=true; submitBtn.textContent='處理中...'; messageDiv.innerHTML='';

    try{
        var qty=parseInt(qtyInput.value);
        var subtotal=PRICE*qty;
        var shipping=0;
        
        // 計算運費
        if(pickupMethod === '宅配'){
            shipping = (qty>=FREE_SHIPPING_QTY) ? 0 : SHIPPING_DELIVERY;
        } else if(pickupMethod === '7-11' || pickupMethod === '全家'){
            shipping = (qty>=FREE_SHIPPING_QTY) ? 0 : SHIPPING_STORE;
        } else if(pickupMethod === '面交'){
            shipping = 0;
        }
        
        var total=subtotal+shipping;
        var orderId=generateOrderId();
        var orderTime=new Date().toLocaleString('zh-TW',{year:'numeric',month:'2-digit',day:'2-digit',hour:'2-digit',minute:'2-digit',hour12:false});
        var customerName=document.getElementById('name').value;
        var customerEmail=document.getElementById('email').value;
        var note=document.getElementById('note').value||'無';

        var merchantEmailContent=`╔═══════════════════════════════════╗
🛒 新訂單通知 - 渝味食記
╚═══════════════════════════════════╝
訂單編號:${orderId}
訂單時間:${orderTime}
姓名:${customerName}
電話:${phone}
Email:${customerEmail}
取貨方式:${pickupMethod}
收貨地址/門市:${finalAddress}
匯款帳號後5碼:${account}
商品名稱:【渝味食記】四川濃香型辣椒醬
單價:NT$ ${PRICE}
數量:${qty} 罐
小計:NT$ ${subtotal}
商品小計:NT$ ${subtotal}
運費:${shipping===0?(pickupMethod==='面交'?'免運費 (面交) ✓':'免運費 ✓'):'NT$ '+shipping}
訂單總額:NT$ ${total}
備註:${note}
提醒事項:
${pickupMethod==='面交'?'⚠️ 此訂單選擇面交,請透過 Instagram 與客戶確認時間地點':''}
${shipping===0&&pickupMethod!=='面交'?'✅ 此訂單已達免運門檻':''}
${pickupMethod==='面交'?'✅ 面交免運費':''}`;

        // 商家信
        await fetch('https://api.web3forms.com/submit',{
            method:'POST',
            headers:{'Content-Type':'application/json','Accept':'application/json'},
            body:JSON.stringify({access_key:WEB3FORMS_ACCESS_KEY,subject:`🛒 新訂單 ${orderId} - 渝味食記`,from_name:'渝味食記訂購系統',email:MERCHANT_EMAIL,message:merchantEmailContent})
        });

        // 顧客信
        var customerEmailContent=`親愛的 ${customerName} 您好:
感謝您於 渝味食記 下單!
訂單編號:${orderId}
商品:【渝味食記】四川濃香型辣椒醬 x ${qty} 罐
小計:NT$ ${subtotal}
運費:${shipping===0?(pickupMethod==='面交'?'免運費 (面交) ✓':'免運費 ✓'):'NT$ '+shipping}
總計:NT$ ${total}
取貨方式:${pickupMethod}
收貨地址/門市:${finalAddress}
備註:${note}
請記住您的訂單編號以便查詢
⚠️ 若選擇面交,請透過 Instagram 私訊我們確認時間地點
Instagram: @yuweishiji`;

        await fetch('https://api.web3forms.com/submit',{
            method:'POST',
            headers:{'Content-Type':'application/json','Accept':'application/json'},
            body:JSON.stringify({access_key:WEB3FORMS_ACCESS_KEY,from_name:'渝味食記訂購系統',email:customerEmail,message:customerEmailContent})
        });

        messageDiv.innerHTML=`<div class="success-message">
✅ 訂單已成功送出!<br><br>
<strong>訂單編號:${orderId}</strong><br><br>
我們已收到您的訂單,會盡快與您聯繫。<br>
${pickupMethod==='面交'?'<br>⚠️ 您選擇了面交,請透過 Instagram 私訊我們確認時間地點。<br>':''}
<br>請記住您的訂單編號以便查詢。<br>
📧 確認信已發送至您的 Email<br>
Instagram: @yuweishiji
</div>`;

        document.getElementById('orderForm').reset();
        qtyInput.value=1;
        selectedStore = '';
        storeSelectGroup.style.display = 'none';
        addressGroup.style.display = 'none';
        updatePrice();

    } catch(err){
        console.error(err);
        messageDiv.innerHTML=`<div class="error-message">
❌ 訂單送出失敗<br><br>
請稍後再試,或直接透過 Instagram 聯繫我們:<br><strong>@yuweishiji</strong>
</div>`;
    } finally{
        submitBtn.disabled=false; submitBtn.textContent='確認訂購';
    }
});

updatePrice();
console.log('渝味食記訂購系統初始化完成(含門市選擇功能)');
</script>
</body>
</html>
