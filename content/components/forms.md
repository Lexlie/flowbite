---
layout: home
title: Tailwind CSS Form Elements - Flowbite
description: Use the Tailwind CSS form and input elements such as checkboxes, radios, textarea, file uploads, and text inputs to collect information from users
group: components
toc: true

previous: Dropdowns
previousLink: components/dropdowns
next: List group
nextLink: components/list-group
---

<div class="lg:grid lg:grid-cols-2 lg:gap-4 my-10">
    <a href="{{< ref "forms/input-groups" >}}" class="p-6 block bg-white hover:bg-gray-100 shadow-md border border-gray-200 rounded-lg mb-6 lg:mb-0">
        <h3 class="text-gray-900 font-bold text-2xl tracking-tight mb-2">Input groups</h3>
        <p class="font-normal text-gray-700">Learn how to get started by downloading and configuring Flowbite locally on your machine and start developing.</p>
    </a>
    <a href="{{< ref "forms/select-menus" >}}" class="p-6 block bg-white hover:bg-gray-100 shadow-md border border-gray-200 rounded-lg mb-6 lg:mb-0">
        <h3 class="text-gray-900 font-bold text-2xl tracking-tight mb-2">Select menus</h3>
        <p class="font-normal text-gray-700">Learn how to get started by downloading and configuring Flowbite locally on your machine and start developing.</p>
    </a>
    <a href="{{< ref "forms/textarea" >}}" class="p-6 block bg-white hover:bg-gray-100 shadow-md border border-gray-200 rounded-lg mb-6 lg:mb-0">
        <h3 class="text-gray-900 font-bold text-2xl tracking-tight mb-2">Textarea</h3>
        <p class="font-normal text-gray-700">Learn how to get started by downloading and configuring Flowbite locally on your machine and start developing.</p>
    </a>
    <a href="{{< ref "forms/checkboxes" >}}" class="p-6 block bg-white hover:bg-gray-100 shadow-md border border-gray-200 rounded-lg mb-6 lg:mb-0">
        <h3 class="text-gray-900 font-bold text-2xl tracking-tight mb-2">Checkboxes</h3>
        <p class="font-normal text-gray-700">Learn how to get started by downloading and configuring Flowbite locally on your machine and start developing.</p>
    </a>
    <a href="{{< ref "forms/radio-groups" >}}" class="p-6 block bg-white hover:bg-gray-100 shadow-md border border-gray-200 rounded-lg mb-6 lg:mb-0">
        <h3 class="text-gray-900 font-bold text-2xl tracking-tight mb-2">Radio groups</h3>
        <p class="font-normal text-gray-700">Learn how to get started by downloading and configuring Flowbite locally on your machine and start developing.</p>
    </a>
    <a href="{{< ref "forms/range-slider" >}}" class="p-6 block bg-white hover:bg-gray-100 shadow-md border border-gray-200 rounded-lg mb-6 lg:mb-0">
        <h3 class="text-gray-900 font-bold text-2xl tracking-tight mb-2">Range slider</h3>
        <p class="font-normal text-gray-700">Learn how to get started by downloading and configuring Flowbite locally on your machine and start developing.</p>
    </a>
    <a href="{{< ref "forms/floating-labels" >}}" class="p-6 block bg-white hover:bg-gray-100 shadow-md border border-gray-200 rounded-lg mb-6 lg:mb-0">
        <h3 class="text-gray-900 font-bold text-2xl tracking-tight mb-2">Floating labels</h3>
        <p class="font-normal text-gray-700">Learn how to get started by downloading and configuring Flowbite locally on your machine and start developing.</p>
    </a>
    <a href="{{< ref "forms/file-upload" >}}" class="p-6 block bg-white hover:bg-gray-100 shadow-md border border-gray-200 rounded-lg mb-6 lg:mb-0">
        <h3 class="text-gray-900 font-bold text-2xl tracking-tight mb-2">File upload</h3>
        <p class="font-normal text-gray-700">Learn how to get started by downloading and configuring Flowbite locally on your machine and start developing.</p>
    </a>
    <a href="{{< ref "forms/color-picker" >}}" class="p-6 block bg-white hover:bg-gray-100 shadow-md border border-gray-200 rounded-lg mb-6 lg:mb-0">
        <h3 class="text-gray-900 font-bold text-2xl tracking-tight mb-2">Color picker</h3>
        <p class="font-normal text-gray-700">Learn how to get started by downloading and configuring Flowbite locally on your machine and start developing.</p>
    </a>
    <a href="{{< ref "forms/toggles-switches" >}}" class="p-6 block bg-white hover:bg-gray-100 shadow-md border border-gray-200 rounded-lg mb-6 lg:mb-0">
        <h3 class="text-gray-900 font-bold text-2xl tracking-tight mb-2">Toggles & Switches</h3>
        <p class="font-normal text-gray-700">Learn how to get started by downloading and configuring Flowbite locally on your machine and start developing.</p>
    </a>
</div>

## Form example

This is an example of a form component including an email, password, checkbox, and submit button that you can use as a starting point for any form element in your website using FlowBite and Tailwind CSS.

{{< example >}}
<form>
  <div class="mb-6">
    <label for="email" class="text-sm font-medium text-gray-900 block mb-2">Your email</label>
    <input type="email" id="email" class="bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5" placeholder="name@flowbite.com" required>
  </div>
  <div class="mb-6">
    <label for="password" class="text-sm font-medium text-gray-900 block mb-2">Your password</label>
    <input type="password" id="password" class="bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5" required>
  </div>
  <div class="flex items-start mb-6">
    <div class="flex items-center h-5">
      <input id="remember" aria-describedby="remember" type="checkbox" class="bg-gray-50 border border-gray-300 focus:ring-3 focus:ring-blue-300 h-4 w-4 rounded" required>
    </div>
    <div class="text-sm ml-3">
      <label for="remember" class="font-medium text-gray-900">Remember me</label>
    </div>
  </div>
  <button type="submit" class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center">Submit</button>
</form>
{{< /example >}}

## Input Sizing

Use the following utility classes to create three different sizing options (large, base, and small) for your form input elements.

{{< example >}}
<div class="mb-6">
    <label for="large-input" class="text-sm font-medium text-gray-900 block mb-2">Large input</label>
    <input type="text" id="large-input" class="bg-gray-50 border border-gray-300 text-gray-900 sm:text-md rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-4">
</div>
<div class="mb-6">
    <label for="base-input" class="text-sm font-medium text-gray-900 block mb-2">Base input</label>
    <input type="text" id="base-input" class="bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5">
</div>
<div>
    <label for="small-input" class="text-sm font-medium text-gray-900 block mb-2">Small input</label>
    <input type="text" id="small-input" class="bg-gray-50 border border-gray-300 text-gray-900 sm:text-xs rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2">
</div>
{{< /example >}}

## Disabled inputs

Use the following utility classes to indicate a disabled form input item.

{{< example >}}
<input type="text" id="disabled-input" class="mb-6 bg-gray-100 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 cursor-not-allowed" value="Disabled input" disabled>
<input type="text" id="disabled-input-2" class="bg-gray-100 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 cursor-not-allowed" value="Disabled readonly input" disabled readonly>
{{< /example >}}

## Shadow inputs

Alternatively, you can decide to apply a shadow styling using the `shadow-sm` class to any of your form input elements.

{{< example >}}
<form>
  <div class="mb-6">
    <label for="email" class="text-sm font-medium text-gray-900 block mb-2">Your email</label>
    <input type="email" id="email" class="shadow-sm bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5" placeholder="name@flowbite.com" required>
  </div>
  <div class="mb-6">
    <label for="password" class="text-sm font-medium text-gray-900 block mb-2">Your password</label>
    <input type="password" id="password" class="shadow-sm bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5" required>
  </div>
  <div class="mb-6">
    <label for="repeat-password" class="text-sm font-medium text-gray-900 block mb-2">Repeat password</label>
    <input type="password" id="repeat-password" class="shadow-sm bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5" required>
  </div>
  <div class="flex items-start mb-6">
    <div class="flex items-center h-5">
      <input id="terms" aria-describedby="terms" type="checkbox" class="bg-gray-50 border border-gray-300 focus:ring-3 focus:ring-blue-300 h-4 w-4 rounded" required>
    </div>
    <div class="text-sm ml-3">
      <label for="terms" class="font-medium text-gray-900">I agree with the <a href="#" class="text-blue-600 hover:underline">terms and conditions</a></label>
    </div>
  </div>
  <button type="submit" class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center">Register new account</button>
</form>
{{< /example >}}

## Helper text

Use the following markup to also add a helper text below your form input item. Usually used for newsletter signup elements.

{{< example >}}
<label for="email" class="text-sm font-medium text-gray-900 block mb-2">Your email</label>
<input type="email" id="email" class="bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5" placeholder="name@flowbite.com">
<p class="mt-2 text-sm text-gray-500">We’ll never share your details. Read our <a href="#" class="font-medium text-blue-600 hover:underline">Privacy Policy</a>.</p>
{{< /example >}}

## Input element with icon

Use the following Tailwind utility classes and SVG icon to add an icon inside input form elements.

{{< example >}}
<label for="email-adress-icon" class="text-sm font-medium text-gray-900 block mb-2">Your Email</label>
<div class="mt-1 relative">
  <div class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none">
    <svg class="w-5 h-5 text-gray-500" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"></path><path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"></path></svg>
  </div>
  <input type="text" id="email-adress-icon" class="bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full pl-10 p-2.5" placeholder="name@flowbite.com">
</div>
{{< /example >}}

## Input element with addon

Use the following utility classes and SVG icon to add an addon icon inside your input form elements.

{{< example >}}
<label for="website-admin" class="text-sm font-medium text-gray-900 block mb-2">Username</label>
<div class="flex">
  <span class="inline-flex items-center px-3 rounded-l-md border border-r-0 border-gray-300 bg-gray-200 text-gray-900 sm:text-sm">
    @
  </span>
  <input type="text" id="website-admin" class="rounded-none rounded-r-lg bg-gray-50 border border-gray-300 text-gray-900 focus:ring-blue-500 focus:border-blue-500 block flex-1 min-w-0 w-full sm:text-sm border-gray-300 p-2.5" placeholder="Bonnie Green">
</div>
{{< /example >}}

## Success and error validation

Use the following two success and error styles when validation your forms.

{{< example >}}
<div class="mb-6">
  <label for="username-success" class="text-sm font-medium text-green-700 block mb-2">Your name</label>
  <input type="text" id="username-success" class="bg-green-50 border border-green-500 text-green-900 placeholder-green-700 sm:text-sm rounded-lg focus:ring-green-500 focus:border-green-500 block w-full p-2.5" placeholder="Bonnie Green">
  <p class="mt-2 text-sm text-green-600"><span class="font-medium">Alright!</span> Username available!</p>
</div>
<div>
  <label for="username-error" class="text-sm font-medium text-red-700 block mb-2">Your name</label>
  <input type="text" id="username-error" class="bg-red-50 border border-red-500 text-red-900 placeholder-red-700 sm:text-sm rounded-lg focus:ring-red-500 focus:border-red-500 block w-full p-2.5" placeholder="Bonnie Green">
  <p class="mt-2 text-sm text-red-600"><span class="font-medium">Oops!</span> Username already taken!</p>
</div>
{{< /example >}}

## Textarea

Use the following code to create a textarea form element.

{{< example >}}
<label for="message" class="text-sm font-medium text-gray-900 block mb-2">Your message</label>
<textarea id="message" rows="4" class="bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2" placeholder="Leave a comment..."></textarea>
{{< /example >}}

## Select input

Use the following select input element to show selectable list of items.

{{< example >}}
<label for="countries" class="text-sm font-medium text-gray-900 block mb-2">Select your country</label>
<select id="countries" class="bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5">
  <option>United States</option>
  <option>Canada</option>
  <option>France</option>
  <option>Germany</option>
</select>
{{< /example >}}

## Checkbox

The code below can be used to create a fieldset of checkbox elements inside a form. We also created a checkbox variant with extra description and one in a disabled form.

{{< example >}}
<fieldset>
  <legend class="sr-only">Checkbox variants</legend>

  <div class="flex items-center items-start mb-4">
      <input id="checkbox-1" aria-describedby="checkbox-1" type="checkbox" class="bg-gray-50 border-gray-300 focus:ring-3 focus:ring-blue-300 h-4 w-4 rounded" checked>
      <label for="checkbox-1" class="text-sm ml-3 font-medium text-gray-900">I agree to the <a href="#" class="text-blue-600 hover:underline">terms and conditions</a></label>
  </div>

  <div class="flex items-start items-center mb-4">
      <input id="checkbox-2" aria-describedby="checkbox-2" type="checkbox" class="bg-gray-50 border-gray-300 focus:ring-3 focus:ring-blue-300 h-4 w-4 rounded">
      <label for="checkbox-2" class="text-sm ml-3 font-medium text-gray-900">I want to get promotional offers</label>
  </div>

  <div class="flex items-start items-center mb-4">
      <input id="checkbox-3" aria-describedby="checkbox-3" type="checkbox" class="bg-gray-50 border-gray-300 focus:ring-3 focus:ring-blue-300 h-4 w-4 rounded">
      <label for="checkbox-3" class="text-sm ml-3 font-medium text-gray-900">I am 18 years or older</label>
  </div>
  
  <div class="flex items-start mb-4">
    <div class="flex items-center h-5">
      <input id="shipping-2" aria-describedby="shipping-2" type="checkbox" class="bg-gray-50 border-gray-300 focus:ring-3 focus:ring-blue-300 h-4 w-4 rounded">
    </div>
    <div class="text-sm ml-3">
      <label for="shipping-2" class="font-medium text-gray-900">Free shipping via Flowbite</label>
      <div class="text-gray-500"><span class="font-normal text-xs">For orders shipped from Flowbite from <span class="font-medium">€ 25</span> in books or <span>€ 29</span> on other categories</span></div>
    </div>
  </div>

  <div class="flex items-start items-center">
      <input id="international-shipping-disabled" aria-describedby="international-shipping-disabled" type="checkbox" class="bg-gray-50 border-gray-300 focus:ring-3 focus:ring-blue-300 h-4 w-4 rounded" disabled>
      <label for="international-shipping-disabled" class="text-sm ml-3 font-medium text-gray-400">Eligible for international shipping (disabled)</label>
  </div>
</fieldset>
{{< /example >}}

## Radio

Group a series of buttons together on a single line or stack them in a vertical column.

{{< example >}}
<fieldset>
  <legend class="sr-only">Countries</legend>

  <div class="flex items-center mb-4">
    <input id="country-option-1" type="radio" name="countries" value="USA" class="h-4 w-4 border-gray-300 focus:ring-2 focus:ring-blue-300" aria-labelledby="country-option-1" aria-describedby="country-option-1" checked>
    <label for="country-option-1" class="text-sm font-medium text-gray-900 ml-2 block">
      United States
    </label>
  </div>

  <div class="flex items-center mb-4">
    <input id="country-option-2" type="radio" name="countries" value="Germany" class="h-4 w-4 border-gray-300 focus:ring-2 focus:ring-blue-300" aria-labelledby="country-option-2" aria-describedby="country-option-2">
    <label for="country-option-2" class="text-sm font-medium text-gray-900 ml-2 block">
      Germany
    </label>
  </div>

  <div class="flex items-center mb-4">
    <input id="country-option-3" type="radio" name="countries" value="Spain" class="h-4 w-4 border-gray-300 focus:ring-2 focus:ring-blue-300" aria-labelledby="country-option-3" aria-describedby="country-option-3">
    <label for="country-option-3" class="text-sm font-medium text-gray-900 ml-2 block">
      Spain
    </label>
  </div>

  <div class="flex items-center mb-4">
    <input id="country-option-4" type="radio" name="countries" value="United Kingdom" class="h-4 w-4 border-gray-300 focus:ring-2 focus:ring-blue-300" aria-labelledby="country-option-4" aria-describedby="country-option-4">
    <label for="country-option-4" class="text-sm font-medium text-gray-900 ml-2 block">
      United Kingdom
    </label>
  </div>

  <div class="flex items-center">
    <input id="option-disabled" type="radio" name="countries" value="China" class="h-4 w-4 border-gray-200 focus:ring-2 focus:ring-blue-300" aria-labelledby="option-disabled" aria-describedby="option-disabled" disabled>
    <label for="option-disabled" class="text-sm font-medium text-gray-400 ml-2 block">
      China (disabled)
    </label>
  </div>
</fieldset>
{{< /example >}}

<div class="mt-8 -mb-5">
  {{< requires_js >}}
</div>

## File upload

Use the following Tailwind CSS file upload element to receive any type of file from users.

{{< example >}}
<label class="text-sm font-medium text-gray-900 block mb-2" for="user_avatar">Upload file</label>
<input class="block w-full cursor-pointer bg-gray-50 border border-gray-300 text-gray-900 focus:outline-none focus:border-transparent text-sm rounded-lg" aria-describedby="user_avatar_help" id="user_avatar" type="file">
<div class="mt-1 text-sm text-gray-500" id="user_avatar_help">A profile picture is useful to confirm your are logged into your account</div>
{{< /example >}}

<div class="mt-8 -mb-5">
  {{< requires_js >}}
</div>

## Toggle (switches)

Use the following toggle (switches) element to ask for a yes or no type of input from your users without the use of JavaScript.

{{< example >}}
<label for="toggle-example" class="flex items-center cursor-pointer relative mb-4">
  <input type="checkbox" id="toggle-example" class="sr-only">
  <div class="toggle-bg bg-gray-200 border-2 border-gray-200 h-6 w-11 rounded-full"></div>
  <span class="ml-3 text-gray-900 text-sm font-medium">Toggle me</span>
</label>

<label for="toggle-example-checked" class="flex items-center cursor-pointer relative">
  <input type="checkbox" id="toggle-example-checked" class="sr-only" checked>
  <div class="toggle-bg bg-gray-200 border-2 border-gray-200 h-6 w-11 rounded-full"></div>
  <span class="ml-3 text-gray-900 text-sm font-medium">Toggle me (checked)</span>
</label>
{{< /example >}}
