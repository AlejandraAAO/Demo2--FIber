<template>
  <section class="font-inter lg:grid lg:grid-cols-2 lg:h-screen">
    <section class=" md:px-32">
      <section class="px-10 pt-8">
        <nav>
          <p class="text-lg font-bold">Fiber</p>
        </nav>
      </section>
      <section class="pt-10">
        <p class="px-10 text-3xl font-bold">Create your Fiber account</p>
      </section>
      <section class="px-10 pt-8">
        <form action="">
          <div class="flex flex-col pb-6">
            <label class="pb-1 font-semibold" for="">Your Name</label>
            <input
              class="border rounded-md px-3 py-2 focus:outline-none focus:ring focus:ring-purple-500"
              type="text"
              placeholder="John Doe"
            />
          </div>
          <div class="flex flex-col pb-6">
            <label class="pb-1 font-semibold" for="">E-mail</label>
            <input
              class="border rounded-md px-3 py-2 focus:outline-none focus:ring focus:ring-purple-500"
              type="text"
              placeholder="john@example.com"
            />
          </div>
          <div class="flex flex-col pb-6">
            <label class="pb-1 font-semibold" for="">Password</label>
            <input
              class="border rounded-md px-3 py-2 focus:outline-none focus:ring focus:ring-purple-500"
              type="password"
              placeholder="At least 8 characters"
            />
          </div>
          <div class="flex flex-row items-start">
            <input
              type="checkbox"
              class="appearance-none border border-gray-200 w-8 lg:w-6  h-5 rounded"
            />
            <label class="pl-2 text-sm" for=""
              >By creating an account on Fiber, you agreee to the
              <span class="text-purple-800 font-bold underline"
                >Terms & Conditions</span
              ></label
            >
          </div>
          <div class="py-4">
            <button
              class="rounded py-3 w-full font-semibold text-white bg-purple-800"
            >
              Create Fiber Account
            </button>
            <p class="py-2 text-center text-sm">
              Already have an account?
              <span class="text-purple-800">Sign in</span>
            </p>
          </div>
        </form>
      </section>
    </section>
    <section class="hidden lg:px-32 lg:bg-purple-800 lg:flex lg:flex-col lg:justify-center">
      <div>
        <picture class="">
          <img src="../assets/signup.png" alt="">
        </picture>
        <div class="pt-6 text-white text-center">
          <p class="text-3xl font-bold">Unparalleled Templates</p>
          <p>Crafted by a team of professional designers, our templates are unparalleled in the market.</p>
        </div>
      </div>
    </section>
  </section>
</template>
