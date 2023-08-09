<template>
    <div class="footer-section">
        <div class="px-6 lg:px-8 py-8 lg:py-14 max-w-screen-xl mx-auto grid lg:grid-cols-2 gap-y-10">
            <div class="lg:max-w-md">
                <div class="logo mb-7 text-center lg:text-start">
                    Biccas
                </div>
                <div class="text-below-logo mb-7 text-center lg:text-start">
                    Get started noew try our product
                </div>
                <form action="">
                    <div class="input-group-container">
                        <input type="text" name="email" id="email" class="appearance-none bg-transparent border-none w-full focus:outline-none py-4 pl-6 pr-20" placeholder="Enter your email here">
                        <button type="submit" class="flex items-center justify-center">
                            <img src="/images/arrow-right.png" alt="">
                        </button>
                    </div>
                </form>
            </div>
            <div class="links flex justify-between flex-col sm:flex-row gap-y-10">
                <div class="space-y-7">
                    <div class="title text-base md:text-lg">
                        Support
                    </div>
                    <ul class="space-y-5 md:space-y-7">
                        <li>
                            <a href="#" class="text-base md:text-lg">
                                Help centre
                            </a>
                        </li>
                        <li>
                            <a href="#" class="text-base md:text-lg">
                                Account information
                            </a>
                        </li>
                        <li>
                            <a href="#" class="text-base md:text-lg">
                                About
                            </a>
                        </li>
                        <li>
                            <a href="#" class="text-base md:text-lg">
                                Contact us
                            </a>
                        </li>
                    </ul>
                </div>
                <div class="space-y-7">
                    <div class="title">
                        Help and Solution
                    </div>
                    <ul class="space-y-5 md:space-y-7">
                        <li>
                            <a href="#" class="text-base md:text-lg">
                                Talk to support
                            </a>
                        </li>
                        <li>
                            <a href="#" class="text-base md:text-lg">
                                Support docs
                            </a>
                        </li>
                        <li>
                            <a href="#" class="text-base md:text-lg">
                                System status
                            </a>
                        </li>
                        <li>
                            <a href="#" class="text-base md:text-lg">
                                Covid respond
                            </a>
                        </li>
                    </ul>
                </div>
                <div class="space-y-7">
                    <div class="title">
                        Product
                    </div>
                    <ul class="space-y-5 md:space-y-7">
                        <li>
                            <a href="#" class="text-base md:text-lg">
                                Update
                            </a>
                        </li>
                        <li>
                            <a href="#" class="text-base md:text-lg">
                                Security
                            </a>
                        </li>
                        <li>
                            <a href="#" class="text-base md:text-lg">
                                Beta test
                            </a>
                        </li>
                        <li>
                            <a href="#" class="text-base md:text-lg">
                                Pricing product
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="px-6 lg:px-8 py-8 lg:pt-14 lg:pb-20 max-w-screen-xl mx-auto copyright-section flex items-center lg:justify-between flex-col lg:flex-row gap-y-4">
            <div class="text-center">
                © 2022 Biccas Inc. Copyright and rights reserved
            </div>
            <div>
                <a href="#" class="hover:underline">
                    Terms and Condtions
                </a>
                &nbsp;
                &bullet;
                &nbsp;
                <a href="#" class="hover:underline">
                    Privacy Policy
                </a>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="scss">
    .footer-section {

        background: #161C28;

        .logo {
            color: #54BD95;
            font-family: Inter;
            font-size: 50px;
            font-style: normal;
            font-weight: 600;
            line-height: 30px; /* 60% */
        }

        .text-below-logo {
            color: #A6A6A6;
            font-family: Inter;
            font-size: 18px;
            font-style: normal;
            font-weight: 500;
            line-height: 30px; /* 166.667% */
        }

        form {

            .input-group-container {
                position: relative;
                border-radius: 70px;
                border: 2px solid #A6A6A6;

                input {
                    color: #FFFFFF
                }

                button[type="submit"] {
                    width: 44px;
                    height: 44px;
                    position: absolute;
                    right: 6px;
                    top: 6px;
                    background-color: #54BD95;
                    border-radius: 100%;
                }
            }
        }

        .links {
            .title {
                color: #FFF;
                font-family: Inter;
                // font-size: 18px;
                font-style: normal;
                font-weight: 500;
                line-height: normal;
            }

            ul {
                li {
                    color: #A6A6A6;
                    font-family: Inter;
                    font-size: 18px;
                    font-style: normal;
                    font-weight: 500;
                    line-height: normal;
                }
            }
        }

        .copyright-section {
            color: #FFF;
            font-family: Inter;
            // font-size: 18px;
            font-style: normal;
            font-weight: 500;
            line-height: 30px; /* 166.667% */
        }
    }
</style>