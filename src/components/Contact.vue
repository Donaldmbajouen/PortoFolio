<template>
<div class="bg-[#101838] text-white" id="contact">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 pt-16 text-center">
        <h2 class="text-5xl font-bold">Contact</h2>
        <p class="pt-6 pb-6 text-base max-w-2xl text-center m-auto dark:text-gray-400">
            Want to contact us? Choose an
            option below and well be happy to show you how we can transform companys web experience.
        </p>
    </div>
    <div
        class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 pt-8 pb-16 grid md:grid-cols-2 lg:grid-cols-2 gap-y-8 md:gap-x-8 md:gap-y-8 lg:gap-x-8 lg:gap-y-16">
        <div>
            <h2 class="text-2xl font-bold">Contact Us</h2>
            <p class="max-w-sm mt-4 mb-4 dark:text-gray-400">Have something to say? We are here to help. Fill up the
                form or send email or call phone.</p>
            <div class="max-w-md">
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi felis mi, faucibus dignissim lorem id, imperdiet interdum mauris. Vestibulum ultrices sed libero non porta. Vivamus malesuada urna eu nibh malesuada, non finibus massa laoreet. Nunc nisi velit, feugiat a semper quis, pulvinar id libero. Vivamus mi diam, consectetur non orci ut, tincidunt pretium justo. In vehicula porta molestie. Suspendisse potenti.
              </p>
            </div>
          </div>
        <div>
            <form>
                <input type="checkbox" id="" class="hidden" style="display:none" name="botcheck">
                <div class="mb-5">
                    <input type="text" placeholder="Entrer votre Nom" autocomplete="false"
                        class="w-full px-4 py-3 border-1 focus:border-red-500 outline-none rounded-md"
                        name="name">
                </div>
                <div class="mb-5">
                    <label for="email_address" class="sr-only">Adresse Email </label>
                    <input id="email_address" type="email" placeholder="Adresse Email " autocomplete="false"
                        class="w-full px-4 py-3 border-1 focus:border-red-500 outline-none rounded-md"
                        name="email">
                </div>
                <div class="mb-3">
                    <textarea placeholder="Your Message"
                        class="w-full px-4 border-2 focus:border-red-500 outline-none rounded-md py-10"
                        name="message">
                    </textarea>
                </div>
                <button type="submit"
                    class="w-full py-4 font-semibold text-white bg-red-500 rounded-md hover:bg-red-700 px-7">Envoyer un
                    Message
                </button>
            </form>
        </div>
    </div>
</div>
</template>
<script setup>

</script>
