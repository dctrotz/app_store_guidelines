#2017
#App Store Review Guidelines

##Introduction

Apps are changing the world, enriching people’s lives, and enabling developers like you to innovate like never before. As a result, the App Store has grown into an exciting and vibrant ecosystem for millions of developers and more than a billion users. Whether you are a first time developer or a large team of experienced programmers, we are excited that you are creating apps for the App Store and want to help you understand our guidelines so you can be confident your app will get through the review process quickly.

The guiding principle of the App Store is simple - we want to provide a safe experience for users to get apps and a great opportunity for all developers to be successful. We have updated the App Review Guidelines with that principle in mind. The guidelines themselves haven’t changed, but they are better organized and provide more context. On the following pages you will find guidelines arranged into five clear sections: Safety, Performance, Business, Design, and Legal. A few other points to keep in mind:

- We have lots of kids downloading lots of apps. Parental controls work great to protect kids, but you have to do your part too. So know that we’re keeping an eye out for the kids.
- The App Store is a great way to reach hundreds of millions of people around the world. If you build an app that you just want to show to family and friends, the App Store isn’t the best way to do that. Consider Ad Hoc distribution or the Enterprise Program. If you’re just getting started, learn more about the Apple Developer Program.
- We strongly support all points of view being represented on the App Store, as long as the apps are respectful to users with differing opinions and the quality of the app experience is great. We will reject apps for any content or behavior that we believe is over the line. What line, you ask? Well, as a Supreme Court Justice once said, “I’ll know it when I see it”. And we think that you will also know it when you cross it.
- If you attempt to cheat the system (for example, by trying to trick the review process, steal user data, copy another developer’s work, or manipulate ratings) your apps will be removed from the store and you will be expelled from the Developer Program.

We hope these new guidelines help you sail through the App Review process, and that approvals and rejections are more consistent across the board. This is a living document; new apps presenting new questions may result in new rules at any time. Perhaps your app will trigger this. We love this stuff too, and honor what you do. We’re really trying our best to create the best platform in the world for you to express your talents and make a living, too.

##Before You Submit

To help your app approval go as smoothly as possible, review the common missteps listed below that can slow down the review process or trigger a rejection. This doesn’t replace the guidelines or guarantee approval, but making sure you can check every item on the list is a good start. If your app no longer functions as intended or you’re no longer actively supporting it, it will be removed from the App Store. Learn more about App Store Improvements.

Make sure you:

- Test your app for crashes and bugs
- Ensure that all app information and metadata is complete and accurate
- Update your contact information in case App Review needs to reach you
- Provide an active demo account and login information, plus any other hardware or resources that might be needed to review your app (e.g. login credentials or a sample QR code)
- Enable backend services so that they’re live and accessible during review
- Include detailed explanations of non-obvious features and in-app purchases in the App Review notes, including supporting documentation where appropriate. If we’re not able to access part of your app because it’s geo-locked or otherwise restricted, provide a link to a video of the functionality
- Check whether your app follows guidance in other documentation, such as:

###Development Guidelines

- App Programming Guide
- App Extension Programming Guide
- iOS Data Storage Guidelines
- macOS File System Documentation
- Safari Extensions Development Guide
- iTunes Connect Developer Help

###Design Guidelines

- iOS Human Interface Guidelines
- macOS Human Interface Guidelines
- tvOS Human Interface Guidelines
- watchOS Human Interface Guidelines
- Brand and Marketing Guidelines
- App Store Marketing Guidelines
- Apple Pay Identity Guidelines
- Add to Apple Wallet Guidelines
- Guidelines for Using Apple Trademarks and Copyrights

##1. Safety

When people install an app from the App Store, they want to feel confident that it’s safe to do so—that the app doesn’t contain upsetting or offensive content, won’t damage their device, and isn’t likely to cause physical harm from its use. We’ve outlined the major pitfalls below, but if you’re looking to shock and offend people, the App Store isn’t the right place for your app.

###1.1 Objectionable Content

Apps should not include content that is offensive, insensitive, upsetting, intended to disgust, or in exceptionally poor taste. Examples of such content include:

**1.1.1** Defamatory, discriminatory, or mean-spirited content, including references or commentary about religion, race, sexual orientation, gender, national/ethnic origin, or other targeted groups, particularly if the app is likely to humiliate, intimidate, or place a targeted individual or group in harm’s way. Professional political satirists and humorists are generally exempt from this requirement.

**1.1.2** Realistic portrayals of people or animals being killed, maimed, tortured, or abused, or content that encourages violence. “Enemies” within the context of a game cannot solely target a specific race, culture, real government, corporation, or any other real entity.

**1.1.3** Depictions that encourage illegal or reckless use of weapons and dangerous objects, or facilitate the purchase of firearms.

**1.1.4** Overtly sexual or pornographic material, defined by Webster’s Dictionary as "explicit descriptions or displays of sexual organs or activities intended to stimulate erotic rather than aesthetic or emotional feelings."

**1.1.5** Inflammatory religious commentary or inaccurate or misleading quotations of religious texts.

**1.1.6** False information and features, including inaccurate device data or trick/joke functionality, such as fake location trackers. Stating that the app is “for entertainment purposes” won’t overcome this guideline. Apps that enable anonymous or prank phone calls or SMS/MMS messaging will be rejected.

**1.1.7 App Store Reviews:**

- App Store customer reviews can be an integral part of the app experience, so you should treat customers with respect when responding to their comments. Keep your responses targeted to the user’s comments and do not include personal information, spam, or marketing in your response.
- Use the provided API to prompt users to review your app; this functionality allows customers to provide an App Store rating and review without the inconvenience of leaving your app, and we will disallow custom review prompts.

###1.2 User Generated Content

Apps with user-generated content present particular challenges, ranging from intellectual property infringement to anonymous bullying. To prevent abuse, apps with user-generated content or social networking services must include:

- A method for filtering objectionable material from being posted to the app
- A mechanism to report offensive content and timely responses to concerns
- The ability to block abusive users from the service
- Published contact information so users can easily reach you

Apps with user-generated content or services that end up being used primarily for pornographic content, objectification of real people (e.g. “hot-or-not” voting), making physical threats, or bullying do not belong on the App Store and may be removed without notice. If your app includes user-generated content from a web-based service, it may display incidental mature “NSFW” content, provided that the content is hidden by default and only displayed when the user turns it on via your website.

###1.3 Kids Category

The Kids Category is a great way for people to easily find apps that are appropriate for children. If you want to participate in the Kids Category, you should focus on creating a great experience specifically for younger users. These apps must not include links out of the app, purchasing opportunities, or other distractions to kids unless reserved for a designated area behind a parental gate. Keep in mind that once customers expect your app to follow the Kids Category requirements, it will need to continue to meet these guidelines in subsequent updates, even if you decide to deselect the category. Learn more about parental gates.

Apps in the Kids Category may not include behavioral advertising (e.g. the advertiser may not serve ads based on the user’s activity), and any contextual ads must be appropriate for young audiences. You should also pay particular attention to privacy laws around the world relating to the collection of data from children online. Be sure to review the Privacy section of these guidelines for more information.

###1.4 Physical Harm

If your app behaves in a way that risks physical harm, we may reject it. For example:

**1.4.1** Medical apps that could provide inaccurate data or information, or that could be used for diagnosing or treating patients may be reviewed with greater scrutiny.

- Apps must clearly disclose data and methodology to support accuracy claims relating to health measurements, and if the level of accuracy or methodology cannot be validated, we will reject your app. For example, apps that claim to take x-rays, measure blood pressure, body temperature, blood glucose levels, or blood oxygen levels using only the sensors on the device are not permitted.
- Apps should remind users to check with a doctor in addition to using the app and before making medical decisions.

If your medical app has received regulatory clearance, please submit a link to that documentation with your app.

**1.4.2** Drug dosage calculators must come from the drug manufacturer, a hospital, university, health insurance company, pharmacy or other approved entity, or receive approval by the FDA or one of its international counterparts. Given the potential harm to patients, we need to be sure that the app will be supported and updated over the long term.

**1.4.3** Apps that encourage consumption of tobacco products, illegal drugs, or excessive amounts of alcohol are not permitted on the App Store. Apps that encourage minors to consume any of these substances will be rejected. Facilitating the sale of marijuana, tobacco, or controlled substances (except for licensed pharmacies) isn’t allowed.

**1.4.4** Apps may only display DUI checkpoints that are published by law enforcement agencies, and should never encourage drunk driving or other reckless behavior such as excessive speed.

**1.4.5** Apps should not urge customers to use their devices in a way that contradicts safety documentation for Apple hardware, risking damage to the device or physical harm to people. For example, apps should not encourage placing the device under a mattress or pillow while charging or perform excessive write cycles to the solid state drive. Review device documentation.

###1.5 Developer Information

People need to know how to reach you with questions and support issues. Make sure your Support URL includes an easy way to reach you. Failure to include accurate and up-to-date contact information not only frustrates customers, but may violate the law in some countries. Also ensure that Wallet passes include valid contact information from the issuer and are signed with a dedicated certificate assigned to the brand or trademark owner of the pass.

##2. Performance

###2.1 App Completeness

Submissions to App Review, including apps you make available for pre-order, should be final versions with all necessary metadata and fully functional URLs included; placeholder text, empty websites, and other temporary content should be scrubbed before submission. Make sure your app has been tested on-device for bugs and stability before you submit it, and include demo account info (and turn on your back-end service!) if your app includes a login. If you offer in-app purchases in your app, make sure they are complete, up-to-date, and visible to the reviewer, or that you explain why not in your review notes. Please don’t treat App Review as a software testing service. We will reject incomplete app bundles and binaries that crash or exhibit obvious technical problems.

###2.2 Beta Testing

Demos, betas, and trial versions of your app don’t belong on the App Store – use TestFlight instead. Any app submitted for beta distribution via TestFlight should be intended for public distribution and should comply with the App Review Guidelines. Note, however, that apps using TestFlight cannot be distributed to testers in exchange for compensation of any kind, including as a reward for crowd-sourced funding. Significant updates to your beta build should be submitted to TestFlight App Review before being distributed to your testers. To learn more, visit the TestFlight Beta Testing.

###2.3 Accurate Metadata

Customers should know what they’re getting when they download or buy your app, so make sure your app description, screenshots, and previews accurately reflect the app’s core experience and remember to keep them up-to-date with new versions.

**2.3.1** Don’t include any hidden or undocumented features in your app; your app’s functionality should be clear to end-users and App Review. Similarly, you should not market your app on the App Store or offline as including content or services that it does not actually offer (e.g. iOS-based virus and malware scanners). Egregious or repeated behavior is grounds for removal from the Developer Program. We work hard to make the App Store a trustworthy ecosystem and expect our app developers to follow suit; if you’re dishonest, we don’t want to do business with you.

**2.3.2** If your app includes in-app purchases, make sure your app description, screenshots, and previews clearly indicate whether any featured items, levels, subscriptions, etc. require additional purchases. If you decide to promote in-app purchases on the App Store, ensure that the in-app purchase Display Name, Screenshot and Description are appropriate for a public audience, that you follow the guidance found in Promoting Your In-App Purchases, and that your app properly handles the SKPaymentTransactionObserver method so that customers can seamlessly complete the purchase when your app launches.

**2.3.3** Screenshots should show the app in use, and not merely the title art, log-in page, or splash screen. They may also include text and image overlays (e.g. to demonstrate input mechanisms, such as an animated touch point or Apple Pencil) and show extended functionality on device, such as Touch Bar.

**2.3.4** Previews are a great way for customers to see what your app looks like and what it does. To ensure people understand what they’ll be getting with your app, previews may only use video screen captures of the app itself. Stickers and iMessage extensions may show the user experience in the Messages app. You can add narration and video or textual overlays to help explain anything that isn’t clear from the video alone.

**2.3.5** Select the most appropriate category for your app, and check out the App Store Category Definitions if you need help. If you’re way off base, we may change the category for you.

**2.3.6** Answer the age rating questions in iTunes Connect honestly so that your app aligns properly with parental controls. If your app is mis-rated, customers might be surprised by what they get, or it could trigger an inquiry from government regulators.

**2.3.7** Choose a unique app name, assign keywords that accurately describe your app, and don’t try to pack any of your metadata with trademarked terms, popular app names, or other irrelevant phrases just to game the system. App names must be limited to 30 characters and should not include prices, terms, or descriptions that are not the name of the app. App subtitles are a great way to provide additional context for your app; they must follow our standard metadata rules and should not include inappropriate content, reference other apps, or make unverifiable product claims. Apple may modify inappropriate keywords at any time.

**2.3.8** Metadata should be appropriate for all audiences, so make sure your app and in-app purchase icons, screenshots, and previews adhere to a 4+ age rating even if your app is rated higher. For example, if your app is a game that includes violence, select images that don’t depict a gruesome death or a gun pointed at a specific character. Use of terms like “For Kids” and “For Children” in app metadata is reserved for the Kids Category. Remember to ensure your metadata, including app name and icons (small, large, Apple Watch app, alternate icons, etc.), are similar to avoid creating confusion.

**2.3.9** You are responsible for securing the rights to use all materials in your app icons, screenshots, and previews, and you should display fictional account information instead of data from a real person.

**2.3.10** Make sure your app is focused on the iOS, Mac, Apple TV or Apple Watch experience, and don’t include names, icons, or imagery of other mobile platforms in your app or metadata, unless there is specific, approved interactive functionality.

**2.3.11** Apps you submit for pre-order on the App Store must be complete and deliverable as submitted. Ensure that the app you ultimately release is not materially different from what you advertise while the app is in a pre-order state. If you make material changes to the app (e.g. change business models), you should restart your pre-order sales.

###2.4 Hardware Compatibility

**2.4.1** To ensure people get the most out of your app, iPhone apps should run on iPad whenever possible. We encourage you to consider building universal apps so customers can use them on all of their devices. Learn more about Universal apps.

**2.4.2** Design your app to use power efficiently. Apps should not rapidly drain battery, generate excessive heat, or put unnecessary strain on device resources.

**2.4.3** People should be able to use your Apple TV app without the need for hardware inputs beyond the Siri remote or third party game controllers, but feel free to provide enhanced functionality when other peripherals are connected. If you require a game controller, make sure you clearly explain that in your metadata so customers know they need additional equipment to play.

**2.4.4** Apps should never suggest or require a restart of the device.

**2.4.5** Apps distributed via the Mac App Store have some additional requirements to keep in mind:

**(i)** They must be appropriately sandboxed, and follow macOS File System Documentation. They should also only use the appropriate macOS APIs for modifying user data stored by other Apps (e.g. bookmarks, Address Book, or Calendar entries).

**(ii)** They must be packaged and submitted using technologies provided in Xcode; no third party installers allowed. They must also be self-contained, single application installation bundles and cannot install code or resources in shared locations.

**(iii)** They may not auto-launch or have other code run automatically at startup or login without consent nor spawn processes that continue to run without consent after a user has quit the app. They should not automatically add their icons to the Dock or leave short cuts on the user desktop.

**(iv)** They may not download or install standalone apps, kexts, additional code, or resources to add functionality or significantly change the app from what we see during the review process.

**(v)** They may not request escalation to root privileges or use setuid attributes.

**(vi)** They may not present a license screen at launch, require license keys, or implement their own copy protection.

**(vii)** They must use the Mac App Store to distribute updates; other update mechanisms are not allowed.

**(viii)** Apps should run on the currently shipping OS and may not use deprecated or optionally installed technologies (e.g. Java, Rosetta)

**(ix)** Apps must contain all language and localization support in a single app bundle.

###2.5 Software Requirements

**2.5.1** Apps may only use public APIs and must run on the currently shipping OS. Learn more about public APIs. Keep your apps up-to-date and make sure you phase out any deprecated features, frameworks or technologies that will no longer be supported in future versions of an OS. Apps should use APIs and frameworks for their intended purposes and indicate that integration in their app description. For example, the HomeKit framework should provide home automation services; and HealthKit should be used for health and fitness purposes and integrate with the Health app.

**2.5.2** Apps should be self-contained in their bundles, and may not read or write data outside the designated container area, nor may they download, install, or execute code, including other apps. Educational apps designed to teach, develop, or allow students to test executable code may, in limited circumstances, download code provided that such code is not used for other purposes. Such apps must make the source code provided by the Application completely viewable and editable by the user.

**2.5.3** Apps that transmit viruses, files, computer code, or programs that may harm or disrupt the normal operation of the operating system and/or hardware features, including Push Notifications and Game Center, will be rejected. Egregious violations and repeat behavior will result in removal from the Developer Program.

**2.5.4** Multitasking apps may only use background services for their intended purposes: VoIP, audio playback, location, task completion, local notifications, etc. If your app uses location background mode, include a reminder that doing so may dramatically decrease battery life.

**2.5.5** We will be reviewing on an IPv6 network, so if your app isn’t compatible with the IPv6 addressing, it may fail during review.

**2.5.6** Apps that browse the web must use the appropriate WebKit framework and WebKit Javascript.

**2.5.7** Video streaming content over a cellular network longer than 10 minutes must use HTTP Live Streaming and include a baseline 192 kbps HTTP Live stream.

**2.5.8** Apps that create alternate desktop/home screen environments or simulate multi-app widget experiences will be rejected.

**2.5.9** Apps that alter or disable the functions of standard switches, such as the Volume Up/Down and Ring/Silent switches, or other native user interface elements or behaviors will be rejected. For example, apps should not block links out to other apps or other features that users would expect to work a certain way. Learn more about proper handling of links.

**2.5.10** Apps should not be submitted with empty ad banners or test advertisements.

**2.5.11** SiriKit

**(i)** Apps integrating SiriKit should only sign up for intents they can handle without the support of an additional app and that users would expect from the stated functionality. For example, if your app is a meal planning app, you should not incorporate an intent to start a workout, even if the app shares integration with a fitness app.

**(ii)** Ensure that the vocabulary and phrases in your plist pertains to your app and the SiriKit functionality of the intents the app has registered for. Aliases must relate directly to your app or company name and should not be generic terms or include third party app names or services.

**(iii)** Resolve the Siri request in the most direct way possible and do not insert ads or other marketing between the request and its fulfillment. Only present interstitial UI when required to complete the task (e.g. asking the user to specify a particular type of workout).

**2.5.12** Apps using CallKit or including an SMS Fraud Extension should only block phone numbers that are confirmed spam. Apps that include call-, SMS-, and MMS- blocking functionality or spam identification must clearly identify these features in their marketing text and explain the criteria for their blocked and spam lists. You may not use the data accessed via these tools for any purpose not directly related to operating or improving your app or extension (e.g. you may not use, share, or sell it for tracking purposes, creating user profiles, etc.)

**2.5.13** Apps using facial recognition for account authentication must use LocalAuthentication (and not ARKit or other facial recognition technology), and must use an alternate authentication method for users under 13 years old.

##3. Business

There are many ways to monetize your app on the App Store. If your business model isn’t obvious, make sure to explain in its metadata and App Review notes. If we can’t understand how your app works or your in-app purchases aren’t immediately obvious, it will delay your review and may trigger a rejection. And while pricing is up to you, we won’t distribute apps and in-app purchase items that are clear rip-offs. We’ll reject expensive apps that try to cheat users with irrationally high prices.

If we find that you have attempted to manipulate reviews, inflate your chart rankings with paid, incentivized, filtered, or fake feedback, or engage with third party services to do so on your behalf, we will take steps to preserve the integrity of the App Store, which may include expelling you from the Developer Program.


###3.1 Payments

**3.1.1 In-App Purchase:**

- If you want to unlock features or functionality within your app, (by way of example: subscriptions, in-game currencies, game levels, access to premium content, or unlocking a full version), you must use in-app purchase. Apps may use in-app purchase currencies to enable customers to “tip” digital content providers in the app. Apps and their metadata may not include buttons, external links, or other calls to action that direct customers to purchasing mechanisms other than in-app purchase.
- Any credits or in-game currencies purchased via in-app purchase may not expire, and you should make sure you have a restore mechanism for any restorable in-app purchases.
- Remember to assign the correct purchasability type or your app will be rejected.
- Apps should not directly or indirectly enable gifting of in-app purchase content, features, or consumable items to others.
- Apps distributed via the Mac App Store may host plug-ins or extensions that are enabled with mechanisms other than the App Store.
- Apps offering “loot boxes” or other mechanisms that provide randomized virtual items for purchase must disclose the odds of receiving each type of item to customers prior to purchase.

**3.1.2 Subscriptions:** Apps may offer auto-renewing in-app purchase subscriptions, regardless of category on the App Store. When incorporating auto-renewable subscriptions into your app, be sure to follow the guidelines below.

**3.1.2(a) Permissible uses:** If you offer an auto-renewing subscription, you must provide ongoing value to the customer, and the subscription period must last at least seven days and be available across all of the user’s devices. While the following list is not exhaustive, examples of appropriate subscriptions include: new game levels; episodic content; multi-player support; apps that offer consistent, substantive updates; access to large collections of, or continually updated, media content; software as a service (“SAAS”); and cloud support. In addition:

- Subscriptions may be offered alongside a la carte offerings (e.g. you may offer a subscription to an entire library of films as well the purchase or rental of a single movie).
- You may offer a single subscription that is shared across your own apps and services, but these subscriptions may not extend to third party apps or services. Games offered in a game subscription must be owned or exclusively licensed by the developer (e.g. not part of a game publishing platform). Each game must be downloaded directly from the App Store, must be designed to avoid duplicate payment by a subscriber, and should not disadvantage non-subscriber customers.
- Subscriptions must work on all of the user’s devices where the app is available. Learn more about sharing a subscription across your apps.
- Apps must not force users to rate the app, review the app, download other apps, or other similar actions in order to access functionality, content, or use of the app.
- As with all apps, those offering subscriptions should allow a user to get what they’ve paid for without performing additional tasks, such as posting on social media, uploading contacts, checking in to the app a certain number of times, etc.
- Subscriptions may include consumable credits, gems, in-game currencies, etc., and you may offer subscriptions that include access to discounted consumable goods (e.g. a platinum membership that exposes gem-packs for a reduced price).
- If you are changing your existing app to a subscription-based business model, you should not take away the primary functionality existing users have already paid for. For example, let customers who have already purchased a “full game unlock” continue to access the full game after you introduce a subscription model for new customers.

**3.1.2(b) Upgrades and Downgrades:** Users should have a seamless upgrade/downgrade experience and should not be able to inadvertently subscribe to multiple variations of the same thing. Review best practices on managing your subscription upgrade and downgrade options.

**3.1.2(c) Subscription Information:** Before asking a customer to subscribe, you should clearly describe what the user will get for the price. How many issues per month? How much cloud storage? What kind of access to your service? Also ensure you clearly communicate the requirements described in Schedule 2 of your agreement in Agreements, Tax, and Banking.

**3.1.3 “Reader” Apps:** Apps may allow a user to access previously purchased content or content subscriptions (specifically: magazines, newspapers, books, audio, music, video, access to professional databases, VoIP, cloud storage, and approved services such as educational apps that manage student grades and schedules), as well as consumable items in multi-platform games, provided that you agree not to directly or indirectly target iOS users to use a purchasing method other than in-app purchase, and your general communications about other purchasing methods are not designed to discourage use of in-app purchase.

**3.1.4 Content Codes:** Apps may not use their own mechanisms to unlock content or functionality, such as license keys, augmented reality markers, QR codes, etc. In limited circumstances, such as when features are dependent upon specific hardware to function, the app may unlock that functionality without using in-app purchase (e.g. an astronomy app that adds features when synced with a telescope). App features that work in combination with an approved physical product (such as a toy) on an optional basis may unlock functionality without using in-app purchase, provided that an in-app purchase option is available as well. You may not, however, require users to purchase unrelated products or engage in advertising or marketing activities to unlock app functionality.

**3.1.5(a) Physical Goods and Services Outside of the App:** If your app enables people to purchase goods or services that will be consumed outside of the app, you must use purchase methods other than in-app purchase to collect those payments, such as Apple Pay or traditional credit card entry.

**3.1.5(b) Cryptocurrencies:** Apps may facilitate transmission of approved virtual currencies (e.g. Bitcoin, DogeCoin) provided that they do so in compliance with all state and federal laws for the territories in which the app functions. Apps facilitating Initial Coin Offerings (“ICOs”), cryptocurrency futures trading, and other crypto-securities or quasi-securities trading must come from established banks, securities firms, futures commission merchants (“FCM”), or other approved financial institutions and must comply with all applicable law.

**3.1.6 Apple Pay:** Apps using Apple Pay must provide all material purchase information to the user prior to sale of any good or service and must use Apple Pay branding and user interface elements correctly, as described in the Apple Pay Identity Guidelines and Human Interface Guidelines. Apps using Apple Pay to offer recurring payments must, at a minimum, disclose the following information:

- The length of the renewal term and the fact that it will continue until canceled
- What will be provided during each period
- The actual charges that will be billed to the customer
- How to cancel

###3.2 Other Business Model Issues

The lists below are not exhaustive, and your submission may trigger a change or update to our policies, but here are some additional do’s and don’ts to keep in mind:

**3.2.1** Acceptable

**(i)** Displaying your own apps for purchase or promotion within your app, provided the app is not merely a catalog of your apps.

**(ii)** Displaying or recommending a collection of third party apps that are designed for a specific approved need (e.g. health management, aviation, accessibility). Your app should provide robust editorial content so that it doesn’t seem like a mere storefront.

**(iii)** Disabling access to specific approved rental content (e.g. films, television programs, music, books) after the rental period has expired; all other items and services may not expire.

**(iv)** Wallet passes can be used to make or receive payments, transmit offers, or offer identification (such as movie tickets, coupons, and VIP credentials). Other uses may result in the rejection of the app and the revocation of Wallet credentials.

**(v)** Insurance apps must be free, in legal-compliance in the regions distributed, and cannot use in-app purchase.

**(vi)** Approved nonprofits may fundraise directly within their own apps or third-party apps, provided those fundraising campaigns adhere to all App Review Guidelines and offer Apple Pay support. These apps must disclose how the funds will be used, abide by all required local and federal laws, and ensure appropriate tax receipts are available to donors. Additional information shall be provided to App Review upon request. Nonprofit platforms that connect donors to other nonprofits must ensure that every nonprofit listed in the app has also gone through the nonprofit approval process. Learn more about becoming an approved nonprofit.

**(vii)** Apps may enable individual users to give a monetary gift to another individual without using in-app purchase, provided that (a) the gift is a completely optional choice by the giver, and (b) 100% of the funds go to the receiver of the gift. However, a gift that is connected to or associated at any point in time with receiving digital content or services must use in-app purchase.

**(viii)** Apps used for financial trading, investing, or money management should come from the financial institution performing such services or must use a public API offered by the institution in compliance with its Terms & Conditions.

**3.2.2** Unacceptable

**(i)** Creating an interface for displaying third party apps, extensions, or plug-ins similar to the App Store or as a general-interest collection.

**(ii)** Monetizing built-in capabilities provided by the hardware or operating system, such as Push Notifications, the camera, or the gyroscope; or Apple services, such as Apple Music access or iCloud storage.

**(iii)** Artificially increasing the number of impressions or click-throughs of ads, as well as apps that are designed predominantly for the display of ads.

**(iv)** Unless you are an approved nonprofit or otherwise permitted under Section 3.2.1 (vi) above, collecting funds within the app for charities and fundraisers. Apps that seek to raise money for such causes must be free on the App Store and may only collect funds outside of the app, such as via Safari or SMS.

**(v)** Arbitrarily restricting who may use the app, such as by location or carrier.

**(vi)** Apps should allow a user to get what they’ve paid for without performing additional tasks, such as posting on social media, uploading contacts, checking in to the app a certain number of times, etc. Apps should not require users to rate the app, review the app, watch videos, download other apps, tap on advertisements, or take other similar actions in order to access functionality, content, use the app, or receive monetary or other compensation.

**(vii)** Artificially manipulating a user’s visibility, status, or rank on other services unless permitted by that service’s Terms and Conditions.

**(viii)** Apps that facilitate binary options trading are not permitted on the App Store. Consider a web app instead. Apps that facilitate trading in contracts for difference (“CFDs”) or other derivatives (e.g. FOREX) must be properly licensed in all jurisdictions where the service is available.

##4. Design

Apple customers place a high value on products that are simple, refined, innovative, and easy to use, and that’s what we want to see on the App Store. Coming up with a great design is up to you, but the following are minimum standards for approval to the App Store. And remember that even after your app has been approved, you should update your app to ensure it remains functional and engaging to new and existing customers. Apps that stop working or offer a degraded experience may be removed from the App Store at any time.

###4.1 Copycats

Come up with your own ideas. We know you have them, so make yours come to life. Don’t simply copy the latest popular app on the App Store, or make some minor changes to another app’s name or UI and pass it off as your own. In addition to risking an intellectual property infringement claim, it makes the App Store harder to navigate and just isn’t fair to your fellow developers.

###4.2 Minimum Functionality

Your app should include features, content, and UI that elevate it beyond a repackaged website. If your app is not particularly useful, unique, or “app-like,” it doesn’t belong on the App Store. If your App doesn't provide some sort of lasting entertainment value, or is just plain creepy, it may not be accepted. Apps that are simply a song or movie should be submitted to the iTunes Store. Apps that are simply a book or game guide should be submitted to the iBooks Store.

**4.2.1** Apps using ARKit should provide rich and integrated augmented reality experiences; merely dropping a model into an AR view or replaying animation is not enough.

**4.2.2** Other than catalogs, apps shouldn’t primarily be marketing materials, advertisements, web clippings, content aggregators, or a collection of links.

**4.2.3** Your app should work on its own without requiring installation of another app to function.

**4.2.4** Apple Watch apps that appear to be a watch face are confusing, because people will expect them to work with device features such as swipes, notifications, and third party complications. Creative ways of expressing time as an app interface is great (say, a tide clock for surfers), but if your app comes too close to resembling a watch face, we will reject it.

**4.2.5** Apps that are primarily iCloud and iCloud Drive file managers need to include additional app functionality to be approved.

**4.2.6** Apps created from a commercialized template or app generation service will be rejected unless they are submitted directly by the provider of the app’s content. These services should not submit apps on behalf of their clients and should offer tools that let their clients create customized, innovative apps that provide unique customer experiences. Another acceptable option for template providers is to create a single binary to host all client content in an aggregated or “picker” model, for example as a restaurant finder app with separate customized entries or pages for each client restaurant, or as an event app with separate entries for each client event.

###4.3 Spam

Don’t create multiple Bundle IDs of the same app. If your app has different versions for specific locations, sports teams, universities, etc., consider submitting a single app and provide the variations using in-app purchase. Also avoid piling on to a category that is already saturated; the App Store has enough fart, burp, flashlight, and Kama Sutra apps already. Spamming the store may lead to your removal from the Developer Program.

###4.4 Extensions

Apps hosting or containing extensions must comply with the App Extension Programming Guide or the Safari Extensions Development Guide and should include some functionality, such as help screens and settings interfaces where possible. You should clearly and accurately disclose what extensions are made available in the app’s marketing text, and the extensions may not include marketing, advertising, or in-app purchases.

**4.4.1** Keyboard extensions have some additional rules.

They must:

- Provide keyboard input functionality (e.g. typed characters);
- Follow Sticker guidelines if the keyboard includes images or emojis;
- Provide a method for progressing to the next keyboard;
- Remain functional without full network access and without requiring full access;
- Collect user activity only to enhance the functionality of the user’s keyboard extension on the iOS device.

They must not:

- Launch other apps besides Settings; or
- Repurpose keyboard buttons for other behaviors (e.g. holding down the “return” key to launch the camera).

**4.4.2** Safari extensions must run on the current version of Safari on macOS. They may not interfere with System or Safari UI elements and must never include malicious or misleading content or code. Violating this rule will lead to removal from the Developer Program. Safari extensions should not claim access to more websites than strictly necessary to function.

**4.4.3** Stickers

Stickers are a great way to make Messages more dynamic and fun, letting people express themselves in clever, funny, meaningful ways. Whether your app contains a sticker extension or you’re creating free-standing sticker packs, its content shouldn’t offend users, create a negative experience, or violate the law.

**(i)** In general, if it wouldn’t be suitable for the App Store, it doesn’t belong in a sticker.

**(ii)** Consider regional sensitivities, and do not make your sticker pack available in a country where it could be poorly received or violate local law.

**(iii)** If we don’t understand what your stickers mean, include a clear explanation in your review notes to avoid any delays in the review process.

**(iv)** Ensure your stickers have relevance beyond your friends and family; they should not be specific to personal events, groups, or relationships.

**(v)** You must have all the necessary copyright, trademark, publicity rights, and permissions for the content in your stickers, and shouldn’t submit anything unless you’re authorized to do so. Keep in mind that you must be able to provide verifiable documentation upon request. Apps with sticker content you don’t have rights to use will be removed from the App Store and repeat offenders will be removed from the Developer Program. If you believe your content has been infringed by another provider, submit a claim here.

###4.5 Apple Sites and Services

**4.5.1** Apps may use approved Apple RSS feeds such as the iTunes Store RSS feed, but may not scrape any information from Apple sites (e.g. apple.com, the iTunes Store, App Store, iTunes Connect, developer portal, etc.) or create rankings using this information.

**4.5.2** Apple Music

**(i)** The MusicKit APIs let customers access their subscription while using your app. They are intended for simple music playback by Apple Music subscribers. Users must initiate the playback of an Apple Music stream and be able to navigate using standard media controls such as “play,” “pause,” and “skip.” Moreover, your app may not require payment or indirectly monetize access to the Apple Music service (e.g. in-app purchase, advertising, requesting user info, etc.). Do not download, upload, or enable sharing of music files sourced from the MusicKit APIs, except as explicitly permitted in MusicKit documentation.

**(ii)** Using the MusicKit APIs is not a replacement for securing the licenses you might need for a deeper or more complex music integration. For example, if you want your app to play a specific song at a particular moment, or to create audio or video files that can be shared to social media, you’ll need to contact rights-holders directly to get their permission (e.g. synchronization or adaptation rights) and assets. Cover art and other metadata may only be used in connection with music playback or playlists (including App Store screenshots displaying your app’s functionality), and should not be used in any marketing or advertising without getting specific authorization from rights-holders. Make sure to follow the Apple Music Identity Guidelines when integrating Apple Music services in your app.

**(iii)** Apps that access Apple Music user data, such as playlists and favorites, must clearly disclose this access in the purpose string. Any data collected may not be shared with third parties for any purpose other than supporting or improving the app experience. This data may not be used to identify users or devices, or to target advertising.

**4.5.3** Do not use Apple Services to spam, phish, or send unsolicited messages to customers, including Game Center, Push Notifications, etc. Do not attempt to reverse lookup, trace, relate, associate, mine, harvest, or otherwise exploit Player IDs, aliases, or other information obtained through Game Center, or you will be removed from the Developer Program.

**4.5.4** Push Notifications must not be required for the app to function, and should not be used for advertising, promotions, or direct marketing purposes or to send sensitive personal or confidential information.

**4.5.5** Only use Game Center Player IDs in a manner approved by the Game Center terms and do not display them in the app or to any third party.

###4.6 Alternate App Icons

Apps may display customized icons, for example, to reflect a sports team preference, provided that each change is initiated by the user and the app includes settings to revert to the original icon. All icon variants must relate to the content of the app and changes should be consistent across all system assets, so that the icons displayed in Settings, Notifications, etc. match the new springboard icon. This feature may not be used for dynamic, automatic, or serial changes, such as to reflect up-to-date weather information, calendar notifications, etc.

###4.7 HTML5 Games, Bots, etc.

Apps may contain or run code that is not embedded in the binary (e.g. HTML5-based games, bots, etc.), as long as code distribution isn’t the main purpose of the app, the code is not offered in a store or store-like interface, and provided that the software (1) is free or purchased using in-app purchase; (2) only uses capabilities available in a standard WebKit view; your app must use WebKit and JavaScript Core to run third party software and should not attempt to extend or expose native platform APIs to third party software; (3) is offered by developers that have joined the Apple Developer Program and signed the Apple Developer Program License Agreement; and (4) adheres to the terms of these App Review Guidelines (e.g. does not include objectionable content). You must provide an index of software and metadata available in your app upon request.

##5. Legal

Apps must comply with all legal requirements in any location where you make them available (if you’re not sure, check with a lawyer). We know this stuff is complicated, but it is your responsibility to understand and make sure your app conforms with all local laws, not just the guidelines below. And of course, apps that solicit, promote, or encourage criminal or clearly reckless behavior will be rejected. In extreme cases, such as apps that are found to facilitate human trafficking and/or the exploitation of children, appropriate authorities will be notified.

###5.1 Privacy

Protecting user privacy is paramount in the Apple ecosystem, and you should use care when handling personal data to ensure you’ve complied with applicable laws and the terms of the Apple Developer Program License Agreement, not to mention customer expectations. More particularly:

**5.1.1 Data Collection and Storage**

**(i)** Apps that collect user or usage data must have a privacy policy and secure user consent for the collection. This includes—but isn’t limited to—apps that implement HealthKit or other health/medical technologies, apps that utilize ARKit, Camera APIs, Photo APIs, or other software for depth of facial mapping information, HomeKit, Keyboard extensions, Apple Pay, Stickers and iMessage extensions, include a login, or access user data from the device. Your app description should let people know what types of access (e.g. location, contacts, calendar, etc.) are requested by your app, and what aspects of the app won’t work if the user doesn’t grant permission.

**(ii)** If your app doesn’t include significant account-based features, let people use it without a log-in. Apps may not require users to enter personal information to function, except when directly relevant to the core functionality of the app or required by law. If your core app functionality is not related to a specific social network (e.g. Facebook, WeChat, Weibo, Twitter, etc.), you must provide access without a login or via another mechanism. Pulling basic profile information, sharing to the social network, or inviting friends to use the app are not considered core app functionality.

**(iii)** Developers that use their apps to surreptitiously discover passwords or other private data will be removed from the Developer Program.

**(iv)** SafariViewController must be used to visibly present information to users; the controller may not be hidden or obscured by other views or layers. Additionally, an app may not use SafariViewController to track users without their knowledge and consent.

**5.1.2** Data Use and Sharing

**(i)** You may not attempt, facilitate, or encourage others to identify anonymous users or reconstruct user profiles based on data collected from depth and/or facial mapping tools (e.g. ARKit, Camera APIs, or Photo APIs), or data that you say has been collected in an “anonymized,” “aggregated,” or otherwise non-identifiable way. You may not use or transmit someone’s personal data without first obtaining their permission and providing access to information about how and where the data will be used.

**(ii)** Data collected from apps may not be used or shared with third parties for purposes unrelated to improving the user experience or software/hardware performance connected to the app’s functionality, or to serve advertising in compliance with the Apple Developer Program License Agreement.

**(iii)** Data gathered from the HomeKit API or from depth and/or facial mapping tools (e.g. ARKit, Camera APIs, or Photo APIs) may not be used for advertising or other use-based data mining, including by third parties.

**(iv)** Apps using Apple Pay may only share user data acquired via Apple Pay with third parties to facilitate or improve delivery of goods and services.

**5.1.3** Health and Health Research

Health, fitness, and medical data are especially sensitive and apps in this space have some additional rules to make sure customer privacy is protected:

**(i)** Apps may not use or disclose to third parties data gathered in the health, fitness, and medical research context—including from the HealthKit API, Motion and Fitness, or health-related human subject research—for advertising or other use-based data mining purposes other than improving health management, or for the purpose of health research, and then only with permission.

**(ii)** Apps must not write false or inaccurate data into HealthKit or any other medical research or health management apps, and may not store personal health information in iCloud.

**(iii)** Apps conducting health-related human subject research must obtain consent from participants or, in the case of minors, their parent or guardian. Such consent must include the (a) nature, purpose, and duration of the research; (b) procedures, risks, and benefits to the participant; (c) information about confidentiality and handling of data (including any sharing with third parties); (d) a point of contact for participant questions; and (e) the withdrawal process.

**(iv)** Apps conducting health-related human subject research must secure approval from an independent ethics review board. Proof of such approval must be provided upon request.

**5.1.4** Kids

For many reasons, it is critical to use care when dealing with personal data from kids, and we encourage you to carefully review all the requirements for complying with laws like the Children’s Online Privacy Protection Act (“COPPA”) and any international equivalents.

Apps may ask for birthdate and parental contact information only for the purpose of complying with these statutes, but must include some useful functionality or entertainment value regardless of a person’s age.

Moreover, apps in the Kids Category or those that collect, transmit, or have the capability to share personal information (e.g. name, address, email, location, photos, videos, drawings, the ability to chat, other personal data, or persistent identifiers used in combination with any of the above) from a minor must include a privacy policy and must comply with all applicable children’s privacy statutes. For the sake of clarity, the parental gate requirement for the Kid’s Category is generally not the same as securing parental consent to collect personal data under these privacy statutes.

**5.1.5** Location Services

Use Location services in your app only when it is directly relevant to the features and services provided by the app. Location-based APIs shouldn’t be used to provide emergency services or autonomous control over vehicles, aircraft, and other devices, except for small devices such as lightweight drones and toys, or remote control car alarm systems, etc. Ensure that you notify and obtain consent before collecting, transmitting, or using location data. If your app uses background location services, be sure to explain the purpose in your app; refer to the Human Interface Guidelines for best practices on doing so.

###5.2 Intellectual Property

Make sure your app only includes content that you created or that you have a license to use. Your app may be removed if you’ve stepped over the line and used content without permission. Of course, this also means someone else’s app may be removed if they’ve “borrowed” from your work. If you believe your intellectual property has been infringed by another developer on the App Store, submit a claim via our web form. Laws differ in different countries, but at the very least, make sure to avoid the following common errors:

**5.2.1** Generally: Don’t use protected third party material such as trademarks, copyrighted works, or patented ideas in your app without permission, and don’t include misleading, false, or copycat representations, names, or metadata in your app bundle or developer name. Apps should be submitted by the person or legal entity that owns or has licensed the intellectual property and other relevant rights and is responsible for offering any services provided by the app.

**5.2.2** Third Party Sites/Services: If your app uses, accesses, monetizes access to, or displays content from a third party service, ensure that you are specifically permitted to do so under the service’s terms of use. Authorization must be provided upon request.

**5.2.3** Audio/Video Downloading: Apps should not facilitate illegal file sharing or include the ability to save, convert, or download media from third party sources (e.g. Apple Music, YouTube, SoundCloud, Vimeo, etc.) without explicit authorization from those sources. Streaming of audio/video content may also violate Terms of Use, so be sure to check before your app accesses those services. Documentation must be provided upon request.

**5.2.4** Apple Endorsements: Don’t suggest or infer that Apple is a source or supplier of the App, or that Apple endorses any particular representation regarding quality or functionality. If your app is selected as an “Editor’s Choice,” Apple will apply the badge automatically.

**5.2.5** Apple Products: Don’t create an app that appears confusingly similar to an existing Apple product, interface (e.g. Finder), app (such as the App Store, iTunes Store, or Messages) or advertising theme. Apps and extensions, including third party keyboards and Sticker packs, may not include Apple emoji. iTunes music previews may not be used for their entertainment value (e.g. as the background music to a photo collage or the soundtrack to a game) or in any other unauthorized manner. If your app displays Activity rings, they should not visualize Move, Exercise, or Stand data in a way that resembles the Activity control. The Human Interface Guidelines have more information on how to use Activity rings.

###5.3 Gaming, Gambling, and Lotteries

Gambling, gaming, and lotteries can be tricky to manage and tend to be one of the most regulated offerings on the App Store. Only include this functionality if you’ve fully vetted your legal obligations everywhere you make your app available and are prepared for extra time during the review process. Some things to keep in mind:

**5.3.1** Sweepstakes and contests must be sponsored by the developer of the app.

**5.3.2** Official rules for sweepstakes, contests, and raffles must be presented in the app and make clear that Apple is not a sponsor or involved in the activity in any manner.

**5.3.3** Apps may not use in-app purchase to purchase credit or currency for use in conjunction with real money gaming of any kind, and may not enable people to purchase lottery or raffle tickets or initiate fund transfers in the app.

**5.3.4** Apps that offer real money gaming (e.g. sports betting, poker, casino games, horse racing) or lotteries must have necessary licensing and permissions in the locations where the App is used, must be geo-restricted to those locations, and must be free on the App Store. Illegal gambling aids, including card counters, are not permitted on the App Store. Lottery apps must have consideration, chance, and a prize.

###5.4 VPN Apps

Apps offering VPN services must utilize the NEVPNManager API and must make a clear declaration of what user data will be collected and how it will be used. VPN apps must not violate local laws, and if you choose to make your VPN app available in a territory that requires a VPN license, you must provide your license information in the App Review Notes field.

##After You Submit

Once you’ve submitted your app and metadata in iTunes Connect and you’re in the review process, here are some things to keep in mind:

- **Timing:** App Review will examine your app as soon as we can, and we’ve been working hard to improve review times. Learn more about App Review.
- **Status Updates:** The current status of your app will be reflected in iTunes Connect, so you can keep an eye on things from there.
- **Expedite Requests:** If you have a critical timing issue, you can request an expedited review. Please respect your fellow developers by seeking expedited review only when you truly need it. If we find you’re abusing this system, we may reject your requests going forward.
- **Release Date:** If your release date is set for the future, the app will not appear on the App Store until that date, even if it is approved by App Review. And remember that it can take up to 24-hours for your app to appear on all selected storefronts.
- **Rejections:** Our goal is to apply these guidelines fairly and consistently, but nobody’s perfect. If your app has been rejected and you have questions or would like to provide additional information, please use the Resolution Center to communicate directly with the App Review team. This may help get your app on the store, and it can help us improve the App Review process or identify a need for clarity in our policies. If you still disagree with the outcome, please submit an appeal.

We’re excited to see what you come up with next!