<template>
     <div class="ms_container sectionTre d-flex justify-content-between">

         <div class="text-center col-3 aaa">
             <h4 class="col-uno-tx  mt-5 mb-3">Find a freshly backed product perfect for you</h4>
            <div class="col-uno-our mt-1">Integer a nibh vitae ex porttitor rutrum et ut velit. Etiam ac felis at leo feugiat placerat. Sed  ac nulla id orci tempor convallis sed.</div>
            <button class="btn-prymary btn-tx ms_btn-style-primary mt-3"><a href="#">Shop All Products</a></button>
         </div>

         <div class="col-2 aaa">
            <div class="select-container-left  imageUno">
                 <div class="select select-left"> <i class="fas fa-angle-left"></i> </div>
            </div>
            <div class="text-center mt-3">
                    <b class="img-name">Choco Chip Cookies</b>
                    <h6 class="img-price mt-2">$19.00 - $39.00</h6>
            </div>
         </div>
        
         <div class="col-2 aaa">
             <div class="img imageDuo"></div>
              <div class="text-center mt-3">
                    <b class="img-name">Strawberry Jam Cookies</b>
                    <h6 class="img-price mt-2">$24.00 - $62.00</h6>
            </div>
         </div>

         <div class="col-2 aaa">
             <div class="img imageTre"></div>
              <div class="text-center mt-3">
                    <b class="img-name">Strawberry Donut</b>
                    <h6 class="img-price mt-2">$24.00 - $42.00</h6>
            </div>
         </div>

         <div class="col-2 aaa">
             <div class="select-container-right  imageQuattro">
                 <div class="select select-right"><i class="fas fa-angle-right"></i> </div>
             </div> 
              <div class="text-center mt-3">
                    <b class="img-name">Perfect Macarons</b>
                    <h6 class="img-price mt-2">$18.00 - $52.00</h6>
            </div>
         </div>
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

     .aaa{
        margin: 4rem 0; 

        
            .col-uno-our{
                color:$color-grey-text;
                font-size: .9rem;
            }

            .col-uno-tx{
                color:$brand-primary-color;
                padding-top:3rem;

            }
        } 

         .select{
                background-color: #a698c4;
                padding: 1.3rem .8rem;
                color:white;
            }

        .select-container-left{
            height: 300px;
            background-image: url("../assets/image/choco-chip-cookies-400x510.jpg");
            background-position: center;
            background-size:cover;
            background-repeat:no-repeat;
            position:relative;
            
              .select-left{
                    position: absolute;
                    top: 40%;
                    left: 0;
                }
        }

         .select-container-right{
             height: 300px;
            background-image: url("../assets/image/strawberry-jam-cookies-400x510.jpg");
            background-position: center;
            background-size:cover;
            background-repeat:no-repeat;
            position: relative;
            
             .select-right{
                    position: absolute;  
                    top: 40%;
                    right: 0;
                }
        }
        .img{
            height:300px;
            background-position: center;
            background-size:cover;
            background-repeat:no-repeat;
        }
        .imageUno{
            background-image: url("../assets/image/choco-chip-cookies.jpg");
        }

          .imageDuo{
            background-image: url("../assets/image/strawberry-jam-cookies.jpg");
        }
          .imageTre{
            background-image: url("../assets/image/strawberry-donut.jpg");
        }

          .imageQuattro{
            background-image: url("../assets/image/perfect-macarons.jpg");
        }

        .img-name{
                color:$brand-primary-color;
                font-size:1.2rem;
        }

        .img-price{
            color:$brand-primary-color;  
            font-size:.8rem;    
        }
}
</style>