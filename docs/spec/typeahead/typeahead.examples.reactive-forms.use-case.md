16.7: Typeahead Reactive forms example
=============================================
**Primary Actor**: User

**Scope**: Ngx-bootstrap DEMO / BS version 3&4

**Goal**: Show user how typeahead can be used in reactive forms

Main success scenario:
----------------------
1. User open Typeahead demo page
2. User clicks on Reactive forms sub-menu
3. User sees typeahead input and typeahead card with "Model:" text and it's filled with "null". The input has a placeholder "Typeahead inside a form"
4. When user places mouse coursor in the "Model" then a drop-down with the first seven States is shown
5. When user starts to type a name of a State from "states" array and there are no matches then the drop-down is hidden. The "Model" is filled with inputted data
6. If there are any matches found then the drop-down with a list of States matches is shown
7. Items in the drop-down are clickable
8. When user clicks on any item in typeahead drop-down, then typeahead container auto-fills with a selected State

Variations:
-----------
2*. User scrolls to Reactive forms sub-menu
