<script>
  
  </script>
  
  <section id="home">
    <div class="background-image"></div>
    <h1>Utvikler Boy<span class="primColor">();</span></h1>
    <p>python slayer, database crusher, server rampager & tea drinker</p>
  </section>
  
  <style>
    #home {
      height: 80vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 0 1rem;
      position: relative;
      overflow: hidden;
    }
  
    #home .background-image {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: url('/background.jpg') no-repeat center center;
      background-size: cover;
      opacity: 0.1;
      z-index: -1;
      filter: grayscale(1);
    }
  
    h1 {
      z-index: 1;
      font-size: 2.5rem;
      color: #fff;
      margin: 0;
    }
  
    p {
      z-index: 1;
      font-size: 1.0rem;
      color: #71b7d5;
    }
  
    .primColor {
      z-index: 1;
      color: #71b7d5;
      font-size: 2.6rem;
    }
  
   
    @media (max-width: 768px) {
      #home {
        height: 60vh; 
      }
  
      #home h1 {
        font-size: 2rem; 
      }
  
      #home p {
        font-size: 0.9rem;
      }
    }
  

    @media (max-width: 480px) {
      #home {
        margin: 0; 
        height: 50vh;
        padding: 0;
      }
  
      #home h1, #home .primColor {
        font-size: 1.5rem; 
      }
  
      #home p {
        font-size: 0.8rem;
      }
    }
  </style>