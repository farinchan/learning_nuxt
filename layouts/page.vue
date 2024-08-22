<template>
    <div class="bg-gray-50 text-gray-800 dark:bg-gray-950 dark:text-gray-100 min-h-screen">
        <PageNavigation />
        <slot />
        <footer>
            <div class="bg-gray-500/50 text-white p-4 text-center">
                &copy; 2021 My App
            </div>
        </footer>
    </div>
</template>