<svg xmlns="http://www.w3.org/2000/svg" width="100%" height="300" viewBox="0 0 800 300">
  <style>
    @keyframes gradient {
      0% { fill: #4F46E5; }
      50% { fill: #EC4899; }
      100% { fill: #4F46E5; }
    }
    .name-text {
      font-family: 'Segoe UI', system-ui;
      font-weight: 700;
      animation: gradient 5s ease-in-out infinite;
    }
    .tech-icon {
      transition: transform 0.3s ease;
    }
    .tech-icon:hover {
      transform: translateY(-5px);
    }
  </style>
  
  <!-- Nome Principal -->
  <text x="50%" y="40%" text-anchor="middle" font-size="48" class="name-text">
    Gabriel Silva
  </text>

  <!-- Ícones de Tecnologias -->
  <g transform="translate(100, 150)">
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML" >
      <image class="tech-icon" x="0" y="0" width="40" height="40" href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg"/>
    </a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/CSS" >
      <image class="tech-icon" x="60" y="0" width="40" height="40" href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg"/>
    </a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" >
      <image class="tech-icon" x="120" y="0" width="40" height="40" href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg"/>
    </a>
    <a href="https://www.php.net/docs.php" >
      <image class="tech-icon" x="180" y="0" width= "40" height= "40" href= "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg"/>
    </a>
    <a href= "https://isocpp.org/" target= "_blank">
      <image class= "tech-icon" x= "240" y= "0" width= "40" height= "40" href= "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg"/>
    </a>
    <a href= "https://getbootstrap.com/docs/" target= "_blank">
      <image class= "tech-icon" x= "300" y= "0" width= "40" height= "40" href= "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg"/>
    </a>
    <a href= "https://dev.mysql.com/doc/" target= "_blank">
      <image class= "tech-icon" x= "360" y= "0" width= "40" height= "40"
href= "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg"/>
</a>
<a href= "https://wordpress.org/documentation/" >
<image class= "tech-icon"
x =  420 
y =  0 
width =  40 
height =  40 
href =   https://cdn.jsdelivr.net/gh/devicons/devicon/icons/wordpress/wordpress-plain.svg />
</a>
</g>
</svg>
