# Mini-Project: Mood Board

## Description
This dynamic mood board appliation helps users compile images using the image URL and allows users to add text of their choice. Once images and texts have been added, users may drag the content as they please to place their inspirations as needed. 

## Table of Contents
  * [Description](#description)
  * [User Story](#user-story)
  * [Specifications](#specifications)


## User Story

The completed application should meet the following criteria:

* As a user, I want to add an image of my choice using a URL.

  * For example:

  ```md
  https://static.bc-edx.com/coding/full-stack/04-Web-APIs/assets/100-m4-mini.png
  ```

* As a user, I want to drop that image into the mood board.

* As a user, I want to add some text to the mood board.

* As a user, I want drag that text into the mood board.

* As a user, I want to see the image or text being dragged as I move it into the mood board.

* As a user, I want my mood board to be saved in local storage.

## Specifications

* When a user pastes an image URL into the input field and clicks the "Add Image" button, the image should be draggable.

* When a user clicks a draggable element on to the mood board, the element should be appended to the mood board in the position of the mouse.

* When a user enters text into the input field and clicks the "Add Text" button, the text should be draggable.

* When a user clicks the draggable element on to the mood board, the element should be appended to the mood board in the position of the mouse.

* When a user refreshes or returns to the browser page, the mood board should persist.

* When a user clicks the "Clear All" button, the mood board should be cleared and the local storage should be cleared.

## 💡 Notes

Refer to the documentation:

* [MDN Web Docs on addEventListener()](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener)

* [MDN Web Docs on Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)

* [MDN Web Docs on loops and iteration](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)

* [MDN Web Docs on MouseEvent](https://developer.mozilla.org/en-US/docs/Web/API/MouseEvent)

* [MDN Web Docs on getBoundingClientRect()](https://developer.mozilla.org/en-US/docs/Web/API/Element/getBoundingClientRect)

* [MDN Web Docs on localStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)


---

© 2024 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
