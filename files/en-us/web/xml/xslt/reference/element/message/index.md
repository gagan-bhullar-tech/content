---
title: <xsl:message>
slug: Web/XML/XSLT/Reference/Element/message
page-type: xslt-element
sidebar: xmlsidebar
---

The `<xsl:message>` element outputs a message (to the JavaScript Console in NS) and optionally terminates execution of the stylesheet. It can be useful for debugging.

## Syntax

```xml
<xsl:message terminate="yes" | "no" >
  TEMPLATE
</xsl:message>
```

### Required Attributes

None.

### Optional Attributes

- `terminate`
  - : Set to `yes`, indicates that execution should be terminated. The default value is `no`, in which case the message is output and execution continues.

### Type

Instruction, appears within a template.

## Specifications

XSLT, section 13.

## Gecko support

Supported.
