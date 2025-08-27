<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Struktur HTML & CSS Flex</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 20px;
      background: linear-gradient(135deg, #74ebd5, #ACB6E5);
    }

    .container {
      display: flex;
      flex-direction: column;
      gap: 15px;
    }

    /* HEADER */
    .header {
      padding: 20px;
      text-align: center;
      border-radius: 20px;
      font-size: 1.8rem;
      font-weight: 600;
      color: white;
      background: linear-gradient(90deg, #0096c7, #00b4d8);
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }
