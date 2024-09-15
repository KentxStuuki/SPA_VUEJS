<!--
  Name: Mark Erolle D. Quiambao
  Section: WD - 303
-->

<!--
  Im not sure why sir but my output in stackblitz does not match the output i created when i does the live server 
-->

<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
     <div id="app">
        <!-- Container of both left and right -->
        <div class="container">
            <!-- Profile cotnainer or the left container-->
            <!-- Profile picture -->
            <div class="left-container">
                <img src="https://scontent.fcrk1-5.fna.fbcdn.net/v/t1.15752-9/459385970_1247035506732029_3558658731421739884_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=9f807c&_nc_eui2=AeGg_v3qcZDQyMqz7SzYYN22mE-4OalazUiYT7g5qVrNSGDhnptT8uQ-RurkpWJyxV2e5xUHBY2cBrPNMyaFnSvM&_nc_ohc=gy04839LHUMQ7kNvgEjAXnJ&_nc_ht=scontent.fcrk1-5.fna&_nc_gid=Anr6Ku4Pyg6nGZPdJHbwNHP&oh=03_Q7cD1QHOzQiDQvtEi7NiCp6_WwzSkhsDTcR2ze1HaKvZYtqbQg&oe=670E24F8" alt="profile Picture">
                <!-- My name and my Course -->
                <div class="name">
                    <h2>Mark Erolle D. Quiambao</h2>
                    <h2>Webdev</h2>
                </div>
                <hr>
                
                <!-- My Contacts -->
                <div class="contact">
                    <h2>CONTACT INFO</h2>
                    <h3>Phone: 09063815462</h3>
                    <h3>Email: markerolle@gmail.com</h3>
                    <h3>GitHub: github.com/KentxStuuki</h3>
                </div>

                <!-- Education -->
                <div class="education">
                    <h2>EDUCATION</h2>
                    <h3>B.S in Information Technology with area specialization in Web Development</h3>
                    <h3>RELEVANT COURSE WORK:</h3>
                    <ul class="educ-ul">
                        <li><h4> Dynamic Web Application and Development Tools</h4></li>
                        <li><h4>Data Structure and Algorithms</h4></li>
                        <li><h4>Object-Oriented Programming</h4></li>
                        <li><h4>Information Assurance and Security</h4></li>
                        <li> <h4>Advance Database</h4></li>
                        <li><h4>Web and Advertising Publishing Concepts</h4></li>
                        <li><h4>Web Server and Client Services</h4></li>
                        <li><h4>Holy Angel University Student</h4></li>
                    </ul>
                </div>            
            </div>

            <!-- Right Container or my personal information--->
            <div class="right-container">
                <div class="inside-right">

                    <!-- Professional summary -->
                    <div class="prof-sum">

                        <h2>PROFESSION SUMMARY</h2>
                        <h5>I am a front-end web developer skilled in HTML, CSS, and JavaScript, focused on creating interactive, responsive, and user-friendly websites. I specialize in turning designs into functional applications, ensuring cross-device compatibility and optimizing performance.</h5>

                        <ul>
                            <li><h5>HTML: Crafting clean, well-structured semantic markup for accessible, and unique structures.</h5></li>
                            <li><h5>CSS: Styling websites with modern design techniques, including Flexbox, Grid, and implementing animations for enhanced interactivity.</h5></li>
                            <li><h5>JavaScript: Building dynamic web applications with vanilla JS and frameworks like React or Vue to improve front-end functionality and client-side scripting.</h5></li>
                        </ul>

                        <h5>With an eye for detail and a drive to stay updated on the latest industry trends, I continuously improve my coding practices to deliver cutting-edge web solutions. I collaborate effectively within teams, leveraging version control tools and agile methodologies to ensure timely project delivery. My goal is to contribute my technical expertise to projects that push the boundaries of web development.</h5>

                        <!-- Techincal Skills-->
                        <div class="technical">
                            <h2>TECHNICAL SKILLS</h2>
                            <h3>Languages:</h3>
                            <ul>
                                <li><h4>HTML</h4></li>
                                <li><h4>CSS</h4></li>
                                <li><h4>TAILWINDCSS</h4></li>
                                <li><h4>JAVASCRIPT</h4></li>
                                <li><h4>JAVA</h4></li>
                                <li><h4>PHP</h4></li>
                            </ul>   
                            <h3>Database:</h3>
                            <ul>
                                <li><h4>MYSQL</h4></li>
                                <li><h4>MONGODB</h4></li>
                                <li><h4>FIGMA</h4></li>

                            </ul>
                            <h3>Frameworks and Libraries:</h3>
                            <ul>
                                <li><h4>NODEJS</h4></li>
                                <li><h4>EXPRESSJS</h4></li>
                            </ul>
                            <h3>Tools and Platforms:</h3>
                            <ul>
                                <li><h4>Git</h4></li>
                                <li><h4>GitHub</h4></li>
                                <li><h4>Visual Studio Code</h4></li>
                                <li><h4>NPM</h4></li>
                            </ul>
                        </div>
                    </div>

                        <!-- Projects -->
                        <div class="projects">
                            <h2>PROJECTS</h2>

                            <div class="project-box">
                                <h3>Library Management System</h3>
                                <h4>Created a system to manage library operations, including book checkouts, returns, and user management. Implemented a user-friendly interface and robust backend using modern web technologies.</h4>
                            </div>
                            <div class="project-box">
                                <h3>CafeWhiskers</h3>
                                <h4> Created as an project that is dedicated to the delicious coffee and the kind, friendly, and peatable cat that heals your heart with there cuteness as they accompany you inside the cafe. This is also created to help cats to find there true parents and home.</h4>
                            </div>

                            <div class="project-box">
                                <h3>Art Capsul</h3>
                                <h4> This Website was created to help the unpopular digital artisit to post and advertise there master piece so that they can gain more customer, followers, and possible bright future as they use the webpage to endores there works.</h4>
                            </div>

                            <div class="project-box">
                                <h3>Raiden Shogun</h3>
                                <h4> This webpage was deidicated to be made in the inspiration of the characyer raiden shogun in Genshin impact as it displays her kits such as material needs, talents, constelations, and her background story in the game.</h4>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
*{
    margin: 0;
    padding: 0;

}

/* Container */
.container{
    display: flex;
}

/* Left Container*/
.left-container{
    background-color: #421ca9;
    height: 100%;
    width: 25%;
}

.left-container img{
    display: block;
    padding-top: 70px;
    margin: 0 auto;
    width: 220px;
    height: 200px;
    border-radius: 50%;
    padding: 40px;
}

/* Name */
.name{
    text-align: center;
    color: aliceblue;
}

hr{
    width: 90%;
    margin: 20px auto;
}

/* Contact */
.contact h2{
    text-align: center;
    color: aliceblue;
}

.contact h3, a{
    color: aliceblue;
    padding-left: 20px;
    text-decoration: none;
}

/* Education */
.education{
    margin-top: 45px;
}

.education h2, h3, h4, .educ-ul li{
    color: aliceblue;
    padding: 10px;
}

/* Right Container*/
.right-container{
    width: 75%;
    background-color: #f2f2f2;
}

.inside-right{
    display: flex;
}

.prof-sum{
    width: 50%;
}

.prof-sum h2{
    color: #421ca9;
    padding: 20px;
}

.prof-sum h5{
    color: #421ca9;
    padding: 20px;
    font-size: 17px;
}

/* Technical Skills */
.technical h2{
    text-align: center;
}

.technical h3, li{
    color: #421ca9;
    padding-left: 15px;
}

/* Projects */
.projects{
    width: 50%;
}

.projects h2 {
    text-align: center;
    color: #421ca9;
    padding: 20px;
}

.project-box {
    border: 1px solid #000;
    border-radius: 8px;
    padding: 20px;
    margin-bottom: 30px;
    background-color: #d8d8d8;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    width: 90%;
}  

.projects h3 {
    color: #421ca9;
    font-size: 20px;
}

.project-box h4 {
    color: #421ca9;
    font-size: 16px;
}
</style>
