---
layout: post
title: "Character"
---

<div style="max-width: 700px; margin: 0 auto; font-family: sans-serif;">

  <div style="color: #444; line-height: 1.6; border-left: 3px solid #333; padding-left: 15px;">
    <strong>A Thought:</strong>
    
    <p style="margin-top: 10px;">
      Twice now, Claude has dropped in Chinese words in place of English words at points without a super obvious connection. I heard there was a <a href="https://www.anthropic.com/engineering/a-postmortem-of-three-recent-issues" style="color: #2a7ae2; text-decoration: none; border-bottom: 1px dotted #2a7ae2;">bug fix in recent months for this</a>, but it just happened again today.
    </p>

    <p>
      In the first case, I was discussing the difference between true astronauts and space tourists, and Claude said "航空 travel" instead of "air travel". In the second case, today, we were discussing support vs product roles, and it used "純 support" instead of "pure support".
    </p>

    <p>Anthropic said of the earlier bug:</p>

    <blockquote style="background: #f5f5f5; padding: 15px; border-radius: 6px; font-style: italic; margin: 20px 0; color: #555; border-left: 4px solid #ccc;">
      "An issue caused by a runtime performance optimization occasionally assigned a high probability to tokens that should rarely be produced given the context, for example producing Thai or Chinese characters in response to English prompts, or producing obvious syntax errors in code. A small subset of users that asked a question in English might have seen 'สวัสดี' in the middle of the response, for example."
    </blockquote>

    <p style="margin-bottom: 0;">
      What fascinates me is that there are multiple levels of error explanation to be had here. Why an error at all? Why Chinese? Why those specific words? So much to unpack.
    </p>
  </div>

</div>