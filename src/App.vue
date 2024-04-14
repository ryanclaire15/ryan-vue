<template>
  <div class="container-fluid">
            <div class="row">
                <div class="col-md-12 top"></div>
            </div>
            <div class="row">
                <div class="col-md-12">
                    <div class="hamburger-menu mobile">
                        <div class="button_container" id="toggle"><span class="top"></span><span class="middle"></span><span class="bottom"></span></div>
                        <div class="overlay" id="overlay">
                            <nav class="overlay-menu">
                                <ul>
                                    <li><a href="#home">HOME</a></li>
                                    <li><a href="#about">ABOUT Me</a></li>
                                    <li><a href="#gallery">GALLERY</a></li>
                                    <li><a href="#contact">CONTACT ME!</a></li>
                                </ul>
                            </nav>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="row menu top-nav align-items-center desktop">
                <div class="col-md-12 right-menu">
                    <ul class="navigation">
                        <li>
                            <a href="#home">HOME</a>
                        </li>
                        <li>
                            <a href="#about">ABOUT ME</a>
                        </li>
                        <li>
                            <a href="#gallery">GALLERY</a>
                        </li>
                        <li>
                            <a href="#contact">CONTACT ME</a>
                        </li>
                   </ul>
                </div>
            </div>
            <div class="row align-items-center text-center bg-container" id="home">
                <div class="col-md-12">
                    <h1>KAPANGGAL</h1>
                    <div class="separator"></div>
                    <h1>RYAN</h1>
                </div>
            </div>
            <div class="row"  id="about">
                <div class="col-md-12 green-content-separator"></div>
            </div>
            <div class="row align-items-center text-center bg-title team">
                <div class="bg-overlay"></div>
                <div class="col-md-12">
                    <h1>ABOUT ME</h1>
                </div>
            </div>
            <div class="row about-box-content team-box">
                <h1></h1>
                <div class="col-md-6 col-sm-12 text-right">
                    <div class="box">
                    </div>
                </div>
                <div class="col-md-6 col-sm-12 about-content">
                    <p>
                      A man of God doesn't follow his own will but follow the will of the Lord Jesus Christ. I believe the power of God that changes a boy into a man of God, which is i created this to show a glimpse of my world and experiences that shapes me.                    </p>
                    <p>
                      "My role and responsibility, as a man of God, are to steward the resources and gifts He has given me." Jesus teaches this in the parable of the talents and the minas. Remember, you are not responsible for things God has not put in your care, only that for which He has graciously given you.                    </p>
                </div>
            </div>
            <div class="row align-items-center text-center bg-title gallery-head">
                <div class="bg-overlay"></div>
                <div class="col-md-12">
                    <h1>GALLERY</h1>
                </div>
            </div>
            <div class="row gallery">
                <div class="col-md-4 box">
                    <div class="box-img">
                        <img :src="require('@/assets/images/ryan1.jpg')" alt="fp-logo">
                    </div>
                </div>
                <div class="col-md-4 box">
                    <div class="box-img">
                        <img :src="require('@/assets/images/ryan2.jpg')" alt="fp-logo">
                    </div>
                </div>
                <div class="col-md-4 box">
                    <div class="box-img">
                        <img :src="require('@/assets/images/ryan3.jpg')" alt="fp-logo">
                    </div>
                </div>
                <div class="col-md-4 box">
                    <div class="box-img">
                        <img :src="require('@/assets/images/ryan4.jpg')" alt="fp-logo">
                    </div>
                </div>
                <div class="col-md-4 box">
                    <div class="box-img">
                        <img :src="require('@/assets/images/ryan5.jpg')" alt="fp-logo">
                    </div>
                </div>
                <div class="col-md-4 box">
                    <div class="box-img">
                        <img :src="require('@/assets/images/ryan6.jpg')" alt="fp-logo">
                    </div>
                </div>
                <div class="col-md-4 box">
                    <div class="box-img">
                        <img :src="require('@/assets/images/ryan7.jpg')" alt="fp-logo">
                    </div>
                </div>
                <div class="col-md-4 box">
                    <div class="box-img">
                        <img :src="require('@/assets/images/ryan8.jpg')" alt="fp-logo">
                    </div>
                </div>
                <div class="col-md-4 box">
                    <div class="box-img">
                        <img :src="require('@/assets/images/ryan9.jpg')" alt="fp-logo">
                    </div>
                </div>
            </div>
             <div class="row" id="contact">
                <div class="col-md-12 green-content-separator"></div>
            </div>
            <div class="row align-items-center text-center bg-title contact">
                <div class="bg-overlay"></div>
                <div class="col-md-12">
                    <h1>CONTACT ME</h1>
                </div>
            </div>
            <div class="row contact-container">
                <div class="col-md-12">
                    <div class="row contact-box align-items-center">
                        <div class="col-md-12 form text-center">
                            <h1>Get in Touch!</h1>
                            <span>Feel free to drop us a line below</span>
                            <form action="">
                                <input type="text" name="" id="" placeholder="Your Full Name">
                                <input type="text" name="" id="" placeholder="Your Email">
                                <textarea name="" id="" cols="30" rows="10" placeholder="Type here your concerns"></textarea>
                                <button>Submit</button>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
            <div class="row footer align-items-center">
                <div class="col-md-12 text-center">
                    <p>Copyright 2023. All Rights Reserved</p>
                </div>
            </div>
        </div>
</template>

<script>
export default {
  name: 'App',
  mounted() {
    $('#toggle').click(function() {
      $(this).toggleClass('active');
      $('#overlay').toggleClass('open');
    });
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
