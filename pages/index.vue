<template>
    <div>
        <h1>This is a index page.</h1>
        <div class="mt-5 flex gap-5 justify-center">
            <NuxtLink to="/about">
                <button
                    class="py-5 px-10 border border-blue-500 bg-blue-200 rounded-md flex items-center gap-5 hover:bg-blue-300">
                    <Icon name="line-md:account" style="color: black" size="20" />
                    Go to about page
                </button>
            </NuxtLink>
        </div>
    </div>
</template>