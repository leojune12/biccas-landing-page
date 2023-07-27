<template>
    <section class="features-section relative">
        <div class="bg-circle z-40 hidden lg:block"></div>
        <div class="px-6 lg:px-8 py-8 lg:py-16 max-w-screen-xl mx-auto relative z-50">
            <div class="grid lg:grid-cols-3 gap-8 mb-20">
                <div class="primary-text text-3xl md:text-4xl lg:text-5xl leading-10 text-center lg:text-start">
                    Our Features you can get
                </div>
                <div class="secondary-text text-center lg:text-start flex items-center">
                    We offer a variety of interesting features that you can help increase yor productivity at work and manage your projrct esaly
                </div>
                <div class="flex justify-end items-center">
                    <a href="#" class="inline-flex items-center justify-center px-7 mr-0 lg:mr-3 rounded-full bg-primary-color focus:ring-4 focus:ring-primary-300 h-16 get-started-text mb-3 lg:mb-0 w-full lg:w-auto">
                        Get Started
                    </a>
                </div>
            </div>
            <div class="features-cards grid lg:grid-cols-3 gap-11 text-center lg:text-start">
                <div class="grid gap-4 lg:gap-7">
                    <div class="flex justify-center">
                        <img src="/images/Frame-247.png" alt="">
                    </div>
                    <div class="title">
                        Collboration Teams
                    </div>
                    <div class="subtitle">
                        Here you can handle projects together with team virtually
                    </div>
                </div>
                <div class="grid gap-4 lg:gap-7">
                    <div class="flex justify-center">
                        <img src="/images/Frame-53.png" alt="">
                    </div>
                    <div class="title">
                        Cloud Storage
                    </div>
                    <div class="subtitle">
                        No nedd to worry about storage because we provide storage up to 2 TB
                    </div>
                </div>
                <div class="grid gap-4 lg:gap-7">
                    <div class="flex justify-center">
                        <img src="/images/Frame-54.png" alt="">
                    </div>
                    <div class="title">
                        Daily Analytics
                    </div>
                    <div class="subtitle">
                        We always provide useful informatin to make it easier for you every day
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
<style lang="scss">
    .features-section {
        .bg-circle {
            position: absolute;
            bottom: 0px;
            left: -194px;

            width: 634px;
            height: 634px;

            border-radius: 634px;
            background: #FFD6D6;
            filter: blur(500px);
        }

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
            font-size: 18px;
            font-style: normal;
            font-weight: 500;
            line-height: 30px; 
        }

        .get-started-text {
            color: #FFF;
            font-family: Inter;
            font-size: 18px;
            font-style: normal;
            font-weight: 500;
            line-height: 30px; 
        }

        .features-cards {
            .title {
                color: #191A15;
                font-family: Inter;
                font-size: 30px;
                font-style: normal;
                font-weight: 600;
                line-height: 30px;
            }

            .subtitle {
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