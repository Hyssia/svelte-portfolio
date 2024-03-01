<section id="projects">
    <h2>Projects</h2>


    <!-- ender href tell link tell github repo -->
    <div class="project-cards">
      <div class="card">
        <img src="/placeholder.png" alt="" />
        <p>Project 1</p>
        <a href="#home"><p class="gURL">Github URL</p></a>
      </div>
      <div class="card">
        <img src="/placeholder.png" alt="" />
        <p>Project 2</p>
        <a href="#home"><p class="gURL">Github URL</p></a>
      </div>
      <div class="card">
        <img src="/placeholder.png" alt="" />
        <p>Project 3</p>
        <a href="#home"><p class="gURL">Github URL</p></a>
      </div>
      <div class="card">
        <img src="/placeholder.png" alt="" />
        <p>Project 4</p>
        <a href="#home"><p class="gURL">Github URL</p></a>
      </div>
      <div class="card">
        <img src="/placeholder.png" alt="" />
        <p>Project 5</p>
        <a href="#home"><p class="gURL">Github URL</p></a>
      </div>
      <div class="card">
        <img src="/placeholder.png" alt="" />
        <p>Project 6</p>
        <a href="#home"><p class="gURL">Github URL</p></a>
      </div>
    </div>
  </section>
  
  <style>
    #projects {
      padding: 4rem 1rem;
      text-align: center;
      margin: 0 10rem;
      color: #fff;
      margin: 0 10rem 0 10rem;
    }
  
    h2 {
      font-size: 2.2rem;

      font-family: "Josefin Sans", sans-serif;
      text-transform: uppercase;
    }
  
    .gURL {
      color: #096b90;
    }
  
    .project-cards {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1rem;
    }
  
    .card {
      flex: 0 0 calc(33.333% - 1rem);
      border: 1px solid #ccc;
      padding: 1rem;
      box-sizing: border-box;
      overflow: hidden;
      transition: transform 0.3s ease-in-out; 
      cursor: pointer;
    }
  
    .card:hover {
      transform: scale(1.1);
      z-index: 2;
    }
  
    .card img {
      width: 100%;
      height: auto;
      object-fit: cover;
    }
  
    @media (max-width: 768px) {
      #projects {
        margin: 0 5rem; 
      }
  
      .card {
        flex: 0 0 calc(50% - 1rem); 
      }
    }
  
    @media (max-width: 480px) {
      #projects {
        margin: 0 2rem; 
      }
  
      .card {
        flex: 0 0 100%;
      }
    }
  </style>