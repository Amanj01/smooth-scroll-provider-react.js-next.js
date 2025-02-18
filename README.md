# Smooth Scroll with @studio-freight/lenis in Next.js

This project demonstrates how to integrate smooth scrolling using `@studio-freight/lenis` in a Next.js application.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)

## Introduction

Lenis is a lightweight and easy-to-use smooth scrolling library that can be integrated into your React or Next.js project to provide a pleasant scrolling experience.

## Installation

First, install the `@studio-freight/lenis` package using npm or yarn:

```bash
npm install @studio-freight/lenis

usage:
``` 
--- How to use Lenis in your Next.js project: ---
1. Install the Lenis package:
npm install @studio-freight/lenis
2. Import Lenis and create an instance:
import Lenis from '@studio-freight/lenis';
copy the code that i wrote in the SmoothScrollProvider.jsx file
use the custom css also you can modify the css as you want
import the SmoothScrollProvider.jsx in the layout.jsx or main.jsx file
then wrap the children with the SmoothScrollProvider.jsx


Customization:

You can customize the behavior of the Lenis smooth scroll by adjusting the options in the Lenis constructor. Here are a few options you can modify:

duration: The duration of the scrolling animation.

easing: The easing function for the scrolling animation.

direction: The scroll direction, either 'vertical' or 'horizontal'.

smooth: Enable or disable smooth scrolling.

smoothTouch: Enable or disable smooth scrolling on touch devices.

touchMultiplier: Adjust the scrolling speed on touch devices.# smooth-scroll-provider-react.js-next.js
