---
-api-id: M:Windows.Data.Text.UnicodeCharacters.IsHighSurrogate(System.UInt32)
-api-type: winrt method
-api-device-family-note: xbox
---

<!-- Method syntax
public bool IsHighSurrogate(System.UInt32 codepoint)
-->

# Windows.Data.Text.UnicodeCharacters.IsHighSurrogate

## -description
Determines if a specified Unicode character is a high surrogate.

## -parameters
### -param codepoint
A Unicode character. This must be in the proper range: 0 &lt;= *codepoint* &lt;= 0x10FFFF.

## -returns
**TRUE** if *codepoint* is a high surrogate; otherwise **FALSE**.

## -remarks


## -examples

## -see-also
[GetCodepointFromSurrogatePair](unicodecharacters_getcodepointfromsurrogatepair_1886831018.md), [Surrogates and Supplementary Characters](http://msdn.microsoft.com/library/0dea39e2-a2b4-47fc-b44a-56af8ba1e346)