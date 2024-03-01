<script>


</script>

<nav>
  <a href="#home">
    <img class="logo" src="/logo.png" alt="Logo" />
  </a>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#about">About</a></li>
    </ul>
  </nav>
  
  <style>
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 2rem;
      margin: 0 8rem 0 8rem;
    }
  
    nav a {
      color: #fff;
      text-decoration: none;
      transition: color 0.3s ease-in-out;
      font-family: "Josefin Sans", sans-serif;
      text-transform: uppercase;
    }
  
    nav a:hover {
      color: #a1ccdc;
    }
  
    .logo {
      width: 8rem;
      height: auto;
    }
  
    ul {
      display: flex;
      list-style-type: none;
      margin: 0;
      padding: 0;
    }
  
    li {
      margin-left: 20px;
    }
  
    a {
      text-decoration: none;
      color: #fff;
    }
  
    @media (max-width: 768px) {
      nav {
        justify-content: center; 
        margin: 0;
      }
  
      .logo {
        display: none;
      }
  
      ul {
        width: 100%;
        justify-content: center;
      }
  
      li {
        margin: 0 10px;
      }
    }
  </style>