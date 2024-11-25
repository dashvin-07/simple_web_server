# EX01 Developing a Simple Webserver

# Date:
# AIM:
To develop a simple webserver to serve html pages and display the configuration details of laptop.

# DESIGN STEPS:
## Step 1:
HTML content creation.

## Step 2:
Design of webserver workflow.

## Step 3:
Implementation using Python code.

## Step 4:
Serving the HTML pages.

## Step 5:
Testing the webserver.

# PROGRAM:

~~~
!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Laptop Specifications</title>
  <style>
    /* Reset default styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    /* Body styling */
    body {
      font-family: 'Arial', sans-serif;
      background: linear-gradient(to right, #f3e5f5, #e1f5fe);
      color: #333;
      padding: 20px;
      text-align: center;
    }

    /* Container styling */
    .specifications-container {
      max-width: 800px;
      margin: 20px auto;
      padding: 20px;
      background-color: white;
      border-radius: 12px;
      box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
    }

    .specifications-container h1 {
      font-size: 28px;
      color: #2c3e50;
      margin-bottom: 20px;
    }

    /* Table styling */
    .spec-table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
    }

    /* Table header styling */
    .spec-table thead {
      background: linear-gradient(to right, #ff6f61, #f06292);
      color: white;
    }

    .spec-table th, .spec-table td {
      padding: 14px;
      text-align: left;
      border: 1px solid #ddd;
    }

    .spec-table th {
      font-size: 18px;
      font-weight: bold;
    }

    /* Table body row colors */
    .spec-table tbody tr:nth-child(1) td {
      background-color: #ffecb3; /* Light yellow */
    }

    .spec-table tbody tr:nth-child(2) td {
      background-color: #b3e5fc; /* Light blue */
    }

    .spec-table tbody tr:nth-child(3) td {
      background-color: #c8e6c9; /* Light green */
    }

    .spec-table tbody tr:nth-child(4) td {
      background-color: #f8bbd0; /* Light pink */
    }

    .spec-table tbody tr:nth-child(5) td {
      background-color: #d1c4e9; /* Light purple */
    }

    .spec-table tbody tr:nth-child(6) td {
      background-color: #ffe0b2; /* Peach */
    }

    .spec-table tbody tr:nth-child(7) td {
      background-color: #b2dfdb; /* Mint green */
    }

    .spec-table td {
      font-size: 16px;
      color: #333;
    }

    /* Hover effect */
    .spec-table tbody tr:hover td {
      background-color: #f1f8e9; /* Light lime */
      transition: background-color 0.3s ease;
    }
  </style>
</head>
<body>
  <div class="specifications-container">
    <h1>Laptop Specifications</h1>
    <table class="spec-table">
      <thead>
        <tr>
          <th>Specification</th>
          <th>Details</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Processor</td>
          <td>13th Gen Intel(R) Core(TM) i5-1335U 1.30 GHz</td>
        </tr>
        <tr>
          <td>RAM</td>
          <td>16.0 GB (15.7 GB usable)</td>
        </tr>
        <tr>
          <td>Storage</td>
          <td>350GB SSD</td>
        </tr>
        <tr>
          <td>Display</td>
          <td>15.6-inch Full HD</td>
        </tr>
        <tr>
          <td>Graphics</td>
          <td>NVIDIA GeForce GTX 1650</td>
        </tr>
        <tr>
          <td>Battery Life</td>
          <td>Up to 10 hours</td>
        </tr>
        <tr>
          <td>Operating System</td>
          <td>Windows 11 Home</td>
        </tr>
      </tbody>
    </table>
  </div>
</body>
</html>
~~~
## OUTPUT:
![Screenshot 2024-11-25 141113](https://github.com/user-attachments/assets/0d231b17-2d68-41c6-ae9d-9fa3e7a4cb43)

# RESULT:
The program for implementing simple webserver is executed successfully.
