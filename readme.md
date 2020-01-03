This CSS adds a Kill Team flavour to Battlescribe's standard HTML output. It's designed to be more practical for referencing during games, with two viewing modes: one for viewing on screens and one for printing out.

It looks like this on my iPad:

![](https://github.com/r0tational/killteam-battlescribe/blob/master/screen-page.png)

And when printed it looks like this:

![](https://github.com/r0tational/killteam-battlescribe/blob/master/print-page.jpg)

I'm neither a designer nor a web developer, so I'm making no claims for my CSS skills! But please feel free to use as-is at your discretion and, of course, adapt/amend to your heart's content!

Here's what to do:

1. Grab the replacement CSS [from here](https://github.com/r0tational/killteam-battlescribe/blob/master/killteam-battlescribe.css)
2. Use Battlescribe to generate an HTML file and open in a text editor
3. Copy the full text of the CSS
4. Paste it into the HTML file, replacing everything between and *including* the `<style>` and `</style>` tags
5. Save the HTML and open it in a web browser. Chrome and Firefox recommended (Safari won't print with the print view for some reason). Then print, ensuring that the Background Graphics option is checked in the print dialog

Some quick notes:

- It displays in two ways. On your screen it should appear as a single column and be fairly clear to reference on a tablet during a game. Print it out, however, and it switches to a two-column view with smaller text.
- If you have it installed, the CSS will use the (premium) Minion Pro font, which is used in the official Kill Team rules book. Otherwise, it'll default to the Google Fonts-hosted Garamond EB, which is very similar.
- There are page break rules to prevent entries from splitting over columns and pages. I optimised it for keeping specialists, leaders/commanders/fire teams on single pages. The first page will be almost empty, and models with long lists of rules might break over pages and generally look terrible, but I've done what I can to make it practical.

Please feel free to share any improvements with the community; I'll do my best to add any changes I feel improves the stylesheet. Hope it's useful!
