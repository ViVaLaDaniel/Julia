<template>
  <!-- component -->
  <div class="flex items-center justify-center p-12">
    <!-- Форма -->
    <div class="w-full md:w-1/2">
      <form action="https://formbold.com/s/FORM_ID" method="POST" class="w-full max-w-lg mx-auto">
        <div class="mb-5">
          <label for="name" class="mb-3 block text-base font-medium text-[#07074D]">Full Name</label>
          <input type="text" name="name" id="name" placeholder="Full Name" class="w-full rounded-md border border-[#e0e0e0] bg-white py-3 px-6 text-base font-medium text-[#6B7280] outline-none focus:border-[#6A64F1] focus:shadow-md" />
        </div>
        <div class="mb-5">
          <label for="email" class="mb-3 block text-base font-medium text-[#07074D]">Email Address</label>
          <input type="email" name="email" id="email" placeholder="example@domain.com" class="w-full rounded-md border border-[#e0e0e0] bg-white py-3 px-6 text-base font-medium text-[#6B7280] outline-none focus:border-[#6A64F1] focus:shadow-md" />
        </div>
        <div class="mb-5">
          <label for="subject" class="mb-3 block text-base font-medium text-[#07074D]">Subject</label>
          <input type="text" name="subject" id="subject" placeholder="Enter your subject" class="w-full rounded-md border border-[#e0e0e0] bg-white py-3 px-6 text-base font-medium text-[#6B7280] outline-none focus:border-[#6A64F1] focus:shadow-md" />
        </div>
        <div class="mb-5">
          <label for="message" class="mb-3 block text-base font-medium text-[#07074D]">Message</label>
          <textarea rows="4" name="message" id="message" placeholder="Type your message" class="w-full resize-none rounded-md border border-[#e0e0e0] bg-white py-3 px-6 text-base font-medium text-[#6B7280] outline-none focus:border-[#6A64F1] focus:shadow-md"></textarea>
        </div>
        <div>
          <button class="hover:shadow-form rounded-md bg-[#6A64F1] py-3 px-8 text-base font-semibold text-white outline-none">Submit</button>
        </div>
      </form>
    </div>
  
    <!-- Карта -->
    <div class="w-full md:w-1/2 ">
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d152.18765116972773!2d16.87767691473513!3d52.38850647214209!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x4704457f4e305ad3%3A0x51c21bbeb6586d08!2sKeit.HandMade!5e0!3m2!1sru!2spl!4v1707312356598!5m2!1sru!2spl" width="100%" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    </div>
  </div>
  </template>
  
  