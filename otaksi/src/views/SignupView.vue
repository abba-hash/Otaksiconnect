<template>
    <div class="max-w-7xl mx-auto grid grid-cols-2 gap-4">
        <div class="main-left">
            <div class="p-12 bg-white border border-gray-200 rounded-lg">
                <h1 class="mb-6 text-2xl">
                    Sign up
                </h1>
                <p class="mb-6 text-gray-500">
                    Lorem ipsum, dolor sit amet consectetur adipisicing elit. Reiciendis, quidem possimus. 
                    Quisquam vero voluptatum veniam et eveniet eaque fuga quod nemo laborum accusamus illo, dignissimos delectus.
                </p>
                <p class="font-bold">
                    Already have an account <RouterLink :to="{'name': 'login'}" class="underline">Click here</RouterLink> to log in!
                </p>
            </div>
        </div>
        <div class="main-right">
            <div class="p-12 bg-white border border-gray-200 rounded-lg">
                <form class="space-y-6">
                    <div>
                        <label>Name</label><br>
                        <input type="name" placeholder="Your full name" class="w-full mt-2 px-6 py-4 border border-gray-200 rounded-lg">
                    </div>

                    <div>
                        <label>E-mail</label><br>
                        <input type="email" placeholder="Your email address" class="w-full mt-2 px-6 py-4 border border-gray-200 rounded-lg">
                    </div>

                    <div>
                        <label>Password</label><br>
                        <input type="password" placeholder="Your password" class="w-full mt-2 px-6 py-4 border border-gray-200 rounded-lg">
                    </div>

                    <div>
                        <label>Repeat Password</label><br>
                        <input type="password" placeholder="Repeat your password" class="w-full mt-2 px-6 py-4 border border-gray-200 rounded-lg">
                    </div>

                    <div>
                        <button class="px-6 py-4 bg-purple-600 text-white rounded-lg">Sign Up</button>
                    </div>
                </form>
            </div>
        </div>
    </div>
</template>