<template>
    <div class="contact-us-section">
        <div class="px-6 lg:px-8 py-8 lg:py-32 max-w-screen-xl mx-auto grid gap-8 lg:gap-0 lg:grid-cols-2">
            <div class="pr-0 lg:pr-24">
                <div class="mx-auto space-y-5 mb-10">
                    <h1 class="primary-text text-3xl md:text-4xl lg:text-5xl leading-10 text-center lg:text-start">People are Saying About DoWhith</h1>
                    <div class="secondary-text text-center lg:text-start">
                        Everything you need to accept to payment and grow your money of manage anywhere on planet
                    </div>
                </div>
                <div class="mb-10 flex justify-center lg:justify-start">
                    <img src="/images/Group-212.png" alt="">
                </div>
                <div class="quote mb-10 text-center lg:text-start">
                    <div class="mb-10">
                        I am very helped by this E-wallet application , my days are very easy to use this application and its very helpful in my life , even I can pay a short time 😍
                    </div>
                    <div>
                        _ Aria Zinanrio
                    </div>
                </div>
                <div class="flex justify-around lg:justify-start lg:gap-5">
                    <a href="#" class="w-9 h-9 sm:w-16 sm:h-16">
                        <img src="/images/contact-1.png" alt="">
                    </a>
                    <a href="#" class="w-9 h-9 sm:w-16 sm:h-16">
                        <img src="/images/contact-2.png" alt="">
                    </a>
                    <a href="#" class="w-9 h-9 sm:w-16 sm:h-16">
                        <img src="/images/contact-3.png" alt="">
                    </a>
                    <a href="#" class="w-9 h-9 sm:w-16 sm:h-16">
                        <img src="/images/contact-4.png" alt="">
                    </a>
                    <a href="#" class="w-9 h-9 sm:w-16 sm:h-16">
                        <img src="/images/play-white.png" alt="">
                    </a>
                </div>
            </div>
            <div class="contact-form pt-10 px-6 lg:px-20 pb-8 lg:pb-16">
                <div class="flex justify-center mb-3">
                    <img src="/images/Group.png" alt="">
                </div>
                <div class="title text-center mb-3 ">
                    Get Started
                </div>
                <form action="">
                    <div class="mb-4">
                        <label class="block mb-5 font-family-inter text-white" for="email">
                            Email
                        </label>
                        <input class="shadow appearance-none border rounded w-full py-4 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="email" type="text" placeholder="Enter your email">
                    </div>
                    <div class="mb-4">
                        <label class="block mb-5 font-family-inter text-white" for="message">
                            Message
                        </label>
                        <textarea class="shadow appearance-none border rounded w-full py-4 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="message" type="text" placeholder="What are you say?"></textarea>
                    </div>
                    <div class="mb-3">
                        <button type="submit" class="w-full py-5">
                            Request Demo
                        </button>
                    </div>
                    <div class="free-trial-link text-white text-end">
                        or <a href="#" class="text-white hover:underline">Start Free Trial</a>
                    </div>
                </form>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="scss">
    .contact-us-section {
        background: #161C28;

        .primary-text {
            color: #FFF;
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
            line-height: 30px; /* 166.667% */
        }

        .quote {
            color: #A6A6A6;
            font-family: Inter;
            font-size: 18px;
            font-style: normal;
            font-weight: 500;
            line-height: 30px; /* 166.667% */
        }

        .contact-form {
            border-radius: 20px;
            background: #222938;

            .title {
                color: #FFF;
                font-family: Inter;
                font-size: 30px;
                font-style: normal;
                font-weight: 500;
                line-height: normal;
            }

            button[type="submit"] {
                color: #FFF;
                font-family: Inter;
                font-size: 16px;
                font-style: normal;
                font-weight: 600;
                line-height: normal;
                border-radius: 10px;
                background: #54BD95;
            }

            .free-trial-link {
                color: #A6A6A6;
                font-family: Inter;
                font-size: 14px;
                font-style: normal;
                font-weight: 500;
                line-height: normal;
            }
        }
    }
</style>