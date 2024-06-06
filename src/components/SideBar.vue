<template>
    <div class="w-1/4 bg-white p-4 shadow-lg">
        <div class="mb-4">
            <h2 class="text-xl font-bold mb-2">Menu</h2>
            <input type="text" placeholder="Search" class="w-full px-4 py-2 border rounded-md">
        </div>
        <div class="mb-4">
            <h3 class="text-lg font-semibold mb-2">Tasks</h3>
            <ul>
            <li class="mb-2"><a href="#" class="flex justify-between px-4 py-2 bg-gray-200 rounded-md">Upcoming <span>12</span></a></li>
            <li class="mb-2"><a href="#" class="flex justify-between px-4 py-2 rounded-md">Today <span>5</span></a></li>
            <li class="mb-2"><a href="#" class="flex justify-between px-4 py-2 rounded-md">Calendar</a></li>
            <li class="mb-2"><a href="#" class="flex justify-between px-4 py-2 rounded-md">Sticky Wall</a></li>
            </ul>
        </div>
        <div class="mb-4">
            <h3 class="text-lg font-semibold mb-2">Lists</h3>
            <ul>
            <li class="mb-2"><a href="#" class="flex justify-between px-4 py-2 bg-red-200 rounded-md">Personal <span>3</span></a></li>
            <li class="mb-2"><a href="#" class="flex justify-between px-4 py-2 bg-blue-200 rounded-md">Work <span>6</span></a></li>
            <li class="mb-2"><a href="#" class="flex justify-between px-4 py-2 bg-yellow-200 rounded-md">List 1 <span>3</span></a></li>
            <li class="mb-2"><a href="#" class="flex justify-between px-4 py-2 rounded-md">Add New List</a></li>
            </ul>
        </div>
        <div class="mb-4">
            <h3 class="text-lg font-semibold mb-2">Tags</h3>
            <div class="flex flex-wrap gap-2">
            <span class="px-2 py-1 bg-green-200 rounded-md">Tag 1</span>
            <span class="px-2 py-1 bg-pink-200 rounded-md">Tag 2</span>
            <button class="px-2 py-1 bg-gray-200 rounded-md">+ Add Tag</button>
            </div>
        </div>
        <div class="mt-auto">
            <button class="w-full px-4 py-2 mb-2 bg-gray-200 rounded-md">Settings</button>
            <button class="w-full px-4 py-2 bg-gray-200 rounded-md">Sign out</button>
        </div>
    </div>
</template>

<script>
</script>

<style scoped>
/* Your component styles go here */
</style>