TML/CSS/JavaScript/ReactJS practice exercises

Exercises for lecture #8 Блокова модель документа
В середині exercises створіть піддиректорію lecture-08. В середині lecture-08 створіть файли index.html та README.md. Відредагуйте файл exercises/lecture-08/index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
	<style>
  
  .box { 
		padding-top:    10px; 
		padding-right:  20px; 
		padding-bottom: 25px; 
		padding-left:   20px;  

		margin-top:    25px; 
		margin-right:  20px; 
		margin-bottom: 25px; 
		margin-left:   20px;  
	}
	</style>
</head>
<body>
   <div class="box"></div>
</body>
</html>
Перепишіть властивості padding та margin за допомогою скороченого синтаксу
Обчислити ширину елемента .box
<body>
   <div class="box"></div>
</body>
.box{ 
  width: 300px; 
  padding: 10px; 
  border: dashed 2px green;
}
Обчислити ширину і висоту елемента .first-box
<body>
   <div class="first-box"></div>
</body>
.first-box {
  width: 200px;
  height: 100px;
  border: 8px solid blue;
  padding: 20px;
  background: yellow;
  
}
Обчислити ширину і висоту елемента .second-box
<body>
   <div class="second-box"></div>
</body>
.second-box {
  width: 200px;
  height: 100px;
  border: 8px solid blue;
  background: yellow;
}
Обчислити ширину елемента div
div{
  box-sizing:content-box;
  width: 200px;
  border: 8px solid blue;
  padding: 20px;
  background: yellow;
}
Обчислити ширину контенту елемента div
div{
  box-sizing:border-box;
  width: 200px;
  border: 8px solid blue;
  padding: 20px;
  background: yellow;
}
Маємо таку розмітку:
<style>
  div {
    border: 10px dotted black;
    padding: 15px;
    background: lightblue;
  }
</style>
</head>
<body>
  <div id="example1">
    <p>Правило для example1: фон всередині елемента має простягатися за межі рамки.</p>
  </div>

  <div id="example2">
    <p>Правило для example2: фон всередині елемента має простягатися до внутрішнього краю рамки.</p>
  </div>

  <div id="example3">
    <p>Правило для example3: фон всередині елемента має простягатися до краю поля вмісту.</p>
  </div>
Для кожного з example1б example2, example3 встановити властивість background-clip згідно з правилами, визначеними у відповідному параграфі
Є заголовок з властивістю display: inline-block, який потрібно розбити на два рядки. Його ширина має бути динамічною.
<h1><span>Awesome article</span></h1>