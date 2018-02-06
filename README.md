# SGA0.2
<!DOCTYPE html>
<html>
<head>
<script src="/assets/jquery.js"></script>
<link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet">
<style>
body {
  font-family: helvetica, sans-serif;
  margin: 0 auto;
  max-width: 600px;
  background: #232323;
}
div {
  height: 200px;
  background-size: cover;
  position: relative;
  margin: 40px 0 0 0;
  border-radius: 12px;
}
h1 {
  font-family: 'Montserrat', sans-serif;
  text-align: center;
  font-size: 75px;
  color: #aaaaaa;
  margin: 60px 0 0 0;
}
h2 {
  text-align: center;
  color: #bbbbbb;
  margin: 0px 0 70px 0;
}
p {
  color: rgba(255,255,255,1);
  background: black;
  background: linear-gradient(bottom, rgba(0,0,0,1), rgba(0,0,0,.4));
  background: -webkit-linear-gradient(bottom, rgba(0,0,0,1), rgba(0,0,0,.4));
  background: -moz-linear-gradient(bottom, rgba(0,0,0,1), rgba(0,0,0,.4));
  padding: 10px;
  line-height: 28px;
  text-align: justify;
  position: absolute;
  bottom: 0;
  margin: 0;
  height: 30px;
  transition: height .5s;
  -webkit-transition: height .5s;
  -moz-transition: height .5s;
}

small {
  opacity: 0;
}

.show-description p {
  height: 150px;
}

.show-description small {
  opacity: 1;
}

.pizza{
  background-image: url("https://i.imgur.com/Ue9xzRgh.jpg");
}
.fries{
  background-image: url("https://i.imgur.com/j8K3Oszh.jpg");
}
.fresh{
  background-image: url("https://i.imgur.com/u7eZDTch.jpg");
}
.price {
  float: right;
}
@media (max-width: 500px) {
  h1 {
    font-size: 50px;
    margin-top: 20px;
    line-height: 40px;
  }
  h2 {
    font-size: 20px;
    margin: 20px 0 30px 0;
  }
  div {
    margin: 20px 12px 0 12px;
  }
  p {
    font-size: 20px;
    line-height: 24px;
  }
  small {
    font-size: 16px;
  }
}

</style>

</head>

<body>
<h1>bola's restaurant</h1>
<h2>A Lagos City eatery</h2>
<div class="pizza">
  <p>Ikeja Pizza <span class="price">#1,999</span><br />
  <small>Pizza is a traditional Italian dish consisting of a yeasted flatbread typically topped with tomato sauce and cheese and baked in an oven. It can also be topped with additional vegetables, meats, and condiments, and can be made without cheese.</small></p>
</div>

<div class="fries">
  <p>Abule Fries<span class="price">#1,499</span><br />
  <small>French fries are served hot, either soft or crispy, and are generally eaten as part of lunch or dinner or by themselves as a snack. Fries in America are generally salted and are almost always served with ketchup</small></p>
</div>
  
<div class="fresh">
  <p>Fresh Taste<span class="price">#999</span><br />
  <small>Fresh taste is a dish consisting of various kinds of fruit, sometimes served in a liquid, either in their own juices or a syrup. The chocolate bar is a plus!</small></p>
</div>

<script>
  $('div').on('click', function() {
      $(this).toggleClass('show-description');
  });
</script>

</body>
</html>
