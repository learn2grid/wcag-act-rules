---
title: Explicit semantic role
---

The _explicit semantic role_ is the [semantic role][] of an element set by its [role attribute](https://www.w3.org/TR/role-attribute/).

The [role attribute](https://www.w3.org/TR/role-attribute/) takes a list of tokens. The explicit semantic role is the first valid role in this list. If none of the tokens are valid, the [implicit semantic role](#implicit-role) will be used instead. The valid roles are all non-abstract roles from [WAI-ARIA Specifications](#wai-aria-specifications).

Other roles may be added as they become available. Not all roles will be supported in all assistive technologies. Testers are encouraged to adjust which roles are allowed according to the [accessibility support base line](https://www.w3.org/TR/WCAG-EM/#step1c). For the purposes of executing test cases in all rules, it should be assumed that all roles are supported by assistive technologies so that none of the roles fail due to lack of accessibility support.

[semantic role]: #semantic-role