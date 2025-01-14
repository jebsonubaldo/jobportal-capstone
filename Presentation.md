---
marp: true
# theme: uncover
# class: invert
---

<style>
    @import url('https://fonts.googleapis.com/css2?family=DM+Sans:opsz,wght@9..40,100;9..40,200;9..40,300;9..40,400;9..40,500;9..40,600;9..40,700;9..40,800;9..40,900;9..40,1000&display=swap');

    * {
        font-family: "DM Sans", sans-serif;
    }

    h1 {
        font-size: 64px;
        font-weight: 900;
        color: #16a34a;
    }

    h2 {
        color: #16a34a;
        font-weight: 700;
    }

    .planning {
        display: grid;
        grid-template-columns: repeat(2, minmax(0, 1fr));
        gap: 0.5rem;
    }

    .deployment {
        display: grid;
        grid-template-columns: repeat(3, minmax(0, 1fr));
        gap: 0.5rem;
    }
</style>

<!-- ![bg right](https://picsum.photos/720?image=1)
![bg](https://picsum.photos/720?image=20) -->

<h1>JOBI: JOB PORTAL PROJECT</h1>

<h2>Developers:</h2>

<a href="https://github.com/SDarius14"><img src="https://img.shields.io/badge/dariushernandez-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white"></a> - Project Manager </br> <a href="https://github.com/emailjohnthomascaballero"><img src="https://img.shields.io/badge/johncaballero-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white"></a> - QA Test Engineer </br> <a href="https://github.com/jebsonubaldo"><img src="https://img.shields.io/badge/jebsonubaldo-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white"></a> - DevOps Engineer

--- 

<h2>About the Project</h2>

Jobi is a cutting-edge job portal website that aims to redefine the way you search for your dream career. In a rapidly evolving job market, finding the perfect job opportunity can be daunting and time-consuming. Jobi is here to simplify this process, providing a seamless and intuitive platform that connects talented job seekers with a diverse range of employers.


---

<h2>Planning</h2>

<div class="planning">
<div>

* Screenshot of reference design

    <img src="./public/assets/presentation/inspiration_design.png" class="steps">

</div>
<div>

* Separation of pages per member

    <img src="./public/assets/presentation/notion.png" class="steps">

</div>
</div>

---

<h2>Planning</h2>

<div class="planning">
<div>

* Familiarization of <img src="https://img.shields.io/badge/git%20-%23F05032.svg?&style=for-the-badge&logo=git&logoColor=white"/> commands

    <img src="./public/assets/presentation/git.png" class="steps">

</div>
<div>

* Familiarization of <img src="https://img.shields.io/badge/EJS%20-%23E74C3C.svg?&style=for-the-badge&logo=EJS&logoColor=white"> boilerplate

    <img src="./public/assets/presentation/workaround.png" class="steps">

</div>
</div>

---
<h2>Planning</h2>

* Identification of common components such navbar, footer, color scheme <a href=""><img src="https://img.shields.io/badge/Primary%20Color-%2314532d-14532d"></a> <a href=""><img src="https://img.shields.io/badge/Secondary%20Color-%2316a34a-16a34a"></a> <a href=""><img src="https://img.shields.io/badge/Accent%20Color-%23d2f34c-d2f34c"></a>

* Tools and languages
    - Planning <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white"> <img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white"> <img src="https://img.shields.io/badge/git%20-%23F05032.svg?&style=for-the-badge&logo=git&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/> <img src="https://img.shields.io/badge/Excalidraw%20-%23FFDC00.svg?&style=for-the-badge&logo=Excalidraw&logoColor=black"/>
    - Design <img src="https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white"> <img src="https://img.shields.io/badge/Envato%20Elements-00AEF0?style=for-the-badge&logo=envato&logoColor=white)](https://elements.envato.com/"> <img src="https://img.shields.io/badge/Google%20Fonts%20-%234285F4.svg?&style=for-the-badge&logo=Google%20Fonts&logoColor=white"> <img src="https://img.shields.io/badge/Unsplash%20-%2316a34a.svg?&style=for-the-badge&logo=Unsplash&logoColor=white">
    - Development <img src="https://img.shields.io/badge/Visual%20Studio-5C2D91?style=for-the-badge&logo=visual-studio"> <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white"> <img src="https://img.shields.io/badge/javascript%20-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"> <img src="https://img.shields.io/badge/Embedded_Javascript%20-%23E74C3C.svg?&style=for-the-badge&logo=EJS&logoColor=white">
    - Libraries <img src="https://img.shields.io/badge/tailwind%20css%20-%2338B2AC.svg?&style=for-the-badge&logo=tailwind-css&logoColor=white"> <img src="https://img.shields.io/badge/node.js%20-%23008CC1.svg?&style=for-the-badge&logo=node.js&logoColor=white"> <img src="https://img.shields.io/badge/Express.js-47A248?style=for-the-badge&logo=express&logoColor=white"> <img src="https://img.shields.io/badge/Particle.js%20-%23007BFF.svg?&style=for-the-badge&logo=particle.js&logoColor=white"> <img src="https://img.shields.io/badge/Chart.js%20-%23FF6384.svg?&style=for-the-badge&logo=chart.js&logoColor=white"> <img src="https://img.shields.io/badge/Swiper.js%20-%23FF4500.svg?&style=for-the-badge&logo=Swiper.js&logoColor=white"> <img src="https://img.shields.io/badge/Alpine.js%20-%238BC34A.svg?&style=for-the-badge&logo=Alpine.js&logoColor=white"> <img src="https://img.shields.io/badge/ScrollReveal%20-%230A0A0A.svg?&style=for-the-badge&logo=ScrollReveal&logoColor=white"> 
    - Deployment <img src="https://img.shields.io/badge/Heroku%20-%23430098.svg?&style=for-the-badge&logo=heroku&logoColor=white"> 
    - Presentation <img src="https://img.shields.io/badge/Marp%20-%23007ACC.svg?&style=for-the-badge&logo=Marp&logoColor=white"> 
---

<h2>Development</h2>

<div class="planning">
<div>

* Initialize <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/> repository

    <img src="./public/assets/presentation/github.png" class="steps">

</div>
<div>

* Creating <img src="https://img.shields.io/badge/Embedded_Javascript%20-%23E74C3C.svg?&style=for-the-badge&logo=EJS&logoColor=white"> boilerplate
    
    <img src="./public/assets/presentation/workaround.png" class="steps">

</div>
</div>

---
<h2>Challenges Encountered</h2>

<div class="planning">
<div>

* Complex merges with team members simultaneous work can cause conflicts, code inconsistencies, and errors.

    <img src="./public/assets/presentation/challenge_1.jfif" class="steps">

</div>
<div>

* Implementing forEach loops in EJS templates for dynamic content that can lead to unexpected behavior and error.

    <img src="./public/assets/presentation/challenge_2.png" class="steps">

</div>
</div>

---

<h2>Development</h2>

<div class="planning">
<div>

* Setup <img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white">  daily meetings for deliverables

    <img src="./public/assets/presentation/discord_1.png" class="steps">

</div>
<div>

* Mentoring & discussing challenges via <img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white"> chat
    
    <img src="./public/assets/presentation/discord_2.png" class="steps">

</div>
</div>

---

<h2>Development</h2>

<div class="planning">
<div>

* Workaround
    * Setting up route
    * Analyzation of page structure
    * Identification of components
    * Identification of partials
    * Building the whole page

</div>
<div>

<img src="./public/assets/presentation/workaround.png" class="steps">

</div>
</div>
  
---
## Deployment

<!-- ###### Using <img src="https://img.shields.io/badge/Heroku%20-%23430098.svg?&style=for-the-badge&logo=heroku&logoColor=white">  for deployment -->

<div class="deployment">
<div>

* Step 1: Setting Port Number

    <img src="./public/assets/presentation/step_1.png" class="steps">

</div>
<div>

* Step 2: Change package.json

    <img src="./public/assets/presentation/step_2.png" class="steps">

</div>
<div>

* Step 3: Create Your Procfile

    <img src="./public/assets/presentation/step_3.png" class="steps">

</div>
</div>

* Github Link: https://github.com/SDarius14/jobportal-capstone
* Project Link: https://jobi-6e0b4dda90ab.herokuapp.com/

---

# Thank you for listening.
