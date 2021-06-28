---
title: শুরুর আগে
subtitle: >-
  শুরু করার আগে যে যে সেটআপ প্রয়োজন তা ভালো করে দেখে নাও ও ফুলফিল করো। কম্পিউটার
  বা মোবাইল উভয় ইউজারের সেটআপই এখানে দেখানো হলো। এসংক্রান্ত যেকোন সমস্যায়
  স্ক্রীনশটসহ মেইল করে জানিয়ে দিও।
seo:
  title: Theme Style Guide
  description: A reference for suggested typographic treatment and styles for your content
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Theme Style Guide
      keyName: property
    - name: 'og:description'
      value: >-
        A reference for suggested typographic treatment and styles for your
        content
      keyName: property
    - name: 'og:image'
      value: images/1.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Theme Style Guide
    - name: 'twitter:description'
      value: >-
        A reference for suggested typographic treatment and styles for your
        content
    - name: 'twitter:image'
      value: images/1.jpg
      relativeUrl: true
layout: page
---
##### তুমি যদি কম্পিউটার ইউজার হও তাহলে নিচের কাজ দুটি করে ফেলো

*   তোমার মেশিনে NodeJs ইন্সটল করে ফেলো। নোড নিয়ে আমরা পরে বিস্তারিত আলোচনা করবো। আপাতত [nodejs.org](https://nodejs.org) থেকে তোমার মেশিনের মানানসই প্যাকেজটি ইন্সটল করো। প্রয়োজনে অনলাইনে সাহায্য নাও। কোথায় সাহায্য পাবে সেটা তো জানোই।

*   ভালো একটা কোড এডিটর ইন্সটল করো, আমার রিকমেন্ডেশান হলো [Visual Studio](https://code.visualstudio.com/). তোমার মতো জুনিয়র থেকে বড়ো বড়ো ডেভেলপারদের বেশিরভাগই এটা ইউজ করে।

তুমি যদি NodeJs ও Visual Studio Code ঠিকভাবে ইন্সটল করে থাকো, তাহলে তুমি কোডিংয়ের জন্য রেডি।

![](https://i.ibb.co/yVsnXs8/vs-node.png)

File থেকে New File ক্রিয়েট করে একটা নাম দাও **.js** এক্সটেনশন সহ। এরপর এখানে কোড লিখতে হবে। আমি যখন বলবো রান করো, তখন প্রথম কাজ হচ্ছে কোডটাকে সেভ করা ctrl s চেপে। এরপর মেনুবার থেকে Terminal এ New Terminal এ ক্লিক করে একটা টারমিনাল ওপেন করবে। সেখানে লিখবে node filename.js এরপর enter চাপলে কোড রান হবে। এখানে filename এর জায়গায় তোমার ফাইলের নাম দিবে। টার্মিনাল এবং কমান্ডের কিছু না বোঝলে আমার বেসিক কম্পিউটিং এর লেখাগুলো দেখে আসো।

##### এবার আসি তুমি যদি স্মার্টফোন ইউজার হও

*   প্রথমে ফটাফট [এখানে Google Play](https://play.google.com/store/apps/details?id=com.foxdebug.acodefree\&hl=en\&gl=US) থেকে অথবা [এখানে থেকে](https://m.apkpure.com/acode-powerful-code-editor/com.foxdebug.acodefree)  Acode Editor  ইন্সটল করে নাও।

*   এরপর নিচের দেখানো সেটিংস ঠিক করে নাও।

![](https://i.ibb.co/41b1rY3/Screenshot-20210627-223008.jpg)

উপরের ছবির মতো 3 dot অপশন থেকে Setting এ গিয়ে Other setting থেকে Preview mode কে In App সিলেক্ট করে দাও, Show console এনেবেল করা না থাকলে এনেবেল করে দাও।

![](https://i.ibb.co/bFFrnJ5/Screenshot-20210627-223106.jpg)

আবার উপরের ছবির মতো Setting থেকে Editor setting থেকে Live Autocompletion কে ডিজেবল করে দাও।

এবার তোমার এডিটর প্রস্তুত। এবার মেনু থেকে New file এ একটি ফাইল ক্রিয়েট করবে ইচ্ছামতো নাম দিয়ে .js এক্সটেনশ সহ ( যেমন app.js ) এবং সেভ করার সময় লোকেশন দেখিয়ে দেবে। আগে থেকে একটা ফোল্ডার খুলে রাখবে সব ফাইলকে একসাথে রাখার জন্য, ঐ ফোল্ডার দেখিয়ে দেবে। যখুনি কোড লিখতে বলব তখন নিচের মতো কোড লিখবে।

![](https://i.ibb.co/71gFPT8/Screenshot-20210627-223309.jpg)

আর যখন রান করতে বলবো তখন সবার আগে ফাইলটিকে সেভ করবে। এরপর উপরের ডান পাশে play বাটনে প্রেস করবে। তাহলে তোমার কোডের রেজাল্ট দেখতে পারবে এরকম -

![](https://i.ibb.co/nrySBtV/Screenshot-20210627-223327.jpg)

আর যদি কোডে ভুল থাকে, তাহলে রেজাল্টের বদলে লাল ব্যাকগ্রাউন্ডে এরর পাবে।

> অভারঅল সেটাপে যেকোন প্রবলেমে স্ক্রীনশট সহ মেইল করে জানাও অথবা Ask me তে মেসেজ পাঠাও।
