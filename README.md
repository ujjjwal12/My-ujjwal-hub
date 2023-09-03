<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Web Developer Portfolio</title>
  <style>
    /* Add some basic styling */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    .container {
      display: flex;
      justify-content: space-between;
      background-color: #ffffff;
      /* Warning background color */
      padding: 20px;
    }

    .left-column {
      flex: 1;
      /* Adjust this value to control the width of the left column */
      padding: 20px;
      background-color: rgb(52, 128, 141);
      color: white;
      /* Add a yellow background color here */

    }

    .right-column {
      flex: 3;
      /* Adjust this value to control the width of the right column */
      padding: 20px;
      background-color: white;


    }

    .portfolio {

      padding: 20px;
      border-radius: 5px;
    }

    /* Add some styles for your skills section */
    .skills {
      font-weight: bold;
    }

    /* Add styles for the GitHub profile photo frame */
    .github-frame {
      border: 7px solid #ffffff;
      border-radius: 50%;
      overflow: hidden;
      width: 150px;
      height: 150px;
      margin: 20px auto;
    }

    .line {
      border-top: 8px solid rgb(52, 128, 141);;
      /* Change the color to yellow */
      margin-top: 20px;
      /* Adjust the margin to control the spacing between lines */
    }
    .circle-frame {
            width: 150px; /* Adjust the size of the circular frame */
            height: 150px; /* Should be equal to width to create a perfect circle */
            border-radius: 50%; /* Creates a circular shape */
            overflow: hidden; /* Clips the image to the circle */
            margin: 20px auto; /* Centers the circle */
        }

        .circle-frame img {
            max-width: 100%;
            height: auto;
            display: block;
        }
        .line{
            height: 10px;
            background-color:   rgb(52, 128, 141);;
        }
        .txt{
            text-align: justify;
        }
        .line1{
            background-color: gray;
            height: 20px;
            width: 250px;
            
        }
        .line2{
            background-color: rgb(220, 207, 207);
            height: 20px;
            width: 100px;
            
        }
        .fle{
            display: flex;
        }
  </style>
</head>

<body>
  <div class="container">
    <div class="left-column">
      <div class="circle-frame">
        <img src="uspa.png" alt="Your Photo">
    </div>
      <h3 class="mt-5 fw-bold "> E D U C A T I O N</h3>
      <h5>Bachelor's in B tech</h5>
      <p>April 2018 - April-2022</p>
      <p> <b>Punjab</b> technical university kapurthala</p>
      <p> <b>Under</b> the college of anand college of engineering & management</p><br>
      <h3 class="mt-5 fw-bold "> R E F R E N C E</h3>
      <h5>Mr.Archer Jordan</h5>
      <p>cheif ceo</p>
      <p> <b>Email-</b> ujjwalsha167@gmail.com</p>
      <p> <b>contact</b> 9874660475</p>
      <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Odit officiis cumque, perferendis fugiat debitis iure. Consequuntur quis consectetur accusamus aspernatur, sed ipsa expedita nobis amet, qui ipsam optio culpa at?</p>
      <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Iste, reiciendis ipsa dolor officia nobis accusantium, quidem totam nemo ullam nisi sunt, sapiente dignissimos voluptate quia laborum at distinctio dolorum? Placeat.</p>
      <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Beatae voluptatibus eum eius, enim ipsam cum. Numquam, sapiente illo veniam officiis sequi laboriosam beatae facilis iusto soluta natus, rerum ea quas?</p>
      <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Et voluptatem deserunt at praesentium mollitia aperiam, porro tenetur temporibus sapiente corporis? Id a nobis, expedita quisquam amet ea dolor dolorum explicabo.</p>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus, corrupti molestias blanditiis eveniet tempore quas iste molestiae optio aliquam. Itaque quasi consectetur earum autem adipisci iste excepturi quaerat qui provident?</p>
    </div>

    <div class="right-column">
      <h1>Ujjwal shaw</h1>
      <P>Web Developer</P>
      

      <div class="line">

     <div class="section">
        <h2>About Me</h2>
        <p>Hi, I'm Ujjwal shaw a passionate web developer with a strong commitment to creating exceptional digital
          experiences. With 5 years of hands-on experience in web development, I'm dedicated to delivering innovative
          and functional websites that not only meet but exceed client expectations.</p>
        <p>My journey in web development began with a fascination for crafting beautiful, user-friendly interfaces. Over
          the years, I've honed my skills in front-end and back-end technologies, mastering languages such as HTML, CSS,
          JavaScript, and [additional languages/frameworks].</p>
        <p>My approach to web development combines creativity with technical proficiency. I believe that a great website
          should not only look stunning but also perform flawlessly. Whether it's creating responsive designs,
          optimizing website performance, or implementing interactive features, I'm committed to delivering excellence
          in every project.</p>
        <p>Continuous learning is at the core of my professional ethos. The ever-evolving world of web development keeps
          me on my toes, and I'm always eager to explore new tools and technologies to stay ahead of industry trends.
          Collaboration and problem-solving are skills I hold dear, allowing me to work seamlessly with cross-functional
          teams and tackle complex challenges head-on.</p>

      </div>

      <div class="line">
        <h2>Work Experience</h2>
        <div class="experience-item">

          <ul>
            <li>Designed and implemented responsive and user-friendly web interfaces using HTML, CSS, and JavaScript.
            </li>
            <li>Collaborated with the design team to ensure pixel-perfect implementation of UI/UX designs.</li>
            <li>Optimized website performance for faster loading and better user experience.</li>
            <li>Integrated third-party APIs and libraries to enhance website functionality.</li>
          </ul>

        </div>
        <div class="line">

        </div>

        <div class="experience-item">
          <h3>Freelance Web Developer</h3>
          <p>January 2018 - May 2020</p>
          <ul>
            <li>Worked with various clients to create custom websites tailored to their specific needs.</li>
            <li>Developed and maintained responsive and cross-browser compatible websites.</li>
            <li>Provided ongoing support and updates to ensure the longevity of web projects.</li>
          </ul>
        </div>
       

           <div class="m-4">
          <h4 class="fw-bold mt-4">W O R K  <span class="ms-3">E X P E R I E N C E</span></h4>
          <p class="">F R E S H E R</p>
           </div>

           <div class="line ms-4"></div>


           <div class="m-4">
            <h4 class="fw-bold mt-5">S K I L L S<h4>
            <div class="row mt-5">
                <div class="col-6 fs-5">
                    <p>HTML</p>
                    <div class="fle">
                        <div class="line1">  </div>
                        <div class="line2">  </div>
                    </div>
                    
                </div>
                <div class="col-6 fs-5">
                    <p>CSS</p>
                    <div class="fle">
                        <div class="line1">  </div>
                        <div class="line2">  </div>
                    </div>
                </div>
                <div class="col-6 fs-5 mt-4"><p>BOOTSTRAP</p>
                    <div class="fle">
                        <div class="line1">  </div>
                        <div class="line2">  </div>
                    </div>
                </div>
                <div class="col-6 fs-5 mt-4"><p>JAVASCRIPT
                    <div class="fle">
                        <div class="line1">  </div>
                        <div class="line2">  </div>
                    </div>

                </p></div>
            </div>
             </div>
        
        </div>
    </div>
   </div>


    <script src="bootstrap.bundle.min.js"></script>
  </div>
</body>

</html>
