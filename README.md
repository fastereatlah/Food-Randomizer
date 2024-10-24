## What would you like to eat today?
<html>
<head>
<style>
#randomFood{
                font-size:40px;
                text-align:center;
                margin:50px auto;
                font-family:Arial, sans-serif;
            }
</style>
  <button type="randomFood" onclick="randomFood()">Feed Me</button>
  <input name="randomFood" id="randomFood">


<script>

var food = Array("Restaurant Sun Fatt Kee", "Thong Kee Café Sea Park", "Sunrise Roast Duck", "Restoran Shuang Siew", "Restaurant Kong Sai", "O & S Restaurant","Choon Prawn Mee House 春虾面","Shokudo Japanese Curry Rice","Ribs King","Soong Kee Beef Noodles","Ai Jiak Penang Food","Boran (Seapark) - Classic Thai Street Food","Kampar Café","Restoran Prosperity Bowl","Lim Fried Chicken SS2","Tang Pin Kitchen","Village Chicken Restaurant PLT","Mama Ting Sarawak Noodle","Restoran Lim Mee Yoke","TNR by Sean & Angie","Ipoh Ipoh Kafe","Pho King","66 Nyonya Secrets","Shin Zushi SS2","DayOne DayOne Noodles @SS2","Restoran Lau Dou Pork Noodle","Eastern Kopitiam","Kaw Kaw Pak Kopi","香港仔冰室 SS2 Cafe Hk Boy","銘记粥品 Ming Kee Porridge SS2","Jojo Little Kitchen","Restoran Super Kitchen Chilly Pan Mee","Lorong Seratus Tahun","頭家 tau ke","YILO RESTAURANT & BAR","Mala Cantine 麻辣食堂","Restaurant 134 Mixed Rice","Hainan Joy Café","66大山脚猪肉粉","66 Chu Yuk Fun","Restoran Choong Kee Kampar Claypot Rice","Vary Pasta","New Ipoh Nga Choy Chicken Rice 1977","Big Big Wantan Mee Rice Damansara Jaya","Restoran Jin Xuan Hong Kong (Damansara Jaya)","Boon Signature Roast Pork","Aman Suria Shu Mala Hot Pot 蜀麻辣湘锅","Kalamazoo Restaurant & Café","Betty's Midwest Kitchen","Restoran New Wong Poh","Acha Curry House","UNCLE CHENG SPECIAL BEEF NOODLE","Tasty Chapathi PJ","Ramen Bar Shishido","STREAT Thai","Kanna Curry House","Next Station Noodle House","Flakes (The Hub SS2)","Mei by Fat Spoon (The Hub SS2)","slow coffee","The Butcher's Table @SS2","Fatt Kee Soy Sauce Chicken Rice (Wan Shoon Restaurant)","Kompassion","Lat Tali Lat Café","Rasa Viet Kitchen ( Damansara Kim )","Restaurant Lin Li Xiang","Ara Vietnamese Noodles (non-halal)","Sneaky Burgers","Menya Hanabi 麺屋はなび Damansara Utama","Restoran Sate Kajang Hj Samuri","Mamalee Nasi Lemak","Village Park Restaurant","Hartton Kitchen","Annie 1 Kopitiam","Restoran Choon Yien","Ban Huat Heng Coffee Shop","Good Blue Men","黃記雞飯 Wong Kee Chicken Rice","Jane’s Nem","Goodview Kopitiam","Kedai Kopi Yun Kei","Kedai Kopi Wah Cheong","SS2 Chow Yang Kopitiam 志昇茶餐室","Soon Soon Pan Mee & Fish Head Noodles");

function randomFood() {
  var randomFood = food[Math.floor(Math.random() * food.length)];
  document.getElementById('randomFood').value = randomFood;
};

</script>

</head>
</html>
