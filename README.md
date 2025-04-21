
## 📸 Gallery Project Documentation

### 📌 Project Description

This project implements an **interactive image gallery** using HTML, CSS, and JavaScript. When a user clicks on an image, a modal window (lightbox) opens with a full-size version of the image. The modal can be closed by pressing the `Escape` key.
 
The modal window is implemented using the [`basicLightbox`](https://basiclightbox.electerious.com/) library.

----------

### ⚙️ Tech Stack
-   HTML5
-   CSS3 (including `transition` and `transform` effects)
-   JavaScript (ES6+)
-   Library: `basicLightbox`
    

----------

### 📁 Project Structure

```plaintext
project/
│
├── index.html               # Main HTML file
├── js/
│   └── gallery.js           # Gallery script
├── css/
│   └── styles.css           # Gallery and modal styles

```

----------

### 🧰 Features

-   Generates a list of images from the `images` array of objects.
    
-   Thumbnail images rendered as `<img>` elements inside a `<ul>` list.
    
-   On image click:
    -   A modal window opens with a full-size image.
    -   Pressing `Escape` closes the modal.
        
-   Hover effect that scales up the image (`scale(1.04)`).
    
-   Custom backdrop styling for the modal window.