---
layout: home
title: Tailwind CSS List Group - Flowbite
description: Use the list group component to display a series of items, buttons or links inside a single element
group: components
toc: true

previous: Forms
previousLink: components/forms
next: Typography
nextLink: components/typography
---

The list group component can be used to display a series of elements, buttons or links inside a single card component similar to a sidebar.

## Default example

Here's an example of a list group that you can use right away.

{{< example >}}
<ul class="bg-white rounded-lg border border-gray-200 w-48 text-gray-900 text-sm font-medium">
    <li class="px-4 py-2 border-b border-gray-200 w-full rounded-t-lg">Profile</li>
    <li class="px-4 py-2 border-b border-gray-200 w-full">Settings</li>
    <li class="px-4 py-2 border-b border-gray-200 w-full">Messages</li>
    <li class="px-4 py-2 w-full rounded-b-lg">Download</li>
</ul>
{{< /example >}}

## List group with links

You can also display a series of links inside the list group element.

{{< example >}}
<div class="bg-white rounded-lg border border-gray-200 w-48 text-gray-900 text-sm font-medium">
    <a href="#" aria-current="true" class="block px-4 py-2 border-b border-gray-200 w-full rounded-t-lg bg-blue-700 text-white cursor-pointer">
        Profile
    </a>
    <a href="#" class="block px-4 py-2 border-b border-gray-200 w-full hover:bg-gray-100 hover:text-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-700 focus:text-blue-700 cursor-pointer">
        Settings
    </a>
    <a href="#" class="block px-4 py-2 border-b border-gray-200 w-full hover:bg-gray-100 hover:text-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-700 focus:text-blue-700 cursor-pointer">
        Messages
    </a>
    <a href="#" class="block px-4 py-2 border-b border-gray-200 w-full rounded-b-lg hover:bg-gray-100 hover:text-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-700 focus:text-blue-700 cursor-pointer">
        Download
    </a>
</div>
{{< /example >}}

## List group with buttons

It is also possible to display a list of button element inside the list group component. The following example includes an active and disabled item as well.

{{< example >}}
<div class="bg-white rounded-lg border border-gray-200 w-48 text-gray-900 text-sm font-medium">
    <button aria-current="true" type="button" class="text-left px-4 py-2 border-b border-gray-200 w-full rounded-t-lg bg-blue-700 text-white focus:outline-none cursor-pointer">
        Profile
    </button>
    <button type="button" class="text-left px-4 py-2 border-b border-gray-200 w-full hover:bg-gray-100 hover:text-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-700 focus:text-blue-700 cursor-pointer">
        Settings
    </button>
    <button type="button" class="text-left px-4 py-2 border-b border-gray-200 w-full hover:bg-gray-100 hover:text-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-700 focus:text-blue-700 cursor-pointer">
        Messages
    </button>
    <button disabled type="button" class="text-left px-4 py-2 border-b border-gray-200 bg-gray-100 w-full rounded-b-lg cursor-not-allowed">
        Download
    </button>
</div>
{{< /example >}}

## List group with icons

Use the following example to create a list of buttons as a menu together with SVG icons.

{{< example >}}
<div class="bg-white rounded-lg border border-gray-200 w-48">
    <button type="button" class="px-4 py-2 relative hover:bg-gray-100 hover:text-blue-700 text-gray-900 text-sm font-medium border-b border-gray-200 focus:z-10 focus:ring-2 focus:ring-blue-700 focus:text-blue-700 w-full rounded-t-lg inline-flex items-center">
        <svg class="w-4 h-4 mr-2 fill-current" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-6-3a2 2 0 11-4 0 2 2 0 014 0zm-2 4a5 5 0 00-4.546 2.916A5.986 5.986 0 0010 16a5.986 5.986 0 004.546-2.084A5 5 0 0010 11z" clip-rule="evenodd"></path></svg>
        Profile
    </button>
    <button type="button" class="px-4 py-2 relative hover:bg-gray-100 hover:text-blue-700 text-gray-900 text-sm font-medium border-b border-gray-200 focus:z-10 focus:ring-2 focus:ring-blue-700 focus:text-blue-700 w-full inline-flex items-center">
        <svg class="w-4 h-4 mr-2 fill-current" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M5 4a1 1 0 00-2 0v7.268a2 2 0 000 3.464V16a1 1 0 102 0v-1.268a2 2 0 000-3.464V4zM11 4a1 1 0 10-2 0v1.268a2 2 0 000 3.464V16a1 1 0 102 0V8.732a2 2 0 000-3.464V4zM16 3a1 1 0 011 1v7.268a2 2 0 010 3.464V16a1 1 0 11-2 0v-1.268a2 2 0 010-3.464V4a1 1 0 011-1z"></path></svg>
        Settings
    </button>
    <button type="button" class="px-4 py-2 relative hover:bg-gray-100 hover:text-blue-700 text-gray-900 text-sm font-medium border-b border-gray-200 focus:z-10 focus:ring-2 focus:ring-blue-700 focus:text-blue-700 w-full inline-flex items-center">
        <svg class="w-4 h-4 mr-2 fill-current" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M5 3a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2V5a2 2 0 00-2-2H5zm0 2h10v7h-2l-1 2H8l-1-2H5V5z" clip-rule="evenodd"></path></svg>
        Messages
    </button>
    <button type="button" class="px-4 py-2 relative hover:bg-gray-100 hover:text-blue-700 text-gray-900 text-sm font-medium focus:z-10 focus:ring-2 focus:ring-blue-700 focus:text-blue-700 w-full rounded-b-lg inline-flex items-center">
        <svg class="w-4 h-4 mr-2 fill-current" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M2 9.5A3.5 3.5 0 005.5 13H9v2.586l-1.293-1.293a1 1 0 00-1.414 1.414l3 3a1 1 0 001.414 0l3-3a1 1 0 00-1.414-1.414L11 15.586V13h2.5a4.5 4.5 0 10-.616-8.958 4.002 4.002 0 10-7.753 1.977A3.5 3.5 0 002 9.5zm9 3.5H9V8a1 1 0 012 0v5z" clip-rule="evenodd"></path></svg>
        Download
    </button>
</div>
{{< /example >}}