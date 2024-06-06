<script setup>
import SideBar from '@/components/SideBar.vue'
</script>

<template>
    <html>
        <body class="bg-gray-100 font-sans">
            <div class="flex h-screen">
                <!-- Sidebar -->
                 <SideBar />

                <!-- Main Content -->
                <div class="w-full p-8">
                    <div class="mb-8">
                        <h1 class="text-3xl font-bold">Upcoming</h1>
                        <span class="text-2xl bg-gray-200 rounded-md px-2">12</span>
                    </div>
                    <div class="grid grid-cols-3 gap-8">
                        <!-- Today -->
                        <div>
                        <h2 class="text-xl font-semibold mb-4">Today</h2>
                        <button class="w-full mb-4 px-4 py-2 border rounded-md">+ Add New Task</button>
                        <ul class="space-y-2">
                            <li class="flex justify-between p-4 bg-white shadow-sm rounded-md">
                            <span>Research content ideas</span>
                            <input type="checkbox">
                            </li>
                            <li class="flex justify-between p-4 bg-white shadow-sm rounded-md">
                            <span>Create a database of guest authors</span>
                            <input type="checkbox">
                            </li>
                            <li class="flex justify-between p-4 bg-white shadow-sm rounded-md">
                            <div>
                                <span>Renew driver's license</span>
                                <div class="text-sm text-gray-500">22-03-22 | Subtasks: 1 | Personal</div>
                            </div>
                            <input type="checkbox">
                            </li>
                            <li class="flex justify-between p-4 bg-white shadow-sm rounded-md">
                            <span>Consult accountant</span>
                            <input type="checkbox">
                            </li>
                        </ul>
                        </div>

                        <!-- Tomorrow -->
                        <div>
                        <h2 class="text-xl font-semibold mb-4">Tomorrow</h2>
                        <button class="w-full mb-4 px-4 py-2 border rounded-md">+ Add New Task</button>
                        <ul class="space-y-2">
                            <li class="flex justify-between p-4 bg-white shadow-sm rounded-md">
                            <span>Create job posting for SEO specialist</span>
                            <input type="checkbox">
                            </li>
                            <li class="flex justify-between p-4 bg-white shadow-sm rounded-md">
                            <span>Request design assets for landing page</span>
                            <input type="checkbox">
                            </li>
                        </ul>
                        </div>

                        <!-- This Week -->
                        <div>
                        <h2 class="text-xl font-semibold mb-4">This Week</h2>
                        <button class="w-full mb-4 px-4 py-2 border rounded-md">+ Add New Task</button>
                        <ul class="space-y-2">
                            <li class="flex justify-between p-4 bg-white shadow-sm rounded-md">
                            <span>Research content ideas</span>
                            <input type="checkbox">
                            </li>
                            <li class="flex justify-between p-4 bg-white shadow-sm rounded-md">
                            <span>Create a database of guest authors</span>
                            <input type="checkbox">
                            </li>
                            <li class="flex justify-between p-4 bg-white shadow-sm rounded-md">
                            <span>Renew driver's license</span>
                            <input type="checkbox">
                            </li>
                            <li class="flex justify-between p-4 bg-white shadow-sm rounded-md">
                            <span>Consult accountant</span>
                            <input type="checkbox">
                            </li>
                            <li class="flex justify-between p-4 bg-white shadow-sm rounded-md">
                            <span>Print business card</span>
                            <input type="checkbox">
                            </li>
                        </ul>
                        </div>
                    </div>
                </div>
            </div>
        </body>
    </html>
</template>

<style scoped>
</style>