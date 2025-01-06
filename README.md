# React Native FlatList Inconsistent Key Issue

This repository demonstrates a common error in React Native's FlatList component: using inconsistent or missing keys for list items.  Using the index as a key is a frequent mistake that can cause unpredictable behavior, particularly when items are inserted, removed, or reordered.

## Problem
Incorrect rendering and performance issues may occur if keys are duplicated or missing. Items may appear in the wrong order, disappear, or the list may fail to update correctly.

## Solution
Use a unique identifier from each item in your data array as the key. This could be a database ID, a UUID, or any other unique property. Avoid using the index.