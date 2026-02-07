<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Valentine</title>
  <link rel="stylesheet" href="style.css">
  <link href="https://fonts.googleapis.com/css2?family=Rubik+Puddles&display=swap" rel="stylesheet">
</head>
<body>
  <div class="card">
    <div class="heart">🩷</div>
    <h1>
      I'm willing to wait for you<br>
      but would I still win<br>
      if I still wait?
    </h1>
    <div class="buttons">
      <a href="yes.html" class="btn">Yes</a>
      <a href="no.html" class="btn">No</a>
    </div>
  </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Yes</title>
  <link rel="stylesheet" href="style.css">
  <link href="https://fonts.googleapis.com/css2?family=Rubik+Puddles&display=swap" rel="stylesheet">
</head>
<body>
  <div class="card">
    <div class="heart">💗</div>
    <p>
      Oh really? I'm not expecting that you're really gonna choose yes.<br><br>
      I just wanna say sorry if I'm being too jealous,
      but you can just make me stop if it made you uncomfortable.
    </p>
    <h2>Are you uncomfortable?</h2>
    <div class="buttons">
      <a href="comfortable.html" class="btn">No</a>
      <a href="uncomfortable.html" class="btn">Yes</a>
    </div>
  </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Yes</title>
  <link rel="stylesheet" href="style.css">
  <link href="https://fonts.googleapis.com/css2?family=Rubik+Puddles&display=swap" rel="stylesheet">
</head>
<body>
  <div class="card">
    <div class="heart">💔</div>
    <p>If that's the case...<br>I guess I'm out..</p>
  </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Comfortable</title>
  <link rel="stylesheet" href="style.css">
  <link href="https://fonts.googleapis.com/css2?family=Rubik+Puddles&display=swap" rel="stylesheet">
</head>
<body>
  <div class="card">
    <div class="heart">❤️</div>
    <p>I'm really glad to hear that.<br>Thank you for understanding me.</p>
  </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Uncomfortable</title>
  <link rel="stylesheet" href="style.css">
  <link href="https://fonts.googleapis.com/css2?family=Rubik+Puddles&display=swap" rel="stylesheet">
</head>
<body>
  <div class="card">
    <div class="heart">💞</div>
    <p>Thank you for being honest.<br>I really appreciate you telling me.</p>
  </div>
  body {
  margin: 0;
  height: 100vh;
  background: linear-gradient(135deg, #ff7eb3, #ff758c);
  display: flex;
  justify-content: center;
  align-items: center;
  font-family: 'Rubik Puddles', cursive;
  text-align: center;
  color: #4b1020;
}

.card {
  background: #fff0f5;
  padding: 40px;
  border-radius: 30px;
  max-width: 450px;
  box-shadow: 0 20px 40px rgba(0,0,0,0.25);
  animation: pop 0.8s ease;
}

.heart {
  font-size: 3rem;
  margin-bottom: 15px;
}

.buttons {
  margin-top: 20px;
}

.btn {
  display: inline-block;
  text-decoration: none;
  background: #ff3f6c;
  color: white;
  padding: 12px 26px;
  margin: 8px;
  border-radius: 40px;
  font-size: 1.1rem;
  transition: transform 0.2s ease;
}

.btn:hover {
  transform: scale(1.1);
}

@keyframes pop {
  from { opacity: 0; transform: scale(0.9); }
  to { opacity: 1; transform: scale(1); }
}body {
  margin: 0;
  height: 100vh;
  background: linear-gradient(135deg, #ff7eb3, #ff758c);
  display: flex;
  justify-content: center;
  align-items: center;
  font-family: 'Rubik Puddles', cursive;
  text-align: center;
  color: #4b1020;
}

.card {
  background: #fff0f5;
  padding: 40px;
  border-radius: 30px;
  max-width: 450px;
  box-shadow: 0 20px 40px rgba(0,0,0,0.25);
  animation: pop 0.8s ease;
}

.heart {
  font-size: 3rem;
  margin-bottom: 15px;
}

.buttons {
  margin-top: 20px;
}

.btn {
  display: inline-block;
  text-decoration: none;
  background: #ff3f6c;
  color: white;
  padding: 12px 26px;
  margin: 8px;
  border-radius: 40px;
  font-size: 1.1rem;
  transition: transform 0.2s ease;
}

.btn:hover {
  transform: scale(1.1);
}

@keyframes pop {
  from { opacity: 0; transform: scale(0.9); }
  to { opacity: 1; transform: scale(1); }
}
