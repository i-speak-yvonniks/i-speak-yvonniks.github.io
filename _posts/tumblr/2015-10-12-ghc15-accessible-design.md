---
layout: post
title: GHC15 Accessible Design
date: '2015-10-12T20:21:54+00:00'
tags:
- ghc15
- workshop
- accessibility
tumblr_url: https://yvonniks.tumblr.com/post/131054760216/ghc15-accessible-design
---
Hello friends! This post is primarily for GHC folks attending the workshop on Accessible Design: Breaking Barriers between Disability and Digital Interfaces.You can use this post as reference during or after the workshop. I’ve compiled a bunch of resources, guidelines, tools, additional reading, and videos to check out. Feel free to ping me directly if you want to chat more! &nbsp;&nbsp;

**LAWS AND REGULATIONS**  
Much information technology we know and see today requires legal compliance. Many regulations, laws, and guidelines have been implemented over the years to enforce accessibility.  
  
[The Americans with Disabilities Act (ADA)](http://www.ada.gov/ada_intro.htm) prohibited discrimination against people with disabilities. This act was implemented before the Internet was commonplace for people to communicate/ get information.&nbsp;  
  
[Section 508](http://webaim.org/standards/508/checklist) is an amendment to the Rehabilitation Act of 1973, which requires all electronic information presented by federal or government agencies to be accessible to people with disabilities.&nbsp;  
  
The [World](https://www.w3.org/) [Wide Web Consortium (W3C)](https://www.w3.org/) published [WCAG](http://www.w3.org/TR/WCAG10/) [1.0](http://www.w3.org/TR/WCAG10/), which are the web content guidelines for creating accessible websites. [WCAG 2.0](https://www.w3.org/WAI/WCAG20/from10/diff.php) is the latest and updated version.  
  
The [21st](https://www.fcc.gov/guides/21st-century-communications-and-video-accessibility-act-2010)[Century Communications and Video Accessibility Act (CCVA)](https://www.fcc.gov/guides/21st-century-communications-and-video-accessibility-act-2010) requires all videos used for communicating on the web and on mobile devices and all video programming to communicate emergency information to include captioning.  
  
Outside of the U.S., Canada has government [Web Standards](http://www.tbs-sct.gc.ca/ws-nw/index-eng.asp) (previously known as Common Look and Feel Standards). Australia, Ireland, and UK has laws against disability discrimination. The British Standards Institute issued a [Code of Practice for Web Accessibility](https://www.access8878.co.uk/) in 2010. Japan has their web content guidelines under the [Japanese Industrial Standards](https://www.jisc.go.jp/eng/std/index_e.html).   
  
**PLATFORM GUIDELINES &nbsp;**  
If you’re designing or developing for mobile platforms, it’s worth taking a look at each platform’s accessibility guidelines to get a grasp on rules, existing built-in features, and other resources. **&nbsp;**   
  
[iOS Accessibility Guidelines](https://developer.apple.com/accessibility/ios/)  
[iOS Human Interface Guidelines](https://developer.apple.com/technologies/ios/accessibility.html%0A)   
[Android Accessibility Guidelines](https://developer.android.com/guide/topics/ui/accessibility/index.html%0A)  
[Windows Accessibility Guidelines](https://msdn.microsoft.com/en-us/library/windows/apps/hh700407.aspx)   
[IHENI’s Curated List of Mobile Accessibility Resources](http://www.iheni.com/mobile-accessibility-guidelines/)   
  
**PRINCIPLES OF ACCESSIBLE DESIGN&nbsp;**  
These guiding principles defined by the [W3C](http://www.w3.org/WAI/intro/people-use-web/principles) can help us measure the usability of existing content and thus produce new or improved content so that it can be accessed by everyone. Ask yourself these questions as you are designing interfaces.&nbsp;

PERCEIVABLE  
Can the user hear or see the information? Can he do so through the browser or through assistive technologies?&nbsp;  
  
OPERABLE   
Are any of the UI elements interactive? Can the user interact with all controls? If it’s touch, can he navigate to them easily? If on desktop, can he interact with the elements using a mouse, keyboard, or alternative assistive technology?

UNDERSTANDABLE   
Is the information presented easy to understand? Or does it cause more confusion or ambiguity? Does the user understand how to use the app or website? Or is the onboarding/ learning process too long or too tough to handle?   
  
ROBUST   
Can the interface and content be easily interpreted by customized interfaces? By different devices? Or by different operating systems or browsers?  
  
**TOOLS AND SIMULATORS**   
There are many accessibility tools available to test or validate your code or designs. Simulators are also helpful to understand visual implications when creating new designs. Here is a list to get you started.   
  
[W3 HTML/CSS Validator](http://validator.w3.org/)  
[Deque’s Website Accessibility Checklist](http://accessibility.deque.com/website-accessibility-checklist-download)  
[WebAIM Color Contrast Checker](http://webaim.org/resources/contrastchecker/)   
[Firefox Accessibility Evaluation Toolbar](https://addons.mozilla.org/en-US/firefox/addon/accessibility-evaluation-toolb/)  
[Readability Test Tool](http://www.read-able.com/)   
[Color Oracle](http://colororacle.org/)   
[Soft-proofing for colorblindness in Adobe Photoshop CS6](http://help.adobe.com/en_US/creativesuite/cs/using/WS3F71DA01-0962-4b2e-B7FD-C956F8659BB3.html)  
[Color Contrast Analyser](https://www.paciellogroup.com/resources/contrastanalyser/)   
[Luminosity Color Contrast Ratio Analyser](http://juicystudio.com/services/luminositycontrastratio.php)  
[See Chrome Extension](https://chrome.google.com/webstore/detail/see/dkihcccbkkakkbpikjmpnbamkgbjfdcn?hl=en)   
[WebAIM Low Vision Simulation](http://webaim.org/simulations/lowvision)  
[Eye-Sim](http://www.eye-sim.com/)  
[Chromatic Vision Simulator](http://asada.tukusi.ne.jp/cvsimulator/e/)  
[VisionSim App (iOS only)](https://itunes.apple.com/us/app/visionsim-by-braille-institute/id525114829?mt=8)  
  
**BEYOND THE SCREEN&nbsp;**  
In a world of a constant, fast, and fierce technological change, how can we leverage emerging technologies to create accessible products and services? Let’s take a look at how some companies have removed barriers beyond the digital screen to improve people’s lives.   
  
HAPTICS   
[Haptics](https://en.wikipedia.org/wiki/Haptic_technology) is any form of interaction involving touch. Haptic feedback or kinesthetic communication recreates the sense of touch by applying forces, vibrations, or motions.&nbsp;  
  
[TouchFire Keyboard](https://touchfire.com/%0A) is an augmentation of the iPad’s keyboard by providing a raised tactile surface for users to feel and touch.   
  
[The Bradley](https://www.kickstarter.com/projects/eone/the-bradley-a-timepiece-designed-to-touch-and-see) is a watch that you can feel and touch to tell the time. &nbsp;  
  
[Apple Watch](https://support.apple.com/en-us/HT204793%0A) allows users to receive physical cues for notifications using a gentle tap or vibration. Users can adjust the intensity and can also allow audio cues as well.   
  
NAVIGATION   
[Wayfindr](http://www.rlsb.org.uk/campaigns/wayfindr) uses bluetooth beacons and bone conduction headphones to guide users through the subway system.&nbsp;[View the](https://youtu.be/mc3KmbfxuUQ) [Wayfindr video](https://youtu.be/mc3KmbfxuUQ)&nbsp;  
&nbsp;&nbsp;  
[Blind Maps](http://www.fastcodesign.com/1671924/iphone-maps-for-the-blind-using-haptic-tech) is a physical piece that can be attached to the mobile device which offers constantly updated haptic pins basing off of Google Maps navigation.  
  
Automotive and technology companies like Google, Mercedes, BMW, and Tesla are all working on [self-driving cars](http://www.businessinsider.com/report-10-million-self-driving-cars-will-be-on-the-road-by-2020-2015-5), which will be available to the public sooner than we think. Autonomous vehicles benefits everyone needing to drive or use transportation, disabled or not.   
  
VOICE AND AUDIO&nbsp;  
[Apple’](http://www.apple.com/ios/siri/)[s Siri](http://www.apple.com/ios/siri/), [Microsoft](http://www.microsoft.com/en-us/mobile/experiences/cortana/)[’](http://www.microsoft.com/en-us/mobile/experiences/cortana/)[s Cortana](http://www.microsoft.com/en-us/mobile/experiences/cortana/), and [Amazon’s Echo](http://www.amazon.com/dp/B00X4WHP5E) are some examples of voice-activated devices/technology available today to assist users with limited sight or mobility. &nbsp; &nbsp;  
  
Born with achromatopsia (complete color blindness) Neil Harbisson, founder of the [Cyborg Foundation](http://cyborgproject.com/), developed a device that translates colors into sounds called the Eyeborg using cybernetics and audio cues. [View the video about Neil and the Eyeborg](http://vimeo.com/51920182#at=0) &nbsp;  
  
SCIENCE AND HEALTH   
Recently approved by the FDA, the [Bionic Eye: Argus II](http://www.nytimes.com/2013/02/15/health/fda-approves-technology-to-give-limited-vision-to-blind-people.html?_r=0) is a pair of glasses (used in conjunction with surgically implanted electrodes in the eyes) that translates images to light so users may see movement.   
  
**ADDITIONAL READING**   
Here’s some additional articles I found helpful when iterating on projects and sharing out design rationale. We should all aim to reduce customer pain by creating better legibility and readability. Pay attention to type case, color contrast, use of white space, link colors or animations.   
  
[Legibility and Readability](http://www.designyourway.net/drb/legibility-and-readability-principles-that-shouldnt-be-ignored-when-designing/)  
[Color Contrast for Better Readability](https://viget.com/inspire/color-contrast)  
[WCAG 2.0: A/AA/AAA Compliance](http://www.inqbation.com/wcag-2-0-level-a-aa-aaa-versus-section-508-compliance/)

**Post Edit:**   
Thank you so much attending!! Your participation, enthusiasm, and passion for learning more about and practicing accessible design totally made my day.&nbsp;  
[DOWNLOAD SLIDES HERE](https://www.dropbox.com/s/qppb7m9sbk7kxxn/2015_ghc_accessibility_v04.pdf?dl=0)  
  
Stay in touch!&nbsp;
