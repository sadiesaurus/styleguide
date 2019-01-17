# Shopify Help Center style guide

**This guide is intended to be your go-to resource if you're writing or reviewing docs.** It’s here to help keep up the consistency and quality across our self-help materials, and to save Shopifolk from puzzling over points of style or formatting during the docs-writing process (we've already done that so you don't have to... <strike>your</strike> you’re welcome). These objectives both serve the same end:  to write docs that educate and empower Shopify’s merchants.

**If you’re writing something other than documentation**, you might find it more helpful to check out the **[Shopify Admin Style Guide](https://styleguide.myshopify.com/)**.

## Contents

1. [Why do I need this guide?](#why-do-i-need-this-guide)
2. [Planning for your audience](#planning-for-your-audience)
2. [Organizing the doc](#organizing-the-doc)
3. [Documenting tasks](#documenting-tasks)
4. [Voice and tone](#voice-and-tone)
5. [Grammar, punctuation, and typography](#grammar-punctuation-and-typography)
6. [Vocabulary](#vocabulary)
7. [Metadata](#metadata)
8. [Internationalization](#internationalization)

---

## Why do I need this guide?

Technical documentation from the companies who do it best looks like it was all written by a single person. That level of consistency of formatting and style adds to the docs' usability by helping to make the text itself almost transparent, with few surprises along the way, and without the text of a doc calling attention to itself (through irregularities in the tone, unexpected formatting, etc.).

**How should I use this guide?** Documentation is complicated. This guide offers detail-oriented descriptions of best practices that are based on in-house conventions, generally accepted docs wisdom, and design principles:

* For a quick summary of style and formatting, refer to the overviews that follow [each major section](#contents) of this guide.
* For questions relating to vocabulary, refer to the [Shopify Admin Style Guide](https://styleguide.myshopify.com/content/vocabulary) or to the [Docs Lexicon](#vocabulary). In cases where this guidance doesn't cover the term in question, defer to [Merriam-Webster](https://www.merriam-webster.com/).
* For a quick summary of the preferred writing style in the docs, refer to the [Voice and tone](#voice-and-tone) section. For a broader view, check out the [Shopify Admin Style Guide](https://styleguide.myshopify.com/).
* For a list of typographical conventions -- like when you should use bold, italics, etc. when writing documentation -- refer to [Typographical conventions](#typographical-conventions) section of this guide.

In keeping with Shopify culture, the docs team welcomes feedback on the technical documentation: send your questions, comments, suggestions, or even complaints (we love those) to <a href="mailto:docs@shopify.com">docs@shopify.com</a>. This is an internal Shopify address though, so please don’t give it out to customers. For quick fixes or issues just drop by the <a href="https://shopify.slack.com/messages/docs/">#docs</a> channel on Slack.

---

## Planning for your audience

Shopify’s documentation should reflect its intended audience. For any given doc, we can expect a wide spectrum of Shopify users who will encounter it:

<table>
	<tr>
		<th width="25%">User type</th>
		<th>Relationship with Shopify</th>
	</tr>
	<Tr>
		<td>Prospective users</td>
		<td>not signed up yet, possibly doing the free trial</td>
	</tr>
		<td>Novice users</td>
		<td>they’ve signed up but they might not have sold online before, possibly not very computer-literate, new to Shopify concepts and workflow</td>
	</tr>
	<tr>
		<td>Experienced, confident users</td>
		<td>possibly been using Shopify for some time, familiar with the basic concepts and workflow, confident with computers, able to try some customization with guidance
	<tr>
		<td>Highly technical users</td>
		<td>experienced confident users with extensive computing experience, who are happy to experiment and take risks; experienced problem-solvers. These users are expert learners and can often support themselves</td>
 	</tr>
 </table>
<br>

Each of these different users will likely have different expectations for the doc. Let's take a look at how that might play out:

<table>
	<tr>
		<th width="25%">User type</th>
		<th>What they want from the docs</th>
	</tr>
	<tr>
		<td>Prospective users</td>
		<td>a quickstart guide, conceptual overviews</td>
	</tr>
	<tr>
		<td>Novice users</td>
		<td>clear step-by-step instructions, conceptual overviews, definitions of terms, tutorials, context-sensitive help</td>
	</tr>
	<tr>
		<td>Experienced, confident users</td>
		<td>clear step-by-step instructions, conceptual overviews, definitions of terms, more challenging tutorials, context-sensitive help</td>
	</tr>
	<tr>
		<td>Highly technical users</td>
		<td>procedural instructions (can be terse), code fragments, pointers to information sources. Don’t waste their time with verbiage</td>
 	</tr>
 </table>

However we imagine Shopify’s merchants, our aim for the docs remains the same: to accommodate a wide range of users and their objectives. We can do this by presenting information in a way that’s inclusive of different levels of expertise, different learning styles, and different workflows through a given doc.

The following sections of this guide describe how to apply an understanding of our audience to the writing and document design of our docs.

---

## Organizing the doc

Shopify’s docs receive well over 100,000 sessions per week. Odds are that there are people reading the docs [at this very moment](https://www.google.com/analytics/web/?hl=en#realtime/rt-overview/a82702w67835191p69823666/). Let’s imagine how they might be going about it: maybe one is working through a long, multi-stage setup process to integrate a third-party app into his admin; maybe another is using her tablet to check out the details of Shopify POS and see if it could be used at her cafe; maybe one is trying to make a quick edit to his storefront in the half hour he has left before going to pick up his kids from school. In all of these different situations, the individual user benefits from documentation that’s findable, usable, and relevant &mdash; or, in short, _organized_.

We can follow a few key practices to organize the contents of our docs: headings and chunks.

### In this section
* [Headings](#headings)
* [Chunks: concept, task, reference](#chunks-concept-task-reference)
* [Concept chunk](#concept-chunk)
* [Task chunk](#task-chunk)
* [Reference chunk](#reference-chunk)
* [Internal cross-references (links)](#internal-cross-references-links)
* [Glossary definitions](#glossary-definitions)

### Headings

Effective headings make it clear to the readers which sections of a doc are most relevant to their current tasks (findability), and provide them with a good sense of their progression through the overall doc as they move from one task to the next (usability).

**For page-level or topic-level headings, use short, gerund statements** (like “Creating products”) **or short noun phrases** (like "Themes for your online store"). Don't use imperatives. Make sure that each page title is unique, since duplicate titles are confusing when presented alongside each other in a page of search results. Consider also how much context the title will supply to the reader when it appears as a search result in the Help Center. Is the title clear enough for a reader to tell whether a page contains the information that they want?

For docs with longer titles, consider using a shorter variation in the short_title field of the doc’s YAML header. If you use a shorter title for the sidebar, then make sure that it clearly conveys the same topic or concept. See [Metadata](#metadata).

For section-level headings (H2 and lower), use imperatives for tasks (like “Add a customer”), and either gerund statements or noun statements for broader, conceptual topics (like “Responding to in-app feedback” or “Domains overview”).

As a general rule, **the lower a heading is in the doc’s hierarchy, the more flexible you can be in terms of tone** (it can be longer and more specific, less formal, etc.).

**Avoid pronouns in headings to keep them short**. Go with “Connecting Facebook accounts” rather than “Connecting a Facebook account” or “Connecting your Facebook account”.

**Avoid long strings of nouns in a heading**. Go with “Posting products” (or "creating posts") rather than "creating product posts" (two nouns, perhaps not terrible) or “creating product post pages” (three nouns, definitely terrible).

**Try to maintain the heading hierarchy throughout the doc**: don’t skip heading levels arbitrarily or abandon structure just because you're deep in the hierarchy. The heading hierarchy helps the readers to position themselves within the doc, whether they’re progressing through a specific workflow or quickly scanning through a doc to evaluate it. However, if the prescribed heading level doesn't work in a specific context or particular situation, you can make judicious use of a lower-level heading.

**Keep the key descriptors close to the front of a heading** to make the heading easier to scan quickly. Don’t bury them under “How to”, “To”, etc.

  > ✓ Add a product<br>
  ✕ How to add a product

**Maintain grammatical parallelism between headings of the same level.** The heading `Next steps` is an exception, and may follow a series of otherwise grammatically parallel headings:

  >✓ Boost a post, Choose an audience, Fulfill an order<br>
  ✕ Boost a post, Choosing your audience, How to fulfill your orders

**In most cases, headings should be statements rather than questions.** Save question-style headings for the Next steps, FAQs, or low-level headings that address specific functions.

**Use sentence case for all headings**, but no periods at the end. References within headings to interface elements or buttons should be formatted and capitalized according to how they appear in the Shopify admin.

### Chunks: concept, task, reference

Most docs can be organized according to three different types or “chunks” of information: concept, task, and reference. If written information is arranged in discrete chunks, readers can scan it faster to find the specific part they’re looking for. In many cases, readers don’t want to read a whole page or sequence of pages from start to finish: they’ll just jump from one relevant chunk to the next. These jumps are easier to make if the chunks are easy to identify and distinguish. Any doc you write can contain any number of chunks from these three categories, but try not to nest chunks or mix chunk types within a single paragraph.

#### Concept chunk
A concept chunk answers the question “What is…?” It will include descriptions, overviews, broad outlines of processes without specifics, generic steps. Also definitions. Can be chatty. Might be read only once. In practice, most docs begin with a concept chunk that introduces the topic, and sometimes answers the question “Why is this a thing?” This bit of context can encourage best practices at the storefront level, and help merchants see why they might want to use a particular feature of Shopify.

A concept chunk might look like this:

> A product is an individual item for sale in a Shopify store. Products are often physical goods, but they can also be a digital download (such as a movie, music or ebook file), or a service (equipment rental, work for hire, customization of another product or an extended warranty.)


#### Task chunk

A task chunk answers the question: “How do I …?” It will include step-by-step instructions for specific tasks. Might be read several times. Might be read by users who are actively switching between the doc and another screen or window on their computers to complete a given task.

A task chunk might look like this:

>Steps:
>1. From your shop admin, go to the **Products** page.
>2. Click the product you want to hide.
>3. In the **Visibility** section, uncheck the channels you want to hide the Product from.
>4. Press **Save**.


See [Documenting tasks](#documenting-tasks) for a full description of task-oriented writing.)

#### Reference chunk

A reference chunk answers the question "...?" It will offer a terse lookup or referral information, definitions, sitemap, index, list of tables, list of screenshots, or additional supportive information. Reference chunks are designed for speed &mdash; users want to read it, then move on quickly.

Another example of a reference chunk is the Next steps section that follows a doc. Also FAQs.

A reference chunk might look like this:

<table>
    <tr>
        <th width="20%">Attribute</th>
        <th>Value</th>
        <th width="20%">Default</th>
    </tr>
    <tr>
        <td>`data-shop`</td>
        <td>The myshopify domain (such as `storename.myshopify.com`) connected to the button.</td>
        <td>Your Shopify domain</td>
    </tr>
    <tr>
        <td>`data-product_handle`</td>
        <td>The `product_handle` of the featured product, which is based on the product's title. Each of your products has a unique handle in Shopify.</td>
        <td>The featured product's `product_handle`</td>
    </tr>
</table>


### Internal cross references (links)

Links to other topics in the Help Center are a great way to send merchants to related information that helps them complete a task or learn about a concept. But too many links can make content harder to read, and following a link distracts the reader from the main point. Links without enough context can leave a reader wondering if they should go to wherever the link might take them. To make the most of our cross references, follow a few guidelines.

**Add links judiciously** so that they don’t overwhelm the reader with too many options. If there’s only a small chance of a reader needing to follow a link, leave it out.

**Ensure that every inline link is clearly relevant and of value to the task or concept**. Don't add links just because another concept is mentioned in passing.

**Keep the number of inline links (links within sentences and paragraphs) as low as possible**.

**Try to avoid links in steps of a task** because following such a link can take the reader out of the flow and the context, and into a completely different topic.

**If you need to include several links in a paragraph or section, try to group the links together** so that the reader knows they are secondary but related information. This can prevent having a block of text that is peppered with distracting links.

**Give preference to cross references at the end of sentences, paragraphs, or notes**. Provide some introductory context to help the reader know whether visiting the link will be helpful to them.

>To access domain settings, you need to have the Domains permission. For information on viewing and setting your permissions, see [_Setting staff account permissions_](/).

### Glossary definitions

The glossary generates contextual definitions for terms added to the `/app/assets/javascripts/glossary.json` file. Glossary terms underline in-text and serve in pop-up bubbles when hovered over. Terms serve the first time they appear from the point at which a person enters a page: if a person enters a page at the top, then the first instances of glossary terms highlight; if a person enters a page at an H2 subhead, then the first instances of glossary terms highlight from that point onwards.

To add a term to the Help Center glossary:

- Definitions should describe “description + function." I.e. for a water bottle, a definition could be “A container (description) that holds water (function).” The function can also describe what the term doesn’t do, if that provides more context than a description of what it does do.
- Do not use a term to define itself.
- For acronyms, begin definition by giving the full term, and then providing the definition. For example, “PIN - Personal Identification Number. A private password that . . .”
- Aim to keep glossary definitions as short as possible. One sentence is ideal. Glossary terms will need to display in mobile, so a long definition could be problematic.
- Definitions should be singular, not plural.
- Use your judgement with examples. In most cases, you do not need to provide an example, as the user will get context from the topic in which the definition resides. However, in some cases an example is necessary.
- For terms that are verbs, define the infinitive.
- If a term applies to Shopify uniquely, then use “the”, as in “Admin: the place where you can set up your store.”
- If a term is a universal concept, then use “a”, as in “Ecommerce site: A website that sells goods or services.” Use your best judgment on this.

---

## Documenting tasks

Most of the docs are essentially task-oriented:  they are designed to guide the readers through the specific steps required to set up and run their stores. The best docs will save the readers’ time by helping them complete the tasks in view as quickly as possible. Ideally, they will also help build the readers’ mastery of Shopify. The specific ways we present task-oriented information in a set of instructions have a big impact on their effectiveness, in terms of both saving time and building mastery.

**Start by providing introduction and context.** In most cases, a doc shouldn’t begin by launching the reader into a set of instructions without offering any context first. Give some brief introductory comment or define a key concept that is relevant for the current doc. Try to anticipate what information would benefit the readers most as they begin to read the instructions. This is true also for major sub-sections within a doc. If you begin with a numbered step immediately after a heading, consider whether or not some introduction or context at the outset might help the readers through the process.

**Document the simplest and most straightforward way to complete a task.** When there is more than one way to complete a task, it can be confusing to a merchant if both methods are described.  Instead, choose the simplest way.  If you want to include information about another method, then add a tip referring to it without documenting the whole process.

### In this section
* [Tasks](#tasks)
* [Documenting choice](#documenting-choice)
* [Representing results of user actions](#representing-results-of-user-actions)
* [Including screenshots](#including-screenshots)
* [Using note blocks](#using-note-blocks)
* [Documenting as teaching](#documenting-as-teaching)

### Tasks

**Tell the user what they can do with Shopify, not what Shopify can do**. Structure the documentation around user actions rather than product features. They don’t want to read a specification; they want to get their shop working so they can sell stuff:

>✓ Use this feature to keep track of key updates and promotions.<br>
✕ This feature notifies you about key updates and promotions.

**Divide up the instructions in a way that anticipates how the readers might think of the task at hand.** To that end, try to separate the conceptual side from the mechanical:  the readers think of what they’re doing as “adding products to the cart” rather than “clicking on the ‘add products’ button; entering the products’ names; clicking save; etc..” This helps to conserve your readers’ attention, and makes it easier for them to switch between sub-tasks on a docs page and the Shopify admin.

**Highlight optional steps** in a task by beginning the step with "Optional:". Do not use bolding or other text formatting. Use your discretion when highlighting a step as optional: flagging consecutive steps as optional can be distracting, and it should not be used for steps where there is a consequence for not performing the step. For example, providing an SEO description for each product is optional, but not providing this description will hinder search engine hits.

In general, **aim for short lists of numbered steps**, which are more manageable for the reader than long lists. If you have a task that seems to require more than five or six steps, consider whether or not it can be separated into separate sub tasks with their own respective sub headings.

**Make sure that the instructions for major tasks within a longer doc are effective standalone piece of documentation.** If the instructions for a task pick up abruptly where an earlier task left off, the readers who begin at that point might struggle to orient themselves in the workflow. Start documenting each task at the beginning of the workflow required to complete it (ie. the Shopify admin).

**Introduce a procedure with the word Steps:**
Add #### Steps: before a numbered list. For example:

>You can print a test shipping label to make sure that your printer is set up properly. You will not be charged for printing a test label.
>
> Steps:
>1. From your Shopify admin, click **Settings**, and then click **Shipping**.
>2. In the **Shipping labels** section, click **Print test label**: {{ '/manual/shipping/usps-test-label.png' | image }}

**In general, avoid grouping multiple actions together in a single numbered step**. Each step should include only one or two user actions:

> Steps:
>1. From your Shopify admin, click **Products**.  
>2. Click **Add a product**, and then enter the product details.

**For navigation steps, simplify the instructions**. Use the following shorthand to make the step more scannable:

> 1. From your Shopify admin, go to **Products** > **Collections**.

You can also use this shorthand for steps which involve a drop-down list:

>1. From your Shopify admin, go to **Products**.
>2. Click **More actions** > **Find more products to sell**.

**For conditional cases, lead with the “if”** so the readers don’t have to read an entire sentence only to find out that the condition does not apply to them, and include a "then" to help distinguish between the condition and the outcome:

>✓ If you need Z, then click A, B, and C.<br>
✕ Click A, B, and C, if you need Z.

**Use command verbs consistently** when you're directing the reader’s actions:
<table>
	<tr>
		<th>Go with</th>
		<th>Avoid...</th>
	</tr>
	<tr>
		<td>enter</td>
		<td>type in / input / write</td>
	</tr>
	<tr>
		<td>click</td>
		<td>click on</td>
	</tr>
	<tr>
		<td>Click Themes</td>
		<td>click the Themes button</td>
	</tr>
	<tr>
		<td>tap (touchscreen)</td>
		<td>click, select</td>
	</tr>
</table>

Readers will likely be glancing back and forth between the doc and other screens (such as their Shopify admin) throughout process of reading a doc. **Use visual and rhetorical signposts to make it easier for them keep track of their place in the doc**. Small chunks, smart tasking and numbering, and meta steps all make it easier to switch between tasks and screens.

**Avoid using language that implies direction**, such as “Click the button in the top right-hand corner.” Use the name of the button and a screenshot instead.

**Avoid telling the user to "find" or "locate" something in a task.**
>✕ Find the **Pinterest** section, then click **Remove channel**.<br>
✓ In the **Pinterest** section, click **Remove channel**.

**Use markdown rather than HTML for lists of numbered steps**. This makes sure that the information is indented properly, which creates visible structure that helps the reader scan the information and discern the hierarchy of the doc.

In some cases you'll want to refer the reader to a demo or an example. We've set a standard phrase for this sort of thing:

>✓ To see how this feature works, [visit the demo store](#).<br>
✕ Check out a demo of a [password protected store](#).

**Link to the _Keyboard shortcuts_ page in the docs' Productivity section** when asking the reader to copy and paste content (see `https://docs.shopify.com/manual/intro-to-shopify/productivity/keyboard-shortcuts#basic-shortcuts`). In most cases, you'll want to do this with only the first reference to copy and paste on that page of documentation.

>✓ First, [copy and paste](/manual/more/productivity/keyboard-shortcuts) the embed code.<br>
✕ First, copy+paste the embed code (`Ctrl+C`).

### Documenting choice

Use the verb `select` when you're telling the reader to pick something from a finite number of choices (like from a list or drop-down menu), and use `choose` when you're referring to the reader making a decision that's more open-ended (like “You have to choose what kind of store you want to open”).

**Use consistent phrasing when referring to the reader’s choice**. Use the most direct “If you want to…” instead of more formal options such as “If you would like to…” or “if you wish to…”:

>✓ If you want to add a product, click Add product.<br>
✕ If you wish to add a product, click Add product.<br>
✕ If you’d like to add a product, click Add product.

If a set of instructions contains several “If you want to...” statements in a row, **consider using other means of representing those conditions or options**:  perhaps try a table, instead? Long numbered lists that contain several optional or case-specific “steps” can mean the doc is actually a spec in disguise.

**Avoid using “desired” in place of the more direct “want”**:

>✓ Select the item you want to add to the order.<br>
✕ Select the desired item.

**Be as direct as possible when representing forks or parallel approaches in the UI.** Try to address potential states in the same instructions to avoid confusion:

>✓ Use the drop-down list or the available buttons beside Accept payment for this order to process payment.<br>
✕  Use the drop-down menu beside Accept payment for this order to process payment. Depending on your order, you might see a selection of buttons at this step instead.

### Representing results of user actions

**Don’t use a separate numbered step to describe only what is displayed by the UI or seen by the user as the result of an earlier action.** If it is necessary to include those “outputs”, append them to the steps that describe the actions that prompted them to begin with. But in general, omit results statements unless the result is surprising or unexpected.

**Include separate “navigation statements” that indicate what the reader will see only where necessary.** Ideally, the documentation will be clear enough to keep the reader oriented:

>✓ 3. Tap **Take Payment**. You will be taken to the **Checkout** screen.<br>
✕ You'll see a confirmation message.

**Avoid summary statements at the close of a task chunk**:

>✓ 5. Click **Save** to complete the exchange and update your inventory.<br>
✕ 6. The purchase has effectively been exchanged and your inventory levels for each product have been properly updated.

**Use references to the reader’s past actions** to communicate necessity and progress, and to reinforce the intended order of operations. For progress within a series of steps, use the phrase “When you’ve …” or “After you’ve…” (implies necessity). Avoid using “Once you’ve…” For progress between tasks, begin a section with “Now that you’ve …” or “After you’ve…” (implies prior accomplishment, completion, etc.).

**For instructions, use the imperative / present tense form.** Limit the use of the future tense to cases that actually refer to the chronological future:

>✓ Click **Save**. The price changes when the discount is applied.<br>
✕ Click **Save**. The price will change when the discount is applied.

>✓ Choose an End Date. After this date, the boosted post will revert to a regular post.<br>

When asking the reader to verify or confirm something, use:

- **make sure** in cases where there's still a related important task (instead of "check that," "verify that," etc.)
- **confirm** for cases where they've already been told to do the thing, and we're reminding them.

### Including screenshots

Screenshots can be useful to help orient readers and reassure them that they are in the right place. However, screenshots often have to change to match the UI and can’t easily be translated, so they come at a cost in maintenance and consistency. Screenshots can also use up a lot of space on a help page, causing visual clutter that might distract the reader.
* If necessary, include a screenshot to provide context and establish where most of the steps in a task occur.
* Use a screenshot to clarify a step or an instruction that isn’t fairly obvious from the product UI. But avoid a series of multiple images. And in procedures, avoid having a screenshot for every step.
* Include only the portion of the screen necessary to orient the reader as to where the point of interest is. Crop images down to save space and remove superfluous information. (This is usually not the case with screenshots for mobile apps, though, where the full screen is often best.)
* If you do use several screenshots in a topic or example, keep their details consistent to help build a narrative.

For technical details of adding screenshots, see the [screenshot guide](https://vault.shopify.com/Documentation/Screenshot-Style-Guide) in the Vault.

### Using note blocks

Note blocks are useful because they draw a reader’s attention to specific information. For that same reason, too many note blocks on a page can be distracting. They’re also often used to bring attention to negative information, so using them inappropriately can lead to a page of overstated warnings and limitations.

You can see the markdown code for adding note blocks [here](https://github.com/Shopify/documentation/tree/master/_plugins#note-blocks).

Below is a description and some examples of how you should use each note block type.

* [Note blocks](#3-documenting-tasks_using-note-blocks_note-blocks)
* [Caution blocks](#3-documenting-tasks_using-note-blocks_caution-blocks)
* [Tip blocks](#3-documenting-tasks_using-note-blocks_tip-blocks)
* [Growth blocks](#3-documenting-tasks_using-note-blocks_growth-blocks)
* [General note guidance](#3-documenting-tasks_using-note-blocks_general-note-guidance)

#### Note blocks

“Note” blocks are used to highlight or supplement the information in the main text. Use “Note” blocks to briefly flag important information that the reader might have missed if they’ve skipped to the current section, or to bring attention to information that’s true only in certain cases.

Don’t use a “Note” block just because something isn’t possible. If the information is directly relevant to the current topic and true in every case, then it belongs in the main text.

**Do**

>**Note**<br>
>Users with limited access can’t manage accounts other than their own.

**Don’t**

>**Note**<br>
The Socket Mobile CHS Qi 2D barcode scanner is not compatible with Shopify POS for iPhone or Android.

The above is from the compatibility section of the 2D barcode scanner page. In this context, it should be in the main text.

#### Caution blocks

“Caution” blocks are for content that we definitely want readers to notice and read. Use a “Caution” block for information that aims to prevent merchants from seriously breaking something or losing money.

Don’t use a “Caution” block just because something might not work.

**Do**

>**Caution**<br>
Do not select the External Credit or External Debit payment methods unless you're using an external card terminal and payment is being processed by a third-party payment gateway. Shopify doesn't process the payment when you use the these payment methods.

**Don’t**

>**Caution**<br>
The gift receipt option will appear only if you have the receipt printer.

#### Tip blocks

“Tip” blocks tell the reader about a feature, tool, or workflow that they can use to complete a task more easily. Use a “Tip” block for information that isn’t crucial to completing the task, and that can be safely ignored by the reader.

Don’t use a “Tip” block for content when a “Note” or “Caution” block would be more appropriate.

**Do**

>**Tip**<br>
You can restrict access to the register settings by enabling limited permissions in your staff settings.

**Don’t**

>**Tip**<br>
You won't see the options to print paper receipts if you don't have a receipt printer installed.

#### Growth blocks

“Grow your business” blocks are similar to “Tip” blocks, but the former will have an emphasis on business strategy, whereas the latter will have an emphasis on learning. Like “Tip” blocks, “Grow your business” blocks can be safely ignored. They should start with a question, and be followed by a sentence that links to the solution. Use a “Grow your business” block to link to Help Center and external resources that help merchants sell in new ways and market their business.

Don’t use “Grow your business” blocks to explain how a part of the Shopify product works. Don’t break the question-answer format.

**Do**

>**Grow your business**<br>
Want to accept payments in person? Try the <a href="https://help.shopify.com/manual/sell-in-person/">Shopify POS app</a> on your iOS or Android device.

**Don’t**

>**Grow your business**<br>
You can control which collections appear in Shopify POS by editing their visibility setting.


#### Shopify Plus note blocks
Shopify Plus note blocks are used to contain content that applies to Shopify Plus only.

#### General note guidance

* Use as few note blocks as possible, and never place two note blocks next to each other on a page. Wherever possible, include information in the main content of the page instead of using a note block.
* Don’t necessarily add a note block just because we’ve received a request to add a note. People outside our team might use the word “note”, but really all they want is some information added to a page.
* Try to keep note blocks to one or two sentences.
* Don’t place images in note blocks or place note blocks in tables.
* If you think you need to use more than a couple of sentences or to use an image, then consider creating a section on the page for the content.
* If you find that a page requires a lot of notes, then try reorganizing the content of the page to create appropriate places for note content in the main text.

### Documenting as teaching

**Provide next steps beyond the current doc** that link to relevant topics or tasks. These can be chosen deliberately to reflect multiple reader profiles and responses to the doc, including prospective users, etc..

**Motivate the reader to learn** by explaining briefly in the introduction “why this [feature] is a thing” and making it clear what the merchant will gain from implementing it.

Where possible, **give the readers “early wins”** by making the first step or two of the task you’re describing relatively brief and manageable.

**Aim to integrate the current task with readers’ wider knowledge of the platform.** Connect the subject matter of the current doc with other aspects of the admin, the store-building process, and even the business-building process.

Although we avoid repetition and redundancy at the paragraph level, we can deliberately **include some redundancy at the document level to ensure the readers’ awareness of important points**. For example, a key warning or condition might be mentioned twice, once in the introductory comments and once in the task at the relevant step.

---

## Voice and tone

Sad as it may seem, most people don't want to spend ages reading our beautiful docs. They want to get in and get out. This means that the language in a doc needs to be concise, direct, and task-oriented throughout. However, none of that precludes friendliness, nor does it mean your text must be choppy or dry.

### In this section
* [Tone](#tone)
* [General prose style](#general-prose-style)

### Tone

As a general rule, the higher the level in the doc’s hierarchy, the lighter the tone for the text. Within introductions to tasks, for example, some informality is welcome and can help draw the reader into the doc. At this highest level, the writer can provide accessible context and even encourage the reader to read further. A relatable tone when introducing separate steps (or sub-tasks) gives the reader a break from the instructions and provides friendly context. But for actions and task-oriented passages, you should probably aim for a much more direct tone. At that lowest level, terse, directed prose is best. You can still add a bit of informality and friendliness there by using contractions to link directions and results.

**There are things you can do** to achieve an engaging, friendly tone and avoid sounding robotic:
* Use contractions (you’re, isn’t, can't, etc.) to establish an informal and friendly tone.
* Address the reader or user as “you”.
* Use the active voice for the most part, which generally sounds less formal than the passive voice. Frame the document in terms of “what the merchant does” instead of “what is being done by the merchant.” But in cases where the passive voice sounds more natural than the active voice, you just go ahead and use that passive voice (such as with verbs like “publish” or “assign” and nouns like “discount”).

>✓ After the discount is applied, click Save.<br>
✓ The amount of tax included in the orders that you export from Shopify to QuickBooks online is assigned to the tax agency that you select here.

* Use linking adverbs, conjunctions, and prepositions liberally to avoid choppy writing:

>✓ Click the button to open the window.<br>
✕ Click the button. The window opens. <br>
✕ Click **Update**. Click **Save**.<br>
✓ Click **Update**, then click **Save**.

For a more in-depth approach to voice and tone, check out the global [Shopify voice and tone guide](https://vault.shopify.com/Writing/Voice-and-tone).

**There are also a few things you can avoid** to keep the tone in check:

* Sounding patronizing, chummy, cheery, childish or otherwise inappropriate in an attempt to seem informal and relatable.

* Colloquialisms, jokes, sarcasm, jargon and slang. Avoid anything that's too culturally specific.

* Use of the word **may**. Use might or can as appropriate. (The word may means both and is sometimes confusing for non-native English speakers.)

* The passive voice (most of the time).

  >✓ You can add all your products to your store from the Products page of the admin.<br>
  ✕ Products are added to the store from the Products page of the admin.

* Anthropomorphism (also known as the Shopify-as-a-human syndrome.) It’s better than the passive voice but avoid it if you can.

  >✓ Shopify passes the modified URLs to Google Analytics. (might be OK)<br>
  ✕ Shopify remembers what you’ve typed and will complain if the fields don’t match. (not really OK)

* Anything that causes the user to pause or hesitate, unless you explicitly want them to. It adds to the cognitive workload.

### General prose style

**Vary your sentence structure, especially in longer paragraphs**. Try to avoid using more than two phrases with a “To x, do y” structure in a row &mdash; this gets repetitive and can disengage the reader. Add a shorter, declarative sentence to the mix if possible, and use conjunctions to break up choppy passages.

**Treat structure and organization as key signs of a finished doc:**  avoid brain dumps. (That said, a brain dump is a great way to start writing a given doc.)

**Use parallel structure in lists, headings, and pretty much everywhere else** to encourage comprehension and recall.

**Aim for consistency in the grammatical subject** within longer paragraphs or sections.

**Use full sentences throughout.** Avoid sentence fragments except where they serve the purposes of both style and substance. Don’t use emoticons, as they do alienate some types of reader. Sorry :(

---

## Grammar, punctuation, and typography

For a general summary of the grammatical conventions that we hold dear at Shopify, refer to the [Content style guide](https://styleguide.myshopify.com/content/grammar_and_mechanics). For a sense of some docs-specific grammatical and typographical challenges, read on, fellow documentarian.

### In this section
* [Abbreviations](#abbreviations)
* [Capitalization](#capitalization)
* [Lists](#lists)
* [Numbers in text](#numbers-in-text)
* [Pronouns](#pronouns)
* [Verbs](#verbs)
* [Hyphens](#hyphens)
* [Commas](#commas)
* [Periods](#periods)
* [Brackets](#brackets)
* [Colons](#colons)
* [Semicolons](#semicolons)
* [Exclamation marks](#exclamation-marks)
* [Quotation marks](#quotation-marks)
* [Apostrophes](#apostrophes)
* [Typography](#typography)
* [Italics](#italics)
* [Bold](#bold)
* [Code](#code)
* [User input](#user-input)
* [Styling key presses](#styling-key-presses)
* [Labelling figures and tables](#labelling-figures-and-tables)
* [Links](#links)

### Abbreviations

**Try to avoid using abbreviations** such as ie. or eg. It is more friendly to use phrases like "like", "for example", and "such as" instead.

### Capitalization

**Excepting buttons, use sentence case when referring to UI elements**:

>✓ On the the **Products** page, click **Add product**.<br>
✕ On the products page, click **add product**.

**Match the capitalization of the UI when referring to buttons**:

>✓ Tap **Refund**. (iPhone instructions)<br>
✓ Tap **REFUND**. (Android instructions)

**Use sentence case for all headings**:

>✓ Create a product variant<br>
✕ Create a Product Variant

**Don’t capitalize parts of Shopify that aren’t unique to Shopify**:

>✓ From your Shopify admin, you can publish blog posts about your retail store.<br>
✓ You can post the same products on Facebook and your online store.<br>
✕ From your Shopify Admin, you can publish Blog Posts about your Retail Store.

### Lists

Use **unordered lists** for items whose order doesn’t matter. If the list items are not complete sentences, then start every line in lowercase (unless it requires caps for some other reason).

In cases where the bullet list is an extended sentence which in another context (eg legal) would be broken up by semicolons, use a full stop only at the end of the last item. If any list item contains more than one sentence, use sentence case for every item (and make each item a complete sentence = parallel structure) and end each with a full stop.

If you have a bulleted list that is a series of terms, statuses, or elements followed by descriptions or explanations, bold the term and then separate it from the description with a hyphen. Example:

>**Complete** - Your tax information for this state is the same in both Shopify and Avalara.<br>
**Action required** - You have tax information for this state in Avalara that isn't included in your Shopify tax settings.

Use **numbered lists** for task-oriented directions. Use sentence case, ie initial capitals and a full stop at the end of every item. It’s not essential to introduce the list with a colon.

For **navigation lists and tables of contents**, don't add punctuation.

For **variable lists**,  no punctuation for the shorter item or term, but descriptions/points should be punctuated as sentences, even if they’re fragments.

### Numbers in text
**Write out numbers ten and under, except in cases where a numeral would be more natural**. In some cases, you can avoid using specific numbers where a more open-ended description would do:

>✓ You have the following choices: <br>
✕ You have these two choices:

### Pronouns

In general, **use the plural form of “customer” to avoid the grammatical issue of pronoun agreement**:

>✓ The customers can make their purchases through this gateway.<br>
✕ The customer can make their purchases through this gateway.<br>
✕ The customer can make his or her purchases through this gateway.

Where a singular form of “customer” is required, try to omit the personal pronoun reference.

>✓ Enter the customer’s credit card information, then click **Save**. <br>
✕ After the customer enters their credit card information, click **Save**.

**Use “you” when referring to the reader**. Do not use “we” to refer to yourself and the reader together:

>✓ After you enter the price, click **Save**.<br>
✕ We can add a customer to the order by clicking **Add Customer** at this step.

### Verbs

**For instructions, use the imperative / present tense form**. Limit the use of the future tense to cases that actually refer to the future:

>✓ Click the Save button. The price changes when the discount is applied.<br>
✕ Click the Save button. The price will change when the discount is applied.<br>
✓ Choose an End Date. After this date, the boosted post will revert to a regular post.

**When FAQs have a yes or no answer, answer first with an initial fragment**, such as “Yes.” or “No.”

>✓ Yes. The price will change when the discount is applied.<br>
✕ Yes, the price will change when the discount is applied.

Be aware of procedural verbs that have similar -- but different! -- noun counterparts:

<table>
	<tr>
		<th>Verb</th>
		<th>Noun</th>
	</tr>
	<tr>
		<td>set up</td>
		<td>setup</td>
	</tr>
	<tr>
		<td>log in</td>
		<td>login</td>
	</tr>
	<tr>
		<td>check out</td>
		<td>checkout</td>
	</tr>
</table>
<br>

**Use the active voice** for the most part. Frame the doc in terms of “what the merchant does” instead of “what is being done by the merchant”:

>✓ You can add all your products to your store from the **Products** page of the admin.<br>
✕ Products are added to the store from the **Products** page of the admin.

**The passive voice can be used sometimes**. In a few cases it sounds way more natural than the active voice (with verbs like “publish” and nouns like “discount”):

>✓ The price changes when the discount is applied.<br>
✓ This updates all posts that have been published previously. <br>
✕ The price is changed when you click **Save**.

## Punctuation

### Hyphens

Most compound adjectives (two words that combine to modify or describe another) require hyphenation:<br>

>✓ single-variant product<br>
✕ single variant product<br>

>✓ a unique single-variant product<br>
✕ a unique single variant product<br>

>✓ drop-down list<br>
✕ drop down menu

There are several commonly used compound adjectives in Shopify’s documentation:

>✓ carrier-calculated shipping<br>
✓ third-party application<br>
✓ iOS-based app<br>
✓ iOS-compatible app<br>
✓ Shopify-supported theme<br>
✓ amazing, state-of-the-art saas platform

But it’s sometimes OK to **omit a hyphen in compounds where it seems unusual**:

>✓ a credit card terminal<br>
✕ a credit-card terminal<br>

>✓ a gift card policy<br>
✕ a gift-card policy

**Avoid using only the hyphens when stacking up multiple parallel compounds**. Expand each term to avoid potential confusion, even if it means some repetition:

>✓ Set up a vendor-specific or type-specific size chart.<br>
✕ Set up a vendor- or type-specific size chart.<br>

>✓ Set up specific size charts for vendors or types.<br>
✕ Set up a vendor or type specific size chart.

Oh, and **don’t hyphenate in between adjectives and adverbs ending in -ly**:

>✓ this fully supported hardware<br>
✕ your newly-created product

Omit hyphens after most prefixes. Use one only if clarity requires it.  If you've added a prefix that requires a hyphen, consider rewriting the phrase to avoid that prefix.

>✓ reorder<br>
✓ resend<br>
✓ recreate<br>
✕ re-send<br>
✕ un-do<br>

And **don’t hyphenate email or ecommerce** ever.

### Commas

**Use the Oxford comma** (before both *and* and *or*):

>✓ This screen displays your products, orders, and customers.<br>
✕ This screen displays your products, orders and customers.<br>


**Use commas before conjunctions or linking adverbs** where they help to emphasize sequence, timing, or cause and effect:

>✓ Select a variant, then click **Save**.<br>
✕ Select a variant and click **Save**.

**Use commas after prepositional phrases except where it sounds weird to you**. In general, very short prepositional phrases don’t require commas afterwards:

>✓ After you’ve finished editing your storefront, click **Save**.<br>
✓ In most cases the products will be set to visible.

**Use commas to separate multiple adjectives when there’s no natural order**:

>✓ We saw a strong, healthy unicorn.<br>
✕ We saw a strong healthy unicorn.

**Don’t use commas after each item in a bulleted list**.

### Periods

**Use periods**:
* after the last in an unordered list (but not after the other items in the same list)
* after list items that are complete sentences (and if one of the items in a list is a complete sentence, consider making them all complete sentences so that the list is fully parallel)
* outside of linked text (even when the link is at the end of a sentence).

**Don't use periods**:
* in headings
* in tables of contents or navigation lists
* at the end of each item in a list (unless one of the items is a complete sentence, in which case you should just add a period after after each item in the list, and probably at least try to make them all complete sentences)
* inside formatting tags (like bold, code, or italics) unless it has a good reason to be there
* inside links
* at the end of headings.

### Brackets

**Include parenthetical comments within ordinary sentence punctuation**:

>✓ Use brackets sparingly (but use them well).<br>
✕ Use brackets sparingly (but use them well.)

**Avoid putting complete sentences inside brackets**. If it is a complete sentence, you should probably just let it be free (of brackets):

>✓ Use brackets sparingly. They can be tedious when overused.<br>
✕ Use brackets sparingly (they can be tedious when overused).

**Refer to different species of brackets consistently**:

>`( )` = "brackets"<br>
`[ ]` = "square brackets"<br>
`{ }` = "curly brackets"<br>
`< >` = "angle brackets"

### Colons
**Use colons at the end of sentences or phrases that directly introduce things** like lists, sets of instructions, screenshots, and code snippets.

### Semicolons
**Don't use semicolons**; they’re generally frowned on in tech writing because of potential confusion with semicolons in code:

>✓ Click **Save** to continue. This will save the thing.<br>
✕ Click **Save** to continue; this will save the thing.

### Exclamation marks
**Don't use exclamation marks**. They make you sound surprised, or condescending, or both.

### Quotation marks
**Avoid using these guys** unless they’re part of code that’s included in the doc:

>✓ Choose an audience from the **Audiences** section. <br>
✕ Choose an audience from the “Audiences” section.

### Apostrophes
For possessives, **use 's** after singular nouns and proper nouns that end in the letter S.


>✓ Edit your business's Facebook page.<br>
✕ Edit your business' Facebook page.

## Typography

**Don’t be afraid of whitespace**. Paragraph breaks and indentation can enhance online readability:  if in doubt, spread it out. When done right, typography and whitespace make a doc’s hierarchy visible to the reader at a glance.

### Italics
**Use italics for**:
* article titles when you refer to an article by its title within a sentence
* introducing special terminology
* adding special emphasis in text where appropriate (use sparingly), and as an acceptable alternative to USING UPPERCASE FOR STRESS OR EMPHASIS which you should never do.

### Bold
**Use bold for**:
* named interface elements and text, including pages, buttons, lists, menus, fields, and dialogs:

  >✓ On the **Products** page, browse through your products by swiping your screen left and right.

* anything the user clicks on or selects rather than typing:
  >✓ Click **Save** to continue.<br>
  ✓ To view your Shopify admin, click **View your admin** on the **Admin options** dialog.

* the first instance of a keyword, term, or feature (ie. in an introductory chunk…); this looks especially snappy on the overview page of a larger section.

### code
Use `monospace` for small code fragments. To write in monocode in markdown, put three backticks before the snippet, and three backticks after the snippet.

For extended code samples, use [GitHub-style fenced code blocks](https://help.github.com/articles/creating-and-highlighting-code-blocks/). Label the code block with the code language if you know what it is.

Use code formatting also for all URLs, pathnames, filenames, and file extensions. File extensions should be set in lowercase and begin with a period:

>✓ Delete `random.csv` from the `Moneyhats` folder before creating a new `.csv` file. <br>
✕ Delete <kbd>random.csv</kbd> from *moneyhats* before creating a new **CSV** file.<Br>
✓ Use your `myshopify.com` URL.

You can also use code to represent buttons that show symbols instead of proper names:

>✓ To add a product, tap the `+` button.<br>
✕ To add a product, tap `+`.<br>
✕ To add a product, tap the plus button.

### User input
Use markdown backticks around anything the user physically types into the Shopify interface, such as entries in fields and dialog boxes, tag names, commands, keyboard shortcuts, and file names.

>✓ In **Tax rate**, enter `15`.

### Styling key presses

- Windows: Write `ctrl`, `shift`, `alt`, and `Windows key` for modifier keys
- Mac: Write `command`, `option`, `control`, and `shift` for modifier keys
- Write a + between the keys if the user needs to press both keys at the same time
- Place a space between key labels and the +
- Do not use code styling on the + sign
- Capitalize single-letter keypresses like `G` and `H`, even when used in multi-key combos
- Refer to platforms as "PC" and "Mac", not "Windows" and "OS X"
- List PC key combos first, then Mac -- although we develop on Macs, most docs users are on PCs

>Press `ctrl` + `C` on a PC or `command` + `C` on a Mac to copy the code.

>From your Shopify admin, press `G` `H` to go to your store home page.

### Labelling figures and tables
Don't.

### Links
**Embed links around the shortest phrase necessary to make the link target obvious**. Avoid using a separate phrase just to call attention to the link:

>✓ You can [update your product descriptions] at any time.<br>
✕ [Click here] to learn more.<br>

>✓ These transactions aren’t covered in [Facebook’s ad policy].
✕ These transactions aren’t covered in Facebook’s ad policy. [Learn more &rsaquo;]<br>


**If a link appears at the end of a sentence, don't include the closing period within the link**.

**Set links to open in new tabs *only* in cases where the reader would benefit** from having the docs open beside the page you're linking to (whether it's the Shopify admin, a third-party admin, or a key reference). This means using HTML instead of Markdown. This practice encourages the reader to follow along with the documentation while completing the task.

**When referring to a named page in the Shopify admin, link only the name of the page**, and use bold formatting.

**When linking to a doc that describes how to do a relevant process, link a relevant verb phrase**:

>✓ You can &#91;delete the order&#93;(/manual/your-store/orders/cancel-order) afterwards.

## Vocabulary

Try to use terms consistently across the docs. Check the [Merriam-Webster](https://www.merriam-webster.com/) dictionary if you're not sure which form or spelling of a word to use (as recommended in [Polaris](https://polaris.shopify.com/content/vocabulary)).

### In this section
* [Interface elements and in-admin terminology](#interface-elements-and-in-admin-terminology)
* [Registered trademarks/our own IP](#registered-trademarks-our-own-ip)
* [Other people's intellectual property](#other-peoples-intellectual-property)
* [Currencies](#currencies)
* [Specific terms](#specific-terms)

### Interface elements and in-admin terminology

You can find content guidelines for general Shopify vocabulary in the [Admin Style Guide](https://styleguide.myshopify.com/content/vocabulary).

Try to avoid mentioning specific UI elements unless they need to be called out or are not obvious. For example, don't write "Click the **Open** button." Instead, write "Click **Open**".

Beyond that:

<table>
	<tr>
		<th>Go with</th>
		<th>Avoid...</th>
	</tr>
	<tr>
		<td>rich text editor, the editor (<em>optional for second use</em>)</td>
		<td>Rich Text Editor, RTE</td>
	</tr>
        <tr>
              <td>menu</td>
	    <td>list</td>
	</tr>
</table>
<br>

Avoid referring to radio buttons. Just use the verb "select" and call it a day:

>✓ Select **Locations**.<br>
✕ Click the **Locations** radio button.<br>
✕ Select the **Locations** radio button.

When referring to checkboxes, use the verb "check" or "uncheck":

>✓ Check **Locations**.<br>
✓ Uncheck **Locations**.<br>
✕ Check the box beside **Locations**.<br>
✕ Click to check **Locations**.

When referring to toggle buttons, do this:

>✓ Enable **Locations** by tapping the toggle button.<br>
✕ Tap the **Locations** toggle to enable it.

There are a few ways to refer to "pop ups" -- let's use "dialog" for now:

>✓ In the **Edit shipping** dialog, click **Save**.<br>
✕ In the **Edit shipping** dialog window, click **Save**.<br>
✕ In the **Edit shipping** modal, click **Save**.

### Registered trademarks/our own IP

Apparently we implicitly acknowledge all third-party rights so there’s no need for fancy markup in the doc to indicate copyright.

**Don’t capitalize elements that aren’t trademarks or unique to Shopify** (such as admin, app store, dashboard):

>✓ Shopify Unlimited plan, Basic plan<br>
✕ Shopify unlimited plan, basic plan

### Other people’s intellectual property

Except for cases where it seems unreasonable, aim to reproduce the formatting used in third parties’ product literature. For example, since Facebook capitalizes “News Feed” in their docs, we should reproduce that in our own.

In general, omit TM or copyright symbols from product names (except in cases where that formatting's required based on a legal agreement with a third party).

### Currencies

The ways that we represent currencies and currency amounts will vary depending on the context.

In general, assume that currency amounts in the docs are US dollars. Add a `$` symbol before the currency amount, and omit the decimal places for whole dollar amounts.

>✓ You can sign up for Shopify for as low as $9 per month.<br>
✓ Lintercorp charges a monthly fee of $9.99 to use their app.<br>
✕ Add the retail package to your Shopify plan for 40 dollars per month.<br>

When representing foreign currency amounts, use the ISO 4027 standard currency code after the currency amount, separated by a space. You can find that standard on [Wikipedia](https://en.wikipedia.org/wiki/ISO_4217). Avoid using currency symbols, except where they're required to resolve ambiguity.

>✓ 400 EUR<br>
✕ 400 Euros<br>
✓ 25 GBP<br>
✕ £25 GBP<br>
✕ GBP 25

In cases where there's potential ambiguity between USD and other currencies, or in cases where USD is being compared with other currencies, add the USD currency code after the currency amount, and omit the initial `$` symbol.

>✓ If your business is based in Canada, then your invoice will include a charge of 25 USD. <br>

>✓ The following credits are available:
>* 25 USD
>* 20 CAD
>* 15 GBP
>* 20 EUR

### Specific terms

#### Shopify POS, POS, and point of sale

In most cases, write “Shopify POS”. However, in introductory material you might need to write out “point of sale (POS)” in some descriptions about in-person sales. Also, some Shopify admin elements might use different wording, so match the admin’s wording in those cases.

>✓ The Total sales amount includes online store sales and Shopify POS sales.<br>
✕ The sales amount includes online store sales and point of sale sales.

#### zip code

Write this out in lowercase as two words.

#### Black Friday, Cyber Monday
Treating BFCM as a holiday is a marketing push by Shopify that merchants and their customers don't necessarily understand out of context. Treat Black Friday and Cyber Monday as separate, independent holidays and write out their names in full. You can refer to one without the other.

## Metadata

Be aware of the following best practices for metadata that's contained in the docs' YAML headers.

Remember: *metadata is a love note to the future.*

### In this section
* [title](#title)
* [sidebar_title](#sidebar-title)
* [description](#description)
* [Keywords](#keywords)
* [Tags](#tags)
* [Hiding a page](#hiding-a-page)
* [Redirects](#redirects)
* [Anchor links](#anchor-links)
* [Adding a file that can be downloaded](#adding-a-file-that-can-be-downloaded)

### `title`

Where possible, use the "-ing" form for verbs that appear in the title tag.

Make sure that the title is unique.

>✓ Adding a Facebook button to your online store<br>
✕ Facebook

### `sidebar_title`

Where possible, use the "-ing" form for verbs that appear in the title tag.

### `description`

Description tags are some of the most fussy of citizens of YAMLopolis. When you're writing or revising description tags, make sure that they're:

* action-oriented (use present tense, begin with a verb)
* unique (they shouldn't be the same as another page’s description, or the same  as the page title; but avoid weak synonyms across title and description, like “Set up” in one and “Configure” in the other)
* rich in keywords and controlled vocabulary
* results-oriented (provide a solution or benefit; answer “why is this a thing?”)
* about 150 characters long (enough space to capture the full scope of the doc, right?)
* free from quotation marks (these can break things)
* as many sentences long as they need to be (more than one sentence = OK)


>**Message Us:** "Learn how to add a Message Us button to your online store, so that your customers can easily contact you about their orders using Facebook Messenger." (149 characters)

>**Shopify Shipping:** "Get reduced rates from USPS and save time at the post office by using Shopify Shipping to buy and print shipping labels in your Shopify admin." (142 characters)

### Keywords

When you're creating a new doc or updating an existing one, add the `keywords` tag to add some terms that will make the doc searchable. This will help surface docs in search results that may contain content that isn't necessarily obvious just by looking at the title or description of the doc alone.

You can access a full list of keywords that exist in docs by going to [https://help.shopify.com/keywords/keywords.json](https://help.shopify.com/keywords/keywords.json). You can search that list using `command + f` if you are looking for something specific.

There is no right or wrong way to add keywords to a doc, so here are some guidelines that we’ve been following:

- **Add keywords as plurals as long as it makes sense to do so**. For example, if you are adding the keyword `domain`, add `domains` instead. It will account for the word `domain`. But, if you are adding the keyword `PayPal`, it wouldn’t really make sense to add `PayPals`.
- **Avoid adding verbs as keywords**. Verbs like add, change, and delete tend to throw off search because they are very common. However, there are certain verbs that would be ‘unique enough’ that they can help distinguish docs from others. For example, `publish` in the context of themes, or `transfer` in the context of domains.  
- **Pick keywords that will make a particular page stand out from similar pages**. Especially for long pages. For example, a page like [Advanced publishing](https://help.shopify.com/manual/sell-online/online-store/blogs/publishing-blogs) for blogs, you can include terms like `wordpress`, `tumblr`, and `blogger` as keywords since it may not be obvious from the title that the content exists on that page.
- **Add the terms POS and Plus to content that is specific to POS or to Plus features**. We have filters that use keywords to narrow down content for POS and for Plus. To make sure that this continues to work, we need to add the terms `POS` and `Plus` to the pages that are about POS or Plus-specific features.
- **Use Google Analytics to look up search terms for a specific page**. If you are adding keywords to an existing page, you can see what search terms people used to land on that page using the **Navigation Summary** in Google Analytics. Add those terms as keywords but only if they make sense to the content of the page.

To look up search results for a specific page in GA:

1. Go to the [Documentation - Without Shopify Visits view in GA](https://analytics.google.com/analytics/web/provision/?authuser=0#provision/SignUp/).
2. Click on **Behavior** > **Site Content** > **All Pages**.
3. Click on the **Navigation Summary** tab.
4. Set the date range at the top of the page to **Jan 1, 2017 - Mar 30, 2017** (doesn't have to be these exact dates but choose a duration that's at least 3 months) and click **Apply**.
5. Go to the [Keywords spreadsheet](https://docs.google.com/spreadsheets/u/1/d/1JS6PIpkbs-bhFcbgj0aOs9AwHpAH-BOVkt1PaurlO6Y/edit?usp=sharing) and copy the path for the doc you’re working on (e.g., `/manual/apps/apps-by-shopify/script-editor/limitations`).
6. Go back to the **Navigation Summary**, click on the **Current Selection** drop-down, and then paste the doc path into the **Search** field.
7. Hit **return** and then click on the result under **Page** that matches the doc.
8. In the **Search** field in the **Previous Page Path** column, type the word `search`, and then hit **return**.

You will see results like `/search?stq=database&stp=1`. The search term in this case is `database`. Try to include results that have at least 5+ pageviews.


### Tags

You can add tags to docs which will display in the sidebar and at the top of the doc:

The tags available are:
* beta
* plus

The correct syntax for adding a tag to front matter is as follows:

```
tags:
   - beta
```

### Hiding a page

 ```
hidden: true
```

Use these tags to hide a page from the docs search, Google search, and the sidebar. This page can be accessed from a direct URL only.

### Redirects

When you need to create a redirect link, for example, when a page is deleted from the docs, add the redirect link to the metadata using the field legacy-urls. For example:

    ---
    layout: default
    title: Getting started with Shopify POS
    sidebar_title: Getting started
    description: Set up your Shopify POS store.
    legacy-urls:
      - /manual/sell-in-person/mobile/installing
    ...

### Anchor links

GitHub flavoured Markdown lets you create links to headers (sections inside a page) by using the name of the heading (with space characters replaced with (-) dashes) as the link anchor. The disadvantage of this method is that if you change the text of the header, then you need to update your links. To avoid updating your links each time that you tweak a header title, you can assign an ID to the header and use the ID in your links.

To assign an ID to a header:

In the source file, underneath the header tag, add an **a** element with the **id** attribute. For example:

~~~~
HH My header
<a id="anchor-id"></a>
~~~~

In the target file, add a link with the following format:

~~~~
[my-header](source-file#anchor-id)
~~~~

---

## Internationalization

Making commerce better for everyone means making our products work for people all over the world. These guidelines help us design, write, and build products for the global market.

### Building for a global audience

Making our content and interface work for a global audience includes more than just translation. Our goal is to make everything we create easy to understand for the following audiences:

* Native English speakers
* Non-native English speakers
* Translators hired to localize our content
* People reading the translated content

### Writing

Our writing should be easy to translate and easy to understand by merchants who aren’t native English speakers.

#### Keep sentences short

In general, shorter sentences are easier to understand and translate.

Break up long sentences into shorter ones. Sometimes you may need rewrite or rephrase your sentence to make the meaning clearer. Bulleted lists can be used in place of sentences that contain lists of three or more items.

>✕ We offer one complimentary hour of design support, so if you’re planning on making large, extensive changes to your theme, then you should consider hiring a Shopify Expert instead.<br>
✓ We offer one complimentary hour of design support. If you want to make big changes to your theme, then consider hiring a Shopify Expert instead.

#### Use plain language

Use everyday words. Replace jargon and buzzwords with common English words.

#### Be friendly, but polite

Many cultures are more formal, especially in business transactions.

#### Use terms consistently

Some words that seem the same in English can translate very differently.

Always be conscious of the words you use to describe a UI element, action, or concept, and use that same term throughout.

>✕ The **newsletter signup form** is always displayed in the footer of your store. If you want to remove the **customer sign-up**, you can…<br>
✕ A **favicon** is a logo image that appears in the address bar. You can create a **favourites icon** by…<br>
✓ By default, this theme displays a **slideshow** on the home page. A **slideshow** is…

#### Use syntactic clues
Always use syntactic clues to make your sentences as clear and concise as possible. Note that this might require using passive voice.

>✕ You can change your tax settings using the admin.<br>
✓ You can change your tax settings by using the admin.<br>
✕ The theme settings window will display.

_Why is this wrong? Because the sentence seems unfinished. The translator might be prompted to ask “The theme settings window will display what?”_

>✓ The theme settings window will be **displayed**.

Another example of a syntactic clue is the use of the word “that”:

>✕ The way themes work hasn’t changed.<br>
✓ The way that themes work hasn’t changed.

#### Avoid words like may or while
**May** is a difficult word to translate, since it can mean either **might** or **can**. Use **might** or **can** instead.

**While** can either mean **during** or **although**.

#### Avoid clumps of negative terms
Double and triple negatives can be difficult to understand, especially for non-native English readers.

#### Avoid humor
Humor doesn’t translate well. A joke tailored to North American or English-speaking audiences can be senseless or even offensive to global audiences.

#### Be inclusive of cultural differences
Avoid colloquial words, idioms, and pop culture references. Additionally, consider cultural norms when building a narrative within your docs:
* Be inclusive. Use customer names and locations from multiple countries and ethnicities.
* Product images should be acceptable to all cultures. For example, avoid showing product images of bikinis, strapless dresses, T-shirts with slogans in English or images of cartoon characters, etc.

#### Avoid abbreviations and acronyms
Avoid abbreviations and acronyms. They often won’t be the same in other languages, and they may not translate at all.

If you have to use an acronym, spell it out on first use. Don’t use Latin abbreviations.

> ✕ You can add social media icons, such as Facebook, Pinterest, **et al**, to each product page.<br>
✕ Try using a search engine, **e.g.** Google, to find … <br>
✓ Try using a search engine, **such as** Google, to find…

#### Avoid shortcuts like and/or and (s)
These are very difficult to translate, and non-native English readers might have difficulty understanding. Instead of **(s)**, try **each**, **every**, or **any of**.

> ✕ To translate your **theme(s)**, you can…<br>
✓ To translate **any of your themes**, you can…

Instead of **and/or**, use **and**.

>✕ You can create products **and/or** variants in your admin…<br>
✓ You can create products **and** variants in your admin…

#### Use leading sentences for bulleted lists
When setting up a bulleted list, make sure that the leading sentence does not appear to end mid-sentence. This can be confusing for translators and might prompt an inquiry asking if the sentence is incomplete. Leading sentences should clearly indicate that it is introducing a list.

>✕ You can:
* add a video section to your store’s theme
* use the rich text editor (RTE) to embed a video link
* add a video slideshow to your home page.

>✕ If you want to add a video to your store:
* add a video section to your store’s theme
* use the rich text editor (RTE) to embed a video link
* add a video slideshow to your home page.

>✓ If you want to add a video to your store, then you can do any of the following steps:
* Add a video section to your store’s theme.
* Use the rich text editor (RTE) to embed a video link.
* Add a video slideshow to your home page.

>✓ Try any of the following methods to add a video to your store:
* Add a video section to your store’s theme.
* Use the rich text editor (RTE) to embed a video link.
* Add a video slideshow to your home page.

