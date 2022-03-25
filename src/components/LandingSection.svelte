<script>
    
</script>

<main>
    <img class="bgm_img" src="images/bgm_img.jpg" alt="">
    <div class="navbar">
        <img src="images/cyborn-logo.png" alt="" class="mainlogo">
        <div class="menu">
            <a href="." class="home">Home</a>
            <a href="." class="about">About us</a>
            <a href="." class="career">Career</a>
            <a href="." class="blog">Blog</a>
        </div>
    </div>

    <div class="landingsection">
        <p class="landing-text">
            Lorem ipsum dolor sit amet consectetur adipisicing elit.
        </p>

    </div>
</main>

<style>
    @import url('http://fonts.cdnfonts.com/css/sofia-pro');
    main{ 
        background: rgb(14, 14, 14); 
        color: #FFFFFF;
        overflow: hidden;
    }
    
    .bgm_img{ 
        height: 971px;
        background-position:center;
        background-repeat: no-repeat;
        opacity: 0.80;
        width: 1512px;
        animation: zoom 100s linear 2s infinite normal none;
        
    }

    @keyframes zoom{
        0% {transform: scale(1, 1);}

        12% {transform: scale(1.12, 1.12);}

        25% {transform: scale(1.25, 1.25);}

        37% {transform: scale(1.37,1.37);}

        50% {transform: scale( 1.5, 1.5);}

        62% {transform: scale(1.37, 1.37);}

        75% {transform: scale( 1.25, 1.25);}

        87% {transform: scale( 1.12, 1.12);}
        
        100% {transform: scale(1,1);}
    }

    .mainlogo{
        position: absolute;
        width: 42.83px;
        height: 48px;
        top: 56px;
        left: 90px;
    }

    .menu{
        width: 100%;
        height: 100px;
        position: absolute;
        top: 0;
        display: flex;
        flex-direction: column;
    }

    .blog{
        position: absolute;
        right: 90px;
        top: 74px;
        text-decoration: none;
        font-family: 'Sofia Pro';
        font-style: normal;
        font-weight: 400;
        font-size: 20px;
        line-height: 20px;
        color: #FFFFFF;
    }

    .career{
        position: absolute;
        right: 190px;
        top: 74px;
        text-decoration: none;
        font-family: 'Sofia Pro';
        font-style: normal;
        font-weight: 400;
        font-size: 20px;
        line-height: 20px;
        color: #FFFFFF;
    }


    .home{
        position: absolute;
        right: 430px;
        top: 74px;
        width: auto;
        text-decoration: none;
        font-family: 'Sofia Pro';
        font-style: normal;
        font-weight: 400;
        font-size: 20px;
        line-height: 20px;
        color: #FFFFFF;
    }

    .about{
        position: absolute;
        right: 300px;
        top: 74px;
        text-decoration: none;
        font-family: 'Sofia Pro';
        font-style: normal;
        font-weight: 400;
        font-size: 20px;
        line-height: 20px;
        color: #FFFFFF;
    }

    .landingsection{
        background-color: transparent;
        padding-left: 90px;
    }

    .landing-text{
        position: absolute;
        bottom: 50px;
        width: 50%;
        font-family: 'Sofia Pro';
        font-style: normal;
        font-weight: 700;
        font-size: 55px;
        line-height: 60px;
        color: #FFFFFF;
    }

    /* Extra small devices (phones, 600px and down) */
    /*From 0 to 600px*/
    @media only screen and (max-width: 600px) {
        
        main{
            background-color: rgb(0, 0, 0);
            overflow:hidden;
        }

        .mainlogo{
            top: 23px;
            left: 30px;
        }
        
        .menu{
            position: absolute;
            width: 100%;
            height: 100px;
            top: 0;
            display: flex;
            flex-direction: column;
        }

        .home{
            position: absolute;
            top: 30px;
            right: 30px;
            font-family: 'Sofia Pro';
            font-style: normal;
            font-weight: 400;
            font-size: 20px;
            line-height: 20px;
            text-decoration: none;
            color: #FFFFFF;
        }
        
        .about{
            position: absolute;
            top: 80px;
            right: 30px;
            font-family: 'Sofia Pro';
            font-style: normal;
            font-weight: 400;
            font-size: 20px;
            line-height: 20px;
            text-decoration: none;
            color: #FFFFFF;
        }

        .career{
            position: absolute;
            top: 130px;
            right: 30px;
            font-family: 'Sofia Pro';
            font-style: normal;
            font-weight: 400;
            font-size: 20px;
            line-height: 20px;
            text-decoration: none;
            color: #FFFFFF;
        }

        .blog{
            position: absolute;
            top: 180px;
            right: 30px;
            font-family: 'Sofia Pro';
            font-style: normal;
            font-weight: 400;
            font-size: 20px;
            line-height: 20px;
            text-decoration: none;
            color: #FFFFFF;
        }

        .landing-text{
            left: 30px;
            top: 375px;
        }
    }

    /* Small devices (portrait tablets and large phones, 600px and up) */
    /*From 600 to 768px*/    
    @media only screen and (min-width: 600px) and (max-width: 744px) {
        main{
            background-color: rgb(0, 0, 0);
            width: 100%;
        }

        .bgm_img{
            height: 909px;
        }

        .mainlogo{
            top:45px;
            left:44px;
        }

        .blog{
            right: 45px;
            top: 59px;
        }

        .career{
            top: 59px;
            right: 157px;
        }

        .about{
            top: 59px;
            right: 291px;
        }

        .home{
            top:59px;
            right: 441px;
        }

        .landing-text{
            width: 402px;
            height: 67px;
            left: 44px;
            top: 450px;
        }
    }

</style>