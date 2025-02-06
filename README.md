# Uncommon HTML Bug: Initial Display State

This repository demonstrates a subtle bug related to the initial display state of an HTML element when using JavaScript to control its visibility.  The `div` element is expected to be hidden initially, but it isn't.  The solution file offers a fix for this problem, highlighting best practices.

## Bug Description

The `bug.html` file shows a `div` element.  A JavaScript function `showHide` is intended to toggle its visibility.  However, the `div` is initially visible even though no explicit styling sets `display` to `block`.  This can be confusing and lead to unexpected behavior.

## Solution

The `solution.html` file demonstrates a corrected version.  The solution involves explicitly setting the `display` property to `none` in the CSS or using a class to hide it initially.