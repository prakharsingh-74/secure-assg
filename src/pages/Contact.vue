<template>
  <div class="min-h-screen bg-white py-20 px-8 flex flex-col md:flex-row items-center justify-between">
    <div class="w-full md:w-1/2 flex justify-center mb-8 md:mb-0">
      <img src="/src/assets/Mask Group 1.svg" alt="Contact Illustration" class="w-80" />
    </div>
    <div class="w-full md:w-1/2 max-w-lg bg-white shadow-lg rounded-lg p-8">
      <h2 class="text-2xl font-bold mb-6">Send Us message</h2>
      <form class="space-y-4">
        <div>
          <label class="block text-gray-700">Your Email*</label>
          <input type="email" class="w-full border border-gray-300 rounded px-4 py-2" required />
        </div>
        <div>
          <label class="block text-gray-700">Your Name*</label>
          <input type="text" class="w-full border border-gray-300 rounded px-4 py-2" required />
        </div>
        <div>
          <label class="block text-gray-700">Phone Number*</label>
          <input type="tel" class="w-full border border-gray-300 rounded px-4 py-2" required />
        </div>
        <div>
          <label class="block text-gray-700">Subject</label>
          <input type="text" class="w-full border border-gray-300 rounded px-4 py-2" />
        </div>
        <div>
          <label class="block text-gray-700">Your Message</label>
          <textarea class="w-full border border-gray-300 rounded px-4 py-2" rows="3"></textarea>
        </div>
        <div class="flex items-center">
          <input type="checkbox" class="mr-2" required />
          <span class="text-gray-600 text-xs">By sending this message, you confirm that you have read and agreed to our privacy policy.</span>
        </div>
        <button type="submit" class="bg-blue-600 text-white px-6 py-3 rounded-full font-semibold w-full">Get Started &rarr;</button>
      </form>
    </div>
  </div>
</template>

<script setup>
</script>
