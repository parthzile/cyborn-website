<script>

</script>

<main>
    <div class="footer">
        <img src="images/cyborn-logo.png" alt="" class="mainlogo">
    </div>

    <div class="flex-container">
        <div class="column1"> 
            <p>Column 1</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint, maiores.</p>
        </div>
        <div class="column2"> 
            <p>Column 2</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint, maiores.</p>
        </div>
        <div class="column3">
            <p> Column 3</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint, maiores.</p>
        </div>
        <div class="column4"> 
            <p> Column 4</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint, maiores.</p>
        </div>
        <div class="column5"> 
            <p> Column 5</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint, maiores.</p>

        </div>
    </div>
</main>

<style>
    @import url('http://fonts.cdnfonts.com/css/sofia-pro');

    main{
        height: auto;
        left: 0px;
        background: #000000;
        padding-left: 90px;
        padding-right: 90px;
        padding-bottom: 90px;
        margin: none;
        font-family: 'Sofia Pro';
        font-size: 20px;
        font-weight: 400;
    }

    .mainlogo{
        position: relative;
        padding-top: 50px;
        width: 42.83px;
        height: 48px;

    }

    .flex-container{
        display: flex;
        flex-direction: row;
        color: #FFFFFF;
        padding-left: 150px;
        padding-right: 90px;
        justify-content: space-around;
    }


    .column1{
        width: auto;
        padding-right: 50px;
        text-align: center;
    }
    .column2{
        width: auto;
        padding-right: 50px;
        text-align: center;
    }
    .column3{
        width: auto;
        padding-right: 50px;
        text-align: center;
    }
    .column4{
        width: auto;
        padding-right: 50px;
        text-align: center;
    }
    .column5{
        width: auto;
        padding-right: 50px;
        text-align: center;
    }

    /* Extra small devices (phones, 600px and down) */
    /*From 0 to 600px*/
    @media only screen and (max-width: 600px) {
        
        main{
            background-color: rgb(0, 0, 0);
            padding-left: 0;
            padding-right: 0;
        }

        .mainlogo{
            padding-left: 30px;
            padding-top: 18px;
        }

        .flex-container{
            align-self: flex-center;
            flex-direction: column;
        }

        .column1{
            padding-right: 20px;
        }

        .column2{
            padding-right: 20px;
        }

        .column3{
            padding-right: 20px;
        }

        .column4{
            padding-right: 20px;
        }
        
        .column5{
            padding-right: 20px;
        }
        
    }

    @media only screen and (min-width: 600px) and (max-width: 744px) {
        main{
            background-color: rgb(0, 0, 0);
            padding-left: 0px;
            padding-right: 0px;
        }

        .mainlogo{
            padding-left: 44px;
        }

        .flex-container{
            /*align-self: flex-center;*/
            flex-direction: column;
        }
    
    }

    /* Medium devices (landscape tablets, 768px and up) */
    /*From 768 and above  */  
    @media only screen and (min-width: 744px) {
        @import url('http://fonts.cdnfonts.com/css/sofia-pro');

        main{
            height: auto;
            left: 0px;
            top: 750px;
            background: #000000;
            padding-left: 90px;
            padding-right: 90px;
            padding-bottom: 90px;
            margin: none;
            font-family: 'Sofia Pro';
            font-size: 20px;
            font-weight: 400;
        }

        .mainlogo{
            padding-top: 50px;
            width: 42.83px;
            height: 48px;

        }

        .flex-container{
            display: flex;
            flex-direction: row;
            color: #FFFFFF;
            padding-left: 150px;
            padding-right: 90px;
            justify-content: space-around;
        }

        .column1{
            width: auto;
            padding-right: 50px;
            text-align: center;
        }

        .column2{
            width: auto;
            padding-right: 50px;
            text-align: center;
        }

        .column3{
            width: auto;
            padding-right: 50px;
            text-align: center;
        }

        .column4{
            width: auto;
            padding-right: 50px;
            text-align: center;
        }

        .column5{
            width: auto;
            padding-right: 50px;
            text-align: center;
        }

    }

</style>