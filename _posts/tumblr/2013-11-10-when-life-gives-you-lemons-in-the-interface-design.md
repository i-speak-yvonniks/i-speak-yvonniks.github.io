---
layout: post
title: When Life Gives You Lemons in the Interface Design World
date: '2013-11-10T17:21:00+00:00'
tags: []
tumblr_url: https://yvonniks.tumblr.com/post/69522993295/when-life-gives-you-lemons-in-the-interface-design
thumbnail-img: http://i.imgur.com/hcJarXnl.png
---
Over the past year at Intuit, the Small Business Financial Services division has been working hard toward a harmonized product ecosystem. The goal is for all products have the same look and feel so users immediately know they are using an Intuit (as a brand) product. The teams under QuickBooks Online (QBO) have been collaborating to align on patterns, color, content, layout styles, etc. with the vision that QBO users find the product experiences easy, convenient, and delightful to use whether it be on the web, tablet, or phone.&nbsp;

Now when Apple announced iOS7, their newest operating system, it became an unexpected curveball for the QuickBooks Online mobile team. Apple has set the latest societal fashion trend, essentially making a bold statement that if we don’t hop on board and comply with iOS7, we will not only become a fashion faux pas- we will fall behind and die.&nbsp;  
   
 So we got to work.&nbsp;  
   
 However, we didn’t want to just conform to iOS7, we wanted to continue working toward a world class kick butt delightful app with more solid functionality and design as well as sticking with our QBO harmony&nbsp;ecosystem strategy.&nbsp;  
   
 After reading up on iOS7 guidelines and resources, one of the first things our engineering team put together was a checklist of existing UI elements to tackle immediately.&nbsp;  
   
 We needed to respect the major themes of iOS7 increasing:&nbsp;  
 a) **Deference** - design elements should respect and never compete with data or content  
 b) **Clarity** - text, icons, graphics should be clear and precise  
 c) **Depth** - presentation of information layers, transitions, motion should be fluid and graceful&nbsp;  
   
 Our list included removing custom layout code, replacing hard-coded sizes and heights with Auto Layout, replacing hard-coded fonts with Dynamic Type, removing drop shadows/bevels, revisiting custom buttons, etc.&nbsp;

![engineering checklist](http://i.imgur.com/hcJarXnl.png)

### **EVOLVING AWAY FROM SKEUMORPHISM**

Visual design concepting included some major mind shifting in the sense of going flat, introducing translucency, lightening the chrome and font- all while maintaining alignment with Intuit brand colors and style guide. &nbsp;  
   
 Because&nbsp;iOS7 was a deliberate evolution away from skeumorphism, we had to make some drastic changes to how we represented the hierarchy of our application.&nbsp;Our Harmony system was also moving in this direction, so it was an opportunity to think about what happens when:&nbsp;  
   
 a) no more backgrounds or patterns to differentiate between types of form data&nbsp;  
 b) no real-world paper metaphor&nbsp;  
 c) no stamps to represent status&nbsp;  
 d) no 3D buttons&nbsp;  
  
 The team had to rethink how we support the intrinsic hierarchy of our data in a flat system. After much collaboration, brainstorming sessions, iteration upon iteration, collecting feedback from engineers, product managers, researchers and customers, the outcome included:&nbsp;  
   
 a) using&nbsp;color as emphasis&nbsp;  
 b) leveraging different font weights when&nbsp;appropriate  
 c)&nbsp;edge to edge photo elements&nbsp;  
 d) date and amounts as focus  
 e) de-emphasizing chrome and borders

### **MENU**

One of the first views we changed was the menu. You can see that we got rid of the bevels, shadows, textures, and simplified the view. The new colors we used was a deliberate change we had in our ecosystem roadmap as they are primary colors in our Harmony system style guide.&nbsp;  
   
 **Before and After:&nbsp;**

![nav list](http://i.imgur.com/mrkqpykl.png)

### **FORMS**

Next, we revisited our forms. iOS7 encourages us to de-emphasize the chrome and borders and utilize all of the screen real estate so we made our form fields run edge to edge. We also changed the button styles emphasizing on text and iconography rather than gradient-filled button treatment.

**Before and After:**

![form design](http://i.imgur.com/URY0xhsl.png)

### **ICONS**

All of our icons also had to be re-worked to fit into the flat world. Like most other apps before iOS7, our icons in iOS6 have bevel and gradients. We could’ve simply remove those elements and flatten them, but when there are multiple displayed together, they still felt a bit heavy against a dark background. To make them fit into our more lightweight design, we sought to make them more iOS7-like with minimal fill and change the background color to a lighter gray color with slight transparency.

**Iterations/ Before and After:**

![icons iterations](http://i.imgur.com/rqr1LrLl.png)

&nbsp;

### **TRANSACTION VIEW**

The transaction view was the most difficult to re-design. The content presented in each transaction type is imperative for business accounting needs. How could we successfully move away from skeumorphic elements when they provided such a strong mental connection with real-world accounting? How could we keep a professional modern business feel without losing the QB brand personality?

For our early explorations of transaction view, we really questioned the mental connection to accounting. Should we really move away from paper metaphors entirely? We felt it was necessary to keep a bit of it to reinforce the notion of accounting transactions.

**Early Explorations:**

![transaction views 1](http://i.imgur.com/GTzbGXXl.png)

We also needed to think about how the designs would scale across devices and align with QBO web. Was it possible to move away from paper and stamp elements? Why not try it? At this point, our design team went super broad in our thinking about how phone designs might translate over on tablets or web, then narrowed down on a couple designs we liked and agreed upon, then iterated upon those.

![brainstorm and sketch](http://i.imgur.com/IhFt1lUl.png)

After several iterations, we ultimately decided that while skeumorphic elements do help reinforce our product’s purpose, it does not define our product or brand. We finalized on a color block layout providing better readability, solid contrast, and emphasized statuses with QB Harmony colors. We feel the new layout really speaks to iOS7’s principle that “data is king,” making complex info simple, actions clear, call attention to key data, and data is scannable.   
  
 **Before and After:**

![transaction views 2](http://i.imgur.com/plK8jEfl.png)

### **COLOR AS EMPHASIS**

![color as emphasis](http://i.imgur.com/M8XS60Pl.png)

### **FLATTENING OUT**

![expense by category view](http://i.imgur.com/9rFL6LIl.png)

### **ADDING DEPTH**

Now that we’ve flattened out, we needed to make sure all of our screens fit within our Harmony system and gelled together nicely to form a world-class featured app. For the iOS7 release, we really invested in adding more depth to support the fluidity and richness of the app experience. iOS7 introduced some really nice animations, layer transitions, blur/transparency, subtle parallax (movement of objects as you move your device)- all which serve to support the notion of beautiful design and depth of the new operating system.

However, we encountered some limitations as default iOS7’s layers and animations interfered with our own ideas. It was hard for us to find ways to use gestures to support our own app hierarchy. For example, the top notification panel and bottom control panel halted our plans for introducing a window shade interaction in our customer detail view to access details from the customer activity feed. The top and bottom swipes have already been monopolized by the operating system. This is the example:

![adding depth](http://i.imgur.com/3Ay55QDl.png)

Of course, that didn’t stop us. We decided to take this limitation as an opportunity to explore other ways to introduce depth. We didn’t want to be forceful or obnoxious about it, though. Whatever depth we thought about introducing, we wanted it to be subtle and delightful, yet compelling enough to display important information. Our new customer view has a tabbed layout- the information layer below the customer summary animates left and right when the user taps on a tab. The customer summary and icon bar also has subtle blur effects.

**Before and After:**

![customer detail blur](http://i.imgur.com/MT83MMXl.png)

Furthermore, we took a look at our action sheets to see if we could add some ‘oomph’ in that area. We took advantage of the fact that our app offers multiple transactions a user can create at the company activity level. Let’s not be so plain and drab- let’s see if we make the act of creating a transaction fun. So, we introduced a ‘global create’ custom action sheet complete with animation and translucency. This is considered a bold change in our app which we feel adds more brand personality and delight. The design feels very iOS7, and it creates a more modern look and feel for QuickBooks Online.

![global nav](http://i.imgur.com/jHngd1Vl.png)

Additional animations we’ve introduced include the pulsating create button on an empty state screen, parallax in our backgrounds and filtering mechanism, and subtle animations between each screen in our First Time Use screens. We urge you to download our app and play with it!

![benefits screens](http://i.imgur.com/hgCKy4ll.png)

### **WHEN TO USE DYNAMIC TYPE**

We used our best judgement when deciding where to use dynamic type. We wanted to utilize all of the new iOS7 UI features as much as possible, and definitely want all of our screen designs to scale, but when it comes to dynamic type, it has some limitations. It makes sense in some cases and less in others. There are a lot of edge cases in how data is presented in our app. We also support multiple languages so we have to consider the effects on localization efforts. This makes it difficult to ensure that dynamic type won’t mess up the intended layout. Ultimately, we decided at least for launch that it makes more sense to use dynamic text in a list view, but NOT in a transaction detail view. We may re-visit the layout of the detail views in the future to incorporate use of dynamic type.

![dynamic type](http://i.imgur.com/EghslHQl.png)

Designing for iOS7 has been unexpected and challenging, but fulfilling. I believe our users will be delighted to see the updated app. If there’s one thing to take away from the experience thus far, I have to quote Atmosphere: “When life gives you lemons, paint that sh\*t gold.” The team not only aimed to fit within iOS7, we aimed to be world-class, improving the overall mobile QBO experience- and we’re not going to stop.

[Check us out](https://itunes.apple.com/us/app/quickbooks-online-for-iphone/id393232373?mt=8) by downloading the iOS7 app on the app store!
