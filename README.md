# ShoppingCart

<!DOCTYPE html>

<html>

<head>

<style>

body { 
    font-size: 16px;
    line-height: 1.5;
    font-weight: 450;
    font-family: "Helvetica Neue", sans-serif;
    background-image: url("https://i1.wp.com/mychronicdreams.com/wp-content/uploads/2017/11/krystian-tambur-101317.jpg?fit=4000%2C3000&ssl=1");
   
    font-style: normal;
    text-align: center;
}
img{
  width: 30%;
}
.title {
    font-size: 40px;
    line-height: 2;
    font-weight: 500;
    font-family: "Calibri", sans-serif;
    border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #E8E1FF;
    font-style: normal;
    padding: 20px;
}

.product {
    border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #6EE0FF;
    padding: 20px;
}

.prdImg {
    border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #E8E1FF;
    padding: 20px;
}

.prdTitle {
    font-size: 20px;
    line-height: 1.5;
    font-weight: 450;
    background-color: #fff;
    border: 5px;
    border-color: #A4E6FF;
    border-style: dotted;
    border-radius: 5px;
    background-color: #BFABFD;
    font-style: normal;
    padding: 20px;
}

.prdDetails {
    font-size: 17px;
    line-height: 2;
    font-weight: 450;
    border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #E8E1FF;
    color: #333;
    font-style: normal;
    padding: 20px;
  
}

.prdPrice {
  font-size: 18px;
    line-height: 2;
    font-weight: 450;
    border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #E8E1FF;
    color: #333;
    font-style: normal;
    padding: 20px;
  
}

.prdQuantity {
    font-size: 18px;
    line-height: 2;
    font-weight: 450;
    border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #E8E1FF;
    color: #333;
    font-style: normal;
    padding: 20px;
}

.prdRemoval {
    font-size: 16px;
    line-height: 1.5;
    font-weight: 450;
    border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #E8E1FF;
    color: #333;
    font-style: normal;
    padding: 20px;
}

.prdLNPrice {
  border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #E8E1FF;
    padding: 20px;
}

.prdDesc {
    background-color: #fff;
    border: 5px;
    border-color: #A4E6FF;
    border-style: dotted;
    border-radius: 5px;
    padding: 20px;
}



.t {
    border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #E9FFC8;
    padding: 20px;
}

.tItem {
    border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #D6FFC6;
    padding: 20px;
}

.tValue {
    border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #C8EFFF;
    padding: 20px;
}

.iTotals {
    border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #89DDFF;
    padding: 20px;
}

.rPrd {
    border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #78FFCA;
    padding: 20px;
}

.checkout {
    border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #78FFCA;
    padding: 20px;
}
#credit {
  background-color: #A4E6FF;
  border: 10px solid #78FFCA;
  border-radius: 5px;
  font-size: 30px;
}
</style>

  <title>Shopping cart</title>
  
  <link rel="stylesheet" href="Yes.css">
  
</head>

<body>

  <h1 class="title">Shopping Cart</h1>

  <div class="sCart">
  
    <div class="product">
    
      <div class="prdImg">
      
        <img src="https://vignette.wikia.nocookie.net/runescape2/images/a/a4/Durable_Jellyfish.png/revision/20150714212839">
        
      </div>
      
      <div class="prdDetails">
      
        <div class="prdTitle" id="prdSecond"></div>
        
        <p class="prdDesc" id="prdSecond1"></p>
        
      </div>
      
      <div class="prdPrice" id="prdSecond2"></div>
      
      <div class="prdQuantity">
      
        <input type="number" value="0" min="0">
        
      </div>
      
      <div class="prdRemoval">
      
        <button class="rPrd">
      
      Remove
      
      </button>
      
      </div>
      
      <div class="prdLNPrice">0.00</div>
    
    </div>

    <div class="product">
    
    <div class="prdImg">
    
    <img src="https://media.tnh.me/54ec061c5ccacf5872264eac/551875c75ccacf1b8200b49c">
    
    </div>
    
    <div class="prdDetails">
    
    <div class="prdTitle" id="prdOne"></div>
    
    <p class="prdDesc" id="prdOne1"></p>
    
    </div>
    
    <div class="prdPrice" id="prdOne2"></div>
    
    <div class="prdQuantity">
    
    <input type="number" value="0" min="0">
    
    </div>
    
    <div class="prdRemoval">
    
    <button class="rPrd">
    
    Remove
    
    </button>
    
    </div>
    
    <div class="prdLNPrice">0.00</div>
    
    </div>

    <div class="product">
    
    <div class="prdImg">
    
    <img src="https://polygonkight.files.wordpress.com/2013/07/04-jellyfish.png">
    
    </div>
    
    <div class="prdDetails">
    
    <div class="prdTitle" id="prdThird"></div>
    
    <p class="prdDesc" id="prdThird1"></p>
    
    </div>
    
    <div class="prdPrice" id="prdThird2"></div>
    
    <div class="prdQuantity">
    
    <input type="number" value="0" min="0">
    
    </div>
    
    <div class="prdRemoval">
    
    <button class="rPrd">
    
    Remove
    
    </button>
    
    </div>
    
    <div class="prdLNPrice">0.00</div>
    
    </div>
    
    <div class="t">
    
    <div class="tItem">
    
    <span>Subtotal</span>
    
    <div class="tValue" id="cSubtotal"></div>
    
    </div>
    
    <div class="tItem">
    
    <span>Tax (7.5%)</span>
    
    <div class="tValue" id="cTax"></div>
    
    </div>
    
    </div>
    
    <div class="iTotals">
    
    <span>Grand Total</span>
    
    <div class="tValue" id="cTotal"></div>
    
    </div>
    
    <div id="credit"></div>
    
    </div>
        
        <button class="checkout">Checkout</button>

  </div>
 
 <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.0/jquery.min.js"></script>
 
 <script src="shopping_cartJS.js"></script>
<script> // Create objects 
var cartItems = {
  title: "Futuristic Jellyfish",
  description: "Born in the past yet back from the future, this jellyfish has the ability time travel one second every five minutes. On top of it's cool color scheme, it's GLUTEN FREE!",
  price: 56.99
}
var cartItems1 = {
  title: "Andriod Camera Quality Jellyfish",
  description: "This potato quality jellyfish brings all the charm of a 144 pixel youtube video, combined with the aesthetic of a terribly funded ATARI game. We don't know why people want it, but what we do know is that you will buy it.",
  price: 1000.01
}
var cartItems2 = {
  title: "Super Sayian Jellyfish",
  description: "From the depths of the ocean, we bring to you Super Sayian 45 Jellyfish. It has the ability to destroy universes, travel faster than the speed of light, conjour huge balls of energy, and most importantly, significantly increase its power by screaming ear-piercingly loud for 30 minutes to an hour.",
  price: 9001.02
}
//Turn objects into strinsgs and print onto the HMTL
var cartItemsJSON = JSON.stringify(cartItems.title);
var cartItemsJSON1 = JSON.stringify(cartItems.description);
var cartItemsJSON2 = JSON.stringify(cartItems.price);
$('#prdOne').html(cartItemsJSON);
$('#prdOne1').html(cartItemsJSON1);
$('#prdOne2').html(cartItemsJSON2);

var cartItems1JSON = JSON.stringify(cartItems1.title);
var cartItems1JSON1 = JSON.stringify(cartItems1.description);
var cartItems1JSON2 = JSON.stringify(cartItems1.price);
$('#prdSecond').html(cartItems1JSON);
$('#prdSecond1').html(cartItems1JSON1);
$('#prdSecond2').html(cartItems1JSON2);

var cartItems2JSON = JSON.stringify(cartItems2.title);
var cartItems2JSON1 = JSON.stringify(cartItems2.description);
var cartItems2JSON2 = JSON.stringify(cartItems2.price);
$('#prdThird').html(cartItems2JSON);
$('#prdThird1').html(cartItems2JSON1);
$('#prdThird2').html(cartItems2JSON2);

// rates
var taxRate = 0.075;

// Set recalculations functions to the inputs and buttons 
$('.prdQuantity input').change( function() {
  updateQuantity(this);
});

$('.prdRemoval button').click( function() {
  removeItem(this);
});


// Recalculate cart 
function recalculateCart()
{
  var subtotal = 0;
  
  // Sum up row totals
  $('.product').each(function () {
    subtotal += parseFloat($(this).children('.prdLNPrice').text());
  });
  
  // Calculate totals 
  var tax = subtotal * taxRate;
  var total = subtotal + tax; 
  
  // Update totals display 
$('.tValue').html(function() {
    $('#cSubtotal').html(subtotal.toFixed(2));
    $('#cTax').html(tax.toFixed(2));
    $('#cTotal').html(total.toFixed(2));
    if(total > 0){
      $('.checkout').show();
    }else{
      $('.checkout').hide();
    }
    $('.tValue').html();
    if(total > 100){
      $('#credit').html('You may pay cash or credit.');
    } else if (total < 100) {
      $('#credit').html('You GOT to pay cash kid!');
    } else {
      $('#credit').html('YOU BROKE SON, GET A JOB!')
    }
  }); 
}

// Update quantity 
function updateQuantity(quantityInput)
{
  // Calculate line price 
  var productRow = $(quantityInput).parent().parent();
  var price = parseFloat(productRow.children('.prdPrice').text());
  var quantity = $(quantityInput).val();
  var linePrice = price * quantity;
  
  // recalculate totals 
  productRow.children('.prdLNPrice').each(function () {
    $(this).html(function() {
      $(this).text(linePrice.toFixed(2));
      recalculateCart();
    });
  });  
}


// Remove item from cart 
function removeItem(removeButton)
{
  // Remove item and recalculate totals 
  var productRow = $(removeButton).parent().parent();
  productRow.html(function() {
    productRow.remove();
    recalculateCart();
  });
}
//Print totals
$('.checkout').click(function() {
  alert('Your Subtotal is ' + $('#cSubtotal').html());
  alert('Your Tax is ' + $('#cTax').html());
  alert('Your Grand Total is ' + $('#cTotal').html());
}); </script>
</body>

</html>
