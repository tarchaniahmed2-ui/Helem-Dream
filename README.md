<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="verse-box">
        <p class="arabic" id="ayah-text">جاري تحميل الآية...</p>
    </div>

    <script>
        fetch('Ayah_114.txt')
            .then(response => response.text())
            .then(data => {
                document.getElementById('ayah-text').innerText = data;
            })
            .catch(error => console.error('خطأ:', error));
    </script>
</body>
</html>

<img width="720" height="1053" alt="Screenshot_20260525_011645_Photos~2" src="https://github.com/user-attachments/assets/eac97329-ea15-4635-aa3b-17795d528883" />
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>أنوار القرآن - صرح الزليج</title>
    <style>
        body { font-family: 'Arial', sans-serif; text-align: center; background-color: #f4f4f4; padding: 20px; }
        .main-container { max-width: 800px; margin: auto; background: white; padding: 20px; border-radius: 10px; }
        img { width: 100%; height: auto; border-radius: 8px; border: 2px solid #ddd; }
        .verse-box { margin-bottom: 20px; padding: 15px; border-bottom: 2px solid #3498db; }
    </style>


</head>
<body>
    <div class="main-container">
        <h1>أنوار القرآن</h1>
        <div class="verse-box">
            <p>"لَا يُكَلِّفُ اللَّهُ نَفْسًا إِلَّا وُسْعَهَا"</p>
        </div>
        <!-- تم وضع الصورة هنا -->
        <img src="zellige_full.jpg" alt="صرح الزليج الرقمي">
    </div>
</body>
</html>https://github.com/tarchaniahmed2-ui/Helem-Dream.git
