---
title: Make PageView.controller nullable
description: >-
  PageView.controller converted to be nullable.
---

## Summary

If a controller isn't provided in the constructor, the `controller` member is `null`.
This makes `PageviewController` consistent with other widgets.

## Migration guide

Before:

```dart
pageView.controller.page
```

After:

```dart
pageView.controller!.page
```

## Timeline

Landed in version: 3.19.0

## References

Relevant issues:

* [PageView uses global controller, that is never disposed. (Issue 141119)][]

[PageView uses global controller, that is never disposed. (Issue 141119)]: {{site.repo.flutter}}/issues/141119
