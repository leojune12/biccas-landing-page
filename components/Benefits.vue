<template>
    <div class="benefits-section">
        <div class="px-6 lg:px-8 py-8 lg:py-16 max-w-screen-xl mx-auto grid gap-8 lg:gap-0 lg:grid-cols-12">
            <div class="mr-auto place-self-start col-span-12 lg:col-span-6 order-2 lg:order-1 space-y-8 lg:space-y-12">
                <h1 class="primary-text text-3xl md:text-4xl lg:text-5xl leading-10 text-center md:text-start lg:max-w-md">What Benifit Will You Get</h1>
                <ul class="space-y-8 benefits-items">
                    <li class="flex items-center space-x-5">
                        <img src="/images/check.png" alt="">
                        <span>
                            Free Consulting With Experet Saving Money
                        </span>
                    </li>
                    <li class="flex items-center space-x-5">
                        <img src="/images/check.png" alt="">
                        <span>
                            Online Banking
                        </span>
                    </li>
                    <li class="flex items-center space-x-5">
                        <img src="/images/check.png" alt="">
                        <span>
                            Investment Report Every Month
                        </span>
                    </li>
                    <li class="flex items-center space-x-5">
                        <img src="/images/check.png" alt="">
                        <span>
                            Saving Money For The Future
                        </span>
                    </li>
                    <li class="flex items-center space-x-5">
                        <img src="/images/check.png" alt="">
                        <span>
                            Online Transection
                        </span>
                    </li>
                </ul>
            </div>
            <div class="lg:mt-0 col-span-12 lg:col-span-6 order-1 lg:order-2 flex justify-center">
                <img src="/images/Rectangle-48.png" alt="mockup">
            </div>                
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="scss">
    .benefits-section {
        .primary-text {
            color: #191A15;
            font-family: Inter;
            font-style: normal;
            font-weight: 700;
            line-height: normal;
        }

        ul {
           li {
                color: #191A15;
                font-family: Inter;
                font-size: 18px;
                font-style: normal;
                font-weight: 500;
                line-height: 30px; 
           } 
        }
    }
</style>