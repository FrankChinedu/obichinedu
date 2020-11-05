<template>
  <div id="app">
    <header class="header">
        <div class="container clearfix">                       
            <img class="profile-image img-fluid float-left" src="./assets/images/profile.png" alt="Obi chinedu frank" />
            <div class="profile-content float-left">
                <h1 class="name">Obi Chinedu Frank</h1>
                <h2 class="desc">Web Developer</h2>   
                <ul class="social list-inline">
                    <li class="list-inline-item"><a href="https://twitter.com/frankieetchy"><i class="fab fa-twitter"></i></a></li>                   
                    <!-- <li class="list-inline-item"><a href="#"><i class="fab fa-google-plus-g"></i></a></li> -->
                    <li class="list-inline-item"><a href="https://www.linkedin.com/in/obi-chinedu-frank-77007484/"><i class="fab fa-linkedin-in"></i></a></li>
                    <li class="list-inline-item"><a href="https://github.com/FrankChinedu"><i class="fab fa-github-alt"></i></a></li>    
                    <!-- <li class="list-inline-item"><a href="#"><i class="fab fa-stack-overflow"></i></a></li>    -->
                    <!-- <li class="list-inline-item last-item"><a href="#"><i class="fab fa-codepen"></i></a></li>                 -->
                </ul> 
            </div><!--//profile-->
        </div><!--//container-->
    </header>
    
    <div class="container sections-wrapper">
        <div class="row">
            <div class="primary col-lg-8 col-12">
                <section class="about section">
                    <div class="section-inner">
                        <h2 class="heading">About Me</h2>
                        <div class="content">
                            <p>
                                Hey there, I'm Frank, an enthusiastic developer that loves writing code and living.
                                 I have 3+ years of experience in web development and software engineering. 
                                 I am Goal-oriented, a conceptual thinker, a great team player and very passionate about enhancing human potential 
                                 by helping people and organizations grow. Fun guy, Love adventures, passion to learn and meet people. 
                            </p>
                        </div><!--//content-->
                    </div><!--//section-inner-->                 
                </section><!--//section-->
    
               <section class="latest section">
                    <div class="section-inner">
                        <h2 class="heading">Latest Projects</h2>
                        <div class="content">    
                                               
                            <div class="item featured text-center">
                                <h3 class="title"><a href="https://demeter-ah-frontend-staging.herokuapp.com/#/" target="_blank">Authors Haven</a></h3>
                                <p class="summary">A platform to share your amazing ideas and articles with the rest of the world</p>
                                <div class="featured-image has-ribbon">
                                    <a href="#">
                                    <img class="img-fluid project-image" src="./assets/images/projects/authors-haven.png" alt="Authors Haven" />
                                    </a>
                                    <div class="ribbon">
                                        <div class="text">New</div>
                                    </div>
                                </div>
                                    
                                <a class="btn btn-cta-secondary" href="https://demeter-ah-frontend-staging.herokuapp.com/#/" target="_blank"><i class="fas fa-thumbs-up"></i> Back my project</a>                 
                            </div><!--//item-->
                            <hr class="divider" />
                            <div class="item row">
                                <a class="col-md-4 col-12" href="" target="_blank">
                                <img class="img-fluid project-image" src="./assets/images/projects/riby.png" alt="Riby" />
                                </a>
                                <div class="desc col-md-8 col-12">
                                    <h3 class="title"><a href="https://riby.me/" target="_blank">Riby</a></h3>
                                    <p class="mb-2">Supporting your journey to financial freedom</p>
                                   </div><!--//desc-->                          
                            </div><!--//item-->
                            
                            <div class="item row">
                                <a class="col-md-4 col-12" href="https://watchtower.andela.com/" target="_blank">
                                <img class="img-fluid project-image" src="./assets/images/projects/watch-tower.png" alt="project name" />
                                </a>
                                <div class="desc col-md-8 col-12">
                                    <h3 class="title"><a href="" target="_blank">Watch Tower</a></h3>
                                    <p class="mb-2">It helps to keep track of an engineer growth rate, areas that need to be worked on, areas they are excelling at</p>
                                </div><!--//desc-->                          
                            </div><!--//item--> 

                            <div class="item row">
                                <a class="col-md-4 col-12" href="http://convertproof.com/home/" target="_blank">
                                <img class="img-fluid project-image" src="./assets/images/projects/convertproof.png" alt="project name" />
                                </a>
                                <div class="desc col-md-8 col-12">
                                    <h3 class="title"><a href="https://app.convertproof.com/login" target="_blank">ConvertProof</a></h3>
                                    <p class="mb-2">Increase conversion on your marketing pages by displaying live conversion notifications across your funnel.</p>
                                </div><!--//desc-->                          
                            </div><!--//item--> 


                        </div><!--//content-->  
                    </div><!--//section-inner-->                
                </section><!--//section-->
                
                <section class="experience section">
                    <div class="section-inner">
                        <h2 class="heading">Work Experience</h2>
                        <div class="content">
                            <div class="item">
                                <h3 class="title">Software Engineer- <span class="place"><a href="#">Riby</a></span> <span class="year">(2019 - Present)</span></h3>
                                <p></p>
                            </div><!--//item-->
                            <div class="item">
                                <h3 class="title">Software Engineer - <span class="place"><a href="#">Andela</a></span> <span class="year">(May-2019 - Sept-2019)</span></h3>
                                <p></p>
                            </div><!--//item-->
                            
                            <div class="item">
                                <h3 class="title">Software Engineer - <span class="place"><a href="#">SnapiLabs</a></span> <span class="year">(Jan-2018 - Jan-2019)</span></h3>
                                <p></p>
                            </div><!--//item-->
                            
                        </div><!--//content-->  
                    </div><!--//section-inner-->                 
                </section><!--//section-->
                <section class="github section">
                    <div class="section-inner">
                        <h2 class="heading">My GitHub Profile</h2> 
                        <div id="github-graph" class="github-graph">

                        </div><!--//github-graph-->

                        <div id="ghfeed" class="ghfeed">
                        </div><!--//ghfeed-->
                        
                    </div><!--//secton-inner-->
                </section><!--//section-->
            </div><!--//primary-->
            <div class="secondary col-lg-4 col-12">
                 <aside class="info aside section">
                    <div class="section-inner">
                        <h2 class="heading sr-only">Basic Information</h2>
                        <div class="content">
                            <ul class="list-unstyled">
                                <li><i class="fas fa-map-marker-alt"></i><span class="sr-only">Location:</span>Lagos Nigeria, US</li>
                                <li><i class="fas fa-envelope"></i><span class="sr-only">Email:</span><a href="#">frankieetchy@gmail.com</a></li>
                                <li><i class="fas fa-link"></i><span class="sr-only">Website:</span><a href="#">www.obichinedu.com</a></li>
                            </ul>
                        </div><!--//content-->  
                    </div><!--//section-inner-->                 
                </aside><!--//aside-->
                
                <aside class="skills aside section">
                    <div class="section-inner">
                        <h2 class="heading">Skills</h2>
                        <div class="content">
                            <p class="intro">
                            </p>
                            <div class="skillset">
                               
                                <div class="item">
                                    <h3 class="level-title">Nodejs<span class="level-label" data-toggle="tooltip" data-placement="left" data-animation="true" title="expert"><i class="fas fa-info-circle"></i>Expert</span></h3>
                                    <div class="level-bar">
                                        <div class="level-bar-inner" data-level="76%">
                                        </div>                                      
                                    </div><!--//level-bar-->                                 
                                </div><!--//item-->
                                
                                <div class="item">
                                    <h3 class="level-title">Javascript<span class="level-label" data-toggle="tooltip" data-placement="left" data-animation="true" title="You can use the tooltip to explain more about your skill level..."><i class="fas fa-info-circle"></i>Expert</span></h3>
                                    <div class="level-bar">
                                        <div class="level-bar-inner" data-level="96%">
                                        </div>                                      
                                    </div><!--//level-bar-->                                 
                                </div><!--//item-->
                                
                                <div class="item">
                                    <h3 class="level-title">HTML5 &amp; CSS3<span class="level-label" data-toggle="tooltip" data-placement="left" data-animation="true" title="You can use the tooltip to explain more about your skill level..."><i class="fas fa-info-circle"></i>Expert</span></h3>
                                    <div class="level-bar">
                                        <div class="level-bar-inner" data-level="96%">
                                        </div>                                      
                                    </div><!--//level-bar-->                                 
                                </div><!--//item-->
                                
                                <div class="item">
                                    <h3 class="level-title">Vuejs<span class="level-label" data-toggle="tooltip" data-placement="left" data-animation="true" title="You can use the tooltip to explain more about your skill level..."><i class="fas fa-info-circle"></i>Pro</span></h3>
                                    <div class="level-bar">
                                        <div class="level-bar-inner" data-level="70%">
                                        </div>                                      
                                    </div><!--//level-bar-->                                 
                                </div><!--//item-->

                                <div class="item">
                                    <h3 class="level-title">Reactjs<span class="level-label" data-toggle="tooltip" data-placement="left" data-animation="true" title="You can use the tooltip to explain more about your skill level..."><i class="fas fa-info-circle"></i>Pro</span></h3>
                                    <div class="level-bar">
                                        <div class="level-bar-inner" data-level="70%">
                                        </div>                                      
                                    </div><!--//level-bar-->                                 
                                </div><!--//item-->

                                <div class="item">
                                    <h3 class="level-title">Laravel<span class="level-label" data-toggle="tooltip" data-placement="left" data-animation="true" title="You can use the tooltip to explain more about your skill level..."><i class="fas fa-info-circle"></i>Pro</span></h3>
                                    <div class="level-bar">
                                        <div class="level-bar-inner" data-level="70%">
                                        </div>                                      
                                    </div><!--//level-bar-->                                 
                                </div><!--//item-->
                            </div>              
                        </div><!--//content-->  
                    </div><!--//section-inner-->                 
                </aside><!--//section-->
                
                <aside class="testimonials aside section">
                    <div class="section-inner">
                        <h2 class="heading">Testimonials</h2>
                        <div class="content">
                            <div class="item">
                                <blockquote class="quote">                                  
                                    <p><i class="fas fa-quote-left"></i>Frank is a fantastic person to work with and is a multi-skilled and insightful colleague. He is a very hardworking and proactive individual.</p>
                                </blockquote>                
                                <p class="source"><span class="name">Timi Tejumola</span><br /><span class="title">Curabitur commodo</span></p>                                                             
                            </div><!--//item-->
                            
                            <p><a class="more-link" href="https://www.linkedin.com/in/obi-chinedu-frank-77007484/"><i class="fas fa-external-link-alt"></i>More on Linkedin</a></p> 
                            
                        </div><!--//content-->
                    </div><!--//section-inner-->
                </aside><!--//section-->
                
                <aside class="education aside section">
                    <div class="section-inner">
                        <h2 class="heading">Education</h2>
                        <div class="content">
                            <div class="item">                      
                                <h3 class="title"><i class="fas fa-graduation-cap"></i>Physics</h3>
                                <h4 class="university">Federal university of Technology, owerri<span class="year">(2009-2014)</span></h4>
                            </div><!--//item-->
                        </div><!--//content-->
                    </div><!--//section-inner-->
                </aside><!--//section-->
                            
                <aside class="languages aside section">
                    <div class="section-inner">
                        <h2 class="heading">Languages</h2>
                        <div class="content">
                            <ul class="list-unstyled">
                                <li class="item">
                                    <span class="title"><strong>English:</strong></span>
                                    <span class="level">Native Speaker <br class="visible-xs"/><i class="fas fa-star"></i> <i class="fas fa-star"></i> <i class="fas fa-star"></i> <i class="fas fa-star"></i> <i class="fas fa-star"></i> </span>
                                </li><!--//item-->
                                
                            </ul>
                        </div><!--//content-->
                    </div><!--//section-inner-->
                </aside><!--//section-->
                
                <aside class="blog aside section">
                    <div class="section-inner">
                        <!-- <h2 class="heading">Latest Blog Posts</h2> -->
                        <!-- <p>You can use Sascha Depold's <a href="https://github.com/sdepold/jquery-rss" target="_blank">jQuery RSS plugin</a> to pull in your blog post feeds.</p> -->
                        <!-- <div id="rss-feeds" class="content"> -->

                        <!-- </div>//content -->
                    </div><!--//section-inner-->
                </aside><!--//section-->
                
                <aside class="list music aside section">
                    <div class="section-inner">
                        <h2 class="heading">Favourite coding music</h2>
                        <div class="content">
                            <ul class="list-unstyled">
                                <li><i class="fas fa-headphones"></i> <a href="https://youtu.be/M7g7Pfx6zjg">youtube programming song</a></li>
                                <li><i class="fas fa-headphones"></i> <a href="https://www.deezer.com">Deezer</a></li>
                            </ul>
                        </div><!--//content-->
                    </div><!--//section-inner-->
                </aside><!--//section-->
                
                <aside class="list conferences aside section">
                    <div class="section-inner">
                        <h2 class="heading">Conferences</h2>
                        <div class="content">
                            <ul class="list-unstyled">
                                <li><i class="far fa-calendar-alt"></i> <a href="https://www.concatenate.dev/">Concatenate</a> (Lagos Nigeria)</li>
                            </ul>
                        </div><!--//content-->
                    </div><!--//section-inner-->
                </aside><!--//section-->
              
            </div><!--//secondary-->    
        </div><!--//row-->
    </div><!--//masonry-->
    
    <!-- ******FOOTER****** --> 
    <footer class="footer">
        <div class="container text-center">
                <!--/* This template is free as long as you keep the attribution link below. Thank you for your support. :) If you'd like to use the template without the attribution, you can buy the commercial license via our website: themes.3rdwavemedia.com */-->
                <small class="copyright">Designed with <i class="fas fa-heart"></i> by <a href="https://themes.3rdwavemedia.com" target="_blank">Xiaoying Riley</a> for developers</small>
        </div><!--//container-->
    </footer><!--//footer-->
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
