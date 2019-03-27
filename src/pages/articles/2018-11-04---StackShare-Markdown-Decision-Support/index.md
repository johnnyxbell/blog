---
title: StackShare Decision Markdown Support
date: "2018-11-04"
layout: post
draft: false
path: "/posts/stackshare-decision-markdown-support/"
category: "StackShare"
tags:
  - "StackShare"
  - "Tech"
description: "Soooo we at StackShare have launched something amazing, You can now leave decisions about what tech you chose and why… To find out what its all about it head over..."
---
![decisions.jpg](./decisions.jpg)

*StackShare - Decisions*

Soooo we at StackShare have launched something amazing, You can now leave decisions about what tech you chose and why... To find out what its all about it head over and [read more about it](https://stackshare.io/posts/introducing-stack-decisions) or if you don't have an account [Signup for StackShare (what are you waiting for)](https://stackshare.io/)

I recently [wrote a decision](https://stackshare.io/johnnyxbell/decisions/101179048957859072) about how I built the markdown support into decisions. This blog post is going to outline what markdown we support in our decisions as of right now. 

### Whats Supported?

We currently support the following tags: a, b, em, code, inline code, ul, ol

___

#### Links

```
www.stackshare.io
http://www.stackdhare.io
[StackShare](https://stackshare.io/)
```

www.stackshare.io <br />
http://www.stackdhare.io<br />
[StackShare](https://stackshare.io/)

#### Bold

```
__Bold text__
**Also bold text**
```

__Bold text__<br />
**Also bold text**

#### Italics

```
_Italic text_
*Italic text*
```

_Italic text_ <br />
*Italic text*

#### Code Block

Surround your code with ` ``` ` 3 backticks.

<div class="gatsby-highlight">
<pre class="language-text">
```
var factorial = function(number) {
  if (number <= 0) { // terminal case
    return 1;
  } else { // block to execute
    return (number * factorial(number - 1));
  }
};
console.log(factorial(6));
```
</pre>
</div>

```
var factorial = function(number) {
  if (number <= 0) { // terminal case
    return 1;
  } else { // block to execute
    return (number * factorial(number - 1));
  }
};
console.log(factorial(6));
```

#### Inline Code

Surround your code with ` code ` 1 backtick.

<div class="gatsby-highlight">
<pre class="language-text">
dolor sit amet, `consectetur` adipiscing elit.
</div>

dolor sit amet, `consectetur` adipiscing elit.

### Ordered List

```
1. React is really cool
2. Angular is really cool
3. Vue is really cool

1. React is really cool
2. Angular is really cool
   * Kind of is cool
   * Only a little cool
3. Vue is really cool
```

1. React is really cool
2. Angular is really cool
3. Vue is really cool

--

1. React is really cool
2. Angular is really cool
   * Kind of is cool
   * Only a little cool
3. Vue is really cool

### Unordered List

```
* React is really cool
* Angular is really cool
* Vue is really cool

* React is really cool
* Angular is really cool
   * Kind of is cool
   * Only a little cool
* Vue is really cool
```

* React is really cool
* Angular is really cool
* Vue is really cool

--

* React is really cool
* Angular is really cool
  - Kind of is cool
  - Only a little cool
* Vue is really cool

Annnnd thats all we support for now, if there are anymore markdown features you'd love to see in the decisions please let me know by commenting below, commenting on my [decision](https://stackshare.io/johnnyxbell/decisions/101179048957859072) or hitting me up on [twitter](https://twitter.com/johnnyxbell).