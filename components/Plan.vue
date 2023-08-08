<template>
    <div class="benefits-section">
        <div class="px-6 lg:px-8 py-8 lg:py-16 max-w-screen-xl mx-auto space-y-10">
            <div class="mx-auto space-y-10">
                <h1 class="primary-text text-3xl md:text-4xl lg:text-5xl leading-10 text-center">Choose Plan<br> That’s Right For You</h1>
                <div class="secondary-text text-center">
                    Choose plan that works best for you, feel free to contact us
                </div>
            </div>
            <div class="w-80 mx-auto">
                <form action="" class="plan-type p-2 bg-white">
                    <input type="radio" id="monthly" name="plan_type" value="monthly" checked/>
                    <label for="monthly" class="h-14 w-1/2 flex items-center justify-center">
                        <span>
                            Bil Monthly
                        </span>
                    </label>
                    <input type="radio" id="yearly" name="plan_type" value="yearly" checked />
                    <label for="yearly" class="h-14 w-1/2 flex items-center justify-center">
                        <span>
                            Bil Yearly
                        </span>
                    </label>
                </form>
            </div>
            <div class="cards grid lg:grid-cols-3 gap-7">
                <div class="item px-5 pb-5 pt-16">
                    <div class="title mb-4">
                        Free
                    </div>
                    <div class="description mb-4">
                        Have a go  and test your<br>  superpowers
                    </div>
                    <div class="price mb-4">
                        $0
                    </div>
                    <div class="list px-9 py-7 space-y-7">
                        <ul class="space-y-6">
                            <li class="flex items-center space-x-3">
                                <img src="/images/check.png" alt="" class="w-7">
                                <span>
                                    2 Users
                                </span>
                            </li>
                            <li class="flex items-center space-x-3">
                                <img src="/images/check.png" alt="" class="w-7">
                                <span>
                                    2 Files
                                </span>
                            </li>
                            <li class="flex items-center space-x-3">
                                <img src="/images/check.png" alt="" class="w-7">
                                <span>
                                    Public Share & Comments
                                </span>
                            </li>
                            <li class="flex items-center space-x-3">
                                <img src="/images/check.png" alt="" class="w-7">
                                <span>
                                    Chat Support 
                                </span>
                            </li>
                            <li class="flex items-center space-x-3">
                                <img src="/images/check.png" alt="" class="w-7">
                                <span>
                                    New income apps
                                </span>
                            </li>
                        </ul>

                        <div class="flex">
                            <a href="#" class="signup-btn w-full h-16 flex items-center justify-center">
                                Signup for free
                            </a>
                        </div>
                    </div>
                </div>
                <div class="item px-5 pb-5 pt-16 pro">
                    <div class="title mb-4">
                        Pro
                    </div>
                    <div class="description mb-4">
                        Experiment the power of infinite possibilities
                    </div>
                    <div class="price mb-4">
                        $8
                    </div>
                    <div class="mb-4 flex justify-center">
                        <span class="save-per-year px-3 py-2">
                            Save $50 a year
                        </span>
                    </div>
                    <div class="list px-9 py-7 space-y-7">
                        <ul class="space-y-6">
                            <li class="flex items-center space-x-3">
                                <img src="/images/check.png" alt="" class="w-7">
                                <span>
                                    4 Users
                                </span>
                            </li>
                            <li class="flex items-center space-x-3">
                                <img src="/images/check.png" alt="" class="w-7">
                                <span>
                                    All apps
                                </span>
                            </li>
                            <li class="flex items-center space-x-3">
                                <img src="/images/check.png" alt="" class="w-7">
                                <span>
                                    Unlimited editable exports
                                </span>
                            </li>
                            <li class="flex items-center space-x-3">
                                <img src="/images/check.png" alt="" class="w-7">
                                <span>
                                    Folders and collaboration 
                                </span>
                            </li>
                            <li class="flex items-center space-x-3">
                                <img src="/images/check.png" alt="" class="w-7">
                                <span>
                                    All incoming apps
                                </span>
                            </li>
                        </ul>

                        <div class="flex">
                            <a href="#" class="signup-btn w-full h-16 flex items-center justify-center">
                                Go to pro
                            </a>
                        </div>
                    </div>
                </div>
                <div class="item px-5 pb-5 pt-16">
                    <div class="title mb-4">
                        Business
                    </div>
                    <div class="description mb-4">
                        Unveil new superpowers and join the Design Leaque
                    </div>
                    <div class="price mb-4">
                        $16
                    </div>
                    <div class="list px-9 py-7 space-y-7">
                        <ul class="space-y-6">
                            <li class="flex items-center space-x-3">
                                <img src="/images/check.png" alt="" class="w-7">
                                <span>
                                    All the features of pro plan
                                </span>
                            </li>
                            <li class="flex items-center space-x-3">
                                <img src="/images/check.png" alt="" class="w-7">
                                <span>
                                    Account success Manager
                                </span>
                            </li>
                            <li class="flex items-center space-x-3">
                                <img src="/images/check.png" alt="" class="w-7">
                                <span>
                                    Single Sign-On (SSO)
                                </span>
                            </li>
                            <li class="flex items-center space-x-3">
                                <img src="/images/check.png" alt="" class="w-7">
                                <span>
                                    Co-conception pogram
                                </span>
                            </li>
                            <li class="flex items-center space-x-3">
                                <img src="/images/check.png" alt="" class="w-7">
                                <span>
                                    Collaboration-Soon
                                </span>
                            </li>
                        </ul>

                        <div class="flex">
                            <a href="#" class="signup-btn w-full h-16 flex items-center justify-center">
                                Go to Business
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>

    .benefits-section {

        .primary-text {
            color: #191A15;
            text-align: center;
            font-family: Inter;
            // font-size: 50px;
            font-style: normal;
            font-weight: 700;
            line-height: 73px; /* 146% */
        }

        .secondary-text {
            color: #A6A6A6;
            text-align: center;
            font-family: Inter;
            font-size: 18px;
            font-style: normal;
            font-weight: 700;
            line-height: normal;
        }

        .plan-type {
            display: flex;
            margin-bottom: 36px;
            overflow: hidden;
            border-radius: 10px;

            input {
                position: absolute !important;
                clip: rect(0, 0, 0, 0);
                height: 1px;
                width: 1px;
                border: 0;
                overflow: hidden;

                &:checked + label {
                    color: #FFFFFF;
                    background-color: #54BD95;
                    box-shadow: none;
                }
            }

            label {
                background-color: #FFFFFF;
                transition: all 0.1s ease-in-out;
                border-radius: 10px;
                color: #191A15;
                font-family: Inter;
                font-size: 18px;
                font-style: normal;
                font-weight: 500;
                line-height: 30px; /* 166.667% */
                
                &:hover {
                    cursor: pointer;
                    background-color: #ebfff7;
                }
            }
        }

        .cards {
            .item {
                background-color: #FFFFFF;
                border-radius: 20px;
                
                .title {
                    color: #191A15;
                    text-align: center;
                    font-family: Inter;
                    font-size: 30px;
                    font-style: normal;
                    font-weight: 600;
                    line-height: normal;
                }
                .description {
                    color: #A6A6A6;
                    text-align: center;
                    font-family: Inter;
                    font-size: 18px;
                    font-style: normal;
                    font-weight: 500;
                    line-height: 27px; /* 150% */
                }
                .price {
                    color: #191A15;
                    text-align: center;
                    font-family: Inter;
                    font-size: 50px;
                    font-style: normal;
                    font-weight: 600;
                    // line-height: 50px; /* 60% */
                }

                .list {
                    border-radius: 10px;
                    background: #F9FAFB;
                }

                .signup-btn {
                    color: #54BD95;
                    font-family: Inter;
                    font-size: 18px;
                    font-style: normal;
                    font-weight: 600;
                    line-height: 30px; /* 166.667% */

                    border-radius: 20px;
                    background: #FFF;
                    box-shadow: 0px 4px 9px 0px rgba(0, 0, 0, 0.05);
                }

                &.pro {
                    background: #54BD95;

                    .title {
                        color: #FFFFFF;
                    }

                    .description {
                        color: #FFFFFF;
                    }

                    .price {
                        color: #FFFFFF;
                    }

                    .save-per-year {
                        color: #FFF;
                        font-family: Inter;
                        font-size: 14px;
                        font-style: normal;
                        font-weight: 600;
                        line-height: 30px; /* 214.286% */
                        border-radius: 10px;
                        background: #85DAB9;
                    }

                    .list {
                        .signup-btn {
                            color: #FFFFFF;
                            background: #54BD95;
                        }
                    }
                }
            }
        }
    }
</style>