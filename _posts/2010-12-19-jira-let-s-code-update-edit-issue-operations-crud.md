---
layout: post
title: Jira - let's code update, edit issue operations (CRUD)
date: 2010-12-19
comments: false
permalink: 2010/12/jira-lets-code-update-edit-issue.html
tags: [atlassian, jira, java]
---

If you are familiar with JIRA and it's API then you might agree, that some easy operations become a little difficult when it comes to coding  (all the workflows, overall JIRA stack understanding, configuration items, integration with other systems etc).
<div>
</div><div>The same is especially true when it comes to creating / updating JIRAs issues, which definitely is backbone for issue tracking systems. Some might argue that this type of things should be done by JIRA itself only. And I couldn't agree more. However JIRA tend to become issue-tracking puzzle-building machinery, where JIRA itself is LEGO puzzle only, so plenty of crazy stuff "you better shouldn't do this" or "you are not supposed to do that" is very popular in the JIRA plugin development world.</div><div>
</div><div>So, back to issue creation/update problem. This is kind of task I code almost in every plugin. And anyway, it bugs me every time :) It's difficult for me to remember all the nuances and it's context dependent as well. Lets see that JIRA development form says about this - <a href="http://forums.atlassian.com/search.jspa?threadID=&amp;q=create+issue&amp;objID=f100&amp;dateRange=all&amp;numResults=15&amp;rankBy=10001">create</a>, <a href="http://forums.atlassian.com/search.jspa?objID=f100&amp;q=update+issue">update</a>. Seems already solved problem, isn't it? However it takes me a plenty time to solve it out if I don't have out-the box solution in my local repository.  </div><div>
</div><div>So, this time I decided to share a little code with you, and just a reminder to myself as well (I tend to forget things all the time).</div><div>
<script src="https://gist.github.com/746976.js?file=IssueCrudOperations.java"></script>
</div>
And here comes the implementation itself:
<div><script src="https://gist.github.com/746976.js?file=IssueCrudOperationsImpl.java"></script>
</div>
