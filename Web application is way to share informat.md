












I. Introduction:

Now a days web and mobile Apps are become an important part of everyone's life and it plays crutial role in order to ease their day to day tasks. But the problem infront of software stakeholders is that they have to build both native apps for accessing it in mobile and Web-based apps for accessing it via Desktop for delivering the same features
and functionalities to endusers. The hardest problem with software is distribution anyone who's ever worked in IT understand this. How does it play on mobile is the 
must question it's true that most of the time people spend their time in native apps, Re-engaging features of native apps keeps user in apps, Notifications brings user back even when app is closed and home screen icon aslo maitains visibility. And advantage of web-based app is that it can be accessed by typing URL on web this is power of URL, we did not need to install a app to access the web-app while it provide same and features and functionalities. Now, the web has been perceived as safer and more respectful of privacy, but it doesn't have those native features. To have both this features on a single technology platform we may go towards Progressive Web Apps(PWA). so a progressive web application (PWA), commonly known as a progressive web app, is a type of application software delivered through the web, built using common web technologies including HTML, CSS, JavaScript, and WebAssembly. It is intended to work on any platform that uses a standards-compliant browser, including both desktop and mobile devices. This concept firstly presented by google developer with the vision of “build better experiences across devices and contexts within a single codebase” as before this time we needed different multiple codebases to create beautiful apps. So to provide good, fast and economical software products several web frameworks were created. To choose best of all framework (currently present in world like React, Angular, svelte, Vue, etc.) especially for progressive web apps is the challenge.
so we've discussed in this paper about how svelte is good for PWAs.


II. Prelimanaries:
A short review on features of PWA and Svelte and sveltekit frameworks for developing PWA.


A. Features of PWA:

Before we buidling our pwa, let’s take look closer at how PWAs work. The following two features work in conjunction with progressive webnenhancement to create an experience similar to native apps. Service workers act as intermediaries or proxies for web applications, enabling the use of caching resources and handling poor internet connections gracefully.For example, when internet connection is lost, we may use a service worker to display a message to a user so that the app does not crash suddenly. Similarly, a service worker may cause our app to save local activity and resync after regaining internet connection. Web manifests enable users to download or install apps on specific platforms. The app that the user sees in the browser can be run offline or in a state similar to a native implementation. Although manifests are still considered as experimental and also they are heavily supported by all modern browsers.

B. Svelte:

Svelte is new approach for building user interface. where in traditional frameworks like react and Vue do there many of work in the browser, svelte shifts that work into the one step that happens when you basically build your app instead using techniques Like DOM Virtual diffing, svelte writes code that continuously updates the DOM when the state of your app can changes. we are proudful that svelte was recently voted for the most loved web framework with the most of satisfied developers in a pairs of survey which can conducted by industry. According to me svelte is very lovable framework for developers. for constantly updates we should look at the blogs and the post of Svelte is widely praised by developers. Taking the top ranking in multiple large scale developer surveys, it was chosen as the Stack Overflow 2021 most loved web framework and 2020 State of JS frontend framework with the most satisfied developers.Svelte has been the adopted by most of a high-profile web companies including The New York Times, Apple, Spotify, Elasticrun ,Rakuten, Reuters, Ikea, Facebook, the community of svelte is very helpful for nonmaintainers to run the svelte in summit conference writing a newsletter for the svelte, hosting the podcasts for svelte and host directory for tooling, templates and components of svelte.


C. what is Sveletkit:

SvelteKit is a framework for building extremely high-performance web apps and PWA's. Buiding an app with all the modern features and best practices is complicated task. those practices and features includes build optimizations, so that help us to load only the minimal required code;offline support;re-engaging feature;push notifications;and configurable rendering that allows us to generate HTML on the server or in the browser at runtime or at built-time.Sveltekit is taken care of this boring stuff for you can focus on creative part. It uses Vite server  with a Svelte plugin which provide feature-rich and lighting-fast development experience with HOT MODULE REPLACEMENT(HMR), where any changes made in your code are being reflected in the browser instantly.With the help of sveltekit we can efficiently build PWA's.



III. CASE STUDY 

A. When should use PWA?

The hardest problem with software is distribution and anyone who've ever worked in IT industry may understand this.It is true that most of time people spend most of their time in native apps. Re-engaging features keeps user in apps, notification brings user back even when app is closed and home screen icon maintain visibility But usage is concentrated. It's a winner take over all situation. App developers often spend more for distribution than they actually earn back. so if the native ecosystem isn't going so well, why hasn't the web been even more distrutive? well, here's one way to think of the differences between web and native capabilities access. native apps have the ability to startup fast and reliability they can work offline and use push, sync, sensors and so on.

Now , the web has been perceived as safer and more respectful of privacy,but it doesn't have those native features. if we add another access,reach, you can see where the web succeeds, google data shows that mobile users visit around 100 sites per month. this is the power of url's. they meets one-off needs.But what if the web could meets those user expectations? this is what progressive web apps represents,PWA for short. web apps are finally able to earn their place on the home screen and in the notification tray and they doesn't have to give up on reach. so what was missing from the web. well, first we needed realibility and performance on par with native apps. next we needed to be in notification tray and lastly for being trustworthy apps we needed to be on the home screen. so now let's talk about performance well all time is money and this data shows just how badly bounce rate increases with load time. other studies shows that after just 3 seconds, 40% of users will abandon of website. but what if you didn't need to traverse the network everytime for every asset ? what if you intelligently cache locally reliably ? well that what service workers do. service workers enables you to implement caching with the cache API, not just by hoping to rely on browser caching. this means that after the first visit, sites and apps can be reliably fast. well, that's huge but what about the first visit ? the AMP project from google search team was built to address the web obesity epidemic and provides reliably fast web components for first load. These AMP Components can be much faster to load and less-data hungry than non-amp content. well, what if you could combining AMP and service worker this is were AMP meets PWA. So do you want to try out progressive web apps ? well great tools built into the chrome protocols for PWA developers, Google engineers have created lighthouse. this reports on how well your site or app is doing in terms of performance, security, accessibilty, SEO , and PWA features. You also get command line tools you can build into your workflow and production processes. so to sum up, PWA are 

1. Reliable : fast loading, work offline and flasky network.
2. Fast : soomth, animation jank free scrolling and seamless navigation. 
3. Engaging : Launched from home screen and send push notification.

we've been really excited to see incredible momentum across the globe here's a sample of folks shipping or actively working on PWA and now web API's  with these early adopeters, we've seen that every site has their own way of investing in mobile web and starting down the path towards progressive web apps.









