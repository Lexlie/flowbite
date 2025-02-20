---
layout: home
title: Tailwind CSS Typography - Flowbite
description: Use the typography and the utility classes from Tailwind CSS to style text with FlowBite
group: components
toc: true

previous: List group
previousLink: components/list-group
next: Modals
nextLink: components/modal
---

The typography for FlowBite is completely based on the utility classes from Tailwind CSS.

We have listed some of the commonly used typography classes that we use throughout the FlowBite UI, however, you can also check out all of the utility classes on the [Tailwind CSS documentation](https://tailwindcss.com/docs/font-family) directly.

## Font Size

Use the following `text-{size}` utility classes from Tailwind to set the font size for any text element.

{{< example >}}
<p class="text-xs">FlowBite</p>
<p class="text-sm">FlowBite</p>
<p class="text-base">FlowBite</p>
<p class="text-lg">FlowBite</p>
<p class="text-xl">FlowBite</p>
<p class="text-2xl">FlowBite</p>
<p class="text-3xl">FlowBite</p>
<p class="text-4xl">FlowBite</p>
<p class="text-5xl">FlowBite</p>
<p class="text-6xl">FlowBite</p>
<p class="text-7xl">FlowBite</p>
<p class="text-8xl">FlowBite</p>
<p class="text-9xl">FlowBite</p>
{{< /example >}}

## Font Weight

Use the following `font-{weight}` utility classes to set the font weight for any text element.

{{< preview >}}
<p class="text-4xl font-thin">FlowBite</p>
<p class="text-4xl font-extralight">FlowBite</p>
<p class="text-4xl font-light">FlowBite</p>
<p class="text-4xl font-normal">FlowBite</p>
<p class="text-4xl font-medium">FlowBite</p>
<p class="text-4xl font-semibold">FlowBite</p>
<p class="text-4xl font-bold">FlowBite</p>
<p class="text-4xl font-extrabold">FlowBite</p>
<p class="text-4xl font-black">FlowBite</p>
{{< /preview >}}

```html
<p class="font-thin">FlowBite</p>
<p class="font-extralight">FlowBite</p>
<p class="font-light">FlowBite</p>
<p class="font-normal">FlowBite</p>
<p class="font-medium">FlowBite</p>
<p class="font-semibold">FlowBite</p>
<p class="font-bold">FlowBite</p>
<p class="font-extrabold">FlowBite</p>
<p class="font-black">FlowBite</p>
```

## Line Height

Use the following `leading-{type}` utility classes to set the line height for any text element.

{{< preview >}}
<span class="text-blue-700 font-normal">.leading-none</span>
<p class="leading-none text-gray-700 mb-4">Themesberg was created to bring quality code and templates together. They use unique and new design trends created solely by their team and innovate the process of developers by their products.</p>
<span class="text-blue-700 font-normal">.leading-tight</span>
<p class="leading-tight text-gray-700 mb-4">Themesberg was created to bring quality code and templates together. They use unique and new design trends created solely by their team and innovate the process of developers by their products.</p>
<span class="text-blue-700 font-normal">.leading-snug</span>
<p class="leading-snug text-gray-700 mb-4">Themesberg was created to bring quality code and templates together. They use unique and new design trends created solely by their team and innovate the process of developers by their products.</p>
<span class="text-blue-700 font-normal">.leading-normal</span>
<p class="leading-normal text-gray-700 mb-4">Themesberg was created to bring quality code and templates together. They use unique and new design trends created solely by their team and innovate the process of developers by their products.</p>
<span class="text-blue-700 font-normal">.leading-relaxed</span>
<p class="leading-relaxed text-gray-700 mb-4">Themesberg was created to bring quality code and templates together. They use unique and new design trends created solely by their team and innovate the process of developers by their products.</p>
<span class="text-blue-700 font-normal">.leading-loose</span>
<p class="leading-loose text-gray-700 mb-4">Themesberg was created to bring quality code and templates together. They use unique and new design trends created solely by their team and innovate the process of developers by their products.</p>
{{< /preview >}}

```html
<p class="leading-none">Themesberg was created to bring quality ...</p>
<p class="leading-tight">Themesberg was created to bring quality ...</p>
<p class="leading-snug">Themesberg was created to bring quality ...</p>
<p class="leading-normal">Themesberg was created to bring quality ...</p>
<p class="leading-relaxed">Themesberg was created to bring quality ...</p>
<p class="leading-loose">Themesberg was created to bring quality ...</p>
```

## Lists

Use the following code to create list items with ordered and unordered lists.

{{< preview >}}
<span class="text-blue-700 font-normal">.list-disc</span>
<ul class="list-disc text-gray-700 mb-6 pl-4">
    <li>Design</li>
    <li>Develop</li>
    <li>Test</li>
</ul>

<span class="text-blue-700 font-normal">.list-decimal</span>
<ol class="list-decimal text-gray-700 mb-6 pl-4">
    <li>Design</li>
    <li>Develop</li>
    <li>Test</li>
</ol>

<span class="text-blue-700 font-normal">.list-default</span>
<ul class="text-gray-700">
    <li>Design</li>
    <li>Develop</li>
    <li>Test</li>
</ul>
{{< /preview >}}

```html
<ul class="list-disc">
    <li>Design</li>
    <li>Develop</li>
    <li>Test</li>
</ul>

<ol class="list-decimal">
    <li>Design</li>
    <li>Develop</li>
    <li>Test</li>
</ol>

<ul>
    <li>Design</li>
    <li>Develop</li>
    <li>Test</li>
</ul>
```

## List position

Use the `list-inside` and `list-outside` classes to set the list item position inside a list component.

{{< preview >}}
<span class="text-blue-700 font-normal">.list-inside</span>
<ul class="list-disc list-inside text-green-700 bg-green-100 rounded-lg mt-2 mb-6">
    <li>Design</li>
    <li>Develop</li>
    <li>Test</li>
</ul>
<span class="text-blue-700 font-normal">.list-outside</span>
<ul class="list-disc list-outside text-green-700 bg-green-100 rounded-lg mt-2">
    <li>Design</li>
    <li>Develop</li>
    <li>Test</li>
</ul>
{{< /preview >}}

```html
<ul class="list-disc list-inside">
    <li>Design</li>
    <li>Develop</li>
    <li>Test</li>
</ul>

<ul class="list-disc list-outside">
    <li>Design</li>
    <li>Develop</li>
    <li>Test</li>
</ul>
```

## Text Decoration

You can use the following classes to set the text decoration for any inline text element.

{{< preview >}}
<span class="text-blue-700 font-normal">.underline</span>
<p class="underline mt-2 mb-4">please read our terms and services</p>
<span class="text-blue-700 font-normal">.line-through</span>
<p class="line-through mt-2 mb-4">please read our terms and services</p>
{{< /preview >}}

```html
<p class="underline">please read our terms and services</p>
```