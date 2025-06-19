---
title: Contact
date: 2021-12-18T03:10:36.000Z
draft: false
language: en
description: A test with @tailwindcss/typography & Prose
---

<!-- @format -->

<section class="lg:pb-24">
  <div class="max-w-screen-md px-4 mx-auto">
     <form name="pendaftaran" action="https://formsubmit.co/your@email.com" method="POST" class="space-y-8">
    <div class="my-4">
        <label for="nama" class="block mb-2 font-medium text-gray-900 text-md dark:text-gray-300"><strong>Nama Lengkap Siswa:</strong></label>
        <input type="text" name="nama" class="shadow-sm bg-gray-50 border border-gray-300 text-gray-900 text-md rounded-lg focus:ring-indigo-500 focus:border-indigo-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-indigo-500 dark:focus:border-indigo-500 dark:shadow-sm-light" placeholder="Nama lengkap siswa" required>
    </div>
    <div class="my-4">
        <label for="email_ortu" class="block mb-2 font-medium text-gray-900 text-md dark:text-gray-300"><strong>Email Orang Tua:</strong></label>
        <input type="email" name="email_ortu" class="shadow-sm bg-gray-50 border border-gray-300 text-gray-900 text-md rounded-lg focus:ring-indigo-500 focus:border-indigo-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-indigo-500 dark:focus:border-indigo-500 dark:shadow-sm-light" placeholder="email@contoh.com" required>
    </div>
    <div class="my-4">
        <label for="telepon" class="block mb-2 font-medium text-gray-900 text-md dark:text-gray-300"><strong>No. HP/WA:</strong></label>
        <input type="tel" name="telepon" class="block w-full p-3 text-gray-900 border border-gray-300 rounded-lg shadow-sm text-md bg-gray-50 focus:ring-indigo-500 focus:border-indigo-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-indigo-500 dark:focus:border-indigo-500 dark:shadow-sm-light" placeholder="08xxxxxxxxxx" required>
    </div>
    <div class="my-4">
        <label for="asal_sekolah" class="block mb-2 font-medium text-gray-900 text-md dark:text-gray-300"><strong>Asal Sekolah:</strong></label>
        <input type="text" name="asal_sekolah" class="block w-full p-3 text-gray-900 border border-gray-300 rounded-lg shadow-sm text-md bg-gray-50 focus:ring-indigo-500 focus:border-indigo-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-indigo-500 dark:focus:border-indigo-500 dark:shadow-sm-light" placeholder="Contoh: SDIT Al-Falah" required>
    </div>
    <div class="my-4 sm:col-span-2">
        <label for="catatan" class="block mb-2 font-medium text-gray-900 text-md dark:text-gray-400"><strong>Catatan Tambahan:</strong></label>
        <textarea id="catatan" name="catatan" rows="6" class="block p-2.5 w-full text-md text-gray-900 bg-gray-50 rounded-lg shadow-sm border border-gray-300 focus:ring-indigo-500 focus:border-indigo-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-indigo-500 dark:focus:border-indigo-500" placeholder="Contoh: Anak saya alergi makanan tertentu..."></textarea>
    </div>
    <div class="mt-6 lg:pb-16">
        <button type="submit" class="px-5 py-3 font-bold text-center text-white bg-indigo-600 rounded-lg text-md sm:w-fit hover:bg-indigo-800 focus:ring-4 focus:outline-none focus:ring-indigo-300 dark:bg-indigo-600 dark:hover:bg-indigo-700 dark:focus:ring-indigo-800">Kirim Pendaftaran</button>
    </div>
</form>

      </form>
  </div>
</section>
