---
title: Understanding Tailwind Typography
subtitle: "Okay "
date: 2024-12-26T20:11:00.000Z
draft: true
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
categories: ["risk management", "decision analysis"]  
---

## The usual Markdown codes:

```
# First
## Second
### Third
#### Fourth
```
## _Render as:_ 

# First
## Second
### Third
#### Fourth  

<hr>



<h1 class="sm:text-md font-medium">Now is the time...</h1> -->
<hr>  


# Using H1

```
<h1 class="font-light"> font-light </h1> 
<h1 class="font-normal"> font-normal </h1> 
<h1 class="font-medium"> font-medium </h1> 
<h1 class="font-semibold"> font-semibold </h1> 
<h1 class="font-bold"> font-bold </h1>
<h1 class="font-extrabold"> font-extrabold </h1>
```
# _H1 Renders as:_

<h1 class="font-light"> font-light </h1> 
<h1 class="font-normal"> font-normal </h1> 
<h1 class="font-medium"> font-medium </h1> 
<h1 class="font-semibold"> font-semibold </h1> 
<h1 class="font-bold"> font-bold </h1>
<h1 class="font-extrabold"> font-extrabold </h1>


## _H2 renders as:_

<h2 class="font-light"> font-light </h2> 
<h2 class="font-normal"> font-normal </h2> 
<h2 class="font-medium"> font-medium </h2> 
<h2 class="font-semibold"> font-semibold </h2> 
<h2 class="font-bold"> font-bold </h2>
<h2 class="font-extrabold"> font-extrabold </h2>

<hr>

### _H3 Renders as:_

<h3 class="font-light">   font-light </h3> 
<h3 class="font-normal">   font-normal </h3> 
<h3 class="font-medium">   font-medium </h3> 
<h3 class="font-semibold">   font-semibold </h3> 
<h3 class="font-bold">   font-bold </h3> 
<h3 class="font-extrabold">   font-extrabold </h3> 

<hr>

#### _H4 Renders as:_
<h4 class="font-light"> font-light </h4> 
<h4 class="font-normal"> font-normal </h4> 
<h4 class="font-mediumn"> font-medium </h4> 
<h4 class="font-semibold"> font-semibold </h4> 
<h4 class="font-bold"> font-bold </h4> 
<hr>

### Tailwind font weight classes in a \<p\> element
```

<p class="font-light ...">font-light: </p>
<p class="font-normal ...">font-normal: </p>
<p class="font-medium ...">font-medium: </p>
<p class="font-semibold ...">font-semibold: </p>
<p class="font-bold ...">font-bold: </p>
<p class="font-extrabold ...">font-extrabold: </p>
<p class="font-black ...">font-black:</p>
``` 

### _renders to:_

<p class="font-light ...">  - font-light</p>
<p class="font-normal ...">  - font-normal</p>
<p class="font-medium ...">  - font-medium</p>
<p class="font-semibold ...">  - font-semibold </p>
<p class="font-bold ...">  - font-bold</p>
<p class="font-extrabold ...">  - font-extrabold</p>
<p class="font-black ...">  - font-black</p>

<hr>

## Classes found in the blox page and single templates

```
<h1 class="sm:text-5xl font-medium">Now is the time...h1 sm:text-5xl font-medium</h1>
<h1 class="sm:text-lg font-medium">Now is the time...h1 sm:text-lg font-medium</h1>
<h1 class="sm:text-md font-medium">Now is the time...sm:text-md</h1>
<h1 class="sm:text font-large">Now is the time...lg:text-4xl</h1>
<h1 class="lg:m:text-3xl font-medium">Now is the time...lg:text-3xl</h1>
```
### _Rendering as:_

<h1 class="sm:text-5xl font-medium">h1 sm:text-5xl font-medium</h1>
<h1 class="sm:text-lg font-medium">h1 sm:text-lg font-medium</h1>
<h1 class="sm:text-md font-medium">sm:text-md</h1>
<h1 class="sm:text font-large">lg:text-4xl</h1>
<h1 class="lg:m:text-3xl font-medium">lg:text-3xl</h1>



From hugo_stats.json
```    "font-black", 
      "font-bold",
      "font-color:blue",
      "font-extrabold",
      "font-italic",
      "font-large",
      "font-light",
      "font-medium",
      "font-mediumn",
      "font-normal",
      "font-semibold",
      "font-small",

      "sm:text",
      "sm:text-5xl",
      "sm:text-lg",
      "sm:text-md",

      "text-1xl",
      "text-2xl",
      "text-3xl",
      "text-4xl",
      "text-[0.6rem]",
      "text-base",
      "text-black",
      "text-center",
      "text-current",
      "text-dark",
      "text-ellipsis",
      "text-gray-200",
      "text-gray-500",
      "text-gray-700",
      "text-gray-900",
      "text-lg",
      "text-md",
      "text-neutral-500",
      "text-neutral-700",
      "text-neutral-800",
      "text-primary-600",
      "text-primary-700",
      "text-primary-800",
      "text-red-400",
      "text-right",
      "text-slate-500",
      "text-slate-700",
      "text-slate-900",
      "text-sm",
      "text-white",
      "text-wrap",
      "text-xl",
      "text-xs",
      "text-zinc-400",
      "text-zinc-600",
      "text-zinc-800",
```
<p class="text-slate-500">The quick brown fox...</p>
<p class="text-slate-700">The quick brown fox...</p>
<p class="text-slate-900">The quick brown fox...</p>

<p class="text-base">The quick brown fox...</p>




```
      <p class="sm:text">The quick brown fox...</p>
      <p class="sm:text-5xl">The quick brown fox...</p>
      <p class="sm:text-lg">The quick brown fox...</p>
      <p class="sm:text-md">The quick brown fox...</p>

      <p class="text-1xl">The quick brown fox...</p>
      <p class="text-2xl">The quick brown fox...</p>
      <p class="text-3xl">The quick brown fox...</p>
      <p class="text-4xl">The quick brown fox...</p>
```

<p class="sm:text">sm:text -- The quick brown fox...</p>
<p class="sm:text-5xl">sm:text-5xl -- The quick brown fox...</p>
<p class="sm:text-lg">sm:text-lg -- The quick brown fox...</p>
<p class="sm:text-md">sm:text-md -- The quick brown fox...</p>

<p class="text-1xl">The quick brown fox...</p>
<p class="text-2xl">The quick brown fox...</p>
<p class="text-3xl">The quick brown fox...</p>
<p class="text-4xl">The quick brown fox...</p>


For xl 1 through 5

<p class="sm:text-1xl">sm:text-1xl -- The quick brown fox...</p>
<p class="sm:text-2xl">sm:text-2xl -- The quick brown fox...</p>
<p class="sm:text-3xl">sm:text-3xl -- The quick brown fox...</p>
<p class="sm:text-4xl">sm:text-4xl -- The quick brown fox...</p>
<p class="sm:text-5xl">sm:text-5xl -- The quick brown fox...</p>