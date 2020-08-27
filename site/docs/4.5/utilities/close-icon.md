---
layout: docs
title: 关闭图标
description: Use a generic close icon for dismissing content like modals and alerts.
group: utilities
---

**Be sure to include text for screen readers**, as we've done with `aria-label`.

{% capture example %}
<button type="button" class="close" aria-label="Close">
  <span aria-hidden="true">&times;</span>
</button>
{% endcapture %}
{% include example.html content=example %}
