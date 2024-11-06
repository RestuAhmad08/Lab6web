|*Nama|NIM|Kelas|Matkul*|
|----|---|-----|------|
|Restu Sayidina Ahmad|312310431|TI.23.A4|Pemograman Web 1|

Buatlah layout web sederhana menggunakan css frameword (Twitter Bootsrtap).

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Simple Bootstrap Layout</title>
  <!-- Link to Bootstrap CSS -->
  <link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Header -->
  <header class="bg-primary text-white text-center py-3">
    <h1>My Bootstrap Website</h1>
    <p>Simple Layout with Bootstrap</p>
  </header>

  <!-- Main Content Area -->
  <div class="container mt-4">
    <div class="row">
      <!-- Main Content -->
      <div class="col-md-8">
        <h2>Main Content</h2>
        <p>This is the main content section where articles or main information is displayed.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus lacinia odio vitae vestibulum vestibulum.</p>
      </div>

      <!-- Sidebar -->
      <aside class="col-md-4">
        <h3>Sidebar</h3>
        <ul class="list-group">
          <li class="list-group-item">Item 1</li>
          <li class="list-group-item">Item 2</li>
          <li class="list-group-item">Item 3</li>
          <li class="list-group-item">Item 4</li>
        </ul>
      </aside>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-3 mt-4">
    <p>&copy; 2024 My Bootstrap Website. All Rights Reserved.</p>
  </footer>

  <!-- Link to Bootstrap JS and dependencies -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.0.7/dist/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>


Hasilnya

![Layout](https://github.com/user-attachments/assets/f28d6622-5e1b-47ad-ac7f-8dbbe6cbc90b)
