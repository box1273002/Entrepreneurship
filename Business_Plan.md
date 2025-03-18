
# FOCO: Creating a credit-based screen time limiter app

## 1. Our Product

### 1.1 The Problem

In today's digital age, screen time dependency has become a widespread issue, with over **53% of Americans** seeking to reduce their phone usage to improve time management, mental health, and focus. However, breaking free from screen addiction is no easy feat — **49% of people** feel addicted to their devices, and **69% of Gen Z** openly acknowledge their phone dependency [1].

Our research also uncovered a critical gap in the market — existing screen time management apps, such as *Opal*, rely on rigid blocking mechanisms that can be inconvenient and demotivating for users.

### 1.2 Motivational Experiences

**Dhru's Story:** Dhru, one of FOCO's dedicated developers, has struggled with balancing his screentime. He tried several apps all of which sufferd from the same problem inflexiblity, particularly with apps like WhatsApp. When he blocked WhatsApp to stay focused, he found himself unable to use WhatApp when he genuinely need it to commicate. His experience demonstrates the importance of healthy digital habits and was the initial inspiration behind FOCO.

**Ptolemy's Story:** A similar problem was encountered by Ptolemy. This time the issue was will Youtube. He found himself spending too much time on the app and went to block it. This however was also too restrictive as it meant he was unable to watch some of university resources which were posting on youtube, again the inflexibility was his key pain point.

**Similar Experiences:** After this issue was bought to the attention of the team it was identified as a common among them and there social group. This motivated use to create something better.

### 1.3 Our Solution

Imagine the same scenario — but with FOCO’s innovative coin system.

Instead of a strict lockout, the user allocates coins to WhatsApp, deciding how much time they’re willing to “spend” on the app. When the coins run out, access is blocked — not as a punishment but as a natural consequence of spending their digital currency. This transforms screen time management into a strategic, gamified experience rather than a restrictive one. We will introduce a solution.

#### 1.4 App and Product Description

*FOCO* is a playful, gamified screen time management app designed to help users take back control of their digital habits, one coin at a time! 

This is a simple and powerful app where every week, the users sets a fixed number of coins. These coins can then be spent to unlock and use specific apps for a limited time.

Once their coins run out, access to their pre-selected locked apps are completely blocked until the next reset. 

**But Why?**

This scarcity encourages users to be intentional and strategic with their screen time, treating their digital attention as a valuable currency that is always has been. We recognise that time is the user's commodity and we help the user be purposeful with how they spend it online.

Our system will consist of a free verion and a premium version:
- **Free Version:**
    - Set a fixed number of weekly coins
    - Spend coins to unlock selected apps for a period of time
    - Locked apps become inaccessible once coins run out
    - Watch ads to earn extra coins
    - Simple hourly rate settings for app access
- **Premium Version:**
    - No ads, no data collection
    - Advanced locking features (puzzles, weekday locks)
    - Customizable coin schedules (higher coin costs for evenings or binge sessions)
    - Daily coin “weaning” feature to reduce digital dependency
    - Adjustable weekly coin caps for progressive time management

**The Service We Are Developing** 

The app will run on Android.

We will utilise gamification, behavioral psychology, and simple finance-style mechanisms (coins, investments) to create a fun app that helps users break free from digital addiction or casual users who want to be purposeful with their time. _Our Functional and Non Functional Requirements for our project can be found in the appendix_.

### 1.5 Selling Points
There are a number of things that set us apart from the competition. These are our five selling points:

1. **Mission-Driven, Not Profit-Driven:** FOCO is built by those who have experienced screen addiction firsthand and are committed to helping others break free.
2. **Affordable for Everyone:** Our premium plans start at just **£1/month or £10/year** — the most cost-effective option on the market.
3. **Gamified Time Management:** The coin system encourages strategic usage instead of strict app blocking.
4. **Build a Better Life:** Users can earn coins by completing real-life goals, reinforcing positive habits both online and offline.
5. **Fighting the Battle Together:** FOCO is a supportive tool, not a digital prison — we grow and evolve alongside our users.

### 1.6 Are We Economically Viable? - Value Mapping

Our value mapping (see *Appendix I*) demonstrates that FOCO offers the most affordable, flexible, and engaging screen time solution compared to competitors like *Cold Turkey*, *Opal*, and *Forest*. With features like coin-based time management, ad-based coin earning, and personalized scheduling, FOCO bridges the gap between rigid time-blocking apps and user-driven digital wellness.

## 2. Market Section

### 2.1 Market Research Goals

To ensure that our product provides users with the most effective productivity service on the market, we first performed extensive research. Our main lines of questioning were as follows:

- Target market and user needs: what demographics make up our target audience and why do these users consume these products?
- Market size and demand: how many people actively seek screen time control solutions and how will this change into the future?
- Competitive landscape: what existing apps offer screen time restrictions, and how do they work, how do competitors monetize their apps and what are the strengths and weaknesses of competing products?

### 2.2 Secondary Research

**Target market and user needs:**

Our research has shown that the market for productivity and time management apps is expanding, driven by increased smartphone usage and work-from-home trends. Demand for time tracking in both personal and professional contexts indicates potential for subscription-based monetization models. [2]

From analyzing the literature on the subject, we confirmed that most of the target audience would use the system as an intervention rather than as a guide. Based on this, we tailored our app to take into account the relationships of the user with their family and friends. By involving families in the intervention (in a Family Media Plan [3]), the project aimed to create tailored strategies for managing screen time, which can be supported by caregivers modeling healthy behaviors. This approach is essential for fostering long-term changes in media habits among adolescents. Intervening technologies are most effective when paired with support and enforcement of a third-party.

The benefits of the intervention were not just short-term; participants in [4] maintained lower levels of smartphone use and improved well-being for at least six weeks after the intervention ended. Ensuring that the user makes it through the initial few days is the hardest part in the “rehabilitation” timeline, hence it is a part we need to focus on the most in terms of encouraging and motivating the user.

**Market size and demand:**

Screen time management has become crucial due to rising smartphone and computer use, with adults averaging over 6 hours daily and children 3–4 hours [5]. What surprised us when assessing the market demand for this system was just how severe the problem of screen addiction was, especially with children. Increasing amount of time children spend on screens and the associated negative health outcomes, such as poor academic performance and obesity [6].

From looking at other similar systems, one standout aspects of many successful systems such as App Limit Monitor [7]. Users can tailor their screen time limits according to their personal needs and preferences, making it a flexible solution for different lifestyles. We realized that a  successful app should be highly flexible to allow the user to customize their settings in whatever way they wish (if they feel they cannot achieve their desired settings they may disengage), whilst also being restrictive in the areas it needs to be, the screen time limiter [7, 8].

**Competitive landscape:**

When assessing the competitive landscape, we were able to identify a number of successful competing systems, proving that this idea is tried and true. Nevertheless, we identified several gaps in the market which we look to exploit (see Main Competitors). Some applications and their revenues are listed below:

- Clarymind (launched Dec 2023) reduces screen time by up to 2 hours/day through AI-driven mindfulness features like 10-second pause before app use, guided meditation, sleep aids (calming music).
- ScreenTime+ ($15K/month) and BePresent ($10K/month) show strong market demand for screen management tools.

Despite several competitors, our data shows that the market is yet to be fully saturated. The parental control software market ($1.25B in 2023) is projected to grow to $3.54B by 2032 at 12.3% CAGR. Factors driving growth include: increased mobile use, pandemic-induced digital habits, and rising demand for parental controls.

In terms of business models, most competitors opt for a subscription model to maintain a constant income. Clarymind [4] for example operates on a subscription model (Monthly: $14.99 | 6-Month: $49.99 | Yearly: $62.99 | Pro: $34.99), estimated to generate ~$2M annually with 100,000+ active users.

### 2.3 Primary Research and Consulting

To validate our findings from our secondary research, we decided it would be most productive for our business to conduct our own primary research. First, we tried to determine how to monetize the product in a way that is most compatible with the users. Out of all of the participants, 80% people would prefer sharing their data rather than watching ads, and 60% of participants would be willing to pay up to £3 to remove ads. For the premium version, roughly half would pay £1.00 per month / £ 10.00 per year / £25.00 lifetime (the other half were not interested in premium). Surprisingly, out of monthly, yearly and lifetime subscription models, participants were completely mixed, with an even split each. 

We also asked our participants for more general feedback. Participants suggested as premium features: graphing the amount of time spent on each app, allowing cashing in unused coins and buying cosmetic features. In additional comments, participants stated that the user should not be allowed to game the system, such as by leaving productive apps open and not doing anything in the.
This survey was excellent at getting a direct insider view into the opinions of the target audience and was greatly influential in how we shaped our product.

### 2.4 Main Competitors

The screen time management app market has experienced significant growth in recent years, driven by increasing awareness of digital wellbeing and the negative impacts of excessive screen time. According to recent studies, the average American spends approximately 7 hours per day on digital devices, with smartphone usage accounting for a significant portion of this time. This has created a substantial market opportunity for applications that help users manage and reduce their screen time.

The market can be segmented into several categories:

- Simple monitoring apps that track usage
- Blocking apps that restrict access to certain applications
- Comprehensive management tools that combine tracking, blocking, and behavioral modification
- Specialized solutions for parental control and family management

FOCO positions itself primarily in the comprehensive management category, offering a blend of monitoring, blocking, and behavioral modification through its unique coin system. This approach allows it to appeal to a broad audience while differentiating itself from competitors.

#### 2.4.1 Opal: The Premium Competitor

Opal [9] has established itself as a premium player in the focus app market, with a strong emphasis on deep work and distraction elimination.

**Strengths**:

- Social competition through friend leaderboards drives engagement
- DeepFocus Mode provides stringent app locking that prevents users from disabling restrictions
- Professional design and user experience

**Weaknesses**:

- High premium pricing creates a barrier to entry for many potential users
- Limited customization options create a rigid user experience
- Lacks the gamification elements that make screen time management engaging

**Competitive Implications for FOCO**:
Opal's premium positioning and relatively high price point ($8.29/month) create an opportunity for FOCO to offer comparable functionality at its more accessible £1/month price point. While Opal's DeepFocus Mode represents a gold standard for hardcore focus seekers, FOCO's customizable restriction levels could appeal to users seeking more flexibility.

FOCO should consider implementing a similarly robust blocking mechanism while maintaining its price advantage and expanding its customization options. The significant price differential ($7/month) could be a compelling driver for users to choose FOCO over Opal if the core blocking functionality is comparable.

#### 2.4.2 Forest: The Gamification Pioneer

Forest [10] has successfully leveraged environmental impact and visual rewards to create a compelling productivity tool that has garnered significant market attention.

**Strengths**:

- Strong gamification through tree-planting mechanics
- Appealing visual design that resonates with users
- Real-world environmental impact through tree planting partnerships
- Established brand recognition with over 10 million downloads

**Weaknesses**:

- Easy to bypass restrictions limits effectiveness for users lacking self-discipline
- Basic analytics and insights restrict users' ability to understand usage patterns
- Limited blocking capabilities compared to more robust competitors

**Competitive Implications for FOCO**:
Forest's success demonstrates the power of gamification in the screen time management market. FOCO's coin system represents a similar but distinct approach to gamification that can be expanded upon. While Forest uses environmental impact as its emotional hook, FOCO might consider emphasizing personal wellbeing and mental health benefits as its emotional driver.

FOCO's potential advantage lies in combining Forest's engaging gamification with more robust blocking mechanisms and detailed analytics. By providing users with both the emotional rewards of gamification and the practical tools for enforcing discipline, FOCO could position itself as an evolution beyond Forest's approach.

#### 2.4.3 Cold Turkey: The Hardcore Blocker

Cold Turkey [11] takes a no-nonsense approach to digital distraction, offering some of the most stringent blocking mechanisms available.

**Strengths**:

- Extremely effective blocking that requires system reboots to bypass
- One-time purchase model appeals to subscription-fatigued consumers
- Established reputation for effectiveness among serious productivity enthusiasts

**Weaknesses**:

- Desktop-focused with limited mobile presence
- Unfriendly user interface creates friction for new users
- Lacks gamification elements that could increase engagement
- Extreme blocking may be too restrictive for casual users

**Competitive Implications for FOCO**:
Cold Turkey's focus on desktop platforms creates a significant opportunity for FOCO in the mobile space. By offering comparable blocking effectiveness on mobile devices with a more user-friendly interface, FOCO could capture users seeking Cold Turkey's effectiveness in a more accessible package.

FOCO should consider how to balance blocking effectiveness with user experience, perhaps offering tiered levels of restriction that allow users to gradually increase blocking severity as they build discipline. The subscription model versus one-time purchase difference represents a strategic choice, with FOCO betting on long-term recurring revenue over upfront payments.

#### 2.4.4 Jomo: The Widget Innovator

Jomo [12] has created distinctive value through its widget-based approach and dynamic limits.

**Strengths**:

- Home screen widgets provide convenient access to key functions
- Dynamic limits that adjust based on user behavior create flexibility
- Social features enhance engagement and accountability

**Weaknesses**:

- Lack of cross-device synchronization limits utility for multi-device users
- Widgets lack personality and gamification elements
- Limited blocking capabilities compared to dedicated blocking apps

**Competitive Implications for FOCO**:
Jomo's widget-based approach represents an opportunity for FOCO to enhance its accessibility through similar home screen integrations. By developing widgets that display coin balances, time spent statistics, and quick blocking controls, FOCO could increase engagement and utility.

The lack of cross-device synchronization in Jomo highlights an opportunity for FOCO to implement robust cross-platform functionality, ensuring a seamless experience across all of a user's devices. Additionally, FOCO's coin system could be extended to the widget interface, bringing gamification elements to the home screen in a way that Jomo has not accomplished.

### 2.5 Competitive Analysis

Based on an analyiss of our competitors, FOCO occupies a promising position in the screen time management market by combining elements that have proven successful across multiple competitors:

1. **Gamification (like Forest)** through its coin system
2. **Robust blocking (like Cold Turkey)** through DNS-level website blocking
3. **Social features (like Opal and Jomo)** through friend connections and challenges
4. **Customization (beyond most competitors)** through themes and personalization options
5. **Affordability (better than premium competitors)** at £1/month

This combined approach addresses multiple user needs within a single platform, potentially eliminating the need for users to employ multiple applications for different aspects of screen time management.

#### 2.5.1 Key Market Advantages

FOCO's most significant advantages in the current market include:

1. **Price-to-Feature Ratio**: By offering comprehensive functionality at a lower price point than premium competitors, FOCO presents compelling value.
2. **Balanced Approach**: The combination of monitoring, blocking, and gamification creates a more comprehensive solution than competitors that focus primarily on one approach.
3. **Coin System Innovation**: The bidirectional coin system (earning and spending) creates a more dynamic and engaging experience than the one-way systems used by competitors like Forest.
4. **Customization Depth**: The extensive personalization options provide users with a sense of ownership and identity within the app ecosystem.
5. **Mission-Driven Positioning**: The emphasis on accessibility and wellbeing over profit maximization can create stronger brand loyalty and word-of-mouth marketing.

#### 2.5.2 Primary Challenges and Risks

Despite its advantages, FOCO faces several significant challenges that could impact its success:

1. **Market Saturation**: The screen time management space is increasingly crowded, making user acquisition costly and competitive.
2. **Feature Replication**: Successful features like the coin system could be replicated by established competitors with larger user bases and development resources.
3. **Platform Restrictions**: Apple and Google have increasingly built screen time management features into their operating systems, potentially reducing the perceived need for third-party solutions.
4. **User Retention**: Screen time management apps often face high churn rates as users either succeed in reducing their screen time (and thus no longer need the app) or abandon their efforts entirely.
5. **Low Price Sustainability**: The £1 price point, while attractive to users, may create challenges in funding ongoing development and marketing efforts, particularly in a competitive user acquisition environment. Given our study however, it seems that this is a price that would allow us to access a much wider user base who might not otherwise be interested in these apps: as our main cost would be development, this would mean that we can scale up at no additional cost. We should therefore be able to obtain a much larger user base than any of the pre existing apps, and use this large scale to make up for the low revenue per user.
6. **Behavioral Change Complexity**: Successfully changing deeply ingrained digital habits requires more than just technical tools—it requires behavioral science expertise that may be challenging to implement effectively.

### 2.6 Assumptions and Risk Assessment

FOCO's business model rests on several key assumptions that should be critically evaluated:

1. **Gamification Effectiveness**: If the coin system proves too complex or insufficiently motivating, users may abandon the app for simpler solutions.
    - *Mitigation Strategy*: A/B testing different reward mechanisms and simplification of the core coin mechanics based on user feedback.
2. **Price Point Sustainability**: The low price point may attract users but create challenges in funding growth and development.
    - *Mitigation Strategy*: Implementing a tiered pricing model with additional premium features at higher price points while maintaining the core £1 base offering.
3. **Platform Competition**: Native OS screen time features continue to improve, potentially diminishing the perceived value of third-party apps.
    - *Mitigation Strategy*: Focusing on features that go beyond what OS-native solutions offer, particularly in areas of blocking, gamification, and social engagement.
4. **Retention Challenges**: Users who successfully reduce screen time may no longer see value in paying for the app.
    - *Mitigation Strategy*: Expanding the value proposition beyond just screen time reduction to include broader digital wellbeing and productivity enhancement.
5. **Marketing Costs**: User acquisition in a crowded market may require significant spending that the low price point cannot support.
    - *Mitigation Strategy*: Leveraging the mission-driven positioning for PR and word-of-mouth growth, potentially supplemented by strategic partnerships with digital wellbeing organizations, or through university programs.

## 3 Strategy Section

### 3.1 Priority Road Map

#### 3.1.1 Short Term Priorities (0-6 months)

1. **Core Feature Refinement**: Ensure the coin system is intuitive, engaging, and provides clear value to users from their first interaction.
2. **User Acquisition Campaigns**: Launch targeted marketing campaigns that emphasize FOCO's unique value proposition and affordability compared to premium competitors.
3. **Early Adopter Community**: Build a community of highly engaged users who can provide feedback and serve as brand ambassadors.
4. **Analytics Enhancement**: Develop comprehensive usage insights that exceed competitors like AntiSocial while maintaining an engaging presentation.
5. **Widget Development**: Create home screen widgets that display coin balances and quick access to key features, addressing Jomo's innovation in this area.

#### 3.1.2 Medium Term Strategy (6-18 months)

1. **Family Plan Development**: Expand into the family market with parent-child functionality that leverages the coin system for household screen time management.
2. **Cross-Device Synchronization**: Implement seamless experience across all user devices, addressing a weakness identified in competitors like Jomo.
3. **Tiered Pricing Refinement**: Test and optimize additional premium tiers while maintaining the core affordable offering.
4. **Strategic Partnerships**: Develop relationships with digital wellbeing organizations, educational institutions, and mental health platforms to expand reach.
5. **API Integration**: Create integrations with productivity platforms and health apps to expand the ecosystem and increase switching costs.

#### 3.1.3 Long Term Vision (18+ months)

1. **Behavioral Science Expansion**: Incorporate advanced behavioral science principles beyond simple gamification to create lasting habit changes.
2. **Enterprise Solutions**: Develop workplace-focused versions that help organizations promote digital wellbeing among employees.
3. **Education Focus**: Create specialized versions for educational settings that help students manage screen time while still accessing necessary digital resources.
4. **International Expansion**: Adapt the coin system and interface for cultural differences in international markets.
5. **Broader Digital Wellbeing Platform**: Expand beyond screen time management to address other aspects of digital wellbeing like posture, blue light exposure, and sleep quality.

### 3.2 Legal Status and Structure

#### 3.2.1 Current Structure: Private Limited Company (Ltd)

FOCO is planned to be structured as a Private Limited Company (Ltd) registered in the United Kingdom. This structure was selected for several strategic reasons:

- **Limited Liability Protection**: The Ltd structure creates a separate legal entity, protecting the personal assets of founders and shareholders from business liabilities. This is particularly important for a digital application where user data management and potential service disruptions pose ongoing operational risks.
- **Ownership Flexibility**: The company's shares are privately held among founders and early investors, with no requirement for public trading. This allows the management team to maintain decision-making control during the critical early development stages.
- **Credibility and Formality**: The Ltd designation provides FOCO with enhanced credibility when engaging with potential partners, users, and investors compared to sole trader or partnership structures.
- **Tax Efficiency**: As a Ltd company, FOCO is subject to UK Corporation Tax (currently 25% for companies with profits exceeding £250,000, and 19% for those with profits under £50,000) rather than personal income tax rates. This creates potential tax advantages, particularly as the company begins generating significant revenue.

#### 3.2.2 Future Structure: Public Limited Company (PLC)

As FOCO continues to scale, converting to a Public Limited Company could be advantageous as a step toward potential public listing.

**Advantages**:

- Enhanced ability to raise capital through public markets
- Increased prestige and visibility
- Greater liquidity for shareholders
- Potential for higher valuation multiples

**Considerations**:

- Significantly increased regulatory requirements
- Additional disclosure obligations
- Quarterly reporting pressures
- Higher governance standards and administrative costs
- Vulnerability to activist investors and takeovers

#### 3.2.3 Regulatory Compliace and Legal Considerations

As a screen time management application that monitors user activity, data protection represents one of the most significant legal considerations for FOCO. We would need to ensure compliance with the General Data Protections Regulation (GDPR):

- **Privacy Policy**: A detailed privacy policy clearly articulates what data is collected, how it is used, stored, and the legal basis for processing.
- **Data Minimization**: The application is designed to collect only essential data required for core functionality, in accordance with data minimization principles.
- **User Consent Mechanisms**: Clear opt-in processes should be implemented for all non-essential data collection, with straightforward methods for users to withdraw consent.
- **Data Subject Rights**: Processes should be implemented to handle data subject access requests, the right to be forgotten, and other GDPR-mandated user rights.
- **Data Protection Impact Assessment**: FOCO would require a DPIA due to the nature of the data processing activities involved in tracking app usage.

Given that screen time management apps may appeal to parents seeking to monitor children's device usage, FOCO would need to implement additional safeguards:

- **Age Verification**: Processes to verify user age and obtain parental consent where required.
- **Enhanced Data Protection**: Special protection measures for data potentially relating to children under 13.
- **Compliance with Children's Data Regulations**: Including the Age Appropriate Design Code in the UK and COPPA in the US market.

#### 3.2.4 Trademark Protection

As FOCO's business value is substantially tied to its intellectual property assets, we would need to ensure the following:

- **Registered Trademark**: "FOCO" would need to be registered as a trademark in the UK under classes 9 (computer software) and 42 (software as a service).
- **International Registration**: We would need to apply for EU and US trademark protection through the Madrid Protocol.
- **Brand Guidelines**: Clear internal guidelines govern the use of the FOCO brand to prevent dilution.

#### 3.2.5 Copyright Protection

- **Software Code**: Copyright protection for the application's source code, with proper documentation of ownership.
- **Visual Elements**: Copyright protection for unique visual elements, including the app's user interface, logo, and graphic designs.
- **Content**: Original content within the application, including texts, notifications, and guidance materials.

#### 3.2.6 Patent Considerations

- **Innovative Features**: The coin system mechanism is potentially patentable, though the company has currently opted for trade secret protection rather than patent filing, which would require public disclosure of the methodology.
- **Patent Landscape Analysis**: Regular monitoring of the competitive patent landscape to avoid infringement and identify potential patentable innovations.

#### 3.2.7 Consumer Protection Compliance

FOCO would require measures to ensure compliance with consumer protection laws:

- **Terms of Service**: Clear, transparent terms of service that define the relationship between FOCO and its users.
- **Subscription Management**: Straightforward processes for users to manage, modify, or cancel subscriptions in compliance with consumer rights regulations.
- **Pricing Transparency**: Clear disclosure of all costs, including in-app purchases and subscription renewals.
- **Right of Withdrawal**: Processes to handle consumer withdrawal rights, including refund policies in line with app store requirements and local regulations.

### 3.3 The Team

We are currently working in a small team consisting of 5 member in order to create a minimum working prototype. It should be noted that the current stage of the company that all team members share responsibility, and as the company matures the roles may change as they become more strictly defined.

**Tomáš Pecher - CEO**

Perhaps the most well rounded team with prior experience acting as team leader in numerous university project, Tom is well positioned to lead the team as CEO.

**Marilyn D’Costa - CFO**

Marilyn has specialized in the data science and business strategy elements of her computer science. As such she is best suited to take on the role of CEO.

**Dhru Randeria - CMO**

With prior experience as a social media ambassador for the University, Dhru is well position to bring our message across as CMO. 

**George Rawlinson - Developer Lead**

The most technically proficient member of the team, George’s high grades development modules as well as his experience as a professional software developer place him in a strong position to lead the technical of the app.

**Ptolemy Morris - Product manager**

With prior stakeholder engagement experience, Ptolemy will be working closely the development team translating costumer suggestions/feedback into them into technical requirements.

### 3.4 Required Resources

The product has been specifically selected as it has limited upfront startup cost, with the initial costs being largely development related, not requiring significant capital investment.

#### 3.4.1 Capital Requirements

**Google Development Console - $25.00**

In order to publish to the Google Play Store there is a one time cost of $25.00. After this a 15.0% commission on revenue up to $1,000,000 on the app, after this the commission is then doubled to 30.0%.

**Apple Developer Program - $99.00 per year**

In order to publish on the App Store a $99.00 per year subscription is necessary. In addition to a 30.0% commission on all revenue generated on the app.

**Work Laptop - N/A**

Due to the small nature of our company and the fact that we all possess personal laptop that can be used for development. This however would likely change as the company matures.

#### 3.4.2 Skill Requirements

**Graphic Designer** 

Our team is comprised of technical individuals and as such we need to hire a graphic designer to ensure a visual appealing UI, which is essential to compete in the current mobile phone app market. This is not required until after the creation of a minimum working prototype, which we will use to as a tool to aid hiring.

**App Store Optimization** 

Although it is unlikely we will need to bring a dedicated team member on board to handle App Store Optimization it would be beneficial for one or more team member to undertake some form of App Store Optimization training, likely the CMO Dhru Randeria.

### 3.5 Approach to Financing

Our approach to funding will involve bootstrapping the app for initial development and testing so we can have full control of the app without relying on investors and to allow us to validate our idea before committing to any financial decisions. We would then release a free version of the app with basic features to gain users such as configuring the credit settings and being able to change them by performing a long task. After one year, we would then release a Freemium Model of our app. The premium version of our app would have simpler tasks to change the credit system and could also contain features that can implement the credit system from the app during certain periods of the day, e.g.: the credit system could be implemented on Monday to Friday from 9am-5pm if someone wants to be productive during the working week but wants to relax outside of work. 

#### 3.5.1 Financial Projections

**1st Year Projections**

In our first year, we would focus on user growth. In order to gain more users, we would invest money on hosting and development costs and potential marketing (such as social media advertisements and promotions) and not focus too much on the revenue we make because we want users to implement the app into their daily lives and provide us feedback. We aim to reach about 5,000-10,000 active users by the end of the year and we would collect feedback from them to refine features on our app.

**2nd Year Projections**

For our second year, we would introduce the freemium model. We could also provide some in-app purchases for users to gain insight into their productivity such as an analytics dashboard that could tell a user how much time they spent on unproductive apps in a week and compare it to the previous week. By the end of the year, we hope to have at least 5% of our users on the premium version of our app and hope for at least £500/month revenue. We still want to maintain user growth so with the revenue, we would invest some of it into partnerships.

**Year 3+ Projections**

In the long-term, we would want to introduce AI-driven recommendations and integrate the tool with existing work-tools such as Notion or Slack. To gain additional revenue, we could expand subscriptions options, such as teams or corporate packages and we could partner with universities and employers to offer the app as part of wellness initiatives.

**Exit Strategy**

As an exit strategy, we could sell the company to a larger technology company or we could expand it until we have a standalone business.

### 3.6 Initial Sales and Marketing Strategy

#### 3.6.1 App Store Optimisation and User Feedback

We are planning on releasing our app onto the Apple and Google Play Stores and to make our app more visible to the public, we aim to use more optimised descriptions and keywords. We would do this by including keywords and terms such as “Productivity Tracker” or “Focus App”. We will also have a clear explanation of what our app does, highlight its unique features and include screenshots of the app as well as a video demonstrating the app in action. In order to gain positive reviews and respond to user feedback, we will ask users via the app how satisfied they are with the app via a 5-star rating. If the user rates the app, they will be asked to provide some feedback and if the rating is high (4 or 5 stars), they would be asked if they can provide a review to an app store so that more people are convinced to install our app. We would then respond to user feedback and try to implement any features the users suggest.

#### 3.6.2 Referral Programs

In order to get more users to use our app, we will also implement a referral program, which would benefit current users of the app as well as new users. Referral programs provide a way to reach new users passively, with its effectiveness scaling with our user base. We are currently exploring two possibles for the reward that given for successful referrals. The first possibility is giving 30 days of premium when somebody you referred purchases a premium plan. The second is a giving the user a random alternate app skin for any sign up with a the referral link regardless of the whether they pay for premium. Both approaches come with different advantages, with the skin based approach having no variable costs but likely having a lower conversion rate to new customers. Once the app launches we experiment to see which approach is more successful and whether they can be successfully run in parallel. 

#### 3.6.3 University and Workplace Partnerships

Because our app focuses on productivity, one of our main audiences would be students. Therefore, we would focus on marketing for this audience via university and workplace partnerships. We could start with the University of Bath and market the app via social media platforms, especially via the University’s Instagram page [13] because there are student vloggers who make content that promotes how student life is like at the University of Bath as well as the University’s programmes [14]. However, this does however come with the risk of the app coming across as pushed by the university, contradicting with our core message of take back control. We could also ask content creators that are promoting study content to advertise our app and perhaps, if we get content creators that are very well-known, we could provide a 3-month free premium model if customers sign up with a promotion code. A suitable platform to advertise this on is YouTube because there are study communities on this app such as the “StudyTubing” community [15] and it would be beneficial if content creators could provide demonstrations of the app via long-form content, compared to platforms that mainly provide short-form content such as TikTok.

#### 3.6.4 User Case Studies

To promote our app further, we could promote case studies of people using our app as a second point of contact after word-of-mouth referring and marketting advertisements for our product via platforms such as LinkedIn and our app website to signify how our app promotes productivity, which could help provide more information for people that are considering using our product. Furthermore, if our app is successful, we could show the retention statistics of using our app. This would be how many weeks the user would update their credit system as it could signify ongoing use of the app.

### 3.7 Main Risks and Mitigation Strategies

We have four main risks with our business idea: Google and Apple restricting user permissions, user resistance, data privacy and security, and competition with other productivity apps.

#### 3.7.1 User Permission Restrictions

The most significant risk to the success of our company come from Google and Apple. This is due to the nature of our app requiring significant privileges to function. The risk comes as the possibility that either Google or Apple could restrict iOS/Android users ability to give such overarching permissions to 3rd party apps such as ours. However, it is unclear how likely a risk this is as it would entail curtailing user control with no financial incentive. This small risk is being mitigated by developing the application for multiple platforms, as it is unlikely all platforms will disallow this at once. 

#### 3.7.2 User Resistance

For user resistance, users could easily lose retention if they suddenly lose access to apps that they deem unproductive. In order to mitigate users from losing retention and from our app gain viewership, we would implement gradual restrictions instead of a sudden app block. A suggested idea that we may follow is that we would implement a warning system to the user if their credit is getting low. The user would set a number of credits that they would like to start getting warnings at and would also set how often they would want this reminder given to them, whilst they are losing credits.

#### 3.7.3 Data Privacy Concerns

Another main concern is data privacy and security. This is specificly important due to the sensitive nature of data. To ensure that our app does not cause any data privacy or security concerns, the data security risk will be mitigated by storing data via the iCloud or Google Drive because they are run by a larger organization and as such have dedicated to address any issues. The privacy risk will be mitigated by ensuring transparency in data collection by not accessing any personal user data except when explicitly given permission (e.g. if the user interacts with our app with the data plan) and complying to all GDPR regulations.

#### 3.7.4 Competition with Other Productivity Apps

In order to deal with competition, we will implement unique features that differentiate our app from competititors, such as making the user complete a long verification process to re-configure the credit system, as well as combining elements that have already succeeded with existing competitors such as gamification, robust blocking, social features and customisation.

## Reference

[1] Harmony Healthcare IT (2025) Phone screen time statistics. Available at: https://www.harmonyhit.com/phone-screen-time-statistics/ (Accessed: 16 March 2025)

[2] Nield, D. (2025) *The Best Time Management Apps to tame the chaos*, *Wired*. Available at: https://www.wired.com/story/best-time-management-apps (Accessed: 16 March 2025). 

[3] Persichetti, E. (2020). *Unplugging: An Evidence-Based Project to Reduce Screen Time and Improve Healthy Media Use in the Adolescent Population*. https://doi.org/10.22371/07.2020.024 (Accessed: 16 March 2025). 

[4] Olson, J. A., D, S., Chmoulevitch, D., Raz, A., & Spl, V. (2021). *A ten-step behavioural intervention to reduce screen time and problematic smartphone use*. https://doi.org/10.31234/OSF.IO/TJYNK (Accessed: 16 March 2025).

[5] Chanda, D. (2025) Mindful Screen Time Management app development like Clarymind, IdeaUsher. Available at: https://ideausher.com/blog/screen-time-management-app-development-like-clarymind (Accessed: 16 March 2025). 

[6] Bleckmann, P., Schwendemann, H., Flaig, S., Kuntz, L., Stiller, A., Mößle, T., & Bitzer, E. M. (2019). *MEDIA PROTECT: A setting- and parent-targeted intervention for a healthy childhood in the digital age* (pp. 233–246). Policy Press. https://doi.org/10.56687/9781447344520-018 (Accessed: 16 March 2025). 

[7] Agrawal, P. A. (2024). AppLimit Monitor for Smartphone Addiction. *Indian Scientific Journal Of Research In Engineering And Management*. https://doi.org/10.55041/ijsrem29133 (Accessed: 16 March 2025). 

[8] Hoof, K. van (2023) *5 best apps for limiting screen time in 2025: Tested*, *SafetyDetectives*. Available at: https://www.safetydetectives.com/blog/best-apps-for-limiting-screen-time (Accessed: 16 March 2025).

[9] Opal Corporation (2024). Opal. https://www.opal.so/ (Accessed: 16 March 2025).

[10] SeekrTech (2025). Forest: Focus for Productivity. https://www.forestapp.cc/ (Accessed: 16 March 2025).

[11] Cold Turkey Software Inc. (2025) Cold Turkey. https://getcoldturkey.com/ (Accessed: 16th March 2025). 

[12] Jomo SAS. (2024) Jomo. https://jomo.so/ (Accessed: 16th March 2025) 

[13] University of Bath [@uniofbath], 2025. Instagram Page [Online]. Available from: https://www.instagram.com/uniofbath/?hl=en [Accessed 16/03/2025]

[14] Uni of Bath Student Support [@bathstusupport], 2025. Instagram Post [Online], 21/11/2023. Available from: https://www.instagram.com/bathstusupport/reel/Cz6hbgvtd_n/ [Accessed 16/03/2025]

[15] Whitehall, E., 2020. *How StudyTube is Changing Education* [Online]. United Kingdom: The Indiependent. Available from: https://www.indiependent.co.uk/how-studytube-is-changing-education/ [Accessed 16/03/2025]


### Appendices
