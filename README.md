<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <title>Seatwork 2</title>
    <style>
        body {
            background-image: url('https://images.squarespace-cdn.com/content/v1/664c7ae50eea9c731b37e817/9804865a-f6de-47d0-b463-c569491b9621/OBMC+MONTESSORI+FV+1+-+AY+2026+FA.jpg');
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            min-height: 100vh;
        }
    </style>
</head>
<body>
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid">
    <a class="navbar-brand" href="#"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTdUNCgZLlwPBRL3cJP6tslfmdJxOAwIlNMASao2XZiYsz9coLxYUHWrEU&s=10" class="img-fluid rounded-circle" style=" height: 60px; width: 60px;"></a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#mynavbar">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="mynavbar">
      <ul class="navbar-nav me-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">HOME</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">ABOUT</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">CONTACT</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">SEARCH</a>
        </li>
      </ul>
      <form class="d-flex">
        <button class="btn btn-primary" type="button">PORTAL</button>
      </form>
    </div>
  </div>
</nav>
<body>
 <h1 class="schedule-title">Office Hours Schedule</h1>
    <table>
        <thead>
            <tr>
                <th>Day</th>
                <th>Office Hours</th>
                <th>Department</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Monday</td>
                <td>8:00 AM – 4:00 PM</td>
                <td>Registrar's Office</td>
            </tr>
            <tr>
                <td>Tuesday</td>
                <td>8:00 AM – 4:00 PM</td>
                <td>Accounting Office</td>
            </tr>
        </tbody>
    </table>
<style>
    .contact {
      box-sizing: border-box;
      width: min(100%, 320px);
      margin-left: auto;
      padding: 24px;
      background: #eeeeee;
      border: 1px solid #cccccc;
    }
    input { box-sizing: border-box; width: 100%; margin: 8px 0 16px; }
  </style>
</head>
<body>
  <section class="contact">
  </style>

    <h2 class="form-title">Contact Us</h2> 
      <form action="/submit-form-endpoint" method="POST"></form>
       <div>
        <label for="name">Full Name</label>
        <input type="text" id="name" name="user_name" placeholder="Renn SANTOS" required>
    </div>

   
    <div>
        <label for="email">Email Address</label>
        <input type="email" id="email" name="user_email" placeholder="name@gmail.com" required>
    </div>
    
    <button type="submit">Subnit</button>
    </form>

</body>
</html>
