<template>
    <div class="bg-white header-navigation">
        <header class="max-w-screen-xl mx-auto z-50">
            <nav class="flex items-center justify-between p-6 lg:px-8 lg:py-10" aria-label="Global">
                <div class="flex lg:flex-1">
                <a href="#" class="-m-1.5 p-1.5 company-logo">
                    <!-- <span class="sr-only">Your Company</span> -->
                    <!-- <img class="h-8 w-auto" src="https://tailwindui.com/img/logos/mark.svg?color=indigo&shade=600" alt="" /> -->
                    Biccas
                </a>
                </div>
                <div class="flex lg:hidden">
                <button type="button" class="-m-2.5 inline-flex items-center justify-center rounded-md p-2.5 text-gray-700" @click="mobileMenuOpen = true">
                    <span class="sr-only">Open main menu</span>
                    <Bars3Icon class="h-6 w-6" aria-hidden="true" />
                </button>
                </div>
                <div class="hidden lg:flex lg:gap-x-12">
                <a v-for="item in navigation" :key="item.name" :href="item.href" class="leading-6 header-navigation-link" :class="{ active: item.isActive }">{{ item.name }}</a>
                </div>
                <div class="hidden lg:flex lg:flex-1 lg:justify-end">
                    <a href="#" class="login-btn flex items-center justify-center">Log in</a>
                    <a href="#" class="sign-up-btn flex items-center justify-center">Sign Up</a>
                </div>
            </nav>
            <Dialog as="div" class="lg:hidden" @close="mobileMenuOpen = false" :open="mobileMenuOpen">
                <div class="fixed inset-0 z-50" />
                <DialogPanel class="fixed inset-y-0 right-0 z-50 w-full overflow-y-auto bg-white px-6 py-6 sm:max-w-sm sm:ring-1 sm:ring-gray-900/10">
                <div class="flex items-center justify-between">
                    <a href="#" class="-m-1.5 p-1.5">
                    <span class="sr-only">Your Company</span>
                    <img class="h-8 w-auto" src="https://tailwindui.com/img/logos/mark.svg?color=indigo&shade=600" alt="" />
                    </a>
                    <button type="button" class="-m-2.5 rounded-md p-2.5 text-gray-700" @click="mobileMenuOpen = false">
                    <span class="sr-only">Close menu</span>
                    <XMarkIcon class="h-6 w-6" aria-hidden="true" />
                    </button>
                </div>
                <div class="mt-6 flow-root">
                    <div class="-my-6 divide-y divide-gray-500/10">
                        <div class="space-y-2 py-6">
                            <a v-for="item in navigation" :key="item.name" :href="item.href" class="-mx-3 block rounded-lg px-3 py-2 header-navigation-link" :class="{ active: item.isActive }">{{ item.name }}</a>
                        </div>
                        <div class="py-6">
                            <a href="#" class="-mx-3 block rounded-lg px-3 py-2.5 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50">Log in</a>
                        </div>
                    </div>
                </div>
                </DialogPanel>
            </Dialog>
        </header>
    </div>
</template>

<script setup>
import { ref } from 'vue'
import { Dialog, DialogPanel } from '@headlessui/vue'
import { Bars3Icon, XMarkIcon } from '@heroicons/vue/24/outline'

const navigation = [
  { name: 'Home', href: '#', isActive: true },
  { name: 'Product', href: '#', isActive: false },
  { name: 'FAQ', href: '#', isActive: false },
  { name: 'Blog', href: '#', isActive: false },
  { name: 'About Us', href: '#', isActive: false },
]

const mobileMenuOpen = ref(false)
</script>