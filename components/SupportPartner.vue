<template>
    <section class="support-partner-section relative z-50">
        <div class="grid px-6 lg:px-8 py-8 mx-auto lg:gap-8 xl:gap-0 lg:py-16 lg:grid-cols-12 max-w-screen-xl z-50">
            <div class="mr-auto place-self-center col-span-12 lg:col-span-6 mb-10 lg:mb-0">
                <h1 class="lg:max-w-2xl mb-7 text-3xl md:text-4xl lg:text-5xl primary-text leading-10 text-center lg:text-start">How we support our pratner all over the worlds</h1>
                <p class="lg:max-w-lg mb-6 lg:mb-16 secondary-text text-center lg:text-start">SaaS become a common delivery model for many business application, including office software, messaging software, payroll processing software, DBMS software, management software</p>
                <div class="flex rating flex-col lg:flex-row text-center lg:text-start">
                    <div class="mr-0 lg:mr-20 mb-6 lg:mb-0">
                        <img src="/images/5-star.png" alt="" class="w-36 mb-4 mx-auto lg:mx-0">
                        <div class="rate mb-4">
                            4.9 / 5 rating
                        </div>
                        <div class="partner-name">
                            databricks
                        </div>
                    </div>
                    <div>
                        <img src="/images/4-star.png" alt="" class="w-36 mb-4 mx-auto lg:mx-0">
                        <div class="rate mb-4">
                            4.8 / 5 rating
                        </div>
                        <div class="partner-name">
                            Chainalysis
                        </div>
                    </div>
                </div>
            </div>
            <div class="lg:mt-0 col-span-12 lg:col-span-6 pl-0 lg:pl-6 features flex flex-col space-y-10">
                <div class="flex space-y-4 lg:space-y-0 lg:space-x-5 flex-col lg:flex-row items-center lg:items-start text-center lg:text-start">
                    <div class="white-square shrink-0 flex justify-center items-center">
                        <img src="/images/svg/activity-1.svg" alt="">
                    </div>
                    <div>
                        <h3 class="mb-2 title-text text-xl lg:text-2xl">Publishing</h3>
                        <p class="subtitle-text">Plan, collaborate, and publishing your contetn that drivees meaningful engagement and growth for your barnd</p>
                    </div>
                </div>
                <div class="flex space-y-4 lg:space-y-0 lg:space-x-5 flex-col lg:flex-row items-center lg:items-start text-center lg:text-start">
                    <div class="white-square shrink-0 flex justify-center items-center">
                        <img src="/images/svg/pie-chart-1.svg" alt="">
                    </div>
                    <div>
                        <h3 class="mb-2 title-text text-xl lg:text-2xl">Analytics</h3>
                        <p class="subtitle-text">Analyze your performance and create goegeous report</p>
                    </div>
                </div>
                <div class="flex space-y-4 lg:space-y-0 lg:space-x-5 flex-col lg:flex-row items-center lg:items-start text-center lg:text-start">
                    <div class="white-square shrink-0 flex justify-center items-center">
                        <img src="/images/svg/command-1.svg" alt="">
                    </div>
                    <div>
                        <h3 class="mb-2 title-text text-xl lg:text-2xl">Engagement</h3>
                        <p class="subtitle-text">Quiuckly navigate you anda engage with your adience</p>
                    </div>
                </div>
            </div>                
        </div>
    </section>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
    .support-partner-section {
        background: #F9F8FE;

        .primary-text {
            color: #191A15;
            font-family: Inter;
            // font-size: 50px;
            font-style: normal;
            font-weight: 600;
            line-height: normal;
        }

        .secondary-text {
            color: #A6A6A6;
            font-family: Inter;
            font-size: 16px;
            font-style: normal;
            font-weight: 500;
            line-height: 30px;
        }

        .rating {
            .rate {
                color: #191A15;
                font-family: Inter;
                font-size: 18px;
                font-style: normal;
                font-weight: 700;
                line-height: normal;
            }

            .partner-name {
                color: #A6A6A6;
                font-family: Inter;
                font-size: 18px;
                font-style: normal;
                font-weight: 700;
                line-height: normal;
            }
        }

        .features {
            .white-square {
                width: 60px;
                height: 60px;

                background: #FFF;
                box-shadow: 0px 4px 9px 0px rgba(0, 0, 0, 0.05);
            }
            .title-text {
                color: #191A15;
                font-family: Inter;
                // font-size: 28px;
                font-style: normal;
                font-weight: 700;
                line-height: normal;
            }

            .subtitle-text {
                color: #A6A6A6;
                font-family: Inter;
                font-size: 18px;
                font-style: normal;
                font-weight: 500;
                line-height: 30px;
            }
        }
    }
</style>