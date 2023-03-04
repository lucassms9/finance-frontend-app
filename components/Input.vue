<template>
    <div>
        <label for="first_name" class="block mb-2 text-sm font-medium">Search</label>
        <div class="relative">
            <div class="absolute inset-y-0 left-0 flex items-center pl-3 pointer-events-none">
                <svg aria-hidden="true" class="w-5 h-5 text-gray-500 dark:text-gray-400" fill="none" stroke="currentColor"
                    viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                        d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path>
                </svg>
            </div>
            <input type="text" id="first_name"
                class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-sm w-full p-2.5 pl-10"
                placeholder="Search by bank, account, reference, category, date, amount, currency...">
        </div>

    </div>
</template>