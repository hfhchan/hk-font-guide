# HK Font Guide

Guide for designing glyphs in the _modern-style_ Sung or Hei typefaces for the Hong Kong market.

## Background

There are two main reference documents for character glyphs in Hong Kong.

- 香港小學學習字詞表  
  This is produced by the Education Bureau and distributed to primary and secondary schools.  
  The glyphs provided are in the Kai typeface.  
  See: https://www.edbchinese.hk/lexlist_ch/

- Reference Glyphs for Chinese Computer Systems in Hong Kong  
  This is published by the Office of the Government Chief Information Officer.  
  The glyphs provided are in the Kai typeface and Song typeface.  
  See: https://www.ccli.gov.hk/en/download/reference_glyphs.html

These documents are prepared by the respective government agencies as a reference only. They differ
in various aspects to commerically produced fonts.

As noted on the page for the reference glyphs produced by OGCIO:

> Please note that it is not the intention of the document to set standards for characters commonly
> used in Hong Kong, or to impose any restrictions on the styles adopted by font developers.

Commerical fonts are widely used in advertising and publishing. Government brochures and promotional
materials use off-the-shelf commerical fonts which contain glyphs which differ from the reference
materials. Commerical fonts are also widely used in newspapers.  Commerical fonts are also often used
in textbooks. Not a lot of textbooks actually use the "standards compliant" fonts. The forms found in
commerical fonts are actually the forms that most people are familiar with, not the reference glyphs
provided by the government.

When designing fonts for the Hong Kong market or greater Traditional Chinese market, font developers
need to use their own judgement to design the glyphs to use appropriate forms.

This repository aims to provide a general guide for producing fonts which are most suited to the Hong
Kong market. This document is written in reference to the norms of Simplified Chinese font production.

## Stroke Style

There are two main styles of glyphs which are used in commerical fonts, the _traditional-style_ and
_modern-style_. The most popular commerical fonts used in Hong Kong are in _modern-style_.

Even though they are _modern-style_ fonts, the bulk of these fonts use the traditional split-stroke
hook and the split-stroke corner stroke instead of the joined hook and joined corner stroke commonly
seen in GB-compliant fonts produced for mainland China.

Always use the traditional split-stroke hook and split-stroke corner. It is widely accepted and superior
in terms of aesthetics and legibility.

## Avoidance of strokes

In the reference guides, the avoidance of strokes (避讓) is applied extremely broadly. Characters on the
top with a 捺 stroke needs to be changed to a 點 stroke even if the character on the bottom does not
have a 捺 stroke, e.g. 香 has a 點 stroke instead of a 捺 stroke. The reverse is also true, e.g. the 矢
in 挨 has a 點 stroke instead of 捺 stroke. For some cases like 央, the 捺 stroke is even changed when it is
on the right.

Commerically produced fonts do not follow these avoidance of strokes. They may either follow the
GB-compliant forms where the 捺 stroke is changed only in cases to ensure that only one 捺 stroke is present
in each character, or keep 捺 strokes as they are.

Either are fine. Do not apply the avoidance of strokes simply because the character is on the top or bottom.

Avoid the stroke when the character is on the left e.g. the 文 inside 斑. Exception: the 捺 of 瓜 in 瓣 is
usually kept unchanged in commercial fonts.

Avoid the stroke when the character is inside a enclosure component may sometimes not be applied especially
in extra bold fonts, e.g. 各 inside 閣.

## Balance

Most Sung typefaces produced for the Traditional Chinese market prefer narrower 中宮 than mainstream
typefaces produced for the Simplified Chinese market. It is nearly obviously recognizable which fonts
are produced for the Simplified Chinese market and which fonts are produced for the Traditional Chinese
market instantly based on the 中宮.

Most Hei typefaces also use thicker strokes compared to those for the Simplified Chinese market for
more complex characters, leading to a visually more consistent vertical stroke length but higher
variability in overall "grayness". Do not over thin the vertical strokes for better "grayness".
There is supposed to be a contrast between characters with a few strokes and characters with a lot of
strokes.

## Components and Structure

Some characters use different components and/or structure compared to the GB-compliant forms. A small
subset of high frequency characters have different components / structure according to the reference
guides, but the GB-compliant forms are actually the most common and widely accepted, e.g. 七, 也, 感.
Refer to the respective .md files for more details.
