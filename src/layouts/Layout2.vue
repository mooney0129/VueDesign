<script>
</script>

<template>
  <div class="layout2-container mt40 f-row f-center">
        <div class="f-col">
            <div class="f60 f-dark-blue ftb">Token Details</div>
            <div class="layout2-token-detail f-row f-center">
                <div class="f-col f-center w25 h100 mr10">
                    <div class="f-col  w100 h50">
                        <div class="f18 f-dark-blue f-al">Ticker</div>
                        <div class="f32 f-dark-blue f-ar">HMT</div>
                    </div>
                    <div class="w100 brt mt5"></div>
                    <div class="f-col w100 h50 mt15">
                        <div class="f18 f-dark-blue f-al">Token Price</div>
                        <div class="">
                            <div class="f32 f-dark-blue d-in-l">USD</div>
                            <div class="f32 f-dark-blue d-in-r">7.6</div>
                        </div>
                    </div>
                </div>
                <div class="brr h100"></div>
                <div class="f-col f-center w75 ml20">
                    <div class="w100 h33 f-row f-center">
                        <div class="f18 f-dark-blue w50 f-al">Circulating Supply</div>
                        <div class="f32 f-dark-blue w50 f-ar">120,000,000</div>
                    </div>
                    <div class="w100 brt mt5"></div>
                    <div class="w100 h33 f-row f-center">
                        <div class="f18 f-dark-blue w50 f-al">Total Supply</div>
                        <div class="f32 f-dark-blue w50 f-ar">1.000.000.000</div>
                    </div>
                    <div class="w100 brt mt5"></div>
                    <div class=" w100 h33  f-row f-center">
                        <div class="f18 f-dark-blue w50 f-al">Market Cap</div>
                        <div class="f32 f-dark-blue w50 f-ar">1.000.000.000</div>
                    </div>
                </div>
            </div>
            <div class=" mt20">
                <div class="token-type-container d-in-l">
                    <div class="f18 ma d-in-l"><span class=" f-row f-center" style="height:45px; padding-left:20px">Token Type</span></div>
                    <div class="f32 f-dark-blue d-in-r mr10">ERC-20</div>
                </div>
                <div class="contact-address-container d-in-r">
                    <div>
                        <div class="f18 ma d-in-l f-dark-blue d-in-l"><span class=" f-row f-center" style="height:45px; padding-left:20px">Contact Address</span></div>
                        <div class="d-in-r"><button class="link-btn ml30">Ethereum</button></div>
                        <div class="d-in-r"><button class="link-btn ml40 mr10">Polygon</button></div>
                    </div>
                </div>
               
            </div>
             <div class="f-row f-center mt40">
                <div class="audit-item w50 pd10" style="padding:20px">
                    <div class="f18 d-in-l" style="height:100%"><div class=" f-row f-center" style="height:100%">Smart Contract Audit</div></div>
                    <div class="f32 d-in-r" style="height:100%"><div class=" f-row f-center" style="height:100%">Loremipsum</div></div>
                </div>
                <div class="audit-item w50 ml40  pd10" style="padding:20px">
                    <div class="f18 d-in-l" style="height:100%"><div class=" f-row f-center" style="height:100%">Escrow Factory</div></div>
                    <div class="f32 d-in-r" style="height:100%"><div class=" f-row f-center" style="height:100%">Loremipsum</div></div>
                </div>
            </div>
            <div class="company-lists f-row f-center">
                <div class="f18 ftb f-dark-blue f-row f-center w100">Exchanges</div>
                <div class="f18 ftb f-dark-blue w100 f-row f-center"><img src="@/assets/company1.png" style="width:177px; height:20px"></div>
                <div class="f18 ftb f-dark-blue w100 f-row f-center"><img src="@/assets/company2.png" style="width:132px; height:46"></div>
                <div class="f18 ftb f-dark-blue w100 f-row f-center"><img src="@/assets/company3.png" style="width:168px; height:18px"></div>
                <div class="f18 ftb f-dark-blue w100 f-row f-center"><img src="@/assets/company4.png" style="width:122px; height:33px"></div>
                <div class="f18 ftb f-dark-blue w100 f-row f-center"><img src="@/assets/company5.png" style="width:109px; height:24px"></div>
            </div>
        </div>
  </div>
</template>

<style scoped>
    @media only screen and (max-width:1175px)
    {
        .layout2-container{
            display: none!important;
        }
    }
    .layout2-container{
        padding:143px 0px;
        width: 100%;
        background: linear-gradient(167.14deg, #F0F2FC 9.58%, #FFFFFF 93.46%)!important;
    }
    
    .layout2-token-detail{
        margin-top: 60px;
        width:1168px;
        height:248px;
        padding:80px 38px 40px 38px;
        background: #FFFFFF;
        border-radius: 30px;
    }
    .token-type-container{
        padding:14px;
        width:357px;
        height:79px;
        background: #FFFFFF;
        border-radius: 30px;
    }
    .contact-address-container{
        padding:14px;
        width:auto;
        height:79px;
        background: #FFFFFF;
/* Blue/400 */
        border: 2px solid #320A8D;
        border-radius: 40px;
    }
    .audit-item{
        height:80px;
        background: #320A8D;
        border-radius: 25px;
        color:white;
    }
    .link-btn{
        width:200px;
        height:75px;
        background: #FFFFFF;
        border-radius: 10px;
      cursor:pointer;
    }
    .company-lists{
        margin-top: 69px;
        width:1168px;
        height:80px;
        box-shadow: 4px 4px 10px #e9eaf0;
        background: #FFFFFF;
        border-radius: 30px;
    }
</style>
