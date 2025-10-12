<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" integrity="" crossorigin="anonymous">

<meta name="viewport" content="width=device-width, initial-scale=1">
<title>OKFlip Business Card</title>
<style>

body {
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
  background: black;  
  justify-content: center;
  padding: 20px;
  color: #fff;
}
.card {
      width: 400px;
      background:	#008080;
      margin: 40px auto;
      color: black;
      padding: 25px;
      border-radius: 20px;
      box-shadow:  0 10px 25px rgba(0,0,0,0.5);
      overflow: hidden;
      text-align: center;
      position: relative;
      padding-bottom: 15px;
/* Logo area */
.logo {
  background: lightgray;
 
  border-bottom-left-radius: 60px;
  border-bottom-right-radius: 60px;
}

.logo img {
  height: 70px;
    }
.logo p {
  margin: 2px 0;
  font-size: 13px;
  color: #fff;
}
/* Views bubble */
.views {
  position: absolute;
  top: 12px;
  right: 15px;
  background: #00bcd4;
  color: #fff;
  font-size: 13px;
  padding: 6px 10px;
  border-radius: 20px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.3);
}


/* MD image and name */
.mdimage {
  margin-top: 15px;
  text-align: center;
}
.mdimage img {
  width: 120px;
  height: 120px;
  object-fit: cover;
  border-radius: 50%;
  border: 3px solid #00bcd4;
  box-shadow: 0 5px 15px rgba(0,188,212,0.4);
  margin-bottom: 15px;
}

.mdimage h2 {
  font-size: 20px;
  font-weight: 700;
  color: #00bcd4; /* Name color */
  margin-bottom: 10px;
}


/* Buttons row */
.buttons {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 10px;
  margin: 15px 20px;
}

.buttons a {
  text-decoration: none;
  color: #fff;
}

.buttons button {
  background: #007bff;
  border: none;
  padding: 8px 16px;
  border-radius: 8px;
  cursor: pointer;
  font-weight: 500;
  transition: 0.3s;
}

.buttons button:hover {
  background: #0056b3;
}

/* Info Section */
.info {
  background: #111;
  padding: 15px 25px;
  font-size: 14px;
  color: #ccc;
  line-height: 1.6;
  border-radius: 12px;
  margin: 0 20px 15px;
  text-align: left;
}

.info a {
  color: #00bcd4;
  text-decoration: none;
}
/* Bottom Buttons */
.bottom-buttons {
  display: flex;
  justify-content: space-between;
  margin: 0 20px;
}

.bottom-buttons button {
  flex: 1;
  margin: 5px;
  background: #333;
  color: #fff;
  border: none;
  padding: 10px;
  border-radius: 8px;
  cursor: pointer;
  transition: 0.3s;
}

.bottom-buttons button:hover {
  background: #00bcd4;
}

/* Responsive */
@media (max-width: 480px) {
  .card {
    width: 90%;
  }
}
.about
{background: lightblue;
  padding: 20px;
  border-radius: 12px;
  max-width: 500px;
  margin: 20px auto;
  box-shadow: 0 2px 8px rgba(0,0,0,5);
    }
    h2 {
        font-size: 28px;
    color: #333;
    margin-bottom: 10px;
    }
    p {
    color: #555;
    font-size: 16px;
    line-height: 1.7;
    }
    ul {
        list-style-type: circle;
        padding-left: 20px;
    }
.about .btn:hover {
    background: #1565c0;
  }
 .payment-container {
        max-width: 400px;
        
        padding: 25px;
        border-radius: 8px;
        box-shadow: 0 2px 8px rgba(0,0,0,0);
    }
    h2 {
        color: white;
    }
    .details {
        margin: 10px 0;
    }
    .details span {
        font-weight: bold;
    }
   img {
        max-width: 100%;
        margin-top: 5px;
    }
    /* Product Gallery */
 .Product-container {

  background: lightblue;
  padding: 20px;
  border-radius: 12px;
  max-width: 500px;
  margin: 20px auto;
  box-shadow: 0 2px 8px rgba(0,0,0,5);

}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); /* smaller card size */
  gap: 20px;
  justify-content: center; /* center align grid */
}

.card {
 background: #d4ebf2; /* soft color */
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
  overflow: hidden;
  display: flex;
  flex-direction: column;
  transition: all 0.3s ease;
  width: 240px;            /* smaller card */
  margin: auto;            /* center each card */
}

.card:hover {
  transform: translateY(-6px);
  box-shadow: 0 6px 18px rgba(0,0,0,0.25);
}

.thumb {
  width: 100%;
  aspect-ratio: 4 / 3;
  object-fit: cover;
  display: block;
}

.content {
  padding: 10px 12px;
  display: flex;
  flex-direction: column;
  gap: 6px;
  flex: 1;
  text-align: center; /* centers all text */
}

.name {
  font-weight: 600;
  font-size: 0.1rem;
  color: #333;
}

.meta {
  color: #555;
  font-size: 0.9rem;
}

.price-row {
  display: flex;
  align-items: center;
  justify-content: center; /* center prices */
  gap: 10px;
  margin-top: 5px;
}

.price {
  font-weight: 600;
  color: #000;
}

.mrp {
  font-size: 0.85rem;
  color: gray;
  text-decoration: line-through;
}

.actions {
  display: flex;
  justify-content: center; /* center buttons */
  gap: 10px;
  margin-top: 10px;
}

.btn {
  border: 0;
  background: #0b5cff;
  color: #fff;
  padding: 6px 14px;
  border-radius: 6px;
  font-weight: 600;
  cursor: pointer;
  transition: background 0.3s;
}

.btn:hover {
  background: #0847c2;
}

.tag {
  background: #eef2ff;
  color: #0b5cff;
  padding: 2px 10px;
  border-radius: 999px;
  font-size: 0.75rem;
  align-self: center;
}
  a.card-link {
    text-decoration: none;
    color: inherit;
  }

    /* 📸 Gallery Section */
    .gallery {
      background: lightblue;
  padding: 20px;
  border-radius: 12px;
  max-width: 500px;
  margin: 20px auto;
  box-shadow: 0 2px 8px rgba(0,0,0,5);
    }
    .gallery h3 {
      font-size: 18px;
      margin-bottom: 10px;
      color: #333;
    }
    .gallery-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 8px;
    }
    .gallery-grid img {
      width: 100%;
      border-radius: 8px;
      transition: 0.3s;
    }
    .gallery-grid img:hover {
      transform: scale(1.05);
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }
/* Video Section */
.video {
  background: lightblue;
  padding: 30px;
  border-radius: 12px;
  max-width: 400px;
  margin: 20px auto;
  box-shadow: 0 2px 8px rgba(0,0,0,5);
}
.video h3 {
  font-size: 16px;
  color: #0f172a;
  margin-bottom: 8px;
}
.video iframe {
  width: 100%;
  height: 200px;
  border-radius: 10px;
}
 .payment-container {
background: lightblue;
  padding: 20px;
  border-radius: 12px;
  max-width: 500px;
  margin: 20px auto;
  box-shadow: 0 2px 8px rgba(0,0,0,5);
    }
    h2 {
        color: white;
    }
    .details {
        margin: 10px 0;
    }
    .details span {
        font-weight: bold;
    }
   img {
        max-width: 100%;
        margin-top: 5px;
    }

/* Feedback Section */
.feedback {
  background: lightblue;
  padding: 20px;
  border-radius: 12px;
  max-width: 500px;
  margin: 20px auto;
  box-shadow: 0 2px 8px rgba(0,0,0,5);
}

.feedback h3 {
  text-align: center;
  margin-bottom: 15px;
  color: green;
}

.feedback form {
  display: flex;
  flex-direction: column;
  gap: 10px;
}

.feedback input, .feedback textarea {
  padding: 3px;
  border: 2px solid #ddd;
  border-radius: 6px;
  font-size: 14px;
  width: 100%;
}

.feedback button {
  background: #0ea5a4;
  color: white;
  padding: 12px;
  border: none;
  border-radius: 8px;
  font-size: 16px;
  font-weight: bold;
  cursor: pointer;
  transition: 0.3s;
}

.feedback button:hover {
  background: #0c8c8b;
}

/* Enquiry Section */
.enquiry {
background: lightblue;
  padding: 20px;
  border-radius: 12px;
  max-width: 500px;
  margin: 20px auto;
  box-shadow: 0 2px 8px rgba(0,0,0,5);
}
.enquiry h3 {
  font-size: 16px;
  color: #0f172a;
  margin-bottom: 8px;
}
.enquiry form input, .enquiry form textarea {
  width: 100%;
  padding: 8px;
  margin-bottom: 8px;
  border-radius: 6px;
  border: 1px solid #ccc;
}
.enquiry form button {
  padding: 8px 12px;
  background: #0ea5a4;
  color: white;
  border: none;
  border-radius: 6px;
  cursor: pointer;
}

/* Share Section */
    .social {
    background: lightblue;
  padding: 20px;
  border-radius: 12px;
  max-width: 500px;
  margin: 20px auto;
  box-shadow: 0 2px 8px rgba(0,0,0,5);
    }
 .social h3 {
      font-size: 18px;
      margin-bottom: 10px;
      color: #333;
}
    .social a {
      text-decoration: none;
      font-size: 20px;
      color: #fff;
      padding: 12px;
      border-radius: 50%;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      width: 30px;
      height: 30px;
      transition: 0.3s;
    }
    .social a:hover {
      opacity: 0.8;
      transform: scale(1.1);
    }
    .facebook { background: #3b5998; }
    .instagram { background: #e4405f; }
    .linkedin { background: #0077b5; }
    .whatsapp { background: #25d366; }
    .pinterest { background: #bd081c; }
    .blogger { background: #f57d00; }
    .twitter { background: #1da1f2; }
    .snapchat { background: #fffc00; color: #000; }
    .youtube { background: #bd081c; }
  
    

/* Footer Menu */
.footer-menu {
  display: flex;
  justify-content: space-around;
  background: #0ea5a4;
}
.footer-menu a {
  color: white;
  text-decoration: none;
  font-size: 14px;
  padding: 10px 0;
  flex: 1;
  text-align: center;
}
.footer-menu a:hover {
  background: #089191;
}


/* Footer Menu Bar */
.footer-menu {
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%;
  background: #0ea5a4;
  display: flex;
  justify-content: space-around;
  align-items: center;
  border-top: 2px solid #0c8c8b;
  z-index: 9999;
}

.footer-menu a {
  flex: 1;
  text-align: center;
  color: white;
  text-decoration: none;
  padding: 8px 0;
  font-size: 12px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.footer-menu a i {
  font-size: 20px;
  margin-bottom: 4px;
}

.footer-menu a:hover {
  background: #089191;
  transition: 0.3s;
}

/* Responsive footer labels */
@media (max-width: 500px) {
  .footer-menu a span {
    display: none;
  }
}

</style>
</head>
<body>
  <div class="card" id="card">
    <div class="views">👁️ Views: 328</div>

    <div class="logo">
      <img src="C:\Users\a2z\Desktop\New folder\image\logo.png" alt="Logo">
	<p>Life, Nothing Else</p>
	<p>सर्वे भवन्तु सुखिनः सर्वे सन्तु निरामयाः</p>
   </div>
<div class="mdimage">
<h2>Okflip India Pvt. ltd</h2>
 <img src="C:\Users\a2z\Desktop\Bussiness 2\image\Dr. J. R. Meena (1).jpg" alt="MD Image">

   <div class="buttons">
      <button><a href="tel:+919462431760">📞 Call</a></button>
      <button><a href="https://wa.me/919462431760">💬 WhatsApp</a></button>
      <button><a href="https://maps.google.com">📍 Direction</a></button>
      <button><a href="mailto:fssindia2015@gmail.com">✉️ Mail</a></button>
    </div>

    <div class="info">
     <a href="https://www.google.com/maps/place/OKFLIP+INDIA+PVT+LTD+,Head+Office-Jaipur/@26.9210918,75.7507671,17z/data=!3m1!4b1!4m6!3m5!1s0x396db30061cadadb:0x9fd373f1b18e1c2d!8m2!3d26.921087!4d75.753342!16s%2Fg%2F11y3jfls3z?entry=ttu&g_ep=EgoyMDI1MTAwMS4wIKXMDSoASAFQAw%3D%3D"> 📍LG-09, Sankalp Tower,Jharkhand Mod,Vaishali Nagar, Jaipur-302021 (Raj.) India</a><br>
 <a href="https://okflip.com/UI/Default.aspx"> 🌐 https://okflip.com<br></a>
<a href="mailto:fssindia2015@gmail.com">✉️ fssindia2015@gmail.com</a>
    </div>
    <div class="bottom-buttons">
      <button>📱 Add to Phone Book</button>
      <button>💾 Save Card</button>
    </div>
</div>

    <!-- About Us -->
    <div class="about" id="about">
    <h3>About</h3>
    <p><strong>Company Name:</strong> Okflip India Pvt Ltd</p>
    <p><strong>Year of Establishment:</strong> 2021</p>
    <p><strong>GST Number:</strong> 08AADCO4528M1Z3</p>
    <p><strong>Nature of Business:</strong> Manufacturer</p>
    <div class="specialities">
      <strong>Specialities:</strong>
      <ul>
        <li>Premium quality products</li>
        <li>Natural & safe formulations</li>
        <li>Ayurvedic + modern science blend</li>
        <li>Health & Wellness Products</li>
        <li>Home Appliances</li>
        <li>Skincare & Personal Care</li>
	<li>Immunity boosting products</li>
        <li>Affordable pricing</li>
        <li>ISO & GMP Certified</li>
        <li>Advanced hydration with pH-balanced, mineral-rich water.</li>
        <li>Natural remedies for vitality, stress relief, kidney care, and overall wellness.</li>
        <li>Safe, natural, and chemical-free solutions.</li>
      </ul>
</div>
    <p>Our commitment is to blend innovation, quality, and trust to improve everyday life for individuals and communities across India.</p>
</div>

   <!-- Product -->
 <div class="Product-container" id="product">
    <div class="header">
      <h3>Okflip - Top 10 Products</h3>
     </div>

    <div id="grid" class="grid" aria-live="polite"></div>
  </div>

  <script>
    // Product data (from your list)
    const products = [
  	{id:1,name:'OKFLIP ALKALINE PURIFIER',price:'₹49,297',mrp:'MRP ₹59,297 with tax)' ,img:'https://okflip.com/Upload/ProductImages/Actual/4.png' ,link:'https://okflip.com/UI/ProductDetails.aspx?ID=4'},

       {id:28,name:'ALKALINE OKFLIP IONIZER 5 PLATE(NEW MODEL)',price:'₹1,29,850',mrp:'₹1,49,850.00(with tax)',img:'https://okflip.com/Upload/ProductImages/Actual/28_Img1.jpg',link:'https://okflip.com/UI/ProductDetails.aspx?ID=28'},

      {id:26,name:'OKFLIP WATER IONIZER 7 PLATE(NEW MODEL)',price:'₹1,99,500',mrp:'MRP ₹2,49,950.00',img:'https://okflip.com/Upload/ProductImages/Actual/26.png',link:'https://okflip.com/UI/ProductDetails.aspx?ID=26'},     

      {id:4,name:'BONEFIGHTER ARTHO OIL',price:'₹290',mrp:'MRP ₹348',img:'https://okflip.com/Upload/ProductImages/Actual/11.png',link:'https://okflip.com/UI/ProductDetails.aspx?ID=11'},
     
	{id:68,name:'BONEFIGHTER 1000ML',price:'₹1,310',mrp:'MRP ₹1,549.00 ',img:'https://okflip.com/Upload/ProductImages/Actual/68_Img3.png',link:'https://okflip.com/UI/ProductDetails.aspx?ID=68'}, 

{id:12,name:'RED ONION OIL',price:'₹499',mrp:'MRP ₹549',img:'https://okflip.com/Upload/ProductImages/Actual/12.jpg',link:'https://okflip.com/UI/ProductDetails.aspx?ID=12'},

         {id:7,name:'YOUNGER BLAST',price:'₹1,834',mrp:'MRP ₹1,981',img:'https://okflip.com/Upload/ProductImages/Actual/7_Img3.png',link:'https://okflip.com/UI/ProductDetails.aspx?ID=7'},
      {id:7,name:'OKFLIP GAS SAFETY DEVICE',price:'₹3,950',mrp:'MRP ₹4,550',img:'https://okflip.com/Upload/ProductImages/Actual/15_Img2.png',link:'https://okflip.com/UI/ProductDetails.aspx?ID=15'},
      {id:23,name:'OKFLIP CARDIACPRO',price:'₹1,680',mrp:'MRP 1,867',img:'https://okflip.com/Upload/ProductImages/Actual/23.png' ,link:'https://okflip.com/UI/ProductDetails.aspx?ID=23'},
      {id:73,name:'LIVERPRO 1000ML',price:'₹1,496',mrp:'MRP ₹1,868',img:'https://okflip.com/Upload/ProductImages/Actual/73.png',link:'https://okflip.com/UI/ProductDetails.aspx?ID=19'},
      {id:21,name:'ENERGYPRO',price:'₹3,950',mrp:'MRP ₹4,399',img:'https://okflip.com/Upload/ProductImages/Actual/21.jpg',link:'https://okflip.com/UI/ProductDetails.aspx?ID=21'}
    ];

    // NOTE: I added the real product detail page URLs (link:) for each card above.
    // I could not reliably extract hosted product image URLs from okflip.com (some pages block scraping),
    // so the current img values are placeholders. If you want, I can:
    // - replace placeholders with exact image URLs if you allow me to fetch each product page screenshot or
    // if you can share the image files; OR
    // - point img to a likely path on the site (e.g. /Upload/Product/...) if you want me to try guessed paths.
    // The "Buy Now" button (below) will open the real product page using the link field.


    const grid = document.getElementById('grid');

   function createCard(p){
  const link = document.createElement('a');
  link.href = p.link;
  link.target = "_blank";
  link.className = "card-link";

  const card = document.createElement('article');
  card.className = 'card';
  card.setAttribute('aria-label', p.name);

      const img = document.createElement('img');
      img.className = 'thumb';
      img.alt = p.name;
      img.src = p.img;

      const box = document.createElement('div');
      box.className = 'content';

      const title = document.createElement('h3');
      title.className = 'name';
      title.textContent = p.name;

      const meta = document.createElement('div');
      meta.className = 'meta';
      meta.textContent = 'Product ID: ' + p.id;

      const priceRow = document.createElement('div');
      priceRow.className = 'price-row';

      const left = document.createElement('div');
      const price = document.createElement('div');
      price.className = 'price';
      price.textContent = p.price;
      const mrp = document.createElement('span');
      mrp.className = 'mrp';
      mrp.textContent = p.mrp;
      left.appendChild(price);
      left.appendChild(mrp);

      const actions = document.createElement('div');
      actions.className = 'actions';

      const buy = document.createElement('button');
      buy.className = 'btn';
      buy.type = 'button';
      buy.textContent = 'Buy Now';
      buy.onclick = ()=> window.open(p.link, "_blank");

      const tag = document.createElement('div');
      tag.className = 'tag small';
      tag.textContent = 'View';

      actions.appendChild(buy);
      actions.appendChild(tag);

      priceRow.appendChild(left);
      priceRow.appendChild(actions);

      box.appendChild(title);
      box.appendChild(meta);
      box.appendChild(priceRow);

      card.appendChild(img);
      card.appendChild(box);

      link.appendChild(card);
  return link;
    }

    // render
    products.forEach(p=> grid.appendChild(createCard(p)));
  </script>


<!-- 📸 Gallery Section -->
    <div class="gallery" id="gallery">
      <h3>My Gallery</h3>
      <div class="gallery-grid">
 <img src="C:\Users\a2z\Desktop\Bussiness 2\image\OKFLIP INCORPORATION_page-0001.jpg" alt="Gallery 4">
        <img src="C:\Users\a2z\Desktop\Bussiness 2\image\CERT - OKFLIP INDIA - ISO 9001 (1) (1)_page-0001.jpg" alt="Gallery 1">
        <img src="C:\Users\a2z\Desktop\Bussiness 2\image\I START_page-0001.jpg" alt="Gallery 2">
        <img src="C:\Users\a2z\Desktop\Bussiness 2\image\STARTUP CERTIFICATE (2) (1)_page-0001.jpg" alt="Gallery 3">
        
        <img src="C:\Users\a2z\AppData\Local\Temp\0e8e4d7d-032c-40ed-bb06-667a15450a80_ilovepdf_pages-to-jpg (1).zip.a80\Food Safety and Standards_page-0001.jpg" alt="Gallery 5">
       
      
      </div>
    </div>
<!-- Payment -->
   <div class="payment-container" id="payment">
    	<h3>Payment</h3>
   	 <div class="details"><span>Bank Name:</span> 	HDFC Bank Ltd</div>
   	 <div class="details"><span>IFSC Code:</span> 	HDFC0001329</div>
    	 <div class="details"><span>Account Name:</span> OKFLIP INDIA PVT.LTD.</div>
    	<div class="details"><span>Account Number:</span> 50200058134787</div>
   	 <div class="details"><span>Account Type:</span> CURRENT ACCOUNT</div>
   	 <div class="details"><span>QR Code:</span></div>
  	  <img src="C:\Users\a2z\Desktop\New folder\image\WhatsApp Image 2025-10-03 at 16.04.11_c3fd5dac.jpg" alt="QR Code">
    </div>
    <!-- Video -->
    <div class="video" id="video">
      <h3>Watch Video</h3>
  
    <iframe width="560" height="315" src="https://www.youtube.com/embed/z5sv-rYEqbA?si=3idg6FMM-bcsQ6Tk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe><br>

   <iframe width="560" height="315" src="https://www.youtube.com/embed/k7EJBZSzQiE?si=PnUpsxGKm02-QjSh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe><br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/6_op15e9fk0?si=t2Qz6TcQtEktGhTd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe><br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/oKjyDH7qneA?si=yiD9kyqGywJA_gFq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe><br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/wjUzW1k6d7U?si=Y_K2MWHQ5Kgg7VG0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/wjUzW1k6d7U?si=Y_K2MWHQ5Kgg7VG0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
   
    </div>

    <!-- Feedback Section -->
<div class="feedback" id="feedback">
  <h3>💬 Share Your Feedback</h3>
  <form action="submit-feedback.php" method="post">
    <label for="name">Your Name</label>
    <input type="text" id="name" name="name" placeholder="Enter your name" required>
    
    <label for="email">Your Email</label>
    <input type="email" id="email" name="email" placeholder="Enter your email" required>
    
    <label for="message">Your Feedback</label>
    <textarea id="message" name="message" rows="4" placeholder="Write your feedback here..." required></textarea>
    
    <button type="submit">Send Feedback</button>
  </form>
</div>

    <!-- Enquiry -->
    <div class="enquiry" id="enquiry">
      <h3>Enquiry</h3>
      <form>
        <input type="text" placeholder="Your Name">
        <input type="email" placeholder="Your Email">
        <textarea placeholder="Your Message"></textarea>
        <button type="submit">Send Enquiry</button>
      </form>
    </div>

    <!-- Share -->
    <div class="social" id="social">
      <a href="https://www.facebook.com/people/Okflip-India-Pvt-Ltd/61559059526350/?mibextid=wwXIfr&rdid=SI2F3ruU4k3elErt&share_url=https%3A%2F%2Fwww.facebook.com%2Fshare%2F19sgbTGkEh%2F%3Fmibextid%3DwwXIfr" target="_blank" class="facebook"><i class="fab fa-facebook-f"></i></a>
      <a href="https://www.instagram.com/_okflip_india_official/" target="_blank" class="instagram"><i class="fab fa-instagram"></i></a>
      <a href="https://www.linkedin.com/in/okflip-india-b91109388" target="_blank" class="linkedin"><i class="fab fa-linkedin-in"></i></a>
      <a href="https://wa.me/919876543210" target="_blank" class="whatsapp"><i class="fab fa-whatsapp"></i></a>
      <a href="https://pinterest.com/yourprofile" target="_blank" class="pinterest"><i class="fab fa-pinterest-p"></i></a>
      <a href="https://okflip.blogspot.com/2025/" target="_blank" class="blogger"><i class="fab fa-blogger-b"></i></a>
      <a href="https://x.com/Okflip_India23" target="_blank" class="twitter"><i class="fab fa-x-twitter"></i></a>
      <a href="https://www.snapchat.com/@okflip_india" target="_blank" class="snapchat"><i class="fab fa-snapchat-ghost"></i></a>
      <a href="https://youtube.com/@fighterguru?si=c7usHBk0_tTjEvUX" target="_blank" class="youtube"><i class="fab fa-youtube"></i></a>
      
</div>
  <!-- Footer Menu -->
<!-- Footer Menu with Icons -->
  <div class="footer-menu">
    <a href="#card"><i class="fa-solid fa-house"></i><span>Home</span></a>
    <a href="#about"><i class="fa-solid fa-user"></i><span>About</span></a>
    <a href="#product"><i class="fa-solid fa-cart-shopping"></i><span>Product</span></a>
    <a href="#gallery"><i class="fa-solid fa-layer-group"></i><span>Gallary</span></a>
    <a href="#payment"><i class="fa-brands fa-google-pay"></i><span>Payment</span></a>
    <a href="#video"><i class="fa-solid fa-video"></i><span>Videos</span></a>
    <a href="#feedback"><i class="fa-solid fa-comment-dots"></i><span>Feedback</span></a>
    <a href="#enquiry"><i class="fa-solid fa-envelope"></i><span>Enquiry</span></a>
    <a href="#social"><i class="fa-solid fa-share"></i><span>Share</span></a>     
</div>
<footer style="text-align:center; padding:2px; background:lightblue; color:white; font-size:10px;">
  <p>&copy; 2025 <strong>OKFLIP India Pvt. Ltd.</strong> | All Rights Reserved.</p>
  <p>Designed with ❤️ by <a href="#" style="color:#00bcd4; text-decoration:none;">OKFLIP Team</a></p>
</footer>
</body>
</html>
                                                                                                                                                                                                                                                                                                                  
