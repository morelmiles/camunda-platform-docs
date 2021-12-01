# Technical Writing Style Guide

## Overview

The following document outlines technical writing techniques and practices Camunda utilizes to ensure uniform styling across Camunda documentation and to yield a more cohesive and organized user experience alongside a fast-growing staff. This document is focused predominantly on technical writing, and is separate from Camunda marketing and communications standards.

Default to [Google's Style Guide](https://developers.google.com/style) for anything not referenced or preferred in this document.

## Application

The Camunda Technical Writing Style Guide applies primarily to current and future external-facing technical content:

- Camunda Platform documentation
- Camunda Cloud documentation

If you are unsure whether or not you should utilize the practices within this document, please refer to your line manager or team lead.

## Goals

We encourage document authors and technical writers to keep in mind grammar, punctuation, formatting, and terminology to create user-friendly documentation between developers and users. Keeping these tools in mind, our goal is to achieve three key goals in our technical writing:

| Goal | Questions to ask |
| -- | -- |
| Organization | Is the documentation organized? Is the flow of information logical? Have I broken large components into smaller, simpler components? |
| Clarity | Is the information clear? Have I spelled out acronyms and avoided too much company jargon or slang? Does the reader understand what I'm saying? |
| Direction | Does the reader know what they need to do? Does the reader know where to turn if they don't know what to do? |

## Grammar

| Subject | Practice | Avoid | Example/Use |
| -- | -- | -- | -- |
| Bolding | Bold when referring to button names or items to select. | Bold to refer to another section within a document. | Click "Create New Diagram." | Click **Create New Diagram** under the **Diagrams** tab. |
| Capitalization | Refer to [Purdue's American capitalization guide](https://owl.purdue.edu/owl/general_writing/mechanics/help_with_capitals.html). | i like Camunda cloud. | I like Camunda Cloud. |
| Currency | Use the currency symbol first, followed by the amount. Where appropriate, round to a whole number. | I have two hundred dollars. | €300<br>$22,600<br>€22.6 million |
| Dates | Avoid expressing a month as a number to avoid common confusion around US/EU conventions. If there is no way around it, use the US-English "/" as separators.<br>In technical documentation, it is best to remove the day of the week as it may not be as relevant as the day and month. | 10 December, 2018<br>10-12-2018 | December 10, 2018<br>If you must use numbers: 2021-05-19 |
| Date ranges | Avoid repeating the same month twice in the same date range.<br>If you are using numerical values, enter as follows: Year, month, date. | Camunda Community Summit April 27 - April 28 | Camunda Community Summit April 27-28 |
| [In to vs. into](https://www.grammarly.com/blog/into-vs-in-to/?&utm_source=google&utm_medium=cpc&utm_campaign=10273012991&utm_targetid=aud-879636892685:dsa-1233402314764&gclid=CjwKCAjw55-HBhAHEiwARMCszrAxBW--e56ITNgN5AVsSot_KSUlLcc6oLBkI0741uFAWldNQeVzrRoCwvIQAvD_BwE&gclsrc=aw.ds) | Always think of "into" as a single preposition (within or outside of something.)<br>Typically, "into" refers to physically going inside.<br>Think of "in to" as two independent prepositions that happen to end up next to one another, and typically aren't physically entering or exiting something.<br>Oftentimes, you can tell if you should use "in to" because you could place a comma after "in," and the sentence would still make sense. | Type your name in to the text box to sign up for Camunda Cloud.<br>"Check which folder the file is into ensure you are in the correct location." | Type your name into the text box to sign up for Camunda Cloud.<br>"Check which folder the file is in to ensure you are in the correct location." |
| Italics | Use when applying emphasis to a word. | Avoid overuse, using for button names.<br> Click *Create New Diagram*. | See the **Bolding** section in this style guide above.<br>Click **Create New Diagram** under the **Diagrams** tab.<br>"You *must* ensure your environment is configured correctly before moving forward through the steps below." |
| Numbers | Write whole numbers one through nine in full.<br>Whole numbers 10 and upwards are written as numerals.<br>Large numbers may be written as numerals with definition (million, billion).<br>Currency does not follow the same rules. See details in the sub-section titled **Currency** above this table. | In this example, we will create 1 diagram and eleven processes to help 1,000,000 customers. | In this example, we will create one diagram and 11 processes to help 1 million customers.|
| Percentages | Written as % and always in numerals. | 10 percent | 10% |
| Pronoun references | Unclear pronoun reference occurs when a pronoun (often "it," "this," "that," or "they") could refer to more than one subject in a sentence, according to practice by [English Composition](https://englishcomposition.org/essential-writing/unclear-pronoun-reference/). Practice clarifying these pronouns, and removing them where appropriate. | After you execute `npm start`, you can run it.<br>In the example above, what exactly are we running? | After you execute `npm start`, you can run the program.<br>In the revised example above, we removed the unclear pronoun. |
| Spacing | Following a period, it is standard to have *one* space before beginning a new sentence. | Avoid using two spaces after a period: "Message correlation is a powerful feature in Camunda Cloud.  It allows you to target a running workflow with a state update from an external system asynchronously." | "Message correlation is a powerful feature in Camunda Cloud. It allows you to target a running workflow with a state update from an external system asynchronously." |
| Spelling | Default to American spelling and US English.<br>See details in the sub-section titled **Spelling** below this table. | Analyse<br>Colour<br>Capitalise<br>Humour<br>Bernd Rücker | Analyze<br>Color<br>Capitalize<br>Humor<br>Bernd Ruecker |
| Times | Use the 12-hour clock, preferably UTC, and uppercase AM or PM where necessary. Always use the corresponding time zone if necessary. See this useful list of [standard abbreviations](https://www.timeanddate.com/time/zones/) for time zones.<br>Be mindful of time zones when writing about events that occur across multiple borders. We aren't imposing any hard and fast rules, because we're dealing with global time zones and hundreds of conventions as a remote-first company.<br>Standardizing on timezones, we typically communicate in or default to CET, ET, and PT. | Avoid using hyphens to display time periods. Instead, use an en dash.<br>To type an en dash on your Mac, type Option+Minus (-). To type an en dash on Windows, hold down Alt and type 0150 on the numeric keyboard; the en dash will appear upon releasing the Alt key. | 1PM CET<br>10AM PT<br>6–10AM PT |
| Voice/Tense | Second person, [active voice](https://www.grammarly.com/blog/active-vs-passive-voice/). | I, me, my.<br>The computer is turned on by pressing the power button. | You, your.<br>Press the power button to turn on the computer. |

### Spelling

- We default to American spelling and US English.
- Think 'Z' not 'S' and 'be damned with U'
    - Analyse -> Analyze
    - Capitalise -> Capitalize  
    - Colour -> Color 
    - Humour -> Humor
    - Bernd Rücker -> Bernd Ruecker 
- Visit the [Oxford American Dictionary](https://www.oxfordreference.com/view/10.1093/acref/9780195392883.001.0001/acref-9780195392883) for details.
- Refer to common differences in British and American spelling within [Oxford's guide to terminology](https://www.oxfordinternationalenglish.com/differences-in-british-and-american-spelling/).
- Write umlauted letters (ü, ä, ö) in full by placing an 'e' after them (ue, ae, oe).

## Punctuation

Default to [American punctuation](https://www.unr.edu/writing-speaking-center/student-resources/writing-speaking-resources/british-american-english).

| Subject| Practice | Avoid |Use |
| -- | -- | -- | -- |
| [Apostrophes](https://www.thepunctuationguide.com/apostrophe.html) |There are three key uses for apostrophes: contractions, plurals, and possessives.<br>Apostrophes are not used for time periods.<br>If the noun ends in an 's', place the apostrophe after the 's'. | 1980's<br>Let us run the command below.<br>We work to assist the businesses's microservices. | Let us = Let's<br>Do not = Don't<br>It is = It's<br>1980s<br>Let's run the command below.<br>We work to assist the businesses' microservices.
| [Commas](https://www.grammarly.com/blog/comma/) | Camunda uses the [Oxford comma](https://www.grammarly.com/blog/what-is-the-oxford-comma-and-why-do-people-care-so-much-about-it/). See details in the sub-section titled "Oxford comma" below this table.<br>Always use a comma to separate independent clauses when they are joined by any of these seven [coordinating conjunctions](https://www.grammarly.com/blog/coordinating-conjunctions/): and, but, for, or, nor, so, yet.<br>Avoid using too many commas and initiating a [run-on sentence](https://owl.purdue.edu/owl/general_writing/punctuation/independent_and_dependent_clauses/runonsentences.html), however. When possible, use short, separate sentences as opposed to several pieces of information in one sentence.<br>Always use a comma to separate a sentence introduction from the remainder of the sentence content (Therefore, Thus, As a result, So, Henceforth,) | Camunda loves its products, GitHub and Google Analytics.<br>We want to automate a process so let's start by creating an account with Camunda Cloud.<br>Therefore we needed to wait for the program to load. | Camunda loves its products, GitHub, and Google Analytics.<br>We want to automate a process, so let's start by creating an account with Camunda Cloud.<br>Therefore, we needed to wait for the program to load. |
| [Em dash](https://www.grammarly.com/blog/why-you-should-love-the-em-dash/) | —<br>As you can see, em dashes are slightly longer than en dashes.<br>On a Mac, execute Shift+Option+Minus (-); on Windows use Ctrl+Alt+Minus (-).<br>The em dash is used to set apart additional, descriptive notes also defined as "parenthetical information," or information you might put inside parentheses.<br>In many programs, you will be unable to create an em dash with a single line. In these instances, please use two hyphens (--) with no white space between to create an em dash.<br>If you find yourself pondering if you're using this correctly, cover up the sentence you've written after the em dash. If the first sentence makes perfect sense without it, then you're onto a winner. | - –<br>In the true spirit of the city Camunda was founded, Berlin, Germany, Camunda is a diverse, distributed and global organization with "Camundos" around the world.<br>At Camunda, we have made it our mission to enable organizations to design, automate and improve these processes, no matter where they are and what they entail.<br>Camunda was founded in 2008, at a time when established industry players were advocating a low-code approach, but we believed in a developer-first approach. | In the true spirit of the city Camunda was founded—that is, Berlin, Germany— Camunda is a diverse, distributed, and global organization with "Camundos" around the world.<br>At Camunda, we have made it our mission to enable organizations to design, automate and improve these processes—no matter where they are and what they entail.<br>Camunda was founded in 2008, at a time when established industry players were advocating a low-code approach—but we believed in a developer-first approach. |
| [En dash](https://www.grammarly.com/blog/dash/) | –<br>The en dash is shorter than an em dash, and is not the same as a hyphen.<br>To type an en dash on your Mac, type Option+Minus (-). To type an en dash on Windows, hold down Alt and type 0150 on the numeric keyboard; the en dash will appear upon releasing the Alt key.<br>The en dash should predominantly be used for date and time ranges. | -<br>The scheduled window for the installation is 1-3pm. | The scheduled window for the installation is 1–3pm. |
| Hyphens | Use the hyphen (-) to create a compound adjective (where you squash two describing words together, just like German, but easier to read.) | User friendly interface.<br>Biggest ever release. | User-friendly interface.<br>Biggest-ever release. |
| [Prefixes](https://dictionary.cambridge.org/us/grammar/british-grammar/prefixes) | Prefixes are a stumbling block for many native English speakers. There's no right or wrong way to use them, because it genuinely depends on the dictionary you use, the style guide you follow, or just how confusing we want to make the language.<br>Prefixes are basically a few letters tagged at the front of a word to create a different meaning.<br>Ensure you omit the hyphen!<br>If at any point you feel a word doesn't look quite right, just send DevRel a quick Slack, because, unfortunately, there are a ton of exceptions. | Un happy<br>De activate<br>Re-activate<br>Un-do | Unhappy<br>Deactivate<br>Reactivate<br>Undo |
| Quotation marks | We only use double quotations to illustrate the words spoken by another individual.<br>We do not use quotations when referring to buttons or programs, nor sections of a document.<br>See the **Bolding** section in the table above. | One of the greatest benefits of this project has been the close cooperation between business and IT. -Michael Voeller, Head of Project and Demand Management<br>Navigate to the "**Decisions**" section of this manual. | "One of the greatest benefits of this project has been the close cooperation between business and IT," said Michael Voeller, Head of Project and Demand Management<br>Navigate to the **Decisions** section of this page.<br>Preferably, we would link the **Decisions** section in the example above so the user doesn't have to go out of their way to find it. |
| Semicolons | Semicolons are a wondrous use of punctuation when understood! | Semicolons are stronger than a comma, but not as divisive as a period.<br>Use semicolons to connect two related but independent clauses (the two pieces of information are related to one another, but they can also stand alone.)<br>Do not capitalize the first word of the second clause following the semicolon unless it is a proper noun or acronym.<br>Semicolons are also used to replace conjunctions (and, or, etc.) | We've automated several processes for our partners, we love to see them succeed. | We've automated several processes for our partners; we love to see them succeed. |

### Oxford comma

- **Why we use it**: The Oxford comma is extremely helpful in developing a clear list of items or subjects. Take a look at the example below where we do not use an Oxford comma to separate all of the subjects:

    **"Camunda loves its products, GitHub and Google Analytics."**

In the example above, one might assume Camunda's products include GitHub and Google Analytics, when in fact, they are not Camunda products. Instead, you want to state that Camunda loves its products, Camunda loves GitHub, and Camunda loves Google Analytics.

To help clarify this statement, we need to separate all of the subjects by a comma so the reader understands exactly what we are trying to say.

**"Camunda loves its products, GitHub, and Google Analytics."**

- **Why it's preferred**: The Oxford comma is preferred because it erases potential confusion within a sentence or list. Take a look at the second example below:

	**"Rachel Ray finds inspiration in cooking her family and her dog."**

In the example above, one might assume Rachel Ray finds inspiration in cooking her family and cooking her dog, when in reality, Rachel Ray enjoys all three of these things separately (thankfully.) We should adjust the sentence to the following to increase clarity and decrease ambiguity:
	
**"Rachel Ray finds inspiration in cooking, her family, and her dog."**

## Formatting, organization and structure for conceptual pieces

The following table outlines best practices for conceptual pieces of information in the document. These pieces usually introduce the reader to a topic with a goal of teaching the reader about that topic before introducing further details or steps for implementation. (For example, an opening summary or overview of the document subject.)
| Subject | Practice| Avoid | Use |
| -- | -- | -- | -- |
| Concision | One of the most important techniques in technical writing is keeping your text short, clear, clean, and concise.<br>As a result, work to eliminate unnecessary words or phrases to reduce the amount of text the user must read.<br>To help test how readable and user-friendly your text is, check out these [readability metrics](https://medium.com/technical-writing-is-easy/readability-metrics-and-technical-writing-b776422eaba) you can use.<br>Check out this additional [guide to Hemingway](https://medium.com/technical-writing-is-easy/hemingway-app-for-technical-writing-f994c8b2412a), a great tool to test the readability and user experience of your document. | Camunda Cloud is powered by Zeebe, a new class of BPMN workflow engine that delivers true horizontal scalability and enables high-performance use cases that were once beyond the realm of workflow automation.<br>Camunda Cloud is architected for the cloud from the ground up. It is ideal for cloud application use cases such as microservices-based applications and integrates seamlessly with best-in-class cloud components. | Camunda Cloud is powered by Zeebe, a new class of BPMN workflow engine that delivers horizontal scalability and high-performance use cases for workflow automation.<br>Ideal for microservice-based applications, Camunda Cloud easily integrates with industry-leading cloud components. |
| Separated paragraphs | A user-friendly experience is a clean, concise one with as few words as possible.<br>A user-friendly experience separates these chunks of information into separate sections for easy reading and organization.<br>Avoid large, lengthy paragraphs. Instead, try to keep your paragraphs to a maximum of four or five sentences, and then begin a new paragraph introducing more information. | Message correlation is a powerful feature in Camunda Cloud. It allows you to target a running workflow with a state update from an external system asynchronously. This tutorial uses the Node.js client, but it serves to illustrate message correlation concepts that are applicable to all language clients. We will use Simple Monitor to inspect the running workflow state. Simple Monitor is a community-supported tool, and is not designed to be used in production - however, it is useful during development. | Message correlation is a powerful feature in Camunda Cloud. It allows you to target a running workflow with a state update from an external system asynchronously.<br>This tutorial uses the Node.js client, but it serves to illustrate message correlation concepts that are applicable to all language clients.<br>We will use Simple Monitor to inspect the running workflow state. Simple Monitor is a community-supported tool, and is not designed to be used in production - however, it is useful during development. |
| Short sentences | Avoid long, lengthy sentences and practice short, separate sentences when describing various processes and technologies. This will help the user take a step-by-step approach, piece by piece, through a larger conceptual item without getting lost or feeling overwhelmed. | At Camunda we have made it our mission to provide developers with the best experience because our platform and tools are easy to get started and use in your environment right away, with full public access to all our docs, open APIs to integrate with just about anything, and a vibrant community of 100,000 developers. | At Camunda we have made it our mission to provide developers with the best experience. Our platform and tools are easy to get started and use in your environment right away. We offer full public access to all our docs and open APIs. We strive to integrate with just about anything, and a vibrant community of 100,000 developers. |
| That | Avoid overuse of the term "that." More often than not, the term is repetitive or unnecessary.<br>To practice, double check your sentences by typing Ctrl+F and searching the term "that." Read your sentences without the term to see if the sentences still make sense. If they do, chances are you can remove the term.<br>Typically, you can remove "that" before most nouns, though you may want to keep "that" before an adjective. | To confirm that the first gateway works correctly, complete the steps below: | To confirm the first gateway works correctly, complete the steps below: |
| Titles and headers | Sentence case spelling in titles and headers.<br>For sentence case spelling, only capitalize the first word and any proper nouns.<br>Ensure titles and headers are descriptive enough so Camunda doesn't have a large surplus of mere "Overview" pages.<br>In Markdown, do not include a colon in your headers. | How To Open A File<br>Our travel guide to berlin, germany<br>Camunda Cloud overview<br>Readiness probe as yaml config: | How to open a file<br>Our travel guide to Berlin, Germany<br>What is Camunda Cloud?<br>Readiness probe as yaml config |
| Whether or not | "Whether X produces the expected value or not" can seem a bit repetitive.<br>In most cases, it is appropriate to remove the "or not" at the end of the sentence to avoid repetition and unnecessary text.<br>In a picturesque world, we should lean on "If X produces the expected value," entirely eliminating the need to use the "whether or not" terminology. | This specifies whether host language resources like classes and their methods are accessible or not. | This specifies if host language resources like classes and their methods are accessible. |

### Titles and headers (sentence case):

- **Why we use it**: Camunda uses sentence case spelling in titles and headers within technical documentation because this format is more synchronous with the way and flow of human speaking and writing, allowing a more modern and user-friendly approach to the document.
- **Why it's preferred**: On top of its modern structure, sentence case titles and headers tend to read more clear, clean, and neat on the page. While title case is great for printed newspapers and magazines, sentence case tends to read more friendly on the web in a conversational style. See a few of our examples below:

    **"Setting up your first development project"**
    **"Monitor your process in Operate"**
    **"Getting started with Camunda Cloud"**

## Formatting, organization and structure for implementation steps

The following table outlines best practices for the implementation section of the document. This section usually offers a distinct thing or things for the reader to do (for example, a list of steps).

| Subject | Practice | Avoid | Use |
| -- | -- | -- | -- |
| [Admonitions](https://docusaurus.io/docs/markdown-features/admonitions) | Currently within Docusaurus, we have the opportunity to utilize [admonitions](https://docusaurus.io/docs/markdown-features/admonitions) to separate important notes in our documents. Please utilize these admonitions appropriately according to [Docusaurus' guidance](https://docusaurus.io/docs/markdown-features/admonitions). This will add a significant boost to our UX! | Note: This is the `bpmnProcessId`, you'll need to create a new instance. | :::note<br>This is the `bpmnProcessId`, you'll need to create a new instance.<br>::: |
| Bulleted lists | Use bulleted lists for a list of three or more items.<br>You may use complete sentences in bulleted lists (followed by a period), or you may avoid using periods in your bulleted lists if the items are fragmented or short (apples, bananas, grapes, for example).<br>Always capitalize the first word of the item in the bullet. | Do not use bullets for a series of steps or instructions. Instead, use numerical lists. See **Numerical lists/steps** in the table below.<br>Avoid using commas and/or semicolons in bulleted lists as this can cause confusion between listed items.<br>Do not lowercase the first word following each bullet. Ensure capitalization. | Camunda Cloud can be used for several purposes, including:<br><li><ul>To automate a process</ul><br><ul>To avoid bottlenecks in business</ul><ul>To create an organized framework</ul></li> |
| Button names| Click **Next**.<br>Use the arrow icon > to list out a series of buttons the user needs to press.<br>See **Menu bar traversal** for details in the table below. | Italics and quotes.<br>Click "Next" and then select "Open" and press "Enter" at the bottom of the page. | Verb + **Button Name**<br>Can use screenshot or icon in instructions.<br>Click **Next** > **Open** > **Enter** |
| Button verbs | Use common terms like **Click** or **Select**. | Hit, press<br>Hit the **Next** button. | Click, select<br>Select **Next**. |
| Code blocks | Use code blocks when you are specifically referring to components within code or filenames.<br>Use code block highlighting, if available. This will not apply to inline code, but instead for larger blocks of code. | Do not use code blocks for anything outside of code or filenames, including buttons, titles, etc. | Ensure the `taskID` on your JavaScript page is the same.<br>Execute the following command:<br>`npm start`<br>```javascript var = 1;``` |
| Filenames | Place filenames within a code block, as noted in the component **Code blocks** in the table above. | Avoid bolding or italicizing filenames. | Open `codeStuff.txt` |
| Images | Ensure your images are appropriate in size and clarity.<br>All images should include alt text for accessibility purposes.<br>If using a screenshot to show steps to fill out a UI, include text above or below the screenshot that includes input text.<br>Crop the user bar and any personal information out of your photo or screenshot. This may include names, passwords, usernames, etc. | Avoid blurry screenshots. Avoid including any personal information in your images. Avoid images that are unnecessarily large or bulky to keep the page clean and concise. | N/A |
| Links | Link text whenever it refers to a separate section of our documentation or website. No section reference should go unlinked.<br>Ensure links are externally linked, meaning when clicked, the link will open in a separate tab and not remove the position the user is in within the documentation in their current tab.<br>Please also make sure any repo links are linked to the anchor link on the repo instead of the master/main/{branch name} link. | Visit our Getting Started Guide for more details. | Visit [Get started with Camunda](https://docs.camunda.org/get-started/) for more details. |
| Menu bar traversal | When listing out a series of buttons as steps, use the arrow key to break between buttons. | In the "File" menu, click "Save as." | In the **File** menu, click **Save as**.<br>Go to **File > New File > BPMN Diagram**. |
| Numerical lists/steps | When possible, replace a loaded or long sentence with a series of steps to keep things clear and concise.<br>See details in the sub-section titled **Numerical lists/steps** below this table. | Use the Camunda Modeler to open the Payment Retrieval process then click on the Approve Payment Task. Change the activity type to Business Rule Task in the wrench button menu. | 1. Use Camunda Modeler to open the **Payment Retrieval** process.<br> 2. Click the **Approve Payment** task.<br> 3. Click the wrench icon, revealing a menu, to change the **activity type** to **Business Rule Task**. |
| Please and thank you | In technical writing, give direct, clear instructions. You do not need to ask the user to "please" do something.<br>Do not use "please" in a numerical or bulleted list.<br>This may seem rather blunt, but our goal is to create clean, direct instructions and documentation. | Please open the link. | Open the link. |
| Tabs | When listing several different command options across operating systems, ensure these different references are separated into their own tabs for a clean, clear UX. | See this [documentation](https://docs.camunda.io/docs/components/zeebe/deployment-guide/getting-started/create-process-instance/) example. | See this [GitHub](https://github.com/camunda-cloud/camunda-cloud-documentation/pull/345) example. |
| Visuals | Keep visuals in mind as you create a document to avoid large, lengthy paragraphs. Consider the following:<br>Would this series of information be more visually-appealing in a table?<br>Should I add a brief video, gif, or image to show the user the more complex steps I've described? | Avoid several paragraphs of information contained in large bodies of text. | Practice clean, clear, and brief chunks of text. Consider a table or image to display the information you've outlined. |

### Numerical lists/steps:

- **Why we use them**: Many users do not enjoy reading long sentences or paragraphs because they can get lost in a lengthy series of information and actions. Instead, Camunda utilizes a series of steps to break each concept and/or action into its own numerical line. This way, the user can more easily follow along with the process.
- **Why they're preferred**: Steps allow step-by-step guidance so the reader can more easily track their progress or a particular place where they may get stuck/pause. See an example of this transformation below for added clarity:

**Change this**:
    
Create a new Maven project

Start by creating a new Maven project in your IDE. If you're using Eclipse, you can follow these steps:

In Eclipse, go to File / New / Other …. This opens the New Project Wizard. In the New Project Wizard, select Maven / Maven Project.

Click Next.

On the first page of the New Maven Project Wizard, select Create a simple project (you can skip archetype selection). Click Next.

**To this**:
    
Create a new Maven project
Create a new Maven project in your IDE. If you're using Eclipse, follow these steps:
1. In Eclipse, go to **File > New > Other**. This opens the New Project Wizard.
2. In the New Project Wizard, select **Maven > Maven Project > Next**.
3. On the first page of the New Project Wizard, select **Create a simple project** (you can skip archetype selection) **> Next**.

## Product names and other terminology

**NOTE: This section is an *overview* of a few commonly misunderstood Camunda terms. Refer to the Camunda Technical Writing Terms and Glossary for a complete list of frequently used Camunda terms in documentation and their proper use.**

**NOTE: To avoid overuse of company jargon or confusion, please refer to [this summary of OMG specifications](https://www.omg.org/spec/category/business-modeling/) when referring to acronyms within your documentation.**

| Subject | Practice | Avoid | Use |
| -- | -- | -- | -- |
| Acronyms | BPMN, DMN, TTFN – the use of acronyms should be judged by the level of audience knowledge.<br>For a technical audience, use industry standard acronyms from the start. However, for new concepts or emerging acronyms, write the process in full first, and then follow with the acronym at the next use.<br>For a non-technical audience, always write an acronym in full the first time you use it in any new piece of content. Afterwards, it can be abbreviated. | Avoid abbreviating the term on its first use if the documentation is for an audience which may be non-technical. | Most often, you should spell out the acronym on first reference and abbreviate thereafter depending on the level of audience knowledge. |
| And/or | Either or both of two stated possibilities. | You can further parallelize archiver and(or) importer within one node using the following configuration parameters | You can further parallelize archiver and/or importer within one node using the following configuration parameters |
| Camunda Cloud | See details in the sub-section titled **Camunda Cloud** below this table. | Avoid confusion of Camunda Cloud components with other Camunda product components. | See details in the sub-section titled **Camunda Cloud** below this table. |
| Camunda Platform | See details in the sub-section titled **Camunda Platform** below this table. | Avoid confusion of Camunda Platform components with other Camunda product components. | See details in the sub-section titled **Camunda Platform** below this table. |
| File extensions | Do not capitalize file extensions like .pdf, .doc, etc. | Uppercase | Lowercase |
| [Job titles](https://grammar.yourdictionary.com/capitalization/capitalization-of-job-titles.html) | Do not capitalize a job title if listed after a name.<br>Do capitalize a job title if listed before a name. | Charley Mann, Content Strategist | Charley Mann, content strategist |
| Process | See details in the sub-section titled **Process vs. workflow** below this table. | Avoid "workflow automation" and "workflow instance" where "process automation" and "process instance" is preferred. | We prefer process automation and process instance over workflow automation or workflow instance.<br>See details in the sub-section titled **Process vs. workflow** below this table. |
| Workflow | See details in the sub-section titled **Process vs. workflow** below this table. | Avoid "workflow automation" and "workflow instance" where "process automation" and "process instance" is preferred. | We prefer process automation and process instance over workflow automation or workflow instance.<br>See details in the sub-section titled **Process vs. workflow** below this table. |

### Camunda Cloud:

**Camunda Cloud** is made up of the following **components**:

- Console
- Cloud Modeler
- Camunda Modeler 
- Zeebe
- Operate
- Tasklist
- Optimize
- IAM

Operate and Tasklist may need to be qualified outside of Camunda Cloud context.

Modelers must be qualified so as not to be confused.

**NOTE: An alternative way to use Camunda Cloud is to host it yourself. This is called Camunda Cloud Self-Managed.**

### Camunda Platform:

**Camunda Platform** is used in conjunction with the following **products and web applications**:

- Camunda Modeler
- Camunda Cockpit or Cockpit
- Tasklist
- Camunda Optimize
- Cawemo

Some of these can drop their Camunda qualifier if used within the context of Camunda Platform.

### Process vs. workflow:

**Process automation** and **process instance** over *workflow automation or workflow instance*.

Replace **workflow** (flows) with **process**:
- workflow
- flows
- Zeebe workflows
- workflow instance
- workflow instance variable

Exceptions:
- workflow engine
- sequence flow
- process flow