---
title: "C# 12 - Collection Literals"
date: 2023-06-20T10:50:36-03:00
draft: true
author: "Matheus Macedo"
description: "Csharp 12 - Collection Literals "
tags: ["csharp","c#", "tutorial", "new", "feature", "collections", "collectionslitrals", "news"]
categories: ["C#", "C#12"]
images: []
resources:
- name: featured-image
  src: featured-image.jpg
draft: false
---

**C# 12 New Feature: Collection Literals**

Are you ready for a new and exciting feature in the next iteration of C#? Brace yourself for "Collection Literals," designed to simplify the way we work with collections. If you're tired of cumbersome syntax or intricate steps for handling collections, this new feature is here to make your coding life a breeze!

So, what exactly are collection literals? Well, they introduce a concise and straightforward syntax for creating common collection values. Imagine being able to build collections effortlessly and even combine multiple collections into one. Yes, it's that powerful!

Let's take a closer look at some examples to understand how this works. Suppose we have a list called `numbers` containing `[1, 2, 3]`, and we want to combine it with another span of numbers, `[5, 6, 7]`, along with an additional element, `4`. With collection literals, achieving this desired outcome is a breeze:

```csharp
List<int> numbers = [1, 2, 3];
Span<int> additionalNumbers = [5, 6, 7];
var combinedList = (List<int>)[..numbers, 4, ..additionalNumbers];

// The resulting list: [1, 2, 3, 4, 5, 6, 7]
```

Here, we create a new list called `combinedList` by utilizing the collection literal syntax. We effortlessly merge the elements from the `numbers` list, add `4` in between, and include the elements from the `additionalNumbers` span.

The resulting list becomes `[1, 2, 3, 4, 5, 6, 7]`. As you can see, collection literals make it easy to compose collections with concise and readable code.

With this powerful feature, manipulating collections becomes more intuitive and efficient. Say goodbye to convoluted processes and embrace the simplicity of collection literals in your C# code. Enjoy coding with enhanced productivity and clarity!

Please note that since this feature is still in the preview stage, there is a chance it may not make it into the final release or undergo some changes. The dedicated C# team is actively working on addressing any outstanding concerns to ensure a seamless user experience.

So, what do you think about this upcoming addition to C#? Is it just another language feature or a remarkable improvement? Collection literals promise to simplify working with collections, streamline your code, and enhance productivity. While there might be some uncertainty during the preview phase, the potential benefits are worth the excitement.

Stay tuned for C# 12 news firsthand.

Happy coding!
