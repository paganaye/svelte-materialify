---
title: Content
related:
  - styles/colors/
  - styles/reset/
---

<style>
div.html-example {
  border: 1px dotted #cc5;
  border-radius: 10px;
  padding: 20px;
  position: relative;
}
div.html-example::before {
  position: absolute;
  content: "For example";
  top: -12px;
  background-color: white;
  padding: 5px;
  font-size: 0.6em !important;
  color: #cc5;
}
</style>

# Content

The Materialify standard stylesheet, customizes many HTML standard elements

## Paragraph

The `<p>` html element represents a paragraph, with Materialify, the default font is Roboto.

<div class="html-example">
Lorem ipsum dolor sit amet, consectetur adipisicing elit. Harum maiores modi quidem veniam, expedita quis laboriosam, ullam facere adipisci, iusto, voluptate sapiente corrupti asperiores rem nemo numquam fuga ab at.
</div>

## Blockquote

The `<blockquote>` html element indicates that the enclosed text is an extended quotation, it is rendered visually with a left indentation and a thinner font face.

<div class="html-example">
<blockquote>
Lorem ipsum dolor sit amet, consectetur adipisicing elit. Harum maiores modi quidem veniam, expedita quis laboriosam, ullam facere adipisci, iusto, voluptate sapiente corrupti asperiores rem nemo numquam fuga ab at.
</blockquote>
</div>

## Code

The `<code>` html element displays its contents styled in a fashion intended to indicate that the text is a short fragment of computer code.

<div class="html-example">
Inline <code>code</code> element
</div>

## Variables

The `<var>` html element represents the name of a variable in a mathematical expression or a programming context. It's presented as italicized

<div class="html-example">
<var>v</var> = <var>u</var> + <var>at</var>
</div>

## User Input

The `<kbd>` html element represents a span of inline text denoting textual user input from a keyboard, voice input, or any other text entry device.

<div class="html-example">
To install svelte materialify, type <kbd>yarn add svelte-materialify</kbd>
</div>
