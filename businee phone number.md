# Designed 0→1 Product Experience for Tide's Business Phone Number

`B2B`  • `Mobile App` • `Shipped March 2026`

Role: **Product Designer II**

Timeline: 1 **month**

Team: **1 PM + 3 ENGG. + 1 DESIGNER + 1 UX WRITER**

Partner: **GIGs** (A specialist in embedded mobile services that links digital platforms with telecoms carriers.)

## Tide helps over 1.8 million SMEs with everything they need to run their business

With a presence across the UK, India, Germany and France, Tide provides a single platform for banking, admin, invoicing and other tools that keep small businesses moving.

![Image](Designed%200%E2%86%921%20Product%20Experience%20for%20Tide's%20Busines/image.png)

`PROBLEM`

## Most small business owners run their entire business from a single, personal mobile.

Running a business still means juggling personal phones, contracts and suppliers alongside their day-to-day work. There's no separation, no professionalism, no off-switch between personal and business.

From client calls to supplier coordination and personal conversations, everything happens on one phone. This leads to constant context-switching, reduced professionalism, and no clear boundary between work and personal life.

`<image>` Single screen with multiple notificaiton - personal and business `</image>`

---

`USER OPPORTUNITY`

## We can provide them a simple way to manage business communications on a single device.

By introducing a dedicated business phone number within the Tide app, we can help users manage their business interactions more effectively without needing a second device.

For our users (small business owners; mostly sole traders) - This can result in reduced operational overhead, improved credibility, and a clearer separation between work and personal life.

By bringing business phone numbers directly into the Tide app, we can remove yet another task from their to-do list and help them keep their business and personal lives clearly separate.

Tide Business Phone Number helps you separate your personal and work life easily, allowing small business owners to stay connected anywhere, anytime - right from their personal devices.

![Image](Designed%200%E2%86%921%20Product%20Experience%20for%20Tide's%20Busines/image%201.png)

---

`BUSINESS OPPORTUNITY`

## This will drive paid plan upgrades with an increased product adoption and retention - directly contributing to Tide's revenue. Adding one more tool to Tide’s product suite to increase their paid plans subscription.

Business phone numbers add incremental value to Tide’s existing plans, encouraging upgrades while supporting more frequent product usage and user retention. With the launch of this product, Tide aims to further strengthen its position as a core tool for small business management.

Currently Tide has 4 plans: Free, Smart, Pro and Max.
Business Phone number is available at no extra cost for members on Tide's Smart, Pro and Max subscriptions.

`<image>` Add image of plans screens here with Business Phone Number highlighted `</image>`

---

`SOLUTION`

## Business Phone Number — A dedicated eSIM-based phone line within the Tide app. Everything related to business, in one app.

Allowing users can set up and manage a business phone number directly within their Tide account, without needing multiple devices or switching between personal and business communication.

- It provides a business number with unlimited calls and texts.
- Customers who want mobile data can add the Unlimited Boost plan for £15 per month, which includes unlimited 5G data and 10GB of EU roaming data.
- No annual price rises
- Doesn't require credit checks.

`<video>` end to end flow `</video>`

---

`CONSTRAINTS`

## Building 0→1 generally means flying a plane while building it.

I started with creating alignment around understanding what the product was, who it was for, and what success looked like – before I could design any of it.

## Working within partner-defined guidelines and evolving constraints.

Our partner, Gigs, introduced specific requirements that shaped both the experience and execution. This included restrictions on surfacing the underlying network provider and changes to installation and uninstallation status flows, introduced late in the process.

Designs needed to be continuously adapted while remaining functionally sound.

**Third-party constraints**

- Limited flexibility for broad exploration
- Adherence to Gigs’ design and technical guidelines
- Mandatory partner approval for final sign-off

## Coordinating across teams for a dependent feature launch.

As Business Phone Number was positioned to drive paid plan adoption, close collaboration with the Plans team was critical. Timelines and execution were interdependent, requiring alignment across multiple teams to ensure a successful launch.

Tide App → Plan Team → MEM team → Plan team

![Image](Designed%200%E2%86%921%20Product%20Experience%20for%20Tide's%20Busines/image%202.png)

---

`DISCOVERY & RESEARCH`

## **I started the discovery by studying the existing eSIM setup flows across some popular apps like Revolut, N26 and Saily.**

![Image](Designed%200%E2%86%921%20Product%20Experience%20for%20Tide's%20Busines/image%203.png)

Revolut

![Image](Designed%200%E2%86%921%20Product%20Experience%20for%20Tide's%20Busines/image%204.png)

N26

![Image](Designed%200%E2%86%921%20Product%20Experience%20for%20Tide's%20Busines/image%205.png)

Saily

![Image](Designed%200%E2%86%921%20Product%20Experience%20for%20Tide's%20Busines/Screenshot_2026-03-22_at_5.49.04_PM.png)

## I benchmarked similar apps to understand how setup instructions can be communicated effectively through design.

We identified early on that our third-party partner couldn’t provide installation status, as it depended on the network provider (e.g., Vodafone). This meant the frontend couldn’t reliably track or display installation progress.

Also, the installation flows varied by device. Some required QR codes, others activation codes, while a few supported direct setup via the Tide app. This made it important for the design to clearly guide users through each path and reduce potential confusion.

Since we got to know about a constraint early on by the thrid party partners that they wpn't be able to provide us the installation status as its dependent on the provider (Vodafone), hence engineering would not be able to track the installation status and show it in the Front end. Also, every device had a different installation process. Some used QR, while others use an activation code, while some can be done directly via the Tide app. To cater to all the installation cases as per the device compatibility, this become a crucial design decision to focus on.

![Image](Designed%200%E2%86%921%20Product%20Experience%20for%20Tide's%20Busines/Screenshot_2026-03-22_at_5.49.51_PM.png)

## After the discovery, I mapped out the end-to-end user journey, before diving into the finer details.

This helps me organise my thoughts and align my stakeholders to bring more clarity and structure for the next steps.

![Image](Designed%200%E2%86%921%20Product%20Experience%20for%20Tide's%20Busines/Screenshot_2026-03-22_at_7.05.03_PM.png)

## The first challenge was to design a landing screen that clearly communicates the product’s value and benefits.

I used Figma Make [🤖…] to explore initial concepts while adhering to Tide’s design system. This helped define the information architecture of the page and how the product should be positioned within Tide’s broader suite of offerings.

![Image](Designed%200%E2%86%921%20Product%20Experience%20for%20Tide's%20Busines/image%206.png)

`<add iteration explorations made with AI>`

## To proceed with eSIM setup, users need to be on a paid Tide plan.

Free plan users are prompted to upgrade before continuing, while paid plan users can move directly to the next step, i.e., eSIM setup.

`<add plan upgrade flow here>`

## The eSIM setup process includes activation and installation.

Users first activate their eSIM number, followed by installing it on their mobile device. Insights from the discovery and research helped shape and define this core user flow.

- **Activation** Users provide consent to activate their business phone number, after which the number is registered to their business and ready for use.

`<add activation flow here>`

- **Installation** Based on device compatibility, users are guided through the installation process via QR code, activation code, or direct setup within the Tide app – with clear, step-by-step instructions.

`<add installation guides here>`

Once the installation is completed by the users successfully, they receive a confirmation SMS from the provider (Vodafone) and soon after, they can start using their business phone number for calls and texts.

`All set… eSIM has been setup!`

## Once installed successfully, users can purchase a data plan to unlock the full value of the eSIM.

Tide, in partnership with Gigs, currently offers unlimited 5G data across the UK, along with 10GB 5G data plans in select roaming countries. Over time, we plan to introduce more flexible data plans with varied pricing to better support different business needs.

## All set! Users can now track and manage their eSIM related activities within the app.

Users can

- **Manage an external / another number**  they can either choose to transfer it to Tide, or cancel it from the Tide app itself.
- **Uninstalling eSIM** - Removing eSIM from the device it’s currently installed on
- **Cancel Business Phone Number -** If you cancel, you'll have 1 month to transfer your number to another provider, or your number will be lost forever.
- **Data usage tracking -** For both native and roaming data.

## **Lets take a step back now. It was time to think how users will find and reach this product within the app.**

Since business phone number is an admin product, we decided to include entry points on the "Admin" tab within the app.

Users can also type in and find it via the Global search.

We also focused on a launch marketing strategy with the CRM team to send comms (email and push notifications) to the existing Tide users on both free and paid plans.

## We launched the first version of BPN in March 2026

`<metrics>`

`<linkedin post, articles links & collage >`

## After a successful launch, we came up with growth strategies to expand the discovery and activations of Business Phone Number

This focuses on bringing more visibility to this product by introducing contextual upsells for business phone number products in the appropriate user flows and touch points across the app.

- Business profile
- CoFo registration journey
- Onboarding setup guide
- Invoice templates
- Team member hub – providing business phone number to team members.

![Image](Designed%200%E2%86%921%20Product%20Experience%20for%20Tide's%20Busines/Screenshot_2026-03-22_at_10.07.33_PM.png)

That's all for now.

Reach out to me at iamjahanvi@gmail.com

View more projects: iamjahanvi.com

