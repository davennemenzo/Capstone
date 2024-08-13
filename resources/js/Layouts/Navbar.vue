<script setup lang="ts">
import { Link } from "@inertiajs/vue3";
</script>

<sciprt setup>
</sciprt>

<template>
    <nav class="bg-white border-b border-gray-200 shadow-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16">
                <div class="flex-shrink-0 flex items-center">
                    <a href="#" class="text-4xl font-semibold">Tudlo</a>
                </div>
                <div class="hidden md:flex md:space-x-8 md:items-center">
                    <Link
                        :href="route('about')"
                        class="text-black hover:text-gray-600 font-bold"
                        >About</Link
                    >
                    <Link
                        :href="route('services')"
                        class="text-black hover:text-gray-600 font-bold"
                        >Services</Link
                    >

                    <a href="#" class="text-black hover:text-gray-600 font-bold"
                        >Become a Tutor</a
                    >
                </div>

                <div class="hidden md:flex md:space-x-3 md:items-center">
                    <a href="#" class="text-black hover:text-gray-600 font-bold"
                        >Sign up</a
                    >

                    <Link
                        :href="route('login')"
                        class="inline-flex items-center px-4 py-2 bg-blue-500 text-white font-semibold rounded-lg hover:bg-blue-600 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-offset-2"
                    >
                        Login
                    </Link>
                </div>
            </div>
        </div>
    </nav>
</template>
