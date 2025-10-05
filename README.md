# Ex.06 Book Front Cover Page Design
## Date:05.10.2027

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
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Book Cover - Manikandan G</title>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;600;800;900&family=Open+Sans:wght@400;600&display=swap" rel="stylesheet">
<style>
  :root{
    --bg:#333235;
    --accent:#e67e22;
    --muted:#cfcfcf;
  }
  *{box-sizing:border-box}
  body{
    margin:20px;
    background:#fafafa;
    font-family: "Open Sans", sans-serif;
  }

  .cover {
    width: 420px;
    height: 640px;
    background: var(--bg);
    color: white;
    border-radius: 4px;
    overflow: hidden;
    position: relative;
    box-shadow: 0 6px 20px rgba(0,0,0,0.25);
    padding: 28px;
    display:flex;
    flex-direction:column;
    justify-content:space-between;
  }

  .top-label{
    display:flex;
    align-items:center;
    gap:12px;
    font-size:13px;
    letter-spacing:0.06em;
    font-weight:600;
    color: #ddd;
  }
  .top-label .line{height:2px; background:var(--accent); flex:1; margin-left:8px; opacity:0.95}

  .title{
    margin-top:12px;
    font-family: "Montserrat", sans-serif;
    font-weight:900;
    line-height:0.95;
    font-size:52px;
    letter-spacing:-1px;
    min-height:150px; /* space reserved for book name */
    display:flex;
    align-items:center;
    justify-content:flex-start;
  }

  .subtitle{
    margin-top:16px;
    max-width:80%;
    color:var(--muted);
    font-size:14px;
    font-weight:600;
  }

  .wave{
    position:absolute;
    left: -20px;
    bottom: 120px;
    width: 480px;
    height: 220px;
    pointer-events:none;
    opacity:0.95;
  }

  .edition {
    margin-top: 6px;
    font-weight:700;
    color:var(--accent);
    font-size:20px;
  }

  .bottom-band{
    background: rgba(0,0,0,0.25);
    padding:16px 20px;
    display:flex;
    align-items:center;
    justify-content:space-between;
    gap:12px;
  }
  .author{
    font-family: "Montserrat", sans-serif;
    font-weight:700;
    font-size:22px;
  }

  .photo-wrap{
    width:84px;
    height:84px;
    border-radius:50%;
    overflow:hidden;
    flex-shrink:0;
    border:4px solid rgba(255,255,255,0.85);
    background: #fff;
  }
  .photo-wrap img{
    width:100%;
    height:100%;
    object-fit:cover;
    display:block;
  }

  .publisher{
    width:92px;
    text-align:center;
    color:#fff;
    font-weight:700;
    font-size:20px;
  }
</style>
</head>
<body style="background-color:burlywood;">
<center>
  <div class="cover">
    <div>
      <div class="top-label">
        EXPERT INSIGHT
        <div class="line"></div>
      </div>

      
      <div class="title">
        Your next chapter
      </div>

      <div class="subtitle">
       "Turning change into opportunity "
      </div>

      <div class="edition">First Edition</div>
    </div>

    <svg class="wave" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg">
      <defs>
        <linearGradient id="g1" x1="0" x2="1">
          <stop offset="0" stop-color="#7ad0d6"/>
          <stop offset="1" stop-color="#bfeaa6"/>
        </linearGradient>
      </defs>
      <g fill="none" stroke="url(#g1)" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" opacity="0.95">
        <path d="M0 120 C80 60, 160 140, 240 110 C320 80, 400 150, 480 110 C560 70, 640 150, 800 110" stroke-opacity="0.18"/>
        <path d="M0 140 C80 80, 160 160, 240 130 C320 100, 400 170, 480 130 C560 90, 640 170, 800 130" stroke-opacity="0.14"/>
        <path d="M0 100 C80 40, 160 120, 240 90 C320 60, 400 130, 480 90 C560 50, 640 130, 800 90" stroke-opacity="0.2"/>
      </g>
    </svg>

    <div class="bottom-band">
      <div class="author">Manikandan G</div>
      <div style="display:flex;align-items:center;gap:12px;">
        
        <div class="photo-wrap">
          <img src="C:\Users\ajith\Pictures\myphoto.jpg" alt="Manikandan G">
        </div>+
        
        <div class="publisher">Packt</div>
      </div>
    </div>
  </div>
</center>
</body>
</html>

```

## OUTPUT:

![alt text](<Screenshot 2025-10-05 223704.png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
