<script>
    // Můžete zde přidat dynamické chování pro menu nebo jiné funkce
  </script>
  

  
  <header>
    <div class="logo">ZOO z postele</div>
    
    <div class="nav-links">
      <a href="/">Mapa</a>
      <a href="/about">Kurzy</a>
      <a href="/services">Encyklopedie</a>
    </div>
  
    <!-- Ikona pro mobilní verzi -->
    <div class="wrapper-hamburger">
      <span></span>
      <span></span>
      <span></span>
    </div>


  </header>

  <style>

header .wrapper-hamburger {
  width: 50px;
  height: 30px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  cursor: pointer;
  margin-right: 20px;
  transition: transform ease 1s;
}
header .wrapper-hamburger span {
  transition: transform ease 1s;
  transition: ease 1s;
  border: 2px solid #000;
}
    /* Základní styly pro záhlaví */
    header {
      background-color: #372e29;
      color: white;
      padding: 1rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
  
    .logo {
      font-size: 1.5rem;
      font-weight: bold;
    }
  
    .nav-links {
      display: flex;
      gap: 1rem;
      font-size: 22px;
    }
  
    .nav-links a {
      color: white;
      text-decoration: none;
    }
  
    /* Mobilní verze */
  
    /* Styl pro zobrazení menu při kliknutí na ikonu na mobilu */
    .nav-links.mobile {
      display: flex;
      flex-direction: column;
      gap: 1rem;
      position: absolute;
      top: 60px;
      right: 0;
      background-color: #333;
      padding: 1rem;
      width: 200px;
    }
  </style>
  