<template>
    <section class="bg-white hero-section relative">
        <div class="upper-left-circle z-40 hidden lg:block"></div>
        <div class="upper-right-circle z-40 hidden lg:block"></div>
        <div class="middle-circle z-40 hidden lg:block"></div>
        <div class="bottom-right-circle z-40 hidden lg:block"></div>
        <div class="relative grid px-6 lg:px-8 py-8 mx-auto gap-8 lg:gap-0 lg:py-16 lg:grid-cols-2 max-w-screen-xl z-50">
            <div class="mr-auto place-self-center order-2 lg:order-1">
                <h1 class="lg:max-w-2xl mb-7 text-4xl md:text-5xl xl:text-7xl primary-text leading-10 text-center lg:text-start">We’re here to Increase your Productivity</h1>
                <div class="w-full lg:max-w-lg hidden lg:block">
                    <svg height="34" viewBox="0 0 487 34" fill="none" xmlns="http://www.w3.org/2000/svg" class="mb-12 w-full">
                        <path d="M4 30C73.6307 10.3798 266.914 -17.0885 483 30" stroke="#54BD95" stroke-width="8" stroke-linecap="round"/>
                    </svg>
                </div>
                <p class="lg:max-w-lg mb-6 lg:mb-8 secondary-text text-center lg:text-start">Let's make your work more organize and easily using the Taskio Dashboard with many of the latest featuresin managing work every day.</p>
                <div class="flex justify-center lg:justify-start flex-col lg:flex-row">
                    <a href="#" class="inline-flex items-center justify-center px-7 mr-0 lg:mr-3 rounded-full bg-primary-color focus:ring-4 focus:ring-primary-300 h-14 free-trial-text mb-3 lg:mb-0">
                        Try free trial
                    </a>
                    <a href="#" class="inline-flex items-center justify-center px-7 text-gray-900 rounded-full hover:bg-gray-100 focus:ring-4 focus:ring-primary-300 h-14 view-demo-text">
                        <svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg" class="mr-3">
                            <path fill-rule="evenodd" clip-rule="evenodd" d="M20 4.16675C28.7432 4.16675 35.8333 11.2553 35.8333 20.0001C35.8333 28.7448 28.7432 35.8334 20 35.8334C11.2552 35.8334 4.16666 28.7448 4.16666 20.0001C4.16666 11.2553 11.2552 4.16675 20 4.16675Z" stroke="#191A15" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                            <path fill-rule="evenodd" clip-rule="evenodd" d="M25 19.9919C25 18.64 18.0709 14.3152 17.2848 15.0928C16.4988 15.8705 16.4232 24.0401 17.2848 24.891C18.1464 25.7449 25 21.3438 25 19.9919Z" stroke="#191A15" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg>
                        View Demo
                    </a> 
                </div>
            </div>
            <div class="lg:mt-0 order-1 lg:order-2 mx-auto">
                <img src="/images/Group-138.png" alt="mockup">
            </div>                
        </div>
    </section>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
    .hero-section {

        .primary-text {
            color: #191A15;
            font-family: Inter;
            font-style: normal;
            font-weight: 700;
        }

        .secondary-text {
            color: #000;
            font-size: 18px;
            font-family: Inter;
            font-style: normal;
            font-weight: 500;
            line-height: 30px;
        }

        .free-trial-text {
            color: #FFF;
            font-size: 18px;
            font-family: Inter;
            font-style: normal;
            font-weight: 500;
            line-height: normal;        
        }

        .view-demo-text {
            color: #191A15;
            font-size: 18px;
            font-family: Inter;
            font-style: normal;
            font-weight: 500;
            line-height: normal;        
        }

        .upper-left-circle {
            position: absolute;
            top: -437px;
            left: -317px;

            width: 634px;
            height: 634px;

            border-radius: 634px;
            background: #52BDAA;
            filter: blur(500px);
        }

        .upper-right-circle {
            position: absolute;
            top: -437px;
            right: 225px;

            width: 634px;
            height: 634px;

            border-radius: 634px;
            background: #FFD6D6;
            filter: blur(500px);
        }

        .middle-circle {
            position: absolute;
            top: calc(50% - 317px);
            left: calc(50% - 317px);

            width: 634px;
            height: 634px;

            border-radius: 634px;
            background: #FFF;
            filter: blur(500px);
        }

        .bottom-right-circle {
            position: absolute;
            top: 270px;
            right: -317px;

            width: 634px;
            height: 634px;

            border-radius: 634px;
            background: #54BE96;
            filter: blur(500px);
        }
        }
</style>