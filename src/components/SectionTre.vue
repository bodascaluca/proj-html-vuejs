<template>
     <div class="ms_container sectionTre d-flex justify-content-between">

         <div class="border text-center col-3 aaa">
            <div class="col-uno-our text-uppercase">our products</div>
            <h4 class="col-uno-tx mt-3 mb-5">All our delectable pastries are backed fresh in our Kitchen very morning, and are made with all-natural. all organic ingredients.</h4>
            <button class="btn-prymary btn-tx ms_btn-style-primary" ><a href="#">Start Shopping</a></button>
         </div>

         <div class="border imageUno col-2 aaa"></div>

         <div class="border imageDuo col-2 aaa"></div>

         <div class="border imageTre col-2 aaa"></div>

         <div class="border imageQuattro col-2 aaa"></div>


        <!-- <div class="col-5 me-5 aaa">
            <div class="col-uno-our text-uppercase">our products</div>
            <h4 class="col-uno-tx mt-3 mb-5">All our delectable pastries are backed fresh in our Kitchen very morning, and are made with all-natural. all organic ingredients.</h4>
            <button class="btn-prymary btn-tx ms_btn-style-primary" ><a href="#">Start Shopping</a></button>
        </div> -->

        <!-- <div class="select-container-left col-5 aaa">
            <div class="select select-left"> <i class="fas fa-angle-left"></i> </div>
        </div>

        <div class="select-container-right col-5 aaa">
            <div class="select select-right"><i class="fas fa-angle-right"></i> </div>
        </div> -->

        
    </div>
</template>

<script>
export default {
    name:"SectionTre",
}
</script>

<style scoped lang="scss">
@import "../style/common.scss";
@import "../style/btn.scss";

.sectionTre{
    border:1px solid orange;

     .aaa{
        margin: 4rem 0; 

        
            .col-uno-our{
                color:$color-grey-text;
                font-size: .7rem;
            }

            .col-uno-tx{
                color:$brand-primary-color;
            }
        } 

         .select{
                background-color: #a698c4;
                padding: 1.3rem .8rem;
                color:white;
            }

        .select-container-left{
            height: 400px;
            background-image: url("../assets/image/choco-chip-cookies-400x510.jpg");
            background-position: center;
            background-size:cover;
            background-repeat:no-repeat;
            position:relative;
            
              .select-left{
                    position: absolute;
                    top: 43%;
                    left: 0;
                }
        }

         .select-container-right{
             height: 400px;
            background-image: url("../assets/image/strawberry-jam-cookies-400x510.jpg");
            background-position: center;
            background-size:cover;
            background-repeat:no-repeat;
            position: relative;
            
             .select-right{
                    position: absolute;  
                    top: 43%;
                    right: 0;
                }
        }

        .imageUno{
            background-image: url("../assets/image/choco-chip-cookies.jpg");
             background-position: center;
            background-size:cover;
            background-repeat:no-repeat;
        }

          .imageDuo{
            background-image: url("../assets/image/strawberry-jam-cookies.jpg");
             background-position: center;
            background-size:cover;
            background-repeat:no-repeat;
        }
          .imageTre{
            background-image: url("../assets/image/strawberry-donut.jpg");
             background-position: center;
            background-size:cover;
            background-repeat:no-repeat;
        }

          .imageQuattro{
            background-image: url("../assets/image/perfect-macarons.jpg");
             background-position: center;
            background-size:cover;
            background-repeat:no-repeat;
        }
}
</style>