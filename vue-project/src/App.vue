<script setup>
//import { RouterLink, RouterView } from 'vue-router'
import PinkButton from './components/PinkButton.vue'
</script>

<template>
  
    <header>        
        <nav>
            <img src="./assets/Images/logo.svg" alt="Logotipo Sync">

            <ul class="dropdown" id="dropdown">
                <li class="nav_option"><a href="#tab_description">DESCRIPTION</a></li>
                <li class="nav_option"><a href="#tab_features">FEATURES</a></li>
                <li class="nav_option"><a href="#tab_user_testimonials">SCREENS</a></li>
                <li class="nav_option"><a href="#tab_extras">EXTRA <img src="./assets/Images/down-arrow.png" id="menu_arrow"></a>
                    <ul class="dropdown_menu">
                        <li class="nav_subm_option"><a href="#">ARTICLE DETAILS</a></li>
                        <hr>
                        <li class="nav_subm_option"><a href="#">TERMS CONDITIONS</a></li>
                        <hr>
                        <li class="nav_subm_option"><a href="#">PRIVACY POLICY</a></li>
                    </ul>
                </li>
                <li class="nav_option"><a href="https://factoriaf5.org/" target="_blank">DOWNLOAD</a></li>
            </ul>

        </nav>
    </header>

    <main>       

        <section>
            <h1>Mobile App Landing Page</h1>
            <p>Start focusing on your goals and get more things done with Sync mobile application. It's the first app to harness the power of social connections to help you stay focused and get organized
            </p>
            <div class="button_ribbon_download_app">
              <PinkButton></PinkButton>
                <!--<a href="#"><img src="./assets/Images/apple.png" alt="logo Apple">DOWNLOAD</a>-->
                <a href="#"><img src="./assets/Images/playstore.png" alt="logo Google Play">DOWNLOAD</a>
            </div>
            
            <img src="./assets/Images/header-iphone.png" alt="Imagen de movil con la pantalla de la app" class="main_section_image">
            
        </section>
        <section class="circles_area">
            <a href="" class="each_topic_circle">
                <img src="./assets/Images/grupo_circulo.png" alt="Identify Goals">
                Identify Goals
            </a>
            <a href="" class="each_topic_circle">
                <img src="./assets/Images/etiqueta_circulos.png" alt="Situational Analysis">
                Situational Analysis
            </a>
            <a href="" class="each_topic_circle">
                <img src="./assets/Images/engranaje_circulo.png" alt="Task Settings">
                Task Settings
            </a>
            <a href="" class="each_topic_circle">
                <img src="./assets/Images/burbuja-de-dialogo.png" alt="Social Interaction">
                Social Interaction
            </a>
            <a href="" class="each_topic_circle">
                <img src="./assets/Images/rocket-solid.svg" alt="Get Things Done">
                Get Things Done
            </a>
        </section>
        
        <section id="tab_description">            
            <img src="./assets/Images/description-1-app.png" alt="Imagenes de la app">
            <article>
                <h2>Organize Your Time And Start Getting Resoults</h2>

                <p class="tab_description_inner_text">
                    Sync is the first mobile app on the market to harness the power of social connections to help you stop procastinating and start getting thing done. Give it try and see the changes right away.
                </p>
                    
                <ul class="tab_description_inner_text">
                    <li>Analyse and evaluate your current status and productivity</li>
                    <br>
                    <li>Begin monitoring your day routine with Sync app</li>
                    <br>
                    <li>See the improved resoults in no more than a couple of weeks</li>
                </ul>

                <a href="#" class="lonely_button_link">LIGHTBOX</a>

            </article>
        </section>        

        <section id="tab_features">
            <article>
                <div>
                    <a href="#"><img src="./assets/Images/reloj_2.png" alt="Reloj">Schedule</a>
                    <a href="#"><img src="./assets/Images/menu_hamb_2.png" alt="Tracking">Tracking</a>
                    <a href="#"><img src="./assets/Images/calendario_2.png" alt="Calendario">Organize</a>                    
                </div>
                <p>
                    Schedule tasks to keep track of their completion. Sync provides multiple scheduling options including alarms and reminders.
                </p>
                <ul>
                    <li>You can always add new tasks or change the settings of existing ones in your calendar view or the app control panel
                    </li>
                    <br>
                    <li>It's easy to stay focused on your most important daily activities that will get you closer to meeting your goals
                    </li>
                    <br>
                    <li>Use phone reminders to free up your long term memory which will reduce stress and make you more productive
                    </li>
                </ul>

            </article>
            <img src="./assets/Images/description-2-app.png" alt="Capturas de pantalla de la agenda">
        </section>

        

        <section id="tab_user_testimonials">
            <h2>User Testimonials</h2>
            <article>
                <div class="tab_users_ratings">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                </div>
                <hr>
                <p>
                    love using Sync for my personal development needs. It meets all my requirements and it actually helps a lot with focusing skills.
                </p>  
                <p>
                    Rick Jones - Designer
                </p>              
            </article>
            <article>
                <div class="tab_users_ratings">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                </div>
                <hr>
                <p>
                    After trying out a large number of
                    Never dreamed I could learn so fast how
                    personal coaching apps I decided to give to focus on my personal goals and Sync a try and what a wonderful surprise improve my life to levels I never thought
                    it was.
                    possible.
                </p>    
                <p>
                    Lynda Marquez - Developer
                </p>               
            </article>
            <article>
                <div class="tab_users_ratings">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                </div>
                <hr>
                <p>
                   Never dreamed I could learn so fast how to focus on my personal goals and improve my life to leveles I never thought possible.
                </p>    
                <p>
                    Jay Frisco - Marketer
                </p>               
            </article>

            <div class="tab_users_partners">
                <img src="./assets/Images/customer-logo-1.png" alt="Primester">
                <img src="./assets/Images/customer-logo-2.png" alt="GreenApp">
                <img src="./assets/Images/customer-logo-3.png" alt="Voltmeter">
                <img src="./assets/Images/customer-logo-4.png" alt="Keyrunner">
                <img src="./assets/Images/customer-logo-5.png" alt="Amplifier">
            </div>

            <article>
                <div class="tab_users_ratings">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                </div>
                <hr>
                <p>
                    I got so much value from using Sync in my daily life for which I am very grateful and would recommend it to everybody
                </p>    
                <p>
                    Frank Gibson - Manager
                </p>               
            </article>

            <article>
                <div class="tab_users_ratings">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                </div>
                <hr>
                <p>
                    If you have great goals but can't figure out a way to keep focused then you should definitely give Sync a try and see the results
                </p>    
                <p>
                    Rita Longmile - Designer
                </p>               
            </article>
            <article>
                <div class="tab_users_ratings">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                    <img src="./assets/Images/estrella.png" alt="Estrella">
                </div>
                <hr>
                <p>
                    I've been looking for a great organizer app for such a long time but now I am really happy that I found Sync. It's been working great
                </p>    
                <p>
                    Jones Smith - Developer
                </p>               
            </article>
        </section>

        <section id="tab_users_ratings_wrapup" class="circles_area">
            <a href="#" class="each_topic_circle"><img src="./assets/Images/grupo_circulo.png" alt="Happy Users"><span>231</span>Happy Users</a>
            <a href="#" class="each_topic_circle"><img src="./assets/Images/etiqueta_circulos.png" alt="Happy Users"><span>385</span>Issues Solved</a>
            <a href="#" class="each_topic_circle"><img src="./assets/Images/engranaje_circulo.png" alt="Happy Users"><span>159</span>Good Reviews</a>
            <a href="#" class="each_topic_circle"><img src="./assets/Images/burbuja-de-dialogo.png" alt="Happy Users"><span>127</span>Case Studies</a>
            <a href="#" class="each_topic_circle"><img src="./assets/Images/rocket-solid.svg" alt="Happy Users"><span>211</span>Orders Recieved</a>
        </section>

        <section>

            <img src="./assets/Images/download-iphone.png" alt="Imagen de movil con la pantalla de la app" class="main_section_image">

            <p>Do you feel like you're wasting time with small stuff instead of working towards your goals? Start using Sync to organize your time and get a grip on your personal development
            </p>
            <div class="button_ribbon_download_app">
                <a href="#"><img src="./assets/Images/apple.png" alt="logo Apple">DOWNLOAD</a>
                <a href="#"><img src="./assets/Images/playstore.png" alt="logo Google Play">DOWNLOAD</a>
            </div>           
        </section>   
        <img src="./assets/Images/decorative-green-diamond.svg" alt="diamante verde decorativo" id="dec_green_diamond">
    <img src="./assets/Images/decorative-blue-circle.svg" alt="circunferencia azul decorativa" id="dec_blue_circle">
    <img src="./assets/Images/decorative-white-circle.svg" alt="circulo blanco grande decorativo" id="dec_white_circle">
    <img src="./assets/Images/decorative-white-circle.svg" alt="circulo blanco grande decorativo" id="dec_white_circle_2">
    <img src="./assets/Images/decorative-yellow-circle.svg" alt="circulo amarillo decorativo" id="dec_yellow_circle">

        
    </main>

    <footer>
        <section id="tab_extras">
            <article>
                <h6>Contact Info</h6>
                <ul>                        
                    <li>
                        <img src="./assets/Images/location-dot-solid.svg" alt="Ubicacion"> 22 Innovation Street, CA, US
                    </li>
                    <li>
                        <img src="./assets/Images/envelope-solid.svg" alt="Direccion de email"> office@syncmobile.com
                    </li>
                    <li>
                        <img src="./assets/Images/phone-solid.svg" alt="Telefono"> +44 375 945 23
                    </li>
                </ul>
            </article>
            <article>
                <h6>Value Links</h6>
                    <ul>
                        <li>
                            Terms & Conditions
                        </li>
                        <li>
                            Privacy Policy
                        </li>
                        <li>
                            Article Details
                        </li>
                    </ul>
            </article>
            <article>
                <h6>Other Apps</h6>
                    <ul>
                        <li>
                            Scientific Calculator
                        </li>
                        <li>
                            Advanced Timer
                        </li>
                        <li>
                            Music Store
                        </li>
                    </ul>
            </article>
            <article id="social_networks">
                <a href="#"><img src="./assets/Images/facebook.svg" alt="Facebook"></a>
                <a href="#"><img src="./assets/Images/twitter.svg" alt="Facebook"></a>
                <a href="#"><img src="./assets/Images/pinterest.svg" alt="Facebook"></a>
                <a href="#"><img src="./assets/Images/instagram.svg" alt="Facebook"></a>
            </article>            
           
        </section>
        <h6>Copyright © 2020 Inovatik - All rights reserved</h6>
    </footer>

  
</template>

<style lang="scss" scoped>

$background_color_2: #E5EDF5;
$background_color_3: #FF566E;
$bottom_hover_1: #8F5CE3;

#tab_features{ 
    width:100vw;
    background-color: $background_color_2;
    display: flex;
    flex-direction: row; 
    justify-content: center;
    flex-wrap: wrap;  

    >img{
        display:flex;
        padding: 0 2vw 0 0;
        width: 40vw;
        align-self:flex-start;
        margin-top: 5vh;
        margin-bottom: 10vh;
    }

    article{
        display:flex;
        flex-direction: column;
        padding: 3vh 0 0 3vw;  
        justify-content: left;
        align-self: start;

        margin: 2vh 0 0 3vw;
        font-size: 0.7rem;       

        div{
            display: flex;
            flex-wrap: wrap;
            flex-direction: row;
            justify-content :left;
            gap: 2vw;
            margin:3vh 0; 
            width: 40vw;           

            a:hover{
                background: $bottom_hover_1;
                color:#E5EDF5;               
            }
            
            a{
                display:flex;
                flex-direction: row;
                background: white;
                font-weight: bold;
                padding: 1vh 2vw;                

                img{
                    display: block;
                    height: 2vh;
                    object-fit: contain;
                    align-self: baseline;
                    padding:0 1vw 0 0;
                    margin-top:0;                    
                } 
            }
        }

        p{
            text-align: left;
            margin:0;
            width: 40vw;
            min-width: 250px;
        }

        ul{
            list-style-image: url(/Public/./assets/Images/list_bullet.png);
            width: 40vw;
            list-style-position: inside;      
            min-width: 250px;
        }
    }
}

#tab_user_testimonials{   
    display:grid;
    grid-template-columns: repeat(3,  1fr); 
    align-items: start;
    margin: 10vh auto;   

    h2{
        grid-column: span 3;
        text-align: center;
    }
    
    article{  
        display: flex;  
        flex-direction: column; 
        gap:2vh; 
        padding: 7vh 0 10vh 0; 
                     

        .tab_users_ratings{
            display: flex; 
            flex-direction: row;  
            justify-content: center;
            flex-wrap: wrap;      
    
            img{
                height: 3vh;
            }              
        }
        hr{                
            width: 50%; 
            margin: 0 auto;          
        }  

        p:last-child{
            font-weight: bold;            
        }
    }   

    .tab_users_partners{
        background-color: white;
        display:flex;
        flex-direction: row;
        gap: 2vh;
        column-gap: 3vw;
        flex-wrap: wrap;
        justify-content: center;
        grid-column: span 3;

        img{
            margin:0;            
        }
    }
}

:root{
    --color-base:#333333;
    --color-hover:#FF566E;
    --color-fondo: #F7FAFD;
}


#tab_users_ratings_wrapup{ 
    width: 100vw;
    background: #E5EDF5;
    display:flex;
    justify-content: space-evenly;
    align-items: center;
    padding: 10vh 0;
    z-index: 3;
    

    a{
        display:flex;
        flex-direction: column;
        align-items: center;
        height: auto;
        font-weight: normal;
        color: #333333;

        span{
            font-size: 2.5rem;
            font-weight: bold;
            line-break:anywhere;
        }

        img{
            background: none;
        }
    }    
}

footer{
    margin: 0 auto;
    width: 90vw;
    border-top: 1px solid #33333320;
    padding-top: 5vh;
    
    section{
        display:flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: start;
        flex-wrap: wrap;
        gap:2vw;
        
        ul{
            list-style-position: inside;
            font-size: 0.6rem;
            list-style-type: none;            

            li{
                display:flex;
                align-items: center;
                margin: 1vh 0;
                line-break: anywhere;               
                
                img{
                    height: 2vh;
                    width: 2vw;
                    object-fit: contain;
                    justify-self:center ;
                    margin-right: 1vw;
                }

            }  
        } 
        
        #social_networks{
            display:flex;
            flex-direction: row;
            justify-content: left;            
            flex-wrap: wrap;
            width:fit-content;

            a img{
                    
                margin-top: 0;
                height: 3vh;                
            } 
        }         
    }
    
    h6{
        width: 100%;
        text-align: center;
        margin-bottom: 5vh;
    }

}

*{  
    font-family: 'Open Sans', sans-serif;    
    padding: 0;    
    text-decoration: none;
    z-index:3;
    position:relative;
    margin: 0;
}

body{ overflow-x: hidden;
    background-color: #F7FAFD;
    margin: 0;
    width: 100%;
    
}

header{
    height: 10vh;
    display: flex;
    align-items: center;
    position: fixed;
    top: 0;
    width: 100%;
    margin: 0 auto;
    z-index:4;
    background-color: #F7FAFD;
    
}

nav{
    width: 100%;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: space-evenly;   
    align-items: center; 
    font-size: 0.6rem;
    font-weight: bold;
    color: var(--color-base);
    margin: 0 auto;
}

main{
    margin: 20vh 0;       
}

#dec_green_diamond{
    position: fixed;
    top: 20vh;
    height: 2vh;
    left: 5vw;
    z-index: 2;
    background-color: transparent;
}

#dec_blue_circle{
    position: fixed;
    top: 55vh;
    height: 5vh;
    left: 9vw;
    z-index: 2;
    background-color: transparent;
}

#dec_white_circle{
    position: fixed;
    top: 50vh;
    width: 30vw;
    left: -15vw;
    z-index: 1;
    background-color: transparent;
}

#dec_white_circle_2{
    position: fixed;
    top: 30vh;
    width: 30vw;
    right: -15vw;
    z-index: 1;
    background-color: transparent;
}

#dec_yellow_circle{
    position: fixed;
    top: 20vh;
    height: 2vh;
    right: 10vw;
    z-index: 2;
    background-color: transparent;
}

h1{
    text-align: center;
    font-size: 6vw;
}

p{
    width: 80%;
    text-align: center;
    margin: 1vh auto;
    font-size: 0.7rem;
}

.tab_description_inner_text{  
    width: 80%;
    text-align: left;
    margin: 1vh 0;
    font-size: 0.7rem;
    list-style-type:square;
    list-style-position: inside;
    min-width: 250px;
}

section{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;      
    margin: 0 auto;
    width:80vw; 
}

section img :first-child{
    width:80%;
}

.button_ribbon_download_app{
    display: flex;
    width:auto;
    margin: 2vh auto;
}

.button_ribbon_download_app a, .lonely_button_link{
    height: 3vh;
    font-size: 0.6rem;
    font-weight: bold;
    display: flex;
    align-items: center;
    width:fit-content;
    background: var(--color-hover);
}

.button_ribbon_download_app img{
    height: 2vh;
    background: var(--color-hover);
    margin-right: 1vw;
}

.button_ribbon_download_app a:link, .lonely_button_link:link{
    border: 2px solid var(--color-hover);
    color: white;
    border-radius: 25px;
    padding: 5px 3vw;
    margin-right:2vw;
    margin-left:0;
}

.button_ribbon_download_app a:visited, .lonely_button_link:visited{
    color:white;
    background: var(--color-hover);
}

.button_ribbon_download_app a:hover, .lonely_button_link:hover, #dropdown>li:last-child :hover{    
    box-shadow: 0px 0px 5px 2px violet;
}

.main_section_image{
    width: 80vw;
    margin: 6vh auto;
    z-index: 2;
}

@keyframes meneillo {
    from{
        transform: rotate(5deg);
    }
    
    to{
        transform: rotate(0deg);
    }
}

.main_section_image:hover{
    animation-name: meneillo;
    animation-duration: 0.25s;
    animation-iteration-count: 4;
    animation-play-state: running;
    animation-direction:alternate-reverse;    
}

#tab_description{
    display: flex;
    flex-direction: row;
    margin: 12vh auto;
    flex-wrap: wrap-reverse;
}

#tab_description>img{
    display: flex;
    padding: 0 2vw;
    width: 35vw;
    align-self: flex-start;
}

#tab_description article{
    display:flex;
    flex-direction: column;
    align-self: flex-start;
    padding: 0 0 3vh 3vw;
    width: 30vw;
    min-width: 250px;  
}

.circles_area a img:hover{
    animation-name: meneillo;
    animation-duration: 0.25s;
    animation-iteration-count: 4;
    animation-play-state: running;
    animation-direction:alternate-reverse;
}

:root{
    --color-base:#333333;
    --color-hover:#FF566E;
    --color-fondo: #F7FAFD;
}

nav img{
    height: 4vh;
}

nav li img{
    height: 5px;
    margin: 0 0.5vw;
}

nav ul{
    display: flex;
    align-items: baseline;
    flex-wrap: wrap;
}

.nav_option{
    list-style-type: none;
    padding: 5px 1vw;    
    display: flex;
    align-items: center;
}

nav a{
    text-decoration: none;
    color:var(--color-base);
}

.nav_option a:hover{
    color:var(--color-hover);
}

nav .nav_option:last-child a{
    border: 2px solid var(--color-hover);
    color:var(--color-hover);
    border-radius: 25px;
    padding: 5px 3vw;
    margin-left: 2vw;  
    font-weight: bolder;  
}

nav ul :nth-child(4):hover{
    color:var(--color-hover);
}

.dropdown :nth-child(4):hover .dropdown_menu{
    display: block;
    background-color: var(--color-fondo);      
}
  
.dropdown_menu {
    display: none;
    position: absolute;    
    padding: 0;
    top: 2vh;
    width: fit-content;
    height:fit-content;
    line-break: normal;
    box-shadow: 0px 5px 5px 2px #b9b7b73f;  
        
}

.dropdown_menu a:link{
    color:var(--color-base);
}

.dropdown_menu a:visited{
    color:var(--color-base);
}

.nav_subm_option{
    list-style-type: none;
    padding: 0.75rem 1.5rem;   
}

hr {
    border: none; 
    border-top: 1px solid #b9b7b73f 
  }

  
.circles_area{
    display:flex;
    flex-direction: row;
    flex-wrap: wrap;
    font-weight: bolder;
    row-gap: 5vh;
    gap: 5vw;
    font-size: 0.75rem;
}

.circles_area img{
    border-radius: 50%;
    height: 8vh;
    padding: 1vh;
}

.circles_area a{
    display:flex;
    flex-direction: column;
    justify-content: center;    
    align-items: center;
    height: 12vh;    
    text-align: center;
}

.circles_area :nth-child(1) img{
    background-color: #A073E930;
}

.circles_area :nth-child(2) img{    
    height: 6vh;
    background-color: #18C38930;
    padding: 2vh;
}

.circles_area :nth-child(3) img{
    height: 6vh;
    background-color: #FF566E30;
    padding: 2vh;
}

.circles_area :nth-child(4) img{
    height: 6vh;
    background-color: #FFAA1130;
    padding: 2vh;
}

.circles_area :nth-child(5) img{
    height: 6vh;
    background-color: #46B0E530;    
    padding: 2vh;
}

#app{
  display: none;
}


</style>
