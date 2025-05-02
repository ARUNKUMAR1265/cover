# Ex.06 Book Front Cover Page Design
## Date:2/5/2025

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Book Cover - The Mystery of Tomorrow</title>
  <style>
    body {
      background: #f0f0f0;
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: 'Georgia', serif;
    }

.book-cover {
  width: 300px;
  height: 450px;
  background-image: url('https://images.unsplash.com/photo-1498050108023-c5249f4df085?auto=format&fit=crop&w=600&q=80'); /* NEW BACKGROUND */
  background-size: cover;
  background-position: center;
  ...
}


    .overlay {
      position: absolute;
      inset: 0;
      background: rgba(0, 0, 0, 0.5);
      z-index: 1;
      border-radius: 12px;
    }

    .content {
      position: relative;
      z-index: 2;
    }

    .book-title {
      font-size: 36px;
      font-weight: bold;
      margin-top: 20px;
      letter-spacing: 1px;
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
    }

    .book-author {
      font-size: 18px;
      margin-top: 15px;
      font-style: italic;
    }

    .book-tagline {
      font-size: 16px;
      margin-bottom: 20px;
      color: #e0e0ff;
      font-style: italic;
    }

    .decoration {
      position: absolute;
      top: 20px;
      right: 20px;
      font-size: 24px;
      opacity: 0.4;
      z-index: 2;
    }

.author-photo {
  position: absolute;
  bottom: 5px; /* Increased from 10px */
  right: 5px;  /* Increased from 10px */
  width: 100px; /* You can adjust size */
  height: 100px;
  border-radius: 50%;
  border: 3px solid white;
  object-fit: cover;
  z-index: 3;
}
  </style>
</head>
<body>

<div class="book-cover">
  <div class="overlay"></div>
  <div class="decoration">★</div>
  <div class="content">
    <div class="book-title">The Mystery of Tomorrow</div>
    <div class="book-author">ARUN KUMAR S</div>
    <div class="book-tagline">"A Journey Beyond Time"</div>
  </div>
  <img src="C:\Users\admin\OneDrive\Documents\personal\photo.jpg" alt="Author Photo" class="author-photo">
</div>

</body>
</html>
```


## OUTPUT:
![Screenshot 2025-05-02 073441](https://github.com/user-attachments/assets/10e55540-c65e-4656-b602-fae8cdd81646)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
