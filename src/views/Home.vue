<template>
    <div>
        <header>
            <h1 class="header">
                Hello medic
            </h1>
            <button class="btn btn-danger header-btn">Login</button>
        </header>

        <div class="quick-ms">
            <div class="quick-ms-contents">
                <h1 class="Quick-Medical-Services">
                Quick Medical Services
            </h1>
            <p>Get a world class first treatment right where you are!</p>
            </div>

            <div class="img-illustration">
                <img src="../assets/imgs/HELLO MEDIC ILLUSTRATION-1.png" alt="" class="hlm-img">
            </div>
        </div>

        <div class="ellipse">
            <img src="../assets/imgs/Group 11.png" alt="">
        </div>

        <div class="what-we-do">
            <h2>What We Do</h2>
            <img src="../assets/imgs/Group 14.png" alt="">
            <p>Get world class health services a click away</p>
        </div>

        <div class="services">
            <div class="box my-4 py-4">
                <img src="../assets/imgs/HELLO MEDIC ILLUSTRATION FIRST AID.png" alt="First Aid">
                <h2 class="text-bold text-center my-4">Health kit</h2>
                <p>Lorem ipsum is simply a dumm text of the printing and typesetting industry. Lorem ipsum has been the industry</p>

                <button class="btn btn-danger my-4">Get your first aid kit &rarr;</button>
            </div>

            <div class="box my-4 py-4">
                <img src="../assets/imgs/HELLO MEDIC ILLUSTRATION DRUGS.png" alt="First Aid">
                <h2 class="text-bold text-center my-4">Prescriptions</h2>
                <p>Lorem ipsum is simply a dumm text of the printing and typesetting industry. Lorem ipsum has been the industry</p>

                <button class="btn btn-danger my-4">Order your prescriptions &rarr;</button>
            </div>

            <div class="box my-4 py-4">
                <img src="../assets/imgs/HELLO MEDIC ILLUSTRATION CALL.png" alt="First Aid">
                <h2 class="text-bold text-center my-4">Health kit</h2>
                <p>Lorem ipsum is simply a dumm text of the printing and typesetting industry. Lorem ipsum has been the industry</p>

                <button class="btn btn-danger my-4">Talk to a doctor &rarr;</button>
            </div>
        </div>

        <footer>
            <p>Hello medic</p>
            <p>&copy; All copyrights reserved</p>
            <p>Connect with us</p>
        </footer>
    </div>
</template>

<style>
body, html{
    width: 100%;
    height: 100%;
    box-sizing: border-box;
}
header {
    display: flex;
    justify-content: space-between;
}

.header {
    width: 233px;
    height: 90.5px;
    background: #e1bebe;
    line-height: 1.9em;
    font-size: 30px;
    text-align: center;
}

.header-btn {
  width: 108px;
  height: 40px;
  margin: 10px;
  border-radius: 3px;
  box-shadow: 0 4px 16px 0 rgba(0, 0, 0, 0.15);
  background-color: #ec3237;
  position: absolute;
  top: 10px;
  right: 0;
  font-family: 'Quicksand-Bold', sans-serif;

}

.quick-ms {
    margin: 30px 90px 0 ;
    display: flex;
    justify-content: space-between;
}

.Quick-Medical-Services{
  width: 483px;
  height: 124px;
  font-family: Quicksand;
  font-size: 52px;
  font-weight: bold;
  font-style: normal;
  font-stretch: normal;
  line-height: normal;
  letter-spacing: normal;
  color: #3f3d56;
}

.quick-ms-contents {
    margin: 75px 0 0 40px;
}

.hlm-img {
  width: 180px;
  position: absolute;
  top: 95px;
  right: 256px;
}

.ellipse {
    padding-top: 115px;
    text-align: center;
}

.what-we-do {
    text-align: center;
    padding-top: 50px;
}

.what-we-do h2 {
    font-weight: bold;
}

.what-we-do img {
    padding: 15px 0;
}

.services {
     margin-top: 40px; 
     background-color: #727a9c;
     padding: 30px;
     display: flex;
     justify-content: space-between;
}

.box {
     margin: 9px;
     background: white;
     width: 33.3%;
     font-weight: bold;
     text-align: center;
     padding: 40px;
     border-radius: 8px;
     box-shadow: 0 2px 12px 0 rgba(0, 0, 0, 0.15);
     border: solid 1px #e0e0e0;
}

.box img {
    padding-top: 30px;
}

footer {
    display: flex;
    justify-content: space-between; 
    background: #3f3d56;
}


footer p {
    line-height: 2.7em;
    font-size: 15px;
    color: white;
}

@media screen and (max-width:760px) {
    .hlm-img {
        display: none;
    }

    .quick-ms {
        text-align: center;
        display: flex;
        justify-content: center;
        align-content: center;
    }

    .services {
        display: flex;
        flex-wrap: wrap;
    }

    .box {
        width : 100%;
    }
}
</style>

