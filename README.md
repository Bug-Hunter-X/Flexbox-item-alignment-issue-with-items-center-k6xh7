# Tailwind CSS Flexbox Alignment Bug

This repository demonstrates a common issue encountered when using Tailwind CSS's flexbox utilities, specifically with the `items-center` class. The problem arises when trying to vertically align items within a flex container, where the items have different heights.

## Bug Description

The `items-center` class is intended to vertically center items in a flex container. However, when one item is significantly taller than another (e.g., a button and a paragraph), the `items-center` class may not align them perfectly in the center. The taller element might push the shorter one away from the center.

## Solution

The solution involves using the `flex` and `items-center` classes in conjunction with an appropriate height for the parent flex container or for the children.   One can also use the `h-[value]` utility class to assign height to the children.