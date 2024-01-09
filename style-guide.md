# Style Guide

For an overview of all gitbook features, visit [Gitbook documentation](https://docs.gitbook.com/).

## Approach to using Gitbook

* Whenever information occurs in more than one current document, this is a good opportunity to pull it out and make it a standalone page. That way, any  topics that need it can link off to that page and when the information changes, it only has to be updated in one place.

## Specific words

* Use `CDC` instead of `the CDC` or `Center for Disease Control`.
* Use [`Vaccines.gov`](https://www.vaccines.gov) (capitalized and linked).&#x20;
* Data entry interface is `COVID Locating Health Provider Portal.`

## Voice and tone

* **Be direct**&#x20;
  * Although it's a nice impulse, avoid using extra language like "Please enter your information..." and just say "Enter your information..."
* **Be action-oriented**
  * Avoid passive language
* **Address the users as "you."**
  * Before: "If there has not been a flu vaccine inventory update in over two weeks..."
  * After: "If you haven't updated your flu vaccine inventory in over two weeks..."

**Tip:** Paste content into [https://hemingwayapp.com/](https://hemingwayapp.com/) to quickly diagnose passive voice and complex language.&#x20;

## Page elements

### Page description

Just under the page title, there's an option to add a page description. **Do not use this** element because it shows text with a lighter gray that doesn't meet accessibility standards.

### When referring to UI elements

Use the code text style when referring to a label on the portal or Vaccines.gov (type the text, highlight it, a menu should appear that lets you select the `code style.`

Ex:) To upload a file, click the `Upload` button.

### Headings

* Use sentence case.
* Don't use punctuation at the end of the heading line.
* Always use built in H1, H2, H3 headings to give your content some structure and nest properly.
* H1's and H2's will automatically appear in the mini contents section on the right of every page so ideally these two levels are used to indicate overall contents (via H1s) and key steps or groups of steps (via H2s). Tip: look at the ToC on the right as a gut check that you've organized the page and labeled each section in a useful way.

### For headings that communicate steps

When information provides step-by-step instructions, use a combination of H1's and H2's.

#### Use an H1 to describe a set of steps (if needed)

* Only use this if a page has instructions for different activities (e.g., "Adding locations..." and "Deleting locations...") . Original drafts used H2's to break up instructions on a single topic into sub sections like "Find your template", "Download.." etc. but given the H3's are used for actual steps, that level of sectioning isn't that helpful.

#### Use an H2 and `:arrow-right:` icon :arrow\_right: for each discrete step user needs to take

* Start with an action verb.

#### Use an H2 and `:fast_forward:` :fast\_forward: icon when a set of instructions is only helpful to some people

### Links

* Use descriptive text for your link label (ie link label should describe contents of the destination. Don't use "click here").

#### Internal links

* When linking to another page in the gitbook, use the [relative link option](https://docs.gitbook.com/editing-content/rich-text#relative-links). Note: you can either write text then designate the page to link to it OR have it plop in the official page name. I prefer the former since it lets you control what you're calling it and if you use the latter then later change that page's name, it doesn't update the link label for your relative link.

#### External links

* When linking to an external website, use the [absolute link option](https://docs.gitbook.com/editing-content/rich-text#absolute-links).

### Alert boxes

Unfortunately, the words in an alert box are NOT findable via the search.&#x20;

Because of this, only use alert boxes for tertiary info or to point to another place in the gitbook with more information.

### Tabs

Gitbook has a tab feature but it isn't useful for our current content. If considering it for future use, I recommend not using it for vital info you definitely want your users to read because they're much more likely to miss it if hidden behind a tab.
